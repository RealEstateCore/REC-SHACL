[Point](../../../Point.md) > [Setpoint](../../Setpoint.md) > [Reset_Setpoint](../Reset_Setpoint.md) > [Temperature_High_Reset_Setpoint](#)
# Temperature_High_Reset_Setpoint

**Display name:** Temperature High Reset Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Temperature_High_Reset_Setpoint;1

---


## Child interfaces
* [Outside_Air_Temperature_High_Reset_Setpoint](Outside_Air_Temperature_High_Reset_Setpoint.md)
* [Return_Air_Temperature_High_Reset_Setpoint](Return_Air_Temperature_High_Reset_Setpoint.md)
* [Supply_Air_Temperature_High_Reset_Setpoint](Supply_Air_Temperature_High_Reset_Setpoint.md)
* [Entering_Hot_Water_Temperature_High_Reset_Setpoint](Entering_Hot_Water_Temperature_High_Reset_Setpoint/Entering_Hot_Water_Temperature_High_Reset_Setpoint.md)
* [Leaving_Hot_Water_Temperature_High_Reset_Setpoint](Leaving_Hot_Water_Temperature_High_Reset_Setpoint/Leaving_Hot_Water_Temperature_High_Reset_Setpoint.md)

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
