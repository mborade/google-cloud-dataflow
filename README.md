# google-cloud-dataflow

This repo contains the code which implements the functionality of performing a lookup against some data stored on any storage system such as GCS or in BigQuery, etc and caching the lookup data and making it available as a side input to any transform function in a streaming dataflow job. The size of the lookup data should be small enough to fit in memory. Also, supports automatic refresh of the lookup data in the cache whenever the lookup data is updated.
