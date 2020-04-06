# iscTransactionItemType
Name | Type | Description
:--- | :--- | :----------
name | string | Description of the transaction item.
quantity |number, format: double | Number of kilograms or head or whatever the basis is.
units | uncefactMassUnitsType | The units to be used for the quantity field.
value | number, format: double | The value per kilogram or head or whatever.
discount | number, format: double | A discount factor such as 0.25 to apply a 25% discount.
discountValue | number, format: double | Specifies a fixed amount of discount
subtotal | number, format: double | Total of (value * quantity) * (1 - discount).