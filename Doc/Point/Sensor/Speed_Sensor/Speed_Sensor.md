[Point](../../Point.md) > [Sensor](../Sensor.md) > [Speed_Sensor](#)
# Speed_Sensor

**Display name:** Speed Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Speed_Sensor;1

---


## Child interfaces
* [Differential_Speed_Sensor](Differential_Speed_Sensor.md)
* [Motor_Speed_Sensor](Motor_Speed_Sensor.md)
* [Wind_Speed_Sensor](Wind_Speed_Sensor.md)

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
