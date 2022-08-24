[Index](../../../Index.md) > [Point](../../Point.md) > [Status](../Status.md) > [Pressure_Status](#)
# Pressure_Status

**Display name:** Pressure Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Pressure_Status;1

---

## Child interfaces
* [Discharge_Air_Duct_Pressure_Status](Discharge_Air_Duct_Pressure_Status.md)
* [Supply_Air_Duct_Pressure_Status](Supply_Air_Duct_Pressure_Status.md)
* [Differential_Pressure_Load_Shed_Status](Differential_Pressure_Load_Shed_Status/Differential_Pressure_Load_Shed_Status.md)

---

## Relationships
### Inherited Relationships
* **[Point](../../Point.md):** isPointOf

---

## Properties
### Inherited Properties
* **[Point](../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name

---

## Target Of
### Inherited
* [Asset](../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../Space/Architecture/Architecture.md).hasPoint
