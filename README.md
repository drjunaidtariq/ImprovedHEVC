# Enhancing HEVC Efficiency: A Novel Approach to Intra-Mode Estimation through Hadamard Cost Analysis.
Steps: <br>
(1) Download the HEVC test Model (HM) platform from https://hevc.hhi.fraunhofer.de/. <br>
(2) Replace the "TAppEncoder" folder of HM by this folder. <br>
(3) The reason of providing complete "TAppEncoder" folder is that there are variables that access data from different files in this folder. <br>
(4) The most of the implementation is done in the "TEncSearch.cpp" file, because it searches the best intra-mode for the current block.
