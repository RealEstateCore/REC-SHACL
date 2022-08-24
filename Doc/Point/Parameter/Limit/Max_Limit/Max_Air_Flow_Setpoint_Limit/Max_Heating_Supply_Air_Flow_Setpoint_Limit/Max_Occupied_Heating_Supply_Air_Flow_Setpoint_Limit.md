[Point](../../../../../Point.md) > [Parameter](../../../../Parameter.md) > [Limit](../../../Limit.md) > [Max_Limit](../../Max_Limit.md) > [Max_Air_Flow_Setpoint_Limit](../Max_Air_Flow_Setpoint_Limit.md) > [Max_Heating_Supply_Air_Flow_Setpoint_Limit](Max_Heating_Supply_Air_Flow_Setpoint_Limit.md) > [Max_Occupied_Heating_Supply_Air_Flow_Setpoint_Limit](#)
# Max_Occupied_Heating_Supply_Air_Flow_Setpoint_Limit

**Display name:** Max Occupied Heating Supply Air Flow Setpoint Limit<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Max_Occupied_Heating_Supply_Air_Flow_Setpoint_Limit;1

---
## Relationships
### Inherited Relationships
* **[Point](../../../../../Point.md):** isPointOf
## Properties
|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Point](../../../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name
## Target Of
### Inherited
* [Asset](../../../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../../../Space/Architecture/Architecture.md).hasPoint
