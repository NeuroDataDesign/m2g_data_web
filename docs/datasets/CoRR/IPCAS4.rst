.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
IPCAS4
******************


Overview
-----------

IPCAS - Institute of Psychology, Chinese Academy of Sciences

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/ipcas_4.html for the website of the original dataset



All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/


**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS4/IPCAS4-m2g-func-04-15-21 <your_local_direction>
	
example: aws s3 sync --no-sign-request s3://ndmg-data/IPCAS4/IPCAS4-m2g-func-04-15-21 .







Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS4/IPCAS4-m2g-func-04-15-21/<subject_number> <your_local_direction>

example: aws s3 sync --no-sign-request s3://ndmg-data/IPCAS4/IPCAS4-m2g-func-04-15-21/sub-0026190 .


======	==============================
order	subject_number
======	==============================
1    	sub-0026190
2    	sub-0026191
3    	sub-0026192
4    	sub-0026193
5    	sub-0026194
6    	sub-0026195
7    	sub-0026196
8    	sub-0026197
9		sub-0026198
10    	sub-0026199
11    	sub-0026200
12    	sub-0026201
13    	sub-0026202
14    	sub-0026203
15    	sub-0026204
16    	sub-0026205
17    	sub-0026206
18    	sub-0026207
19		sub-0026208
20    	sub-0026209
======	==============================
