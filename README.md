# Workflow use-case sample for Library ```dot-quiver```

This repository provides an application use case sample of library [dot-quiver](https://github.com/brunolnetto/dot-quiver) to handle [FlowBuild API](https://github.com/flow-build) artifact **blueprint**. It is a NodeJS application. Hence, you might follow the instructions below to start it.

## How to use

First of all, run commands below:

1. ```npm install```: install the package.json packages;
2. ```pip install pre-commit && pre-commit install```: install pre-commit hooks

Afterwards, you may place the desired _blueprints_ on path ```$WORKFLOW_SAMPLE_PATH/samples/blueprints/```. 

1. Run the command ```npm start```; 
2. Run the following command on the broser URL field ```localhost:8080```.

The result rendering depends on browser. 

The available functions for Workflow are [in this file](https://github.com/dot-quiver/dot-quiver-api/blob/master/utils/workflow/parsers.js).
