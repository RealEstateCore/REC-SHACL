[Point](../../Point.md) > [Alarm](../Alarm.md) > [Temperature_Alarm](#)
# Temperature_Alarm

**Display name:** Temperature Alarm<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Temperature_Alarm;1

---

## Child interfaces
* [Air_Temperature_Alarm](Air_Temperature_Alarm/Air_Temperature_Alarm.md)
* [High_Temperature_Alarm](High_Temperature_Alarm/High_Temperature_Alarm.md)
* [Low_Temperature_Alarm](Low_Temperature_Alarm/Low_Temperature_Alarm.md)
* [Water_Temperature_Alarm](../Water_Alarm/Water_Temperature_Alarm/Water_Temperature_Alarm.md)

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
