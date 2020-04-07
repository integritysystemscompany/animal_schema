# iscTreatmentEventResource
Includes all properties from **icarEventCoreResource**.
Name | Type | Description
:--- | :--- | :----------
medicine | [iscMedicineResource](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscMedicineReferenceType.json) | The Medicine used in this treatment if applicable.
procedure | string | Medicine application method or non-medicine procedure.
batches | array. items: id, expiryDate. | Batches and expiry details of the medicine administered.
id | string | Batch id or number.
expiryDate |string, dateTime. | Expiration date of the batch.
withdrawals | [iscWithdrawalType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscWithdrawalType.json) | Provides withholding details for the treatment administered. 
dose | [iscDoseType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscDoseType.json) | Details of medicine dose administered.
site | string |  Body site where the treatment was administered.
responsible | string | Person responsible for the treatment.
