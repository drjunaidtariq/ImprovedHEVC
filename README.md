# Enhancing HEVC Efficiency: A Novel Approach to Intra-Mode Estimation through Hadamard Cost Analysis.
Steps: <br>
(1) Download the HEVC test Model (HM) platform from https://hevc.hhi.fraunhofer.de/. <br>
(2) Download "TAppEncoder" folder from https://github.com/drjunaidtariq/ImprovedHEVC. This "TAppEncoder" folder contains the proposed model. <br>
(3) Replace the "TAppEncoder" folder of HEVC (Step 1) with the "TAppEncoder" folder of the proposed algorithm (Step 2). The reason of replacing complete "TAppEncoder" folder is that there are variables that access data from different files in this folder. <br>
(4) The most of the implementation is done in the "TEncSearch.cpp" file, because it searches the best intra-mode for the current block. <br>
(5) Rebuild the project, press F5 key from the keyboard. This will compress the video using proposed algorithm.
