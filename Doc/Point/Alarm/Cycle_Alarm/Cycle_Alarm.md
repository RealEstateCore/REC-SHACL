[Point](../../Point.md) > [Alarm](../Alarm.md) > [Cycle_Alarm](#)
# Cycle_Alarm

**Display name:** Cycle Alarm<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Cycle_Alarm;1

---


## Child interfaces
* [Short_Cycle_Alarm](Short_Cycle_Alarm.md)

---
## Relationships
### Inherited Relationships
* **[Point](../../Point.md):** isPointOf
## Properties
### Inherited Properties
* **[Point](../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name
## Target Of
### Inherited
* [Asset](../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../Space/Architecture/Architecture.md).hasPoint
