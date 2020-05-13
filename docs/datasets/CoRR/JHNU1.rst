.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
JHNU1
******************


Overview
-----------

JHNU - Jinling Hospital, Nanjing University (Lu, Zhang)

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/jhnu_1.html for the website of the original dataset




All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/


**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/JHNU_bids/JHNU_bids-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/JHNU_bids/JHNU_bids-m2g-func-04-15-20 .``

    


Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/JHNU_bids/JHNU_bids-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/JHNU_bids/JHNU_bids-m2g-func-04-15-20/sub-0025599 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0025599
2    	sub-0025600
3    	sub-0025601
4    	sub-0025602
5    	sub-0025603
6    	sub-0025604
7    	sub-0025605
8    	sub-0025606
9		sub-0025607
10    	sub-0025608
11    	sub-0025609
12    	sub-0025610
13    	sub-0025611
14    	sub-0025612
15    	sub-0025613
16    	sub-0025614
17    	sub-0025615
18    	sub-0025616
19		sub-0025617
20    	sub-0025618
21    	sub-0025619
22    	sub-0025620
23    	sub-0025621
24    	sub-0025622
25    	sub-0025623
26    	sub-0025624
27    	sub-0025625
28    	sub-0025626
29		sub-0025627
30    	sub-0025628
======	==============================
