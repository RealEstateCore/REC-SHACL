[Point](../../../../Point.md) > [Sensor](../../../Sensor.md) > [Air_Quality_Sensor](../../Air_Quality_Sensor.md) > [Particulate_Matter_Sensor](../Particulate_Matter_Sensor.md) > [PM25_Sensor](#)
# PM25_Sensor

**Display name:** PM2.5 Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:PM25_Sensor;1

---

## Child interfaces
* [PM25_Level_Sensor](PM25_Level_Sensor.md)

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
