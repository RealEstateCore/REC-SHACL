[Point](../../../../Point.md) > [Parameter](../../../Parameter.md) > [PID_Parameter](../../PID_Parameter.md) > [Gain_Parameter](../Gain_Parameter.md) > [Integral_Gain_Parameter](#)
# Integral_Gain_Parameter

**Display name:** Integral Gain Parameter<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Integral_Gain_Parameter;1

---

## Child interfaces
* [Discharge_Air_Integral_Gain_Parameter](Discharge_Air_Integral_Gain_Parameter.md)
* [Supply_Air_Integral_Gain_Parameter](Supply_Air_Integral_Gain_Parameter.md)

---

## Relationships
### Inherited Relationships
* **[Point](../../../../Point.md):** isPointOf

---

## Properties
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
