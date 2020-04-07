# iscMeasurementType
Defines a generalized measurement object with value and resolution. Override to provide specific units.
Name | Type | Description
:--- | :--- | :----------
resolution | number, format: double | The smallest measurement difference that can be discriminated given the current device settings. Specified in Units, for instance 0.5 (kilograms).
value | number, format: double | The weight observation, in the units specified (usually kilograms).
