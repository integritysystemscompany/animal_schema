# iscMovementRetagEventResource
Use this event to record new tags applied to an animal in place of a lost tag. Includes all properties from **icarEventCoreResource**.
Name | Type | Description
:--- | :--- | :----------
replacementTagType | string | Describes the type of replacement tag applied (country specific).
previousIdentifier | **icarAnimalIdentifierType** | The previous identifier of the animal, if known.
animalDetail | **icarAnimalCoreResource** | Where the previous identifier of the animal is not known, captures known life data.
