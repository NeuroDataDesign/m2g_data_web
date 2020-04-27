.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
SWU4
******************


Overview
-----------

SWU 4 - Southwest University

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/swu_4.html for the website of the original dataset

**Sample Connectome** from sub-0025866_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png


.. image:: ../../_static/connectomic_pic/BNU1-sub-0025866_ses-1_dwi_desikan_space-MNI152NLin6_res-2x2x2_connectome.png
	:width: 400
	:align: center


All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Diffusion MRI result**::

	aws s3 sync --no-sign-request s3://ndmg-data/SWU4/SWU4-2-8-20-m2g_staging-native-csa-det <your_local_direction>
	
example: aws s3 sync --no-sign-request s3://ndmg-data/SWU4/SWU4-2-8-20-m2g_staging-native-csa-det .




Single Sample Download Instructions
----------------------------------------



**Diffusion MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/SWU4/SWU4-2-8-20-m2g_staging-native-csa-det/<subject_number> <your_local_direction>

example: aws s3 sync --no-sign-request s3://ndmg-data/SWU4/SWU4-2-8-20-m2g_staging-native-csa-det/sub-0025864 .

======	==============================
order	subject_number
======	==============================
1    	sub-0025629
2    	sub-0025630
3    	sub-0025631
4    	sub-0025632
5    	sub-0025633
6    	sub-0025634
7    	sub-0025636
8    	sub-0025637
9		sub-0025638
10    	sub-0025639
11    	sub-0025640
12    	sub-0025641
13    	sub-0025642
14    	sub-0025643
15    	sub-0025644
16    	sub-0025645
17    	sub-0025646
18    	sub-0025647
19		sub-0025648
20    	sub-0025649
21    	sub-0025650
22    	sub-0025651
23    	sub-0025652
24    	sub-0025653
25    	sub-0025655
26    	sub-0025656
27    	sub-0025657
28    	sub-0025659
29		sub-0025660
30    	sub-0025662
31    	sub-0025663
32    	sub-0025664
33    	sub-0025665
34    	sub-0025667
35    	sub-0025668
36    	sub-0025669
37    	sub-0025670
38    	sub-0025671
39		sub-0025672
40    	sub-0025673
41    	sub-0025674
42    	sub-0025676
43    	sub-0025677
44    	sub-0025678
45    	sub-0025679
46    	sub-0025680
47    	sub-0025681
48    	sub-0025682
49		sub-0025683
50    	sub-0025685
51    	sub-0025686
52    	sub-0025687
53    	sub-0025688
54    	sub-0025689
55    	sub-0025690
56    	sub-0025691
57    	sub-0025692
58    	sub-0025693
59		sub-0025694
60    	sub-0025695
61    	sub-0025696
62    	sub-0025697
63    	sub-0025698
64    	sub-0025699
65    	sub-0025700
66    	sub-0025701
67    	sub-0025702
68    	sub-0025703
69		sub-0025704
70    	sub-0025705
71    	sub-0025706
72    	sub-0025707
73    	sub-0025708
74    	sub-0025709
75    	sub-0025710
76    	sub-0025711
77    	sub-0025712
78    	sub-0025713
79		sub-0025714
80    	sub-0025715
81    	sub-0025716
82    	sub-0025717
83    	sub-0025718
84    	sub-0025719
85    	sub-0025720
86    	sub-0025721
87    	sub-0025722
88    	sub-0025723
89		sub-0025724
90    	sub-0025725
91    	sub-0025726
92    	sub-0025727
93    	sub-0025728
94    	sub-0025729
95    	sub-0025730
96    	sub-0025731
97    	sub-0025732
98    	sub-0025733
99		sub-0025734
100    	sub-0025735
101    	sub-0025736
102    	sub-0025737
103    	sub-0025738
104    	sub-0025739
105    	sub-0025740
106    	sub-0025741
107    	sub-0025742
108    	sub-0025743
109		sub-0025744
110    	sub-0025745
111    	sub-0025747
112    	sub-0025748
113    	sub-0025749
114    	sub-0025750
115    	sub-0025751
116    	sub-0025752
117    	sub-0025753
118    	sub-0025756
119		sub-0025757
120    	sub-0025758
121    	sub-0025759
122    	sub-0025760
123    	sub-0025761
124    	sub-0025762
125    	sub-0025763
126    	sub-0025764
127    	sub-0025765
128    	sub-0025766
129		sub-0025767
130    	sub-0025768
131    	sub-0025769
132    	sub-0025770
133    	sub-0025771
134    	sub-0025772
135    	sub-0025773
136    	sub-0025774
137    	sub-0025775
138    	sub-0025776
139		sub-0025778
140    	sub-0025779
141    	sub-0025780
142    	sub-0025781
143    	sub-0025782
144    	sub-0025783
145    	sub-0025784
146    	sub-0025785
147    	sub-0025786
148    	sub-0025787
149		sub-0025788
150    	sub-0025794
151    	sub-0025795
152    	sub-0025796
153    	sub-0025797
154    	sub-0025798
155    	sub-0025799
156    	sub-0025800
157    	sub-0025801
158    	sub-0025802
159		sub-0025803
160    	sub-0025804
161    	sub-0025805
162    	sub-0025806
163    	sub-0025807
164    	sub-0025808
165    	sub-0025809
166    	sub-0025810
167    	sub-0025811
168    	sub-0025812
169		sub-0025813
170    	sub-0025814
171    	sub-0025815
172    	sub-0025816
173    	sub-0025817
174    	sub-0025819
175    	sub-0025820
176    	sub-0025821
177    	sub-0025822
178    	sub-0025823
179		sub-0025824
180    	sub-0025825
181    	sub-0025826
182    	sub-0025827
183    	sub-0025828
184    	sub-0025829
185    	sub-0025830
186    	sub-0025831
187    	sub-0025832
188    	sub-0025833
189		sub-0025834
190    	sub-0025835
191    	sub-0025836
192    	sub-0025837
193    	sub-0025838
194    	sub-0025840
195    	sub-0025841
196    	sub-0025842
197    	sub-0025843
198    	sub-0025844
199		sub-0025845
200    	sub-0025846
201    	sub-0025847
202    	sub-0025849
203    	sub-0025850
204    	sub-0025851
205    	sub-0025852
206    	sub-0025853
207    	sub-0025854
208    	sub-0025855
209		sub-0025856
210    	sub-0025857
211    	sub-0025858
212    	sub-0025859
213    	sub-0025860
214    	sub-0025861
215    	sub-0025862
216    	sub-0025863
======	==============================