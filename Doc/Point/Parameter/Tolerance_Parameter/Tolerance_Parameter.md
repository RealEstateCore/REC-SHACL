[Index](../../../Index.md) > [Point](../../Point.md) > [Parameter](../Parameter.md) > [Tolerance_Parameter](#)
# Tolerance_Parameter

**Display name:** Tolerance Parameter<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Tolerance_Parameter;1

---

## Child interfaces
* [Humidity_Tolerance_Parameter](Humidity_Tolerance_Parameter.md)
* [Temperature_Tolerance_Parameter](Temperature_Tolerance_Parameter.md)

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
