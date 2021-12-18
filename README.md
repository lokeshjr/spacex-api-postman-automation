# spacex-api-postman-automation
spacex api automation using postman tool and javascript
# Framework overview: 
API automation using postman - javascript. We can run the collection using newman CLI. Generates a nice html report for the tests

# Structure:

* collections
  - SpaceX-API-Automation.postman_collection.json
* newman
  - generates html reports
* .gitignore
* package.json
* package-lock.json

# Running the tests locally from newman CLI - 

First you would need to install the node packages/ dependencies in the package.json file.  

`npm install`

Then, open a new gitbash shell/terminal and type in below commands to run the tests-

`npm run newman-run`


# For reporting purpose - 

used newman-reporter-htmlextra for nice html reports

To serve the report. Please run the below command.

`npm run htmlreport`

# Import Collection to Postman tool or App

From the folder import collection.json file and run the collection.
