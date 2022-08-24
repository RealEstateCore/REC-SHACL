[Point](../../Point.md) > [Sensor](../Sensor.md) > [Current_Sensor](#)
# Current_Sensor

**Display name:** Current Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Current_Sensor;1

---


## Child interfaces
* [Load_Current_Sensor](Load_Current_Sensor.md)
* [Motor_Current_Sensor](Motor_Current_Sensor.md)
* [Current_Output_Sensor](Current_Output_Sensor/Current_Output_Sensor.md)

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
