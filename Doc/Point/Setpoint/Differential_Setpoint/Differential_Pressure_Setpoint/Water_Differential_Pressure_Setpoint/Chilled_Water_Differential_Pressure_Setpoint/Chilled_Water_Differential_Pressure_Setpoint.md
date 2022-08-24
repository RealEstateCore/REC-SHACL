[Point](../../../../../Point.md) > [Setpoint](../../../../Setpoint.md) > [Differential_Setpoint](../../../Differential_Setpoint.md) > [Differential_Pressure_Setpoint](../../Differential_Pressure_Setpoint.md) > [Water_Differential_Pressure_Setpoint](../Water_Differential_Pressure_Setpoint.md) > [Chilled_Water_Differential_Pressure_Setpoint](#)
# Chilled_Water_Differential_Pressure_Setpoint

**Display name:** Chilled Water Differential Pressure Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Chilled_Water_Differential_Pressure_Setpoint;1

---

## Child interfaces
* [Chilled_Water_Differential_Pressure_Load_Shed_Setpoint](Chilled_Water_Differential_Pressure_Load_Shed_Setpoint.md)

---

## Relationships
### Inherited Relationships
* **[Point](../../../../../Point.md):** isPointOf

---

## Properties
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
