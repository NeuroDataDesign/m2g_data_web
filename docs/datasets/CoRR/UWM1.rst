.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
UWM1
******************


Overview
-----------

UWM - University of Wisconsin, Madison

All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/UWM/UWM-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/UWM/UWM-m2g-func-04-15-20 .``




Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/UWM/UWM-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/UWM/UWM-m2g-func-04-15-20/sub-0026018 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0027259
2    	sub-0027260
3    	sub-0027261
4    	sub-0027262
5    	sub-0027263
6    	sub-0027264
7    	sub-0027265
8    	sub-0027266
9		sub-0027267
10    	sub-0027268
11    	sub-0027269
12    	sub-0027270
13    	sub-0027271
14    	sub-0027272
15    	sub-0027273
16    	sub-0027274
17    	sub-0027275
18    	sub-0027276
19		sub-0027277
20    	sub-0027278
21    	sub-0027279
22    	sub-0027280
23    	sub-0027281
24    	sub-0027282
25    	sub-0027283
======	==============================