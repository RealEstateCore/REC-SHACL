[Point](../../../Point.md) > [Sensor](../../Sensor.md) > [Demand_Sensor](../Demand_Sensor.md) > [Cooling_Demand_Sensor](#)
# Cooling_Demand_Sensor

**Display name:** Cooling Demand Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Cooling_Demand_Sensor;1

---


## Child interfaces
* [Average_Cooling_Demand_Sensor](Average_Cooling_Demand_Sensor.md)

---
## Relationships
### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf
## Properties
### Inherited Properties
* **[Point](../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name
## Target Of
### Inherited
* [Asset](../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../Collection/AssetCollection/EquipmentCollection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../Space/Architecture/Architecture.md).hasPoint
