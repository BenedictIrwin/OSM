# OSM
Open Source Malaria 

This is a contribution to the https://github.com/OpenSourceMalaria/Series4_PredictiveModel/issues/1 event

Ben Irwin works at Optibrium Ltd.
Mario Öeren works at Optibrium Ltd.
Tom Whitehead works at Intellegens Ltd.

We will attempt to fill in the data matrix using some deep learning methods and provide this to the community.

We *may* attempt to use the method as described in this publication: 
Imputation of Assay Bioactivity Data Using Deep Learning
T. M. Whitehead, B. W. J. Irwin, P. Hunt, M. D. Segall, and G. J. Conduit
Journal of Chemical Information and Modeling 2019 59 (3), 1197-1204
DOI: 10.1021/acs.jcim.8b00768
https://pubs.acs.org/doi/10.1021/acs.jcim.8b00768

Not due to confusions with the submission format we will try for a simpler mutli assay method first.
01/10/2019: We will now attempt a QSAR vs. Quantum mechanical descriptor approach. We have taken the help of Mario Öeren on board who is an expert in drug metabolism and will help us with potential QM descriptors. This may include pka related endpoints.

Deadline appears to be 11th October.

Have noted the Master chemical list is there but there are inconsistencies. 

--- Training stats  ---
Working with project: OSMMaster_full
EC50Chembl(uM),R^2,0.63,in,0.63,0.65,375,test entries Actual error in range,0.00,1.65,avg,0.39, Alchemite errors ,0.18,1.12,0.50 v 0.39
Ion Regulation Activity,R^2,0.59,in,0.59,0.61,616,test entries Actual error in range,0.00,0.98,avg,0.20, Alchemite errors ,0.00,0.50,0.18 v 0.20
Most Acidic pKa,R^2,0.39,in,0.39,0.40,912,test entries Actual error in range,0.00,37.95,avg,1.45, Alchemite errors ,0.02,2.26,0.77 v 1.45
Most Basic pKa,R^2,0.78,in,0.78,0.79,912,test entries Actual error in range,0.00,23.46,avg,0.84, Alchemite errors ,0.09,3.54,0.80 v 0.84
PfaI EC50 (Inh),R^2,0.70,in,0.70,0.71,159,test entries Actual error in range,0.00,1.66,avg,0.44, Alchemite errors ,0.12,0.85,0.47 v 0.44
Pfal (3D7) IC50 (Broad),R^2,0.95,in,0.95,0.96,11,test entries Actual error in range,0.00,0.07,avg,0.19, Alchemite errors ,0.33,0.53,0.43 v 0.19
Pfal (Dd2) IC50 (Broad),R^2,0.94,in,0.94,0.96,11,test entries Actual error in range,0.00,0.15,avg,0.21, Alchemite errors ,0.30,0.60,0.45 v 0.21
Pfal (K1) IC50 (Avery),R^2,0.96,in,0.96,0.97,24,test entries Actual error in range,0.00,0.10,avg,0.14, Alchemite errors ,0.12,0.62,0.25 v 0.14
Pfal (K1) IC50 (Guy),R^2,0.79,in,0.79,0.92,9,test entries Actual error in range,0.00,0.53,avg,0.31, Alchemite errors ,0.38,0.63,0.47 v 0.31
Pfal IC50 (Avery),R^2,0.87,in,0.87,0.88,156,test entries Actual error in range,0.00,2.26,avg,0.37, Alchemite errors ,0.09,1.25,0.35 v 0.37
Pfal IC50 (Dundee),R^2,0.66,in,0.66,0.69,324,test entries Actual error in range,0.00,4.02,avg,0.43, Alchemite errors ,0.14,1.19,0.39 v 0.43
Pfal IC50 (GSK),R^2,0.94,in,0.94,0.95,71,test entries Actual error in range,0.00,0.23,avg,0.19, Alchemite errors ,0.09,0.75,0.25 v 0.19
Pfal IC50 (Guy),R^2,0.83,in,0.83,0.93,9,test entries Actual error in range,0.00,0.29,avg,0.24, Alchemite errors ,0.32,0.53,0.40 v 0.24
Pfal IC50 (Ralph),R^2,0.79,in,0.79,0.85,85,test entries Actual error in range,0.00,1.63,avg,0.26, Alchemite errors ,0.10,0.93,0.21 v 0.26
Pfal IC50 (Syngene),R^2,0.83,in,0.83,0.85,86,test entries Actual error in range,0.00,1.25,avg,0.34, Alchemite errors ,0.11,0.76,0.39 v 0.34
Single Shot Inhibition %,R^2,0.93,in,0.93,0.94,41,test entries Actual error in range,0.17,409.53,avg,8.20, Alchemite errors ,10.63,34.74,17.94 v 8.20
Average R2 = 0.78675246513352

Some of the assays are to be trusted much more than others.
