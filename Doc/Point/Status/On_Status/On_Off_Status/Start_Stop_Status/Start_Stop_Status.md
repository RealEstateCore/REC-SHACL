[Point](../../../../Point.md) > [Status](../../../Status.md) > [On_Status](../../On_Status.md) > [On_Off_Status](../On_Off_Status.md) > [Start_Stop_Status](#)
# Start_Stop_Status

**Display name:** Start Stop Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Start_Stop_Status;1

---

## Child interfaces
* [Cooling_Start_Stop_Status](Cooling_Start_Stop_Status.md)
* [Dehumidification_Start_Stop_Status](Dehumidification_Start_Stop_Status.md)
* [EconCycle_Start_Stop_Status](EconCycle_Start_Stop_Status.md)
* [Heating_Start_Stop_Status](Heating_Start_Stop_Status.md)
* [Humidification_Start_Stop_Status](Humidification_Start_Stop_Status.md)
* [Run_Status](Run_Status/Run_Status.md)

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
