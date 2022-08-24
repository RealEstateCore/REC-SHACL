[Point](../../../../Point.md) > [Parameter](../../../Parameter.md) > [PID_Parameter](../../PID_Parameter.md) > [Proportional_Band_Parameter](../Proportional_Band_Parameter.md) > [Exhaust_Air_Flow_Proportional_Band_Parameter](#)
# Exhaust_Air_Flow_Proportional_Band_Parameter

**Display name:** Exhaust Air Flow Proportional Band Parameter<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Exhaust_Air_Flow_Proportional_Band_Parameter;1

---


## Child interfaces
* [Exhaust_Air_Stack_Flow_Proportional_Band_Parameter](Exhaust_Air_Stack_Flow_Proportional_Band_Parameter.md)

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
