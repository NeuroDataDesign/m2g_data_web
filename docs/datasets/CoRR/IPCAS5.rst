.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
IPCAS5
******************


Overview
-----------

IPCAS - Institute of Psychology, Chinese Academy of Sciences

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/ipcas_5.html for the website of the original dataset



All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/


**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_5/IPCAS_5-m2g-func-04-15-20 <your_local_direction>
	
example: aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_5/IPCAS_5-m2g-func-04-15-20 .





Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_5/IPCAS_5-m2g-func-04-15-20/<subject_number> <your_local_direction>

example: aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_5/IPCAS_5-m2g-func-04-15-20/sub-0027284 .


======	==============================
order	subject_number
======	==============================
1    	sub-0027284
2    	sub-0027285
3    	sub-0027286
4    	sub-0027287
5    	sub-0027288
6    	sub-0027289
7    	sub-0027290
8    	sub-0027291
9		sub-0027292
10    	sub-0027293
11    	sub-0027294
12    	sub-0027295
13    	sub-0027296
14    	sub-0027297
15    	sub-0027298
16    	sub-0027299
17    	sub-0027300
18    	sub-0027301
19		sub-0027302
20    	sub-0027303
21    	sub-0027304
22    	sub-0027305
======	==============================
