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
<svg width="2998pt" height="3683pt"
 viewBox="0.00 0.00 2998.00 3683.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 3679)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-3679 2994,-3679 2994,4 -4,4"/>
<!-- stratification -->
<g id="node1" class="node">
<title>stratification</title>
<path fill="none" stroke="#000000" d="M12,-1497C12,-1497 424,-1497 424,-1497 430,-1497 436,-1503 436,-1509 436,-1509 436,-1623 436,-1623 436,-1629 430,-1635 424,-1635 424,-1635 12,-1635 12,-1635 6,-1635 0,-1629 0,-1623 0,-1623 0,-1509 0,-1509 0,-1503 6,-1497 12,-1497"/>
<text text-anchor="middle" x="55" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification</text>
<polyline fill="none" stroke="#000000" points="110,-1497 110,-1635 "/>
<text text-anchor="middle" x="120.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="131,-1497 131,-1635 "/>
<text text-anchor="middle" x="273" y="-1619.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status_stratification</text>
<polyline fill="none" stroke="#000000" points="131,-1612 415,-1612 "/>
<text text-anchor="middle" x="273" y="-1596.8" font-family="Times,serif" font-size="14.00" fill="#000000">combined_stratification_variable</text>
<polyline fill="none" stroke="#000000" points="131,-1589 415,-1589 "/>
<text text-anchor="middle" x="273" y="-1573.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_stratification</text>
<polyline fill="none" stroke="#000000" points="131,-1566 415,-1566 "/>
<text text-anchor="middle" x="273" y="-1550.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_radiotherapy</text>
<polyline fill="none" stroke="#000000" points="131,-1543 415,-1543 "/>
<text text-anchor="middle" x="273" y="-1527.8" font-family="Times,serif" font-size="14.00" fill="#000000">grouped_recurrence_score</text>
<polyline fill="none" stroke="#000000" points="131,-1520 415,-1520 "/>
<text text-anchor="middle" x="273" y="-1504.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_chemotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="415,-1497 415,-1635 "/>
<text text-anchor="middle" x="425.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case -->
<g id="node3" class="node">
<title>case</title>
<path fill="none" stroke="#000000" d="M1361,-1180.5C1361,-1180.5 1617,-1180.5 1617,-1180.5 1623,-1180.5 1629,-1186.5 1629,-1192.5 1629,-1192.5 1629,-1283.5 1629,-1283.5 1629,-1289.5 1623,-1295.5 1617,-1295.5 1617,-1295.5 1361,-1295.5 1361,-1295.5 1355,-1295.5 1349,-1289.5 1349,-1283.5 1349,-1283.5 1349,-1192.5 1349,-1192.5 1349,-1186.5 1355,-1180.5 1361,-1180.5"/>
<text text-anchor="middle" x="1373.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">case</text>
<polyline fill="none" stroke="#000000" points="1398,-1180.5 1398,-1295.5 "/>
<text text-anchor="middle" x="1408.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1419,-1180.5 1419,-1295.5 "/>
<text text-anchor="middle" x="1513.5" y="-1280.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_id</text>
<polyline fill="none" stroke="#000000" points="1419,-1272.5 1608,-1272.5 "/>
<text text-anchor="middle" x="1513.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">included_in_analysis</text>
<polyline fill="none" stroke="#000000" points="1419,-1249.5 1608,-1249.5 "/>
<text text-anchor="middle" x="1513.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">case_id</text>
<polyline fill="none" stroke="#000000" points="1419,-1226.5 1608,-1226.5 "/>
<text text-anchor="middle" x="1513.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">on_study_crf_submitted</text>
<polyline fill="none" stroke="#000000" points="1419,-1203.5 1608,-1203.5 "/>
<text text-anchor="middle" x="1513.5" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">ineligible</text>
<polyline fill="none" stroke="#000000" points="1608,-1180.5 1608,-1295.5 "/>
<text text-anchor="middle" x="1618.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- stratification&#45;&gt;case -->
<g id="edge15" class="edge">
<title>stratification&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M268.6364,-1496.8262C309.9702,-1446.0955 373.1412,-1380.457 445,-1347 600.0039,-1274.8311 1088.7062,-1249.8972 1338.6199,-1241.7275"/>
<polygon fill="#000000" stroke="#000000" points="1338.9911,-1245.2174 1348.8732,-1241.3973 1338.7657,-1238.221 1338.9911,-1245.2174"/>
<text text-anchor="middle" x="573" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- study -->
<g id="node2" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1136,-236.5C1136,-236.5 1416,-236.5 1416,-236.5 1422,-236.5 1428,-242.5 1428,-248.5 1428,-248.5 1428,-454.5 1428,-454.5 1428,-460.5 1422,-466.5 1416,-466.5 1416,-466.5 1136,-466.5 1136,-466.5 1130,-466.5 1124,-460.5 1124,-454.5 1124,-454.5 1124,-248.5 1124,-248.5 1124,-242.5 1130,-236.5 1136,-236.5"/>
<text text-anchor="middle" x="1152" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1180,-236.5 1180,-466.5 "/>
<text text-anchor="middle" x="1190.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1201,-236.5 1201,-466.5 "/>
<text text-anchor="middle" x="1304" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_type</text>
<polyline fill="none" stroke="#000000" points="1201,-443.5 1407,-443.5 "/>
<text text-anchor="middle" x="1304" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_description</text>
<polyline fill="none" stroke="#000000" points="1201,-420.5 1407,-420.5 "/>
<text text-anchor="middle" x="1304" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_term</text>
<polyline fill="none" stroke="#000000" points="1201,-397.5 1407,-397.5 "/>
<text text-anchor="middle" x="1304" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_id</text>
<polyline fill="none" stroke="#000000" points="1201,-374.5 1407,-374.5 "/>
<text text-anchor="middle" x="1304" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">dates_of_conduct</text>
<polyline fill="none" stroke="#000000" points="1201,-351.5 1407,-351.5 "/>
<text text-anchor="middle" x="1304" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_name</text>
<polyline fill="none" stroke="#000000" points="1201,-328.5 1407,-328.5 "/>
<text text-anchor="middle" x="1304" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_category</text>
<polyline fill="none" stroke="#000000" points="1201,-305.5 1407,-305.5 "/>
<text text-anchor="middle" x="1304" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_iacuc_approval</text>
<polyline fill="none" stroke="#000000" points="1201,-282.5 1407,-282.5 "/>
<text text-anchor="middle" x="1304" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_designation</text>
<polyline fill="none" stroke="#000000" points="1201,-259.5 1407,-259.5 "/>
<text text-anchor="middle" x="1304" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_su_category</text>
<polyline fill="none" stroke="#000000" points="1407,-236.5 1407,-466.5 "/>
<text text-anchor="middle" x="1417.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- program -->
<g id="node15" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M1122,-.5C1122,-.5 1430,-.5 1430,-.5 1436,-.5 1442,-6.5 1442,-12.5 1442,-12.5 1442,-172.5 1442,-172.5 1442,-178.5 1436,-184.5 1430,-184.5 1430,-184.5 1122,-184.5 1122,-184.5 1116,-184.5 1110,-178.5 1110,-172.5 1110,-172.5 1110,-12.5 1110,-12.5 1110,-6.5 1116,-.5 1122,-.5"/>
<text text-anchor="middle" x="1149" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1188,-.5 1188,-184.5 "/>
<text text-anchor="middle" x="1198.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1209,-.5 1209,-184.5 "/>
<text text-anchor="middle" x="1315" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="1209,-161.5 1421,-161.5 "/>
<text text-anchor="middle" x="1315" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1209,-138.5 1421,-138.5 "/>
<text text-anchor="middle" x="1315" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="1209,-115.5 1421,-115.5 "/>
<text text-anchor="middle" x="1315" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="1209,-92.5 1421,-92.5 "/>
<text text-anchor="middle" x="1315" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="1209,-69.5 1421,-69.5 "/>
<text text-anchor="middle" x="1315" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="1209,-46.5 1421,-46.5 "/>
<text text-anchor="middle" x="1315" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="1209,-23.5 1421,-23.5 "/>
<text text-anchor="middle" x="1315" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="1421,-.5 1421,-184.5 "/>
<text text-anchor="middle" x="1431.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge6" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1276,-236.3905C1276,-222.6101 1276,-208.6095 1276,-195.0235"/>
<polygon fill="#000000" stroke="#000000" points="1279.5001,-194.7254 1276,-184.7255 1272.5001,-194.7255 1279.5001,-194.7254"/>
<text text-anchor="middle" x="1316.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- case&#45;&gt;study -->
<g id="edge3" class="edge">
<title>case&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1365.1423,-1180.3642C1275.8532,-1129.3256 1171,-1045.4508 1171,-933 1171,-933 1171,-933 1171,-553 1171,-526.6786 1178.1334,-500.3891 1188.6815,-475.9031"/>
<polygon fill="#000000" stroke="#000000" points="1191.9523,-477.1644 1192.8836,-466.6106 1185.5741,-474.2801 1191.9523,-477.1644"/>
<text text-anchor="middle" x="1211.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort -->
<g id="node14" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M1282.5,-639.5C1282.5,-639.5 1515.5,-639.5 1515.5,-639.5 1521.5,-639.5 1527.5,-645.5 1527.5,-651.5 1527.5,-651.5 1527.5,-673.5 1527.5,-673.5 1527.5,-679.5 1521.5,-685.5 1515.5,-685.5 1515.5,-685.5 1282.5,-685.5 1282.5,-685.5 1276.5,-685.5 1270.5,-679.5 1270.5,-673.5 1270.5,-673.5 1270.5,-651.5 1270.5,-651.5 1270.5,-645.5 1276.5,-639.5 1282.5,-639.5"/>
<text text-anchor="middle" x="1302" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="1333.5,-639.5 1333.5,-685.5 "/>
<text text-anchor="middle" x="1344" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1354.5,-639.5 1354.5,-685.5 "/>
<text text-anchor="middle" x="1430.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1354.5,-662.5 1506.5,-662.5 "/>
<text text-anchor="middle" x="1430.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_dose</text>
<polyline fill="none" stroke="#000000" points="1506.5,-639.5 1506.5,-685.5 "/>
<text text-anchor="middle" x="1517" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;cohort -->
<g id="edge1" class="edge">
<title>case&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M1472.8125,-1180.3088C1468.5609,-1163.8263 1464.2587,-1145.7823 1461,-1129 1429.7649,-968.1382 1409.4164,-772.9908 1402.0686,-696.0199"/>
<polygon fill="#000000" stroke="#000000" points="1405.5432,-695.5857 1401.1183,-685.9591 1398.5742,-696.244 1405.5432,-695.5857"/>
<text text-anchor="middle" x="1501.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- study_arm -->
<g id="node20" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1371.5,-518.5C1371.5,-518.5 1740.5,-518.5 1740.5,-518.5 1746.5,-518.5 1752.5,-524.5 1752.5,-530.5 1752.5,-530.5 1752.5,-575.5 1752.5,-575.5 1752.5,-581.5 1746.5,-587.5 1740.5,-587.5 1740.5,-587.5 1371.5,-587.5 1371.5,-587.5 1365.5,-587.5 1359.5,-581.5 1359.5,-575.5 1359.5,-575.5 1359.5,-530.5 1359.5,-530.5 1359.5,-524.5 1365.5,-518.5 1371.5,-518.5"/>
<text text-anchor="middle" x="1405.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1451.5,-518.5 1451.5,-587.5 "/>
<text text-anchor="middle" x="1462" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1472.5,-518.5 1472.5,-587.5 "/>
<text text-anchor="middle" x="1602" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_treatment_assignment_code</text>
<polyline fill="none" stroke="#000000" points="1472.5,-564.5 1731.5,-564.5 "/>
<text text-anchor="middle" x="1602" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm</text>
<polyline fill="none" stroke="#000000" points="1472.5,-541.5 1731.5,-541.5 "/>
<text text-anchor="middle" x="1602" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_arm_version</text>
<polyline fill="none" stroke="#000000" points="1731.5,-518.5 1731.5,-587.5 "/>
<text text-anchor="middle" x="1742" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;study_arm -->
<g id="edge2" class="edge">
<title>case&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1522.6967,-1180.3338C1530.5135,-1164.2349 1537.7756,-1146.3797 1542,-1129 1588.9008,-936.0429 1571.4813,-695.9783 1561.2936,-597.8969"/>
<polygon fill="#000000" stroke="#000000" points="1564.7523,-597.3229 1560.2122,-587.7501 1557.7918,-598.0647 1564.7523,-597.3229"/>
<text text-anchor="middle" x="1611.5" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- adverse_event -->
<g id="node23" class="node">
<title>adverse_event</title>
<path fill="none" stroke="#000000" d="M2107.5,-818C2107.5,-818 2502.5,-818 2502.5,-818 2508.5,-818 2514.5,-824 2514.5,-830 2514.5,-830 2514.5,-1036 2514.5,-1036 2514.5,-1042 2508.5,-1048 2502.5,-1048 2502.5,-1048 2107.5,-1048 2107.5,-1048 2101.5,-1048 2095.5,-1042 2095.5,-1036 2095.5,-1036 2095.5,-830 2095.5,-830 2095.5,-824 2101.5,-818 2107.5,-818"/>
<text text-anchor="middle" x="2155.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="2215.5,-818 2215.5,-1048 "/>
<text text-anchor="middle" x="2226" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2236.5,-818 2236.5,-1048 "/>
<text text-anchor="middle" x="2365" y="-1032.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade_description</text>
<polyline fill="none" stroke="#000000" points="2236.5,-1025 2493.5,-1025 "/>
<text text-anchor="middle" x="2365" y="-1009.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_dose</text>
<polyline fill="none" stroke="#000000" points="2236.5,-1002 2493.5,-1002 "/>
<text text-anchor="middle" x="2365" y="-986.8" font-family="Times,serif" font-size="14.00" fill="#000000">unexpected_adverse_event</text>
<polyline fill="none" stroke="#000000" points="2236.5,-979 2493.5,-979 "/>
<text text-anchor="middle" x="2365" y="-963.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_attribution</text>
<polyline fill="none" stroke="#000000" points="2236.5,-956 2493.5,-956 "/>
<text text-anchor="middle" x="2365" y="-940.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade</text>
<polyline fill="none" stroke="#000000" points="2236.5,-933 2493.5,-933 "/>
<text text-anchor="middle" x="2365" y="-917.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_term</text>
<polyline fill="none" stroke="#000000" points="2236.5,-910 2493.5,-910 "/>
<text text-anchor="middle" x="2365" y="-894.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_description</text>
<polyline fill="none" stroke="#000000" points="2236.5,-887 2493.5,-887 "/>
<text text-anchor="middle" x="2365" y="-871.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_other</text>
<polyline fill="none" stroke="#000000" points="2236.5,-864 2493.5,-864 "/>
<text text-anchor="middle" x="2365" y="-848.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_agent_name</text>
<polyline fill="none" stroke="#000000" points="2236.5,-841 2493.5,-841 "/>
<text text-anchor="middle" x="2365" y="-825.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_resolved</text>
<polyline fill="none" stroke="#000000" points="2493.5,-818 2493.5,-1048 "/>
<text text-anchor="middle" x="2504" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;adverse_event -->
<g id="edge24" class="edge">
<title>case&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M1629.0183,-1221.359C1779.4128,-1201.9216 2007.4016,-1167.4836 2086,-1129 2124.0764,-1110.3569 2160.5063,-1083.1684 2192.3474,-1054.9455"/>
<polygon fill="#000000" stroke="#000000" points="2194.8189,-1057.4302 2199.9154,-1048.1417 2190.1389,-1052.2246 2194.8189,-1057.4302"/>
<text text-anchor="middle" x="2098" y="-1150.8" font-family="Times,serif" font-size="14.00" fill="#000000">had_adverse_event</text>
</g>
<!-- assay -->
<g id="node4" class="node">
<title>assay</title>
<path fill="none" stroke="#000000" d="M1015,-2425.5C1015,-2425.5 1047,-2425.5 1047,-2425.5 1053,-2425.5 1059,-2431.5 1059,-2437.5 1059,-2437.5 1059,-2449.5 1059,-2449.5 1059,-2455.5 1053,-2461.5 1047,-2461.5 1047,-2461.5 1015,-2461.5 1015,-2461.5 1009,-2461.5 1003,-2455.5 1003,-2449.5 1003,-2449.5 1003,-2437.5 1003,-2437.5 1003,-2431.5 1009,-2425.5 1015,-2425.5"/>
<text text-anchor="middle" x="1031" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">assay</text>
</g>
<!-- sample -->
<g id="node7" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M844.5,-1347.5C844.5,-1347.5 1267.5,-1347.5 1267.5,-1347.5 1273.5,-1347.5 1279.5,-1353.5 1279.5,-1359.5 1279.5,-1359.5 1279.5,-1772.5 1279.5,-1772.5 1279.5,-1778.5 1273.5,-1784.5 1267.5,-1784.5 1267.5,-1784.5 844.5,-1784.5 844.5,-1784.5 838.5,-1784.5 832.5,-1778.5 832.5,-1772.5 832.5,-1772.5 832.5,-1359.5 832.5,-1359.5 832.5,-1353.5 838.5,-1347.5 844.5,-1347.5"/>
<text text-anchor="middle" x="866.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="900.5,-1347.5 900.5,-1784.5 "/>
<text text-anchor="middle" x="911" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="921.5,-1347.5 921.5,-1784.5 "/>
<text text-anchor="middle" x="1090" y="-1769.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_tumor</text>
<polyline fill="none" stroke="#000000" points="921.5,-1761.5 1258.5,-1761.5 "/>
<text text-anchor="middle" x="1090" y="-1746.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_status_date</text>
<polyline fill="none" stroke="#000000" points="921.5,-1738.5 1258.5,-1738.5 "/>
<text text-anchor="middle" x="1090" y="-1723.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="921.5,-1715.5 1258.5,-1715.5 "/>
<text text-anchor="middle" x="1090" y="-1700.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_pigmented_tumor</text>
<polyline fill="none" stroke="#000000" points="921.5,-1692.5 1258.5,-1692.5 "/>
<text text-anchor="middle" x="1090" y="-1677.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="921.5,-1669.5 1258.5,-1669.5 "/>
<text text-anchor="middle" x="1090" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">necropsy_sample</text>
<polyline fill="none" stroke="#000000" points="921.5,-1646.5 1258.5,-1646.5 "/>
<text text-anchor="middle" x="1090" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">non_tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="921.5,-1623.5 1258.5,-1623.5 "/>
<text text-anchor="middle" x="1090" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">width_of_tumor</text>
<polyline fill="none" stroke="#000000" points="921.5,-1600.5 1258.5,-1600.5 "/>
<text text-anchor="middle" x="1090" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_glass</text>
<polyline fill="none" stroke="#000000" points="921.5,-1577.5 1258.5,-1577.5 "/>
<text text-anchor="middle" x="1090" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area</text>
<polyline fill="none" stroke="#000000" points="921.5,-1554.5 1258.5,-1554.5 "/>
<text text-anchor="middle" x="1090" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="921.5,-1531.5 1258.5,-1531.5 "/>
<text text-anchor="middle" x="1090" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="921.5,-1508.5 1258.5,-1508.5 "/>
<text text-anchor="middle" x="1090" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_tissue_area</text>
<polyline fill="none" stroke="#000000" points="921.5,-1485.5 1258.5,-1485.5 "/>
<text text-anchor="middle" x="1090" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="921.5,-1462.5 1258.5,-1462.5 "/>
<text text-anchor="middle" x="1090" y="-1447.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="921.5,-1439.5 1258.5,-1439.5 "/>
<text text-anchor="middle" x="1090" y="-1424.3" font-family="Times,serif" font-size="14.00" fill="#000000">general_sample_pathology</text>
<polyline fill="none" stroke="#000000" points="921.5,-1416.5 1258.5,-1416.5 "/>
<text text-anchor="middle" x="1090" y="-1401.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_sample_collection</text>
<polyline fill="none" stroke="#000000" points="921.5,-1393.5 1258.5,-1393.5 "/>
<text text-anchor="middle" x="1090" y="-1378.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="921.5,-1370.5 1258.5,-1370.5 "/>
<text text-anchor="middle" x="1090" y="-1355.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="1258.5,-1347.5 1258.5,-1784.5 "/>
<text text-anchor="middle" x="1269" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay&#45;&gt;sample -->
<g id="edge31" class="edge">
<title>assay&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1031.5222,-2425.1722C1033.7987,-2345.2645 1043.031,-2021.2117 1049.4819,-1794.7844"/>
<polygon fill="#000000" stroke="#000000" points="1052.9815,-1794.8476 1049.7678,-1784.7519 1045.9843,-1794.6482 1052.9815,-1794.8476"/>
<text text-anchor="middle" x="1085.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- prior_surgery -->
<g id="node5" class="node">
<title>prior_surgery</title>
<path fill="none" stroke="#000000" d="M1603,-2374.5C1603,-2374.5 1949,-2374.5 1949,-2374.5 1955,-2374.5 1961,-2380.5 1961,-2386.5 1961,-2386.5 1961,-2500.5 1961,-2500.5 1961,-2506.5 1955,-2512.5 1949,-2512.5 1949,-2512.5 1603,-2512.5 1603,-2512.5 1597,-2512.5 1591,-2506.5 1591,-2500.5 1591,-2500.5 1591,-2386.5 1591,-2386.5 1591,-2380.5 1597,-2374.5 1603,-2374.5"/>
<text text-anchor="middle" x="1648.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_surgery</text>
<polyline fill="none" stroke="#000000" points="1706,-2374.5 1706,-2512.5 "/>
<text text-anchor="middle" x="1716.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1727,-2374.5 1727,-2512.5 "/>
<text text-anchor="middle" x="1833.5" y="-2497.3" font-family="Times,serif" font-size="14.00" fill="#000000">procedure</text>
<polyline fill="none" stroke="#000000" points="1727,-2489.5 1940,-2489.5 "/>
<text text-anchor="middle" x="1833.5" y="-2474.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomical_site_of_surgery</text>
<polyline fill="none" stroke="#000000" points="1727,-2466.5 1940,-2466.5 "/>
<text text-anchor="middle" x="1833.5" y="-2451.3" font-family="Times,serif" font-size="14.00" fill="#000000">residual_disease</text>
<polyline fill="none" stroke="#000000" points="1727,-2443.5 1940,-2443.5 "/>
<text text-anchor="middle" x="1833.5" y="-2428.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_surgery</text>
<polyline fill="none" stroke="#000000" points="1727,-2420.5 1940,-2420.5 "/>
<text text-anchor="middle" x="1833.5" y="-2405.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_finding</text>
<polyline fill="none" stroke="#000000" points="1727,-2397.5 1940,-2397.5 "/>
<text text-anchor="middle" x="1833.5" y="-2382.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_indicator</text>
<polyline fill="none" stroke="#000000" points="1940,-2374.5 1940,-2512.5 "/>
<text text-anchor="middle" x="1950.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_surgery&#45;&gt;prior_surgery -->
<g id="edge28" class="edge">
<title>prior_surgery&#45;&gt;prior_surgery</title>
<path fill="none" stroke="#000000" d="M1961.113,-2470.7602C1972.2907,-2464.2762 1979,-2455.1895 1979,-2443.5 1979,-2435.0982 1975.534,-2428.041 1969.434,-2422.3283"/>
<polygon fill="#000000" stroke="#000000" points="1971.2501,-2419.3204 1961.113,-2416.2398 1967.1165,-2424.9696 1971.2501,-2419.3204"/>
<text text-anchor="middle" x="1995" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- enrollment -->
<g id="node13" class="node">
<title>enrollment</title>
<path fill="none" stroke="#000000" d="M1818,-1497C1818,-1497 2136,-1497 2136,-1497 2142,-1497 2148,-1503 2148,-1509 2148,-1509 2148,-1623 2148,-1623 2148,-1629 2142,-1635 2136,-1635 2136,-1635 1818,-1635 1818,-1635 1812,-1635 1806,-1629 1806,-1623 1806,-1623 1806,-1509 1806,-1509 1806,-1503 1812,-1497 1818,-1497"/>
<text text-anchor="middle" x="1853.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrollment</text>
<polyline fill="none" stroke="#000000" points="1901,-1497 1901,-1635 "/>
<text text-anchor="middle" x="1911.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1922,-1497 1922,-1635 "/>
<text text-anchor="middle" x="2024.5" y="-1619.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_short_name</text>
<polyline fill="none" stroke="#000000" points="1922,-1612 2127,-1612 "/>
<text text-anchor="middle" x="2024.5" y="-1596.8" font-family="Times,serif" font-size="14.00" fill="#000000">registering_institution</text>
<polyline fill="none" stroke="#000000" points="1922,-1589 2127,-1589 "/>
<text text-anchor="middle" x="2024.5" y="-1573.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_informed_consent</text>
<polyline fill="none" stroke="#000000" points="1922,-1566 2127,-1566 "/>
<text text-anchor="middle" x="2024.5" y="-1550.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_registration</text>
<polyline fill="none" stroke="#000000" points="1922,-1543 2127,-1543 "/>
<text text-anchor="middle" x="2024.5" y="-1527.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1922,-1520 2127,-1520 "/>
<text text-anchor="middle" x="2024.5" y="-1504.8" font-family="Times,serif" font-size="14.00" fill="#000000">patient_subgroup</text>
<polyline fill="none" stroke="#000000" points="2127,-1497 2127,-1635 "/>
<text text-anchor="middle" x="2137.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_surgery&#45;&gt;enrollment -->
<g id="edge14" class="edge">
<title>prior_surgery&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M1791.856,-2374.2777C1828.7118,-2213.3777 1919.9686,-1814.9805 1958.9154,-1644.9514"/>
<polygon fill="#000000" stroke="#000000" points="1962.3586,-1645.5949 1961.1798,-1635.0658 1955.5353,-1644.0319 1962.3586,-1645.5949"/>
<text text-anchor="middle" x="1968" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- demographic -->
<g id="node6" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M466,-1485.5C466,-1485.5 802,-1485.5 802,-1485.5 808,-1485.5 814,-1491.5 814,-1497.5 814,-1497.5 814,-1634.5 814,-1634.5 814,-1640.5 808,-1646.5 802,-1646.5 802,-1646.5 466,-1646.5 466,-1646.5 460,-1646.5 454,-1640.5 454,-1634.5 454,-1634.5 454,-1497.5 454,-1497.5 454,-1491.5 460,-1485.5 466,-1485.5"/>
<text text-anchor="middle" x="509" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="564,-1485.5 564,-1646.5 "/>
<text text-anchor="middle" x="574.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="585,-1485.5 585,-1646.5 "/>
<text text-anchor="middle" x="689" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="585,-1623.5 793,-1623.5 "/>
<text text-anchor="middle" x="689" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="585,-1600.5 793,-1600.5 "/>
<text text-anchor="middle" x="689" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status</text>
<polyline fill="none" stroke="#000000" points="585,-1577.5 793,-1577.5 "/>
<text text-anchor="middle" x="689" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_birth</text>
<polyline fill="none" stroke="#000000" points="585,-1554.5 793,-1554.5 "/>
<text text-anchor="middle" x="689" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="585,-1531.5 793,-1531.5 "/>
<text text-anchor="middle" x="689" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="585,-1508.5 793,-1508.5 "/>
<text text-anchor="middle" x="689" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="793,-1485.5 793,-1646.5 "/>
<text text-anchor="middle" x="803.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;case -->
<g id="edge19" class="edge">
<title>demographic&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M682.7933,-1485.245C716.1678,-1437.2563 764.8311,-1379.5763 823,-1347 909.1333,-1298.7628 1170.462,-1266.7998 1339.0094,-1250.5876"/>
<polygon fill="#000000" stroke="#000000" points="1339.347,-1254.0714 1348.9694,-1249.6375 1338.6822,-1247.103 1339.347,-1254.0714"/>
<text text-anchor="middle" x="941" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- sample&#45;&gt;case -->
<g id="edge20" class="edge">
<title>sample&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1253.5071,-1347.3185C1268.0181,-1335.3939 1282.9014,-1324.1569 1298,-1314 1310.9968,-1305.257 1325.1514,-1297.278 1339.6847,-1290.058"/>
<polygon fill="#000000" stroke="#000000" points="1341.2976,-1293.1658 1348.7757,-1285.6606 1338.2495,-1286.8643 1341.2976,-1293.1658"/>
<text text-anchor="middle" x="1325" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- sample&#45;&gt;sample -->
<g id="edge27" class="edge">
<title>sample&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1279.5955,-1595.6213C1290.8572,-1588.2644 1297.5,-1578.3906 1297.5,-1566 1297.5,-1556.9006 1293.9175,-1549.1586 1287.5541,-1542.774"/>
<polygon fill="#000000" stroke="#000000" points="1289.583,-1539.9144 1279.5955,-1536.3787 1285.1982,-1545.3709 1289.583,-1539.9144"/>
<text text-anchor="middle" x="1313.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- agent -->
<g id="node8" class="node">
<title>agent</title>
<path fill="none" stroke="#000000" d="M1745.5,-644.5C1745.5,-644.5 1916.5,-644.5 1916.5,-644.5 1922.5,-644.5 1928.5,-650.5 1928.5,-656.5 1928.5,-656.5 1928.5,-668.5 1928.5,-668.5 1928.5,-674.5 1922.5,-680.5 1916.5,-680.5 1916.5,-680.5 1745.5,-680.5 1745.5,-680.5 1739.5,-680.5 1733.5,-674.5 1733.5,-668.5 1733.5,-668.5 1733.5,-656.5 1733.5,-656.5 1733.5,-650.5 1739.5,-644.5 1745.5,-644.5"/>
<text text-anchor="middle" x="1762" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">agent</text>
<polyline fill="none" stroke="#000000" points="1790.5,-644.5 1790.5,-680.5 "/>
<text text-anchor="middle" x="1801" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1811.5,-644.5 1811.5,-680.5 "/>
<text text-anchor="middle" x="1859.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="1907.5,-644.5 1907.5,-680.5 "/>
<text text-anchor="middle" x="1918" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- agent&#45;&gt;study_arm -->
<g id="edge33" class="edge">
<title>agent&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1785.5893,-644.4183C1749.485,-630.0422 1697.7032,-609.4236 1652.4516,-591.4053"/>
<polygon fill="#000000" stroke="#000000" points="1653.4879,-588.0507 1642.9026,-587.603 1650.8984,-594.5541 1653.4879,-588.0507"/>
<text text-anchor="middle" x="1775.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- diagnosis -->
<g id="node9" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M1194.5,-1803.5C1194.5,-1803.5 1537.5,-1803.5 1537.5,-1803.5 1543.5,-1803.5 1549.5,-1809.5 1549.5,-1815.5 1549.5,-1815.5 1549.5,-2228.5 1549.5,-2228.5 1549.5,-2234.5 1543.5,-2240.5 1537.5,-2240.5 1537.5,-2240.5 1194.5,-2240.5 1194.5,-2240.5 1188.5,-2240.5 1182.5,-2234.5 1182.5,-2228.5 1182.5,-2228.5 1182.5,-1815.5 1182.5,-1815.5 1182.5,-1809.5 1188.5,-1803.5 1194.5,-1803.5"/>
<text text-anchor="middle" x="1224.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="1266.5,-1803.5 1266.5,-2240.5 "/>
<text text-anchor="middle" x="1277" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1287.5,-1803.5 1287.5,-2240.5 "/>
<text text-anchor="middle" x="1408" y="-2225.3" font-family="Times,serif" font-size="14.00" fill="#000000">histological_grade</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2217.5 1528.5,-2217.5 "/>
<text text-anchor="middle" x="1408" y="-2202.3" font-family="Times,serif" font-size="14.00" fill="#000000">nuclear_grade</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2194.5 1528.5,-2194.5 "/>
<text text-anchor="middle" x="1408" y="-2179.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_group</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2171.5 1528.5,-2171.5 "/>
<text text-anchor="middle" x="1408" y="-2156.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2148.5 1528.5,-2148.5 "/>
<text text-anchor="middle" x="1408" y="-2133.3" font-family="Times,serif" font-size="14.00" fill="#000000">estrogen_receptor_status</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2125.5 1528.5,-2125.5 "/>
<text text-anchor="middle" x="1408" y="-2110.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_report</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2102.5 1528.5,-2102.5 "/>
<text text-anchor="middle" x="1408" y="-2087.3" font-family="Times,serif" font-size="14.00" fill="#000000">progesterone_receptor_status</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2079.5 1528.5,-2079.5 "/>
<text text-anchor="middle" x="1408" y="-2064.3" font-family="Times,serif" font-size="14.00" fill="#000000">histology_cytopathology</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2056.5 1528.5,-2056.5 "/>
<text text-anchor="middle" x="1408" y="-2041.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_term</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2033.5 1528.5,-2033.5 "/>
<text text-anchor="middle" x="1408" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_histology_confirmation</text>
<polyline fill="none" stroke="#000000" points="1287.5,-2010.5 1528.5,-2010.5 "/>
<text text-anchor="middle" x="1408" y="-1995.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_score</text>
<polyline fill="none" stroke="#000000" points="1287.5,-1987.5 1528.5,-1987.5 "/>
<text text-anchor="middle" x="1408" y="-1972.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_data</text>
<polyline fill="none" stroke="#000000" points="1287.5,-1964.5 1528.5,-1964.5 "/>
<text text-anchor="middle" x="1408" y="-1949.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="1287.5,-1941.5 1528.5,-1941.5 "/>
<text text-anchor="middle" x="1408" y="-1926.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size</text>
<polyline fill="none" stroke="#000000" points="1287.5,-1918.5 1528.5,-1918.5 "/>
<text text-anchor="middle" x="1408" y="-1903.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_data</text>
<polyline fill="none" stroke="#000000" points="1287.5,-1895.5 1528.5,-1895.5 "/>
<text text-anchor="middle" x="1408" y="-1880.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease_type</text>
<polyline fill="none" stroke="#000000" points="1287.5,-1872.5 1528.5,-1872.5 "/>
<text text-anchor="middle" x="1408" y="-1857.3" font-family="Times,serif" font-size="14.00" fill="#000000">stage_of_disease</text>
<polyline fill="none" stroke="#000000" points="1287.5,-1849.5 1528.5,-1849.5 "/>
<text text-anchor="middle" x="1408" y="-1834.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_disease_site</text>
<polyline fill="none" stroke="#000000" points="1287.5,-1826.5 1528.5,-1826.5 "/>
<text text-anchor="middle" x="1408" y="-1811.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_code</text>
<polyline fill="none" stroke="#000000" points="1528.5,-1803.5 1528.5,-2240.5 "/>
<text text-anchor="middle" x="1539" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;case -->
<g id="edge21" class="edge">
<title>diagnosis&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1350.868,-1803.3137C1342.7654,-1637.9001 1340.5305,-1426.183 1375,-1347 1381.9436,-1331.0492 1392.4618,-1316.3023 1404.3529,-1303.1442"/>
<polygon fill="#000000" stroke="#000000" points="1407.1727,-1305.256 1411.4961,-1295.5834 1402.0844,-1300.4487 1407.1727,-1305.256"/>
<text text-anchor="middle" x="1402" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- prior_therapy -->
<g id="node10" class="node">
<title>prior_therapy</title>
<path fill="none" stroke="#000000" d="M2041,-2259.5C2041,-2259.5 2497,-2259.5 2497,-2259.5 2503,-2259.5 2509,-2265.5 2509,-2271.5 2509,-2271.5 2509,-2615.5 2509,-2615.5 2509,-2621.5 2503,-2627.5 2497,-2627.5 2497,-2627.5 2041,-2627.5 2041,-2627.5 2035,-2627.5 2029,-2621.5 2029,-2615.5 2029,-2615.5 2029,-2271.5 2029,-2271.5 2029,-2265.5 2035,-2259.5 2041,-2259.5"/>
<text text-anchor="middle" x="2086.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy</text>
<polyline fill="none" stroke="#000000" points="2144,-2259.5 2144,-2627.5 "/>
<text text-anchor="middle" x="2154.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2165,-2259.5 2165,-2627.5 "/>
<text text-anchor="middle" x="2326.5" y="-2612.3" font-family="Times,serif" font-size="14.00" fill="#000000">nonresponse_therapy_type</text>
<polyline fill="none" stroke="#000000" points="2165,-2604.5 2488,-2604.5 "/>
<text text-anchor="middle" x="2326.5" y="-2589.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2165,-2581.5 2488,-2581.5 "/>
<text text-anchor="middle" x="2326.5" y="-2566.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapy_type</text>
<polyline fill="none" stroke="#000000" points="2165,-2558.5 2488,-2558.5 "/>
<text text-anchor="middle" x="2326.5" y="-2543.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_dose</text>
<polyline fill="none" stroke="#000000" points="2165,-2535.5 2488,-2535.5 "/>
<text text-anchor="middle" x="2326.5" y="-2520.3" font-family="Times,serif" font-size="14.00" fill="#000000">any_therapy</text>
<polyline fill="none" stroke="#000000" points="2165,-2512.5 2488,-2512.5 "/>
<text text-anchor="middle" x="2326.5" y="-2497.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose_any_therapy</text>
<polyline fill="none" stroke="#000000" points="2165,-2489.5 2488,-2489.5 "/>
<text text-anchor="middle" x="2326.5" y="-2474.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose</text>
<polyline fill="none" stroke="#000000" points="2165,-2466.5 2488,-2466.5 "/>
<text text-anchor="middle" x="2326.5" y="-2451.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_name</text>
<polyline fill="none" stroke="#000000" points="2165,-2443.5 2488,-2443.5 "/>
<text text-anchor="middle" x="2326.5" y="-2428.3" font-family="Times,serif" font-size="14.00" fill="#000000">best_response</text>
<polyline fill="none" stroke="#000000" points="2165,-2420.5 2488,-2420.5 "/>
<text text-anchor="middle" x="2326.5" y="-2405.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_in_minimal_residual</text>
<polyline fill="none" stroke="#000000" points="2165,-2397.5 2488,-2397.5 "/>
<text text-anchor="middle" x="2326.5" y="-2382.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_prior_regimens_any_therapy</text>
<polyline fill="none" stroke="#000000" points="2165,-2374.5 2488,-2374.5 "/>
<text text-anchor="middle" x="2326.5" y="-2359.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_at_site</text>
<polyline fill="none" stroke="#000000" points="2165,-2351.5 2488,-2351.5 "/>
<text text-anchor="middle" x="2326.5" y="-2336.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_schedule</text>
<polyline fill="none" stroke="#000000" points="2165,-2328.5 2488,-2328.5 "/>
<text text-anchor="middle" x="2326.5" y="-2313.3" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy_type</text>
<polyline fill="none" stroke="#000000" points="2165,-2305.5 2488,-2305.5 "/>
<text text-anchor="middle" x="2326.5" y="-2290.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_number_of_doses_any_therapy</text>
<polyline fill="none" stroke="#000000" points="2165,-2282.5 2488,-2282.5 "/>
<text text-anchor="middle" x="2326.5" y="-2267.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_first_dose</text>
<polyline fill="none" stroke="#000000" points="2488,-2259.5 2488,-2627.5 "/>
<text text-anchor="middle" x="2498.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_therapy&#45;&gt;prior_therapy -->
<g id="edge29" class="edge">
<title>prior_therapy&#45;&gt;prior_therapy</title>
<path fill="none" stroke="#000000" d="M2509.2384,-2468.2536C2520.4387,-2462.0051 2527,-2453.7539 2527,-2443.5 2527,-2436.13 2523.6104,-2429.7946 2517.545,-2424.4938"/>
<polygon fill="#000000" stroke="#000000" points="2519.4534,-2421.5581 2509.2384,-2418.7464 2515.4704,-2427.3146 2519.4534,-2421.5581"/>
<text text-anchor="middle" x="2543" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- prior_therapy&#45;&gt;enrollment -->
<g id="edge13" class="edge">
<title>prior_therapy&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M2207.6983,-2259.2799C2144.4871,-2069.3216 2048.8964,-1782.0584 2003.1686,-1644.6404"/>
<polygon fill="#000000" stroke="#000000" points="2006.442,-1643.3919 1999.9635,-1635.0086 1999.8001,-1645.6022 2006.442,-1643.3919"/>
<text text-anchor="middle" x="2249" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- evaluation -->
<g id="node11" class="node">
<title>evaluation</title>
<path fill="none" stroke="#000000" d="M964,-3323C964,-3323 1224,-3323 1224,-3323 1230,-3323 1236,-3329 1236,-3335 1236,-3335 1236,-3347 1236,-3347 1236,-3353 1230,-3359 1224,-3359 1224,-3359 964,-3359 964,-3359 958,-3359 952,-3353 952,-3347 952,-3347 952,-3335 952,-3335 952,-3329 958,-3323 964,-3323"/>
<text text-anchor="middle" x="997.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">evaluation</text>
<polyline fill="none" stroke="#000000" points="1043,-3323 1043,-3359 "/>
<text text-anchor="middle" x="1053.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1064,-3323 1064,-3359 "/>
<text text-anchor="middle" x="1139.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_evaluation</text>
<polyline fill="none" stroke="#000000" points="1215,-3323 1215,-3359 "/>
<text text-anchor="middle" x="1225.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival -->
<g id="node12" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1450.5,-1416.5C1450.5,-1416.5 1775.5,-1416.5 1775.5,-1416.5 1781.5,-1416.5 1787.5,-1422.5 1787.5,-1428.5 1787.5,-1428.5 1787.5,-1703.5 1787.5,-1703.5 1787.5,-1709.5 1781.5,-1715.5 1775.5,-1715.5 1775.5,-1715.5 1450.5,-1715.5 1450.5,-1715.5 1444.5,-1715.5 1438.5,-1709.5 1438.5,-1703.5 1438.5,-1703.5 1438.5,-1428.5 1438.5,-1428.5 1438.5,-1422.5 1444.5,-1416.5 1450.5,-1416.5"/>
<text text-anchor="middle" x="1475.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1512.5,-1416.5 1512.5,-1715.5 "/>
<text text-anchor="middle" x="1523" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1533.5,-1416.5 1533.5,-1715.5 "/>
<text text-anchor="middle" x="1650" y="-1700.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_survival_interval</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1692.5 1766.5,-1692.5 "/>
<text text-anchor="middle" x="1650" y="-1677.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_free_interval</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1669.5 1766.5,-1669.5 "/>
<text text-anchor="middle" x="1650" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_interval</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1646.5 1766.5,-1646.5 "/>
<text text-anchor="middle" x="1650" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_survival</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1623.5 1766.5,-1623.5 "/>
<text text-anchor="middle" x="1650" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_event_indicator</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1600.5 1766.5,-1600.5 "/>
<text text-anchor="middle" x="1650" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1577.5 1766.5,-1577.5 "/>
<text text-anchor="middle" x="1650" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_recurrence</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1554.5 1766.5,-1554.5 "/>
<text text-anchor="middle" x="1650" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_dfs_event</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1531.5 1766.5,-1531.5 "/>
<text text-anchor="middle" x="1650" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1508.5 1766.5,-1508.5 "/>
<text text-anchor="middle" x="1650" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_status</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1485.5 1766.5,-1485.5 "/>
<text text-anchor="middle" x="1650" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_withdrawn</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1462.5 1766.5,-1462.5 "/>
<text text-anchor="middle" x="1650" y="-1447.3" font-family="Times,serif" font-size="14.00" fill="#000000">lost_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="1533.5,-1439.5 1766.5,-1439.5 "/>
<text text-anchor="middle" x="1650" y="-1424.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1766.5,-1416.5 1766.5,-1715.5 "/>
<text text-anchor="middle" x="1777" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;case -->
<g id="edge16" class="edge">
<title>survival&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1556.443,-1416.3976C1541.7399,-1377.5055 1526.6253,-1337.5251 1514.4412,-1305.2961"/>
<polygon fill="#000000" stroke="#000000" points="1517.5678,-1303.6688 1510.7577,-1295.5526 1511.0201,-1306.1442 1517.5678,-1303.6688"/>
<text text-anchor="middle" x="1550" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- enrollment&#45;&gt;case -->
<g id="edge17" class="edge">
<title>enrollment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1934.3874,-1496.7555C1901.753,-1448.8224 1852.7784,-1386.7376 1796,-1347 1749.2153,-1314.2567 1691.5804,-1290.3863 1638.9313,-1273.483"/>
<polygon fill="#000000" stroke="#000000" points="1639.7518,-1270.0721 1629.1623,-1270.4073 1637.6496,-1276.7489 1639.7518,-1270.0721"/>
<text text-anchor="middle" x="1794" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- cohort&#45;&gt;study -->
<g id="edge4" class="edge">
<title>cohort&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1329.9367,-639.4849C1306.3322,-627.9308 1282.4991,-611.2946 1269,-588 1249.8103,-554.8854 1245.5164,-514.5471 1247.8174,-476.63"/>
<polygon fill="#000000" stroke="#000000" points="1251.3171,-476.7667 1248.5864,-466.5299 1244.3373,-476.2353 1251.3171,-476.7667"/>
<text text-anchor="middle" x="1309.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort&#45;&gt;study_arm -->
<g id="edge5" class="edge">
<title>cohort&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1421.756,-639.4218C1433.0331,-628.6118 1447.1719,-615.9547 1461,-606 1467.2508,-601.5001 1473.9208,-597.089 1480.718,-592.8524"/>
<polygon fill="#000000" stroke="#000000" points="1482.65,-595.7739 1489.3737,-587.586 1479.0114,-589.7938 1482.65,-595.7739"/>
<text text-anchor="middle" x="1501.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- genomic_report -->
<g id="node16" class="node">
<title>genomic_report</title>
<path fill="none" stroke="#000000" d="M571,-2679.5C571,-2679.5 947,-2679.5 947,-2679.5 953,-2679.5 959,-2685.5 959,-2691.5 959,-2691.5 959,-2943.5 959,-2943.5 959,-2949.5 953,-2955.5 947,-2955.5 947,-2955.5 571,-2955.5 571,-2955.5 565,-2955.5 559,-2949.5 559,-2943.5 559,-2943.5 559,-2691.5 559,-2691.5 559,-2685.5 565,-2679.5 571,-2679.5"/>
<text text-anchor="middle" x="624" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_report</text>
<polyline fill="none" stroke="#000000" points="689,-2679.5 689,-2955.5 "/>
<text text-anchor="middle" x="699.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="710,-2679.5 710,-2955.5 "/>
<text text-anchor="middle" x="824" y="-2940.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="710,-2932.5 938,-2932.5 "/>
<text text-anchor="middle" x="824" y="-2917.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id</text>
<polyline fill="none" stroke="#000000" points="710,-2909.5 938,-2909.5 "/>
<text text-anchor="middle" x="824" y="-2894.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_mois</text>
<polyline fill="none" stroke="#000000" points="710,-2886.5 938,-2886.5 "/>
<text text-anchor="middle" x="824" y="-2871.3" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="710,-2863.5 938,-2863.5 "/>
<text text-anchor="middle" x="824" y="-2848.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_type</text>
<polyline fill="none" stroke="#000000" points="710,-2840.5 938,-2840.5 "/>
<text text-anchor="middle" x="824" y="-2825.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_received_date</text>
<polyline fill="none" stroke="#000000" points="710,-2817.5 938,-2817.5 "/>
<text text-anchor="middle" x="824" y="-2802.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_amois</text>
<polyline fill="none" stroke="#000000" points="710,-2794.5 938,-2794.5 "/>
<text text-anchor="middle" x="824" y="-2779.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_amois</text>
<polyline fill="none" stroke="#000000" points="710,-2771.5 938,-2771.5 "/>
<text text-anchor="middle" x="824" y="-2756.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_mois</text>
<polyline fill="none" stroke="#000000" points="710,-2748.5 938,-2748.5 "/>
<text text-anchor="middle" x="824" y="-2733.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="710,-2725.5 938,-2725.5 "/>
<text text-anchor="middle" x="824" y="-2710.3" font-family="Times,serif" font-size="14.00" fill="#000000">cellularity</text>
<polyline fill="none" stroke="#000000" points="710,-2702.5 938,-2702.5 "/>
<text text-anchor="middle" x="824" y="-2687.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_variants</text>
<polyline fill="none" stroke="#000000" points="938,-2679.5 938,-2955.5 "/>
<text text-anchor="middle" x="948.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_report&#45;&gt;assay -->
<g id="edge10" class="edge">
<title>genomic_report&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M859.51,-2679.2988C915.5754,-2602.2088 980.2928,-2513.2223 1011.7867,-2469.9183"/>
<polygon fill="#000000" stroke="#000000" points="1014.7579,-2471.7835 1017.8091,-2461.6375 1009.0967,-2467.6663 1014.7579,-2471.7835"/>
<text text-anchor="middle" x="909.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- agent_administration -->
<g id="node17" class="node">
<title>agent_administration</title>
<path fill="none" stroke="#000000" d="M1596.5,-737.5C1596.5,-737.5 2065.5,-737.5 2065.5,-737.5 2071.5,-737.5 2077.5,-743.5 2077.5,-749.5 2077.5,-749.5 2077.5,-1116.5 2077.5,-1116.5 2077.5,-1122.5 2071.5,-1128.5 2065.5,-1128.5 2065.5,-1128.5 1596.5,-1128.5 1596.5,-1128.5 1590.5,-1128.5 1584.5,-1122.5 1584.5,-1116.5 1584.5,-1116.5 1584.5,-749.5 1584.5,-749.5 1584.5,-743.5 1590.5,-737.5 1596.5,-737.5"/>
<text text-anchor="middle" x="1669.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_administration</text>
<polyline fill="none" stroke="#000000" points="1754.5,-737.5 1754.5,-1128.5 "/>
<text text-anchor="middle" x="1765" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1775.5,-737.5 1775.5,-1128.5 "/>
<text text-anchor="middle" x="1916" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_amount</text>
<polyline fill="none" stroke="#000000" points="1775.5,-1105.5 2056.5,-1105.5 "/>
<text text-anchor="middle" x="1916" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_dose</text>
<polyline fill="none" stroke="#000000" points="1775.5,-1082.5 2056.5,-1082.5 "/>
<text text-anchor="middle" x="1916" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_time</text>
<polyline fill="none" stroke="#000000" points="1775.5,-1059.5 2056.5,-1059.5 "/>
<text text-anchor="middle" x="1916" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">stop_time</text>
<polyline fill="none" stroke="#000000" points="1775.5,-1036.5 2056.5,-1036.5 "/>
<text text-anchor="middle" x="1916" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="1775.5,-1013.5 2056.5,-1013.5 "/>
<text text-anchor="middle" x="1916" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_vial_id</text>
<polyline fill="none" stroke="#000000" points="1775.5,-990.5 2056.5,-990.5 "/>
<text text-anchor="middle" x="1916" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">route_of_administration</text>
<polyline fill="none" stroke="#000000" points="1775.5,-967.5 2056.5,-967.5 "/>
<text text-anchor="middle" x="1916" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="1775.5,-944.5 2056.5,-944.5 "/>
<text text-anchor="middle" x="1916" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="1775.5,-921.5 2056.5,-921.5 "/>
<text text-anchor="middle" x="1916" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="1775.5,-898.5 2056.5,-898.5 "/>
<text text-anchor="middle" x="1916" y="-883.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_lot_number</text>
<polyline fill="none" stroke="#000000" points="1775.5,-875.5 2056.5,-875.5 "/>
<text text-anchor="middle" x="1916" y="-860.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_course_number</text>
<polyline fill="none" stroke="#000000" points="1775.5,-852.5 2056.5,-852.5 "/>
<text text-anchor="middle" x="1916" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_missed_dose</text>
<polyline fill="none" stroke="#000000" points="1775.5,-829.5 2056.5,-829.5 "/>
<text text-anchor="middle" x="1916" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_duration</text>
<polyline fill="none" stroke="#000000" points="1775.5,-806.5 2056.5,-806.5 "/>
<text text-anchor="middle" x="1916" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_level</text>
<polyline fill="none" stroke="#000000" points="1775.5,-783.5 2056.5,-783.5 "/>
<text text-anchor="middle" x="1916" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_missed_dose</text>
<polyline fill="none" stroke="#000000" points="1775.5,-760.5 2056.5,-760.5 "/>
<text text-anchor="middle" x="1916" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2056.5,-737.5 2056.5,-1128.5 "/>
<text text-anchor="middle" x="2067" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- agent_administration&#45;&gt;agent -->
<g id="edge11" class="edge">
<title>agent_administration&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M1831,-737.4901C1831,-719.6507 1831,-703.5695 1831,-690.9158"/>
<polygon fill="#000000" stroke="#000000" points="1834.5001,-690.7202 1831,-680.7203 1827.5001,-690.7203 1834.5001,-690.7202"/>
<text text-anchor="middle" x="1862" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- treatment -->
<g id="node18" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M2178.5,-1462.5C2178.5,-1462.5 2603.5,-1462.5 2603.5,-1462.5 2609.5,-1462.5 2615.5,-1468.5 2615.5,-1474.5 2615.5,-1474.5 2615.5,-1657.5 2615.5,-1657.5 2615.5,-1663.5 2609.5,-1669.5 2603.5,-1669.5 2603.5,-1669.5 2178.5,-1669.5 2178.5,-1669.5 2172.5,-1669.5 2166.5,-1663.5 2166.5,-1657.5 2166.5,-1657.5 2166.5,-1474.5 2166.5,-1474.5 2166.5,-1468.5 2172.5,-1462.5 2178.5,-1462.5"/>
<text text-anchor="middle" x="2211" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="2255.5,-1462.5 2255.5,-1669.5 "/>
<text text-anchor="middle" x="2266" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2276.5,-1462.5 2276.5,-1669.5 "/>
<text text-anchor="middle" x="2435.5" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">endocrine_therapy_discontinued</text>
<polyline fill="none" stroke="#000000" points="2276.5,-1646.5 2594.5,-1646.5 "/>
<text text-anchor="middle" x="2435.5" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">specific_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="2276.5,-1623.5 2594.5,-1623.5 "/>
<text text-anchor="middle" x="2435.5" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_endocrine_therapy_received</text>
<polyline fill="none" stroke="#000000" points="2276.5,-1600.5 2594.5,-1600.5 "/>
<text text-anchor="middle" x="2435.5" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">duration_of_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="2276.5,-1577.5 2594.5,-1577.5 "/>
<text text-anchor="middle" x="2435.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">received_chemotherapy</text>
<polyline fill="none" stroke="#000000" points="2276.5,-1554.5 2594.5,-1554.5 "/>
<text text-anchor="middle" x="2435.5" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_last_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="2276.5,-1531.5 2594.5,-1531.5 "/>
<text text-anchor="middle" x="2435.5" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_surgical_procedure</text>
<polyline fill="none" stroke="#000000" points="2276.5,-1508.5 2594.5,-1508.5 "/>
<text text-anchor="middle" x="2435.5" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_first_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="2276.5,-1485.5 2594.5,-1485.5 "/>
<text text-anchor="middle" x="2435.5" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="2594.5,-1462.5 2594.5,-1669.5 "/>
<text text-anchor="middle" x="2605" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;case -->
<g id="edge18" class="edge">
<title>treatment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2305.5311,-1462.4624C2264.9333,-1420.0578 2213.0476,-1374.5612 2157,-1347 2068.2607,-1303.3628 1807.4559,-1269.989 1639.1992,-1252.2456"/>
<polygon fill="#000000" stroke="#000000" points="1639.3159,-1248.7388 1629.0057,-1251.1778 1638.5866,-1255.7007 1639.3159,-1248.7388"/>
<text text-anchor="middle" x="2133" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- file -->
<g id="node19" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M1074.5,-2714C1074.5,-2714 1259.5,-2714 1259.5,-2714 1265.5,-2714 1271.5,-2720 1271.5,-2726 1271.5,-2726 1271.5,-2909 1271.5,-2909 1271.5,-2915 1265.5,-2921 1259.5,-2921 1259.5,-2921 1074.5,-2921 1074.5,-2921 1068.5,-2921 1062.5,-2915 1062.5,-2909 1062.5,-2909 1062.5,-2726 1062.5,-2726 1062.5,-2720 1068.5,-2714 1074.5,-2714"/>
<text text-anchor="middle" x="1082" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="1101.5,-2714 1101.5,-2921 "/>
<text text-anchor="middle" x="1112" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1122.5,-2714 1122.5,-2921 "/>
<text text-anchor="middle" x="1186.5" y="-2905.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="1122.5,-2898 1250.5,-2898 "/>
<text text-anchor="middle" x="1186.5" y="-2882.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_format</text>
<polyline fill="none" stroke="#000000" points="1122.5,-2875 1250.5,-2875 "/>
<text text-anchor="middle" x="1186.5" y="-2859.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_locations</text>
<polyline fill="none" stroke="#000000" points="1122.5,-2852 1250.5,-2852 "/>
<text text-anchor="middle" x="1186.5" y="-2836.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="1122.5,-2829 1250.5,-2829 "/>
<text text-anchor="middle" x="1186.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="1122.5,-2806 1250.5,-2806 "/>
<text text-anchor="middle" x="1186.5" y="-2790.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_status</text>
<polyline fill="none" stroke="#000000" points="1122.5,-2783 1250.5,-2783 "/>
<text text-anchor="middle" x="1186.5" y="-2767.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="1122.5,-2760 1250.5,-2760 "/>
<text text-anchor="middle" x="1186.5" y="-2744.8" font-family="Times,serif" font-size="14.00" fill="#000000">uuid</text>
<polyline fill="none" stroke="#000000" points="1122.5,-2737 1250.5,-2737 "/>
<text text-anchor="middle" x="1186.5" y="-2721.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="1250.5,-2714 1250.5,-2921 "/>
<text text-anchor="middle" x="1261" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;assay -->
<g id="edge9" class="edge">
<title>file&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M1114.2144,-2713.7855C1106.2514,-2696.3814 1098.5303,-2678.3405 1092,-2661 1066.9628,-2594.5165 1046.8153,-2513.2167 1037.1739,-2471.3582"/>
<polygon fill="#000000" stroke="#000000" points="1040.5848,-2470.5728 1034.9525,-2461.599 1033.7593,-2472.1264 1040.5848,-2470.5728"/>
<text text-anchor="middle" x="1122.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge32" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M1166.0512,-2713.9124C1163.4881,-2491.785 1154.5635,-1975.8261 1126,-1803 1125.5483,-1800.2668 1125.0748,-1797.5207 1124.581,-1794.7641"/>
<polygon fill="#000000" stroke="#000000" points="1127.9853,-1793.9277 1122.7064,-1784.7416 1121.1046,-1795.2147 1127.9853,-1793.9277"/>
<text text-anchor="middle" x="1201.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- file&#45;&gt;diagnosis -->
<g id="edge34" class="edge">
<title>file&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M1213.3298,-2713.5111C1224.4264,-2686.0667 1235.5065,-2656.2243 1244,-2628 1280.9236,-2505.3014 1309.9429,-2365.2376 1330.3993,-2250.6954"/>
<polygon fill="#000000" stroke="#000000" points="1333.8636,-2251.2042 1332.1661,-2240.7463 1326.9714,-2249.9802 1333.8636,-2251.2042"/>
<text text-anchor="middle" x="1293.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_diagnosis</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge7" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1445.9901,-518.3788C1434.4588,-512.9647 1423.2282,-506.8527 1413,-500 1401.2798,-492.1477 1389.8609,-483.0974 1378.9377,-473.4194"/>
<polygon fill="#000000" stroke="#000000" points="1381.213,-470.7578 1371.4571,-466.6259 1376.507,-475.9398 1381.213,-470.7578"/>
<text text-anchor="middle" x="1453.5" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge23" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1527.7842,-518.3124C1517.7416,-507.0234 1505.9469,-494.8702 1494,-485 1476.1874,-470.2837 1456.6036,-456.0317 1436.7057,-442.6637"/>
<polygon fill="#000000" stroke="#000000" points="1438.4296,-439.607 1428.1631,-436.9899 1434.5568,-445.4381 1438.4296,-439.607"/>
<text text-anchor="middle" x="1539.5" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- visit -->
<g id="node21" class="node">
<title>visit</title>
<path fill="none" stroke="#000000" d="M1266.5,-3318C1266.5,-3318 1441.5,-3318 1441.5,-3318 1447.5,-3318 1453.5,-3324 1453.5,-3330 1453.5,-3330 1453.5,-3352 1453.5,-3352 1453.5,-3358 1447.5,-3364 1441.5,-3364 1441.5,-3364 1266.5,-3364 1266.5,-3364 1260.5,-3364 1254.5,-3358 1254.5,-3352 1254.5,-3352 1254.5,-3330 1254.5,-3330 1254.5,-3324 1260.5,-3318 1266.5,-3318"/>
<text text-anchor="middle" x="1278" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">visit</text>
<polyline fill="none" stroke="#000000" points="1301.5,-3318 1301.5,-3364 "/>
<text text-anchor="middle" x="1312" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1322.5,-3318 1322.5,-3364 "/>
<text text-anchor="middle" x="1377.5" y="-3348.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_date</text>
<polyline fill="none" stroke="#000000" points="1322.5,-3341 1432.5,-3341 "/>
<text text-anchor="middle" x="1377.5" y="-3325.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_number</text>
<polyline fill="none" stroke="#000000" points="1432.5,-3318 1432.5,-3364 "/>
<text text-anchor="middle" x="1443" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- visit&#45;&gt;visit -->
<g id="edge26" class="edge">
<title>visit&#45;&gt;visit</title>
<path fill="none" stroke="#000000" d="M1366.2183,-3364.2371C1407.4427,-3429.6803 1471.5,-3421.9346 1471.5,-3341 1471.5,-3263.7012 1413.0686,-3253.1633 1371.9043,-3309.3865"/>
<polygon fill="#000000" stroke="#000000" points="1368.9389,-3307.5233 1366.2183,-3317.7629 1374.7306,-3311.4548 1368.9389,-3307.5233"/>
<text text-anchor="middle" x="1487.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- image -->
<g id="node22" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M989,-2799.5C989,-2799.5 1025,-2799.5 1025,-2799.5 1031,-2799.5 1037,-2805.5 1037,-2811.5 1037,-2811.5 1037,-2823.5 1037,-2823.5 1037,-2829.5 1031,-2835.5 1025,-2835.5 1025,-2835.5 989,-2835.5 989,-2835.5 983,-2835.5 977,-2829.5 977,-2823.5 977,-2823.5 977,-2811.5 977,-2811.5 977,-2805.5 983,-2799.5 989,-2799.5"/>
<text text-anchor="middle" x="1007" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
</g>
<!-- image&#45;&gt;assay -->
<g id="edge8" class="edge">
<title>image&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M1006.47,-2799.4546C1005.6934,-2768.1761 1004.6734,-2701.8777 1008,-2646 1011.7191,-2583.5296 1021.2781,-2510.7184 1026.8321,-2471.6755"/>
<polygon fill="#000000" stroke="#000000" points="1030.3225,-2471.9924 1028.2842,-2461.5955 1023.394,-2470.9942 1030.3225,-2471.9924"/>
<text text-anchor="middle" x="1038.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- adverse_event&#45;&gt;agent -->
<g id="edge12" class="edge">
<title>adverse_event&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M2195.7044,-817.9674C2162.7432,-788.2723 2124.9154,-758.6218 2086,-737 2040.5506,-711.7479 1985.6809,-694.289 1938.5009,-682.6566"/>
<polygon fill="#000000" stroke="#000000" points="1939.0975,-679.2003 1928.556,-680.2621 1937.4588,-686.0058 1939.0975,-679.2003"/>
<text text-anchor="middle" x="2079" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- adverse_event&#45;&gt;adverse_event -->
<g id="edge30" class="edge">
<title>adverse_event&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M2514.7046,-960.2761C2525.876,-953.5862 2532.5,-944.4941 2532.5,-933 2532.5,-924.7386 2529.0781,-917.7181 2523.0052,-911.9385"/>
<polygon fill="#000000" stroke="#000000" points="2524.8073,-908.9155 2514.7046,-905.7239 2520.6119,-914.519 2524.8073,-908.9155"/>
<text text-anchor="middle" x="2548.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- variant -->
<g id="node24" class="node">
<title>variant</title>
<path fill="none" stroke="#000000" d="M596.5,-3007.5C596.5,-3007.5 921.5,-3007.5 921.5,-3007.5 927.5,-3007.5 933.5,-3013.5 933.5,-3019.5 933.5,-3019.5 933.5,-3662.5 933.5,-3662.5 933.5,-3668.5 927.5,-3674.5 921.5,-3674.5 921.5,-3674.5 596.5,-3674.5 596.5,-3674.5 590.5,-3674.5 584.5,-3668.5 584.5,-3662.5 584.5,-3662.5 584.5,-3019.5 584.5,-3019.5 584.5,-3013.5 590.5,-3007.5 596.5,-3007.5"/>
<text text-anchor="middle" x="618.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant</text>
<polyline fill="none" stroke="#000000" points="652.5,-3007.5 652.5,-3674.5 "/>
<text text-anchor="middle" x="663" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="673.5,-3007.5 673.5,-3674.5 "/>
<text text-anchor="middle" x="793" y="-3659.3" font-family="Times,serif" font-size="14.00" fill="#000000">raw_copy_number</text>
<polyline fill="none" stroke="#000000" points="673.5,-3651.5 912.5,-3651.5 "/>
<text text-anchor="middle" x="793" y="-3636.3" font-family="Times,serif" font-size="14.00" fill="#000000">protein</text>
<polyline fill="none" stroke="#000000" points="673.5,-3628.5 912.5,-3628.5 "/>
<text text-anchor="middle" x="793" y="-3613.3" font-family="Times,serif" font-size="14.00" fill="#000000">aMOI</text>
<polyline fill="none" stroke="#000000" points="673.5,-3605.5 912.5,-3605.5 "/>
<text text-anchor="middle" x="793" y="-3590.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_ref</text>
<polyline fill="none" stroke="#000000" points="673.5,-3582.5 912.5,-3582.5 "/>
<text text-anchor="middle" x="793" y="-3567.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id_analysis_id</text>
<polyline fill="none" stroke="#000000" points="673.5,-3559.5 912.5,-3559.5 "/>
<text text-anchor="middle" x="793" y="-3544.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="673.5,-3536.5 912.5,-3536.5 "/>
<text text-anchor="middle" x="793" y="-3521.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm_specific</text>
<polyline fill="none" stroke="#000000" points="673.5,-3513.5 912.5,-3513.5 "/>
<text text-anchor="middle" x="793" y="-3498.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternative_allele</text>
<polyline fill="none" stroke="#000000" points="673.5,-3490.5 912.5,-3490.5 "/>
<text text-anchor="middle" x="793" y="-3475.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_type</text>
<polyline fill="none" stroke="#000000" points="673.5,-3467.5 912.5,-3467.5 "/>
<text text-anchor="middle" x="793" y="-3452.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_95percent</text>
<polyline fill="none" stroke="#000000" points="673.5,-3444.5 912.5,-3444.5 "/>
<text text-anchor="middle" x="793" y="-3429.3" font-family="Times,serif" font-size="14.00" fill="#000000">function</text>
<polyline fill="none" stroke="#000000" points="673.5,-3421.5 912.5,-3421.5 "/>
<text text-anchor="middle" x="793" y="-3406.3" font-family="Times,serif" font-size="14.00" fill="#000000">read_depth</text>
<polyline fill="none" stroke="#000000" points="673.5,-3398.5 912.5,-3398.5 "/>
<text text-anchor="middle" x="793" y="-3383.3" font-family="Times,serif" font-size="14.00" fill="#000000">transcript</text>
<polyline fill="none" stroke="#000000" points="673.5,-3375.5 912.5,-3375.5 "/>
<text text-anchor="middle" x="793" y="-3360.3" font-family="Times,serif" font-size="14.00" fill="#000000">ref_copy_number</text>
<polyline fill="none" stroke="#000000" points="673.5,-3352.5 912.5,-3352.5 "/>
<text text-anchor="middle" x="793" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_ref</text>
<polyline fill="none" stroke="#000000" points="673.5,-3329.5 912.5,-3329.5 "/>
<text text-anchor="middle" x="793" y="-3314.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs</text>
<polyline fill="none" stroke="#000000" points="673.5,-3306.5 912.5,-3306.5 "/>
<text text-anchor="middle" x="793" y="-3291.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_05percent</text>
<polyline fill="none" stroke="#000000" points="673.5,-3283.5 912.5,-3283.5 "/>
<text text-anchor="middle" x="793" y="-3268.3" font-family="Times,serif" font-size="14.00" fill="#000000">genome_reference</text>
<polyline fill="none" stroke="#000000" points="673.5,-3260.5 912.5,-3260.5 "/>
<text text-anchor="middle" x="793" y="-3245.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="673.5,-3237.5 912.5,-3237.5 "/>
<text text-anchor="middle" x="793" y="-3222.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="673.5,-3214.5 912.5,-3214.5 "/>
<text text-anchor="middle" x="793" y="-3199.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_alt</text>
<polyline fill="none" stroke="#000000" points="673.5,-3191.5 912.5,-3191.5 "/>
<text text-anchor="middle" x="793" y="-3176.3" font-family="Times,serif" font-size="14.00" fill="#000000">confirmed</text>
<polyline fill="none" stroke="#000000" points="673.5,-3168.5 912.5,-3168.5 "/>
<text text-anchor="middle" x="793" y="-3153.3" font-family="Times,serif" font-size="14.00" fill="#000000">strand</text>
<polyline fill="none" stroke="#000000" points="673.5,-3145.5 912.5,-3145.5 "/>
<text text-anchor="middle" x="793" y="-3130.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_alt</text>
<polyline fill="none" stroke="#000000" points="673.5,-3122.5 912.5,-3122.5 "/>
<text text-anchor="middle" x="793" y="-3107.3" font-family="Times,serif" font-size="14.00" fill="#000000">position</text>
<polyline fill="none" stroke="#000000" points="673.5,-3099.5 912.5,-3099.5 "/>
<text text-anchor="middle" x="793" y="-3084.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="673.5,-3076.5 912.5,-3076.5 "/>
<text text-anchor="middle" x="793" y="-3061.3" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="673.5,-3053.5 912.5,-3053.5 "/>
<text text-anchor="middle" x="793" y="-3038.3" font-family="Times,serif" font-size="14.00" fill="#000000">allele_frequency</text>
<polyline fill="none" stroke="#000000" points="673.5,-3030.5 912.5,-3030.5 "/>
<text text-anchor="middle" x="793" y="-3015.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_name</text>
<polyline fill="none" stroke="#000000" points="912.5,-3007.5 912.5,-3674.5 "/>
<text text-anchor="middle" x="923" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- variant&#45;&gt;genomic_report -->
<g id="edge25" class="edge">
<title>variant&#45;&gt;genomic_report</title>
<path fill="none" stroke="#000000" d="M759,-3007.2357C759,-2993.0591 759,-2979.1882 759,-2965.8076"/>
<polygon fill="#000000" stroke="#000000" points="762.5001,-2965.674 759,-2955.674 755.5001,-2965.6741 762.5001,-2965.674"/>
<text text-anchor="middle" x="792.5" y="-2977.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_report</text>
</g>
<!-- follow_up -->
<g id="node25" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M2646,-1508.5C2646,-1508.5 2978,-1508.5 2978,-1508.5 2984,-1508.5 2990,-1514.5 2990,-1520.5 2990,-1520.5 2990,-1611.5 2990,-1611.5 2990,-1617.5 2984,-1623.5 2978,-1623.5 2978,-1623.5 2646,-1623.5 2646,-1623.5 2640,-1623.5 2634,-1617.5 2634,-1611.5 2634,-1611.5 2634,-1520.5 2634,-1520.5 2634,-1514.5 2640,-1508.5 2646,-1508.5"/>
<text text-anchor="middle" x="2676.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="2719,-1508.5 2719,-1623.5 "/>
<text text-anchor="middle" x="2729.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2740,-1508.5 2740,-1623.5 "/>
<text text-anchor="middle" x="2854.5" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_since_last_contact</text>
<polyline fill="none" stroke="#000000" points="2740,-1600.5 2969,-1600.5 "/>
<text text-anchor="middle" x="2854.5" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">contact_type</text>
<polyline fill="none" stroke="#000000" points="2740,-1577.5 2969,-1577.5 "/>
<text text-anchor="middle" x="2854.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_status</text>
<polyline fill="none" stroke="#000000" points="2740,-1554.5 2969,-1554.5 "/>
<text text-anchor="middle" x="2854.5" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">explain_unknown_status</text>
<polyline fill="none" stroke="#000000" points="2740,-1531.5 2969,-1531.5 "/>
<text text-anchor="middle" x="2854.5" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_contact</text>
<polyline fill="none" stroke="#000000" points="2969,-1508.5 2969,-1623.5 "/>
<text text-anchor="middle" x="2979.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;case -->
<g id="edge22" class="edge">
<title>follow_up&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2780.3607,-1508.3387C2748.4909,-1456.4525 2694.185,-1383.0057 2625,-1347 2539.538,-1302.5233 1928.1522,-1262.7089 1639.3607,-1246.1476"/>
<polygon fill="#000000" stroke="#000000" points="1639.4085,-1242.6447 1629.225,-1245.5683 1639.009,-1249.6333 1639.4085,-1242.6447"/>
<text text-anchor="middle" x="2575" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
</g>
</svg>
</div>
