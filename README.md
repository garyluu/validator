### Validation Server Health
See http://142.1.177.94:5000/health_check to check its health.

### Validation Server Environment
See http://142.1.177.94:5000/environment to see the environment it is running on.

### Tool Registry Service Validation Status
| Service       | Status        |
| ------------- |---------------|
| Dockstore     | [![Validator Running](http://142.1.177.94:5000/trs/validator?url=https://dockstore.org:8443)](http://142.1.177.94:5000/trs/validator/debug?url=https://dockstore.org:8443) | 
| {placeholder_name} | [![Validator Running](http://142.1.177.94:5000/trs/validator?url={placeholder_url})](http://142.1.177.94:5000/trs/validator/debug?url={placeholder_url})      |  
| Add based on template above, just change {placeholder_name} to your service name| Add based on template above, just change {placeholder_url} to your webservice's url|   

If you see "Validator Running", refresh the page in a minute.
