.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
HNU1
******************



Overview
-----------

Connectivity-based Brain Imaging Research Database (C-BIRD) at HNU

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/hnu_1.html for the website of the original dataset

**Sample Connectome** from sub-0025431_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png


.. image:: ../../_static/connectomic_pic/HUN1-sub-0025431_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png
	:width: 400
	:align: center



All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



Diffusion MRI result::

	aws s3 sync --no-sign-request s3://ndmg-data/HNU1/HNU1-2-8-20-m2g_staging-native-csa-det




Single Sample Download Instructions
----------------------------------------


**Diffusion MRI single sample**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


sub-0025427   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025427

sub-0025428   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025428
	
sub-0025429   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025429
	
sub-0025430   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025430
	
sub-0025431   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025431

sub-0025432   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025432
	
sub-0025433   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025433
	
sub-0025434   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025434
	
sub-0025435   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025435

sub-0025436   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025436
	
sub-0025437  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025437
	
sub-0025438   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025438
		
sub-0025439  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025439
	
sub-0025440   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025440
	
sub-0025441   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025441

sub-0025442   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025442
	
sub-0025443   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025443
	
sub-0025444   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025444
	
sub-0025445   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025445

sub-0025446   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025446
	
sub-0025447  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025447
	
sub-0025448   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025448
		
sub-0025449  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025449
		
sub-0025450   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025450
	
sub-0025451   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025451

sub-0025452   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025452
	
sub-0025453   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025453
	
sub-0025454   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025454
	
sub-0025455   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025455

sub-0025456   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025456
	