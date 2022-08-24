[Point](../../../../Point.md) > [Setpoint](../../../Setpoint.md) > [Temperature_Setpoint](../../Temperature_Setpoint.md) > [Radiant_Panel_Temperature_Setpoint](../Radiant_Panel_Temperature_Setpoint.md) > [Embedded_Temperature_Setpoint](Embedded_Temperature_Setpoint.md) > [Core_Temperature_Setpoint](.)
# Core_Temperature_Setpoint
**DTMI:** dtmi:org:brickschema:schema:Brick:Core_Temperature_Setpoint;1
## Display name
- **en:** Core Temperature Setpoint
## Description
## Relationships
### Inherited Relationships
* **dtmi:org:brickschema:schema:Brick:Point;1:** isPointOf
## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
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
