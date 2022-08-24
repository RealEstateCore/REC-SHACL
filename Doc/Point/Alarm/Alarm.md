[Point](../Point.md) > [Alarm](.)
# Alarm

**Display name:** Alarm<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Alarm;1

---


## Child interfaces
* [Change_Filter_Alarm](Change_Filter_Alarm.md)
* [Communication_Loss_Alarm](Communication_Loss_Alarm.md)
* [Liquid_Detection_Alarm](Liquid_Detection_Alarm.md)
* [Low_Battery_Alarm](Low_Battery_Alarm.md)
* [Luminance_Alarm](Luminance_Alarm.md)
* [Maintenance_Required_Alarm](Maintenance_Required_Alarm.md)
* [Overload_Alarm](Overload_Alarm.md)
* [Valve_Position_Alarm](Valve_Position_Alarm.md)
* [Air_Alarm](Air_Alarm/Air_Alarm.md)
* [CO2_Alarm](CO2_Alarm/CO2_Alarm.md)
* [Cycle_Alarm](Cycle_Alarm/Cycle_Alarm.md)
* [Emergency_Alarm](Emergency_Alarm/Emergency_Alarm.md)
* [Failure_Alarm](Failure_Alarm/Failure_Alarm.md)
* [Humidity_Alarm](Humidity_Alarm/Humidity_Alarm.md)
* [Leak_Alarm](Leak_Alarm/Leak_Alarm.md)
* [Power_Alarm](Power_Alarm/Power_Alarm.md)
* [Pressure_Alarm](Pressure_Alarm/Pressure_Alarm.md)
* [Smoke_Alarm](Smoke_Alarm/Smoke_Alarm.md)
* [Temperature_Alarm](Temperature_Alarm/Temperature_Alarm.md)
* [Voltage_Alarm](Voltage_Alarm/Voltage_Alarm.md)
* [Water_Alarm](Water_Alarm/Water_Alarm.md)

---
## Relationships
### Inherited Relationships
* **dtmi:org:brickschema:schema:Brick:Point;1:** isPointOf
## Properties
### Inherited Properties
* **dtmi:org:brickschema:schema:Brick:Point;1:** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name
## Target Of
### Inherited
* Asset.hasPoint
* EquipmentCollection.hasPoint
* ActuationEvent.targetPoint
* ExceptionEvent.sourcePoint
* ObservationEvent.sourcePoint
* ServiceObject.producedBy
* Architecture.hasPoint
