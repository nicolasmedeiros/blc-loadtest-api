# blc-loadtest-api
1. [Install jmeter](https://jmeter.apache.org/download_jmeter.cgi)
2. Open jmeter: `./bin/jmeter` 
3. Open the test suite `create_inspection.jmx` and fill in the header values in the "HTTP Header Manager" for the REST API
4. Add vehicle IDs to the `vehicles.csv`. This vehicles should not have inspections 

*Note*: `create_inspection.jmx` to change the image to be uploaded usa a Base64 encoded imagen and paste it in the payload field `sections_attributes.encoded_image`.

