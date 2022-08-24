[Point](../../../Point.md) > [Setpoint](../../Setpoint.md) > [Temperature_Setpoint](../Temperature_Setpoint.md) > [Cooling_Temperature_Setpoint](.)
# Cooling_Temperature_Setpoint

**Display name:** Cooling Temperature Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Cooling_Temperature_Setpoint;1

---


## Child interfaces
* [Occupied_Cooling_Temperature_Deadband_Setpoint](../Temperature_Deadband_Setpoint/Occupied_Cooling_Temperature_Deadband_Setpoint.md)
* [Occupied_Cooling_Temperature_Setpoint](Occupied_Cooling_Temperature_Setpoint.md)
* [Unoccupied_Cooling_Temperature_Deadband_Setpoint](../Temperature_Deadband_Setpoint/Unoccupied_Cooling_Temperature_Deadband_Setpoint.md)
* [Unoccupied_Cooling_Temperature_Setpoint](Unoccupied_Cooling_Temperature_Setpoint.md)
* [Effective_Air_Temperature_Cooling_Setpoint](../Air_Temperature_Setpoint/Effective_Air_Temperature_Setpoint/Effective_Air_Temperature_Cooling_Setpoint.md)
* [Occupied_Air_Temperature_Cooling_Setpoint](../Air_Temperature_Setpoint/Occupied_Air_Temperature_Setpoint/Occupied_Air_Temperature_Cooling_Setpoint.md)
* [Cooling_Supply_Air_Temperature_Deadband_Setpoint](../Temperature_Deadband_Setpoint/Supply_Air_Temperature_Deadband_Setpoint/Cooling_Supply_Air_Temperature_Deadband_Setpoint.md)
* [Supply_Air_Temperature_Cooling_Setpoint](../Air_Temperature_Setpoint/Supply_Air_Temperature_Setpoint/Supply_Air_Temperature_Cooling_Setpoint.md)
* [Unoccupied_Air_Temperature_Cooling_Setpoint](../Air_Temperature_Setpoint/Unoccupied_Air_Temperature_Setpoint/Unoccupied_Air_Temperature_Cooling_Setpoint.md)
* [Zone_Air_Cooling_Temperature_Setpoint](../Air_Temperature_Setpoint/Zone_Air_Temperature_Setpoint/Zone_Air_Cooling_Temperature_Setpoint.md)
* [Discharge_Air_Temperature_Cooling_Setpoint](../Air_Temperature_Setpoint/Discharge_Air_Temperature_Setpoint/Discharge_Air_Temperature_Cooling_Setpoint/Discharge_Air_Temperature_Cooling_Setpoint.md)

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
