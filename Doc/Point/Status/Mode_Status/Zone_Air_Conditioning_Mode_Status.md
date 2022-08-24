[Point](../../Point.md) > [Status](../Status.md) > [Mode_Status](Mode_Status.md) > [Zone_Air_Conditioning_Mode_Status](.)
# Zone_Air_Conditioning_Mode_Status

**Display name:** Zone Air Conditioning Mode Status<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Zone_Air_Conditioning_Mode_Status;1

---
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
