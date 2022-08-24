[Point](../../../Point.md) > [Parameter](../../Parameter.md) > [Limit](../Limit.md) > [Fresh_Air_Setpoint_Limit](#)
# Fresh_Air_Setpoint_Limit

**Display name:** Fresh Air Setpoint Limit<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Fresh_Air_Setpoint_Limit;1

---

## Child interfaces
* [Max_Fresh_Air_Setpoint_Limit](../Max_Limit/Max_Fresh_Air_Setpoint_Limit.md)
* [Min_Fresh_Air_Setpoint_Limit](../Min_Limit/Min_Fresh_Air_Setpoint_Limit.md)

---

## Relationships
### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf

---

## Properties
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
