[Point](../../../Point.md) > [Setpoint](../../Setpoint.md) > [Load_Setpoint](../Load_Setpoint.md) > [Load_Shed_Setpoint](Load_Shed_Setpoint.md) > [Leaving_Medium_Temperature_Hot_Water_Temperature_Load_Shed_Setpoint](#)
# Leaving_Medium_Temperature_Hot_Water_Temperature_Load_Shed_Setpoint

**Display name:** Leaving Medium Temperature Hot Water Temperature Load Shed Setpo<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Leaving_Medium_Temperature_Hot_Water_Temperature_Load_Shed_Setpoint;1

---

## Relationships
### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf

---

## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Point](../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name

---

## Target Of
### Inherited
* [Asset](../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../Space/Architecture/Architecture.md).hasPoint
