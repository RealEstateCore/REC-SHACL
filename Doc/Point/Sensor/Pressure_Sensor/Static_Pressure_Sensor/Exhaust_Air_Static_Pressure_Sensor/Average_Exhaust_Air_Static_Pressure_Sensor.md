[Index](../../../../../Index.md) > [Point](../../../../Point.md) > [Sensor](../../../Sensor.md) > [Pressure_Sensor](../../Pressure_Sensor.md) > [Static_Pressure_Sensor](../Static_Pressure_Sensor.md) > [Exhaust_Air_Static_Pressure_Sensor](Exhaust_Air_Static_Pressure_Sensor.md) > [Average_Exhaust_Air_Static_Pressure_Sensor](#)
# Average_Exhaust_Air_Static_Pressure_Sensor

**Display name:** Average Exhaust Air Static Pressure Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Average_Exhaust_Air_Static_Pressure_Sensor;1

---

## Relationships
### Inherited Relationships
* **[Point](../../../../Point.md):** isPointOf

---

## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Point](../../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name

---

## Target Of
### Inherited
* [Asset](../../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../../Space/Architecture/Architecture.md).hasPoint
