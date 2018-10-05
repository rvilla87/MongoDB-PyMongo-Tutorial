# MongoDB-PyMongo-Tutorial
[MongoDB.ipynb](jupyter/MongoDB.ipynb): Some uses cases of Pymongo (**MongoDB** with Python) that includes:
- PyMongo [Tutorial](http://api.mongodb.com/python/current/tutorial.html).
- [Back to Basics](https://www.mongodb.com/presentations/back-to-basics-introduction-to-mongodb).
- [Beyond the Basics](https://www.mongodb.com/presentations/beyond-the-basics-1).
- Inserting, updating, querying, deleting documents.
- Indexing, geospatial indexes.
- Geospatial queries:
    - **\$geoWithin**: Selects documents with geospatial data that exists entirely within a specified shape.
    - **\$geoIntersects**: Selects documents whose geospatial data intersects with a specified GeoJSON object.
    - **\$near** and **\$nearSphere**: Specifies a point for which a geospatial query returns the documents from nearest to farthest.
    - **\$geoNear (aggregation)**: Outputs documents in order of nearest to farthest from a specified point. Used to calculate the distance between two points.
