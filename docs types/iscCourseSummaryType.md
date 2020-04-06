# iscCourseSummaryType
Name | Type | Description
:--- | :--- | :----------
startDate | string, dateTime | Start date of the treatment course
endDate | string, dateTime | End date of the treatment course.
medicine | [iscMedicineReferenceType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscMedicineReferenceType.json) | Medicine details used in the course.
procedure | string | Medicine application method or non-medicine procedure.
site | string | Body site where the treatment was administered.
reasonForAdministration | string | This attribute can be used when medicine has been administered without a diagnosis.
totalDosage | [iscDoseType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscDoseType.json) | Total dosage proposed or administered.
batches | array, items: id, expiryDate | Batches and expiry details of the medicine administered.
id | string | batch id or number.
expiryDate | string, dateTime | Expiration date of the batch.
planOrActual | string, enum: Plan, Actual | Indicator showing if the attributes in the course Summary are actual information for the treatments or the plan.