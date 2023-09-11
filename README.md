# nosql-challenge

The nosql-challenge takes advantage of the efficient memory processing within Mongodb where it is interacted with via pythonic language using the pymongo library.

using a bash terminal the data set can be imported using the following:

mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json

ensure that you are cd'd into the directory containing the json when you run the import.

If any changes are necessary, it is often better to drop the data base and re run the script since database methods are adding to and deleting from the original JSON - simply re running the python a second time would lead to second instances of additions etc.
