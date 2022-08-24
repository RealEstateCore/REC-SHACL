[Collection](#)
# Collection

An administrative grouping of entities that are adressed and treated as a unit for some purpose. These entities may have some spatial arrangement (e.g., an apartment is typically contiguous) but that is not a requirement (see, e.g., a distributed campus consisting of spatially disjoint plots or buildings). Inclusion in a Collection is determined by the 'includes' field on a specific subclass.


**Display name:** Collection<br />
**DTMI:** dtmi:org:w3id:rec:Collection;1

---


## Child interfaces
* [Portfolio](Portfolio.md)
* [AssetCollection](AssetCollection/AssetCollection.md)
* [SpaceCollection](SpaceCollection/SpaceCollection.md)

---
## Relationships
|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|documentation|**en**: documentation||0-Infinity|[Document](../Information/Document/Document.md)||True|
## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|customTags|**en**: Custom Tags||map (string->boolean)|True|
|externalIds|**en**: External IDs||map (string->string)|True|
|name|**en**: name||string|True|
## Target Of
