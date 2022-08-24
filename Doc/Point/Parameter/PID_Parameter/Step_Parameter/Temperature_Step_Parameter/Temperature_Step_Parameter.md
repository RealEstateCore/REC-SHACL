[Point](../../../../Point.md) > [Parameter](../../../Parameter.md) > [PID_Parameter](../../PID_Parameter.md) > [Step_Parameter](../Step_Parameter.md) > [Temperature_Step_Parameter](#)
# Temperature_Step_Parameter

**Display name:** Temperature Step Parameter<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Temperature_Step_Parameter;1

---


## Child interfaces
* [Air_Temperature_Step_Parameter](Air_Temperature_Step_Parameter/Air_Temperature_Step_Parameter.md)

---
## Relationships
### Inherited Relationships
* **[Point](../../../../Point.md):** isPointOf
## Properties
### Inherited Properties
* **[Point](../../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name
## Target Of
### Inherited
* [Asset](../../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../../Space/Architecture/Architecture.md).hasPoint
