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
<svg width="3052pt" height="3683pt"
 viewBox="0.00 0.00 3051.50 3683.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 3679)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-3679 3047.5,-3679 3047.5,4 -4,4"/>
<!-- diagnosis -->
<g id="node1" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M651.5,-1803.5C651.5,-1803.5 994.5,-1803.5 994.5,-1803.5 1000.5,-1803.5 1006.5,-1809.5 1006.5,-1815.5 1006.5,-1815.5 1006.5,-2228.5 1006.5,-2228.5 1006.5,-2234.5 1000.5,-2240.5 994.5,-2240.5 994.5,-2240.5 651.5,-2240.5 651.5,-2240.5 645.5,-2240.5 639.5,-2234.5 639.5,-2228.5 639.5,-2228.5 639.5,-1815.5 639.5,-1815.5 639.5,-1809.5 645.5,-1803.5 651.5,-1803.5"/>
<text text-anchor="middle" x="681.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="723.5,-1803.5 723.5,-2240.5 "/>
<text text-anchor="middle" x="734" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="744.5,-1803.5 744.5,-2240.5 "/>
<text text-anchor="middle" x="865" y="-2225.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_histology_confirmation</text>
<polyline fill="none" stroke="#000000" points="744.5,-2217.5 985.5,-2217.5 "/>
<text text-anchor="middle" x="865" y="-2202.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_score</text>
<polyline fill="none" stroke="#000000" points="744.5,-2194.5 985.5,-2194.5 "/>
<text text-anchor="middle" x="865" y="-2179.3" font-family="Times,serif" font-size="14.00" fill="#000000">histology_cytopathology</text>
<polyline fill="none" stroke="#000000" points="744.5,-2171.5 985.5,-2171.5 "/>
<text text-anchor="middle" x="865" y="-2156.3" font-family="Times,serif" font-size="14.00" fill="#000000">nuclear_grade</text>
<polyline fill="none" stroke="#000000" points="744.5,-2148.5 985.5,-2148.5 "/>
<text text-anchor="middle" x="865" y="-2133.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_term</text>
<polyline fill="none" stroke="#000000" points="744.5,-2125.5 985.5,-2125.5 "/>
<text text-anchor="middle" x="865" y="-2110.3" font-family="Times,serif" font-size="14.00" fill="#000000">progesterone_receptor_status</text>
<polyline fill="none" stroke="#000000" points="744.5,-2102.5 985.5,-2102.5 "/>
<text text-anchor="middle" x="865" y="-2087.3" font-family="Times,serif" font-size="14.00" fill="#000000">histological_grade</text>
<polyline fill="none" stroke="#000000" points="744.5,-2079.5 985.5,-2079.5 "/>
<text text-anchor="middle" x="865" y="-2064.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="744.5,-2056.5 985.5,-2056.5 "/>
<text text-anchor="middle" x="865" y="-2041.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_group</text>
<polyline fill="none" stroke="#000000" points="744.5,-2033.5 985.5,-2033.5 "/>
<text text-anchor="middle" x="865" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">stage_of_disease</text>
<polyline fill="none" stroke="#000000" points="744.5,-2010.5 985.5,-2010.5 "/>
<text text-anchor="middle" x="865" y="-1995.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease</text>
<polyline fill="none" stroke="#000000" points="744.5,-1987.5 985.5,-1987.5 "/>
<text text-anchor="middle" x="865" y="-1972.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size</text>
<polyline fill="none" stroke="#000000" points="744.5,-1964.5 985.5,-1964.5 "/>
<text text-anchor="middle" x="865" y="-1949.3" font-family="Times,serif" font-size="14.00" fill="#000000">estrogen_receptor_status</text>
<polyline fill="none" stroke="#000000" points="744.5,-1941.5 985.5,-1941.5 "/>
<text text-anchor="middle" x="865" y="-1926.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_report</text>
<polyline fill="none" stroke="#000000" points="744.5,-1918.5 985.5,-1918.5 "/>
<text text-anchor="middle" x="865" y="-1903.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_code</text>
<polyline fill="none" stroke="#000000" points="744.5,-1895.5 985.5,-1895.5 "/>
<text text-anchor="middle" x="865" y="-1880.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_data</text>
<polyline fill="none" stroke="#000000" points="744.5,-1872.5 985.5,-1872.5 "/>
<text text-anchor="middle" x="865" y="-1857.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_disease_site</text>
<polyline fill="none" stroke="#000000" points="744.5,-1849.5 985.5,-1849.5 "/>
<text text-anchor="middle" x="865" y="-1834.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease_type</text>
<polyline fill="none" stroke="#000000" points="744.5,-1826.5 985.5,-1826.5 "/>
<text text-anchor="middle" x="865" y="-1811.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_data</text>
<polyline fill="none" stroke="#000000" points="985.5,-1803.5 985.5,-2240.5 "/>
<text text-anchor="middle" x="996" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case -->
<g id="node9" class="node">
<title>case</title>
<path fill="none" stroke="#000000" d="M1361,-1180.5C1361,-1180.5 1617,-1180.5 1617,-1180.5 1623,-1180.5 1629,-1186.5 1629,-1192.5 1629,-1192.5 1629,-1283.5 1629,-1283.5 1629,-1289.5 1623,-1295.5 1617,-1295.5 1617,-1295.5 1361,-1295.5 1361,-1295.5 1355,-1295.5 1349,-1289.5 1349,-1283.5 1349,-1283.5 1349,-1192.5 1349,-1192.5 1349,-1186.5 1355,-1180.5 1361,-1180.5"/>
<text text-anchor="middle" x="1373.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">case</text>
<polyline fill="none" stroke="#000000" points="1398,-1180.5 1398,-1295.5 "/>
<text text-anchor="middle" x="1408.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1419,-1180.5 1419,-1295.5 "/>
<text text-anchor="middle" x="1513.5" y="-1280.3" font-family="Times,serif" font-size="14.00" fill="#000000">included_in_analysis</text>
<polyline fill="none" stroke="#000000" points="1419,-1272.5 1608,-1272.5 "/>
<text text-anchor="middle" x="1513.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">on_study_crf_submitted</text>
<polyline fill="none" stroke="#000000" points="1419,-1249.5 1608,-1249.5 "/>
<text text-anchor="middle" x="1513.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">ineligible</text>
<polyline fill="none" stroke="#000000" points="1419,-1226.5 1608,-1226.5 "/>
<text text-anchor="middle" x="1513.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">case_id</text>
<polyline fill="none" stroke="#000000" points="1419,-1203.5 1608,-1203.5 "/>
<text text-anchor="middle" x="1513.5" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_id</text>
<polyline fill="none" stroke="#000000" points="1608,-1180.5 1608,-1295.5 "/>
<text text-anchor="middle" x="1618.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;case -->
<g id="edge9" class="edge">
<title>diagnosis&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M929.7156,-1803.2152C931.6125,-1797.1231 933.3808,-1791.0444 935,-1785 960.2708,-1690.6646 906.4053,-1420.2482 971,-1347 1018.8106,-1292.7844 1203.4667,-1264.0401 1338.7298,-1249.9354"/>
<polygon fill="#000000" stroke="#000000" points="1339.1982,-1253.4058 1348.7889,-1248.9038 1338.484,-1246.4423 1339.1982,-1253.4058"/>
<text text-anchor="middle" x="998" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- assay -->
<g id="node2" class="node">
<title>assay</title>
<path fill="none" stroke="#000000" d="M262,-2425.5C262,-2425.5 294,-2425.5 294,-2425.5 300,-2425.5 306,-2431.5 306,-2437.5 306,-2437.5 306,-2449.5 306,-2449.5 306,-2455.5 300,-2461.5 294,-2461.5 294,-2461.5 262,-2461.5 262,-2461.5 256,-2461.5 250,-2455.5 250,-2449.5 250,-2449.5 250,-2437.5 250,-2437.5 250,-2431.5 256,-2425.5 262,-2425.5"/>
<text text-anchor="middle" x="278" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">assay</text>
</g>
<!-- sample -->
<g id="node11" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M66.5,-1347.5C66.5,-1347.5 489.5,-1347.5 489.5,-1347.5 495.5,-1347.5 501.5,-1353.5 501.5,-1359.5 501.5,-1359.5 501.5,-1772.5 501.5,-1772.5 501.5,-1778.5 495.5,-1784.5 489.5,-1784.5 489.5,-1784.5 66.5,-1784.5 66.5,-1784.5 60.5,-1784.5 54.5,-1778.5 54.5,-1772.5 54.5,-1772.5 54.5,-1359.5 54.5,-1359.5 54.5,-1353.5 60.5,-1347.5 66.5,-1347.5"/>
<text text-anchor="middle" x="88.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="122.5,-1347.5 122.5,-1784.5 "/>
<text text-anchor="middle" x="133" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="143.5,-1347.5 143.5,-1784.5 "/>
<text text-anchor="middle" x="312" y="-1769.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="143.5,-1761.5 480.5,-1761.5 "/>
<text text-anchor="middle" x="312" y="-1746.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="143.5,-1738.5 480.5,-1738.5 "/>
<text text-anchor="middle" x="312" y="-1723.3" font-family="Times,serif" font-size="14.00" fill="#000000">width_of_tumor</text>
<polyline fill="none" stroke="#000000" points="143.5,-1715.5 480.5,-1715.5 "/>
<text text-anchor="middle" x="312" y="-1700.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="143.5,-1692.5 480.5,-1692.5 "/>
<text text-anchor="middle" x="312" y="-1677.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_tumor</text>
<polyline fill="none" stroke="#000000" points="143.5,-1669.5 480.5,-1669.5 "/>
<text text-anchor="middle" x="312" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area</text>
<polyline fill="none" stroke="#000000" points="143.5,-1646.5 480.5,-1646.5 "/>
<text text-anchor="middle" x="312" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_tissue_area</text>
<polyline fill="none" stroke="#000000" points="143.5,-1623.5 480.5,-1623.5 "/>
<text text-anchor="middle" x="312" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_sample_collection</text>
<polyline fill="none" stroke="#000000" points="143.5,-1600.5 480.5,-1600.5 "/>
<text text-anchor="middle" x="312" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_pigmented_tumor</text>
<polyline fill="none" stroke="#000000" points="143.5,-1577.5 480.5,-1577.5 "/>
<text text-anchor="middle" x="312" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">non_tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="143.5,-1554.5 480.5,-1554.5 "/>
<text text-anchor="middle" x="312" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="143.5,-1531.5 480.5,-1531.5 "/>
<text text-anchor="middle" x="312" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="143.5,-1508.5 480.5,-1508.5 "/>
<text text-anchor="middle" x="312" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="143.5,-1485.5 480.5,-1485.5 "/>
<text text-anchor="middle" x="312" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="143.5,-1462.5 480.5,-1462.5 "/>
<text text-anchor="middle" x="312" y="-1447.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_glass</text>
<polyline fill="none" stroke="#000000" points="143.5,-1439.5 480.5,-1439.5 "/>
<text text-anchor="middle" x="312" y="-1424.3" font-family="Times,serif" font-size="14.00" fill="#000000">general_sample_pathology</text>
<polyline fill="none" stroke="#000000" points="143.5,-1416.5 480.5,-1416.5 "/>
<text text-anchor="middle" x="312" y="-1401.3" font-family="Times,serif" font-size="14.00" fill="#000000">necropsy_sample</text>
<polyline fill="none" stroke="#000000" points="143.5,-1393.5 480.5,-1393.5 "/>
<text text-anchor="middle" x="312" y="-1378.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="143.5,-1370.5 480.5,-1370.5 "/>
<text text-anchor="middle" x="312" y="-1355.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_status_date</text>
<polyline fill="none" stroke="#000000" points="480.5,-1347.5 480.5,-1784.5 "/>
<text text-anchor="middle" x="491" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay&#45;&gt;sample -->
<g id="edge1" class="edge">
<title>assay&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M278,-2425.1722C278,-2345.2645 278,-2021.2117 278,-1794.7844"/>
<polygon fill="#000000" stroke="#000000" points="281.5001,-1794.7519 278,-1784.7519 274.5001,-1794.752 281.5001,-1794.7519"/>
<text text-anchor="middle" x="314.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- prior_therapy -->
<g id="node3" class="node">
<title>prior_therapy</title>
<path fill="none" stroke="#000000" d="M1698,-2259.5C1698,-2259.5 2154,-2259.5 2154,-2259.5 2160,-2259.5 2166,-2265.5 2166,-2271.5 2166,-2271.5 2166,-2615.5 2166,-2615.5 2166,-2621.5 2160,-2627.5 2154,-2627.5 2154,-2627.5 1698,-2627.5 1698,-2627.5 1692,-2627.5 1686,-2621.5 1686,-2615.5 1686,-2615.5 1686,-2271.5 1686,-2271.5 1686,-2265.5 1692,-2259.5 1698,-2259.5"/>
<text text-anchor="middle" x="1743.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy</text>
<polyline fill="none" stroke="#000000" points="1801,-2259.5 1801,-2627.5 "/>
<text text-anchor="middle" x="1811.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1822,-2259.5 1822,-2627.5 "/>
<text text-anchor="middle" x="1983.5" y="-2612.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_at_site</text>
<polyline fill="none" stroke="#000000" points="1822,-2604.5 2145,-2604.5 "/>
<text text-anchor="middle" x="1983.5" y="-2589.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="1822,-2581.5 2145,-2581.5 "/>
<text text-anchor="middle" x="1983.5" y="-2566.3" font-family="Times,serif" font-size="14.00" fill="#000000">nonresponse_therapy_type</text>
<polyline fill="none" stroke="#000000" points="1822,-2558.5 2145,-2558.5 "/>
<text text-anchor="middle" x="1983.5" y="-2543.3" font-family="Times,serif" font-size="14.00" fill="#000000">best_response</text>
<polyline fill="none" stroke="#000000" points="1822,-2535.5 2145,-2535.5 "/>
<text text-anchor="middle" x="1983.5" y="-2520.3" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy_type</text>
<polyline fill="none" stroke="#000000" points="1822,-2512.5 2145,-2512.5 "/>
<text text-anchor="middle" x="1983.5" y="-2497.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_schedule</text>
<polyline fill="none" stroke="#000000" points="1822,-2489.5 2145,-2489.5 "/>
<text text-anchor="middle" x="1983.5" y="-2474.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_name</text>
<polyline fill="none" stroke="#000000" points="1822,-2466.5 2145,-2466.5 "/>
<text text-anchor="middle" x="1983.5" y="-2451.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_in_minimal_residual</text>
<polyline fill="none" stroke="#000000" points="1822,-2443.5 2145,-2443.5 "/>
<text text-anchor="middle" x="1983.5" y="-2428.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose</text>
<polyline fill="none" stroke="#000000" points="1822,-2420.5 2145,-2420.5 "/>
<text text-anchor="middle" x="1983.5" y="-2405.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_dose</text>
<polyline fill="none" stroke="#000000" points="1822,-2397.5 2145,-2397.5 "/>
<text text-anchor="middle" x="1983.5" y="-2382.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_first_dose</text>
<polyline fill="none" stroke="#000000" points="1822,-2374.5 2145,-2374.5 "/>
<text text-anchor="middle" x="1983.5" y="-2359.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_prior_regimens_any_therapy</text>
<polyline fill="none" stroke="#000000" points="1822,-2351.5 2145,-2351.5 "/>
<text text-anchor="middle" x="1983.5" y="-2336.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose_any_therapy</text>
<polyline fill="none" stroke="#000000" points="1822,-2328.5 2145,-2328.5 "/>
<text text-anchor="middle" x="1983.5" y="-2313.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapy_type</text>
<polyline fill="none" stroke="#000000" points="1822,-2305.5 2145,-2305.5 "/>
<text text-anchor="middle" x="1983.5" y="-2290.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_number_of_doses_any_therapy</text>
<polyline fill="none" stroke="#000000" points="1822,-2282.5 2145,-2282.5 "/>
<text text-anchor="middle" x="1983.5" y="-2267.3" font-family="Times,serif" font-size="14.00" fill="#000000">any_therapy</text>
<polyline fill="none" stroke="#000000" points="2145,-2259.5 2145,-2627.5 "/>
<text text-anchor="middle" x="2155.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_therapy&#45;&gt;prior_therapy -->
<g id="edge23" class="edge">
<title>prior_therapy&#45;&gt;prior_therapy</title>
<path fill="none" stroke="#000000" d="M2166.2384,-2468.2536C2177.4387,-2462.0051 2184,-2453.7539 2184,-2443.5 2184,-2436.13 2180.6104,-2429.7946 2174.545,-2424.4938"/>
<polygon fill="#000000" stroke="#000000" points="2176.4534,-2421.5581 2166.2384,-2418.7464 2172.4704,-2427.3146 2176.4534,-2421.5581"/>
<text text-anchor="middle" x="2200" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- enrollment -->
<g id="node18" class="node">
<title>enrollment</title>
<path fill="none" stroke="#000000" d="M1968,-1497C1968,-1497 2286,-1497 2286,-1497 2292,-1497 2298,-1503 2298,-1509 2298,-1509 2298,-1623 2298,-1623 2298,-1629 2292,-1635 2286,-1635 2286,-1635 1968,-1635 1968,-1635 1962,-1635 1956,-1629 1956,-1623 1956,-1623 1956,-1509 1956,-1509 1956,-1503 1962,-1497 1968,-1497"/>
<text text-anchor="middle" x="2003.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrollment</text>
<polyline fill="none" stroke="#000000" points="2051,-1497 2051,-1635 "/>
<text text-anchor="middle" x="2061.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2072,-1497 2072,-1635 "/>
<text text-anchor="middle" x="2174.5" y="-1619.8" font-family="Times,serif" font-size="14.00" fill="#000000">registering_institution</text>
<polyline fill="none" stroke="#000000" points="2072,-1612 2277,-1612 "/>
<text text-anchor="middle" x="2174.5" y="-1596.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_short_name</text>
<polyline fill="none" stroke="#000000" points="2072,-1589 2277,-1589 "/>
<text text-anchor="middle" x="2174.5" y="-1573.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_informed_consent</text>
<polyline fill="none" stroke="#000000" points="2072,-1566 2277,-1566 "/>
<text text-anchor="middle" x="2174.5" y="-1550.8" font-family="Times,serif" font-size="14.00" fill="#000000">patient_subgroup</text>
<polyline fill="none" stroke="#000000" points="2072,-1543 2277,-1543 "/>
<text text-anchor="middle" x="2174.5" y="-1527.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_registration</text>
<polyline fill="none" stroke="#000000" points="2072,-1520 2277,-1520 "/>
<text text-anchor="middle" x="2174.5" y="-1504.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="2277,-1497 2277,-1635 "/>
<text text-anchor="middle" x="2287.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_therapy&#45;&gt;enrollment -->
<g id="edge34" class="edge">
<title>prior_therapy&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M1968.1974,-2259.2799C2011.6657,-2069.5116 2077.3781,-1782.6328 2108.8921,-1645.0531"/>
<polygon fill="#000000" stroke="#000000" points="2112.3717,-1645.5377 2111.1929,-1635.0086 2105.5484,-1643.9747 2112.3717,-1645.5377"/>
<text text-anchor="middle" x="2118" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- follow_up -->
<g id="node4" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M582,-1508.5C582,-1508.5 914,-1508.5 914,-1508.5 920,-1508.5 926,-1514.5 926,-1520.5 926,-1520.5 926,-1611.5 926,-1611.5 926,-1617.5 920,-1623.5 914,-1623.5 914,-1623.5 582,-1623.5 582,-1623.5 576,-1623.5 570,-1617.5 570,-1611.5 570,-1611.5 570,-1520.5 570,-1520.5 570,-1514.5 576,-1508.5 582,-1508.5"/>
<text text-anchor="middle" x="612.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="655,-1508.5 655,-1623.5 "/>
<text text-anchor="middle" x="665.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="676,-1508.5 676,-1623.5 "/>
<text text-anchor="middle" x="790.5" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_since_last_contact</text>
<polyline fill="none" stroke="#000000" points="676,-1600.5 905,-1600.5 "/>
<text text-anchor="middle" x="790.5" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_status</text>
<polyline fill="none" stroke="#000000" points="676,-1577.5 905,-1577.5 "/>
<text text-anchor="middle" x="790.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_contact</text>
<polyline fill="none" stroke="#000000" points="676,-1554.5 905,-1554.5 "/>
<text text-anchor="middle" x="790.5" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">explain_unknown_status</text>
<polyline fill="none" stroke="#000000" points="676,-1531.5 905,-1531.5 "/>
<text text-anchor="middle" x="790.5" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">contact_type</text>
<polyline fill="none" stroke="#000000" points="905,-1508.5 905,-1623.5 "/>
<text text-anchor="middle" x="915.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;case -->
<g id="edge8" class="edge">
<title>follow_up&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M764.6251,-1508.4473C784.9319,-1449.2978 825.3506,-1359.6041 894,-1314 964.6971,-1267.0356 1186.5964,-1249.0662 1338.4829,-1242.2083"/>
<polygon fill="#000000" stroke="#000000" points="1339.0025,-1245.689 1348.839,-1241.753 1338.6949,-1238.6957 1339.0025,-1245.689"/>
<text text-anchor="middle" x="921" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- study_arm -->
<g id="node5" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1092.5,-518.5C1092.5,-518.5 1461.5,-518.5 1461.5,-518.5 1467.5,-518.5 1473.5,-524.5 1473.5,-530.5 1473.5,-530.5 1473.5,-575.5 1473.5,-575.5 1473.5,-581.5 1467.5,-587.5 1461.5,-587.5 1461.5,-587.5 1092.5,-587.5 1092.5,-587.5 1086.5,-587.5 1080.5,-581.5 1080.5,-575.5 1080.5,-575.5 1080.5,-530.5 1080.5,-530.5 1080.5,-524.5 1086.5,-518.5 1092.5,-518.5"/>
<text text-anchor="middle" x="1126.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1172.5,-518.5 1172.5,-587.5 "/>
<text text-anchor="middle" x="1183" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1193.5,-518.5 1193.5,-587.5 "/>
<text text-anchor="middle" x="1323" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_arm_version</text>
<polyline fill="none" stroke="#000000" points="1193.5,-564.5 1452.5,-564.5 "/>
<text text-anchor="middle" x="1323" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm</text>
<polyline fill="none" stroke="#000000" points="1193.5,-541.5 1452.5,-541.5 "/>
<text text-anchor="middle" x="1323" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_treatment_assignment_code</text>
<polyline fill="none" stroke="#000000" points="1452.5,-518.5 1452.5,-587.5 "/>
<text text-anchor="middle" x="1463" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node17" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1331,-236.5C1331,-236.5 1611,-236.5 1611,-236.5 1617,-236.5 1623,-242.5 1623,-248.5 1623,-248.5 1623,-454.5 1623,-454.5 1623,-460.5 1617,-466.5 1611,-466.5 1611,-466.5 1331,-466.5 1331,-466.5 1325,-466.5 1319,-460.5 1319,-454.5 1319,-454.5 1319,-248.5 1319,-248.5 1319,-242.5 1325,-236.5 1331,-236.5"/>
<text text-anchor="middle" x="1347" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1375,-236.5 1375,-466.5 "/>
<text text-anchor="middle" x="1385.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1396,-236.5 1396,-466.5 "/>
<text text-anchor="middle" x="1499" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_category</text>
<polyline fill="none" stroke="#000000" points="1396,-443.5 1602,-443.5 "/>
<text text-anchor="middle" x="1499" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_id</text>
<polyline fill="none" stroke="#000000" points="1396,-420.5 1602,-420.5 "/>
<text text-anchor="middle" x="1499" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">dates_of_conduct</text>
<polyline fill="none" stroke="#000000" points="1396,-397.5 1602,-397.5 "/>
<text text-anchor="middle" x="1499" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_designation</text>
<polyline fill="none" stroke="#000000" points="1396,-374.5 1602,-374.5 "/>
<text text-anchor="middle" x="1499" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_description</text>
<polyline fill="none" stroke="#000000" points="1396,-351.5 1602,-351.5 "/>
<text text-anchor="middle" x="1499" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_term</text>
<polyline fill="none" stroke="#000000" points="1396,-328.5 1602,-328.5 "/>
<text text-anchor="middle" x="1499" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_type</text>
<polyline fill="none" stroke="#000000" points="1396,-305.5 1602,-305.5 "/>
<text text-anchor="middle" x="1499" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_name</text>
<polyline fill="none" stroke="#000000" points="1396,-282.5 1602,-282.5 "/>
<text text-anchor="middle" x="1499" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_iacuc_approval</text>
<polyline fill="none" stroke="#000000" points="1396,-259.5 1602,-259.5 "/>
<text text-anchor="middle" x="1499" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_su_category</text>
<polyline fill="none" stroke="#000000" points="1602,-236.5 1602,-466.5 "/>
<text text-anchor="middle" x="1612.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge17" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1363.5103,-518.4317C1372.3044,-512.9968 1380.6788,-506.8656 1388,-500 1396.0815,-492.4214 1403.5767,-483.8753 1410.4839,-474.808"/>
<polygon fill="#000000" stroke="#000000" points="1413.3235,-476.8544 1416.4025,-466.7168 1407.6737,-472.7216 1413.3235,-476.8544"/>
<text text-anchor="middle" x="1431.5" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge28" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1286.2455,-518.3353C1290.2672,-507.0479 1295.7547,-494.89 1303,-485 1305.8759,-481.0744 1308.8957,-477.2018 1312.0372,-473.3871"/>
<polygon fill="#000000" stroke="#000000" points="1314.8199,-475.5181 1318.6495,-465.6396 1309.4954,-470.9738 1314.8199,-475.5181"/>
<text text-anchor="middle" x="1343.5" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort -->
<g id="node6" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M1393.5,-639.5C1393.5,-639.5 1626.5,-639.5 1626.5,-639.5 1632.5,-639.5 1638.5,-645.5 1638.5,-651.5 1638.5,-651.5 1638.5,-673.5 1638.5,-673.5 1638.5,-679.5 1632.5,-685.5 1626.5,-685.5 1626.5,-685.5 1393.5,-685.5 1393.5,-685.5 1387.5,-685.5 1381.5,-679.5 1381.5,-673.5 1381.5,-673.5 1381.5,-651.5 1381.5,-651.5 1381.5,-645.5 1387.5,-639.5 1393.5,-639.5"/>
<text text-anchor="middle" x="1413" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="1444.5,-639.5 1444.5,-685.5 "/>
<text text-anchor="middle" x="1455" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1465.5,-639.5 1465.5,-685.5 "/>
<text text-anchor="middle" x="1541.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_dose</text>
<polyline fill="none" stroke="#000000" points="1465.5,-662.5 1617.5,-662.5 "/>
<text text-anchor="middle" x="1541.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1617.5,-639.5 1617.5,-685.5 "/>
<text text-anchor="middle" x="1628" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- cohort&#45;&gt;study_arm -->
<g id="edge27" class="edge">
<title>cohort&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1456.0492,-639.4447C1442.5873,-633.5512 1428.2217,-627.1415 1415,-621 1395.3431,-611.8694 1374.2819,-601.6947 1354.6818,-592.0553"/>
<polygon fill="#000000" stroke="#000000" points="1356.0075,-588.8066 1345.4908,-587.522 1352.911,-595.0845 1356.0075,-588.8066"/>
<text text-anchor="middle" x="1455.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort&#45;&gt;study -->
<g id="edge26" class="edge">
<title>cohort&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1507.1005,-639.3785C1502.7779,-604.9081 1494.3326,-537.5625 1486.6968,-476.6718"/>
<polygon fill="#000000" stroke="#000000" points="1490.1471,-476.056 1485.4299,-466.5692 1483.2015,-476.927 1490.1471,-476.056"/>
<text text-anchor="middle" x="1541.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- agent -->
<g id="node7" class="node">
<title>agent</title>
<path fill="none" stroke="#000000" d="M1180.5,-644.5C1180.5,-644.5 1351.5,-644.5 1351.5,-644.5 1357.5,-644.5 1363.5,-650.5 1363.5,-656.5 1363.5,-656.5 1363.5,-668.5 1363.5,-668.5 1363.5,-674.5 1357.5,-680.5 1351.5,-680.5 1351.5,-680.5 1180.5,-680.5 1180.5,-680.5 1174.5,-680.5 1168.5,-674.5 1168.5,-668.5 1168.5,-668.5 1168.5,-656.5 1168.5,-656.5 1168.5,-650.5 1174.5,-644.5 1180.5,-644.5"/>
<text text-anchor="middle" x="1197" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">agent</text>
<polyline fill="none" stroke="#000000" points="1225.5,-644.5 1225.5,-680.5 "/>
<text text-anchor="middle" x="1236" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1246.5,-644.5 1246.5,-680.5 "/>
<text text-anchor="middle" x="1294.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="1342.5,-644.5 1342.5,-680.5 "/>
<text text-anchor="middle" x="1353" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- agent&#45;&gt;study_arm -->
<g id="edge20" class="edge">
<title>agent&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1267.8164,-644.4183C1269.0899,-631.7417 1270.8509,-614.2114 1272.4905,-597.8901"/>
<polygon fill="#000000" stroke="#000000" points="1275.9731,-598.2379 1273.4902,-587.9381 1269.0081,-597.5382 1275.9731,-598.2379"/>
<text text-anchor="middle" x="1320.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- visit -->
<g id="node8" class="node">
<title>visit</title>
<path fill="none" stroke="#000000" d="M482.5,-3318C482.5,-3318 657.5,-3318 657.5,-3318 663.5,-3318 669.5,-3324 669.5,-3330 669.5,-3330 669.5,-3352 669.5,-3352 669.5,-3358 663.5,-3364 657.5,-3364 657.5,-3364 482.5,-3364 482.5,-3364 476.5,-3364 470.5,-3358 470.5,-3352 470.5,-3352 470.5,-3330 470.5,-3330 470.5,-3324 476.5,-3318 482.5,-3318"/>
<text text-anchor="middle" x="494" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">visit</text>
<polyline fill="none" stroke="#000000" points="517.5,-3318 517.5,-3364 "/>
<text text-anchor="middle" x="528" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="538.5,-3318 538.5,-3364 "/>
<text text-anchor="middle" x="593.5" y="-3348.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_date</text>
<polyline fill="none" stroke="#000000" points="538.5,-3341 648.5,-3341 "/>
<text text-anchor="middle" x="593.5" y="-3325.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_number</text>
<polyline fill="none" stroke="#000000" points="648.5,-3318 648.5,-3364 "/>
<text text-anchor="middle" x="659" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- visit&#45;&gt;visit -->
<g id="edge22" class="edge">
<title>visit&#45;&gt;visit</title>
<path fill="none" stroke="#000000" d="M582.2183,-3364.2371C623.4427,-3429.6803 687.5,-3421.9346 687.5,-3341 687.5,-3263.7012 629.0686,-3253.1633 587.9043,-3309.3865"/>
<polygon fill="#000000" stroke="#000000" points="584.9389,-3307.5233 582.2183,-3317.7629 590.7306,-3311.4548 584.9389,-3307.5233"/>
<text text-anchor="middle" x="703.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- case&#45;&gt;study_arm -->
<g id="edge31" class="edge">
<title>case&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1348.6913,-1232.0138C1097.6629,-1219.8541 592.8414,-1188.258 540,-1129 424.0478,-998.9674 432.7596,-874.3058 540,-737 604.8286,-653.9963 875.6561,-602.9413 1070.1938,-576.2794"/>
<polygon fill="#000000" stroke="#000000" points="1070.8325,-579.7249 1080.2704,-574.9107 1069.8903,-572.7885 1070.8325,-579.7249"/>
<text text-anchor="middle" x="618.5" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- case&#45;&gt;cohort -->
<g id="edge30" class="edge">
<title>case&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M1543.1719,-1180.3076C1546.6942,-1174.4234 1549.7328,-1168.2877 1552,-1162 1554.2614,-1155.7286 1552.1138,-1153.6657 1552,-1147 1548.8884,-964.6981 1573.6546,-915.8083 1538,-737 1535.1794,-722.8544 1530.0032,-707.8574 1524.8616,-695.0554"/>
<polygon fill="#000000" stroke="#000000" points="1528.0573,-693.6249 1520.9762,-685.744 1521.5971,-696.3206 1528.0573,-693.6249"/>
<text text-anchor="middle" x="1598.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- adverse_event -->
<g id="node15" class="node">
<title>adverse_event</title>
<path fill="none" stroke="#000000" d="M1072.5,-818C1072.5,-818 1467.5,-818 1467.5,-818 1473.5,-818 1479.5,-824 1479.5,-830 1479.5,-830 1479.5,-1036 1479.5,-1036 1479.5,-1042 1473.5,-1048 1467.5,-1048 1467.5,-1048 1072.5,-1048 1072.5,-1048 1066.5,-1048 1060.5,-1042 1060.5,-1036 1060.5,-1036 1060.5,-830 1060.5,-830 1060.5,-824 1066.5,-818 1072.5,-818"/>
<text text-anchor="middle" x="1120.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="1180.5,-818 1180.5,-1048 "/>
<text text-anchor="middle" x="1191" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1201.5,-818 1201.5,-1048 "/>
<text text-anchor="middle" x="1330" y="-1032.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_agent_name</text>
<polyline fill="none" stroke="#000000" points="1201.5,-1025 1458.5,-1025 "/>
<text text-anchor="middle" x="1330" y="-1009.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade</text>
<polyline fill="none" stroke="#000000" points="1201.5,-1002 1458.5,-1002 "/>
<text text-anchor="middle" x="1330" y="-986.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_description</text>
<polyline fill="none" stroke="#000000" points="1201.5,-979 1458.5,-979 "/>
<text text-anchor="middle" x="1330" y="-963.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_resolved</text>
<polyline fill="none" stroke="#000000" points="1201.5,-956 1458.5,-956 "/>
<text text-anchor="middle" x="1330" y="-940.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_attribution</text>
<polyline fill="none" stroke="#000000" points="1201.5,-933 1458.5,-933 "/>
<text text-anchor="middle" x="1330" y="-917.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_other</text>
<polyline fill="none" stroke="#000000" points="1201.5,-910 1458.5,-910 "/>
<text text-anchor="middle" x="1330" y="-894.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade_description</text>
<polyline fill="none" stroke="#000000" points="1201.5,-887 1458.5,-887 "/>
<text text-anchor="middle" x="1330" y="-871.8" font-family="Times,serif" font-size="14.00" fill="#000000">unexpected_adverse_event</text>
<polyline fill="none" stroke="#000000" points="1201.5,-864 1458.5,-864 "/>
<text text-anchor="middle" x="1330" y="-848.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_term</text>
<polyline fill="none" stroke="#000000" points="1201.5,-841 1458.5,-841 "/>
<text text-anchor="middle" x="1330" y="-825.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_dose</text>
<polyline fill="none" stroke="#000000" points="1458.5,-818 1458.5,-1048 "/>
<text text-anchor="middle" x="1469" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;adverse_event -->
<g id="edge19" class="edge">
<title>case&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M1429.5302,-1180.2585C1424.1026,-1174.248 1418.8352,-1168.1023 1414,-1162 1388.188,-1129.4235 1363.013,-1092.0026 1341.1194,-1056.9801"/>
<polygon fill="#000000" stroke="#000000" points="1343.8741,-1054.7814 1335.6256,-1048.1321 1337.9272,-1058.4739 1343.8741,-1054.7814"/>
<text text-anchor="middle" x="1483" y="-1150.8" font-family="Times,serif" font-size="14.00" fill="#000000">had_adverse_event</text>
</g>
<!-- case&#45;&gt;study -->
<g id="edge29" class="edge">
<title>case&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1594.7306,-1180.4043C1613.3468,-1165.8923 1630.6791,-1148.7245 1643,-1129 1689.7613,-1054.1402 1675,-1021.2645 1675,-933 1675,-933 1675,-933 1675,-553 1675,-514.5001 1656.3815,-480.8719 1630.3939,-452.6855"/>
<polygon fill="#000000" stroke="#000000" points="1632.711,-450.0455 1623.2585,-445.26 1627.6636,-454.8956 1632.711,-450.0455"/>
<text text-anchor="middle" x="1715.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- genomic_report -->
<g id="node10" class="node">
<title>genomic_report</title>
<path fill="none" stroke="#000000" d="M90,-2679.5C90,-2679.5 466,-2679.5 466,-2679.5 472,-2679.5 478,-2685.5 478,-2691.5 478,-2691.5 478,-2943.5 478,-2943.5 478,-2949.5 472,-2955.5 466,-2955.5 466,-2955.5 90,-2955.5 90,-2955.5 84,-2955.5 78,-2949.5 78,-2943.5 78,-2943.5 78,-2691.5 78,-2691.5 78,-2685.5 84,-2679.5 90,-2679.5"/>
<text text-anchor="middle" x="143" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_report</text>
<polyline fill="none" stroke="#000000" points="208,-2679.5 208,-2955.5 "/>
<text text-anchor="middle" x="218.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="229,-2679.5 229,-2955.5 "/>
<text text-anchor="middle" x="343" y="-2940.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_mois</text>
<polyline fill="none" stroke="#000000" points="229,-2932.5 457,-2932.5 "/>
<text text-anchor="middle" x="343" y="-2917.3" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="229,-2909.5 457,-2909.5 "/>
<text text-anchor="middle" x="343" y="-2894.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_amois</text>
<polyline fill="none" stroke="#000000" points="229,-2886.5 457,-2886.5 "/>
<text text-anchor="middle" x="343" y="-2871.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="229,-2863.5 457,-2863.5 "/>
<text text-anchor="middle" x="343" y="-2848.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="229,-2840.5 457,-2840.5 "/>
<text text-anchor="middle" x="343" y="-2825.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_type</text>
<polyline fill="none" stroke="#000000" points="229,-2817.5 457,-2817.5 "/>
<text text-anchor="middle" x="343" y="-2802.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_variants</text>
<polyline fill="none" stroke="#000000" points="229,-2794.5 457,-2794.5 "/>
<text text-anchor="middle" x="343" y="-2779.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_mois</text>
<polyline fill="none" stroke="#000000" points="229,-2771.5 457,-2771.5 "/>
<text text-anchor="middle" x="343" y="-2756.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id</text>
<polyline fill="none" stroke="#000000" points="229,-2748.5 457,-2748.5 "/>
<text text-anchor="middle" x="343" y="-2733.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_amois</text>
<polyline fill="none" stroke="#000000" points="229,-2725.5 457,-2725.5 "/>
<text text-anchor="middle" x="343" y="-2710.3" font-family="Times,serif" font-size="14.00" fill="#000000">cellularity</text>
<polyline fill="none" stroke="#000000" points="229,-2702.5 457,-2702.5 "/>
<text text-anchor="middle" x="343" y="-2687.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_received_date</text>
<polyline fill="none" stroke="#000000" points="457,-2679.5 457,-2955.5 "/>
<text text-anchor="middle" x="467.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_report&#45;&gt;assay -->
<g id="edge14" class="edge">
<title>genomic_report&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M278,-2679.2988C278,-2603.3354 278,-2515.8207 278,-2471.8459"/>
<polygon fill="#000000" stroke="#000000" points="281.5001,-2471.6375 278,-2461.6375 274.5001,-2471.6375 281.5001,-2471.6375"/>
<text text-anchor="middle" x="308.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- sample&#45;&gt;case -->
<g id="edge10" class="edge">
<title>sample&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M501.6718,-1376.7853C521.0323,-1365.4759 540.9151,-1355.33 561,-1347 697.9675,-1290.194 1112.5644,-1258.9341 1338.4188,-1245.7036"/>
<polygon fill="#000000" stroke="#000000" points="1338.917,-1249.1806 1348.6971,-1245.1063 1338.5109,-1242.1924 1338.917,-1249.1806"/>
<text text-anchor="middle" x="698" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- sample&#45;&gt;sample -->
<g id="edge25" class="edge">
<title>sample&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M501.5955,-1595.6213C512.8572,-1588.2644 519.5,-1578.3906 519.5,-1566 519.5,-1556.9006 515.9175,-1549.1586 509.5541,-1542.774"/>
<polygon fill="#000000" stroke="#000000" points="511.583,-1539.9144 501.5955,-1536.3787 507.1982,-1545.3709 511.583,-1539.9144"/>
<text text-anchor="middle" x="535.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- program -->
<g id="node12" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M1317,-.5C1317,-.5 1625,-.5 1625,-.5 1631,-.5 1637,-6.5 1637,-12.5 1637,-12.5 1637,-172.5 1637,-172.5 1637,-178.5 1631,-184.5 1625,-184.5 1625,-184.5 1317,-184.5 1317,-184.5 1311,-184.5 1305,-178.5 1305,-172.5 1305,-172.5 1305,-12.5 1305,-12.5 1305,-6.5 1311,-.5 1317,-.5"/>
<text text-anchor="middle" x="1344" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1383,-.5 1383,-184.5 "/>
<text text-anchor="middle" x="1393.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1404,-.5 1404,-184.5 "/>
<text text-anchor="middle" x="1510" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="1404,-161.5 1616,-161.5 "/>
<text text-anchor="middle" x="1510" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="1404,-138.5 1616,-138.5 "/>
<text text-anchor="middle" x="1510" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1404,-115.5 1616,-115.5 "/>
<text text-anchor="middle" x="1510" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="1404,-92.5 1616,-92.5 "/>
<text text-anchor="middle" x="1510" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="1404,-69.5 1616,-69.5 "/>
<text text-anchor="middle" x="1510" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="1404,-46.5 1616,-46.5 "/>
<text text-anchor="middle" x="1510" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="1404,-23.5 1616,-23.5 "/>
<text text-anchor="middle" x="1510" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="1616,-.5 1616,-184.5 "/>
<text text-anchor="middle" x="1626.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment -->
<g id="node13" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M1046.5,-1462.5C1046.5,-1462.5 1471.5,-1462.5 1471.5,-1462.5 1477.5,-1462.5 1483.5,-1468.5 1483.5,-1474.5 1483.5,-1474.5 1483.5,-1657.5 1483.5,-1657.5 1483.5,-1663.5 1477.5,-1669.5 1471.5,-1669.5 1471.5,-1669.5 1046.5,-1669.5 1046.5,-1669.5 1040.5,-1669.5 1034.5,-1663.5 1034.5,-1657.5 1034.5,-1657.5 1034.5,-1474.5 1034.5,-1474.5 1034.5,-1468.5 1040.5,-1462.5 1046.5,-1462.5"/>
<text text-anchor="middle" x="1079" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="1123.5,-1462.5 1123.5,-1669.5 "/>
<text text-anchor="middle" x="1134" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1144.5,-1462.5 1144.5,-1669.5 "/>
<text text-anchor="middle" x="1303.5" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">endocrine_therapy_discontinued</text>
<polyline fill="none" stroke="#000000" points="1144.5,-1646.5 1462.5,-1646.5 "/>
<text text-anchor="middle" x="1303.5" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_endocrine_therapy_received</text>
<polyline fill="none" stroke="#000000" points="1144.5,-1623.5 1462.5,-1623.5 "/>
<text text-anchor="middle" x="1303.5" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_first_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="1144.5,-1600.5 1462.5,-1600.5 "/>
<text text-anchor="middle" x="1303.5" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">specific_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="1144.5,-1577.5 1462.5,-1577.5 "/>
<text text-anchor="middle" x="1303.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_surgical_procedure</text>
<polyline fill="none" stroke="#000000" points="1144.5,-1554.5 1462.5,-1554.5 "/>
<text text-anchor="middle" x="1303.5" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_last_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="1144.5,-1531.5 1462.5,-1531.5 "/>
<text text-anchor="middle" x="1303.5" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">received_chemotherapy</text>
<polyline fill="none" stroke="#000000" points="1144.5,-1508.5 1462.5,-1508.5 "/>
<text text-anchor="middle" x="1303.5" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="1144.5,-1485.5 1462.5,-1485.5 "/>
<text text-anchor="middle" x="1303.5" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">duration_of_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="1462.5,-1462.5 1462.5,-1669.5 "/>
<text text-anchor="middle" x="1473" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;case -->
<g id="edge6" class="edge">
<title>treatment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1331.7734,-1462.2188C1368.0749,-1410.4497 1410.8953,-1349.3841 1442.6747,-1304.0639"/>
<polygon fill="#000000" stroke="#000000" points="1445.6004,-1305.9878 1448.4761,-1295.7907 1439.869,-1301.9688 1445.6004,-1305.9878"/>
<text text-anchor="middle" x="1461" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- stratification -->
<g id="node14" class="node">
<title>stratification</title>
<path fill="none" stroke="#000000" d="M1514,-1497C1514,-1497 1926,-1497 1926,-1497 1932,-1497 1938,-1503 1938,-1509 1938,-1509 1938,-1623 1938,-1623 1938,-1629 1932,-1635 1926,-1635 1926,-1635 1514,-1635 1514,-1635 1508,-1635 1502,-1629 1502,-1623 1502,-1623 1502,-1509 1502,-1509 1502,-1503 1508,-1497 1514,-1497"/>
<text text-anchor="middle" x="1557" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification</text>
<polyline fill="none" stroke="#000000" points="1612,-1497 1612,-1635 "/>
<text text-anchor="middle" x="1622.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1633,-1497 1633,-1635 "/>
<text text-anchor="middle" x="1775" y="-1619.8" font-family="Times,serif" font-size="14.00" fill="#000000">combined_stratification_variable</text>
<polyline fill="none" stroke="#000000" points="1633,-1612 1917,-1612 "/>
<text text-anchor="middle" x="1775" y="-1596.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_chemotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="1633,-1589 1917,-1589 "/>
<text text-anchor="middle" x="1775" y="-1573.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_stratification</text>
<polyline fill="none" stroke="#000000" points="1633,-1566 1917,-1566 "/>
<text text-anchor="middle" x="1775" y="-1550.8" font-family="Times,serif" font-size="14.00" fill="#000000">grouped_recurrence_score</text>
<polyline fill="none" stroke="#000000" points="1633,-1543 1917,-1543 "/>
<text text-anchor="middle" x="1775" y="-1527.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status_stratification</text>
<polyline fill="none" stroke="#000000" points="1633,-1520 1917,-1520 "/>
<text text-anchor="middle" x="1775" y="-1504.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_radiotherapy</text>
<polyline fill="none" stroke="#000000" points="1917,-1497 1917,-1635 "/>
<text text-anchor="middle" x="1927.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- stratification&#45;&gt;case -->
<g id="edge7" class="edge">
<title>stratification&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1671.2931,-1496.8404C1631.2552,-1439.9901 1574.9021,-1359.9736 1535.4843,-1304.0036"/>
<polygon fill="#000000" stroke="#000000" points="1538.1718,-1301.7411 1529.5521,-1295.5805 1532.4486,-1305.7717 1538.1718,-1301.7411"/>
<text text-anchor="middle" x="1578" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- adverse_event&#45;&gt;agent -->
<g id="edge11" class="edge">
<title>adverse_event&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M1268.2978,-817.8914C1267.6085,-771.2747 1266.8709,-721.3926 1266.4225,-691.0697"/>
<polygon fill="#000000" stroke="#000000" points="1269.9186,-690.7724 1266.271,-680.8252 1262.9193,-690.8759 1269.9186,-690.7724"/>
<text text-anchor="middle" x="1298" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- adverse_event&#45;&gt;adverse_event -->
<g id="edge24" class="edge">
<title>adverse_event&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M1479.7046,-960.2761C1490.876,-953.5862 1497.5,-944.4941 1497.5,-933 1497.5,-924.7386 1494.0781,-917.7181 1488.0052,-911.9385"/>
<polygon fill="#000000" stroke="#000000" points="1489.8073,-908.9155 1479.7046,-905.7239 1485.6119,-914.519 1489.8073,-908.9155"/>
<text text-anchor="middle" x="1513.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- prior_surgery -->
<g id="node16" class="node">
<title>prior_surgery</title>
<path fill="none" stroke="#000000" d="M2246,-2374.5C2246,-2374.5 2592,-2374.5 2592,-2374.5 2598,-2374.5 2604,-2380.5 2604,-2386.5 2604,-2386.5 2604,-2500.5 2604,-2500.5 2604,-2506.5 2598,-2512.5 2592,-2512.5 2592,-2512.5 2246,-2512.5 2246,-2512.5 2240,-2512.5 2234,-2506.5 2234,-2500.5 2234,-2500.5 2234,-2386.5 2234,-2386.5 2234,-2380.5 2240,-2374.5 2246,-2374.5"/>
<text text-anchor="middle" x="2291.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_surgery</text>
<polyline fill="none" stroke="#000000" points="2349,-2374.5 2349,-2512.5 "/>
<text text-anchor="middle" x="2359.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2370,-2374.5 2370,-2512.5 "/>
<text text-anchor="middle" x="2476.5" y="-2497.3" font-family="Times,serif" font-size="14.00" fill="#000000">residual_disease</text>
<polyline fill="none" stroke="#000000" points="2370,-2489.5 2583,-2489.5 "/>
<text text-anchor="middle" x="2476.5" y="-2474.3" font-family="Times,serif" font-size="14.00" fill="#000000">procedure</text>
<polyline fill="none" stroke="#000000" points="2370,-2466.5 2583,-2466.5 "/>
<text text-anchor="middle" x="2476.5" y="-2451.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomical_site_of_surgery</text>
<polyline fill="none" stroke="#000000" points="2370,-2443.5 2583,-2443.5 "/>
<text text-anchor="middle" x="2476.5" y="-2428.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_surgery</text>
<polyline fill="none" stroke="#000000" points="2370,-2420.5 2583,-2420.5 "/>
<text text-anchor="middle" x="2476.5" y="-2405.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_indicator</text>
<polyline fill="none" stroke="#000000" points="2370,-2397.5 2583,-2397.5 "/>
<text text-anchor="middle" x="2476.5" y="-2382.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_finding</text>
<polyline fill="none" stroke="#000000" points="2583,-2374.5 2583,-2512.5 "/>
<text text-anchor="middle" x="2593.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_surgery&#45;&gt;prior_surgery -->
<g id="edge21" class="edge">
<title>prior_surgery&#45;&gt;prior_surgery</title>
<path fill="none" stroke="#000000" d="M2604.113,-2470.7602C2615.2907,-2464.2762 2622,-2455.1895 2622,-2443.5 2622,-2435.0982 2618.534,-2428.041 2612.434,-2422.3283"/>
<polygon fill="#000000" stroke="#000000" points="2614.2501,-2419.3204 2604.113,-2416.2398 2610.1165,-2424.9696 2614.2501,-2419.3204"/>
<text text-anchor="middle" x="2638" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- prior_surgery&#45;&gt;enrollment -->
<g id="edge33" class="edge">
<title>prior_surgery&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M2395.9654,-2374.2777C2342.397,-2213.2976 2209.7196,-1814.5837 2153.1877,-1644.6975"/>
<polygon fill="#000000" stroke="#000000" points="2156.461,-1643.4492 2149.9826,-1635.0658 2149.8191,-1645.6594 2156.461,-1643.4492"/>
<text text-anchor="middle" x="2399" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge32" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1471,-236.3905C1471,-222.6101 1471,-208.6095 1471,-195.0235"/>
<polygon fill="#000000" stroke="#000000" points="1474.5001,-194.7254 1471,-184.7255 1467.5001,-194.7255 1474.5001,-194.7254"/>
<text text-anchor="middle" x="1511.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- enrollment&#45;&gt;case -->
<g id="edge4" class="edge">
<title>enrollment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2087.306,-1496.9333C2055.5193,-1447.797 2006.485,-1384.1483 1947,-1347 1895.9816,-1315.1391 1752.2366,-1283.8842 1639.2521,-1263.0701"/>
<polygon fill="#000000" stroke="#000000" points="1639.5763,-1259.5714 1629.1096,-1261.2143 1638.3163,-1266.4571 1639.5763,-1259.5714"/>
<text text-anchor="middle" x="1932" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- demographic -->
<g id="node19" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M2328,-1485.5C2328,-1485.5 2664,-1485.5 2664,-1485.5 2670,-1485.5 2676,-1491.5 2676,-1497.5 2676,-1497.5 2676,-1634.5 2676,-1634.5 2676,-1640.5 2670,-1646.5 2664,-1646.5 2664,-1646.5 2328,-1646.5 2328,-1646.5 2322,-1646.5 2316,-1640.5 2316,-1634.5 2316,-1634.5 2316,-1497.5 2316,-1497.5 2316,-1491.5 2322,-1485.5 2328,-1485.5"/>
<text text-anchor="middle" x="2371" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="2426,-1485.5 2426,-1646.5 "/>
<text text-anchor="middle" x="2436.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2447,-1485.5 2447,-1646.5 "/>
<text text-anchor="middle" x="2551" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2447,-1623.5 2655,-1623.5 "/>
<text text-anchor="middle" x="2551" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="2447,-1600.5 2655,-1600.5 "/>
<text text-anchor="middle" x="2551" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_birth</text>
<polyline fill="none" stroke="#000000" points="2447,-1577.5 2655,-1577.5 "/>
<text text-anchor="middle" x="2551" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status</text>
<polyline fill="none" stroke="#000000" points="2447,-1554.5 2655,-1554.5 "/>
<text text-anchor="middle" x="2551" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2447,-1531.5 2655,-1531.5 "/>
<text text-anchor="middle" x="2551" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="2447,-1508.5 2655,-1508.5 "/>
<text text-anchor="middle" x="2551" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="2655,-1485.5 2655,-1646.5 "/>
<text text-anchor="middle" x="2665.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;case -->
<g id="edge5" class="edge">
<title>demographic&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2448.1012,-1485.4571C2414.842,-1437.0725 2365.9785,-1378.8865 2307,-1347 2194.8371,-1286.3595 1843.1983,-1257.3507 1639.3189,-1245.3026"/>
<polygon fill="#000000" stroke="#000000" points="1639.3086,-1241.7961 1629.1215,-1244.7068 1638.9003,-1248.7842 1639.3086,-1241.7961"/>
<text text-anchor="middle" x="2287" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- variant -->
<g id="node20" class="node">
<title>variant</title>
<path fill="none" stroke="#000000" d="M115.5,-3007.5C115.5,-3007.5 440.5,-3007.5 440.5,-3007.5 446.5,-3007.5 452.5,-3013.5 452.5,-3019.5 452.5,-3019.5 452.5,-3662.5 452.5,-3662.5 452.5,-3668.5 446.5,-3674.5 440.5,-3674.5 440.5,-3674.5 115.5,-3674.5 115.5,-3674.5 109.5,-3674.5 103.5,-3668.5 103.5,-3662.5 103.5,-3662.5 103.5,-3019.5 103.5,-3019.5 103.5,-3013.5 109.5,-3007.5 115.5,-3007.5"/>
<text text-anchor="middle" x="137.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant</text>
<polyline fill="none" stroke="#000000" points="171.5,-3007.5 171.5,-3674.5 "/>
<text text-anchor="middle" x="182" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="192.5,-3007.5 192.5,-3674.5 "/>
<text text-anchor="middle" x="312" y="-3659.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_95percent</text>
<polyline fill="none" stroke="#000000" points="192.5,-3651.5 431.5,-3651.5 "/>
<text text-anchor="middle" x="312" y="-3636.3" font-family="Times,serif" font-size="14.00" fill="#000000">aMOI</text>
<polyline fill="none" stroke="#000000" points="192.5,-3628.5 431.5,-3628.5 "/>
<text text-anchor="middle" x="312" y="-3613.3" font-family="Times,serif" font-size="14.00" fill="#000000">allele_frequency</text>
<polyline fill="none" stroke="#000000" points="192.5,-3605.5 431.5,-3605.5 "/>
<text text-anchor="middle" x="312" y="-3590.3" font-family="Times,serif" font-size="14.00" fill="#000000">protein</text>
<polyline fill="none" stroke="#000000" points="192.5,-3582.5 431.5,-3582.5 "/>
<text text-anchor="middle" x="312" y="-3567.3" font-family="Times,serif" font-size="14.00" fill="#000000">transcript</text>
<polyline fill="none" stroke="#000000" points="192.5,-3559.5 431.5,-3559.5 "/>
<text text-anchor="middle" x="312" y="-3544.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_alt</text>
<polyline fill="none" stroke="#000000" points="192.5,-3536.5 431.5,-3536.5 "/>
<text text-anchor="middle" x="312" y="-3521.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="192.5,-3513.5 431.5,-3513.5 "/>
<text text-anchor="middle" x="312" y="-3498.3" font-family="Times,serif" font-size="14.00" fill="#000000">strand</text>
<polyline fill="none" stroke="#000000" points="192.5,-3490.5 431.5,-3490.5 "/>
<text text-anchor="middle" x="312" y="-3475.3" font-family="Times,serif" font-size="14.00" fill="#000000">ref_copy_number</text>
<polyline fill="none" stroke="#000000" points="192.5,-3467.5 431.5,-3467.5 "/>
<text text-anchor="middle" x="312" y="-3452.3" font-family="Times,serif" font-size="14.00" fill="#000000">raw_copy_number</text>
<polyline fill="none" stroke="#000000" points="192.5,-3444.5 431.5,-3444.5 "/>
<text text-anchor="middle" x="312" y="-3429.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_alt</text>
<polyline fill="none" stroke="#000000" points="192.5,-3421.5 431.5,-3421.5 "/>
<text text-anchor="middle" x="312" y="-3406.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs</text>
<polyline fill="none" stroke="#000000" points="192.5,-3398.5 431.5,-3398.5 "/>
<text text-anchor="middle" x="312" y="-3383.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm_specific</text>
<polyline fill="none" stroke="#000000" points="192.5,-3375.5 431.5,-3375.5 "/>
<text text-anchor="middle" x="312" y="-3360.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="192.5,-3352.5 431.5,-3352.5 "/>
<text text-anchor="middle" x="312" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">read_depth</text>
<polyline fill="none" stroke="#000000" points="192.5,-3329.5 431.5,-3329.5 "/>
<text text-anchor="middle" x="312" y="-3314.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_ref</text>
<polyline fill="none" stroke="#000000" points="192.5,-3306.5 431.5,-3306.5 "/>
<text text-anchor="middle" x="312" y="-3291.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="192.5,-3283.5 431.5,-3283.5 "/>
<text text-anchor="middle" x="312" y="-3268.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternative_allele</text>
<polyline fill="none" stroke="#000000" points="192.5,-3260.5 431.5,-3260.5 "/>
<text text-anchor="middle" x="312" y="-3245.3" font-family="Times,serif" font-size="14.00" fill="#000000">genome_reference</text>
<polyline fill="none" stroke="#000000" points="192.5,-3237.5 431.5,-3237.5 "/>
<text text-anchor="middle" x="312" y="-3222.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_name</text>
<polyline fill="none" stroke="#000000" points="192.5,-3214.5 431.5,-3214.5 "/>
<text text-anchor="middle" x="312" y="-3199.3" font-family="Times,serif" font-size="14.00" fill="#000000">function</text>
<polyline fill="none" stroke="#000000" points="192.5,-3191.5 431.5,-3191.5 "/>
<text text-anchor="middle" x="312" y="-3176.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_type</text>
<polyline fill="none" stroke="#000000" points="192.5,-3168.5 431.5,-3168.5 "/>
<text text-anchor="middle" x="312" y="-3153.3" font-family="Times,serif" font-size="14.00" fill="#000000">confirmed</text>
<polyline fill="none" stroke="#000000" points="192.5,-3145.5 431.5,-3145.5 "/>
<text text-anchor="middle" x="312" y="-3130.3" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="192.5,-3122.5 431.5,-3122.5 "/>
<text text-anchor="middle" x="312" y="-3107.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_05percent</text>
<polyline fill="none" stroke="#000000" points="192.5,-3099.5 431.5,-3099.5 "/>
<text text-anchor="middle" x="312" y="-3084.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="192.5,-3076.5 431.5,-3076.5 "/>
<text text-anchor="middle" x="312" y="-3061.3" font-family="Times,serif" font-size="14.00" fill="#000000">position</text>
<polyline fill="none" stroke="#000000" points="192.5,-3053.5 431.5,-3053.5 "/>
<text text-anchor="middle" x="312" y="-3038.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_ref</text>
<polyline fill="none" stroke="#000000" points="192.5,-3030.5 431.5,-3030.5 "/>
<text text-anchor="middle" x="312" y="-3015.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id_analysis_id</text>
<polyline fill="none" stroke="#000000" points="431.5,-3007.5 431.5,-3674.5 "/>
<text text-anchor="middle" x="442" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- variant&#45;&gt;genomic_report -->
<g id="edge18" class="edge">
<title>variant&#45;&gt;genomic_report</title>
<path fill="none" stroke="#000000" d="M278,-3007.2357C278,-2993.0591 278,-2979.1882 278,-2965.8076"/>
<polygon fill="#000000" stroke="#000000" points="281.5001,-2965.674 278,-2955.674 274.5001,-2965.6741 281.5001,-2965.674"/>
<text text-anchor="middle" x="311.5" y="-2977.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_report</text>
</g>
<!-- file -->
<g id="node21" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M508.5,-2714C508.5,-2714 693.5,-2714 693.5,-2714 699.5,-2714 705.5,-2720 705.5,-2726 705.5,-2726 705.5,-2909 705.5,-2909 705.5,-2915 699.5,-2921 693.5,-2921 693.5,-2921 508.5,-2921 508.5,-2921 502.5,-2921 496.5,-2915 496.5,-2909 496.5,-2909 496.5,-2726 496.5,-2726 496.5,-2720 502.5,-2714 508.5,-2714"/>
<text text-anchor="middle" x="516" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="535.5,-2714 535.5,-2921 "/>
<text text-anchor="middle" x="546" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="556.5,-2714 556.5,-2921 "/>
<text text-anchor="middle" x="620.5" y="-2905.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="556.5,-2898 684.5,-2898 "/>
<text text-anchor="middle" x="620.5" y="-2882.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="556.5,-2875 684.5,-2875 "/>
<text text-anchor="middle" x="620.5" y="-2859.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="556.5,-2852 684.5,-2852 "/>
<text text-anchor="middle" x="620.5" y="-2836.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="556.5,-2829 684.5,-2829 "/>
<text text-anchor="middle" x="620.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="556.5,-2806 684.5,-2806 "/>
<text text-anchor="middle" x="620.5" y="-2790.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_locations</text>
<polyline fill="none" stroke="#000000" points="556.5,-2783 684.5,-2783 "/>
<text text-anchor="middle" x="620.5" y="-2767.8" font-family="Times,serif" font-size="14.00" fill="#000000">uuid</text>
<polyline fill="none" stroke="#000000" points="556.5,-2760 684.5,-2760 "/>
<text text-anchor="middle" x="620.5" y="-2744.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_status</text>
<polyline fill="none" stroke="#000000" points="556.5,-2737 684.5,-2737 "/>
<text text-anchor="middle" x="620.5" y="-2721.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_format</text>
<polyline fill="none" stroke="#000000" points="684.5,-2714 684.5,-2921 "/>
<text text-anchor="middle" x="695" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;diagnosis -->
<g id="edge13" class="edge">
<title>file&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M629.9087,-2713.9103C662.5124,-2597.0806 716.5391,-2403.4848 759.1657,-2250.7397"/>
<polygon fill="#000000" stroke="#000000" points="762.6397,-2251.3118 761.9566,-2240.739 755.8973,-2249.4301 762.6397,-2251.3118"/>
<text text-anchor="middle" x="700.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_diagnosis</text>
</g>
<!-- file&#45;&gt;assay -->
<g id="edge15" class="edge">
<title>file&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M518.0291,-2713.801C507.7918,-2701.8778 497.3017,-2690.046 487,-2679 479.0664,-2670.4932 476.0576,-2669.3895 468,-2661 404.0189,-2594.3829 333.7321,-2511.0136 299.3463,-2469.4983"/>
<polygon fill="#000000" stroke="#000000" points="302.0285,-2467.2497 292.9603,-2461.7707 296.6325,-2471.7088 302.0285,-2467.2497"/>
<text text-anchor="middle" x="498.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge2" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M578.6119,-2713.8578C538.183,-2529.5165 448.4707,-2133.0005 355,-1803 354.1986,-1800.1708 353.3855,-1797.3247 352.5619,-1794.4647"/>
<polygon fill="#000000" stroke="#000000" points="355.8735,-1793.3178 349.7227,-1784.6912 349.1514,-1795.2706 355.8735,-1793.3178"/>
<text text-anchor="middle" x="595.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- image -->
<g id="node22" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M12,-2799.5C12,-2799.5 48,-2799.5 48,-2799.5 54,-2799.5 60,-2805.5 60,-2811.5 60,-2811.5 60,-2823.5 60,-2823.5 60,-2829.5 54,-2835.5 48,-2835.5 48,-2835.5 12,-2835.5 12,-2835.5 6,-2835.5 0,-2829.5 0,-2823.5 0,-2823.5 0,-2811.5 0,-2811.5 0,-2805.5 6,-2799.5 12,-2799.5"/>
<text text-anchor="middle" x="30" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
</g>
<!-- image&#45;&gt;assay -->
<g id="edge16" class="edge">
<title>image&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M32.4268,-2799.473C36.6831,-2772.0666 47.1967,-2718.8948 69,-2679 117.1011,-2590.9863 203.6153,-2508.1596 248.769,-2468.2976"/>
<polygon fill="#000000" stroke="#000000" points="251.2148,-2470.8083 256.4377,-2461.5903 246.6063,-2465.5393 251.2148,-2470.8083"/>
<text text-anchor="middle" x="117.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- survival -->
<g id="node23" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M2706.5,-1416.5C2706.5,-1416.5 3031.5,-1416.5 3031.5,-1416.5 3037.5,-1416.5 3043.5,-1422.5 3043.5,-1428.5 3043.5,-1428.5 3043.5,-1703.5 3043.5,-1703.5 3043.5,-1709.5 3037.5,-1715.5 3031.5,-1715.5 3031.5,-1715.5 2706.5,-1715.5 2706.5,-1715.5 2700.5,-1715.5 2694.5,-1709.5 2694.5,-1703.5 2694.5,-1703.5 2694.5,-1428.5 2694.5,-1428.5 2694.5,-1422.5 2700.5,-1416.5 2706.5,-1416.5"/>
<text text-anchor="middle" x="2731.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="2768.5,-1416.5 2768.5,-1715.5 "/>
<text text-anchor="middle" x="2779" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2789.5,-1416.5 2789.5,-1715.5 "/>
<text text-anchor="middle" x="2906" y="-1700.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_free_interval</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1692.5 3022.5,-1692.5 "/>
<text text-anchor="middle" x="2906" y="-1677.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_status</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1669.5 3022.5,-1669.5 "/>
<text text-anchor="middle" x="2906" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1646.5 3022.5,-1646.5 "/>
<text text-anchor="middle" x="2906" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_event_indicator</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1623.5 3022.5,-1623.5 "/>
<text text-anchor="middle" x="2906" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1600.5 3022.5,-1600.5 "/>
<text text-anchor="middle" x="2906" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_recurrence</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1577.5 3022.5,-1577.5 "/>
<text text-anchor="middle" x="2906" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_withdrawn</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1554.5 3022.5,-1554.5 "/>
<text text-anchor="middle" x="2906" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">lost_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1531.5 3022.5,-1531.5 "/>
<text text-anchor="middle" x="2906" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_survival</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1508.5 3022.5,-1508.5 "/>
<text text-anchor="middle" x="2906" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1485.5 3022.5,-1485.5 "/>
<text text-anchor="middle" x="2906" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_interval</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1462.5 3022.5,-1462.5 "/>
<text text-anchor="middle" x="2906" y="-1447.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_survival_interval</text>
<polyline fill="none" stroke="#000000" points="2789.5,-1439.5 3022.5,-1439.5 "/>
<text text-anchor="middle" x="2906" y="-1424.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_dfs_event</text>
<polyline fill="none" stroke="#000000" points="3022.5,-1416.5 3022.5,-1715.5 "/>
<text text-anchor="middle" x="3033" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;case -->
<g id="edge3" class="edge">
<title>survival&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2770.8619,-1416.2812C2746.0949,-1388.9793 2717.2402,-1363.8444 2685,-1347 2594.3242,-1299.6251 1939.676,-1260.8228 1639.1306,-1245.2952"/>
<polygon fill="#000000" stroke="#000000" points="1639.1949,-1241.794 1629.0281,-1244.7752 1638.835,-1248.7847 1639.1949,-1241.794"/>
<text text-anchor="middle" x="2649" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- agent_administration -->
<g id="node24" class="node">
<title>agent_administration</title>
<path fill="none" stroke="#000000" d="M561.5,-737.5C561.5,-737.5 1030.5,-737.5 1030.5,-737.5 1036.5,-737.5 1042.5,-743.5 1042.5,-749.5 1042.5,-749.5 1042.5,-1116.5 1042.5,-1116.5 1042.5,-1122.5 1036.5,-1128.5 1030.5,-1128.5 1030.5,-1128.5 561.5,-1128.5 561.5,-1128.5 555.5,-1128.5 549.5,-1122.5 549.5,-1116.5 549.5,-1116.5 549.5,-749.5 549.5,-749.5 549.5,-743.5 555.5,-737.5 561.5,-737.5"/>
<text text-anchor="middle" x="634.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_administration</text>
<polyline fill="none" stroke="#000000" points="719.5,-737.5 719.5,-1128.5 "/>
<text text-anchor="middle" x="730" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="740.5,-737.5 740.5,-1128.5 "/>
<text text-anchor="middle" x="881" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="740.5,-1105.5 1021.5,-1105.5 "/>
<text text-anchor="middle" x="881" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_missed_dose</text>
<polyline fill="none" stroke="#000000" points="740.5,-1082.5 1021.5,-1082.5 "/>
<text text-anchor="middle" x="881" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="740.5,-1059.5 1021.5,-1059.5 "/>
<text text-anchor="middle" x="881" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">route_of_administration</text>
<polyline fill="none" stroke="#000000" points="740.5,-1036.5 1021.5,-1036.5 "/>
<text text-anchor="middle" x="881" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_missed_dose</text>
<polyline fill="none" stroke="#000000" points="740.5,-1013.5 1021.5,-1013.5 "/>
<text text-anchor="middle" x="881" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_course_number</text>
<polyline fill="none" stroke="#000000" points="740.5,-990.5 1021.5,-990.5 "/>
<text text-anchor="middle" x="881" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="740.5,-967.5 1021.5,-967.5 "/>
<text text-anchor="middle" x="881" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_level</text>
<polyline fill="none" stroke="#000000" points="740.5,-944.5 1021.5,-944.5 "/>
<text text-anchor="middle" x="881" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_vial_id</text>
<polyline fill="none" stroke="#000000" points="740.5,-921.5 1021.5,-921.5 "/>
<text text-anchor="middle" x="881" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_amount</text>
<polyline fill="none" stroke="#000000" points="740.5,-898.5 1021.5,-898.5 "/>
<text text-anchor="middle" x="881" y="-883.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_lot_number</text>
<polyline fill="none" stroke="#000000" points="740.5,-875.5 1021.5,-875.5 "/>
<text text-anchor="middle" x="881" y="-860.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="740.5,-852.5 1021.5,-852.5 "/>
<text text-anchor="middle" x="881" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">stop_time</text>
<polyline fill="none" stroke="#000000" points="740.5,-829.5 1021.5,-829.5 "/>
<text text-anchor="middle" x="881" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_duration</text>
<polyline fill="none" stroke="#000000" points="740.5,-806.5 1021.5,-806.5 "/>
<text text-anchor="middle" x="881" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_dose</text>
<polyline fill="none" stroke="#000000" points="740.5,-783.5 1021.5,-783.5 "/>
<text text-anchor="middle" x="881" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_time</text>
<polyline fill="none" stroke="#000000" points="740.5,-760.5 1021.5,-760.5 "/>
<text text-anchor="middle" x="881" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="1021.5,-737.5 1021.5,-1128.5 "/>
<text text-anchor="middle" x="1032" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- agent_administration&#45;&gt;agent -->
<g id="edge12" class="edge">
<title>agent_administration&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M1042.5181,-741.6599C1045.3461,-740.0776 1048.1739,-738.5236 1051,-737 1093.4932,-714.0917 1144.4094,-696.078 1186.0242,-683.5061"/>
<polygon fill="#000000" stroke="#000000" points="1187.2558,-686.7914 1195.8443,-680.5876 1185.2616,-680.0815 1187.2558,-686.7914"/>
<text text-anchor="middle" x="1157" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- evaluation -->
<g id="node25" class="node">
<title>evaluation</title>
<path fill="none" stroke="#000000" d="M750,-3323C750,-3323 1010,-3323 1010,-3323 1016,-3323 1022,-3329 1022,-3335 1022,-3335 1022,-3347 1022,-3347 1022,-3353 1016,-3359 1010,-3359 1010,-3359 750,-3359 750,-3359 744,-3359 738,-3353 738,-3347 738,-3347 738,-3335 738,-3335 738,-3329 744,-3323 750,-3323"/>
<text text-anchor="middle" x="783.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">evaluation</text>
<polyline fill="none" stroke="#000000" points="829,-3323 829,-3359 "/>
<text text-anchor="middle" x="839.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="850,-3323 850,-3359 "/>
<text text-anchor="middle" x="925.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_evaluation</text>
<polyline fill="none" stroke="#000000" points="1001,-3323 1001,-3359 "/>
<text text-anchor="middle" x="1011.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
</g>
</svg>
</div>
