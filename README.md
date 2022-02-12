# inverseDistanceFringe
OpenFOAM-v2006 overset digging holes to fringe

This lib is implemented under the desire that I want the HOLE cells to be further away from the wall patches. 
The version of OpenFOAM is v2006. Downald the files and wmake directly. 

Usage：add libs (oversetIDFringe) to the head of controlDict file. Set oversetInterpolation to be inverseDistanceFringe and add "nPushBack 2"(or just by default 2).
