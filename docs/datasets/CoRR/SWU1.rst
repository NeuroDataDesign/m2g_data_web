.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
SWU1
******************


Overview
-----------

SWU - Southwest University

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/swu_1.html for the website of the original dataset


All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/SWU1/SWU1-m2g-func-04-15-20 <your_local_direction>
	
example: aws s3 sync --no-sign-request s3://ndmg-data/SWU1/SWU1-m2g-func-04-15-20 .




Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/SWU1/SWU1-m2g-func-04-15-20/<subject_number> <your_local_direction>

example: aws s3 sync --no-sign-request s3://ndmg-data/SWU1/SWU1-m2g-func-04-15-20/sub-0027203 .


======	==============================
order	subject_number
======	==============================
1    	sub-0027203
2    	sub-0027204
3    	sub-0027205
4    	sub-0027206
5    	sub-0027207
6    	sub-0027208
7    	sub-0027209
8    	sub-0027210
9		sub-0027211
10    	sub-0027212
11    	sub-0027213
12    	sub-0027214
13    	sub-0027215
14    	sub-0027216
15    	sub-0027217
16    	sub-0027218
17    	sub-0027219
18    	sub-0027220
19		sub-0027221
20    	sub-0027222
======	==============================