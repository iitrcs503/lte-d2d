//// Problem Statement: Disaster resilient 4G network
//// Group: Himanshu Sagar; Mridul Katta; Kartik 
///////

When the eNbs aren't working (the instance is shown initially), then the Ue(s)(User entities) communicate with each other in a sort of adhoc network. We have implemented D2D communication via creating a wifi adhoc , so that Ues in proximity can communicate with each other.
As soon as eNbs get back working normal 4G working is shown.

Prerequistie:
1. Fully functional ns3 equipped machine; ns ver = 3.25
2. Visualizer
3. NetAnim 

Installation:
1. Download the zip; unzip all the files in ../ns3-dev/scratch/ 
2. In terminal cd to ns3-dev folder
3. Type the command:
	./waf --run scratch/lte
4. Once compiled, type the follows in order
	cd ..
	cd netanim-ver
	./ NetAnim
5. Once in NetAnim:
	Goto open file and locate lte-4G.xml; it will be in ns3-dev folder
6. Zoom as per requirement
7. Click simulate / play
 
