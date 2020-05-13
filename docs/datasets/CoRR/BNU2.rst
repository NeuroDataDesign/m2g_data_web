.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
BNU2
******************


Overview
-----------

Connectivity-based Brain Imaging Research Database (C-BIRD) at BNU

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/bnu_2.html for the website of the original dataset




All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/

	
	
**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/BNU2/BNU2-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/BNU2/BNU2-m2g-func-04-15-20 .``



Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU2/BNU2-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/BNU2/BNU2-m2g-func-04-15-20/sub-0025921 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0025921
2    	sub-0025922
3    	sub-0025923
4    	sub-0025924
5    	sub-0025925
6    	sub-0025926
7    	sub-0025927
8    	sub-0025928
9		sub-0025929
10    	sub-0025930
11    	sub-0025931
12    	sub-0025932
13    	sub-0025933
14    	sub-0025934
15    	sub-0025935
16    	sub-0025936
17    	sub-0025937
18    	sub-0025938
19		sub-0025939
20    	sub-0025940
21    	sub-0025941
22    	sub-0025942
23    	sub-0025943
24    	sub-0025944
25    	sub-0025945
26    	sub-0025946
27    	sub-0025947
28    	sub-0025948
29		sub-0025949
30    	sub-0025950
31    	sub-0025951
32    	sub-0025952
33    	sub-0025953
34    	sub-0025954
35    	sub-0025955
36    	sub-0025956
37    	sub-0025957
38    	sub-0025958
39		sub-0025959
40    	sub-0025960
41    	sub-0025961
42    	sub-0025962
43    	sub-0025963
44    	sub-0025964
45    	sub-0025965
46    	sub-0025966
47    	sub-0025967
48    	sub-0025968
49		sub-0025969
50    	sub-0025970
51    	sub-0025971
52    	sub-0025972
53    	sub-0025973
54    	sub-0025974
55    	sub-0025975
56    	sub-0025976
57    	sub-0025977
58    	sub-0025978
59		sub-0025979
60    	sub-0025980
61    	sub-0025981
======	==============================





