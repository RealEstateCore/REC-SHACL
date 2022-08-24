[Point](../../Point.md) > [Setpoint](../Setpoint.md) > [Differential_Setpoint](.)
# Differential_Setpoint

**Display name:** Differential Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Differential_Setpoint;1

---


## Child interfaces
* [Differential_Speed_Setpoint](Differential_Speed_Setpoint.md)
* [Medium_Temperature_Hot_Water_Differential_Pressure_Load_Shed_Setpoint](Medium_Temperature_Hot_Water_Differential_Pressure_Load_Shed_Setpoint.md)
* [Differential_Pressure_Deadband_Setpoint](Differential_Pressure_Deadband_Setpoint/Differential_Pressure_Deadband_Setpoint.md)
* [Differential_Pressure_Setpoint](Differential_Pressure_Setpoint/Differential_Pressure_Setpoint.md)
* [Differential_Temperature_Setpoint](Differential_Temperature_Setpoint/Differential_Temperature_Setpoint.md)
* [Temperature_Differential_Reset_Setpoint](Temperature_Differential_Reset_Setpoint/Temperature_Differential_Reset_Setpoint.md)

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
