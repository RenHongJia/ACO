The prep_ files are used to import the networks (.dsc files) or import data in the case of the iris
dataset. These files create the BN, sample data from them and deliver a data set that can be used with 
the ACO to create a new BN. 

The _result files are some workspaces saved after running the ACO.

The _analyse files (in seperate folder) are used to gather the relevant measures from the data 
delivered by the ACO so they can be analysed. These scripts perform kruskall-wallis tests on the
effect of weight set and pheromone update strategy.
