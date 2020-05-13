.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
BMB1
******************


Overview
-----------

Berlin School of Mind and Brain / Neuro Bureau Sample

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/bmb_1.html for the website of the original dataset



All Data Download Instructions
-------------------------------------


Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/


**Functional MRI result**::


	aws s3 sync --no-sign-request s3://ndmg-data/BMB_1/BMB_1-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/BMB_1/BMB_1-m2g-func-04-15-20 .``



Single Sample Download Instructions
----------------------------------------



**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BMB_1/BMB_1-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/BMB_1/BMB_1-m2g-func-04-15-20/sub-0003001 .``



=====	==============================
index	subject_number
=====	==============================
1    	sub-0003001
2    	sub-0003002
3    	sub-0003004
4    	sub-0003006
5    	sub-0003007
6    	sub-0003008
7    	sub-0003009
8    	sub-0003010
9		sub-0003011
10    	sub-0003012
11    	sub-0003013
12    	sub-0003014
13    	sub-0003015
14    	sub-0003016
15    	sub-0003017
16    	sub-0003018
17    	sub-0003020
18    	sub-0003021
19		sub-0003022
20    	sub-0003023
21    	sub-0003024
22    	sub-0003025
23    	sub-0003026
24    	sub-0003032
25    	sub-0003033
26    	sub-0003034
27    	sub-0003036
28    	sub-0003037
29		sub-0003038
30    	sub-0003039
31    	sub-0003040
32    	sub-0003041
33    	sub-0003042
34    	sub-0003044
35    	sub-0003045
36    	sub-0003047
37    	sub-0003049
38    	sub-0003050
39		sub-0003051
40    	sub-0003052
41    	sub-0003054
42    	sub-0003055
43    	sub-0003056
44    	sub-0003057
45    	sub-0003059
46    	sub-0003060
47    	sub-0003061
48    	sub-0003062
49		sub-0003063
50    	sub-0003064
=====	==============================