---
layout: bidder
title: TripleLift Native
description: Prebid TripleLift Native Bidder Adapter
biddercode: triplelift_native
gdpr_supported: true
tcf2_supported: true
usp_supported: true
coppa_supported: true
schain_supported: true
floors_supported: true
media_types: native
userIds: criteo, identityLink, unifiedId
prebid_member: true
safeframes_ok: true
deals_supported: true
pbjs: true
pbs: true
pbs_app_supported: true
fpd_supported: true
gvl_id: 28
sidebarType: 1
---

{: .alert.alert-info :}
The Triplelift Prebid Server bidding adapter and user sync endpoint require setup before beginning. Please contact us at prebid@triplelift.com.

This is a Prebid Server adapter for running component native only. For the standard Prebid JS Triplelift bid adapter, see the "Triplelift" bidder.

### Table of Contents

- [Table of Contents](#table-of-contents)
- [Bid Params](#bid-params)
- [First Party Data](#first-party-data)

<a name="triplelift-bid-params" />

### Bid Params

{: .table .table-bordered .table-striped }
| Name       | Scope    | Description            | Example | Type     |
|------------|----------|------------------------|---------|----------|
| inventoryCode | required | TripleLift inventory code for this ad unit (provided to you by your partner manager) | 'code1' | string |
| floor | optional | the bid floor, in usd | 1.2 | number |

<a name="triplelift-first-party" />

### First Party Data

Triplelift supports standard IAB OpenRTB 2.5 First Party Data fields, including:
- `site.*`
- `user.*`
