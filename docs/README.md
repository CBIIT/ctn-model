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
<!-- study_arm -->
<g id="node1" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M839,-242.5C839,-242.5 994,-242.5 994,-242.5 1000,-242.5 1006,-248.5 1006,-254.5 1006,-254.5 1006,-266.5 1006,-266.5 1006,-272.5 1000,-278.5 994,-278.5 994,-278.5 839,-278.5 839,-278.5 833,-278.5 827,-272.5 827,-266.5 827,-266.5 827,-254.5 827,-254.5 827,-248.5 833,-242.5 839,-242.5"/>
<text text-anchor="middle" x="873" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="919,-242.5 919,-278.5 "/>
<text text-anchor="middle" x="929.5" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="940,-242.5 940,-278.5 "/>
<text text-anchor="middle" x="962.5" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000">arm</text>
<polyline fill="none" stroke="#000000" points="985,-242.5 985,-278.5 "/>
<text text-anchor="middle" x="995.5" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study -->
<g id="node6" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M902.5,-98.5C902.5,-98.5 1182.5,-98.5 1182.5,-98.5 1188.5,-98.5 1194.5,-104.5 1194.5,-110.5 1194.5,-110.5 1194.5,-178.5 1194.5,-178.5 1194.5,-184.5 1188.5,-190.5 1182.5,-190.5 1182.5,-190.5 902.5,-190.5 902.5,-190.5 896.5,-190.5 890.5,-184.5 890.5,-178.5 890.5,-178.5 890.5,-110.5 890.5,-110.5 890.5,-104.5 896.5,-98.5 902.5,-98.5"/>
<text text-anchor="middle" x="918.5" y="-140.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="946.5,-98.5 946.5,-190.5 "/>
<text text-anchor="middle" x="957" y="-140.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="967.5,-98.5 967.5,-190.5 "/>
<text text-anchor="middle" x="1070.5" y="-175.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_name</text>
<polyline fill="none" stroke="#000000" points="967.5,-167.5 1173.5,-167.5 "/>
<text text-anchor="middle" x="1070.5" y="-152.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_designation</text>
<polyline fill="none" stroke="#000000" points="967.5,-144.5 1173.5,-144.5 "/>
<text text-anchor="middle" x="1070.5" y="-129.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_id</text>
<polyline fill="none" stroke="#000000" points="967.5,-121.5 1173.5,-121.5 "/>
<text text-anchor="middle" x="1070.5" y="-106.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_description</text>
<polyline fill="none" stroke="#000000" points="1173.5,-98.5 1173.5,-190.5 "/>
<text text-anchor="middle" x="1184" y="-140.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge8" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M925.112,-242.0248C930.566,-231.5748 938.316,-218.6998 947.5,-209 951.2692,-205.0191 955.3249,-201.1492 959.562,-197.4124"/>
<polygon fill="#000000" stroke="#000000" points="961.9738,-199.9569 967.362,-190.8345 957.461,-194.6057 961.9738,-199.9569"/>
<text text-anchor="middle" x="988" y="-212.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- diagnosis -->
<g id="node2" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M12,-664.5C12,-664.5 347,-664.5 347,-664.5 353,-664.5 359,-670.5 359,-676.5 359,-676.5 359,-813.5 359,-813.5 359,-819.5 353,-825.5 347,-825.5 347,-825.5 12,-825.5 12,-825.5 6,-825.5 0,-819.5 0,-813.5 0,-813.5 0,-676.5 0,-676.5 0,-670.5 6,-664.5 12,-664.5"/>
<text text-anchor="middle" x="42" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="84,-664.5 84,-825.5 "/>
<text text-anchor="middle" x="94.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="105,-664.5 105,-825.5 "/>
<text text-anchor="middle" x="221.5" y="-810.3" font-family="Times,serif" font-size="14.00" fill="#000000">histological_grade</text>
<polyline fill="none" stroke="#000000" points="105,-802.5 338,-802.5 "/>
<text text-anchor="middle" x="221.5" y="-787.3" font-family="Times,serif" font-size="14.00" fill="#000000">progesterone_receptor_status</text>
<polyline fill="none" stroke="#000000" points="105,-779.5 338,-779.5 "/>
<text text-anchor="middle" x="221.5" y="-764.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size</text>
<polyline fill="none" stroke="#000000" points="105,-756.5 338,-756.5 "/>
<text text-anchor="middle" x="221.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">nuclear_grade</text>
<polyline fill="none" stroke="#000000" points="105,-733.5 338,-733.5 "/>
<text text-anchor="middle" x="221.5" y="-718.3" font-family="Times,serif" font-size="14.00" fill="#000000">estrogen_receptor_status</text>
<polyline fill="none" stroke="#000000" points="105,-710.5 338,-710.5 "/>
<text text-anchor="middle" x="221.5" y="-695.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_group</text>
<polyline fill="none" stroke="#000000" points="105,-687.5 338,-687.5 "/>
<text text-anchor="middle" x="221.5" y="-672.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_score</text>
<polyline fill="none" stroke="#000000" points="338,-664.5 338,-825.5 "/>
<text text-anchor="middle" x="348.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case -->
<g id="node9" class="node">
<title>case</title>
<path fill="none" stroke="#000000" d="M890.5,-428.5C890.5,-428.5 1146.5,-428.5 1146.5,-428.5 1152.5,-428.5 1158.5,-434.5 1158.5,-440.5 1158.5,-440.5 1158.5,-531.5 1158.5,-531.5 1158.5,-537.5 1152.5,-543.5 1146.5,-543.5 1146.5,-543.5 890.5,-543.5 890.5,-543.5 884.5,-543.5 878.5,-537.5 878.5,-531.5 878.5,-531.5 878.5,-440.5 878.5,-440.5 878.5,-434.5 884.5,-428.5 890.5,-428.5"/>
<text text-anchor="middle" x="903" y="-482.3" font-family="Times,serif" font-size="14.00" fill="#000000">case</text>
<polyline fill="none" stroke="#000000" points="927.5,-428.5 927.5,-543.5 "/>
<text text-anchor="middle" x="938" y="-482.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="948.5,-428.5 948.5,-543.5 "/>
<text text-anchor="middle" x="1043" y="-528.3" font-family="Times,serif" font-size="14.00" fill="#000000">on_study_crf_submitted</text>
<polyline fill="none" stroke="#000000" points="948.5,-520.5 1137.5,-520.5 "/>
<text text-anchor="middle" x="1043" y="-505.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_id</text>
<polyline fill="none" stroke="#000000" points="948.5,-497.5 1137.5,-497.5 "/>
<text text-anchor="middle" x="1043" y="-482.3" font-family="Times,serif" font-size="14.00" fill="#000000">ineligible</text>
<polyline fill="none" stroke="#000000" points="948.5,-474.5 1137.5,-474.5 "/>
<text text-anchor="middle" x="1043" y="-459.3" font-family="Times,serif" font-size="14.00" fill="#000000">case_id</text>
<polyline fill="none" stroke="#000000" points="948.5,-451.5 1137.5,-451.5 "/>
<text text-anchor="middle" x="1043" y="-436.3" font-family="Times,serif" font-size="14.00" fill="#000000">included_in_analysis</text>
<polyline fill="none" stroke="#000000" points="1137.5,-428.5 1137.5,-543.5 "/>
<text text-anchor="middle" x="1148" y="-482.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- diagnosis&#45;&gt;case -->
<g id="edge2" class="edge">
<title>diagnosis&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M261.8377,-664.3445C292.711,-638.3573 329.5592,-611.9283 367.5,-595 454.7565,-556.0683 704.5692,-521.6057 868.1348,-502.3094"/>
<polygon fill="#000000" stroke="#000000" points="868.769,-505.7591 878.2929,-501.1174 867.9531,-498.8068 868.769,-505.7591"/>
<text text-anchor="middle" x="499.5" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- treatment -->
<g id="node3" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M389,-641.5C389,-641.5 814,-641.5 814,-641.5 820,-641.5 826,-647.5 826,-653.5 826,-653.5 826,-836.5 826,-836.5 826,-842.5 820,-848.5 814,-848.5 814,-848.5 389,-848.5 389,-848.5 383,-848.5 377,-842.5 377,-836.5 377,-836.5 377,-653.5 377,-653.5 377,-647.5 383,-641.5 389,-641.5"/>
<text text-anchor="middle" x="421.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="466,-641.5 466,-848.5 "/>
<text text-anchor="middle" x="476.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="487,-641.5 487,-848.5 "/>
<text text-anchor="middle" x="646" y="-833.3" font-family="Times,serif" font-size="14.00" fill="#000000">duration_of_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="487,-825.5 805,-825.5 "/>
<text text-anchor="middle" x="646" y="-810.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_first_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="487,-802.5 805,-802.5 "/>
<text text-anchor="middle" x="646" y="-787.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_endocrine_therapy_received</text>
<polyline fill="none" stroke="#000000" points="487,-779.5 805,-779.5 "/>
<text text-anchor="middle" x="646" y="-764.3" font-family="Times,serif" font-size="14.00" fill="#000000">endocrine_therapy_discontinued</text>
<polyline fill="none" stroke="#000000" points="487,-756.5 805,-756.5 "/>
<text text-anchor="middle" x="646" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_last_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="487,-733.5 805,-733.5 "/>
<text text-anchor="middle" x="646" y="-718.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="487,-710.5 805,-710.5 "/>
<text text-anchor="middle" x="646" y="-695.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_surgical_procedure</text>
<polyline fill="none" stroke="#000000" points="487,-687.5 805,-687.5 "/>
<text text-anchor="middle" x="646" y="-672.3" font-family="Times,serif" font-size="14.00" fill="#000000">received_chemotherapy</text>
<polyline fill="none" stroke="#000000" points="487,-664.5 805,-664.5 "/>
<text text-anchor="middle" x="646" y="-649.3" font-family="Times,serif" font-size="14.00" fill="#000000">specific_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="805,-641.5 805,-848.5 "/>
<text text-anchor="middle" x="815.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;case -->
<g id="edge4" class="edge">
<title>treatment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M760.8073,-641.3306C785.3893,-625.6562 810.5568,-609.7918 834.5,-595 859.0824,-579.8132 885.7234,-563.7867 910.8994,-548.8344"/>
<polygon fill="#000000" stroke="#000000" points="912.9213,-551.7046 919.7376,-543.5935 909.3509,-545.6835 912.9213,-551.7046"/>
<text text-anchor="middle" x="912.5" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- cohort -->
<g id="node4" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M902,-330.5C902,-330.5 1135,-330.5 1135,-330.5 1141,-330.5 1147,-336.5 1147,-342.5 1147,-342.5 1147,-364.5 1147,-364.5 1147,-370.5 1141,-376.5 1135,-376.5 1135,-376.5 902,-376.5 902,-376.5 896,-376.5 890,-370.5 890,-364.5 890,-364.5 890,-342.5 890,-342.5 890,-336.5 896,-330.5 902,-330.5"/>
<text text-anchor="middle" x="921.5" y="-349.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="953,-330.5 953,-376.5 "/>
<text text-anchor="middle" x="963.5" y="-349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="974,-330.5 974,-376.5 "/>
<text text-anchor="middle" x="1050" y="-361.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_dose</text>
<polyline fill="none" stroke="#000000" points="974,-353.5 1126,-353.5 "/>
<text text-anchor="middle" x="1050" y="-338.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1126,-330.5 1126,-376.5 "/>
<text text-anchor="middle" x="1136.5" y="-349.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- cohort&#45;&gt;study_arm -->
<g id="edge7" class="edge">
<title>cohort&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M971.416,-330.4982C962.9004,-325.126 954.5109,-318.921 947.5,-312 940.4099,-305.0007 934.2966,-296.0596 929.4177,-287.5983"/>
<polygon fill="#000000" stroke="#000000" points="932.4534,-285.8538 924.6203,-278.72 926.295,-289.1816 932.4534,-285.8538"/>
<text text-anchor="middle" x="988" y="-300.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort&#45;&gt;study -->
<g id="edge11" class="edge">
<title>cohort&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1024.7381,-330.3609C1026.1585,-324.4135 1027.5323,-317.9995 1028.5,-312 1034.4332,-275.2163 1037.9306,-233.4579 1039.9459,-200.8373"/>
<polygon fill="#000000" stroke="#000000" points="1043.4557,-200.7736 1040.5494,-190.5852 1036.4678,-200.3622 1043.4557,-200.7736"/>
<text text-anchor="middle" x="1078" y="-256.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- survival -->
<g id="node5" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M856,-595.5C856,-595.5 1181,-595.5 1181,-595.5 1187,-595.5 1193,-601.5 1193,-607.5 1193,-607.5 1193,-882.5 1193,-882.5 1193,-888.5 1187,-894.5 1181,-894.5 1181,-894.5 856,-894.5 856,-894.5 850,-894.5 844,-888.5 844,-882.5 844,-882.5 844,-607.5 844,-607.5 844,-601.5 850,-595.5 856,-595.5"/>
<text text-anchor="middle" x="881" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="918,-595.5 918,-894.5 "/>
<text text-anchor="middle" x="928.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="939,-595.5 939,-894.5 "/>
<text text-anchor="middle" x="1055.5" y="-879.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_status</text>
<polyline fill="none" stroke="#000000" points="939,-871.5 1172,-871.5 "/>
<text text-anchor="middle" x="1055.5" y="-856.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_interval</text>
<polyline fill="none" stroke="#000000" points="939,-848.5 1172,-848.5 "/>
<text text-anchor="middle" x="1055.5" y="-833.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_survival</text>
<polyline fill="none" stroke="#000000" points="939,-825.5 1172,-825.5 "/>
<text text-anchor="middle" x="1055.5" y="-810.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_free_interval</text>
<polyline fill="none" stroke="#000000" points="939,-802.5 1172,-802.5 "/>
<text text-anchor="middle" x="1055.5" y="-787.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_survival_interval</text>
<polyline fill="none" stroke="#000000" points="939,-779.5 1172,-779.5 "/>
<text text-anchor="middle" x="1055.5" y="-764.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_withdrawn</text>
<polyline fill="none" stroke="#000000" points="939,-756.5 1172,-756.5 "/>
<text text-anchor="middle" x="1055.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">lost_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="939,-733.5 1172,-733.5 "/>
<text text-anchor="middle" x="1055.5" y="-718.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="939,-710.5 1172,-710.5 "/>
<text text-anchor="middle" x="1055.5" y="-695.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_recurrence</text>
<polyline fill="none" stroke="#000000" points="939,-687.5 1172,-687.5 "/>
<text text-anchor="middle" x="1055.5" y="-672.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="939,-664.5 1172,-664.5 "/>
<text text-anchor="middle" x="1055.5" y="-649.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_dfs_event</text>
<polyline fill="none" stroke="#000000" points="939,-641.5 1172,-641.5 "/>
<text text-anchor="middle" x="1055.5" y="-626.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="939,-618.5 1172,-618.5 "/>
<text text-anchor="middle" x="1055.5" y="-603.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_event_indicator</text>
<polyline fill="none" stroke="#000000" points="1172,-595.5 1172,-894.5 "/>
<text text-anchor="middle" x="1182.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;case -->
<g id="edge5" class="edge">
<title>survival&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1018.5,-595.4639C1018.5,-581.0383 1018.5,-566.9527 1018.5,-553.9465"/>
<polygon fill="#000000" stroke="#000000" points="1022.0001,-553.7614 1018.5,-543.7614 1015.0001,-553.7614 1022.0001,-553.7614"/>
<text text-anchor="middle" x="1045.5" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- program -->
<g id="node7" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M944,-.5C944,-.5 1141,-.5 1141,-.5 1147,-.5 1153,-6.5 1153,-12.5 1153,-12.5 1153,-34.5 1153,-34.5 1153,-40.5 1147,-46.5 1141,-46.5 1141,-46.5 944,-46.5 944,-46.5 938,-46.5 932,-40.5 932,-34.5 932,-34.5 932,-12.5 932,-12.5 932,-6.5 938,-.5 944,-.5"/>
<text text-anchor="middle" x="971" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1010,-.5 1010,-46.5 "/>
<text text-anchor="middle" x="1020.5" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1031,-.5 1031,-46.5 "/>
<text text-anchor="middle" x="1081.5" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="1031,-23.5 1132,-23.5 "/>
<text text-anchor="middle" x="1081.5" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1132,-.5 1132,-46.5 "/>
<text text-anchor="middle" x="1142.5" y="-19.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge9" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1042.5,-98.4099C1042.5,-84.6353 1042.5,-69.8024 1042.5,-56.9992"/>
<polygon fill="#000000" stroke="#000000" points="1046.0001,-56.7897 1042.5,-46.7897 1039.0001,-56.7898 1046.0001,-56.7897"/>
<text text-anchor="middle" x="1083" y="-68.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- stratification -->
<g id="node8" class="node">
<title>stratification</title>
<path fill="none" stroke="#000000" d="M1223.5,-676C1223.5,-676 1635.5,-676 1635.5,-676 1641.5,-676 1647.5,-682 1647.5,-688 1647.5,-688 1647.5,-802 1647.5,-802 1647.5,-808 1641.5,-814 1635.5,-814 1635.5,-814 1223.5,-814 1223.5,-814 1217.5,-814 1211.5,-808 1211.5,-802 1211.5,-802 1211.5,-688 1211.5,-688 1211.5,-682 1217.5,-676 1223.5,-676"/>
<text text-anchor="middle" x="1266.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification</text>
<polyline fill="none" stroke="#000000" points="1321.5,-676 1321.5,-814 "/>
<text text-anchor="middle" x="1332" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1342.5,-676 1342.5,-814 "/>
<text text-anchor="middle" x="1484.5" y="-798.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_radiotherapy</text>
<polyline fill="none" stroke="#000000" points="1342.5,-791 1626.5,-791 "/>
<text text-anchor="middle" x="1484.5" y="-775.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_chemotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="1342.5,-768 1626.5,-768 "/>
<text text-anchor="middle" x="1484.5" y="-752.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_stratification</text>
<polyline fill="none" stroke="#000000" points="1342.5,-745 1626.5,-745 "/>
<text text-anchor="middle" x="1484.5" y="-729.8" font-family="Times,serif" font-size="14.00" fill="#000000">combined_stratification_variable</text>
<polyline fill="none" stroke="#000000" points="1342.5,-722 1626.5,-722 "/>
<text text-anchor="middle" x="1484.5" y="-706.8" font-family="Times,serif" font-size="14.00" fill="#000000">grouped_recurrence_score</text>
<polyline fill="none" stroke="#000000" points="1342.5,-699 1626.5,-699 "/>
<text text-anchor="middle" x="1484.5" y="-683.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status_stratification</text>
<polyline fill="none" stroke="#000000" points="1626.5,-676 1626.5,-814 "/>
<text text-anchor="middle" x="1637" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- stratification&#45;&gt;case -->
<g id="edge3" class="edge">
<title>stratification&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1326.5629,-675.8779C1287.6287,-650.1042 1242.7598,-620.8421 1201.5,-595 1177.2501,-579.8117 1150.9411,-563.8469 1126.0331,-548.9625"/>
<polygon fill="#000000" stroke="#000000" points="1127.6682,-545.8625 1117.2869,-543.7458 1124.0824,-551.8744 1127.6682,-545.8625"/>
<text text-anchor="middle" x="1199.5" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- case&#45;&gt;study_arm -->
<g id="edge12" class="edge">
<title>case&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M878.4937,-444.7113C847.2494,-428.6968 817.9476,-406.7879 799.5,-377 788.5018,-359.2409 789.168,-348.1548 799.5,-330 811.359,-309.162 832.2019,-293.9235 853.0423,-283.1195"/>
<polygon fill="#000000" stroke="#000000" points="854.8183,-286.1471 862.265,-278.6107 851.7439,-279.8584 854.8183,-286.1471"/>
<text text-anchor="middle" x="840" y="-349.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- case&#45;&gt;cohort -->
<g id="edge6" class="edge">
<title>case&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M1018.5,-428.269C1018.5,-413.9945 1018.5,-399.1834 1018.5,-386.5462"/>
<polygon fill="#000000" stroke="#000000" points="1022.0001,-386.5017 1018.5,-376.5017 1015.0001,-386.5017 1022.0001,-386.5017"/>
<text text-anchor="middle" x="1059" y="-398.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- case&#45;&gt;study -->
<g id="edge10" class="edge">
<title>case&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1114.6987,-428.2603C1131.2059,-413.7175 1146.0598,-396.5745 1155.5,-377 1185.0477,-315.7324 1140.0006,-245.5165 1098.3282,-198.4229"/>
<polygon fill="#000000" stroke="#000000" points="1100.7172,-195.8466 1091.4133,-190.7783 1095.5259,-200.5424 1100.7172,-195.8466"/>
<text text-anchor="middle" x="1203" y="-300.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- demographic -->
<g id="node10" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M1677.5,-699C1677.5,-699 2013.5,-699 2013.5,-699 2019.5,-699 2025.5,-705 2025.5,-711 2025.5,-711 2025.5,-779 2025.5,-779 2025.5,-785 2019.5,-791 2013.5,-791 2013.5,-791 1677.5,-791 1677.5,-791 1671.5,-791 1665.5,-785 1665.5,-779 1665.5,-779 1665.5,-711 1665.5,-711 1665.5,-705 1671.5,-699 1677.5,-699"/>
<text text-anchor="middle" x="1720.5" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="1775.5,-699 1775.5,-791 "/>
<text text-anchor="middle" x="1786" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1796.5,-699 1796.5,-791 "/>
<text text-anchor="middle" x="1900.5" y="-775.8" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="1796.5,-768 2004.5,-768 "/>
<text text-anchor="middle" x="1900.5" y="-752.8" font-family="Times,serif" font-size="14.00" fill="#000000">patient_age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="1796.5,-745 2004.5,-745 "/>
<text text-anchor="middle" x="1900.5" y="-729.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status</text>
<polyline fill="none" stroke="#000000" points="1796.5,-722 2004.5,-722 "/>
<text text-anchor="middle" x="1900.5" y="-706.8" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2004.5,-699 2004.5,-791 "/>
<text text-anchor="middle" x="2015" y="-741.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;case -->
<g id="edge1" class="edge">
<title>demographic&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1800.9964,-698.8241C1765.2298,-664.6026 1711.9615,-619.7699 1656.5,-595 1571.4544,-557.0174 1329.0086,-522.5185 1168.6833,-502.9195"/>
<polygon fill="#000000" stroke="#000000" points="1169.0726,-499.4411 1158.7232,-501.7081 1168.2275,-506.3899 1169.0726,-499.4411"/>
<text text-anchor="middle" x="1621.5" y="-565.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
</g>
</svg>
</div>
