### Technical Salient Features

- Both Flow 1 & Flow 2 as identified in the Developer Guide are to be implemented in order to completely implement the IGM 2.0 framework. That is, NP is expected to develop as well as consume all 4 APIs
- While Flow 1 and Flow 2 generally cover the overall flow of complaints on the network, varied complaints respective to the kind of complaint and the domain will have their respective operational flows and their respective resolutions
- Any new action/ update taking place on the complaint will be done through either issue/ on_issue APIs
- The issue_status and on_issue_status APIs act as a current status of the complaint check and are therefore not explicitly - called out in the Flow illustrations, but are to be implemented
- 'context’ object remains the same as the ‘context’ of the core transaction. That is, for example, location object in the context is used for use cases with the 2.x core protocol version, while country/ city codes are used for use cases with the 1.x core protocol version. Same for version attribute, 1.2.0 for RET10, while 2.0.1 for TRV10.