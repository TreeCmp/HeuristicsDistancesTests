# HeuristicsDistancesTests
Tests of heuristic metrics for uSPR distance

A random unrooted tree T<sub>0</sub> containing 50 leaves with a uniform distribution was generated. To generate it, the https://github.com/TreeCmp/PRTGen tool was used by issuing the command: PRTGen\Release>PRTGen -n 50 -e 1 -spr 30. Then a random uSPR operation was performed on it, obtaining a tree T<sub>1</sub>. In the next step, another uSPR operation was performed on the tree T<sub>1</sub>, obtaining T<sub>2</sub> and so on and so forth, up to T<sub>30</sub>. While initially each successive tree T<sub>n</sub> was distant from T<sub>0</sub> equals n in uSPR distance, at some point this distance began to be smaller, sometimes the uSPR operation may not change or even reduce the distance from T<sub>0</sub> by 1. To calculate the true values ​​in the uSPR distance of subsequent trees to T<sub>0</sub>, the tool https://github.com/cwhidden/uspr was used.

