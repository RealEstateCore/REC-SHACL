[Point](../../../Point.md) > [Setpoint](../../Setpoint.md) > [Differential_Setpoint](../Differential_Setpoint.md) > [Differential_Pressure_Deadband_Setpoint](Differential_Pressure_Deadband_Setpoint.md) > [Entering_Water_Differential_Pressure_Deadband_Setpoint](#)
# Entering_Water_Differential_Pressure_Deadband_Setpoint

**Display name:** Entering Water Differential Pressure Deadband Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Entering_Water_Differential_Pressure_Deadband_Setpoint;1

---
## Relationships
### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf
## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
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
