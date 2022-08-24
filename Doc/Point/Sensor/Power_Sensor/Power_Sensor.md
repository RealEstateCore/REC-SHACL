[Index](../../../Index.md) > [Point](../../Point.md) > [Sensor](../Sensor.md) > [Power_Sensor](#)
# Power_Sensor

**Display name:** Power Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Power_Sensor;1

---

## Child interfaces
* [Electric_Power_Sensor](Electric_Power_Sensor/Electric_Power_Sensor.md)
* [Thermal_Power_Sensor](Thermal_Power_Sensor/Thermal_Power_Sensor.md)

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
