[Asset](../../../Asset.md) > [Equipment](../../Equipment.md) > [Valve](../Valve.md) > [Water_Valve](Water_Valve.md) > [Condenser_Water_Valve](#)
# Condenser_Water_Valve

**Display name:** Condenser Water Valve<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Condenser_Water_Valve;1

---

## Relationships
### Inherited Relationships
* **[Equipment](../../Equipment.md):** feeds, isFedBy
* **[Asset](../../../Asset.md):** commissionedBy, documentation, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Equipment](../../Equipment.md):** operationalStageCount
* **[Asset](../../../Asset.md):** assetTag, commissioningDate, customTags, externalIds, geometry, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight

---

## Target Of
### Inherited
* [Asset](../../../Asset.md).hasPart
* [Asset](../../../Asset.md).isPartOf
* [EquipmentCollection](../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).includes
