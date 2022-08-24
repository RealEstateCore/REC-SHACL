[Asset](../../../Asset.md) > [Equipment](../../Equipment.md) > [Security_Equipment](../Security_Equipment.md) > [Intercom_Equipment](#)
# Intercom_Equipment

**Display name:** Intercom Equipment<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Intercom_Equipment;1

---

## Child interfaces
* [Emergency_Phone](Emergency_Phone.md)
* [Video_Intercom](Video_Intercom.md)

---

## Relationships
### Inherited Relationships
* **[Equipment](../../Equipment.md):** feeds, isFedBy
* **[Asset](../../../Asset.md):** commissionedBy, documentation, hasPart, hasPoint, installedBy, isPartOf, locatedIn, manufacturedBy, mountedOn, servicedBy

---

## Properties
### Inherited Properties
* **[Equipment](../../Equipment.md):** operationalStageCount
* **[Asset](../../../Asset.md):** assetTag, commissioningDate, customTags, externalIds, geometry, initialCost, installationDate, IPAddress, MACAddress, maintenanceInterval, modelNumber, name, serialNumber, turnoverDate, weight

---

## Target Of
### Inherited
* [Asset](../../../Asset.md).hasPart
* [Asset](../../../Asset.md).isPartOf
* [EquipmentCollection](../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).includes
