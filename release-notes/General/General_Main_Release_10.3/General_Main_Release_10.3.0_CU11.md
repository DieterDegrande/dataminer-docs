---
uid: General_Main_Release_10.3.0_CU11
---

# General Main Release 10.3.0 CU11 – Preview

> [!IMPORTANT]
> We are still working on this release. Some release notes may still be modified or moved to a later release. Check back soon for updates!

> [!TIP]
> For information on how to upgrade DataMiner, see [Upgrading a DataMiner Agent](xref:Upgrading_a_DataMiner_Agent).

### Enhancements

*No enhancements have been added to this release yet.*

### Fixes

#### GQI: 'Could not find PK column' error after performing a query against an empty parameter table [ID_37978]

<!-- MR 10.3.0 [CU11] - FR 10.4.1 -->

Up to now, in some rare cases, performing a GQI query against an empty parameter table would result in a `Could not find PK column` error. From now on, GQI will return an empty result set instead.
