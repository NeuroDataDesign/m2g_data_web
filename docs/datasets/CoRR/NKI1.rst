.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
NKI1
******************


Overview
-----------

NKI - Nathan Kline Institute (Milham, Colcombe)

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/nki_1.html for the website of the original dataset


**Sample Connectome** from sub-0021006_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png


.. image:: ../../_static/connectomic_pic/NKI1-sub-0021006_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png
	:width: 400
	:align: center


All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



Diffusion MRI result::

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det .



Single Sample Download Instructions
----------------------------------------


**Diffusion MRI single sample**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


sub-0021001   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-0021001 .

sub-0021002   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-0021002 .

sub-0021006   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-0021006 .

sub-0021018   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-0021018 .

sub-0021024   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-0021024 .

sub-1793622   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-1793622 .

sub-1961098   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-1961098 .

sub-2475376   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-2475376 .

sub-2842950   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-2842950 .

sub-3201815   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-3201815 .

sub-3313349   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-3313349 .

sub-3315657   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-3315657 .

sub-3795193   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-3795193 .

sub-3808535   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-3808535 .

sub-4176156   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-4176156 .

sub-7055197   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-7055197 .

sub-8735778   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-8735778 .

sub-9630905   ::	

	aws s3 sync --no-sign-request s3://ndmg-data/NKI1/NKI1-2-8-20-m2g_staging-native-csa-det/sub-9630905 .



=== ======== ==========
ID  名称     地址
=== ======== ==========
1   张三     未填写
2   李四     未填写
=== ======== ==========
   