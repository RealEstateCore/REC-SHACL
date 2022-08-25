[Index](../../../Index.md) > [Point](../../Point.md) > [Sensor](../Sensor.md) > [Adjust_Sensor](#)
# Adjust_Sensor

**Display name:** Adjust Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Adjust_Sensor;1

---

## Child interfaces
* [Temperature_Adjust_Sensor](Temperature_Adjust_Sensor.md)
* [Warm_Cool_Adjust_Sensor](Warm_Cool_Adjust_Sensor.md)

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
