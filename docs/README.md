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
<svg width="2996pt" height="3683pt"
 viewBox="0.00 0.00 2996.00 3683.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 3679)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-3679 2992,-3679 2992,4 -4,4"/>
<!-- file -->
<g id="node1" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M709,-2714C709,-2714 894,-2714 894,-2714 900,-2714 906,-2720 906,-2726 906,-2726 906,-2909 906,-2909 906,-2915 900,-2921 894,-2921 894,-2921 709,-2921 709,-2921 703,-2921 697,-2915 697,-2909 697,-2909 697,-2726 697,-2726 697,-2720 703,-2714 709,-2714"/>
<text text-anchor="middle" x="716.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="736,-2714 736,-2921 "/>
<text text-anchor="middle" x="746.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="757,-2714 757,-2921 "/>
<text text-anchor="middle" x="821" y="-2905.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="757,-2898 885,-2898 "/>
<text text-anchor="middle" x="821" y="-2882.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_format</text>
<polyline fill="none" stroke="#000000" points="757,-2875 885,-2875 "/>
<text text-anchor="middle" x="821" y="-2859.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_status</text>
<polyline fill="none" stroke="#000000" points="757,-2852 885,-2852 "/>
<text text-anchor="middle" x="821" y="-2836.8" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="757,-2829 885,-2829 "/>
<text text-anchor="middle" x="821" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="757,-2806 885,-2806 "/>
<text text-anchor="middle" x="821" y="-2790.8" font-family="Times,serif" font-size="14.00" fill="#000000">uuid</text>
<polyline fill="none" stroke="#000000" points="757,-2783 885,-2783 "/>
<text text-anchor="middle" x="821" y="-2767.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="757,-2760 885,-2760 "/>
<text text-anchor="middle" x="821" y="-2744.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="757,-2737 885,-2737 "/>
<text text-anchor="middle" x="821" y="-2721.8" font-family="Times,serif" font-size="14.00" fill="#000000">file_locations</text>
<polyline fill="none" stroke="#000000" points="885,-2714 885,-2921 "/>
<text text-anchor="middle" x="895.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- sample -->
<g id="node6" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M479,-1347.5C479,-1347.5 902,-1347.5 902,-1347.5 908,-1347.5 914,-1353.5 914,-1359.5 914,-1359.5 914,-1772.5 914,-1772.5 914,-1778.5 908,-1784.5 902,-1784.5 902,-1784.5 479,-1784.5 479,-1784.5 473,-1784.5 467,-1778.5 467,-1772.5 467,-1772.5 467,-1359.5 467,-1359.5 467,-1353.5 473,-1347.5 479,-1347.5"/>
<text text-anchor="middle" x="501" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="535,-1347.5 535,-1784.5 "/>
<text text-anchor="middle" x="545.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="556,-1347.5 556,-1784.5 "/>
<text text-anchor="middle" x="724.5" y="-1769.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="556,-1761.5 893,-1761.5 "/>
<text text-anchor="middle" x="724.5" y="-1746.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_tumor</text>
<polyline fill="none" stroke="#000000" points="556,-1738.5 893,-1738.5 "/>
<text text-anchor="middle" x="724.5" y="-1723.3" font-family="Times,serif" font-size="14.00" fill="#000000">general_sample_pathology</text>
<polyline fill="none" stroke="#000000" points="556,-1715.5 893,-1715.5 "/>
<text text-anchor="middle" x="724.5" y="-1700.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_pigmented_tumor</text>
<polyline fill="none" stroke="#000000" points="556,-1692.5 893,-1692.5 "/>
<text text-anchor="middle" x="724.5" y="-1677.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="556,-1669.5 893,-1669.5 "/>
<text text-anchor="middle" x="724.5" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="556,-1646.5 893,-1646.5 "/>
<text text-anchor="middle" x="724.5" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="556,-1623.5 893,-1623.5 "/>
<text text-anchor="middle" x="724.5" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="556,-1600.5 893,-1600.5 "/>
<text text-anchor="middle" x="724.5" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="556,-1577.5 893,-1577.5 "/>
<text text-anchor="middle" x="724.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="556,-1554.5 893,-1554.5 "/>
<text text-anchor="middle" x="724.5" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">necropsy_sample</text>
<polyline fill="none" stroke="#000000" points="556,-1531.5 893,-1531.5 "/>
<text text-anchor="middle" x="724.5" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="556,-1508.5 893,-1508.5 "/>
<text text-anchor="middle" x="724.5" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area</text>
<polyline fill="none" stroke="#000000" points="556,-1485.5 893,-1485.5 "/>
<text text-anchor="middle" x="724.5" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_tissue_area</text>
<polyline fill="none" stroke="#000000" points="556,-1462.5 893,-1462.5 "/>
<text text-anchor="middle" x="724.5" y="-1447.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_status_date</text>
<polyline fill="none" stroke="#000000" points="556,-1439.5 893,-1439.5 "/>
<text text-anchor="middle" x="724.5" y="-1424.3" font-family="Times,serif" font-size="14.00" fill="#000000">width_of_tumor</text>
<polyline fill="none" stroke="#000000" points="556,-1416.5 893,-1416.5 "/>
<text text-anchor="middle" x="724.5" y="-1401.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_sample_collection</text>
<polyline fill="none" stroke="#000000" points="556,-1393.5 893,-1393.5 "/>
<text text-anchor="middle" x="724.5" y="-1378.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_glass</text>
<polyline fill="none" stroke="#000000" points="556,-1370.5 893,-1370.5 "/>
<text text-anchor="middle" x="724.5" y="-1355.3" font-family="Times,serif" font-size="14.00" fill="#000000">non_tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="893,-1347.5 893,-1784.5 "/>
<text text-anchor="middle" x="903.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge6" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M800.3861,-2713.9196C797.4792,-2491.8065 787.8139,-1975.8743 759.5,-1803 759.0528,-1800.2693 758.5842,-1797.5255 758.0956,-1794.7712"/>
<polygon fill="#000000" stroke="#000000" points="761.5035,-1793.9521 756.2418,-1784.7562 754.6205,-1795.2262 761.5035,-1793.9521"/>
<text text-anchor="middle" x="835" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- assay -->
<g id="node15" class="node">
<title>assay</title>
<path fill="none" stroke="#000000" d="M649.5,-2425.5C649.5,-2425.5 681.5,-2425.5 681.5,-2425.5 687.5,-2425.5 693.5,-2431.5 693.5,-2437.5 693.5,-2437.5 693.5,-2449.5 693.5,-2449.5 693.5,-2455.5 687.5,-2461.5 681.5,-2461.5 681.5,-2461.5 649.5,-2461.5 649.5,-2461.5 643.5,-2461.5 637.5,-2455.5 637.5,-2449.5 637.5,-2449.5 637.5,-2437.5 637.5,-2437.5 637.5,-2431.5 643.5,-2425.5 649.5,-2425.5"/>
<text text-anchor="middle" x="665.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">assay</text>
</g>
<!-- file&#45;&gt;assay -->
<g id="edge17" class="edge">
<title>file&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M748.7144,-2713.7855C740.7514,-2696.3814 733.0303,-2678.3405 726.5,-2661 701.4628,-2594.5165 681.3153,-2513.2167 671.6739,-2471.3582"/>
<polygon fill="#000000" stroke="#000000" points="675.0848,-2470.5728 669.4525,-2461.599 668.2593,-2472.1264 675.0848,-2470.5728"/>
<text text-anchor="middle" x="757" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- diagnosis -->
<g id="node17" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M829,-1803.5C829,-1803.5 1172,-1803.5 1172,-1803.5 1178,-1803.5 1184,-1809.5 1184,-1815.5 1184,-1815.5 1184,-2228.5 1184,-2228.5 1184,-2234.5 1178,-2240.5 1172,-2240.5 1172,-2240.5 829,-2240.5 829,-2240.5 823,-2240.5 817,-2234.5 817,-2228.5 817,-2228.5 817,-1815.5 817,-1815.5 817,-1809.5 823,-1803.5 829,-1803.5"/>
<text text-anchor="middle" x="859" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="901,-1803.5 901,-2240.5 "/>
<text text-anchor="middle" x="911.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="922,-1803.5 922,-2240.5 "/>
<text text-anchor="middle" x="1042.5" y="-2225.3" font-family="Times,serif" font-size="14.00" fill="#000000">stage_of_disease</text>
<polyline fill="none" stroke="#000000" points="922,-2217.5 1163,-2217.5 "/>
<text text-anchor="middle" x="1042.5" y="-2202.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease_type</text>
<polyline fill="none" stroke="#000000" points="922,-2194.5 1163,-2194.5 "/>
<text text-anchor="middle" x="1042.5" y="-2179.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="922,-2171.5 1163,-2171.5 "/>
<text text-anchor="middle" x="1042.5" y="-2156.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease</text>
<polyline fill="none" stroke="#000000" points="922,-2148.5 1163,-2148.5 "/>
<text text-anchor="middle" x="1042.5" y="-2133.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_histology_confirmation</text>
<polyline fill="none" stroke="#000000" points="922,-2125.5 1163,-2125.5 "/>
<text text-anchor="middle" x="1042.5" y="-2110.3" font-family="Times,serif" font-size="14.00" fill="#000000">progesterone_receptor_status</text>
<polyline fill="none" stroke="#000000" points="922,-2102.5 1163,-2102.5 "/>
<text text-anchor="middle" x="1042.5" y="-2087.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_code</text>
<polyline fill="none" stroke="#000000" points="922,-2079.5 1163,-2079.5 "/>
<text text-anchor="middle" x="1042.5" y="-2064.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size</text>
<polyline fill="none" stroke="#000000" points="922,-2056.5 1163,-2056.5 "/>
<text text-anchor="middle" x="1042.5" y="-2041.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_data</text>
<polyline fill="none" stroke="#000000" points="922,-2033.5 1163,-2033.5 "/>
<text text-anchor="middle" x="1042.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">nuclear_grade</text>
<polyline fill="none" stroke="#000000" points="922,-2010.5 1163,-2010.5 "/>
<text text-anchor="middle" x="1042.5" y="-1995.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_report</text>
<polyline fill="none" stroke="#000000" points="922,-1987.5 1163,-1987.5 "/>
<text text-anchor="middle" x="1042.5" y="-1972.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_score</text>
<polyline fill="none" stroke="#000000" points="922,-1964.5 1163,-1964.5 "/>
<text text-anchor="middle" x="1042.5" y="-1949.3" font-family="Times,serif" font-size="14.00" fill="#000000">histology_cytopathology</text>
<polyline fill="none" stroke="#000000" points="922,-1941.5 1163,-1941.5 "/>
<text text-anchor="middle" x="1042.5" y="-1926.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_disease_site</text>
<polyline fill="none" stroke="#000000" points="922,-1918.5 1163,-1918.5 "/>
<text text-anchor="middle" x="1042.5" y="-1903.3" font-family="Times,serif" font-size="14.00" fill="#000000">estrogen_receptor_status</text>
<polyline fill="none" stroke="#000000" points="922,-1895.5 1163,-1895.5 "/>
<text text-anchor="middle" x="1042.5" y="-1880.3" font-family="Times,serif" font-size="14.00" fill="#000000">histological_grade</text>
<polyline fill="none" stroke="#000000" points="922,-1872.5 1163,-1872.5 "/>
<text text-anchor="middle" x="1042.5" y="-1857.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_group</text>
<polyline fill="none" stroke="#000000" points="922,-1849.5 1163,-1849.5 "/>
<text text-anchor="middle" x="1042.5" y="-1834.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_term</text>
<polyline fill="none" stroke="#000000" points="922,-1826.5 1163,-1826.5 "/>
<text text-anchor="middle" x="1042.5" y="-1811.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_data</text>
<polyline fill="none" stroke="#000000" points="1163,-1803.5 1163,-2240.5 "/>
<text text-anchor="middle" x="1173.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;diagnosis -->
<g id="edge4" class="edge">
<title>file&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M847.8298,-2713.5111C858.9264,-2686.0667 870.0065,-2656.2243 878.5,-2628 915.4236,-2505.3014 944.4429,-2365.2376 964.8993,-2250.6954"/>
<polygon fill="#000000" stroke="#000000" points="968.3636,-2251.2042 966.6661,-2240.7463 961.4714,-2249.9802 968.3636,-2251.2042"/>
<text text-anchor="middle" x="927" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_diagnosis</text>
</g>
<!-- study_arm -->
<g id="node2" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M974,-518.5C974,-518.5 1343,-518.5 1343,-518.5 1349,-518.5 1355,-524.5 1355,-530.5 1355,-530.5 1355,-575.5 1355,-575.5 1355,-581.5 1349,-587.5 1343,-587.5 1343,-587.5 974,-587.5 974,-587.5 968,-587.5 962,-581.5 962,-575.5 962,-575.5 962,-530.5 962,-530.5 962,-524.5 968,-518.5 974,-518.5"/>
<text text-anchor="middle" x="1008" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1054,-518.5 1054,-587.5 "/>
<text text-anchor="middle" x="1064.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1075,-518.5 1075,-587.5 "/>
<text text-anchor="middle" x="1204.5" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm</text>
<polyline fill="none" stroke="#000000" points="1075,-564.5 1334,-564.5 "/>
<text text-anchor="middle" x="1204.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_arm_version</text>
<polyline fill="none" stroke="#000000" points="1075,-541.5 1334,-541.5 "/>
<text text-anchor="middle" x="1204.5" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_treatment_assignment_code</text>
<polyline fill="none" stroke="#000000" points="1334,-518.5 1334,-587.5 "/>
<text text-anchor="middle" x="1344.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node8" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1200.5,-236.5C1200.5,-236.5 1480.5,-236.5 1480.5,-236.5 1486.5,-236.5 1492.5,-242.5 1492.5,-248.5 1492.5,-248.5 1492.5,-454.5 1492.5,-454.5 1492.5,-460.5 1486.5,-466.5 1480.5,-466.5 1480.5,-466.5 1200.5,-466.5 1200.5,-466.5 1194.5,-466.5 1188.5,-460.5 1188.5,-454.5 1188.5,-454.5 1188.5,-248.5 1188.5,-248.5 1188.5,-242.5 1194.5,-236.5 1200.5,-236.5"/>
<text text-anchor="middle" x="1216.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1244.5,-236.5 1244.5,-466.5 "/>
<text text-anchor="middle" x="1255" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1265.5,-236.5 1265.5,-466.5 "/>
<text text-anchor="middle" x="1368.5" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_name</text>
<polyline fill="none" stroke="#000000" points="1265.5,-443.5 1471.5,-443.5 "/>
<text text-anchor="middle" x="1368.5" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_term</text>
<polyline fill="none" stroke="#000000" points="1265.5,-420.5 1471.5,-420.5 "/>
<text text-anchor="middle" x="1368.5" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_iacuc_approval</text>
<polyline fill="none" stroke="#000000" points="1265.5,-397.5 1471.5,-397.5 "/>
<text text-anchor="middle" x="1368.5" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_type</text>
<polyline fill="none" stroke="#000000" points="1265.5,-374.5 1471.5,-374.5 "/>
<text text-anchor="middle" x="1368.5" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_su_category</text>
<polyline fill="none" stroke="#000000" points="1265.5,-351.5 1471.5,-351.5 "/>
<text text-anchor="middle" x="1368.5" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_category</text>
<polyline fill="none" stroke="#000000" points="1265.5,-328.5 1471.5,-328.5 "/>
<text text-anchor="middle" x="1368.5" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_description</text>
<polyline fill="none" stroke="#000000" points="1265.5,-305.5 1471.5,-305.5 "/>
<text text-anchor="middle" x="1368.5" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_id</text>
<polyline fill="none" stroke="#000000" points="1265.5,-282.5 1471.5,-282.5 "/>
<text text-anchor="middle" x="1368.5" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_designation</text>
<polyline fill="none" stroke="#000000" points="1265.5,-259.5 1471.5,-259.5 "/>
<text text-anchor="middle" x="1368.5" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">dates_of_conduct</text>
<polyline fill="none" stroke="#000000" points="1471.5,-236.5 1471.5,-466.5 "/>
<text text-anchor="middle" x="1482" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge1" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1234.3869,-518.3771C1242.6905,-512.8899 1250.6146,-506.7616 1257.5,-500 1265.2443,-492.3949 1272.4756,-483.9131 1279.1816,-474.9628"/>
<polygon fill="#000000" stroke="#000000" points="1282.1845,-476.7823 1285.1921,-466.6233 1276.5057,-472.6894 1282.1845,-476.7823"/>
<text text-anchor="middle" x="1300" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge11" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1160.9074,-518.4165C1162.8843,-507.135 1166.3771,-494.9601 1172.5,-485 1175.4265,-480.2395 1178.5868,-475.5785 1181.9435,-471.0217"/>
<polygon fill="#000000" stroke="#000000" points="1184.8479,-472.9871 1188.1896,-462.933 1179.3075,-468.7087 1184.8479,-472.9871"/>
<text text-anchor="middle" x="1213" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- prior_therapy -->
<g id="node3" class="node">
<title>prior_therapy</title>
<path fill="none" stroke="#000000" d="M1681.5,-2259.5C1681.5,-2259.5 2137.5,-2259.5 2137.5,-2259.5 2143.5,-2259.5 2149.5,-2265.5 2149.5,-2271.5 2149.5,-2271.5 2149.5,-2615.5 2149.5,-2615.5 2149.5,-2621.5 2143.5,-2627.5 2137.5,-2627.5 2137.5,-2627.5 1681.5,-2627.5 1681.5,-2627.5 1675.5,-2627.5 1669.5,-2621.5 1669.5,-2615.5 1669.5,-2615.5 1669.5,-2271.5 1669.5,-2271.5 1669.5,-2265.5 1675.5,-2259.5 1681.5,-2259.5"/>
<text text-anchor="middle" x="1727" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy</text>
<polyline fill="none" stroke="#000000" points="1784.5,-2259.5 1784.5,-2627.5 "/>
<text text-anchor="middle" x="1795" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1805.5,-2259.5 1805.5,-2627.5 "/>
<text text-anchor="middle" x="1967" y="-2612.3" font-family="Times,serif" font-size="14.00" fill="#000000">best_response</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2604.5 2128.5,-2604.5 "/>
<text text-anchor="middle" x="1967" y="-2589.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_dose</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2581.5 2128.5,-2581.5 "/>
<text text-anchor="middle" x="1967" y="-2566.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose_any_therapy</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2558.5 2128.5,-2558.5 "/>
<text text-anchor="middle" x="1967" y="-2543.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_in_minimal_residual</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2535.5 2128.5,-2535.5 "/>
<text text-anchor="middle" x="1967" y="-2520.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_name</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2512.5 2128.5,-2512.5 "/>
<text text-anchor="middle" x="1967" y="-2497.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_schedule</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2489.5 2128.5,-2489.5 "/>
<text text-anchor="middle" x="1967" y="-2474.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_number_of_doses_any_therapy</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2466.5 2128.5,-2466.5 "/>
<text text-anchor="middle" x="1967" y="-2451.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapy_type</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2443.5 2128.5,-2443.5 "/>
<text text-anchor="middle" x="1967" y="-2428.3" font-family="Times,serif" font-size="14.00" fill="#000000">any_therapy</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2420.5 2128.5,-2420.5 "/>
<text text-anchor="middle" x="1967" y="-2405.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2397.5 2128.5,-2397.5 "/>
<text text-anchor="middle" x="1967" y="-2382.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_at_site</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2374.5 2128.5,-2374.5 "/>
<text text-anchor="middle" x="1967" y="-2359.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_prior_regimens_any_therapy</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2351.5 2128.5,-2351.5 "/>
<text text-anchor="middle" x="1967" y="-2336.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2328.5 2128.5,-2328.5 "/>
<text text-anchor="middle" x="1967" y="-2313.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_first_dose</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2305.5 2128.5,-2305.5 "/>
<text text-anchor="middle" x="1967" y="-2290.3" font-family="Times,serif" font-size="14.00" fill="#000000">nonresponse_therapy_type</text>
<polyline fill="none" stroke="#000000" points="1805.5,-2282.5 2128.5,-2282.5 "/>
<text text-anchor="middle" x="1967" y="-2267.3" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy_type</text>
<polyline fill="none" stroke="#000000" points="2128.5,-2259.5 2128.5,-2627.5 "/>
<text text-anchor="middle" x="2139" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_therapy&#45;&gt;prior_therapy -->
<g id="edge33" class="edge">
<title>prior_therapy&#45;&gt;prior_therapy</title>
<path fill="none" stroke="#000000" d="M2149.7384,-2468.2536C2160.9387,-2462.0051 2167.5,-2453.7539 2167.5,-2443.5 2167.5,-2436.13 2164.1104,-2429.7946 2158.045,-2424.4938"/>
<polygon fill="#000000" stroke="#000000" points="2159.9534,-2421.5581 2149.7384,-2418.7464 2155.9704,-2427.3146 2159.9534,-2421.5581"/>
<text text-anchor="middle" x="2183.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- enrollment -->
<g id="node7" class="node">
<title>enrollment</title>
<path fill="none" stroke="#000000" d="M1458.5,-1497C1458.5,-1497 1776.5,-1497 1776.5,-1497 1782.5,-1497 1788.5,-1503 1788.5,-1509 1788.5,-1509 1788.5,-1623 1788.5,-1623 1788.5,-1629 1782.5,-1635 1776.5,-1635 1776.5,-1635 1458.5,-1635 1458.5,-1635 1452.5,-1635 1446.5,-1629 1446.5,-1623 1446.5,-1623 1446.5,-1509 1446.5,-1509 1446.5,-1503 1452.5,-1497 1458.5,-1497"/>
<text text-anchor="middle" x="1494" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrollment</text>
<polyline fill="none" stroke="#000000" points="1541.5,-1497 1541.5,-1635 "/>
<text text-anchor="middle" x="1552" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1562.5,-1497 1562.5,-1635 "/>
<text text-anchor="middle" x="1665" y="-1619.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_short_name</text>
<polyline fill="none" stroke="#000000" points="1562.5,-1612 1767.5,-1612 "/>
<text text-anchor="middle" x="1665" y="-1596.8" font-family="Times,serif" font-size="14.00" fill="#000000">patient_subgroup</text>
<polyline fill="none" stroke="#000000" points="1562.5,-1589 1767.5,-1589 "/>
<text text-anchor="middle" x="1665" y="-1573.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_informed_consent</text>
<polyline fill="none" stroke="#000000" points="1562.5,-1566 1767.5,-1566 "/>
<text text-anchor="middle" x="1665" y="-1550.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_registration</text>
<polyline fill="none" stroke="#000000" points="1562.5,-1543 1767.5,-1543 "/>
<text text-anchor="middle" x="1665" y="-1527.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1562.5,-1520 1767.5,-1520 "/>
<text text-anchor="middle" x="1665" y="-1504.8" font-family="Times,serif" font-size="14.00" fill="#000000">registering_institution</text>
<polyline fill="none" stroke="#000000" points="1767.5,-1497 1767.5,-1635 "/>
<text text-anchor="middle" x="1778" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_therapy&#45;&gt;enrollment -->
<g id="edge2" class="edge">
<title>prior_therapy&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M1848.1983,-2259.2799C1784.9871,-2069.3216 1689.3964,-1782.0584 1643.6686,-1644.6404"/>
<polygon fill="#000000" stroke="#000000" points="1646.942,-1643.3919 1640.4635,-1635.0086 1640.3001,-1645.6022 1646.942,-1643.3919"/>
<text text-anchor="middle" x="1888.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- variant -->
<g id="node4" class="node">
<title>variant</title>
<path fill="none" stroke="#000000" d="M231,-3007.5C231,-3007.5 556,-3007.5 556,-3007.5 562,-3007.5 568,-3013.5 568,-3019.5 568,-3019.5 568,-3662.5 568,-3662.5 568,-3668.5 562,-3674.5 556,-3674.5 556,-3674.5 231,-3674.5 231,-3674.5 225,-3674.5 219,-3668.5 219,-3662.5 219,-3662.5 219,-3019.5 219,-3019.5 219,-3013.5 225,-3007.5 231,-3007.5"/>
<text text-anchor="middle" x="253" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant</text>
<polyline fill="none" stroke="#000000" points="287,-3007.5 287,-3674.5 "/>
<text text-anchor="middle" x="297.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="308,-3007.5 308,-3674.5 "/>
<text text-anchor="middle" x="427.5" y="-3659.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_05percent</text>
<polyline fill="none" stroke="#000000" points="308,-3651.5 547,-3651.5 "/>
<text text-anchor="middle" x="427.5" y="-3636.3" font-family="Times,serif" font-size="14.00" fill="#000000">strand</text>
<polyline fill="none" stroke="#000000" points="308,-3628.5 547,-3628.5 "/>
<text text-anchor="middle" x="427.5" y="-3613.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_type</text>
<polyline fill="none" stroke="#000000" points="308,-3605.5 547,-3605.5 "/>
<text text-anchor="middle" x="427.5" y="-3590.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternative_allele</text>
<polyline fill="none" stroke="#000000" points="308,-3582.5 547,-3582.5 "/>
<text text-anchor="middle" x="427.5" y="-3567.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_alt</text>
<polyline fill="none" stroke="#000000" points="308,-3559.5 547,-3559.5 "/>
<text text-anchor="middle" x="427.5" y="-3544.3" font-family="Times,serif" font-size="14.00" fill="#000000">position</text>
<polyline fill="none" stroke="#000000" points="308,-3536.5 547,-3536.5 "/>
<text text-anchor="middle" x="427.5" y="-3521.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id_analysis_id</text>
<polyline fill="none" stroke="#000000" points="308,-3513.5 547,-3513.5 "/>
<text text-anchor="middle" x="427.5" y="-3498.3" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="308,-3490.5 547,-3490.5 "/>
<text text-anchor="middle" x="427.5" y="-3475.3" font-family="Times,serif" font-size="14.00" fill="#000000">allele_frequency</text>
<polyline fill="none" stroke="#000000" points="308,-3467.5 547,-3467.5 "/>
<text text-anchor="middle" x="427.5" y="-3452.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs</text>
<polyline fill="none" stroke="#000000" points="308,-3444.5 547,-3444.5 "/>
<text text-anchor="middle" x="427.5" y="-3429.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="308,-3421.5 547,-3421.5 "/>
<text text-anchor="middle" x="427.5" y="-3406.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="308,-3398.5 547,-3398.5 "/>
<text text-anchor="middle" x="427.5" y="-3383.3" font-family="Times,serif" font-size="14.00" fill="#000000">protein</text>
<polyline fill="none" stroke="#000000" points="308,-3375.5 547,-3375.5 "/>
<text text-anchor="middle" x="427.5" y="-3360.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_ref</text>
<polyline fill="none" stroke="#000000" points="308,-3352.5 547,-3352.5 "/>
<text text-anchor="middle" x="427.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">genome_reference</text>
<polyline fill="none" stroke="#000000" points="308,-3329.5 547,-3329.5 "/>
<text text-anchor="middle" x="427.5" y="-3314.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="308,-3306.5 547,-3306.5 "/>
<text text-anchor="middle" x="427.5" y="-3291.3" font-family="Times,serif" font-size="14.00" fill="#000000">confirmed</text>
<polyline fill="none" stroke="#000000" points="308,-3283.5 547,-3283.5 "/>
<text text-anchor="middle" x="427.5" y="-3268.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm_specific</text>
<polyline fill="none" stroke="#000000" points="308,-3260.5 547,-3260.5 "/>
<text text-anchor="middle" x="427.5" y="-3245.3" font-family="Times,serif" font-size="14.00" fill="#000000">function</text>
<polyline fill="none" stroke="#000000" points="308,-3237.5 547,-3237.5 "/>
<text text-anchor="middle" x="427.5" y="-3222.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_name</text>
<polyline fill="none" stroke="#000000" points="308,-3214.5 547,-3214.5 "/>
<text text-anchor="middle" x="427.5" y="-3199.3" font-family="Times,serif" font-size="14.00" fill="#000000">read_depth</text>
<polyline fill="none" stroke="#000000" points="308,-3191.5 547,-3191.5 "/>
<text text-anchor="middle" x="427.5" y="-3176.3" font-family="Times,serif" font-size="14.00" fill="#000000">transcript</text>
<polyline fill="none" stroke="#000000" points="308,-3168.5 547,-3168.5 "/>
<text text-anchor="middle" x="427.5" y="-3153.3" font-family="Times,serif" font-size="14.00" fill="#000000">raw_copy_number</text>
<polyline fill="none" stroke="#000000" points="308,-3145.5 547,-3145.5 "/>
<text text-anchor="middle" x="427.5" y="-3130.3" font-family="Times,serif" font-size="14.00" fill="#000000">ref_copy_number</text>
<polyline fill="none" stroke="#000000" points="308,-3122.5 547,-3122.5 "/>
<text text-anchor="middle" x="427.5" y="-3107.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_ref</text>
<polyline fill="none" stroke="#000000" points="308,-3099.5 547,-3099.5 "/>
<text text-anchor="middle" x="427.5" y="-3084.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_alt</text>
<polyline fill="none" stroke="#000000" points="308,-3076.5 547,-3076.5 "/>
<text text-anchor="middle" x="427.5" y="-3061.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="308,-3053.5 547,-3053.5 "/>
<text text-anchor="middle" x="427.5" y="-3038.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_95percent</text>
<polyline fill="none" stroke="#000000" points="308,-3030.5 547,-3030.5 "/>
<text text-anchor="middle" x="427.5" y="-3015.3" font-family="Times,serif" font-size="14.00" fill="#000000">aMOI</text>
<polyline fill="none" stroke="#000000" points="547,-3007.5 547,-3674.5 "/>
<text text-anchor="middle" x="557.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_report -->
<g id="node11" class="node">
<title>genomic_report</title>
<path fill="none" stroke="#000000" d="M205.5,-2679.5C205.5,-2679.5 581.5,-2679.5 581.5,-2679.5 587.5,-2679.5 593.5,-2685.5 593.5,-2691.5 593.5,-2691.5 593.5,-2943.5 593.5,-2943.5 593.5,-2949.5 587.5,-2955.5 581.5,-2955.5 581.5,-2955.5 205.5,-2955.5 205.5,-2955.5 199.5,-2955.5 193.5,-2949.5 193.5,-2943.5 193.5,-2943.5 193.5,-2691.5 193.5,-2691.5 193.5,-2685.5 199.5,-2679.5 205.5,-2679.5"/>
<text text-anchor="middle" x="258.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_report</text>
<polyline fill="none" stroke="#000000" points="323.5,-2679.5 323.5,-2955.5 "/>
<text text-anchor="middle" x="334" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="344.5,-2679.5 344.5,-2955.5 "/>
<text text-anchor="middle" x="458.5" y="-2940.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_type</text>
<polyline fill="none" stroke="#000000" points="344.5,-2932.5 572.5,-2932.5 "/>
<text text-anchor="middle" x="458.5" y="-2917.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id</text>
<polyline fill="none" stroke="#000000" points="344.5,-2909.5 572.5,-2909.5 "/>
<text text-anchor="middle" x="458.5" y="-2894.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_mois</text>
<polyline fill="none" stroke="#000000" points="344.5,-2886.5 572.5,-2886.5 "/>
<text text-anchor="middle" x="458.5" y="-2871.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_amois</text>
<polyline fill="none" stroke="#000000" points="344.5,-2863.5 572.5,-2863.5 "/>
<text text-anchor="middle" x="458.5" y="-2848.3" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="344.5,-2840.5 572.5,-2840.5 "/>
<text text-anchor="middle" x="458.5" y="-2825.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_amois</text>
<polyline fill="none" stroke="#000000" points="344.5,-2817.5 572.5,-2817.5 "/>
<text text-anchor="middle" x="458.5" y="-2802.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_mois</text>
<polyline fill="none" stroke="#000000" points="344.5,-2794.5 572.5,-2794.5 "/>
<text text-anchor="middle" x="458.5" y="-2779.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_received_date</text>
<polyline fill="none" stroke="#000000" points="344.5,-2771.5 572.5,-2771.5 "/>
<text text-anchor="middle" x="458.5" y="-2756.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="344.5,-2748.5 572.5,-2748.5 "/>
<text text-anchor="middle" x="458.5" y="-2733.3" font-family="Times,serif" font-size="14.00" fill="#000000">cellularity</text>
<polyline fill="none" stroke="#000000" points="344.5,-2725.5 572.5,-2725.5 "/>
<text text-anchor="middle" x="458.5" y="-2710.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="344.5,-2702.5 572.5,-2702.5 "/>
<text text-anchor="middle" x="458.5" y="-2687.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_variants</text>
<polyline fill="none" stroke="#000000" points="572.5,-2679.5 572.5,-2955.5 "/>
<text text-anchor="middle" x="583" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- variant&#45;&gt;genomic_report -->
<g id="edge34" class="edge">
<title>variant&#45;&gt;genomic_report</title>
<path fill="none" stroke="#000000" d="M393.5,-3007.2357C393.5,-2993.0591 393.5,-2979.1882 393.5,-2965.8076"/>
<polygon fill="#000000" stroke="#000000" points="397.0001,-2965.674 393.5,-2955.674 390.0001,-2965.6741 397.0001,-2965.674"/>
<text text-anchor="middle" x="427" y="-2977.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_report</text>
</g>
<!-- treatment -->
<g id="node5" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M12,-1462.5C12,-1462.5 437,-1462.5 437,-1462.5 443,-1462.5 449,-1468.5 449,-1474.5 449,-1474.5 449,-1657.5 449,-1657.5 449,-1663.5 443,-1669.5 437,-1669.5 437,-1669.5 12,-1669.5 12,-1669.5 6,-1669.5 0,-1663.5 0,-1657.5 0,-1657.5 0,-1474.5 0,-1474.5 0,-1468.5 6,-1462.5 12,-1462.5"/>
<text text-anchor="middle" x="44.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="89,-1462.5 89,-1669.5 "/>
<text text-anchor="middle" x="99.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="110,-1462.5 110,-1669.5 "/>
<text text-anchor="middle" x="269" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">endocrine_therapy_discontinued</text>
<polyline fill="none" stroke="#000000" points="110,-1646.5 428,-1646.5 "/>
<text text-anchor="middle" x="269" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_surgical_procedure</text>
<polyline fill="none" stroke="#000000" points="110,-1623.5 428,-1623.5 "/>
<text text-anchor="middle" x="269" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_endocrine_therapy_received</text>
<polyline fill="none" stroke="#000000" points="110,-1600.5 428,-1600.5 "/>
<text text-anchor="middle" x="269" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">duration_of_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="110,-1577.5 428,-1577.5 "/>
<text text-anchor="middle" x="269" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_last_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="110,-1554.5 428,-1554.5 "/>
<text text-anchor="middle" x="269" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">received_chemotherapy</text>
<polyline fill="none" stroke="#000000" points="110,-1531.5 428,-1531.5 "/>
<text text-anchor="middle" x="269" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">specific_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="110,-1508.5 428,-1508.5 "/>
<text text-anchor="middle" x="269" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_first_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="110,-1485.5 428,-1485.5 "/>
<text text-anchor="middle" x="269" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="428,-1462.5 428,-1669.5 "/>
<text text-anchor="middle" x="438.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case -->
<g id="node13" class="node">
<title>case</title>
<path fill="none" stroke="#000000" d="M1233.5,-1180.5C1233.5,-1180.5 1489.5,-1180.5 1489.5,-1180.5 1495.5,-1180.5 1501.5,-1186.5 1501.5,-1192.5 1501.5,-1192.5 1501.5,-1283.5 1501.5,-1283.5 1501.5,-1289.5 1495.5,-1295.5 1489.5,-1295.5 1489.5,-1295.5 1233.5,-1295.5 1233.5,-1295.5 1227.5,-1295.5 1221.5,-1289.5 1221.5,-1283.5 1221.5,-1283.5 1221.5,-1192.5 1221.5,-1192.5 1221.5,-1186.5 1227.5,-1180.5 1233.5,-1180.5"/>
<text text-anchor="middle" x="1246" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">case</text>
<polyline fill="none" stroke="#000000" points="1270.5,-1180.5 1270.5,-1295.5 "/>
<text text-anchor="middle" x="1281" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1291.5,-1180.5 1291.5,-1295.5 "/>
<text text-anchor="middle" x="1386" y="-1280.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_id</text>
<polyline fill="none" stroke="#000000" points="1291.5,-1272.5 1480.5,-1272.5 "/>
<text text-anchor="middle" x="1386" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">included_in_analysis</text>
<polyline fill="none" stroke="#000000" points="1291.5,-1249.5 1480.5,-1249.5 "/>
<text text-anchor="middle" x="1386" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">on_study_crf_submitted</text>
<polyline fill="none" stroke="#000000" points="1291.5,-1226.5 1480.5,-1226.5 "/>
<text text-anchor="middle" x="1386" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">case_id</text>
<polyline fill="none" stroke="#000000" points="1291.5,-1203.5 1480.5,-1203.5 "/>
<text text-anchor="middle" x="1386" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">ineligible</text>
<polyline fill="none" stroke="#000000" points="1480.5,-1180.5 1480.5,-1295.5 "/>
<text text-anchor="middle" x="1491" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;case -->
<g id="edge21" class="edge">
<title>treatment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M307.9183,-1462.4885C348.3813,-1419.547 400.5434,-1373.6206 457.5,-1347 587.7889,-1286.1052 989.5477,-1256.7091 1211.0603,-1244.7984"/>
<polygon fill="#000000" stroke="#000000" points="1211.3447,-1248.2883 1221.1445,-1244.2616 1210.9725,-1241.2982 1211.3447,-1248.2883"/>
<text text-anchor="middle" x="590.5" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- sample&#45;&gt;sample -->
<g id="edge30" class="edge">
<title>sample&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M914.0955,-1595.6213C925.3572,-1588.2644 932,-1578.3906 932,-1566 932,-1556.9006 928.4175,-1549.1586 922.0541,-1542.774"/>
<polygon fill="#000000" stroke="#000000" points="924.083,-1539.9144 914.0955,-1536.3787 919.6982,-1545.3709 924.083,-1539.9144"/>
<text text-anchor="middle" x="948" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- sample&#45;&gt;case -->
<g id="edge28" class="edge">
<title>sample&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M880.9053,-1347.2275C897.4578,-1334.7841 914.7094,-1323.5004 932.5,-1314 980.048,-1288.6086 1107.6277,-1267.9329 1211.3859,-1254.5924"/>
<polygon fill="#000000" stroke="#000000" points="1211.8711,-1258.059 1221.3491,-1253.3244 1210.9872,-1251.115 1211.8711,-1258.059"/>
<text text-anchor="middle" x="959.5" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- enrollment&#45;&gt;case -->
<g id="edge27" class="edge">
<title>enrollment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1563.5218,-1496.8404C1519.0597,-1439.8733 1456.4423,-1359.6449 1412.7462,-1303.6591"/>
<polygon fill="#000000" stroke="#000000" points="1415.3528,-1301.3102 1406.4409,-1295.5805 1409.8345,-1305.6172 1415.3528,-1301.3102"/>
<text text-anchor="middle" x="1456.5" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- program -->
<g id="node18" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M1186.5,-.5C1186.5,-.5 1494.5,-.5 1494.5,-.5 1500.5,-.5 1506.5,-6.5 1506.5,-12.5 1506.5,-12.5 1506.5,-172.5 1506.5,-172.5 1506.5,-178.5 1500.5,-184.5 1494.5,-184.5 1494.5,-184.5 1186.5,-184.5 1186.5,-184.5 1180.5,-184.5 1174.5,-178.5 1174.5,-172.5 1174.5,-172.5 1174.5,-12.5 1174.5,-12.5 1174.5,-6.5 1180.5,-.5 1186.5,-.5"/>
<text text-anchor="middle" x="1213.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1252.5,-.5 1252.5,-184.5 "/>
<text text-anchor="middle" x="1263" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1273.5,-.5 1273.5,-184.5 "/>
<text text-anchor="middle" x="1379.5" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="1273.5,-161.5 1485.5,-161.5 "/>
<text text-anchor="middle" x="1379.5" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1273.5,-138.5 1485.5,-138.5 "/>
<text text-anchor="middle" x="1379.5" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="1273.5,-115.5 1485.5,-115.5 "/>
<text text-anchor="middle" x="1379.5" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="1273.5,-92.5 1485.5,-92.5 "/>
<text text-anchor="middle" x="1379.5" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="1273.5,-69.5 1485.5,-69.5 "/>
<text text-anchor="middle" x="1379.5" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="1273.5,-46.5 1485.5,-46.5 "/>
<text text-anchor="middle" x="1379.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="1273.5,-23.5 1485.5,-23.5 "/>
<text text-anchor="middle" x="1379.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="1485.5,-.5 1485.5,-184.5 "/>
<text text-anchor="middle" x="1496" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge7" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1340.5,-236.3905C1340.5,-222.6101 1340.5,-208.6095 1340.5,-195.0235"/>
<polygon fill="#000000" stroke="#000000" points="1344.0001,-194.7254 1340.5,-184.7255 1337.0001,-194.7255 1344.0001,-194.7254"/>
<text text-anchor="middle" x="1381" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- agent_administration -->
<g id="node9" class="node">
<title>agent_administration</title>
<path fill="none" stroke="#000000" d="M790,-737.5C790,-737.5 1259,-737.5 1259,-737.5 1265,-737.5 1271,-743.5 1271,-749.5 1271,-749.5 1271,-1116.5 1271,-1116.5 1271,-1122.5 1265,-1128.5 1259,-1128.5 1259,-1128.5 790,-1128.5 790,-1128.5 784,-1128.5 778,-1122.5 778,-1116.5 778,-1116.5 778,-749.5 778,-749.5 778,-743.5 784,-737.5 790,-737.5"/>
<text text-anchor="middle" x="863" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_administration</text>
<polyline fill="none" stroke="#000000" points="948,-737.5 948,-1128.5 "/>
<text text-anchor="middle" x="958.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="969,-737.5 969,-1128.5 "/>
<text text-anchor="middle" x="1109.5" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_amount</text>
<polyline fill="none" stroke="#000000" points="969,-1105.5 1250,-1105.5 "/>
<text text-anchor="middle" x="1109.5" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="969,-1082.5 1250,-1082.5 "/>
<text text-anchor="middle" x="1109.5" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_dose</text>
<polyline fill="none" stroke="#000000" points="969,-1059.5 1250,-1059.5 "/>
<text text-anchor="middle" x="1109.5" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="969,-1036.5 1250,-1036.5 "/>
<text text-anchor="middle" x="1109.5" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_vial_id</text>
<polyline fill="none" stroke="#000000" points="969,-1013.5 1250,-1013.5 "/>
<text text-anchor="middle" x="1109.5" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="969,-990.5 1250,-990.5 "/>
<text text-anchor="middle" x="1109.5" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="969,-967.5 1250,-967.5 "/>
<text text-anchor="middle" x="1109.5" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_missed_dose</text>
<polyline fill="none" stroke="#000000" points="969,-944.5 1250,-944.5 "/>
<text text-anchor="middle" x="1109.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="969,-921.5 1250,-921.5 "/>
<text text-anchor="middle" x="1109.5" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_missed_dose</text>
<polyline fill="none" stroke="#000000" points="969,-898.5 1250,-898.5 "/>
<text text-anchor="middle" x="1109.5" y="-883.3" font-family="Times,serif" font-size="14.00" fill="#000000">stop_time</text>
<polyline fill="none" stroke="#000000" points="969,-875.5 1250,-875.5 "/>
<text text-anchor="middle" x="1109.5" y="-860.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_time</text>
<polyline fill="none" stroke="#000000" points="969,-852.5 1250,-852.5 "/>
<text text-anchor="middle" x="1109.5" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_course_number</text>
<polyline fill="none" stroke="#000000" points="969,-829.5 1250,-829.5 "/>
<text text-anchor="middle" x="1109.5" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_duration</text>
<polyline fill="none" stroke="#000000" points="969,-806.5 1250,-806.5 "/>
<text text-anchor="middle" x="1109.5" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">route_of_administration</text>
<polyline fill="none" stroke="#000000" points="969,-783.5 1250,-783.5 "/>
<text text-anchor="middle" x="1109.5" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_level</text>
<polyline fill="none" stroke="#000000" points="969,-760.5 1250,-760.5 "/>
<text text-anchor="middle" x="1109.5" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_lot_number</text>
<polyline fill="none" stroke="#000000" points="1250,-737.5 1250,-1128.5 "/>
<text text-anchor="middle" x="1260.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- agent -->
<g id="node24" class="node">
<title>agent</title>
<path fill="none" stroke="#000000" d="M930,-644.5C930,-644.5 1101,-644.5 1101,-644.5 1107,-644.5 1113,-650.5 1113,-656.5 1113,-656.5 1113,-668.5 1113,-668.5 1113,-674.5 1107,-680.5 1101,-680.5 1101,-680.5 930,-680.5 930,-680.5 924,-680.5 918,-674.5 918,-668.5 918,-668.5 918,-656.5 918,-656.5 918,-650.5 924,-644.5 930,-644.5"/>
<text text-anchor="middle" x="946.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">agent</text>
<polyline fill="none" stroke="#000000" points="975,-644.5 975,-680.5 "/>
<text text-anchor="middle" x="985.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="996,-644.5 996,-680.5 "/>
<text text-anchor="middle" x="1044" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="1092,-644.5 1092,-680.5 "/>
<text text-anchor="middle" x="1102.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- agent_administration&#45;&gt;agent -->
<g id="edge20" class="edge">
<title>agent_administration&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M1017.995,-737.4901C1017.4015,-719.6507 1016.8665,-703.5695 1016.4454,-690.9158"/>
<polygon fill="#000000" stroke="#000000" points="1019.9369,-690.5983 1016.1062,-680.7203 1012.9408,-690.8312 1019.9369,-690.5983"/>
<text text-anchor="middle" x="1047.5" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- follow_up -->
<g id="node10" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M1084.5,-1508.5C1084.5,-1508.5 1416.5,-1508.5 1416.5,-1508.5 1422.5,-1508.5 1428.5,-1514.5 1428.5,-1520.5 1428.5,-1520.5 1428.5,-1611.5 1428.5,-1611.5 1428.5,-1617.5 1422.5,-1623.5 1416.5,-1623.5 1416.5,-1623.5 1084.5,-1623.5 1084.5,-1623.5 1078.5,-1623.5 1072.5,-1617.5 1072.5,-1611.5 1072.5,-1611.5 1072.5,-1520.5 1072.5,-1520.5 1072.5,-1514.5 1078.5,-1508.5 1084.5,-1508.5"/>
<text text-anchor="middle" x="1115" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="1157.5,-1508.5 1157.5,-1623.5 "/>
<text text-anchor="middle" x="1168" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1178.5,-1508.5 1178.5,-1623.5 "/>
<text text-anchor="middle" x="1293" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_status</text>
<polyline fill="none" stroke="#000000" points="1178.5,-1600.5 1407.5,-1600.5 "/>
<text text-anchor="middle" x="1293" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">explain_unknown_status</text>
<polyline fill="none" stroke="#000000" points="1178.5,-1577.5 1407.5,-1577.5 "/>
<text text-anchor="middle" x="1293" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_since_last_contact</text>
<polyline fill="none" stroke="#000000" points="1178.5,-1554.5 1407.5,-1554.5 "/>
<text text-anchor="middle" x="1293" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">contact_type</text>
<polyline fill="none" stroke="#000000" points="1178.5,-1531.5 1407.5,-1531.5 "/>
<text text-anchor="middle" x="1293" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_contact</text>
<polyline fill="none" stroke="#000000" points="1407.5,-1508.5 1407.5,-1623.5 "/>
<text text-anchor="middle" x="1418" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;case -->
<g id="edge24" class="edge">
<title>follow_up&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1269.9617,-1508.4914C1289.1329,-1451.8415 1318.4114,-1365.3249 1338.6709,-1305.4589"/>
<polygon fill="#000000" stroke="#000000" points="1342.077,-1306.3125 1341.9673,-1295.7183 1335.4464,-1304.0686 1342.077,-1306.3125"/>
<text text-anchor="middle" x="1361.5" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- genomic_report&#45;&gt;assay -->
<g id="edge15" class="edge">
<title>genomic_report&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M494.01,-2679.2988C550.0754,-2602.2088 614.7928,-2513.2223 646.2867,-2469.9183"/>
<polygon fill="#000000" stroke="#000000" points="649.2579,-2471.7835 652.3091,-2461.6375 643.5967,-2467.6663 649.2579,-2471.7835"/>
<text text-anchor="middle" x="544" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- evaluation -->
<g id="node12" class="node">
<title>evaluation</title>
<path fill="none" stroke="#000000" d="M598.5,-3323C598.5,-3323 858.5,-3323 858.5,-3323 864.5,-3323 870.5,-3329 870.5,-3335 870.5,-3335 870.5,-3347 870.5,-3347 870.5,-3353 864.5,-3359 858.5,-3359 858.5,-3359 598.5,-3359 598.5,-3359 592.5,-3359 586.5,-3353 586.5,-3347 586.5,-3347 586.5,-3335 586.5,-3335 586.5,-3329 592.5,-3323 598.5,-3323"/>
<text text-anchor="middle" x="632" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">evaluation</text>
<polyline fill="none" stroke="#000000" points="677.5,-3323 677.5,-3359 "/>
<text text-anchor="middle" x="688" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="698.5,-3323 698.5,-3359 "/>
<text text-anchor="middle" x="774" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_evaluation</text>
<polyline fill="none" stroke="#000000" points="849.5,-3323 849.5,-3359 "/>
<text text-anchor="middle" x="860" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;study_arm -->
<g id="edge8" class="edge">
<title>case&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1387.6121,-1180.2699C1393.7412,-1164.0213 1399.389,-1146.107 1402.5,-1129 1412.2417,-1075.4313 1429.9362,-682.731 1397.5,-639 1384.5251,-621.507 1345.9795,-604.7095 1303.5282,-590.6751"/>
<polygon fill="#000000" stroke="#000000" points="1304.4306,-587.2885 1293.8388,-587.5392 1302.2751,-593.9484 1304.4306,-587.2885"/>
<text text-anchor="middle" x="1453" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- case&#45;&gt;study -->
<g id="edge9" class="edge">
<title>case&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1410.1085,-1180.2806C1454.2506,-1121.8494 1512.5,-1026.9459 1512.5,-933 1512.5,-933 1512.5,-933 1512.5,-553 1512.5,-524.9399 1502.7317,-498.8102 1487.8509,-475.2845"/>
<polygon fill="#000000" stroke="#000000" points="1490.6082,-473.111 1482.1458,-466.7362 1484.7858,-476.9968 1490.6082,-473.111"/>
<text text-anchor="middle" x="1553" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort -->
<g id="node14" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M1143,-639.5C1143,-639.5 1376,-639.5 1376,-639.5 1382,-639.5 1388,-645.5 1388,-651.5 1388,-651.5 1388,-673.5 1388,-673.5 1388,-679.5 1382,-685.5 1376,-685.5 1376,-685.5 1143,-685.5 1143,-685.5 1137,-685.5 1131,-679.5 1131,-673.5 1131,-673.5 1131,-651.5 1131,-651.5 1131,-645.5 1137,-639.5 1143,-639.5"/>
<text text-anchor="middle" x="1162.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="1194,-639.5 1194,-685.5 "/>
<text text-anchor="middle" x="1204.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1215,-639.5 1215,-685.5 "/>
<text text-anchor="middle" x="1291" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1215,-662.5 1367,-662.5 "/>
<text text-anchor="middle" x="1291" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_dose</text>
<polyline fill="none" stroke="#000000" points="1367,-639.5 1367,-685.5 "/>
<text text-anchor="middle" x="1377.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;cohort -->
<g id="edge10" class="edge">
<title>case&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M1337.2967,-1180.2622C1331.2849,-1163.9367 1325.4405,-1145.9852 1321.5,-1129 1281.912,-958.3594 1313.4937,-909.0373 1280.5,-737 1277.8637,-723.2539 1273.8964,-708.361 1270.1175,-695.5298"/>
<polygon fill="#000000" stroke="#000000" points="1273.4024,-694.3006 1267.1564,-685.7428 1266.7024,-696.3279 1273.4024,-694.3006"/>
<text text-anchor="middle" x="1362" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- adverse_event -->
<g id="node20" class="node">
<title>adverse_event</title>
<path fill="none" stroke="#000000" d="M303,-818C303,-818 698,-818 698,-818 704,-818 710,-824 710,-830 710,-830 710,-1036 710,-1036 710,-1042 704,-1048 698,-1048 698,-1048 303,-1048 303,-1048 297,-1048 291,-1042 291,-1036 291,-1036 291,-830 291,-830 291,-824 297,-818 303,-818"/>
<text text-anchor="middle" x="351" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="411,-818 411,-1048 "/>
<text text-anchor="middle" x="421.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="432,-818 432,-1048 "/>
<text text-anchor="middle" x="560.5" y="-1032.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_term</text>
<polyline fill="none" stroke="#000000" points="432,-1025 689,-1025 "/>
<text text-anchor="middle" x="560.5" y="-1009.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_agent_name</text>
<polyline fill="none" stroke="#000000" points="432,-1002 689,-1002 "/>
<text text-anchor="middle" x="560.5" y="-986.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade</text>
<polyline fill="none" stroke="#000000" points="432,-979 689,-979 "/>
<text text-anchor="middle" x="560.5" y="-963.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_description</text>
<polyline fill="none" stroke="#000000" points="432,-956 689,-956 "/>
<text text-anchor="middle" x="560.5" y="-940.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_other</text>
<polyline fill="none" stroke="#000000" points="432,-933 689,-933 "/>
<text text-anchor="middle" x="560.5" y="-917.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_attribution</text>
<polyline fill="none" stroke="#000000" points="432,-910 689,-910 "/>
<text text-anchor="middle" x="560.5" y="-894.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_resolved</text>
<polyline fill="none" stroke="#000000" points="432,-887 689,-887 "/>
<text text-anchor="middle" x="560.5" y="-871.8" font-family="Times,serif" font-size="14.00" fill="#000000">unexpected_adverse_event</text>
<polyline fill="none" stroke="#000000" points="432,-864 689,-864 "/>
<text text-anchor="middle" x="560.5" y="-848.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade_description</text>
<polyline fill="none" stroke="#000000" points="432,-841 689,-841 "/>
<text text-anchor="middle" x="560.5" y="-825.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_dose</text>
<polyline fill="none" stroke="#000000" points="689,-818 689,-1048 "/>
<text text-anchor="middle" x="699.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;adverse_event -->
<g id="edge14" class="edge">
<title>case&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M1221.2475,-1229.8123C1097.9748,-1218.56 915.9226,-1191.9241 769.5,-1129 725.2648,-1109.9902 681.3277,-1082.5912 642.1808,-1054.2779"/>
<polygon fill="#000000" stroke="#000000" points="644.04,-1051.3015 633.9017,-1048.225 639.9086,-1056.9524 644.04,-1051.3015"/>
<text text-anchor="middle" x="914.5" y="-1150.8" font-family="Times,serif" font-size="14.00" fill="#000000">had_adverse_event</text>
</g>
<!-- cohort&#45;&gt;study_arm -->
<g id="edge13" class="edge">
<title>cohort&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1238.0805,-639.2779C1226.3447,-626.5544 1211.4303,-610.3848 1197.6927,-595.4911"/>
<polygon fill="#000000" stroke="#000000" points="1199.992,-592.8216 1190.6392,-587.844 1194.8465,-597.5676 1199.992,-592.8216"/>
<text text-anchor="middle" x="1261" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort&#45;&gt;study -->
<g id="edge12" class="edge">
<title>cohort&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1310.8858,-639.4136C1331.4759,-627.281 1353.0099,-610.2411 1364.5,-588 1381.9319,-554.2576 1383.7297,-514.213 1378.8809,-476.7574"/>
<polygon fill="#000000" stroke="#000000" points="1382.3332,-476.1755 1377.4282,-466.7845 1375.4063,-477.1846 1382.3332,-476.1755"/>
<text text-anchor="middle" x="1421" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- assay&#45;&gt;sample -->
<g id="edge5" class="edge">
<title>assay&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M666.0222,-2425.1722C668.2987,-2345.2645 677.531,-2021.2117 683.9819,-1794.7844"/>
<polygon fill="#000000" stroke="#000000" points="687.4815,-1794.8476 684.2678,-1784.7519 680.4843,-1794.6482 687.4815,-1794.8476"/>
<text text-anchor="middle" x="719" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- visit -->
<g id="node16" class="node">
<title>visit</title>
<path fill="none" stroke="#000000" d="M901,-3318C901,-3318 1076,-3318 1076,-3318 1082,-3318 1088,-3324 1088,-3330 1088,-3330 1088,-3352 1088,-3352 1088,-3358 1082,-3364 1076,-3364 1076,-3364 901,-3364 901,-3364 895,-3364 889,-3358 889,-3352 889,-3352 889,-3330 889,-3330 889,-3324 895,-3318 901,-3318"/>
<text text-anchor="middle" x="912.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">visit</text>
<polyline fill="none" stroke="#000000" points="936,-3318 936,-3364 "/>
<text text-anchor="middle" x="946.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="957,-3318 957,-3364 "/>
<text text-anchor="middle" x="1012" y="-3348.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_date</text>
<polyline fill="none" stroke="#000000" points="957,-3341 1067,-3341 "/>
<text text-anchor="middle" x="1012" y="-3325.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_number</text>
<polyline fill="none" stroke="#000000" points="1067,-3318 1067,-3364 "/>
<text text-anchor="middle" x="1077.5" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- visit&#45;&gt;visit -->
<g id="edge29" class="edge">
<title>visit&#45;&gt;visit</title>
<path fill="none" stroke="#000000" d="M1000.7183,-3364.2371C1041.9427,-3429.6803 1106,-3421.9346 1106,-3341 1106,-3263.7012 1047.5686,-3253.1633 1006.4043,-3309.3865"/>
<polygon fill="#000000" stroke="#000000" points="1003.4389,-3307.5233 1000.7183,-3317.7629 1009.2306,-3311.4548 1003.4389,-3307.5233"/>
<text text-anchor="middle" x="1122" y="-3337.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- diagnosis&#45;&gt;case -->
<g id="edge22" class="edge">
<title>diagnosis&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M990.7814,-1803.1296C984.7151,-1620.0662 982.4845,-1383.1398 1009.5,-1347 1034.7385,-1313.2374 1127.2701,-1285.3509 1211.1253,-1266.2375"/>
<polygon fill="#000000" stroke="#000000" points="1212.0514,-1269.6168 1221.0402,-1264.0087 1210.5161,-1262.7872 1212.0514,-1269.6168"/>
<text text-anchor="middle" x="1036.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- prior_surgery -->
<g id="node19" class="node">
<title>prior_surgery</title>
<path fill="none" stroke="#000000" d="M1243.5,-2374.5C1243.5,-2374.5 1589.5,-2374.5 1589.5,-2374.5 1595.5,-2374.5 1601.5,-2380.5 1601.5,-2386.5 1601.5,-2386.5 1601.5,-2500.5 1601.5,-2500.5 1601.5,-2506.5 1595.5,-2512.5 1589.5,-2512.5 1589.5,-2512.5 1243.5,-2512.5 1243.5,-2512.5 1237.5,-2512.5 1231.5,-2506.5 1231.5,-2500.5 1231.5,-2500.5 1231.5,-2386.5 1231.5,-2386.5 1231.5,-2380.5 1237.5,-2374.5 1243.5,-2374.5"/>
<text text-anchor="middle" x="1289" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_surgery</text>
<polyline fill="none" stroke="#000000" points="1346.5,-2374.5 1346.5,-2512.5 "/>
<text text-anchor="middle" x="1357" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1367.5,-2374.5 1367.5,-2512.5 "/>
<text text-anchor="middle" x="1474" y="-2497.3" font-family="Times,serif" font-size="14.00" fill="#000000">residual_disease</text>
<polyline fill="none" stroke="#000000" points="1367.5,-2489.5 1580.5,-2489.5 "/>
<text text-anchor="middle" x="1474" y="-2474.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomical_site_of_surgery</text>
<polyline fill="none" stroke="#000000" points="1367.5,-2466.5 1580.5,-2466.5 "/>
<text text-anchor="middle" x="1474" y="-2451.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_finding</text>
<polyline fill="none" stroke="#000000" points="1367.5,-2443.5 1580.5,-2443.5 "/>
<text text-anchor="middle" x="1474" y="-2428.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_indicator</text>
<polyline fill="none" stroke="#000000" points="1367.5,-2420.5 1580.5,-2420.5 "/>
<text text-anchor="middle" x="1474" y="-2405.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_surgery</text>
<polyline fill="none" stroke="#000000" points="1367.5,-2397.5 1580.5,-2397.5 "/>
<text text-anchor="middle" x="1474" y="-2382.3" font-family="Times,serif" font-size="14.00" fill="#000000">procedure</text>
<polyline fill="none" stroke="#000000" points="1580.5,-2374.5 1580.5,-2512.5 "/>
<text text-anchor="middle" x="1591" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_surgery&#45;&gt;enrollment -->
<g id="edge3" class="edge">
<title>prior_surgery&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M1432.356,-2374.2777C1469.2118,-2213.3777 1560.4686,-1814.9805 1599.4154,-1644.9514"/>
<polygon fill="#000000" stroke="#000000" points="1602.8586,-1645.5949 1601.6798,-1635.0658 1596.0353,-1644.0319 1602.8586,-1645.5949"/>
<text text-anchor="middle" x="1607.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- prior_surgery&#45;&gt;prior_surgery -->
<g id="edge32" class="edge">
<title>prior_surgery&#45;&gt;prior_surgery</title>
<path fill="none" stroke="#000000" d="M1601.613,-2470.7602C1612.7907,-2464.2762 1619.5,-2455.1895 1619.5,-2443.5 1619.5,-2435.0982 1616.034,-2428.041 1609.934,-2422.3283"/>
<polygon fill="#000000" stroke="#000000" points="1611.7501,-2419.3204 1601.613,-2416.2398 1607.6165,-2424.9696 1611.7501,-2419.3204"/>
<text text-anchor="middle" x="1635.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- adverse_event&#45;&gt;adverse_event -->
<g id="edge31" class="edge">
<title>adverse_event&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M710.2046,-960.2761C721.376,-953.5862 728,-944.4941 728,-933 728,-924.7386 724.5781,-917.7181 718.5052,-911.9385"/>
<polygon fill="#000000" stroke="#000000" points="720.3073,-908.9155 710.2046,-905.7239 716.1119,-914.519 720.3073,-908.9155"/>
<text text-anchor="middle" x="744" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- adverse_event&#45;&gt;agent -->
<g id="edge19" class="edge">
<title>adverse_event&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M639.9703,-817.7928C680.0584,-788.5304 725.0133,-759.1447 769.5,-737 817.4245,-713.144 874.4551,-695.2862 921.5326,-683.0438"/>
<polygon fill="#000000" stroke="#000000" points="922.5988,-686.3839 931.4206,-680.5165 920.8653,-679.6019 922.5988,-686.3839"/>
<text text-anchor="middle" x="878.5" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- demographic -->
<g id="node21" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M1818.5,-1485.5C1818.5,-1485.5 2154.5,-1485.5 2154.5,-1485.5 2160.5,-1485.5 2166.5,-1491.5 2166.5,-1497.5 2166.5,-1497.5 2166.5,-1634.5 2166.5,-1634.5 2166.5,-1640.5 2160.5,-1646.5 2154.5,-1646.5 2154.5,-1646.5 1818.5,-1646.5 1818.5,-1646.5 1812.5,-1646.5 1806.5,-1640.5 1806.5,-1634.5 1806.5,-1634.5 1806.5,-1497.5 1806.5,-1497.5 1806.5,-1491.5 1812.5,-1485.5 1818.5,-1485.5"/>
<text text-anchor="middle" x="1861.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="1916.5,-1485.5 1916.5,-1646.5 "/>
<text text-anchor="middle" x="1927" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1937.5,-1485.5 1937.5,-1646.5 "/>
<text text-anchor="middle" x="2041.5" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="1937.5,-1623.5 2145.5,-1623.5 "/>
<text text-anchor="middle" x="2041.5" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="1937.5,-1600.5 2145.5,-1600.5 "/>
<text text-anchor="middle" x="2041.5" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="1937.5,-1577.5 2145.5,-1577.5 "/>
<text text-anchor="middle" x="2041.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status</text>
<polyline fill="none" stroke="#000000" points="1937.5,-1554.5 2145.5,-1554.5 "/>
<text text-anchor="middle" x="2041.5" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_birth</text>
<polyline fill="none" stroke="#000000" points="1937.5,-1531.5 2145.5,-1531.5 "/>
<text text-anchor="middle" x="2041.5" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1937.5,-1508.5 2145.5,-1508.5 "/>
<text text-anchor="middle" x="2041.5" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="2145.5,-1485.5 2145.5,-1646.5 "/>
<text text-anchor="middle" x="2156" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;case -->
<g id="edge26" class="edge">
<title>demographic&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1935.5853,-1485.2897C1901.8848,-1438.2477 1853.6301,-1381.5596 1797.5,-1347 1711.1341,-1293.8241 1600.061,-1266.5469 1511.6402,-1252.5776"/>
<polygon fill="#000000" stroke="#000000" points="1511.9366,-1249.0822 1501.5207,-1251.0211 1510.8724,-1256.0008 1511.9366,-1249.0822"/>
<text text-anchor="middle" x="1781.5" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- stratification -->
<g id="node22" class="node">
<title>stratification</title>
<path fill="none" stroke="#000000" d="M2196.5,-1497C2196.5,-1497 2608.5,-1497 2608.5,-1497 2614.5,-1497 2620.5,-1503 2620.5,-1509 2620.5,-1509 2620.5,-1623 2620.5,-1623 2620.5,-1629 2614.5,-1635 2608.5,-1635 2608.5,-1635 2196.5,-1635 2196.5,-1635 2190.5,-1635 2184.5,-1629 2184.5,-1623 2184.5,-1623 2184.5,-1509 2184.5,-1509 2184.5,-1503 2190.5,-1497 2196.5,-1497"/>
<text text-anchor="middle" x="2239.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification</text>
<polyline fill="none" stroke="#000000" points="2294.5,-1497 2294.5,-1635 "/>
<text text-anchor="middle" x="2305" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2315.5,-1497 2315.5,-1635 "/>
<text text-anchor="middle" x="2457.5" y="-1619.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_chemotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="2315.5,-1612 2599.5,-1612 "/>
<text text-anchor="middle" x="2457.5" y="-1596.8" font-family="Times,serif" font-size="14.00" fill="#000000">combined_stratification_variable</text>
<polyline fill="none" stroke="#000000" points="2315.5,-1589 2599.5,-1589 "/>
<text text-anchor="middle" x="2457.5" y="-1573.8" font-family="Times,serif" font-size="14.00" fill="#000000">grouped_recurrence_score</text>
<polyline fill="none" stroke="#000000" points="2315.5,-1566 2599.5,-1566 "/>
<text text-anchor="middle" x="2457.5" y="-1550.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_stratification</text>
<polyline fill="none" stroke="#000000" points="2315.5,-1543 2599.5,-1543 "/>
<text text-anchor="middle" x="2457.5" y="-1527.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status_stratification</text>
<polyline fill="none" stroke="#000000" points="2315.5,-1520 2599.5,-1520 "/>
<text text-anchor="middle" x="2457.5" y="-1504.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_radiotherapy</text>
<polyline fill="none" stroke="#000000" points="2599.5,-1497 2599.5,-1635 "/>
<text text-anchor="middle" x="2610" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- stratification&#45;&gt;case -->
<g id="edge25" class="edge">
<title>stratification&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2351.1529,-1496.8933C2309.6633,-1446.5485 2246.6182,-1381.3793 2175.5,-1347 2061.5707,-1291.9253 1714.289,-1260.8217 1512.0286,-1246.9255"/>
<polygon fill="#000000" stroke="#000000" points="1512.1256,-1243.424 1501.9109,-1246.2363 1511.6499,-1250.4079 1512.1256,-1243.424"/>
<text text-anchor="middle" x="2153.5" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- survival -->
<g id="node23" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M2651,-1416.5C2651,-1416.5 2976,-1416.5 2976,-1416.5 2982,-1416.5 2988,-1422.5 2988,-1428.5 2988,-1428.5 2988,-1703.5 2988,-1703.5 2988,-1709.5 2982,-1715.5 2976,-1715.5 2976,-1715.5 2651,-1715.5 2651,-1715.5 2645,-1715.5 2639,-1709.5 2639,-1703.5 2639,-1703.5 2639,-1428.5 2639,-1428.5 2639,-1422.5 2645,-1416.5 2651,-1416.5"/>
<text text-anchor="middle" x="2676" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="2713,-1416.5 2713,-1715.5 "/>
<text text-anchor="middle" x="2723.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2734,-1416.5 2734,-1715.5 "/>
<text text-anchor="middle" x="2850.5" y="-1700.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="2734,-1692.5 2967,-1692.5 "/>
<text text-anchor="middle" x="2850.5" y="-1677.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="2734,-1669.5 2967,-1669.5 "/>
<text text-anchor="middle" x="2850.5" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_withdrawn</text>
<polyline fill="none" stroke="#000000" points="2734,-1646.5 2967,-1646.5 "/>
<text text-anchor="middle" x="2850.5" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_status</text>
<polyline fill="none" stroke="#000000" points="2734,-1623.5 2967,-1623.5 "/>
<text text-anchor="middle" x="2850.5" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_event_indicator</text>
<polyline fill="none" stroke="#000000" points="2734,-1600.5 2967,-1600.5 "/>
<text text-anchor="middle" x="2850.5" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_dfs_event</text>
<polyline fill="none" stroke="#000000" points="2734,-1577.5 2967,-1577.5 "/>
<text text-anchor="middle" x="2850.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="2734,-1554.5 2967,-1554.5 "/>
<text text-anchor="middle" x="2850.5" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_survival_interval</text>
<polyline fill="none" stroke="#000000" points="2734,-1531.5 2967,-1531.5 "/>
<text text-anchor="middle" x="2850.5" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">lost_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="2734,-1508.5 2967,-1508.5 "/>
<text text-anchor="middle" x="2850.5" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_survival</text>
<polyline fill="none" stroke="#000000" points="2734,-1485.5 2967,-1485.5 "/>
<text text-anchor="middle" x="2850.5" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_recurrence</text>
<polyline fill="none" stroke="#000000" points="2734,-1462.5 2967,-1462.5 "/>
<text text-anchor="middle" x="2850.5" y="-1447.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_free_interval</text>
<polyline fill="none" stroke="#000000" points="2734,-1439.5 2967,-1439.5 "/>
<text text-anchor="middle" x="2850.5" y="-1424.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_interval</text>
<polyline fill="none" stroke="#000000" points="2967,-1416.5 2967,-1715.5 "/>
<text text-anchor="middle" x="2977.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;case -->
<g id="edge23" class="edge">
<title>survival&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2715.6814,-1416.4341C2690.8535,-1389.0324 2661.8935,-1363.8188 2629.5,-1347 2532.3844,-1296.5774 1826.2871,-1258.9217 1511.8502,-1244.4674"/>
<polygon fill="#000000" stroke="#000000" points="1511.8964,-1240.9659 1501.7468,-1244.0048 1511.5762,-1247.9586 1511.8964,-1240.9659"/>
<text text-anchor="middle" x="2589.5" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- agent&#45;&gt;study_arm -->
<g id="edge18" class="edge">
<title>agent&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1039.1135,-644.4183C1056.9884,-630.7309 1082.2531,-611.3848 1104.9412,-594.0118"/>
<polygon fill="#000000" stroke="#000000" points="1107.3531,-596.5732 1113.1649,-587.7146 1103.0974,-591.0154 1107.3531,-596.5732"/>
<text text-anchor="middle" x="1135" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
<!-- image -->
<g id="node25" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M623.5,-2799.5C623.5,-2799.5 659.5,-2799.5 659.5,-2799.5 665.5,-2799.5 671.5,-2805.5 671.5,-2811.5 671.5,-2811.5 671.5,-2823.5 671.5,-2823.5 671.5,-2829.5 665.5,-2835.5 659.5,-2835.5 659.5,-2835.5 623.5,-2835.5 623.5,-2835.5 617.5,-2835.5 611.5,-2829.5 611.5,-2823.5 611.5,-2823.5 611.5,-2811.5 611.5,-2811.5 611.5,-2805.5 617.5,-2799.5 623.5,-2799.5"/>
<text text-anchor="middle" x="641.5" y="-2813.8" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
</g>
<!-- image&#45;&gt;assay -->
<g id="edge16" class="edge">
<title>image&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M640.97,-2799.4546C640.1934,-2768.1761 639.1734,-2701.8777 642.5,-2646 646.2191,-2583.5296 655.7781,-2510.7184 661.3321,-2471.6755"/>
<polygon fill="#000000" stroke="#000000" points="664.8225,-2471.9924 662.7842,-2461.5955 657.894,-2470.9942 664.8225,-2471.9924"/>
<text text-anchor="middle" x="673" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
</g>
</svg>
</div>
