# Import Features from ArcGIS Online into ElasticSearch 
-------------- 

## Usage

This package reads the datasets from a file `datasets.json` (an output from ArcGIS Open Data) and will attempt to index every feature into Elastic Search. 

  ```
    Usage: node index.js {host} {index}
    > node index.js localhost:9200 agolfeatures
  ```
