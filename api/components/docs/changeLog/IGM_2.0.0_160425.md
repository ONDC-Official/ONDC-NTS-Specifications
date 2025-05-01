## Change Log: IGM-2.0.0

<table>
<colgroup>
<col style="width: 63%" />
<col style="width: 36%" />
</colgroup>
<thead>
<tr class="header">
<th>Version</th>
<th>IGM_2.0.0_160425</th>
</tr>

**IGM-2.0.0**

- Updated `images` structure with url & size_type
  ```
    "images": [
      {
        "url": "http://buyerapp.com/addtional-details/img1.png",
        "size_type": "xs"
      }
    ]
  ```
- Added `message.issue.action.description.name` in attribute_ui.
- Updated `media` structure with url
  ```
    "media": [
      {
        "url": "http://buyerapp.com/addtional-details/img1.png",
      }
    ]
  ```
- Updated enums from actor_info to actors
- Synced enums for actions and actors.
- Updated, `updated_target` to `update_target`.
- Added type `COUNTERPARTY_NP_GRO` in issue/on_issue calls for Illustrative Flow 1.

  ****22nd April 2025****

- Changed description to descriptor in `actions` and `issues` to align with the core schema specification.

  ****1st May 2025****

- Added the new flow `Illustrative Flow 4 (TRV)`.
