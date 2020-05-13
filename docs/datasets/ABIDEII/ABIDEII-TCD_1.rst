.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
ABIDEII-TCD_1
******************



Overview
-----------

Autism Brain Imaging Data Exchange II  -  TCD


See http://fcon_1000.projects.nitrc.org/indi/abide/abide_II.html for the website of the original dataset

**Sample Connectome** from sub-29124_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png


.. image:: ../../_static/connectomic_pic/ABIDEII-TCD_1-sub-29124_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png
	:width: 400
	:align: center


All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Diffusion MRI result**::

	aws s3 sync --no-sign-request s3://ndmg-data/ABIDEII-TCD_1/ABIDEII-TCD_1-m2g-dwi-04-15-20-csa-det-native <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/ABIDEII-TCD_1/ABIDEII-TCD_1-m2g-dwi-04-15-20-csa-det-native .``

	
**Functional MRI result**::


	aws s3 sync --no-sign-request s3://ndmg-data/ABIDEII-TCD_1/ABIDEII-TCD_1-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/ABIDEII-TCD_1/ABIDEII-TCD_1-m2g-func-04-15-20 .``



Single Sample Download Instructions
----------------------------------------



**Diffusion MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/ABIDEII-TCD_1/ABIDEII-TCD_1-m2g-dwi-04-15-20-csa-det-native/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/ABIDEII-TCD_1/ABIDEII-TCD_1-m2g-dwi-04-15-20-csa-det-native/sub-29117 .``

=====	==============================
index	subject_number
=====	==============================
1    	sub-29117
2    	sub-29118
3    	sub-29119
4    	sub-29120
5    	sub-29121
6    	sub-29122
7    	sub-29123
8    	sub-29124
9		sub-29126
10    	sub-29127
11    	sub-29128
12    	sub-29129
13    	sub-29130
14    	sub-29131
15    	sub-29133
16    	sub-29134
17    	sub-29135
18    	sub-29136
19		sub-29137
=====	==============================




**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/ABIDEII-TCD_1/ABIDEII-TCD_1-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/ABIDEII-TCD_1/ABIDEII-TCD_1-m2g-func-04-15-20/sub-29117 .``


=====	==============================
index	subject_number
=====	==============================
1    	sub-29117
2    	sub-29118
3    	sub-29119
4    	sub-29120
5    	sub-29121
6    	sub-29122
7    	sub-29123
8    	sub-29124
9		sub-29126
10    	sub-29127
11    	sub-29128
12    	sub-29129
13    	sub-29130
14    	sub-29131
15    	sub-29133
16    	sub-29134
17    	sub-29135
18    	sub-29136
19		sub-29137
=====	==============================