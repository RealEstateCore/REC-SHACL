[Point](../../Point.md) > [Status](../Status.md) > [Filter_Status](#)
# Filter_Status

**Display name:** Filter Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Filter_Status;1

---

## Child interfaces
* [Pre_Filter_Status](Pre_Filter_Status.md)

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
