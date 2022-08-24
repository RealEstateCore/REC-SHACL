[Index](../../../../../Index.md) > [Point](../../../../Point.md) > [Setpoint](../../../Setpoint.md) > [Temperature_Setpoint](../../Temperature_Setpoint.md) > [Air_Temperature_Setpoint](../Air_Temperature_Setpoint.md) > [Room_Air_Temperature_Setpoint](#)
# Room_Air_Temperature_Setpoint

**Display name:** Room Air Temperature Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Room_Air_Temperature_Setpoint;1

---

## Child interfaces
* [Effective_Room_Air_Temperature_Setpoint](Effective_Room_Air_Temperature_Setpoint.md)
* [Occupied_Room_Air_Temperature_Setpoint](Occupied_Room_Air_Temperature_Setpoint.md)
* [Unoccupied_Room_Air_Temperature_Setpoint](../Unoccupied_Air_Temperature_Setpoint/Unoccupied_Room_Air_Temperature_Setpoint.md)

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
