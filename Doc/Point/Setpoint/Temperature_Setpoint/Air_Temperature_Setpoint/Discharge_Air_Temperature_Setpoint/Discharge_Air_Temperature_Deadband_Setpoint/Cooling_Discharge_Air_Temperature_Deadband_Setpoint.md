[Point](../../../../../Point.md) > [Setpoint](../../../../Setpoint.md) > [Temperature_Setpoint](../../../Temperature_Setpoint.md) > [Air_Temperature_Setpoint](../../Air_Temperature_Setpoint.md) > [Discharge_Air_Temperature_Setpoint](../Discharge_Air_Temperature_Setpoint.md) > [Discharge_Air_Temperature_Deadband_Setpoint](Discharge_Air_Temperature_Deadband_Setpoint.md) > [Cooling_Discharge_Air_Temperature_Deadband_Setpoint](#)
# Cooling_Discharge_Air_Temperature_Deadband_Setpoint

**Display name:** Cooling Discharge Air Temperature Deadband Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Cooling_Discharge_Air_Temperature_Deadband_Setpoint;1

---

## Relationships
### Inherited Relationships
* **[Point](../../../../../Point.md):** isPointOf

---

## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Point](../../../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name

---

## Target Of
### Inherited
* [Asset](../../../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../../../Space/Architecture/Architecture.md).hasPoint
