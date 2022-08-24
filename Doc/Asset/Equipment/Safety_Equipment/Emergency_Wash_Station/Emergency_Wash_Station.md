[Asset](../../../Asset.md) > [Equipment](../../Equipment.md) > [Safety_Equipment](../Safety_Equipment.md) > [Emergency_Wash_Station](#)
# Emergency_Wash_Station

**Display name:** Emergency Wash Station<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Emergency_Wash_Station;1

---


## Child interfaces
* [Drench_Hose](Drench_Hose.md)
* [Eye_Wash_Station](Eye_Wash_Station.md)
* [Safety_Shower](Safety_Shower.md)

---
## Relationships
### Inherited Relationships
* **[Equipment](../../Equipment.md):** feeds, isFedBy
* **[Asset](../../../Asset.md):** commissionedBy, documentation, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy
## Properties
### Inherited Properties
* **[Equipment](../../Equipment.md):** operationalStageCount
* **[Asset](../../../Asset.md):** assetTag, commissioningDate, customTags, externalIds, geometry, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight
## Target Of
### Inherited
* [Asset](../../../Asset.md).hasPart
* [Asset](../../../Asset.md).isPartOf
* [EquipmentCollection](../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).includes
