[Index](../../../Index.md) > [Point](../../Point.md) > [Alarm](../Alarm.md) > [Smoke_Alarm](#)
# Smoke_Alarm

**Display name:** Smoke Alarm<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Smoke_Alarm;1

---

## Child interfaces
* [Smoke_Detection_Alarm](Smoke_Detection_Alarm/Smoke_Detection_Alarm.md)

---

## Relationships
### Inherited Relationships
* **[Point](../../Point.md):** isPointOf

---

## Properties
### Inherited Properties
* **[Point](../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name

---

## Target Of
### Inherited
* [Asset](../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../Space/Architecture/Architecture.md).hasPoint
