[Index](../../../Index.md) > [Point](../../Point.md) > [Alarm](../Alarm.md) > [Water_Alarm](Water_Alarm.md) > [Deionized_Water_Alarm](#)
# Deionized_Water_Alarm

**Display name:** Deionized Water Alarm<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Deionized_Water_Alarm;1

---

## Relationships
### Inherited Relationships
* **[Point](../../Point.md):** isPointOf

---

## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
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
