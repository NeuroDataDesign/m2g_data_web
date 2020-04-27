.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
BNU1
******************


Overview
-----------

Connectivity-based Brain Imaging Research Database (C-BIRD) at BNU

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/bnu_1.html for the website of the original dataset

**Sample Connectome** from sub-0025866_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png


.. image:: ../../_static/connectomic_pic/BNU1-sub-0025866_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png
	:width: 400
	:align: center


All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



Diffusion MRI result::

	aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det .
	
	
Functional MRI result::


    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20 <your local direction>
	
	example: aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20 .



Single Sample Download Instructions
----------------------------------------


**Diffusion MRI single sample**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

sub-0025864   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025864 .
    
sub-0025865   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025865 .
    
sub-0025866   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025866 .
	
sub-0025867   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025867 .
    
sub-0025868   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025868 .
    
sub-0025869   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025869 .
	
sub-0025870  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025870 .
    
sub-0025871   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025871 .
    
sub-0025872   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025872 .
	
sub-0025873   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025873 .
    
sub-0025874   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025874 .
    
sub-0025875   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025875 .
	
sub-0025876   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025876 .
    
sub-0025877   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025877 .
    
sub-0025878   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025878 .
		
sub-0025879  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025879 .
    
sub-0025880   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025880 .
    
sub-0025881   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025881 .
	
sub-0025882   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025882 .
    
sub-0025883   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025883 .
    
sub-0025884   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025884 .
	
sub-0025885   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025885 .
    
sub-0025886   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025886 .
    
sub-0025887   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025887 .
		
sub-0025888  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025888 .
    
sub-0025889   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025889 .
    
sub-0025890   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025890 .
	
sub-0025891   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025891 .
    
sub-0025892   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025892 .
    
sub-0025893   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025893 .
	
sub-0025894   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025894 .
    
sub-0025895   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025895 .
    
sub-0025896   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025896 .
	    
sub-0025897   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025897 .
	
sub-0025898   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025898 .
    
sub-0025899   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025899 .
    
sub-0025900   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025900 .
	    
sub-0025901   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025901 .
	    
sub-0025902   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025902 .
	    
sub-0025903   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025903 .
	    
sub-0025904   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025904 .
	    
sub-0025905   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025905 .
	    
sub-0025906   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025906 .
	    
sub-0025907   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025907 .
	    
sub-0025908   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025908 .
	    
sub-0025909   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025909 .
		    
sub-0025910   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025910 .
			    
sub-0025911   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025911 .
			    
sub-0025912   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025912 .
			    
sub-0025913   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025913 .
			    
sub-0025914   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025914 .
			    
sub-0025915   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025915 .
			    
sub-0025916   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025916 .
			    
sub-0025917   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025917 .
			    
sub-0025918   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025918 .
			    
sub-0025919   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025919 .
			    
sub-0025920   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-2-8-20-m2g_staging-native-csa-det/sub-0025920 .
    	

**Functional MRI single sample**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


sub-0025864   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025864 .
    
sub-0025865   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025865 .
    
sub-0025866   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025866 .
	
sub-0025867   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025867 .
    
sub-0025868   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025868 .
    
sub-0025869   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025869 .
	
sub-0025870  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025870 .
    
sub-0025871   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025871 .
    
sub-0025872   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025872 .
	
sub-0025873   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025873 .
    
sub-0025874   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025874 .
    
sub-0025875   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025875 .
	
sub-0025876   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025876 .
    
sub-0025877   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025877 .
    
sub-0025878   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025878 .
		
sub-0025879  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025879 .
    
sub-0025880   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025880 .
    
sub-0025881   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025881 .
	
sub-0025882   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025882 .
    
sub-0025883   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025883 .
    
sub-0025884   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025884 .
	
sub-0025885   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025885 .
    
sub-0025886   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025886 .
    
sub-0025887   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025887 .
		
sub-0025888  ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025888 .
    
sub-0025889   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025889 .
    
sub-0025890   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025890 .
	
sub-0025891   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025891 .
    
sub-0025892   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025892 .
    
sub-0025893   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025893 .
	
sub-0025894   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025894 .
    
sub-0025895   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025895 .
    
sub-0025896   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025896 .
	    
sub-0025897   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025897 .
	
sub-0025898   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025898 .
    
sub-0025899   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025899 .
    
sub-0025900   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025900 .
	    
sub-0025901   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025901 .
	    
sub-0025902   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025902 .
	    
sub-0025903   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025903 .
	    
sub-0025904   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025904 .
	    
sub-0025905   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025905 .
	    
sub-0025906   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025906 .
	    
sub-0025907   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025907 .
	    
sub-0025908   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025908 .
	    
sub-0025909   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025909 .
		    
sub-0025910   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025910 .
			    
sub-0025911   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025911 .
			    
sub-0025912   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025912 .
			    
sub-0025913   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025913 .
			    
sub-0025914   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025914 .
			    
sub-0025915   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025915 .
			    
sub-0025916   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025916 .
			    
sub-0025917   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025917 .
			    
sub-0025918   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025918 .
			    
sub-0025919   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025919 .
			    
sub-0025920   ::
    
    aws s3 sync --no-sign-request s3://ndmg-data/BNU1/BNU1-m2g-func-04-15-20/sub-0025920 .
    	
