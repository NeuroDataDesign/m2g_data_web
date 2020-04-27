.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
SWU2
******************


Overview
-----------

SWU - Southwest University

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/swu_2.html for the website of the original dataset


**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/SWU2/SWU2-m2g-func-04-15-20 <your_local_direction>
	
example: aws s3 sync --no-sign-request s3://ndmg-data/SWU2/SWU2-m2g-func-04-15-20 .




Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/SWU2/SWU2-m2g-func-04-15-20/<subject_number> <your_local_direction>

example: aws s3 sync --no-sign-request s3://ndmg-data/SWU2/SWU2-m2g-func-04-15-20/sub-0027176 .


======	==============================
order	subject_number
======	==============================
1    	sub-0027176
2    	sub-0027177
3    	sub-0027178
4    	sub-0027179
5    	sub-0027180
6    	sub-0027181
7    	sub-0027182
8    	sub-0027183
9		sub-0027184
10    	sub-0027185
11    	sub-0027186
12    	sub-0027187
13    	sub-0027188
14    	sub-0027189
15    	sub-0027190
16    	sub-0027191
17    	sub-0027192
18    	sub-0027193
19		sub-0027194
20    	sub-0027195
21    	sub-0027196
22    	sub-0027197
23    	sub-0027198
24    	sub-0027199
25    	sub-0027200
26    	sub-0027201
27    	sub-0027202
======	==============================