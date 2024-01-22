#READ ME file

2D LINE-SCANNING PULSE SEQUENCE SOFTWARE ON PARAVISION 6

Created by Steve (Sangcheon) Choi, scchoi@mgh.harvard.edu, December 2023
Translational Neuroimaging and Neural Control group 
Athinoula A. Martinos Center for Biomedical Imaging, Massachusetts General Hospital, 
Deparment of Radiology, Harvard Medical School, MA, USA.


A. PULSE SEQUENCE SCRIPTS (tnnc2DLS_PV6 for 2D line-scanning fMRI study)

  The scripts contains a modified version of GRE pulse sequence for 2D line-scanning fMRI acquisition.
  it is implemented in ParaVision 6 of Bruker console software.
  Once the scripts are complied, the procotol will appear on the console


B. COMPILE THE PULSE SEQUENCE ON PV6

  1) In 'Workspace Explorer' window on PV6, go to Method Development Menu
  2) Go to User Methods (user account) Menu.
  3) Click the left button of your mouse and select the 'import' option.
  4) Import 'tnnc2DLS_PV' scripts.
  5) Click the left button of your mouse and select the 'complie' option.
      
C. CHECK THE GENERATED PROTOCOL

  1) In 'Scan Program' window on PV6, go to MRI (AnyRegion) Menu
  2) Go to UserMethods Menu.
  3) Find 'tnnc2DLS_PV6' protocol.
  4) Drag and drop the procotol in the 'instruction' window of your examination.

D. REFERENCES

  [1] S. Choi et al, No Replication of Direct Neuronal Activity-related (DIANA) fMRI in Anesthetized Mice. bioRxiv. Epub ahead 
      of print 29 May 2023. DOI: 10.1101/2023.05.26.542419.






