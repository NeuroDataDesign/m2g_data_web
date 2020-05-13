.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
IPCAS8
******************


Overview
-----------

IPCAS - Institute of Psychology, Chinese Academy of Sciences

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/ipcas_8.html for the website of the original dataset



All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/


**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_8/IPCAS_8-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_8/IPCAS_8-m2g-func-04-15-20 .``





Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_8/IPCAS_8-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_8/IPCAS_8-m2g-func-04-15-20/sub-0025586 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0025586
2    	sub-0025587
3    	sub-0025588
4    	sub-0025589
5    	sub-0025590
6    	sub-0025591
7    	sub-0025592
8    	sub-0025593
9		sub-0025594
10    	sub-0025595
11    	sub-0025596
12    	sub-0025597
13    	sub-0025598
======	==============================

