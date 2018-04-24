# Justification Diagram Model To SACM
Model transformation from Justification Diagram to SACM using EMF and ATL

# Running The Tools
1. You need to install a EMF distribution and install ATL plug-in
2. Import the source of this repo as a new project
3. Change the configuration of the ATL transformation to switch between the examples

# Project Organization 
1. ```models``` directory constains the Ecore model for Justification Diagram and SACM
2. ```JD-examples``` directory contains XMI instance of Justification Diagram to transform
3. ```SACM-generated``` directory contains the outputs in XMI of the transformation of the examples
4. ```JD2SCAM.atl``` contains the ALT transformation rules


# Acknowledgement
Thanks to the intial SACM ecore model provided here : https://github.com/epsilonlabs/SACM-UML-Profile
