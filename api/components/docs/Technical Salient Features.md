### Technical Salient Features

- For settle API, the context.bap_id is the subscriber id of the NP calling the settle API, irrespective of buyer app or seller app
- As many number of orders can be shared as required in the settle API call. However, there would be an upper cap that would be defined by the settlement agency.
- Recon API is a bidirectional API that is used to reconcile orderbooks on both side. This is settlement agnostic and can be called before or after the settlement instructions are shared.
- For recon API, the context.bap_id and the bpp_id would be the same as the core order transaction irrespective of whoever is calling the recon API
- As many number of orders can be shared as required in the recon API call as required.
- The order may be divided into multiple part settlements hence the recon API has settlements as an array and this is domain dependent. Most domains support single full settlement only for now.
- Calculation of commission, tcs, tds is domain and use case specific, please consult your legal/ finance teams on its application based on the transaction
