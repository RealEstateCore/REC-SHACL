[Point](../../Point.md) > [Status](../Status.md) > [Off_Status](#)
# Off_Status

**Display name:** Off Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Off_Status;1

---


## Child interfaces
* [Overridden_Off_Status](../Overridden_Status/Overridden_Off_Status.md)
* [Emergency_Power_Off_System_Status](../System_Status/Emergency_Power_Off_System_Status/Emergency_Power_Off_System_Status.md)
* [On_Off_Status](../On_Status/On_Off_Status/On_Off_Status.md)

---
## Relationships
### Inherited Relationships
* **[Point](../../Point.md):** isPointOf
## Properties
### Inherited Properties
* **[Point](../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name
## Target Of
### Inherited
* [Asset](../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../Space/Architecture/Architecture.md).hasPoint
