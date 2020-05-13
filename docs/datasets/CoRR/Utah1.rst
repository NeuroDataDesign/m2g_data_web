.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
Utah1
******************


Overview
-----------

Utah  - University of Utah

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/utah_1.html for the website of the original dataset



All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/Utah1/Utah1-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/Utah1/Utah1-m2g-func-04-15-20 .``




Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/Utah1/Utah1-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/Utah1/Utah1-m2g-func-04-15-20/sub-0026018 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0026018
2    	sub-0026019
3    	sub-0026020
4    	sub-0026021
5    	sub-0026022
6    	sub-0026023
7    	sub-0026024
8    	sub-0026025
9		sub-0026026
10    	sub-0026027
11    	sub-0026028
12    	sub-0026029
13    	sub-0026030
14    	sub-0026031
15    	sub-0026032
16    	sub-0026033
17    	sub-0026034
18    	sub-0026035
19		sub-0026036
20    	sub-0026037
21    	sub-0026038
22    	sub-0026039
23    	sub-0026040
24    	sub-0026041
25    	sub-0026042
26    	sub-0026043
======	==============================