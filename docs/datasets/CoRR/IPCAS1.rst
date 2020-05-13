.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
IPCAS1
******************


Overview
-----------

IPCAS - Institute of Psychology, Chinese Academy of Sciences

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/ipcas_1.html for the website of the original dataset




All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



	
**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS1/IPCAS1-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IPCAS1/IPCAS1-m2g-func-04-15-20 .``



Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS1/IPCAS1-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IPCAS1/IPCAS1-m2g-func-04-15-20/sub-0025485 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0025485
2    	sub-0025486
3    	sub-0025487
4    	sub-0025488
5    	sub-0025489
6    	sub-0025490
7    	sub-0025491
8    	sub-0025492
9		sub-0025493
10    	sub-0025494
11    	sub-0025495
12    	sub-0025496
13    	sub-0025497
14    	sub-0025498
15    	sub-0025499
16    	sub-0025500
17    	sub-0025501
18    	sub-0025502
19		sub-0025503
20    	sub-0025504
21    	sub-0025505
22    	sub-0025506
23    	sub-0025507
24    	sub-0025508
25    	sub-0025509
26    	sub-0025510
27    	sub-0025511
28    	sub-0025512
29		sub-0025513
30    	sub-0025514
======	==============================


