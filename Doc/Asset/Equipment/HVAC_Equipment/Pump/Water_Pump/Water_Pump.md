[Index](../../../../../Index.md) > [Asset](../../../../Asset.md) > [Equipment](../../../Equipment.md) > [HVAC_Equipment](../../HVAC_Equipment.md) > [Pump](../Pump.md) > [Water_Pump](#)
# Water_Pump

**Display name:** Water Pump<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Water_Pump;1

---

## Child interfaces
* [Chilled_Water_Pump](Chilled_Water_Pump.md)
* [Condenser_Water_Pump](Condenser_Water_Pump.md)
* [Hot_Water_Pump](Hot_Water_Pump.md)

---

## Relationships
### Inherited Relationships
* **[Equipment](../../../Equipment.md):** feeds, isFedBy
* **[Asset](../../../../Asset.md):** commissionedBy, documentation, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties
### Inherited Properties
* **[Equipment](../../../Equipment.md):** operationalStageCount
* **[Asset](../../../../Asset.md):** assetTag, commissioningDate, customTags, externalIds, geometry, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight

---

## Target Of
### Inherited
* [Asset](../../../../Asset.md).hasPart
* [Asset](../../../../Asset.md).isPartOf
* [EquipmentCollection](../../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).includes
