# iscLotDetailType
Name | Type | Description
:--- | :--- | :----------
eventName | string | Name of the trading (sale or purchase) event.
eventReference | [iscTradingEventIdentifierType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscTradingEventIdentifierType.json) | Event reference using the scheme and ID method (e.g. auctionsplus.com.au, #15263).
vendor | [iscOrganistionType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscOrganisationType.json) | Details of the vender selling the stock.
purchaser | [iscOrganisationType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscOrganisationType.json) | Details of the buyer purchasing the stock.
lotId | string | Lot Identification number in the sale.
description | string | Lot description
accreditations | string | Any accreditation's that are applicable to the lot.
locations | **icarLocationIdentifierType** | Locations from where the stock are.
agent | [iscOrganisationType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscOrganisationType.json) | Agent details for the lot.
assessments | [iscLotAssessmentType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscLotAssessmentType.json) | A set of assessments for the animal(s) in the lot.
sellingBasis | [iscSellingBasisType](https://github.com/integritysystemscompany/animal_schema/blob/master/types/iscSellingBasisType.json) | Basis on which the stock was sold. 
