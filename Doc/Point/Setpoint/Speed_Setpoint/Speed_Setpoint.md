[Index](../../../Index.md) > [Point](../../Point.md) > [Setpoint](../Setpoint.md) > [Speed_Setpoint](#)
# Speed_Setpoint

**Display name:** Speed Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Speed_Setpoint;1

---

## Child interfaces
* [Rated_Speed_Setpoint](Rated_Speed_Setpoint.md)

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
