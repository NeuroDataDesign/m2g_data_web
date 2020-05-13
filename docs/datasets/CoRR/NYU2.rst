.. m2g_data documentation master file, created by
   sphinx-quickstart on Tue Mar 10 15:24:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

******************
NYU2
******************


Overview
-----------

NYU Institute for Pediatric Neuroscience Sample

See http://fcon_1000.projects.nitrc.org/indi/CoRR/html/nyu_2.html for the website of the original dataset



All Data Download Instructions
-------------------------------------

Download from S3

The most recently published snapshot can be downloaded from S3. This method is best for larger datasets or unstable connections. This example uses AWS CLI: https://aws.amazon.com/cli/?nc1=h_ls/



**Functional MRI result**::


    aws s3 sync --no-sign-request s3://ndmg-data/NYU_2/NYU_2-m2g-func-04-15-20 <your_local_direction>
	
Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/NYU_2/NYU_2-m2g-func-04-15-20 .``




Single Sample Download Instructions
----------------------------------------


**Functional MRI single sample**::
    
    aws s3 sync --no-sign-request s3://ndmg-data/NYU_2/NYU_2-m2g-func-04-15-20/<subject_number> <your_local_direction>

Example: 

``aws s3 sync --no-sign-request s3://ndmg-data/NYU_2/NYU_2-m2g-func-04-15-20/sub-0025000 .``


======	==============================
index	subject_number
======	==============================
1    	sub-0025000
2    	sub-0025001
3    	sub-0025002
4    	sub-0025003
5    	sub-0025004
6    	sub-0025005
7    	sub-0025006
8    	sub-0025007
9		sub-0025008
10    	sub-0025009
11    	sub-0025010
12    	sub-0025011
13    	sub-0025012
14    	sub-0025013
15    	sub-0025014
16    	sub-0025015
17    	sub-0025016
18    	sub-0025017
19		sub-0025018
20    	sub-0025019
21    	sub-0025020
22    	sub-0025021
23    	sub-0025022
24    	sub-0025023
25    	sub-0025024
26    	sub-0025025
27    	sub-0025026
28    	sub-0025027
29		sub-0025028
30    	sub-0025029
31    	sub-0025030
32    	sub-0025031
33    	sub-0025032
34    	sub-0025033
35    	sub-0025034
36    	sub-0025035
37    	sub-0025036
38    	sub-0025037
39		sub-0025038
40    	sub-0025039
41    	sub-0025040
42    	sub-0025041
43    	sub-0025042
44    	sub-0025043
45    	sub-0025044
46    	sub-0025045
47    	sub-0025046
48    	sub-0025047
49		sub-0025048
50    	sub-0025049
51    	sub-0025050
52    	sub-0025051
53    	sub-0025052
54    	sub-0025053
55    	sub-0025054
56    	sub-0025055
57    	sub-0025056
58    	sub-0025057
59		sub-0025058
60    	sub-0025059
61    	sub-0025060
62    	sub-0025061
63    	sub-0025062
64    	sub-0025063
65    	sub-0025064
66    	sub-0025065
67    	sub-0025066
68    	sub-0025067
69		sub-0025068
70    	sub-0025069
71    	sub-0025070
72    	sub-0025071
73    	sub-0025072
74    	sub-0025073
75    	sub-0025074
76    	sub-0025075
77    	sub-0025076
78    	sub-0025077
79		sub-0025078
80    	sub-0025079
81    	sub-0025080
82    	sub-0025081
83    	sub-0025082
84    	sub-0025083
85    	sub-0025084
86    	sub-0025085
87    	sub-0025086
88    	sub-0025087
89		sub-0025088
90    	sub-0025089
91    	sub-0025090
92    	sub-0025091
93    	sub-0025092
94    	sub-0025093
95    	sub-0025094
96    	sub-0025095
97    	sub-0025096
98    	sub-0025097
99		sub-0025098
100    	sub-0025099
101    	sub-0025100
102    	sub-0025101
103    	sub-0025102
104    	sub-0025103
105    	sub-0025104
106    	sub-0025105
107    	sub-0025106
108    	sub-0025107
109		sub-0025108
110    	sub-0025109
111    	sub-0025110
112    	sub-0025111
113    	sub-0025112
114    	sub-0025113
115    	sub-0025114
116    	sub-0025115
117    	sub-0025116
118    	sub-0025117
119		sub-0025118
120    	sub-0025119
121    	sub-0025120
122    	sub-0025121
123    	sub-0025122
124    	sub-0025123
125    	sub-0025124
126    	sub-0025125
127    	sub-0025126
128    	sub-0025127
129		sub-0025128
130    	sub-0025129
131    	sub-0025130
132    	sub-0025131
133    	sub-0025132
134    	sub-0025133
135    	sub-0025134
136    	sub-0025135
137    	sub-0025136
138    	sub-0025137
139		sub-0025138
140    	sub-0025139
141    	sub-0025140
142    	sub-0025141
143    	sub-0025142
144    	sub-0025143
145    	sub-0025144
146    	sub-0025145
147    	sub-0025146
148    	sub-0025147
149		sub-0025148
150    	sub-0025149
151    	sub-0025150
152    	sub-0025151
153    	sub-0025152
154    	sub-0025153
155    	sub-0025154
156    	sub-0025155
157    	sub-0025156
158    	sub-0025157
159		sub-0025158
160    	sub-0025159
161    	sub-0025160
162    	sub-0025161
163    	sub-0025162
164    	sub-0025163
165    	sub-0025164
166    	sub-0025165
167    	sub-0025166
168    	sub-0025167
169		sub-0025168
170    	sub-0025169
171    	sub-0025170
172    	sub-0025171
173    	sub-0025172
174    	sub-0025173
175    	sub-0025174
176    	sub-0025175
177    	sub-0025176
178    	sub-0025177
179		sub-0025178
180    	sub-0025179
181    	sub-0025180
182    	sub-0025181
183    	sub-0025182
184    	sub-0025183
185    	sub-0025184
186    	sub-0025185
187    	sub-0025186
======	==============================