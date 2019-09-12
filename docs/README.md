<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>

<a href="./mdf">Model artifacts</a>

# ctn-model
Location for CRDC Clinical Trial Node model description files and related artifacts

# Description

This repo is a workspace for development of the data model for the [Cancer Research Data Commons](https://datascience.cancer.gov/data-commons) Clinical Trial Node. 

The files are created in [Model Description Format](https://github.com/CBIIT/icdc-model-tool#model-description-files-mdf) and can be visualized using [model-tool](https://github.com/CBIIT/icdc-model-tool#makemodel-and-model-tool).

<div id='graph' style='display:off;'>
<svg width="2034pt" height="903pt"
 viewBox="0.00 0.00 2033.50 903.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 899)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-899 2029.5,-899 2029.5,4 -4,4"/>
<!-- stratification -->
<g id="node1" class="node">
<title>stratification</title>
<path fill="none" stroke="#000000" d="M12,-676C12,-676 424,-676 424,-676 430,-676 436,-682 436,-688 436,-688 436,-802 436,-802 436,-808 430,-814 424,-814 424,-814 12,-814 12,-814 6,-814 0,-808 0,-802 0,-802 0,-688 0,-688 0,-682 6,-676 12,-676"/>
<text text-anchor="middle" x="55" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification</text>
<polyline fill="none" stroke="#000000" points="110,-676 110,-814 "/>
<text text-anchor="middle" x="120.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="131,-676 131,-814 "/>
<text text-anchor="middle" x="273" y="-798.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_radiotherapy</text>
<polyline fill="none" stroke="#000000" points="131,-791 415,-791 "/>
<text text-anchor="middle" x="273" y="-775.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status_stratification</text>
<polyline fill="none" stroke="#000000" points="131,-768 415,-768 "/>
<text text-anchor="middle" x="273" y="-752.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_chemotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="131,-745 415,-745 "/>
<text text-anchor="middle" x="273" y="-729.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_stratification</text>
<polyline fill="none" stroke="#000000" points="131,-722 415,-722 "/>
<text text-anchor="middle" x="273" y="-706.8" font-family="Times,serif" font-size="14.00" fill="#000000">grouped_recurrence_score</text>
<polyline fill="none" stroke="#000000" points="131,-699 415,-699 "/>
<text text-anchor="middle" x="273" y="-683.8" font-family="Times,serif" font-size="14.00" fill="#000000">combined_stratification_variable</text>
<polyline fill="none" stroke="#000000" points="415,-676 415,-814 "/>
<text text-anchor="middle" x="425.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case -->
<g id="node5" class="node">
<title>case</title>
<path fill="none" stroke="#000000" d="M929,-428.5C929,-428.5 1185,-428.5 1185,-428.5 1191,-428.5 1197,-434.5 1197,-440.5 1197,-440.5 1197,-531.5 1197,-531.5 1197,-537.5 1191,-543.5 1185,-543.5 1185,-543.5 929,-543.5 929,-543.5 923,-543.5 917,-537.5 917,-531.5 917,-531.5 917,-440.5 917,-440.5 917,-434.5 923,-428.5 929,-428.5"/>
<text text-anchor="middle" x="941.5" y="-482.3" font-family="Times,serif" font-size="14.00" fill="#000000">case</text>
<polyline fill="none" stroke="#000000" points="966,-428.5 966,-543.5 "/>
<text text-anchor="middle" x="976.5" y="-482.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="987,-428.5 987,-543.5 "/>
<text text-anchor="middle" x="1081.5" y="-528.3" font-family="Times,serif" font-size="14.00" fill="#000000">included_in_analysis</text>
<polyline fill="none" stroke="#000000" points="987,-520.5 1176,-520.5 "/>
<text text-anchor="middle" x="1081.5" y="-505.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_id</text>
<polyline fill="none" stroke="#000000" points="987,-497.5 1176,-497.5 "/>
<text text-anchor="middle" x="1081.5" y="-482.3" font-family="Times,serif" font-size="14.00" fill="#000000">case_id</text>
<polyline fill="none" stroke="#000000" points="987,-474.5 1176,-474.5 "/>
<text text-anchor="middle" x="1081.5" y="-459.3" font-family="Times,serif" font-size="14.00" fill="#000000">on_study_crf_submitted</text>
<polyline fill="none" stroke="#000000" points="987,-451.5 1176,-451.5 "/>
<text text-anchor="middle" x="1081.5" y="-436.3" font-family="Times,serif" font-size="14.00" fill="#000000">ineligible</text>
<polyline fill="none" stroke="#000000" points="1176,-428.5 1176,-543.5 "/>
<text text-anchor="middle" x="1186.5" y="-482.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- stratification&#45;&gt;case -->
<g id="edge3" class="edge">
<title>stratification&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M304.1565,-675.9926C344.7306,-646.7691 395.1032,-614.9347 445,-595 595.3909,-534.9161 779.7555,-507.8191 906.5899,-495.6816"/>
<polygon fill="#000000" stroke="#000000" points="907.1362,-499.1458 916.766,-494.7281 906.4831,-492.1764 907.1362,-499.1458"/>
<text text-anchor="middle" x="568" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- demographic -->
<g id="node2" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M466,-699C466,-699 802,-699 802,-699 808,-699 814,-705 814,-711 814,-711 814,-779 814,-779 814,-785 808,-791 802,-791 802,-791 466,-791 466,-791 460,-791 454,-785 454,-779 454,-779 454,-711 454,-711 454,-705 460,-699 466,-699"/>
<text text-anchor="middle" x="509" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="564,-699 564,-791 "/>
<text text-anchor="middle" x="574.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="585,-699 585,-791 "/>
<text text-anchor="middle" x="689" y="-775.8" font-family="Times,serif" font-size="14.00" fill="#000000">patient_age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="585,-768 793,-768 "/>
<text text-anchor="middle" x="689" y="-752.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status</text>
<polyline fill="none" stroke="#000000" points="585,-745 793,-745 "/>
<text text-anchor="middle" x="689" y="-729.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="585,-722 793,-722 "/>
<text text-anchor="middle" x="689" y="-706.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="793,-699 793,-791 "/>
<text text-anchor="middle" x="803.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;case -->
<g id="edge1" class="edge">
<title>demographic&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M685.3066,-698.8211C721.9997,-667.1955 773.4627,-625.6032 823,-595 850.2967,-578.1366 880.6272,-562.1803 910.1596,-547.9426"/>
<polygon fill="#000000" stroke="#000000" points="911.7793,-551.0478 919.2949,-543.5801 908.7628,-544.7311 911.7793,-551.0478"/>
<text text-anchor="middle" x="906" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- treatment -->
<g id="node3" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M844.5,-641.5C844.5,-641.5 1269.5,-641.5 1269.5,-641.5 1275.5,-641.5 1281.5,-647.5 1281.5,-653.5 1281.5,-653.5 1281.5,-836.5 1281.5,-836.5 1281.5,-842.5 1275.5,-848.5 1269.5,-848.5 1269.5,-848.5 844.5,-848.5 844.5,-848.5 838.5,-848.5 832.5,-842.5 832.5,-836.5 832.5,-836.5 832.5,-653.5 832.5,-653.5 832.5,-647.5 838.5,-641.5 844.5,-641.5"/>
<text text-anchor="middle" x="877" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="921.5,-641.5 921.5,-848.5 "/>
<text text-anchor="middle" x="932" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="942.5,-641.5 942.5,-848.5 "/>
<text text-anchor="middle" x="1101.5" y="-833.3" font-family="Times,serif" font-size="14.00" fill="#000000">endocrine_therapy_discontinued</text>
<polyline fill="none" stroke="#000000" points="942.5,-825.5 1260.5,-825.5 "/>
<text text-anchor="middle" x="1101.5" y="-810.3" font-family="Times,serif" font-size="14.00" fill="#000000">duration_of_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="942.5,-802.5 1260.5,-802.5 "/>
<text text-anchor="middle" x="1101.5" y="-787.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_surgical_procedure</text>
<polyline fill="none" stroke="#000000" points="942.5,-779.5 1260.5,-779.5 "/>
<text text-anchor="middle" x="1101.5" y="-764.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_last_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="942.5,-756.5 1260.5,-756.5 "/>
<text text-anchor="middle" x="1101.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_first_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="942.5,-733.5 1260.5,-733.5 "/>
<text text-anchor="middle" x="1101.5" y="-718.3" font-family="Times,serif" font-size="14.00" fill="#000000">specific_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="942.5,-710.5 1260.5,-710.5 "/>
<text text-anchor="middle" x="1101.5" y="-695.3" font-family="Times,serif" font-size="14.00" fill="#000000">received_chemotherapy</text>
<polyline fill="none" stroke="#000000" points="942.5,-687.5 1260.5,-687.5 "/>
<text text-anchor="middle" x="1101.5" y="-672.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="942.5,-664.5 1260.5,-664.5 "/>
<text text-anchor="middle" x="1101.5" y="-649.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_endocrine_therapy_received</text>
<polyline fill="none" stroke="#000000" points="1260.5,-641.5 1260.5,-848.5 "/>
<text text-anchor="middle" x="1271" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;case -->
<g id="edge4" class="edge">
<title>treatment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1057,-641.1471C1057,-611.8261 1057,-580.6777 1057,-554.0443"/>
<polygon fill="#000000" stroke="#000000" points="1060.5001,-553.6916 1057,-543.6916 1053.5001,-553.6916 1060.5001,-553.6916"/>
<text text-anchor="middle" x="1084" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- study_arm -->
<g id="node4" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M877.5,-242.5C877.5,-242.5 1032.5,-242.5 1032.5,-242.5 1038.5,-242.5 1044.5,-248.5 1044.5,-254.5 1044.5,-254.5 1044.5,-266.5 1044.5,-266.5 1044.5,-272.5 1038.5,-278.5 1032.5,-278.5 1032.5,-278.5 877.5,-278.5 877.5,-278.5 871.5,-278.5 865.5,-272.5 865.5,-266.5 865.5,-266.5 865.5,-254.5 865.5,-254.5 865.5,-248.5 871.5,-242.5 877.5,-242.5"/>
<text text-anchor="middle" x="911.5" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="957.5,-242.5 957.5,-278.5 "/>
<text text-anchor="middle" x="968" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="978.5,-242.5 978.5,-278.5 "/>
<text text-anchor="middle" x="1001" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000">arm</text>
<polyline fill="none" stroke="#000000" points="1023.5,-242.5 1023.5,-278.5 "/>
<text text-anchor="middle" x="1034" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M941,-98.5C941,-98.5 1221,-98.5 1221,-98.5 1227,-98.5 1233,-104.5 1233,-110.5 1233,-110.5 1233,-178.5 1233,-178.5 1233,-184.5 1227,-190.5 1221,-190.5 1221,-190.5 941,-190.5 941,-190.5 935,-190.5 929,-184.5 929,-178.5 929,-178.5 929,-110.5 929,-110.5 929,-104.5 935,-98.5 941,-98.5"/>
<text text-anchor="middle" x="957" y="-140.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="985,-98.5 985,-190.5 "/>
<text text-anchor="middle" x="995.5" y="-140.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1006,-98.5 1006,-190.5 "/>
<text text-anchor="middle" x="1109" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_designation</text>
<polyline fill="none" stroke="#000000" points="1006,-167.5 1212,-167.5 "/>
<text text-anchor="middle" x="1109" y="-152.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_description</text>
<polyline fill="none" stroke="#000000" points="1006,-144.5 1212,-144.5 "/>
<text text-anchor="middle" x="1109" y="-129.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_id</text>
<polyline fill="none" stroke="#000000" points="1006,-121.5 1212,-121.5 "/>
<text text-anchor="middle" x="1109" y="-106.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_name</text>
<polyline fill="none" stroke="#000000" points="1212,-98.5 1212,-190.5 "/>
<text text-anchor="middle" x="1222.5" y="-140.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M963.612,-242.0248C969.066,-231.5748 976.816,-218.6998 986,-209 989.7692,-205.0191 993.8249,-201.1492 998.062,-197.4124"/>
<polygon fill="#000000" stroke="#000000" points="1000.4738,-199.9569 1005.862,-190.8345 995.961,-194.6057 1000.4738,-199.9569"/>
<text text-anchor="middle" x="1026.5" y="-212.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- case&#45;&gt;study_arm -->
<g id="edge12" class="edge">
<title>case&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M916.9937,-444.7113C885.7494,-428.6968 856.4476,-406.7879 838,-377 827.0018,-359.2409 827.668,-348.1548 838,-330 849.859,-309.162 870.7019,-293.9235 891.5423,-283.1195"/>
<polygon fill="#000000" stroke="#000000" points="893.3183,-286.1471 900.765,-278.6107 890.2439,-279.8584 893.3183,-286.1471"/>
<text text-anchor="middle" x="878.5" y="-349.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort -->
<g id="node6" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M940.5,-330.5C940.5,-330.5 1173.5,-330.5 1173.5,-330.5 1179.5,-330.5 1185.5,-336.5 1185.5,-342.5 1185.5,-342.5 1185.5,-364.5 1185.5,-364.5 1185.5,-370.5 1179.5,-376.5 1173.5,-376.5 1173.5,-376.5 940.5,-376.5 940.5,-376.5 934.5,-376.5 928.5,-370.5 928.5,-364.5 928.5,-364.5 928.5,-342.5 928.5,-342.5 928.5,-336.5 934.5,-330.5 940.5,-330.5"/>
<text text-anchor="middle" x="960" y="-349.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="991.5,-330.5 991.5,-376.5 "/>
<text text-anchor="middle" x="1002" y="-349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1012.5,-330.5 1012.5,-376.5 "/>
<text text-anchor="middle" x="1088.5" y="-361.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1012.5,-353.5 1164.5,-353.5 "/>
<text text-anchor="middle" x="1088.5" y="-338.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_dose</text>
<polyline fill="none" stroke="#000000" points="1164.5,-330.5 1164.5,-376.5 "/>
<text text-anchor="middle" x="1175" y="-349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;cohort -->
<g id="edge6" class="edge">
<title>case&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M1057,-428.269C1057,-413.9945 1057,-399.1834 1057,-386.5462"/>
<polygon fill="#000000" stroke="#000000" points="1060.5001,-386.5017 1057,-376.5017 1053.5001,-386.5017 1060.5001,-386.5017"/>
<text text-anchor="middle" x="1097.5" y="-398.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- case&#45;&gt;study -->
<g id="edge10" class="edge">
<title>case&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1153.1987,-428.2603C1169.7059,-413.7175 1184.5598,-396.5745 1194,-377 1223.5477,-315.7324 1178.5006,-245.5165 1136.8282,-198.4229"/>
<polygon fill="#000000" stroke="#000000" points="1139.2172,-195.8466 1129.9133,-190.7783 1134.0259,-200.5424 1139.2172,-195.8466"/>
<text text-anchor="middle" x="1241.5" y="-300.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort&#45;&gt;study_arm -->
<g id="edge7" class="edge">
<title>cohort&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1009.916,-330.4982C1001.4004,-325.126 993.0109,-318.921 986,-312 978.9099,-305.0007 972.7966,-296.0596 967.9177,-287.5983"/>
<polygon fill="#000000" stroke="#000000" points="970.9534,-285.8538 963.1203,-278.72 964.795,-289.1816 970.9534,-285.8538"/>
<text text-anchor="middle" x="1026.5" y="-300.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cohort&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1063.2381,-330.3609C1064.6585,-324.4135 1066.0323,-317.9995 1067,-312 1072.9332,-275.2163 1076.4306,-233.4579 1078.4459,-200.8373"/>
<polygon fill="#000000" stroke="#000000" points="1081.9557,-200.7736 1079.0494,-190.5852 1074.9678,-200.3622 1081.9557,-200.7736"/>
<text text-anchor="middle" x="1116.5" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- survival -->
<g id="node7" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1311.5,-595.5C1311.5,-595.5 1636.5,-595.5 1636.5,-595.5 1642.5,-595.5 1648.5,-601.5 1648.5,-607.5 1648.5,-607.5 1648.5,-882.5 1648.5,-882.5 1648.5,-888.5 1642.5,-894.5 1636.5,-894.5 1636.5,-894.5 1311.5,-894.5 1311.5,-894.5 1305.5,-894.5 1299.5,-888.5 1299.5,-882.5 1299.5,-882.5 1299.5,-607.5 1299.5,-607.5 1299.5,-601.5 1305.5,-595.5 1311.5,-595.5"/>
<text text-anchor="middle" x="1336.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1373.5,-595.5 1373.5,-894.5 "/>
<text text-anchor="middle" x="1384" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1394.5,-595.5 1394.5,-894.5 "/>
<text text-anchor="middle" x="1511" y="-879.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1394.5,-871.5 1627.5,-871.5 "/>
<text text-anchor="middle" x="1511" y="-856.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_status</text>
<polyline fill="none" stroke="#000000" points="1394.5,-848.5 1627.5,-848.5 "/>
<text text-anchor="middle" x="1511" y="-833.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_interval</text>
<polyline fill="none" stroke="#000000" points="1394.5,-825.5 1627.5,-825.5 "/>
<text text-anchor="middle" x="1511" y="-810.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_survival</text>
<polyline fill="none" stroke="#000000" points="1394.5,-802.5 1627.5,-802.5 "/>
<text text-anchor="middle" x="1511" y="-787.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="1394.5,-779.5 1627.5,-779.5 "/>
<text text-anchor="middle" x="1511" y="-764.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_event_indicator</text>
<polyline fill="none" stroke="#000000" points="1394.5,-756.5 1627.5,-756.5 "/>
<text text-anchor="middle" x="1511" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">lost_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="1394.5,-733.5 1627.5,-733.5 "/>
<text text-anchor="middle" x="1511" y="-718.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_withdrawn</text>
<polyline fill="none" stroke="#000000" points="1394.5,-710.5 1627.5,-710.5 "/>
<text text-anchor="middle" x="1511" y="-695.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_recurrence</text>
<polyline fill="none" stroke="#000000" points="1394.5,-687.5 1627.5,-687.5 "/>
<text text-anchor="middle" x="1511" y="-672.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="1394.5,-664.5 1627.5,-664.5 "/>
<text text-anchor="middle" x="1511" y="-649.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_free_interval</text>
<polyline fill="none" stroke="#000000" points="1394.5,-641.5 1627.5,-641.5 "/>
<text text-anchor="middle" x="1511" y="-626.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_survival_interval</text>
<polyline fill="none" stroke="#000000" points="1394.5,-618.5 1627.5,-618.5 "/>
<text text-anchor="middle" x="1511" y="-603.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_dfs_event</text>
<polyline fill="none" stroke="#000000" points="1627.5,-595.5 1627.5,-894.5 "/>
<text text-anchor="middle" x="1638" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;case -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1299.4389,-601.0525C1296.289,-598.9921 1293.1412,-596.9727 1290,-595 1263.0093,-578.0496 1232.9593,-562.0789 1203.6534,-547.8589"/>
<polygon fill="#000000" stroke="#000000" points="1205.116,-544.6786 1194.5866,-543.5028 1202.0846,-550.9882 1205.116,-544.6786"/>
<text text-anchor="middle" x="1281" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- diagnosis -->
<g id="node8" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1678.5,-664.5C1678.5,-664.5 2013.5,-664.5 2013.5,-664.5 2019.5,-664.5 2025.5,-670.5 2025.5,-676.5 2025.5,-676.5 2025.5,-813.5 2025.5,-813.5 2025.5,-819.5 2019.5,-825.5 2013.5,-825.5 2013.5,-825.5 1678.5,-825.5 1678.5,-825.5 1672.5,-825.5 1666.5,-819.5 1666.5,-813.5 1666.5,-813.5 1666.5,-676.5 1666.5,-676.5 1666.5,-670.5 1672.5,-664.5 1678.5,-664.5"/>
<text text-anchor="middle" x="1708.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1750.5,-664.5 1750.5,-825.5 "/>
<text text-anchor="middle" x="1761" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1771.5,-664.5 1771.5,-825.5 "/>
<text text-anchor="middle" x="1888" y="-810.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_group</text>
<polyline fill="none" stroke="#000000" points="1771.5,-802.5 2004.5,-802.5 "/>
<text text-anchor="middle" x="1888" y="-787.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size</text>
<polyline fill="none" stroke="#000000" points="1771.5,-779.5 2004.5,-779.5 "/>
<text text-anchor="middle" x="1888" y="-764.3" font-family="Times,serif" font-size="14.00" fill="#000000">progesterone_receptor_status</text>
<polyline fill="none" stroke="#000000" points="1771.5,-756.5 2004.5,-756.5 "/>
<text text-anchor="middle" x="1888" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">histological_grade</text>
<polyline fill="none" stroke="#000000" points="1771.5,-733.5 2004.5,-733.5 "/>
<text text-anchor="middle" x="1888" y="-718.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_score</text>
<polyline fill="none" stroke="#000000" points="1771.5,-710.5 2004.5,-710.5 "/>
<text text-anchor="middle" x="1888" y="-695.3" font-family="Times,serif" font-size="14.00" fill="#000000">nuclear_grade</text>
<polyline fill="none" stroke="#000000" points="1771.5,-687.5 2004.5,-687.5 "/>
<text text-anchor="middle" x="1888" y="-672.3" font-family="Times,serif" font-size="14.00" fill="#000000">estrogen_receptor_status</text>
<polyline fill="none" stroke="#000000" points="2004.5,-664.5 2004.5,-825.5 "/>
<text text-anchor="middle" x="2015" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;case -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1763.067,-664.2402C1732.2779,-638.4045 1695.6355,-612.098 1658,-595 1579.5485,-559.3591 1358.4967,-525.0422 1207.5143,-504.7318"/>
<polygon fill="#000000" stroke="#000000" points="1207.5964,-501.2116 1197.2204,-503.3541 1206.6677,-508.1498 1207.5964,-501.2116"/>
<text text-anchor="middle" x="1626" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- program -->
<g id="node10" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M982.5,-.5C982.5,-.5 1179.5,-.5 1179.5,-.5 1185.5,-.5 1191.5,-6.5 1191.5,-12.5 1191.5,-12.5 1191.5,-34.5 1191.5,-34.5 1191.5,-40.5 1185.5,-46.5 1179.5,-46.5 1179.5,-46.5 982.5,-46.5 982.5,-46.5 976.5,-46.5 970.5,-40.5 970.5,-34.5 970.5,-34.5 970.5,-12.5 970.5,-12.5 970.5,-6.5 976.5,-.5 982.5,-.5"/>
<text text-anchor="middle" x="1009.5" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1048.5,-.5 1048.5,-46.5 "/>
<text text-anchor="middle" x="1059" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1069.5,-.5 1069.5,-46.5 "/>
<text text-anchor="middle" x="1120" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1069.5,-23.5 1170.5,-23.5 "/>
<text text-anchor="middle" x="1120" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="1170.5,-.5 1170.5,-46.5 "/>
<text text-anchor="middle" x="1181" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge9" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1081,-98.4099C1081,-84.6353 1081,-69.8024 1081,-56.9992"/>
<polygon fill="#000000" stroke="#000000" points="1084.5001,-56.7897 1081,-46.7897 1077.5001,-56.7898 1084.5001,-56.7897"/>
<text text-anchor="middle" x="1121.5" y="-68.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
</g>
</svg>
</div>