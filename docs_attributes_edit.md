#### We have here two different types of non editable Fields:

1. Fields that are not editable by data design (marked in swagger as readonly)
2. Fields that are synced from a dataprovider they are editable but they are overwritten by the sync
 
The information 2 is not saved in Swagger.
The readonly flag in Swagger indicates only that the data has no “Setter”. Means if you send a Json with a modified readonly Field it is not saved to the DB.
For the fields that are synced It depends of the source of the data. At example for Accommodations, we currently have only data from source LTS. And since this data is synced constantly from LTS, it makes no sense to allow editing because after a sync all edits are overwritten. Only ODHTags can be added at the moment…….. So in the current Databrowser I marked many fields as non editable in the edit view.
However for ODHActivityPois the situation gets trickier. Here we have data that is inserted manually from the Redaction, data that is synced daily, data that was synced once and needs to get corrected etc…. So in this case I did not add the non editable marks…. All data is editable but can potentially be overwritten by a sync 😉 The redacteur has to know what data he has to modify and what data not…….

 
To give a little help what we did is we tried to add this information in the info box
 

Not sure how to handle this in future……… I think in a first  version we make everything not marked as readonly in Swagger editable……….


For the next MVPs we have to discuss if we need a strategy here on how to save the info wich field depending on what datastource is editable etc….

A bit of pandoras box, not sure if it gets to complicated handling also this
