# iscMovementDeathEventResource
deathReason, disposalMethod, and disposalReference are required. Includes all properties from **icarEventCoreResource**.
Name | Type | Description
:--- | :--- | :----------
deathReason | **icarDeathReasonType** | Coded reasons for death including disease, parturition complications, consumption by humans or animals.
explanation | string | Free text explanation of the reason for death
disposalMethod | string. enum: "ApprovedService", "ConsumptionOnFarm", "ConsumptionOffFarm", "OnPremise", "Other". | Coded disposal methods including approved service, consumption by humans or animals, etc.
disposalOperator | string | Disposal operator official name.
disposalReference | string | Reference (receipt, docket, or ID) for disposal. 