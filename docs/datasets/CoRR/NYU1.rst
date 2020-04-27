.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
NYU1
******************


Overview
-----------

NYU Institute for Pediatric Neuroscience Sample

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/nyu_1.html for the website of the original dataset


All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/NYU_1/NYU_1-m2g-func-04-15-20 <your_local_direction>
	
example: aws s3 sync --no-sign-request s3://ndmg-data/NYU_1/NYU_1-m2g-func-04-15-20 .




Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/NYU_1/NYU_1-m2g-func-04-15-20/<subject_number> <your_local_direction>

example: aws s3 sync --no-sign-request s3://ndmg-data/NYU_1/NYU_1-m2g-func-04-15-20/sub-0027103 .


======	==============================
order	subject_number
======	==============================
1    	sub-0027103
2    	sub-0027104
3    	sub-0027105
4    	sub-0027106
5    	sub-0027107
6    	sub-0027108
7    	sub-0027109
8    	sub-0027110
9		sub-0027111
10    	sub-0027112
11    	sub-0027113
12    	sub-0027114
13    	sub-0027115
14    	sub-0027116
15    	sub-0027117
16    	sub-0027118
17    	sub-0027119
18    	sub-0027120
19		sub-0027121
20    	sub-0027122
21    	sub-0027123
22    	sub-0027124
23    	sub-0027125
24    	sub-0027126
25    	sub-0027127
======	==============================