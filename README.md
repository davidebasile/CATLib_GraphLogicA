# CATLib for Spatial Problems

This repository groups experiments being performed about applying CATLib to spatial problems, e.g., synthesising a strategy 
enforcing spatial properties on a topological graph.

## Video demo
A video demo created using this repository is available at https://youtu.be/08_iok6R9sw.
Each frame of the video has been generated by executing the code in 
https://github.com/ContractAutomataProject/CATLib_PngConverter/blob/master/src/java/io/github/contractautomata/maze/AppVideoComposition.java
and by incrementing the bound of the call to the composition method. 

All frames are stored in the folder 
https://github.com/ContractAutomataProject/CATLib_PngConverter/tree/master/test/java/io/github/contractautomata/maze/resources/video.


## Miscellanea

The JSONConverter for importing graphs of <a href="https://github.com/vincenzoml/topochecker">topochecker</a> encoding bitmap images has been moved into this repository.
A PngConverter is also available for directly importing png images as automata, by-passing the JSon representation.
