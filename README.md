# Simple Data Pipe &lt;TEMPLATE&gt; Connector 

:no_entry_sign: This project is no longer maintained.

This [Simple Data Pipe](https://developer.ibm.com/clouddataservices/simple-data-pipe/) connector template illustrates how to 
* load a static set of data sets (2016 election speeches) and
* store the results in Cloudant.

### Pre-requisites

##### General 
 Review the pre-requisites listed below.

##### Deploy the Simple Data Pipe

 [Deploy the Simple Data Pipe in Bluemix](https://github.com/ibm-cds-labs/simple-data-pipe) using the Deploy to Bluemix button or manually.

##### Services

This connector does not require any additional Bluemix service.

> 

##### Install the &lt;TEMPLATE&gt; connector

  When you [follow these steps to install this connector](https://github.com/ibm-cds-labs/simple-data-pipe/wiki/Installing-a-Simple-Data-Pipe-Connector), add the following line to the dependencies list in the package.json file: `"simple-data-pipe-connector-template": "https://github.com/ibm-cds-labs/simple-data-pipe-connector-template.git"`

##### Enable OAuth support and collect connectivity information
This sample connector does not connect to a cloud data source and therefore does not require oAuth authentication checking.

### Using the &lt;TEMPLATE&gt; Connector 

To configure and run a pipe

1. Open the Simple Data Pipe web console.
2. Select __Create A New Pipe__.
3. Select __Sample Data Source__ for the __Type__ when creating a new pipe  
4. In the _Connect_ page, enter any string as _consumer key_ and _consumer secret_. 
5. Select the data set (or data sets) to be loaded.
6. Schedule or run the data pipe now.

#### License 

Copyright [2016] IBM Cloud Data Services

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
