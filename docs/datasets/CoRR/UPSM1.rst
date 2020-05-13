.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
UPSM1
******************


Overview
-----------

UPSM - University of Pittsburgh School of Medicine

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/upsm_1.html for the website of the original dataset

All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/UPSM_1/UPSM_1-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/UPSM_1/UPSM_1-m2g-func-04-15-20 .``




Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/UPSM_1/UPSM_1-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/UPSM_1/UPSM_1-m2g-func-04-15-20/sub-0025234 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0025234
2    	sub-0025235
3    	sub-0025236
4    	sub-0025237
5    	sub-0025238
6    	sub-0025239
7    	sub-0025240
8    	sub-0025241
9		sub-0025242
10    	sub-0025243
11    	sub-0025244
12    	sub-0025245
13    	sub-0025246
14    	sub-0025247
15    	sub-0025248
16    	sub-0025249
17    	sub-0025250
18    	sub-0025251
19		sub-0025252
20    	sub-0025253
21    	sub-0025254
22    	sub-0025255
23    	sub-0025256
24    	sub-0025257
25    	sub-0025258
26    	sub-0025259
27    	sub-0025260
28    	sub-0025261
29		sub-0025262
30    	sub-0025263
31    	sub-0025264
32    	sub-0025265
33    	sub-0025266
34    	sub-0025267
35    	sub-0025268
36    	sub-0025269
37    	sub-0025270
38    	sub-0025271
39		sub-0025272
40    	sub-0025273
41    	sub-0025274
42    	sub-0025275
43    	sub-0025276
44    	sub-0025277
45    	sub-0025278
46    	sub-0025279
47    	sub-0025280
48    	sub-0025281
49		sub-0025282
50    	sub-0025283
51    	sub-0025284
52    	sub-0025285
53    	sub-0025286
54    	sub-0025287
55    	sub-0025288
56    	sub-0025289
57    	sub-0025290
58    	sub-0025291
59		sub-0025292
60    	sub-0025293
61    	sub-0025294
62    	sub-0025295
63    	sub-0025296
64    	sub-0025297
65    	sub-0025298
66    	sub-0025299
67    	sub-0025300
68    	sub-0025301
69		sub-0025302
70    	sub-0025303
71    	sub-0025304
72    	sub-0025305
73    	sub-0025306
74    	sub-0025307
75    	sub-0025308
76    	sub-0025309
77    	sub-0025310
78    	sub-0025311
79		sub-0025312
80    	sub-0025313
81    	sub-0025314
82    	sub-0025315
83    	sub-0025316
84    	sub-0025317
85    	sub-0025318
86    	sub-0025319
87    	sub-0025320
88    	sub-0025321
89		sub-0025322
90    	sub-0025323
91    	sub-0025324
92    	sub-0025325
93    	sub-0025326
94    	sub-0025327
95    	sub-0025328
96    	sub-0025329
97    	sub-0025330
99		sub-0025332
100    	sub-0025333
======	==============================