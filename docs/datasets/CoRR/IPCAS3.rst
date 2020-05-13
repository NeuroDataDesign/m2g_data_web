.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
IPCAS3
******************


Overview
-----------

IPCAS - Institute of Psychology, Chinese Academy of Sciences


See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/ipcas_3.html for the website of the original dataset



All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS3/IPCAS3-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IPCAS3/IPCAS3-m2g-func-04-15-20 .``





Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/IPCAS3/IPCAS3-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/IPCAS3/IPCAS3-m2g-func-04-15-20/sub-0025550 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0025550
2    	sub-0025551
3    	sub-0025552
4    	sub-0025553
5    	sub-0025554
6    	sub-0025555
7    	sub-0025556
8    	sub-0025557
9		sub-0025558
10    	sub-0025559
11    	sub-0025560
12    	sub-0025561
13    	sub-0025562
14    	sub-0025563
15    	sub-0025564
16    	sub-0025565
17    	sub-0025566
18    	sub-0025567
19		sub-0025568
20    	sub-0025569
21    	sub-0025570
22    	sub-0025571
23    	sub-0025572
24    	sub-0025573
25    	sub-0025574
26    	sub-0025575
27    	sub-0025576
28    	sub-0025577
29		sub-0025578
30    	sub-0025579
31    	sub-0025580
32    	sub-0025581
33    	sub-0025582
34    	sub-0025583
35    	sub-0025584
36    	sub-0025585
======	==============================

