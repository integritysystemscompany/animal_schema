# iscAnimalCoreResource
Includes all properties from **icarAnimalCoreResource**
Name | Type | Description
:--- | :--- | :----------
birthDateConfidence | string | 3-character string with positional characters representing Year, Month, and Day (YMD).
birthRank | number, minimum: 0 | A value describing the number of progeny born to the same dam in the same birth event.
rearingRank | number, minimum: 0 | Rearing rank is used to indicate the number of progeny reared by the same dame during the same lactation.
birthCohort | number | The contemporary group or cohort that describes the season within the birth year into which animals are categorised.
preBirthMob | number | Mob ewe prior to lambing
postBirthMob | number | Mob ewe post lambing
breedSocSECode | string | Breed Society Single Entry Code"
breedSocRegStatus | string | enum: N, R, Null
breedSocRegDate | **icarDateTimeType** | Date and time of breed society registration status change.
statusChangeDate | **icarDateTimeType** | Date and time animal status last changed.
desexedDate | **icarDateTimeType** | Date and time animal was desexed (change to gender value).