.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
IPCAS7
******************


Overview
-----------

IPCAS - Institute of Psychology, Chinese Academy of Sciences

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/ipcas_7.html for the website of the original dataset




All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/


**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS7/IPCAS7-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IPCAS7/IPCAS7-m2g-func-04-15-20 .``



Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS7/IPCAS7-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IPCAS7/IPCAS7-m2g-func-04-15-20/sub-0026046 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0026046
2    	sub-0026047
3    	sub-0026048
4    	sub-0026049
5    	sub-0026050
6    	sub-0026051
7    	sub-0026052
8    	sub-0026053
9		sub-0026054
10    	sub-0026055
11    	sub-0026057
12    	sub-0026058
13    	sub-0026059
14    	sub-0026060
15    	sub-0026061
16    	sub-0026062
17    	sub-0026063
18    	sub-0026064
19		sub-0026065
20    	sub-0026066
21    	sub-0026067
22    	sub-0026068
23    	sub-0026069
24    	sub-0026070
25    	sub-0026071
26    	sub-0026073
27    	sub-0026074
28    	sub-0026075
29		sub-0026076
30    	sub-0026077
31    	sub-0026078
32    	sub-0026079
33    	sub-0026080
34    	sub-0026081
35    	sub-0026082
36    	sub-0026083
37    	sub-0026084
38    	sub-0026085
39		sub-0026086
40    	sub-0026087
41    	sub-0026088
42    	sub-0026089
43    	sub-0026090
44    	sub-0026091
45    	sub-0026092
46    	sub-0026093
47    	sub-0026094
48    	sub-0026095
49		sub-0026096
50    	sub-0026097
51    	sub-0026098
52    	sub-0026099
53    	sub-0026100
54    	sub-0026101
55    	sub-0026102
56    	sub-0026103
57    	sub-0026104
58    	sub-0026105
59		sub-0026106
60    	sub-0026107
61    	sub-0026108
62    	sub-0026109
63    	sub-0026110
64    	sub-0026111
65    	sub-0026112
66    	sub-0026113
67    	sub-0026114
68    	sub-0026115
69		sub-0026116
70    	sub-0026117
71    	sub-0026118
72    	sub-0026119
======	==============================
