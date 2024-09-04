# API-Automation-CI

## Tech stacks:
+ Postman related components
+ Other tools/Environments handle in Jenkins include: newman, newman-reporter-html, newman-reporter-htmlextra

## Note:
+ **Run command:**
  + `newman run path_to_collection.json -e path_to_environment_file -d path_to_data_file -r htmlextra --reporter-htmlextra-export pạth_to_store_html_report_with_custom_name`
+ **Fix Error that jenkins html publisher show blank screen**
  + Manage Jenkins-> Manage Nodes-> Click settings(gear icon)-> click Script console on left and type in the following command:
`System.setProperty("hudson.model.DirectoryBrowserSupport.CSP", "")`

