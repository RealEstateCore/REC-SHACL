[Point](../../../Point.md) > [Status](../../Status.md) > [Mode_Status](../Mode_Status.md) > [Heating_Mode_Status](#)
# Heating_Mode_Status

**Display name:** Heating Mode Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Heating_Mode_Status;1

---


## Child interfaces
* [Occupied_Heating_Mode_Status](../Occupied_Mode_Status/Occupied_Heating_Mode_Status.md)
* [Unoccupied_Heating_Mode_Status](../Unoccupied_Mode_Status/Unoccupied_Heating_Mode_Status.md)

---
## Relationships
### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf
## Properties
### Inherited Properties
* **[Point](../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name
## Target Of
### Inherited
* [Asset](../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../Space/Architecture/Architecture.md).hasPoint
