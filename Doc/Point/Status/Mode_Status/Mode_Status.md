[Point](../../Point.md) > [Status](../Status.md) > [Mode_Status](#)
# Mode_Status

**Display name:** Mode Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Mode_Status;1

---

## Child interfaces
* [Speed_Mode_Status](../Speed_Status/Speed_Mode_Status.md)
* [Zone_Air_Conditioning_Mode_Status](Zone_Air_Conditioning_Mode_Status.md)
* [Cooling_Mode_Status](Cooling_Mode_Status/Cooling_Mode_Status.md)
* [Heating_Mode_Status](Heating_Mode_Status/Heating_Mode_Status.md)
* [Occupied_Mode_Status](Occupied_Mode_Status/Occupied_Mode_Status.md)
* [Operating_Mode_Status](Operating_Mode_Status/Operating_Mode_Status.md)
* [Unoccupied_Mode_Status](Unoccupied_Mode_Status/Unoccupied_Mode_Status.md)

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
