# dswm
DataStream Washing Machine repo with Elastic Ingest Pipeline to be used with Akamai DataStream.

Just add this ingest pipeline to the index datastream is sending his data to via the "index.default_pipeline": "dswm" parameter and off you go.

PUT /<index>
{
  "settings": {
    "index": {
      "default_pipeline": "dswm"
    }
  }
}
