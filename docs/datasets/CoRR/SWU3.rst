.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
SWU3
******************


Overview
-----------

SWU - Southwest University

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/swu_3.html for the website of the original dataset


All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/SWU3/SWU3-m2g-func-04-15-20 <your_local_direction>
	
example: aws s3 sync --no-sign-request s3://ndmg-data/SWU3/SWU3-m2g-func-04-15-20 .




Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/SWU3/SWU3-m2g-func-04-15-20/<subject_number> <your_local_direction>

example: aws s3 sync --no-sign-request s3://ndmg-data/SWU3/SWU3-m2g-func-04-15-20/sub-0026044 .


======	==============================
order	subject_number
======	==============================
1    	sub-0027152
2    	sub-0027153
3    	sub-0027154
4    	sub-0027155
5    	sub-0027156
6    	sub-0027157
7    	sub-0027158
8    	sub-0027159
9		sub-0027160
10    	sub-0027161
11    	sub-0027162
12    	sub-0027163
13    	sub-0027164
14    	sub-0027165
15    	sub-0027166
16    	sub-0027167
17    	sub-0027168
18    	sub-0027169
19		sub-0027170
20    	sub-0027171
21    	sub-0027172
22    	sub-0027173
23    	sub-0027174
24    	sub-0027175
======	==============================