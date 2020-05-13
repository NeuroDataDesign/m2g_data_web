.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
IACAS1
******************


Overview
-----------


IACAS - Institute of Automation, Chinese Academy of Sciences

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/iacas_1.html for the website of the original dataset




All Data Download Instructions
-------------------------------------


Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/


**Functional MRI result**::


	aws s3 sync --no-sign-request s3://ndmg-data/IACAS_1/IACAS_1-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IACAS_1/IACAS_1-m2g-func-04-15-20 .``



Single Sample Download Instructions
----------------------------------------



**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/IACAS_1/IACAS_1-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IACAS_1/IACAS_1-m2g-func-04-15-20/sub-0025464 .``



=====	==============================
index	subject_number
=====	==============================
1    	sub-0025457
2    	sub-0025458
3    	sub-0025459
4    	sub-0025460
5    	sub-0025461
6    	sub-0025462
7    	sub-0025463
8    	sub-0025464
9		sub-0025465
10    	sub-0025466
11    	sub-0025467
12    	sub-0025468
13    	sub-0025469
14    	sub-0025470
15    	sub-0025471
16    	sub-0025472
17    	sub-0025473
18    	sub-0025474
19		sub-0025475
20    	sub-0025476
21    	sub-0025477
22    	sub-0025478
23    	sub-0025479
24    	sub-0025480
25    	sub-0025481
26    	sub-0025482
27    	sub-0025483
28    	sub-0025484
=====	==============================