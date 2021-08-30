
# Load Testing Demo using Artillery.io

Uses a sample API defined here:



## Notes

* Run all commands below from the root directory of the project

## Setup

* Install Node.js - ([download](https://nodejs.org/en/download/))
* Install Artillery - `npm install -g artillery`
* Install Artillery Expect Plugin - `npm install -g artillery-plugin-expect`
* Install project dependencies - `npm install`


## Run Tests

* Open the terminal to the root directory of this project

### Check Single Endpoint

artillery run tests/filename

### How to generate report as a json file

artillery run --output <filename>.json tests/<test_fileName>.yml

### How to create a html report

artillery report --output <htmlFileName>.html <NameOfJsonReportfile>.json
	
### *** For generate html report, before must have to generate json reponse ***	

