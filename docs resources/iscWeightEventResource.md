# iscWeightEventResource
A livestock weight observation. weight is required. Includes all properties from **icarEventCoreResource**.
Name | Type | Description
:--- | :--- | :----------
weight | [iscMassMeasurementType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscMassMeasurementType.json) | The weight observation, in the units specified (usually kilograms).
method | **icarWeightMethodType** | Method by which the weight is observed.
device | **icarDeviceReferenceType** | Optional information about the device used for the measurement.
traitLabel | **icarIdentifierType** | Identifies the intended formal trait using scheme and ID. For instance: nz.sheep.traits, LW8. 
timeOffFeed | number. format: double. | Time in hours the animal has been off feed.