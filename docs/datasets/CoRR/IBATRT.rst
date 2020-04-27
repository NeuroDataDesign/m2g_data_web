.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
IBATRT
******************


Overview
-----------

IBATRT - Intrinsic Brain Activity, Test-Retest Dataset (LaConte, Craddock)

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/ibatrt.html for the website of the original dataset






All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/

	
	
**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/IBATRT/IBATRT-m2g-func-04-15-20 <your_local_direction>
	
example: aws s3 sync --no-sign-request s3://ndmg-data/IBATRT/IBATRT-m2g-func-04-15-20 .








Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/IBATRT/IBATRT-m2g-func-04-15-20/<subject_number> <your_local_direction>

example: aws s3 sync --no-sign-request s3://ndmg-data/IBATRT/IBATRT-m2g-func-04-15-20/sub-0027223 .


======	==============================
order	subject_number
======	==============================
1    	sub-0027223
2    	sub-0027224
3    	sub-0027225
4    	sub-0027226
5    	sub-0027227
6    	sub-0027228
7    	sub-0027229
8    	sub-0027230
9		sub-0027231
10    	sub-0027232
11    	sub-0027233
12    	sub-0027234
13    	sub-0027235
14    	sub-0027236
15    	sub-0027237
16    	sub-0027238
17    	sub-0027239
18    	sub-0027240
19		sub-0027241
20    	sub-0027242
21    	sub-0027243
22    	sub-0027244
23    	sub-0027245
24    	sub-0027246
25    	sub-0027247
26    	sub-0027248
27    	sub-0027249
28    	sub-0027250
29		sub-0027251
30    	sub-0027252
31    	sub-0027253
32    	sub-0027254
33    	sub-0027255
34    	sub-0027256
35    	sub-0027257
36    	sub-0027258
======	==============================



