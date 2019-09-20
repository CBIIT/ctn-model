<link rel='stylesheet' href="assets/style.css">
<link rel='stylesheet' href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin="">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript"  src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>
<script type="text/javascript" src="assets/actions.js"></script>

Zoom to Node: <select id="node_select">
  <option value="">Zoom to Node</option>
</select>
<div id="model"></div>


<a href="./mdf/ctn-model.svg">SVG file (in view above)</a>

<a href="./mdf">All model artifacts</a>

# ctn-model
Location for CRDC Clinical Trial Node model description files and related artifacts

# Description

This repo is a workspace for development of the data model for the [Cancer Research Data Commons](https://datascience.cancer.gov/data-commons) Clinical Trial Node. 

The files are created in [Model Description Format](https://github.com/CBIIT/icdc-model-tool#model-description-files-mdf) and can be visualized using [model-tool](https://github.com/CBIIT/icdc-model-tool#makemodel-and-model-tool).

<div id='graph' style='display:off;'>
<svg width="2997pt" height="3673pt"
 viewBox="0.00 0.00 2996.50 3673.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 3669)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-3669 2992.5,-3669 2992.5,4 -4,4"/>
<!-- cohort -->
<g id="node1" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M1023,-900C1023,-900 1256,-900 1256,-900 1262,-900 1268,-906 1268,-912 1268,-912 1268,-934 1268,-934 1268,-940 1262,-946 1256,-946 1256,-946 1023,-946 1023,-946 1017,-946 1011,-940 1011,-934 1011,-934 1011,-912 1011,-912 1011,-906 1017,-900 1023,-900"/>
<text text-anchor="middle" x="1042.5" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="1074,-900 1074,-946 "/>
<text text-anchor="middle" x="1084.5" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1095,-900 1095,-946 "/>
<text text-anchor="middle" x="1171" y="-930.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_dose</text>
<polyline fill="none" stroke="#000000" points="1095,-923 1247,-923 "/>
<text text-anchor="middle" x="1171" y="-907.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1247,-900 1247,-946 "/>
<text text-anchor="middle" x="1257.5" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm -->
<g id="node11" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1132,-518.5C1132,-518.5 1501,-518.5 1501,-518.5 1507,-518.5 1513,-524.5 1513,-530.5 1513,-530.5 1513,-575.5 1513,-575.5 1513,-581.5 1507,-587.5 1501,-587.5 1501,-587.5 1132,-587.5 1132,-587.5 1126,-587.5 1120,-581.5 1120,-575.5 1120,-575.5 1120,-530.5 1120,-530.5 1120,-524.5 1126,-518.5 1132,-518.5"/>
<text text-anchor="middle" x="1166" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1212,-518.5 1212,-587.5 "/>
<text text-anchor="middle" x="1222.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1233,-518.5 1233,-587.5 "/>
<text text-anchor="middle" x="1362.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_treatment_assignment_code</text>
<polyline fill="none" stroke="#000000" points="1233,-564.5 1492,-564.5 "/>
<text text-anchor="middle" x="1362.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_arm_version</text>
<polyline fill="none" stroke="#000000" points="1233,-541.5 1492,-541.5 "/>
<text text-anchor="middle" x="1362.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm</text>
<polyline fill="none" stroke="#000000" points="1492,-518.5 1492,-587.5 "/>
<text text-anchor="middle" x="1502.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- cohort&#45;&gt;study_arm -->
<g id="edge10" class="edge">
<title>cohort&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1139.2652,-899.9775C1139.7974,-848.8459 1147.0156,-723.665 1201.5,-639 1212.8043,-621.4339 1229.0283,-606.1538 1245.7405,-593.545"/>
<polygon fill="#000000" stroke="#000000" points="1247.9304,-596.2802 1253.9645,-587.5715 1243.8166,-590.6166 1247.9304,-596.2802"/>
<text text-anchor="middle" x="1242" y="-653.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- study -->
<g id="node16" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1176.5,-236.5C1176.5,-236.5 1456.5,-236.5 1456.5,-236.5 1462.5,-236.5 1468.5,-242.5 1468.5,-248.5 1468.5,-248.5 1468.5,-454.5 1468.5,-454.5 1468.5,-460.5 1462.5,-466.5 1456.5,-466.5 1456.5,-466.5 1176.5,-466.5 1176.5,-466.5 1170.5,-466.5 1164.5,-460.5 1164.5,-454.5 1164.5,-454.5 1164.5,-248.5 1164.5,-248.5 1164.5,-242.5 1170.5,-236.5 1176.5,-236.5"/>
<text text-anchor="middle" x="1192.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1220.5,-236.5 1220.5,-466.5 "/>
<text text-anchor="middle" x="1231" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1241.5,-236.5 1241.5,-466.5 "/>
<text text-anchor="middle" x="1344.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_category</text>
<polyline fill="none" stroke="#000000" points="1241.5,-443.5 1447.5,-443.5 "/>
<text text-anchor="middle" x="1344.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dates_of_conduct</text>
<polyline fill="none" stroke="#000000" points="1241.5,-420.5 1447.5,-420.5 "/>
<text text-anchor="middle" x="1344.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_term</text>
<polyline fill="none" stroke="#000000" points="1241.5,-397.5 1447.5,-397.5 "/>
<text text-anchor="middle" x="1344.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_su_category</text>
<polyline fill="none" stroke="#000000" points="1241.5,-374.5 1447.5,-374.5 "/>
<text text-anchor="middle" x="1344.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_type</text>
<polyline fill="none" stroke="#000000" points="1241.5,-351.5 1447.5,-351.5 "/>
<text text-anchor="middle" x="1344.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_designation</text>
<polyline fill="none" stroke="#000000" points="1241.5,-328.5 1447.5,-328.5 "/>
<text text-anchor="middle" x="1344.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_id</text>
<polyline fill="none" stroke="#000000" points="1241.5,-305.5 1447.5,-305.5 "/>
<text text-anchor="middle" x="1344.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_iacuc_approval</text>
<polyline fill="none" stroke="#000000" points="1241.5,-282.5 1447.5,-282.5 "/>
<text text-anchor="middle" x="1344.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_name</text>
<polyline fill="none" stroke="#000000" points="1241.5,-259.5 1447.5,-259.5 "/>
<text text-anchor="middle" x="1344.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_description</text>
<polyline fill="none" stroke="#000000" points="1447.5,-236.5 1447.5,-466.5 "/>
<text text-anchor="middle" x="1458" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- cohort&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cohort&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1130.1597,-899.5793C1105.9503,-834.9802 1047.3153,-650.3118 1110.5,-518 1121.7897,-494.3589 1138.2569,-472.994 1157.038,-454.0632"/>
<polygon fill="#000000" stroke="#000000" points="1159.6355,-456.4187 1164.3434,-446.9273 1154.7441,-451.4112 1159.6355,-456.4187"/>
<text text-anchor="middle" x="1126" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- survival -->
<g id="node2" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M12,-1406.5C12,-1406.5 337,-1406.5 337,-1406.5 343,-1406.5 349,-1412.5 349,-1418.5 349,-1418.5 349,-1693.5 349,-1693.5 349,-1699.5 343,-1705.5 337,-1705.5 337,-1705.5 12,-1705.5 12,-1705.5 6,-1705.5 0,-1699.5 0,-1693.5 0,-1693.5 0,-1418.5 0,-1418.5 0,-1412.5 6,-1406.5 12,-1406.5"/>
<text text-anchor="middle" x="37" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="74,-1406.5 74,-1705.5 "/>
<text text-anchor="middle" x="84.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="95,-1406.5 95,-1705.5 "/>
<text text-anchor="middle" x="211.5" y="-1690.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="95,-1682.5 328,-1682.5 "/>
<text text-anchor="middle" x="211.5" y="-1667.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_survival</text>
<polyline fill="none" stroke="#000000" points="95,-1659.5 328,-1659.5 "/>
<text text-anchor="middle" x="211.5" y="-1644.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_withdrawn</text>
<polyline fill="none" stroke="#000000" points="95,-1636.5 328,-1636.5 "/>
<text text-anchor="middle" x="211.5" y="-1621.3" font-family="Times,serif" font-size="14.00" fill="#000000">lost_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="95,-1613.5 328,-1613.5 "/>
<text text-anchor="middle" x="211.5" y="-1598.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_recurrence</text>
<polyline fill="none" stroke="#000000" points="95,-1590.5 328,-1590.5 "/>
<text text-anchor="middle" x="211.5" y="-1575.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="95,-1567.5 328,-1567.5 "/>
<text text-anchor="middle" x="211.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_status</text>
<polyline fill="none" stroke="#000000" points="95,-1544.5 328,-1544.5 "/>
<text text-anchor="middle" x="211.5" y="-1529.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="95,-1521.5 328,-1521.5 "/>
<text text-anchor="middle" x="211.5" y="-1506.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_dfs_event</text>
<polyline fill="none" stroke="#000000" points="95,-1498.5 328,-1498.5 "/>
<text text-anchor="middle" x="211.5" y="-1483.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_free_interval</text>
<polyline fill="none" stroke="#000000" points="95,-1475.5 328,-1475.5 "/>
<text text-anchor="middle" x="211.5" y="-1460.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_interval</text>
<polyline fill="none" stroke="#000000" points="95,-1452.5 328,-1452.5 "/>
<text text-anchor="middle" x="211.5" y="-1437.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_survival_interval</text>
<polyline fill="none" stroke="#000000" points="95,-1429.5 328,-1429.5 "/>
<text text-anchor="middle" x="211.5" y="-1414.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_event_indicator</text>
<polyline fill="none" stroke="#000000" points="328,-1406.5 328,-1705.5 "/>
<text text-anchor="middle" x="338.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case -->
<g id="node14" class="node">
<title>case</title>
<path fill="none" stroke="#000000" d="M1235.5,-1170.5C1235.5,-1170.5 1491.5,-1170.5 1491.5,-1170.5 1497.5,-1170.5 1503.5,-1176.5 1503.5,-1182.5 1503.5,-1182.5 1503.5,-1273.5 1503.5,-1273.5 1503.5,-1279.5 1497.5,-1285.5 1491.5,-1285.5 1491.5,-1285.5 1235.5,-1285.5 1235.5,-1285.5 1229.5,-1285.5 1223.5,-1279.5 1223.5,-1273.5 1223.5,-1273.5 1223.5,-1182.5 1223.5,-1182.5 1223.5,-1176.5 1229.5,-1170.5 1235.5,-1170.5"/>
<text text-anchor="middle" x="1248" y="-1224.3" font-family="Times,serif" font-size="14.00" fill="#000000">case</text>
<polyline fill="none" stroke="#000000" points="1272.5,-1170.5 1272.5,-1285.5 "/>
<text text-anchor="middle" x="1283" y="-1224.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1293.5,-1170.5 1293.5,-1285.5 "/>
<text text-anchor="middle" x="1388" y="-1270.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_id</text>
<polyline fill="none" stroke="#000000" points="1293.5,-1262.5 1482.5,-1262.5 "/>
<text text-anchor="middle" x="1388" y="-1247.3" font-family="Times,serif" font-size="14.00" fill="#000000">included_in_analysis</text>
<polyline fill="none" stroke="#000000" points="1293.5,-1239.5 1482.5,-1239.5 "/>
<text text-anchor="middle" x="1388" y="-1224.3" font-family="Times,serif" font-size="14.00" fill="#000000">on_study_crf_submitted</text>
<polyline fill="none" stroke="#000000" points="1293.5,-1216.5 1482.5,-1216.5 "/>
<text text-anchor="middle" x="1388" y="-1201.3" font-family="Times,serif" font-size="14.00" fill="#000000">ineligible</text>
<polyline fill="none" stroke="#000000" points="1293.5,-1193.5 1482.5,-1193.5 "/>
<text text-anchor="middle" x="1388" y="-1178.3" font-family="Times,serif" font-size="14.00" fill="#000000">case_id</text>
<polyline fill="none" stroke="#000000" points="1482.5,-1170.5 1482.5,-1285.5 "/>
<text text-anchor="middle" x="1493" y="-1224.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;case -->
<g id="edge31" class="edge">
<title>survival&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M272.4556,-1406.4274C297.025,-1379.2048 325.6087,-1354.0646 357.5,-1337 501.898,-1259.7347 969.5792,-1237.1981 1213.0504,-1230.6556"/>
<polygon fill="#000000" stroke="#000000" points="1213.4968,-1234.1451 1223.4013,-1230.3834 1213.3127,-1227.1476 1213.4968,-1234.1451"/>
<text text-anchor="middle" x="461.5" y="-1307.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- evaluation -->
<g id="node3" class="node">
<title>evaluation</title>
<path fill="none" stroke="#000000" d="M746.5,-3313C746.5,-3313 1006.5,-3313 1006.5,-3313 1012.5,-3313 1018.5,-3319 1018.5,-3325 1018.5,-3325 1018.5,-3337 1018.5,-3337 1018.5,-3343 1012.5,-3349 1006.5,-3349 1006.5,-3349 746.5,-3349 746.5,-3349 740.5,-3349 734.5,-3343 734.5,-3337 734.5,-3337 734.5,-3325 734.5,-3325 734.5,-3319 740.5,-3313 746.5,-3313"/>
<text text-anchor="middle" x="780" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000">evaluation</text>
<polyline fill="none" stroke="#000000" points="825.5,-3313 825.5,-3349 "/>
<text text-anchor="middle" x="836" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="846.5,-3313 846.5,-3349 "/>
<text text-anchor="middle" x="922" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_evaluation</text>
<polyline fill="none" stroke="#000000" points="997.5,-3313 997.5,-3349 "/>
<text text-anchor="middle" x="1008" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis -->
<g id="node4" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M729,-1793.5C729,-1793.5 1072,-1793.5 1072,-1793.5 1078,-1793.5 1084,-1799.5 1084,-1805.5 1084,-1805.5 1084,-2218.5 1084,-2218.5 1084,-2224.5 1078,-2230.5 1072,-2230.5 1072,-2230.5 729,-2230.5 729,-2230.5 723,-2230.5 717,-2224.5 717,-2218.5 717,-2218.5 717,-1805.5 717,-1805.5 717,-1799.5 723,-1793.5 729,-1793.5"/>
<text text-anchor="middle" x="759" y="-2008.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="801,-1793.5 801,-2230.5 "/>
<text text-anchor="middle" x="811.5" y="-2008.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="822,-1793.5 822,-2230.5 "/>
<text text-anchor="middle" x="942.5" y="-2215.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_term</text>
<polyline fill="none" stroke="#000000" points="822,-2207.5 1063,-2207.5 "/>
<text text-anchor="middle" x="942.5" y="-2192.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_report</text>
<polyline fill="none" stroke="#000000" points="822,-2184.5 1063,-2184.5 "/>
<text text-anchor="middle" x="942.5" y="-2169.3" font-family="Times,serif" font-size="14.00" fill="#000000">stage_of_disease</text>
<polyline fill="none" stroke="#000000" points="822,-2161.5 1063,-2161.5 "/>
<text text-anchor="middle" x="942.5" y="-2146.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease_type</text>
<polyline fill="none" stroke="#000000" points="822,-2138.5 1063,-2138.5 "/>
<text text-anchor="middle" x="942.5" y="-2123.3" font-family="Times,serif" font-size="14.00" fill="#000000">histology_cytopathology</text>
<polyline fill="none" stroke="#000000" points="822,-2115.5 1063,-2115.5 "/>
<text text-anchor="middle" x="942.5" y="-2100.3" font-family="Times,serif" font-size="14.00" fill="#000000">nuclear_grade</text>
<polyline fill="none" stroke="#000000" points="822,-2092.5 1063,-2092.5 "/>
<text text-anchor="middle" x="942.5" y="-2077.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_code</text>
<polyline fill="none" stroke="#000000" points="822,-2069.5 1063,-2069.5 "/>
<text text-anchor="middle" x="942.5" y="-2054.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_disease_site</text>
<polyline fill="none" stroke="#000000" points="822,-2046.5 1063,-2046.5 "/>
<text text-anchor="middle" x="942.5" y="-2031.3" font-family="Times,serif" font-size="14.00" fill="#000000">estrogen_receptor_status</text>
<polyline fill="none" stroke="#000000" points="822,-2023.5 1063,-2023.5 "/>
<text text-anchor="middle" x="942.5" y="-2008.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size</text>
<polyline fill="none" stroke="#000000" points="822,-2000.5 1063,-2000.5 "/>
<text text-anchor="middle" x="942.5" y="-1985.3" font-family="Times,serif" font-size="14.00" fill="#000000">progesterone_receptor_status</text>
<polyline fill="none" stroke="#000000" points="822,-1977.5 1063,-1977.5 "/>
<text text-anchor="middle" x="942.5" y="-1962.3" font-family="Times,serif" font-size="14.00" fill="#000000">histological_grade</text>
<polyline fill="none" stroke="#000000" points="822,-1954.5 1063,-1954.5 "/>
<text text-anchor="middle" x="942.5" y="-1939.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_data</text>
<polyline fill="none" stroke="#000000" points="822,-1931.5 1063,-1931.5 "/>
<text text-anchor="middle" x="942.5" y="-1916.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_histology_confirmation</text>
<polyline fill="none" stroke="#000000" points="822,-1908.5 1063,-1908.5 "/>
<text text-anchor="middle" x="942.5" y="-1893.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_score</text>
<polyline fill="none" stroke="#000000" points="822,-1885.5 1063,-1885.5 "/>
<text text-anchor="middle" x="942.5" y="-1870.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease</text>
<polyline fill="none" stroke="#000000" points="822,-1862.5 1063,-1862.5 "/>
<text text-anchor="middle" x="942.5" y="-1847.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_data</text>
<polyline fill="none" stroke="#000000" points="822,-1839.5 1063,-1839.5 "/>
<text text-anchor="middle" x="942.5" y="-1824.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="822,-1816.5 1063,-1816.5 "/>
<text text-anchor="middle" x="942.5" y="-1801.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_group</text>
<polyline fill="none" stroke="#000000" points="1063,-1793.5 1063,-2230.5 "/>
<text text-anchor="middle" x="1073.5" y="-2008.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;case -->
<g id="edge30" class="edge">
<title>diagnosis&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M890.2474,-1793.151C883.7994,-1609.7402 881.3074,-1372.2762 909.5,-1337 947.3633,-1289.6233 1096.0809,-1260.3903 1213.1216,-1244.2773"/>
<polygon fill="#000000" stroke="#000000" points="1213.8318,-1247.7132 1223.2711,-1242.9018 1212.8916,-1240.7766 1213.8318,-1247.7132"/>
<text text-anchor="middle" x="936.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- variant -->
<g id="node5" class="node">
<title>variant</title>
<path fill="none" stroke="#000000" d="M379,-2997.5C379,-2997.5 704,-2997.5 704,-2997.5 710,-2997.5 716,-3003.5 716,-3009.5 716,-3009.5 716,-3652.5 716,-3652.5 716,-3658.5 710,-3664.5 704,-3664.5 704,-3664.5 379,-3664.5 379,-3664.5 373,-3664.5 367,-3658.5 367,-3652.5 367,-3652.5 367,-3009.5 367,-3009.5 367,-3003.5 373,-2997.5 379,-2997.5"/>
<text text-anchor="middle" x="401" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant</text>
<polyline fill="none" stroke="#000000" points="435,-2997.5 435,-3664.5 "/>
<text text-anchor="middle" x="445.5" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="456,-2997.5 456,-3664.5 "/>
<text text-anchor="middle" x="575.5" y="-3649.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_ref</text>
<polyline fill="none" stroke="#000000" points="456,-3641.5 695,-3641.5 "/>
<text text-anchor="middle" x="575.5" y="-3626.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_95percent</text>
<polyline fill="none" stroke="#000000" points="456,-3618.5 695,-3618.5 "/>
<text text-anchor="middle" x="575.5" y="-3603.3" font-family="Times,serif" font-size="14.00" fill="#000000">ref_copy_number</text>
<polyline fill="none" stroke="#000000" points="456,-3595.5 695,-3595.5 "/>
<text text-anchor="middle" x="575.5" y="-3580.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_name</text>
<polyline fill="none" stroke="#000000" points="456,-3572.5 695,-3572.5 "/>
<text text-anchor="middle" x="575.5" y="-3557.3" font-family="Times,serif" font-size="14.00" fill="#000000">function</text>
<polyline fill="none" stroke="#000000" points="456,-3549.5 695,-3549.5 "/>
<text text-anchor="middle" x="575.5" y="-3534.3" font-family="Times,serif" font-size="14.00" fill="#000000">transcript</text>
<polyline fill="none" stroke="#000000" points="456,-3526.5 695,-3526.5 "/>
<text text-anchor="middle" x="575.5" y="-3511.3" font-family="Times,serif" font-size="14.00" fill="#000000">aMOI</text>
<polyline fill="none" stroke="#000000" points="456,-3503.5 695,-3503.5 "/>
<text text-anchor="middle" x="575.5" y="-3488.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="456,-3480.5 695,-3480.5 "/>
<text text-anchor="middle" x="575.5" y="-3465.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternative_allele</text>
<polyline fill="none" stroke="#000000" points="456,-3457.5 695,-3457.5 "/>
<text text-anchor="middle" x="575.5" y="-3442.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_alt</text>
<polyline fill="none" stroke="#000000" points="456,-3434.5 695,-3434.5 "/>
<text text-anchor="middle" x="575.5" y="-3419.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm_specific</text>
<polyline fill="none" stroke="#000000" points="456,-3411.5 695,-3411.5 "/>
<text text-anchor="middle" x="575.5" y="-3396.3" font-family="Times,serif" font-size="14.00" fill="#000000">allele_frequency</text>
<polyline fill="none" stroke="#000000" points="456,-3388.5 695,-3388.5 "/>
<text text-anchor="middle" x="575.5" y="-3373.3" font-family="Times,serif" font-size="14.00" fill="#000000">protein</text>
<polyline fill="none" stroke="#000000" points="456,-3365.5 695,-3365.5 "/>
<text text-anchor="middle" x="575.5" y="-3350.3" font-family="Times,serif" font-size="14.00" fill="#000000">genome_reference</text>
<polyline fill="none" stroke="#000000" points="456,-3342.5 695,-3342.5 "/>
<text text-anchor="middle" x="575.5" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_05percent</text>
<polyline fill="none" stroke="#000000" points="456,-3319.5 695,-3319.5 "/>
<text text-anchor="middle" x="575.5" y="-3304.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="456,-3296.5 695,-3296.5 "/>
<text text-anchor="middle" x="575.5" y="-3281.3" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="456,-3273.5 695,-3273.5 "/>
<text text-anchor="middle" x="575.5" y="-3258.3" font-family="Times,serif" font-size="14.00" fill="#000000">position</text>
<polyline fill="none" stroke="#000000" points="456,-3250.5 695,-3250.5 "/>
<text text-anchor="middle" x="575.5" y="-3235.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_alt</text>
<polyline fill="none" stroke="#000000" points="456,-3227.5 695,-3227.5 "/>
<text text-anchor="middle" x="575.5" y="-3212.3" font-family="Times,serif" font-size="14.00" fill="#000000">strand</text>
<polyline fill="none" stroke="#000000" points="456,-3204.5 695,-3204.5 "/>
<text text-anchor="middle" x="575.5" y="-3189.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="456,-3181.5 695,-3181.5 "/>
<text text-anchor="middle" x="575.5" y="-3166.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_ref</text>
<polyline fill="none" stroke="#000000" points="456,-3158.5 695,-3158.5 "/>
<text text-anchor="middle" x="575.5" y="-3143.3" font-family="Times,serif" font-size="14.00" fill="#000000">read_depth</text>
<polyline fill="none" stroke="#000000" points="456,-3135.5 695,-3135.5 "/>
<text text-anchor="middle" x="575.5" y="-3120.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs</text>
<polyline fill="none" stroke="#000000" points="456,-3112.5 695,-3112.5 "/>
<text text-anchor="middle" x="575.5" y="-3097.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id_analysis_id</text>
<polyline fill="none" stroke="#000000" points="456,-3089.5 695,-3089.5 "/>
<text text-anchor="middle" x="575.5" y="-3074.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_type</text>
<polyline fill="none" stroke="#000000" points="456,-3066.5 695,-3066.5 "/>
<text text-anchor="middle" x="575.5" y="-3051.3" font-family="Times,serif" font-size="14.00" fill="#000000">confirmed</text>
<polyline fill="none" stroke="#000000" points="456,-3043.5 695,-3043.5 "/>
<text text-anchor="middle" x="575.5" y="-3028.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="456,-3020.5 695,-3020.5 "/>
<text text-anchor="middle" x="575.5" y="-3005.3" font-family="Times,serif" font-size="14.00" fill="#000000">raw_copy_number</text>
<polyline fill="none" stroke="#000000" points="695,-2997.5 695,-3664.5 "/>
<text text-anchor="middle" x="705.5" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_report -->
<g id="node17" class="node">
<title>genomic_report</title>
<path fill="none" stroke="#000000" d="M353.5,-2669.5C353.5,-2669.5 729.5,-2669.5 729.5,-2669.5 735.5,-2669.5 741.5,-2675.5 741.5,-2681.5 741.5,-2681.5 741.5,-2933.5 741.5,-2933.5 741.5,-2939.5 735.5,-2945.5 729.5,-2945.5 729.5,-2945.5 353.5,-2945.5 353.5,-2945.5 347.5,-2945.5 341.5,-2939.5 341.5,-2933.5 341.5,-2933.5 341.5,-2681.5 341.5,-2681.5 341.5,-2675.5 347.5,-2669.5 353.5,-2669.5"/>
<text text-anchor="middle" x="406.5" y="-2803.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_report</text>
<polyline fill="none" stroke="#000000" points="471.5,-2669.5 471.5,-2945.5 "/>
<text text-anchor="middle" x="482" y="-2803.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="492.5,-2669.5 492.5,-2945.5 "/>
<text text-anchor="middle" x="606.5" y="-2930.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_amois</text>
<polyline fill="none" stroke="#000000" points="492.5,-2922.5 720.5,-2922.5 "/>
<text text-anchor="middle" x="606.5" y="-2907.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_type</text>
<polyline fill="none" stroke="#000000" points="492.5,-2899.5 720.5,-2899.5 "/>
<text text-anchor="middle" x="606.5" y="-2884.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_amois</text>
<polyline fill="none" stroke="#000000" points="492.5,-2876.5 720.5,-2876.5 "/>
<text text-anchor="middle" x="606.5" y="-2861.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_mois</text>
<polyline fill="none" stroke="#000000" points="492.5,-2853.5 720.5,-2853.5 "/>
<text text-anchor="middle" x="606.5" y="-2838.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_mois</text>
<polyline fill="none" stroke="#000000" points="492.5,-2830.5 720.5,-2830.5 "/>
<text text-anchor="middle" x="606.5" y="-2815.3" font-family="Times,serif" font-size="14.00" fill="#000000">cellularity</text>
<polyline fill="none" stroke="#000000" points="492.5,-2807.5 720.5,-2807.5 "/>
<text text-anchor="middle" x="606.5" y="-2792.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_variants</text>
<polyline fill="none" stroke="#000000" points="492.5,-2784.5 720.5,-2784.5 "/>
<text text-anchor="middle" x="606.5" y="-2769.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="492.5,-2761.5 720.5,-2761.5 "/>
<text text-anchor="middle" x="606.5" y="-2746.3" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="492.5,-2738.5 720.5,-2738.5 "/>
<text text-anchor="middle" x="606.5" y="-2723.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="492.5,-2715.5 720.5,-2715.5 "/>
<text text-anchor="middle" x="606.5" y="-2700.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_received_date</text>
<polyline fill="none" stroke="#000000" points="492.5,-2692.5 720.5,-2692.5 "/>
<text text-anchor="middle" x="606.5" y="-2677.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id</text>
<polyline fill="none" stroke="#000000" points="720.5,-2669.5 720.5,-2945.5 "/>
<text text-anchor="middle" x="731" y="-2803.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- variant&#45;&gt;genomic_report -->
<g id="edge19" class="edge">
<title>variant&#45;&gt;genomic_report</title>
<path fill="none" stroke="#000000" d="M541.5,-2997.2357C541.5,-2983.0591 541.5,-2969.1882 541.5,-2955.8076"/>
<polygon fill="#000000" stroke="#000000" points="545.0001,-2955.674 541.5,-2945.674 538.0001,-2955.6741 545.0001,-2955.674"/>
<text text-anchor="middle" x="575" y="-2967.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_report</text>
</g>
<!-- image -->
<g id="node6" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M275.5,-2789.5C275.5,-2789.5 311.5,-2789.5 311.5,-2789.5 317.5,-2789.5 323.5,-2795.5 323.5,-2801.5 323.5,-2801.5 323.5,-2813.5 323.5,-2813.5 323.5,-2819.5 317.5,-2825.5 311.5,-2825.5 311.5,-2825.5 275.5,-2825.5 275.5,-2825.5 269.5,-2825.5 263.5,-2819.5 263.5,-2813.5 263.5,-2813.5 263.5,-2801.5 263.5,-2801.5 263.5,-2795.5 269.5,-2789.5 275.5,-2789.5"/>
<text text-anchor="middle" x="293.5" y="-2803.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
</g>
<!-- assay -->
<g id="node22" class="node">
<title>assay</title>
<path fill="none" stroke="#000000" d="M538.5,-2415.5C538.5,-2415.5 570.5,-2415.5 570.5,-2415.5 576.5,-2415.5 582.5,-2421.5 582.5,-2427.5 582.5,-2427.5 582.5,-2439.5 582.5,-2439.5 582.5,-2445.5 576.5,-2451.5 570.5,-2451.5 570.5,-2451.5 538.5,-2451.5 538.5,-2451.5 532.5,-2451.5 526.5,-2445.5 526.5,-2439.5 526.5,-2439.5 526.5,-2427.5 526.5,-2427.5 526.5,-2421.5 532.5,-2415.5 538.5,-2415.5"/>
<text text-anchor="middle" x="554.5" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000">assay</text>
</g>
<!-- image&#45;&gt;assay -->
<g id="edge21" class="edge">
<title>image&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M295.7772,-2789.3897C299.8381,-2761.8746 310.0999,-2708.5628 332.5,-2669 383.2694,-2579.3318 475.2267,-2497.2796 523.3062,-2457.948"/>
<polygon fill="#000000" stroke="#000000" points="525.627,-2460.5723 531.1936,-2451.5576 521.2204,-2455.1334 525.627,-2460.5723"/>
<text text-anchor="middle" x="382" y="-2639.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- demographic -->
<g id="node7" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M984.5,-1475.5C984.5,-1475.5 1320.5,-1475.5 1320.5,-1475.5 1326.5,-1475.5 1332.5,-1481.5 1332.5,-1487.5 1332.5,-1487.5 1332.5,-1624.5 1332.5,-1624.5 1332.5,-1630.5 1326.5,-1636.5 1320.5,-1636.5 1320.5,-1636.5 984.5,-1636.5 984.5,-1636.5 978.5,-1636.5 972.5,-1630.5 972.5,-1624.5 972.5,-1624.5 972.5,-1487.5 972.5,-1487.5 972.5,-1481.5 978.5,-1475.5 984.5,-1475.5"/>
<text text-anchor="middle" x="1027.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="1082.5,-1475.5 1082.5,-1636.5 "/>
<text text-anchor="middle" x="1093" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1103.5,-1475.5 1103.5,-1636.5 "/>
<text text-anchor="middle" x="1207.5" y="-1621.3" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="1103.5,-1613.5 1311.5,-1613.5 "/>
<text text-anchor="middle" x="1207.5" y="-1598.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="1103.5,-1590.5 1311.5,-1590.5 "/>
<text text-anchor="middle" x="1207.5" y="-1575.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_birth</text>
<polyline fill="none" stroke="#000000" points="1103.5,-1567.5 1311.5,-1567.5 "/>
<text text-anchor="middle" x="1207.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status</text>
<polyline fill="none" stroke="#000000" points="1103.5,-1544.5 1311.5,-1544.5 "/>
<text text-anchor="middle" x="1207.5" y="-1529.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1103.5,-1521.5 1311.5,-1521.5 "/>
<text text-anchor="middle" x="1207.5" y="-1506.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1103.5,-1498.5 1311.5,-1498.5 "/>
<text text-anchor="middle" x="1207.5" y="-1483.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="1311.5,-1475.5 1311.5,-1636.5 "/>
<text text-anchor="middle" x="1322" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;case -->
<g id="edge27" class="edge">
<title>demographic&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1204.3866,-1475.3421C1240.2186,-1419.6412 1287.2885,-1346.471 1320.9186,-1294.1929"/>
<polygon fill="#000000" stroke="#000000" points="1323.9393,-1295.9665 1326.406,-1285.6628 1318.0522,-1292.1793 1323.9393,-1295.9665"/>
<text text-anchor="middle" x="1340.5" y="-1307.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- treatment -->
<g id="node8" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1363,-1452.5C1363,-1452.5 1788,-1452.5 1788,-1452.5 1794,-1452.5 1800,-1458.5 1800,-1464.5 1800,-1464.5 1800,-1647.5 1800,-1647.5 1800,-1653.5 1794,-1659.5 1788,-1659.5 1788,-1659.5 1363,-1659.5 1363,-1659.5 1357,-1659.5 1351,-1653.5 1351,-1647.5 1351,-1647.5 1351,-1464.5 1351,-1464.5 1351,-1458.5 1357,-1452.5 1363,-1452.5"/>
<text text-anchor="middle" x="1395.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1440,-1452.5 1440,-1659.5 "/>
<text text-anchor="middle" x="1450.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1461,-1452.5 1461,-1659.5 "/>
<text text-anchor="middle" x="1620" y="-1644.3" font-family="Times,serif" font-size="14.00" fill="#000000">specific_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="1461,-1636.5 1779,-1636.5 "/>
<text text-anchor="middle" x="1620" y="-1621.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_first_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="1461,-1613.5 1779,-1613.5 "/>
<text text-anchor="middle" x="1620" y="-1598.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_endocrine_therapy_received</text>
<polyline fill="none" stroke="#000000" points="1461,-1590.5 1779,-1590.5 "/>
<text text-anchor="middle" x="1620" y="-1575.3" font-family="Times,serif" font-size="14.00" fill="#000000">duration_of_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="1461,-1567.5 1779,-1567.5 "/>
<text text-anchor="middle" x="1620" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">endocrine_therapy_discontinued</text>
<polyline fill="none" stroke="#000000" points="1461,-1544.5 1779,-1544.5 "/>
<text text-anchor="middle" x="1620" y="-1529.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_surgical_procedure</text>
<polyline fill="none" stroke="#000000" points="1461,-1521.5 1779,-1521.5 "/>
<text text-anchor="middle" x="1620" y="-1506.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="1461,-1498.5 1779,-1498.5 "/>
<text text-anchor="middle" x="1620" y="-1483.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_last_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="1461,-1475.5 1779,-1475.5 "/>
<text text-anchor="middle" x="1620" y="-1460.3" font-family="Times,serif" font-size="14.00" fill="#000000">received_chemotherapy</text>
<polyline fill="none" stroke="#000000" points="1779,-1452.5 1779,-1659.5 "/>
<text text-anchor="middle" x="1789.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;case -->
<g id="edge26" class="edge">
<title>treatment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1508.4219,-1452.2188C1475.0308,-1400.5571 1435.6559,-1339.6375 1406.3823,-1294.3462"/>
<polygon fill="#000000" stroke="#000000" points="1409.2203,-1292.2892 1400.8525,-1285.7907 1403.3413,-1296.089 1409.2203,-1292.2892"/>
<text text-anchor="middle" x="1447.5" y="-1307.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- prior_therapy -->
<g id="node9" class="node">
<title>prior_therapy</title>
<path fill="none" stroke="#000000" d="M2053.5,-2249.5C2053.5,-2249.5 2509.5,-2249.5 2509.5,-2249.5 2515.5,-2249.5 2521.5,-2255.5 2521.5,-2261.5 2521.5,-2261.5 2521.5,-2605.5 2521.5,-2605.5 2521.5,-2611.5 2515.5,-2617.5 2509.5,-2617.5 2509.5,-2617.5 2053.5,-2617.5 2053.5,-2617.5 2047.5,-2617.5 2041.5,-2611.5 2041.5,-2605.5 2041.5,-2605.5 2041.5,-2261.5 2041.5,-2261.5 2041.5,-2255.5 2047.5,-2249.5 2053.5,-2249.5"/>
<text text-anchor="middle" x="2099" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy</text>
<polyline fill="none" stroke="#000000" points="2156.5,-2249.5 2156.5,-2617.5 "/>
<text text-anchor="middle" x="2167" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2177.5,-2249.5 2177.5,-2617.5 "/>
<text text-anchor="middle" x="2339" y="-2602.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_schedule</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2594.5 2500.5,-2594.5 "/>
<text text-anchor="middle" x="2339" y="-2579.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_first_dose</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2571.5 2500.5,-2571.5 "/>
<text text-anchor="middle" x="2339" y="-2556.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_number_of_doses_any_therapy</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2548.5 2500.5,-2548.5 "/>
<text text-anchor="middle" x="2339" y="-2533.3" font-family="Times,serif" font-size="14.00" fill="#000000">best_response</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2525.5 2500.5,-2525.5 "/>
<text text-anchor="middle" x="2339" y="-2510.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapy_type</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2502.5 2500.5,-2502.5 "/>
<text text-anchor="middle" x="2339" y="-2487.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_in_minimal_residual</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2479.5 2500.5,-2479.5 "/>
<text text-anchor="middle" x="2339" y="-2464.3" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy_type</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2456.5 2500.5,-2456.5 "/>
<text text-anchor="middle" x="2339" y="-2441.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_dose</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2433.5 2500.5,-2433.5 "/>
<text text-anchor="middle" x="2339" y="-2418.3" font-family="Times,serif" font-size="14.00" fill="#000000">any_therapy</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2410.5 2500.5,-2410.5 "/>
<text text-anchor="middle" x="2339" y="-2395.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2387.5 2500.5,-2387.5 "/>
<text text-anchor="middle" x="2339" y="-2372.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2364.5 2500.5,-2364.5 "/>
<text text-anchor="middle" x="2339" y="-2349.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_at_site</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2341.5 2500.5,-2341.5 "/>
<text text-anchor="middle" x="2339" y="-2326.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_name</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2318.5 2500.5,-2318.5 "/>
<text text-anchor="middle" x="2339" y="-2303.3" font-family="Times,serif" font-size="14.00" fill="#000000">nonresponse_therapy_type</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2295.5 2500.5,-2295.5 "/>
<text text-anchor="middle" x="2339" y="-2280.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose_any_therapy</text>
<polyline fill="none" stroke="#000000" points="2177.5,-2272.5 2500.5,-2272.5 "/>
<text text-anchor="middle" x="2339" y="-2257.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_prior_regimens_any_therapy</text>
<polyline fill="none" stroke="#000000" points="2500.5,-2249.5 2500.5,-2617.5 "/>
<text text-anchor="middle" x="2511" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_therapy&#45;&gt;prior_therapy -->
<g id="edge2" class="edge">
<title>prior_therapy&#45;&gt;prior_therapy</title>
<path fill="none" stroke="#000000" d="M2521.7384,-2458.2536C2532.9387,-2452.0051 2539.5,-2443.7539 2539.5,-2433.5 2539.5,-2426.13 2536.1104,-2419.7946 2530.045,-2414.4938"/>
<polygon fill="#000000" stroke="#000000" points="2531.9534,-2411.5581 2521.7384,-2408.7464 2527.9704,-2417.3146 2531.9534,-2411.5581"/>
<text text-anchor="middle" x="2555.5" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- enrollment -->
<g id="node10" class="node">
<title>enrollment</title>
<path fill="none" stroke="#000000" d="M1830.5,-1487C1830.5,-1487 2148.5,-1487 2148.5,-1487 2154.5,-1487 2160.5,-1493 2160.5,-1499 2160.5,-1499 2160.5,-1613 2160.5,-1613 2160.5,-1619 2154.5,-1625 2148.5,-1625 2148.5,-1625 1830.5,-1625 1830.5,-1625 1824.5,-1625 1818.5,-1619 1818.5,-1613 1818.5,-1613 1818.5,-1499 1818.5,-1499 1818.5,-1493 1824.5,-1487 1830.5,-1487"/>
<text text-anchor="middle" x="1866" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrollment</text>
<polyline fill="none" stroke="#000000" points="1913.5,-1487 1913.5,-1625 "/>
<text text-anchor="middle" x="1924" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1934.5,-1487 1934.5,-1625 "/>
<text text-anchor="middle" x="2037" y="-1609.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_informed_consent</text>
<polyline fill="none" stroke="#000000" points="1934.5,-1602 2139.5,-1602 "/>
<text text-anchor="middle" x="2037" y="-1586.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_short_name</text>
<polyline fill="none" stroke="#000000" points="1934.5,-1579 2139.5,-1579 "/>
<text text-anchor="middle" x="2037" y="-1563.8" font-family="Times,serif" font-size="14.00" fill="#000000">patient_subgroup</text>
<polyline fill="none" stroke="#000000" points="1934.5,-1556 2139.5,-1556 "/>
<text text-anchor="middle" x="2037" y="-1540.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1934.5,-1533 2139.5,-1533 "/>
<text text-anchor="middle" x="2037" y="-1517.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_registration</text>
<polyline fill="none" stroke="#000000" points="1934.5,-1510 2139.5,-1510 "/>
<text text-anchor="middle" x="2037" y="-1494.8" font-family="Times,serif" font-size="14.00" fill="#000000">registering_institution</text>
<polyline fill="none" stroke="#000000" points="2139.5,-1487 2139.5,-1625 "/>
<text text-anchor="middle" x="2150" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_therapy&#45;&gt;enrollment -->
<g id="edge17" class="edge">
<title>prior_therapy&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M2220.1983,-2249.2799C2156.9871,-2059.3216 2061.3964,-1772.0584 2015.6686,-1634.6404"/>
<polygon fill="#000000" stroke="#000000" points="2018.942,-1633.3919 2012.4635,-1625.0086 2012.3001,-1635.6022 2018.942,-1633.3919"/>
<text text-anchor="middle" x="2261.5" y="-2008.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- enrollment&#45;&gt;case -->
<g id="edge24" class="edge">
<title>enrollment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1949.2582,-1486.7917C1917.2107,-1437.7495 1867.9423,-1374.2809 1808.5,-1337 1719.8438,-1281.3967 1604.7766,-1254.1563 1513.8624,-1240.8119"/>
<polygon fill="#000000" stroke="#000000" points="1514.1365,-1237.3156 1503.7425,-1239.369 1513.1483,-1244.2455 1514.1365,-1237.3156"/>
<text text-anchor="middle" x="1803.5" y="-1307.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge12" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1276.4057,-518.3353C1271.9764,-512.6757 1268.1252,-506.5142 1265.5,-500 1262.4552,-492.4446 1260.8162,-484.6296 1260.2962,-476.7187"/>
<polygon fill="#000000" stroke="#000000" points="1263.7957,-476.6303 1260.2145,-466.6591 1256.7959,-476.6872 1263.7957,-476.6303"/>
<text text-anchor="middle" x="1306" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge16" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1339.3423,-518.4499C1342.2941,-512.5108 1344.8573,-506.2369 1346.5,-500 1348.5019,-492.3994 1349.6276,-484.5498 1350.0545,-476.6129"/>
<polygon fill="#000000" stroke="#000000" points="1353.5555,-476.586 1350.2348,-466.525 1346.5566,-476.4608 1353.5555,-476.586"/>
<text text-anchor="middle" x="1380" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- agent_administration -->
<g id="node12" class="node">
<title>agent_administration</title>
<path fill="none" stroke="#000000" d="M1823,-727.5C1823,-727.5 2292,-727.5 2292,-727.5 2298,-727.5 2304,-733.5 2304,-739.5 2304,-739.5 2304,-1106.5 2304,-1106.5 2304,-1112.5 2298,-1118.5 2292,-1118.5 2292,-1118.5 1823,-1118.5 1823,-1118.5 1817,-1118.5 1811,-1112.5 1811,-1106.5 1811,-1106.5 1811,-739.5 1811,-739.5 1811,-733.5 1817,-727.5 1823,-727.5"/>
<text text-anchor="middle" x="1896" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_administration</text>
<polyline fill="none" stroke="#000000" points="1981,-727.5 1981,-1118.5 "/>
<text text-anchor="middle" x="1991.5" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2002,-727.5 2002,-1118.5 "/>
<text text-anchor="middle" x="2142.5" y="-1103.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_amount</text>
<polyline fill="none" stroke="#000000" points="2002,-1095.5 2283,-1095.5 "/>
<text text-anchor="middle" x="2142.5" y="-1080.3" font-family="Times,serif" font-size="14.00" fill="#000000">stop_time</text>
<polyline fill="none" stroke="#000000" points="2002,-1072.5 2283,-1072.5 "/>
<text text-anchor="middle" x="2142.5" y="-1057.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2002,-1049.5 2283,-1049.5 "/>
<text text-anchor="middle" x="2142.5" y="-1034.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_missed_dose</text>
<polyline fill="none" stroke="#000000" points="2002,-1026.5 2283,-1026.5 "/>
<text text-anchor="middle" x="2142.5" y="-1011.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_duration</text>
<polyline fill="none" stroke="#000000" points="2002,-1003.5 2283,-1003.5 "/>
<text text-anchor="middle" x="2142.5" y="-988.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2002,-980.5 2283,-980.5 "/>
<text text-anchor="middle" x="2142.5" y="-965.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_missed_dose</text>
<polyline fill="none" stroke="#000000" points="2002,-957.5 2283,-957.5 "/>
<text text-anchor="middle" x="2142.5" y="-942.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_dose</text>
<polyline fill="none" stroke="#000000" points="2002,-934.5 2283,-934.5 "/>
<text text-anchor="middle" x="2142.5" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_course_number</text>
<polyline fill="none" stroke="#000000" points="2002,-911.5 2283,-911.5 "/>
<text text-anchor="middle" x="2142.5" y="-896.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_time</text>
<polyline fill="none" stroke="#000000" points="2002,-888.5 2283,-888.5 "/>
<text text-anchor="middle" x="2142.5" y="-873.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2002,-865.5 2283,-865.5 "/>
<text text-anchor="middle" x="2142.5" y="-850.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="2002,-842.5 2283,-842.5 "/>
<text text-anchor="middle" x="2142.5" y="-827.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2002,-819.5 2283,-819.5 "/>
<text text-anchor="middle" x="2142.5" y="-804.3" font-family="Times,serif" font-size="14.00" fill="#000000">route_of_administration</text>
<polyline fill="none" stroke="#000000" points="2002,-796.5 2283,-796.5 "/>
<text text-anchor="middle" x="2142.5" y="-781.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_vial_id</text>
<polyline fill="none" stroke="#000000" points="2002,-773.5 2283,-773.5 "/>
<text text-anchor="middle" x="2142.5" y="-758.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_level</text>
<polyline fill="none" stroke="#000000" points="2002,-750.5 2283,-750.5 "/>
<text text-anchor="middle" x="2142.5" y="-735.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_lot_number</text>
<polyline fill="none" stroke="#000000" points="2283,-727.5 2283,-1118.5 "/>
<text text-anchor="middle" x="2293.5" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- agent -->
<g id="node23" class="node">
<title>agent</title>
<path fill="none" stroke="#000000" d="M1448,-639.5C1448,-639.5 1619,-639.5 1619,-639.5 1625,-639.5 1631,-645.5 1631,-651.5 1631,-651.5 1631,-663.5 1631,-663.5 1631,-669.5 1625,-675.5 1619,-675.5 1619,-675.5 1448,-675.5 1448,-675.5 1442,-675.5 1436,-669.5 1436,-663.5 1436,-663.5 1436,-651.5 1436,-651.5 1436,-645.5 1442,-639.5 1448,-639.5"/>
<text text-anchor="middle" x="1464.5" y="-653.8" font-family="Times,serif" font-size="14.00" fill="#000000">agent</text>
<polyline fill="none" stroke="#000000" points="1493,-639.5 1493,-675.5 "/>
<text text-anchor="middle" x="1503.5" y="-653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1514,-639.5 1514,-675.5 "/>
<text text-anchor="middle" x="1562" y="-653.8" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="1610,-639.5 1610,-675.5 "/>
<text text-anchor="middle" x="1620.5" y="-653.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- agent_administration&#45;&gt;agent -->
<g id="edge32" class="edge">
<title>agent_administration&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M1810.9293,-731.7219C1807.7884,-730.1079 1804.6447,-728.533 1801.5,-727 1751.2725,-702.515 1691.3979,-685.9359 1640.9952,-675.1315"/>
<polygon fill="#000000" stroke="#000000" points="1641.5518,-671.6722 1631.0466,-673.047 1640.1162,-678.5235 1641.5518,-671.6722"/>
<text text-anchor="middle" x="1784.5" y="-697.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- follow_up -->
<g id="node13" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M2190.5,-1498.5C2190.5,-1498.5 2522.5,-1498.5 2522.5,-1498.5 2528.5,-1498.5 2534.5,-1504.5 2534.5,-1510.5 2534.5,-1510.5 2534.5,-1601.5 2534.5,-1601.5 2534.5,-1607.5 2528.5,-1613.5 2522.5,-1613.5 2522.5,-1613.5 2190.5,-1613.5 2190.5,-1613.5 2184.5,-1613.5 2178.5,-1607.5 2178.5,-1601.5 2178.5,-1601.5 2178.5,-1510.5 2178.5,-1510.5 2178.5,-1504.5 2184.5,-1498.5 2190.5,-1498.5"/>
<text text-anchor="middle" x="2221" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="2263.5,-1498.5 2263.5,-1613.5 "/>
<text text-anchor="middle" x="2274" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2284.5,-1498.5 2284.5,-1613.5 "/>
<text text-anchor="middle" x="2399" y="-1598.3" font-family="Times,serif" font-size="14.00" fill="#000000">contact_type</text>
<polyline fill="none" stroke="#000000" points="2284.5,-1590.5 2513.5,-1590.5 "/>
<text text-anchor="middle" x="2399" y="-1575.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_status</text>
<polyline fill="none" stroke="#000000" points="2284.5,-1567.5 2513.5,-1567.5 "/>
<text text-anchor="middle" x="2399" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">explain_unknown_status</text>
<polyline fill="none" stroke="#000000" points="2284.5,-1544.5 2513.5,-1544.5 "/>
<text text-anchor="middle" x="2399" y="-1529.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_since_last_contact</text>
<polyline fill="none" stroke="#000000" points="2284.5,-1521.5 2513.5,-1521.5 "/>
<text text-anchor="middle" x="2399" y="-1506.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_contact</text>
<polyline fill="none" stroke="#000000" points="2513.5,-1498.5 2513.5,-1613.5 "/>
<text text-anchor="middle" x="2524" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;case -->
<g id="edge29" class="edge">
<title>follow_up&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2324.226,-1498.454C2292.0864,-1447.0261 2237.7547,-1374.2201 2169.5,-1337 2059.5506,-1277.0433 1715.0068,-1247.8428 1513.7527,-1235.5622"/>
<polygon fill="#000000" stroke="#000000" points="1513.8771,-1232.0635 1503.6844,-1234.9547 1513.4554,-1239.0507 1513.8771,-1232.0635"/>
<text text-anchor="middle" x="2150.5" y="-1307.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- case&#45;&gt;cohort -->
<g id="edge7" class="edge">
<title>case&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M1223.1406,-1172.7551C1215.2158,-1166.5128 1207.8912,-1159.6145 1201.5,-1152 1153.7412,-1095.0997 1142.5029,-1004.7085 1140.0313,-956.2602"/>
<polygon fill="#000000" stroke="#000000" points="1143.5181,-955.8673 1139.6089,-946.0201 1136.5241,-956.1558 1143.5181,-955.8673"/>
<text text-anchor="middle" x="1242" y="-1140.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- case&#45;&gt;study_arm -->
<g id="edge9" class="edge">
<title>case&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1332.1958,-1170.4355C1324.9201,-1154.2626 1318.2194,-1136.3451 1314.5,-1119 1273.699,-928.7281 1297.2198,-694.1326 1309.9632,-597.6494"/>
<polygon fill="#000000" stroke="#000000" points="1313.4422,-598.0396 1311.3097,-587.6616 1306.5049,-597.1043 1313.4422,-598.0396"/>
<text text-anchor="middle" x="1340" y="-697.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- case&#45;&gt;study -->
<g id="edge8" class="edge">
<title>case&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1503.7383,-1221.4622C1754.0108,-1208.4192 2256.7517,-1175.459 2312.5,-1119 2374.0233,-1056.6924 2332.5,-1010.5635 2332.5,-923 2332.5,-923 2332.5,-923 2332.5,-553 2332.5,-467.0293 1765.5604,-397.0598 1478.6908,-367.1583"/>
<polygon fill="#000000" stroke="#000000" points="1478.9134,-363.6627 1468.6055,-366.1115 1478.1907,-370.6253 1478.9134,-363.6627"/>
<text text-anchor="middle" x="2373" y="-653.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- adverse_event -->
<g id="node19" class="node">
<title>adverse_event</title>
<path fill="none" stroke="#000000" d="M1336,-808C1336,-808 1731,-808 1731,-808 1737,-808 1743,-814 1743,-820 1743,-820 1743,-1026 1743,-1026 1743,-1032 1737,-1038 1731,-1038 1731,-1038 1336,-1038 1336,-1038 1330,-1038 1324,-1032 1324,-1026 1324,-1026 1324,-820 1324,-820 1324,-814 1330,-808 1336,-808"/>
<text text-anchor="middle" x="1384" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="1444,-808 1444,-1038 "/>
<text text-anchor="middle" x="1454.5" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1465,-808 1465,-1038 "/>
<text text-anchor="middle" x="1593.5" y="-1022.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_attribution</text>
<polyline fill="none" stroke="#000000" points="1465,-1015 1722,-1015 "/>
<text text-anchor="middle" x="1593.5" y="-999.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_other</text>
<polyline fill="none" stroke="#000000" points="1465,-992 1722,-992 "/>
<text text-anchor="middle" x="1593.5" y="-976.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade</text>
<polyline fill="none" stroke="#000000" points="1465,-969 1722,-969 "/>
<text text-anchor="middle" x="1593.5" y="-953.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_description</text>
<polyline fill="none" stroke="#000000" points="1465,-946 1722,-946 "/>
<text text-anchor="middle" x="1593.5" y="-930.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_dose</text>
<polyline fill="none" stroke="#000000" points="1465,-923 1722,-923 "/>
<text text-anchor="middle" x="1593.5" y="-907.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_agent_name</text>
<polyline fill="none" stroke="#000000" points="1465,-900 1722,-900 "/>
<text text-anchor="middle" x="1593.5" y="-884.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_term</text>
<polyline fill="none" stroke="#000000" points="1465,-877 1722,-877 "/>
<text text-anchor="middle" x="1593.5" y="-861.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade_description</text>
<polyline fill="none" stroke="#000000" points="1465,-854 1722,-854 "/>
<text text-anchor="middle" x="1593.5" y="-838.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_resolved</text>
<polyline fill="none" stroke="#000000" points="1465,-831 1722,-831 "/>
<text text-anchor="middle" x="1593.5" y="-815.8" font-family="Times,serif" font-size="14.00" fill="#000000">unexpected_adverse_event</text>
<polyline fill="none" stroke="#000000" points="1722,-808 1722,-1038 "/>
<text text-anchor="middle" x="1732.5" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;adverse_event -->
<g id="edge20" class="edge">
<title>case&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M1395.6756,-1170.2733C1415.0824,-1135.455 1440.576,-1089.7166 1464.3536,-1047.0569"/>
<polygon fill="#000000" stroke="#000000" points="1467.4295,-1048.7272 1469.2409,-1038.2883 1461.3151,-1045.3191 1467.4295,-1048.7272"/>
<text text-anchor="middle" x="1483.5" y="-1140.8" font-family="Times,serif" font-size="14.00" fill="#000000">had_adverse_event</text>
</g>
<!-- stratification -->
<g id="node15" class="node">
<title>stratification</title>
<path fill="none" stroke="#000000" d="M2564.5,-1487C2564.5,-1487 2976.5,-1487 2976.5,-1487 2982.5,-1487 2988.5,-1493 2988.5,-1499 2988.5,-1499 2988.5,-1613 2988.5,-1613 2988.5,-1619 2982.5,-1625 2976.5,-1625 2976.5,-1625 2564.5,-1625 2564.5,-1625 2558.5,-1625 2552.5,-1619 2552.5,-1613 2552.5,-1613 2552.5,-1499 2552.5,-1499 2552.5,-1493 2558.5,-1487 2564.5,-1487"/>
<text text-anchor="middle" x="2607.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification</text>
<polyline fill="none" stroke="#000000" points="2662.5,-1487 2662.5,-1625 "/>
<text text-anchor="middle" x="2673" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2683.5,-1487 2683.5,-1625 "/>
<text text-anchor="middle" x="2825.5" y="-1609.8" font-family="Times,serif" font-size="14.00" fill="#000000">combined_stratification_variable</text>
<polyline fill="none" stroke="#000000" points="2683.5,-1602 2967.5,-1602 "/>
<text text-anchor="middle" x="2825.5" y="-1586.8" font-family="Times,serif" font-size="14.00" fill="#000000">grouped_recurrence_score</text>
<polyline fill="none" stroke="#000000" points="2683.5,-1579 2967.5,-1579 "/>
<text text-anchor="middle" x="2825.5" y="-1563.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_chemotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="2683.5,-1556 2967.5,-1556 "/>
<text text-anchor="middle" x="2825.5" y="-1540.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_radiotherapy</text>
<polyline fill="none" stroke="#000000" points="2683.5,-1533 2967.5,-1533 "/>
<text text-anchor="middle" x="2825.5" y="-1517.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_stratification</text>
<polyline fill="none" stroke="#000000" points="2683.5,-1510 2967.5,-1510 "/>
<text text-anchor="middle" x="2825.5" y="-1494.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status_stratification</text>
<polyline fill="none" stroke="#000000" points="2967.5,-1487 2967.5,-1625 "/>
<text text-anchor="middle" x="2978" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- stratification&#45;&gt;case -->
<g id="edge28" class="edge">
<title>stratification&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2720.1894,-1486.8467C2678.92,-1435.9499 2615.6814,-1370.0853 2543.5,-1337 2452.0086,-1295.0637 1810.9491,-1253.5523 1513.9278,-1236.3182"/>
<polygon fill="#000000" stroke="#000000" points="1513.6939,-1232.7989 1503.5084,-1235.7154 1513.2895,-1239.7872 1513.6939,-1232.7989"/>
<text text-anchor="middle" x="2489.5" y="-1307.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- program -->
<g id="node20" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M1162.5,-.5C1162.5,-.5 1470.5,-.5 1470.5,-.5 1476.5,-.5 1482.5,-6.5 1482.5,-12.5 1482.5,-12.5 1482.5,-172.5 1482.5,-172.5 1482.5,-178.5 1476.5,-184.5 1470.5,-184.5 1470.5,-184.5 1162.5,-184.5 1162.5,-184.5 1156.5,-184.5 1150.5,-178.5 1150.5,-172.5 1150.5,-172.5 1150.5,-12.5 1150.5,-12.5 1150.5,-6.5 1156.5,-.5 1162.5,-.5"/>
<text text-anchor="middle" x="1189.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1228.5,-.5 1228.5,-184.5 "/>
<text text-anchor="middle" x="1239" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1249.5,-.5 1249.5,-184.5 "/>
<text text-anchor="middle" x="1355.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="1249.5,-161.5 1461.5,-161.5 "/>
<text text-anchor="middle" x="1355.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="1249.5,-138.5 1461.5,-138.5 "/>
<text text-anchor="middle" x="1355.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="1249.5,-115.5 1461.5,-115.5 "/>
<text text-anchor="middle" x="1355.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="1249.5,-92.5 1461.5,-92.5 "/>
<text text-anchor="middle" x="1355.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="1249.5,-69.5 1461.5,-69.5 "/>
<text text-anchor="middle" x="1355.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="1249.5,-46.5 1461.5,-46.5 "/>
<text text-anchor="middle" x="1355.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1249.5,-23.5 1461.5,-23.5 "/>
<text text-anchor="middle" x="1355.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="1461.5,-.5 1461.5,-184.5 "/>
<text text-anchor="middle" x="1472" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge13" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1316.5,-236.3905C1316.5,-222.6101 1316.5,-208.6095 1316.5,-195.0235"/>
<polygon fill="#000000" stroke="#000000" points="1320.0001,-194.7254 1316.5,-184.7255 1313.0001,-194.7255 1320.0001,-194.7254"/>
<text text-anchor="middle" x="1357" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- genomic_report&#45;&gt;assay -->
<g id="edge22" class="edge">
<title>genomic_report&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M541.6657,-2669.4213C541.8739,-2658.1131 542.1467,-2646.8621 542.5,-2636 544.5247,-2573.7426 549.4798,-2500.8501 552.3496,-2461.7365"/>
<polygon fill="#000000" stroke="#000000" points="555.8493,-2461.8689 553.0996,-2451.6372 548.8685,-2461.3505 555.8493,-2461.8689"/>
<text text-anchor="middle" x="573" y="-2639.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- prior_surgery -->
<g id="node18" class="node">
<title>prior_surgery</title>
<path fill="none" stroke="#000000" d="M1615.5,-2364.5C1615.5,-2364.5 1961.5,-2364.5 1961.5,-2364.5 1967.5,-2364.5 1973.5,-2370.5 1973.5,-2376.5 1973.5,-2376.5 1973.5,-2490.5 1973.5,-2490.5 1973.5,-2496.5 1967.5,-2502.5 1961.5,-2502.5 1961.5,-2502.5 1615.5,-2502.5 1615.5,-2502.5 1609.5,-2502.5 1603.5,-2496.5 1603.5,-2490.5 1603.5,-2490.5 1603.5,-2376.5 1603.5,-2376.5 1603.5,-2370.5 1609.5,-2364.5 1615.5,-2364.5"/>
<text text-anchor="middle" x="1661" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_surgery</text>
<polyline fill="none" stroke="#000000" points="1718.5,-2364.5 1718.5,-2502.5 "/>
<text text-anchor="middle" x="1729" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1739.5,-2364.5 1739.5,-2502.5 "/>
<text text-anchor="middle" x="1846" y="-2487.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomical_site_of_surgery</text>
<polyline fill="none" stroke="#000000" points="1739.5,-2479.5 1952.5,-2479.5 "/>
<text text-anchor="middle" x="1846" y="-2464.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_indicator</text>
<polyline fill="none" stroke="#000000" points="1739.5,-2456.5 1952.5,-2456.5 "/>
<text text-anchor="middle" x="1846" y="-2441.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_finding</text>
<polyline fill="none" stroke="#000000" points="1739.5,-2433.5 1952.5,-2433.5 "/>
<text text-anchor="middle" x="1846" y="-2418.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_surgery</text>
<polyline fill="none" stroke="#000000" points="1739.5,-2410.5 1952.5,-2410.5 "/>
<text text-anchor="middle" x="1846" y="-2395.3" font-family="Times,serif" font-size="14.00" fill="#000000">residual_disease</text>
<polyline fill="none" stroke="#000000" points="1739.5,-2387.5 1952.5,-2387.5 "/>
<text text-anchor="middle" x="1846" y="-2372.3" font-family="Times,serif" font-size="14.00" fill="#000000">procedure</text>
<polyline fill="none" stroke="#000000" points="1952.5,-2364.5 1952.5,-2502.5 "/>
<text text-anchor="middle" x="1963" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_surgery&#45;&gt;enrollment -->
<g id="edge18" class="edge">
<title>prior_surgery&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M1804.356,-2364.2777C1841.2118,-2203.3777 1932.4686,-1804.9805 1971.4154,-1634.9514"/>
<polygon fill="#000000" stroke="#000000" points="1974.8586,-1635.5949 1973.6798,-1625.0658 1968.0353,-1634.0319 1974.8586,-1635.5949"/>
<text text-anchor="middle" x="1980.5" y="-2008.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- prior_surgery&#45;&gt;prior_surgery -->
<g id="edge5" class="edge">
<title>prior_surgery&#45;&gt;prior_surgery</title>
<path fill="none" stroke="#000000" d="M1973.613,-2460.7602C1984.7907,-2454.2762 1991.5,-2445.1895 1991.5,-2433.5 1991.5,-2425.0982 1988.034,-2418.041 1981.934,-2412.3283"/>
<polygon fill="#000000" stroke="#000000" points="1983.7501,-2409.3204 1973.613,-2406.2398 1979.6165,-2414.9696 1983.7501,-2409.3204"/>
<text text-anchor="middle" x="2007.5" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- adverse_event&#45;&gt;adverse_event -->
<g id="edge3" class="edge">
<title>adverse_event&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M1743.2046,-950.2761C1754.376,-943.5862 1761,-934.4941 1761,-923 1761,-914.7386 1757.5781,-907.7181 1751.5052,-901.9385"/>
<polygon fill="#000000" stroke="#000000" points="1753.3073,-898.9155 1743.2046,-895.7239 1749.1119,-904.519 1753.3073,-898.9155"/>
<text text-anchor="middle" x="1777" y="-919.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- adverse_event&#45;&gt;agent -->
<g id="edge33" class="edge">
<title>adverse_event&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M1533.5,-807.7062C1533.5,-762.7855 1533.5,-715.151 1533.5,-685.8617"/>
<polygon fill="#000000" stroke="#000000" points="1537.0001,-685.5784 1533.5,-675.5784 1530.0001,-685.5784 1537.0001,-685.5784"/>
<text text-anchor="middle" x="1564.5" y="-697.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- visit -->
<g id="node21" class="node">
<title>visit</title>
<path fill="none" stroke="#000000" d="M1049,-3308C1049,-3308 1224,-3308 1224,-3308 1230,-3308 1236,-3314 1236,-3320 1236,-3320 1236,-3342 1236,-3342 1236,-3348 1230,-3354 1224,-3354 1224,-3354 1049,-3354 1049,-3354 1043,-3354 1037,-3348 1037,-3342 1037,-3342 1037,-3320 1037,-3320 1037,-3314 1043,-3308 1049,-3308"/>
<text text-anchor="middle" x="1060.5" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000">visit</text>
<polyline fill="none" stroke="#000000" points="1084,-3308 1084,-3354 "/>
<text text-anchor="middle" x="1094.5" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1105,-3308 1105,-3354 "/>
<text text-anchor="middle" x="1160" y="-3338.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_number</text>
<polyline fill="none" stroke="#000000" points="1105,-3331 1215,-3331 "/>
<text text-anchor="middle" x="1160" y="-3315.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_date</text>
<polyline fill="none" stroke="#000000" points="1215,-3308 1215,-3354 "/>
<text text-anchor="middle" x="1225.5" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- visit&#45;&gt;visit -->
<g id="edge4" class="edge">
<title>visit&#45;&gt;visit</title>
<path fill="none" stroke="#000000" d="M1148.7183,-3354.2371C1189.9427,-3419.6803 1254,-3411.9346 1254,-3331 1254,-3253.7012 1195.5686,-3243.1633 1154.4043,-3299.3865"/>
<polygon fill="#000000" stroke="#000000" points="1151.4389,-3297.5233 1148.7183,-3307.7629 1157.2306,-3301.4548 1151.4389,-3297.5233"/>
<text text-anchor="middle" x="1270" y="-3327.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- sample -->
<g id="node24" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M379,-1337.5C379,-1337.5 802,-1337.5 802,-1337.5 808,-1337.5 814,-1343.5 814,-1349.5 814,-1349.5 814,-1762.5 814,-1762.5 814,-1768.5 808,-1774.5 802,-1774.5 802,-1774.5 379,-1774.5 379,-1774.5 373,-1774.5 367,-1768.5 367,-1762.5 367,-1762.5 367,-1349.5 367,-1349.5 367,-1343.5 373,-1337.5 379,-1337.5"/>
<text text-anchor="middle" x="401" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="435,-1337.5 435,-1774.5 "/>
<text text-anchor="middle" x="445.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="456,-1337.5 456,-1774.5 "/>
<text text-anchor="middle" x="624.5" y="-1759.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_tissue_area</text>
<polyline fill="none" stroke="#000000" points="456,-1751.5 793,-1751.5 "/>
<text text-anchor="middle" x="624.5" y="-1736.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="456,-1728.5 793,-1728.5 "/>
<text text-anchor="middle" x="624.5" y="-1713.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="456,-1705.5 793,-1705.5 "/>
<text text-anchor="middle" x="624.5" y="-1690.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="456,-1682.5 793,-1682.5 "/>
<text text-anchor="middle" x="624.5" y="-1667.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="456,-1659.5 793,-1659.5 "/>
<text text-anchor="middle" x="624.5" y="-1644.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="456,-1636.5 793,-1636.5 "/>
<text text-anchor="middle" x="624.5" y="-1621.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_tumor</text>
<polyline fill="none" stroke="#000000" points="456,-1613.5 793,-1613.5 "/>
<text text-anchor="middle" x="624.5" y="-1598.3" font-family="Times,serif" font-size="14.00" fill="#000000">necropsy_sample</text>
<polyline fill="none" stroke="#000000" points="456,-1590.5 793,-1590.5 "/>
<text text-anchor="middle" x="624.5" y="-1575.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_glass</text>
<polyline fill="none" stroke="#000000" points="456,-1567.5 793,-1567.5 "/>
<text text-anchor="middle" x="624.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area</text>
<polyline fill="none" stroke="#000000" points="456,-1544.5 793,-1544.5 "/>
<text text-anchor="middle" x="624.5" y="-1529.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="456,-1521.5 793,-1521.5 "/>
<text text-anchor="middle" x="624.5" y="-1506.3" font-family="Times,serif" font-size="14.00" fill="#000000">width_of_tumor</text>
<polyline fill="none" stroke="#000000" points="456,-1498.5 793,-1498.5 "/>
<text text-anchor="middle" x="624.5" y="-1483.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="456,-1475.5 793,-1475.5 "/>
<text text-anchor="middle" x="624.5" y="-1460.3" font-family="Times,serif" font-size="14.00" fill="#000000">non_tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="456,-1452.5 793,-1452.5 "/>
<text text-anchor="middle" x="624.5" y="-1437.3" font-family="Times,serif" font-size="14.00" fill="#000000">general_sample_pathology</text>
<polyline fill="none" stroke="#000000" points="456,-1429.5 793,-1429.5 "/>
<text text-anchor="middle" x="624.5" y="-1414.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_sample_collection</text>
<polyline fill="none" stroke="#000000" points="456,-1406.5 793,-1406.5 "/>
<text text-anchor="middle" x="624.5" y="-1391.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="456,-1383.5 793,-1383.5 "/>
<text text-anchor="middle" x="624.5" y="-1368.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_status_date</text>
<polyline fill="none" stroke="#000000" points="456,-1360.5 793,-1360.5 "/>
<text text-anchor="middle" x="624.5" y="-1345.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_pigmented_tumor</text>
<polyline fill="none" stroke="#000000" points="793,-1337.5 793,-1774.5 "/>
<text text-anchor="middle" x="803.5" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>assay&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M555.2519,-2415.1722C558.5302,-2335.2645 571.8246,-2011.2117 581.114,-1784.7844"/>
<polygon fill="#000000" stroke="#000000" points="584.6126,-1784.887 581.5256,-1774.7519 577.6185,-1784.6 584.6126,-1784.887"/>
<text text-anchor="middle" x="617" y="-2008.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- agent&#45;&gt;study_arm -->
<g id="edge6" class="edge">
<title>agent&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1495.7015,-639.2975C1468.7299,-626.3089 1431.434,-608.3484 1397.8477,-592.1744"/>
<polygon fill="#000000" stroke="#000000" points="1399.013,-588.8509 1388.4847,-587.6654 1395.9758,-595.1577 1399.013,-588.8509"/>
<text text-anchor="middle" x="1506" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- sample&#45;&gt;case -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M779.4284,-1337.3875C796.4047,-1324.7683 814.1495,-1313.4116 832.5,-1304 897.108,-1270.8638 1080.029,-1249.8971 1213.1546,-1238.5691"/>
<polygon fill="#000000" stroke="#000000" points="1213.7832,-1242.0287 1223.4549,-1237.7033 1213.1968,-1235.0533 1213.7832,-1242.0287"/>
<text text-anchor="middle" x="859.5" y="-1307.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- sample&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>sample&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M814.0955,-1585.6213C825.3572,-1578.2644 832,-1568.3906 832,-1556 832,-1546.9006 828.4175,-1539.1586 822.0541,-1532.774"/>
<polygon fill="#000000" stroke="#000000" points="824.083,-1529.9144 814.0955,-1526.3787 819.6982,-1535.3709 824.083,-1529.9144"/>
<text text-anchor="middle" x="848" y="-1552.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- file -->
<g id="node25" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M772,-2704C772,-2704 957,-2704 957,-2704 963,-2704 969,-2710 969,-2716 969,-2716 969,-2899 969,-2899 969,-2905 963,-2911 957,-2911 957,-2911 772,-2911 772,-2911 766,-2911 760,-2905 760,-2899 760,-2899 760,-2716 760,-2716 760,-2710 766,-2704 772,-2704"/>
<text text-anchor="middle" x="779.5" y="-2803.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="799,-2704 799,-2911 "/>
<text text-anchor="middle" x="809.5" y="-2803.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="820,-2704 820,-2911 "/>
<text text-anchor="middle" x="884" y="-2895.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_status</text>
<polyline fill="none" stroke="#000000" points="820,-2888 948,-2888 "/>
<text text-anchor="middle" x="884" y="-2872.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_locations</text>
<polyline fill="none" stroke="#000000" points="820,-2865 948,-2865 "/>
<text text-anchor="middle" x="884" y="-2849.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="820,-2842 948,-2842 "/>
<text text-anchor="middle" x="884" y="-2826.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_format</text>
<polyline fill="none" stroke="#000000" points="820,-2819 948,-2819 "/>
<text text-anchor="middle" x="884" y="-2803.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="820,-2796 948,-2796 "/>
<text text-anchor="middle" x="884" y="-2780.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="820,-2773 948,-2773 "/>
<text text-anchor="middle" x="884" y="-2757.8" font-family="Times,serif" font-size="14.00" fill="#000000">uuid</text>
<polyline fill="none" stroke="#000000" points="820,-2750 948,-2750 "/>
<text text-anchor="middle" x="884" y="-2734.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="820,-2727 948,-2727 "/>
<text text-anchor="middle" x="884" y="-2711.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="948,-2704 948,-2911 "/>
<text text-anchor="middle" x="958.5" y="-2803.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;diagnosis -->
<g id="edge34" class="edge">
<title>file&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M869.1879,-2703.9103C874.475,-2587.0806 883.2361,-2393.4848 890.1485,-2240.7397"/>
<polygon fill="#000000" stroke="#000000" points="893.6453,-2240.887 890.6011,-2230.739 886.6525,-2240.5705 893.6453,-2240.887"/>
<text text-anchor="middle" x="927" y="-2639.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_diagnosis</text>
</g>
<!-- file&#45;&gt;assay -->
<g id="edge23" class="edge">
<title>file&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M794.313,-2703.7035C781.1922,-2690.2392 766.5078,-2678.0202 750.5,-2669 701.9836,-2641.6616 669.1778,-2686.7748 626.5,-2651 569.3749,-2603.1147 557.302,-2508.7828 554.9336,-2461.6667"/>
<polygon fill="#000000" stroke="#000000" points="558.4266,-2461.4164 554.5401,-2451.5602 551.4319,-2461.6888 558.4266,-2461.4164"/>
<text text-anchor="middle" x="657" y="-2639.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge14" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M824.9856,-2703.535C815.2652,-2675.9595 805.3931,-2646.0479 797.5,-2618 749.8718,-2448.7553 745.2846,-2404.2775 715.5,-2231 682.2346,-2037.4722 697.2011,-1985.3108 657.5,-1793 656.9124,-1790.1538 656.3088,-1787.2916 655.6904,-1784.4164"/>
<polygon fill="#000000" stroke="#000000" points="659.097,-1783.6106 653.5329,-1774.5944 652.26,-1785.1125 659.097,-1783.6106"/>
<text text-anchor="middle" x="834" y="-2429.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
</g>
</svg>
</div>
