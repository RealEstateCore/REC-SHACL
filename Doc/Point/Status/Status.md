[Index](../../Index.md) > [Point](../Point.md) > [Status](#)
# Status

**Display name:** Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Status;1

---

## Child interfaces
* [Availability_Status](Availability_Status.md)
* [Disable_Status](Disable_Status.md)
* [Drive_Ready_Status](Drive_Ready_Status.md)
* [Emergency_Generator_Status](Emergency_Generator_Status.md)
* [Emergency_Push_Button_Status](Emergency_Push_Button_Status.md)
* [Even_Month_Status](Even_Month_Status.md)
* [Freeze_Status](Freeze_Status.md)
* [Hold_Status](Hold_Status.md)
* [Lead_Lag_Status](Lead_Lag_Status.md)
* [Lockout_Status](Lockout_Status.md)
* [Manual_Auto_Status](Manual_Auto_Status.md)
* [Open_Close_Status](Open_Close_Status.md)
* [Pump_Status](Pump_Status.md)
* [Stages_Status](Stages_Status.md)
* [Switch_Status](Switch_Status.md)
* [Thermostat_Status](Thermostat_Status.md)
* [Tint_Status](Tint_Status.md)
* [Valve_Status](Valve_Status.md)
* [Direction_Status](Direction_Status/Direction_Status.md)
* [Enable_Status](Enable_Status/Enable_Status.md)
* [Fan_Status](Fan_Status/Fan_Status.md)
* [Fault_Status](Fault_Status/Fault_Status.md)
* [Filter_Status](Filter_Status/Filter_Status.md)
* [Load_Shed_Status](Load_Shed_Status/Load_Shed_Status.md)
* [Mode_Status](Mode_Status/Mode_Status.md)
* [Occupancy_Status](Occupancy_Status/Occupancy_Status.md)
* [Off_Status](Off_Status/Off_Status.md)
* [On_Status](On_Status/On_Status.md)
* [Overridden_Status](Overridden_Status/Overridden_Status.md)
* [Pressure_Status](Pressure_Status/Pressure_Status.md)
* [Speed_Status](Speed_Status/Speed_Status.md)
* [System_Shutdown_Status](System_Status/System_Shutdown_Status.md)
* [System_Status](System_Status/System_Status.md)

---

## Relationships
### Inherited Relationships
* **[Point](../Point.md):** isPointOf

---

## Properties
### Inherited Properties
* **[Point](../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name

---

## Target Of
### Inherited
* [Asset](../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../Space/Architecture/Architecture.md).hasPoint
