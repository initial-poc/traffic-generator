# Jmeter Traffic-generator

This repo contains a Jmeter JMX file through which the traffic can be generated to spanner-crud exposed API endpoint.

Steps to generate traffic:
```
1. CSV Data Set Config from with-in Jmeter script has to be configured with the desired csv file to upload records.
2. Thread Group configuration is kept to 100 threads as default. Can be re-configured with the desired value.
3. Once the above configurations are done, just click the play button in Jmeter to run the script.
```
