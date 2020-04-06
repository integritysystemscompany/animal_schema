# iscConsignmentType
Includes all properties from **icarConsignmentType**.
Name | Type | Description
:--- | :--- | :----------
id | icarIdentiferType | Offical identifier for the movement.
origin | [iscOrganisationType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscOrganisationType.json)
destination | [iscOrganisationType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscOrganisationType.json)
loadingDateTime | icarDateTimeType | Date and time animals were loaded for transport, including time zone (UTC preferred).
unloadingDateTime | icareDateTimeType | Date and time animals were unloaded after transport, including time zone (UTC preferred).
expectedDuration | number | Expected duration of transportation in hours. 
vehicles | string | Identification of the vehicle (for example, licence plate).
transportReference | string | Shipping or transport reference.
isolationFacilityUsed | boolean | True is an isolation facility was used for the movement.
farmAssuranceReference | icarIdentiferType | Indentification reference of a farm assurance operation. 
responsible | [iscPersonType](github.com/integritysystemscompany/animal_schema/blob/master/types/iscPersonType.json) | Person who has authorised the movement. 
transporter | [iscPersonType](github.com/integritysystemscompany/animal_schema/blob/master/types/iscPersonType.json) | Person or driver who is transporting the stock.
documentURI | string | An optional URL to a document for this consignment (for instance, a PDF or image).
transactionRecord | [iscTransactionRecordType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscTransactionRecordType.json) | Transaction record from a government or other official service.
