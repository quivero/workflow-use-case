# Workflow use-case sample for library ```prego```

This repository provides an application use case sample of library [prego](https://github.com/quivero/prego) to handle [FlowBuild API](https://github.com/flow-build) artifact **blueprint**. It is a NodeJS application. Hence, you might follow the instructions below to start it.

## How to use

First of all, run the command ```npm install``` to install the package.json packages. Afterwards, you may place the desired _blueprints_ on path ```$WORKFLOW_SAMPLE_PATH/samples/blueprints/```. Finally, run the commands below:

1. Run the command ```npm start```; 
2. Run the following command on the broser URL field ```localhost:8080```.

The result rendering depends on chosen browser. 

The available functions for Workflow are [in this file](https://github.com/quivero/prego/blob/master/utils/workflow/parsers.js). You must edit the file ```/src/index.js``` to explore the available funcionalities.
