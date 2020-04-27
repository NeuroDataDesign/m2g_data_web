.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
IPCAS2
******************


Overview
-----------

IPCAS - Institute of Psychology, Chinese Academy of Sciences

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/ipcas_2.html for the website of the original dataset




All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/




**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_2/IPCAS_2-m2g-func-04-15-20 <your_local_direction>
	
example: aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_2/IPCAS_2-m2g-func-04-15-20 .



Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_2/IPCAS_2-m2g-func-04-15-20/<subject_number> <your_local_direction>

example: aws s3 sync --no-sign-request s3://ndmg-data/IPCAS_2/IPCAS_2-m2g-func-04-15-20/sub-0025515 .


======	==============================
order	subject_number
======	==============================
1    	sub-0025515
2    	sub-0025516
3    	sub-0025517
4    	sub-0025518
5    	sub-0025519
6    	sub-0025520
7    	sub-0025521
8    	sub-0025522
9		sub-0025523
10    	sub-0025524
11    	sub-0025525
12    	sub-0025526
13    	sub-0025527
14    	sub-0025528
15    	sub-0025529
16    	sub-0025530
17    	sub-0025531
18    	sub-0025532
19		sub-0025533
20    	sub-0025534
21    	sub-0025535
22    	sub-0025536
23    	sub-0025537
24    	sub-0025538
25    	sub-0025539
26    	sub-0025540
27    	sub-0025541
28    	sub-0025542
29		sub-0025543
30    	sub-0025544
31    	sub-0025545
32    	sub-0025546
33    	sub-0025547
34    	sub-0025548
35    	sub-0025549
======	==============================


