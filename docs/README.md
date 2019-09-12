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
<svg width="3619pt" height="3355pt"
 viewBox="0.00 0.00 3619.00 3355.00" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
<g id="graph0" class="graph" transform="scale(1 1) rotate(0) translate(4 3351)">
<title>Perl</title>
<polygon fill="#ffffff" stroke="transparent" points="-4,4 -4,-3351 3615,-3351 3615,4 -4,4"/>
<!-- stratification -->
<g id="node1" class="node">
<title>stratification</title>
<path fill="none" stroke="#000000" d="M12,-1497C12,-1497 424,-1497 424,-1497 430,-1497 436,-1503 436,-1509 436,-1509 436,-1623 436,-1623 436,-1629 430,-1635 424,-1635 424,-1635 12,-1635 12,-1635 6,-1635 0,-1629 0,-1623 0,-1623 0,-1509 0,-1509 0,-1503 6,-1497 12,-1497"/>
<text text-anchor="middle" x="55" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">stratification</text>
<polyline fill="none" stroke="#000000" points="110,-1497 110,-1635 "/>
<text text-anchor="middle" x="120.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="131,-1497 131,-1635 "/>
<text text-anchor="middle" x="273" y="-1619.8" font-family="Times,serif" font-size="14.00" fill="#000000">combined_stratification_variable</text>
<polyline fill="none" stroke="#000000" points="131,-1612 415,-1612 "/>
<text text-anchor="middle" x="273" y="-1596.8" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status_stratification</text>
<polyline fill="none" stroke="#000000" points="131,-1589 415,-1589 "/>
<text text-anchor="middle" x="273" y="-1573.8" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_stratification</text>
<polyline fill="none" stroke="#000000" points="131,-1566 415,-1566 "/>
<text text-anchor="middle" x="273" y="-1550.8" font-family="Times,serif" font-size="14.00" fill="#000000">grouped_recurrence_score</text>
<polyline fill="none" stroke="#000000" points="131,-1543 415,-1543 "/>
<text text-anchor="middle" x="273" y="-1527.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_chemotherapy_stratification</text>
<polyline fill="none" stroke="#000000" points="131,-1520 415,-1520 "/>
<text text-anchor="middle" x="273" y="-1504.8" font-family="Times,serif" font-size="14.00" fill="#000000">planned_radiotherapy</text>
<polyline fill="none" stroke="#000000" points="415,-1497 415,-1635 "/>
<text text-anchor="middle" x="425.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case -->
<g id="node11" class="node">
<title>case</title>
<path fill="none" stroke="#000000" d="M1612,-1180.5C1612,-1180.5 1868,-1180.5 1868,-1180.5 1874,-1180.5 1880,-1186.5 1880,-1192.5 1880,-1192.5 1880,-1283.5 1880,-1283.5 1880,-1289.5 1874,-1295.5 1868,-1295.5 1868,-1295.5 1612,-1295.5 1612,-1295.5 1606,-1295.5 1600,-1289.5 1600,-1283.5 1600,-1283.5 1600,-1192.5 1600,-1192.5 1600,-1186.5 1606,-1180.5 1612,-1180.5"/>
<text text-anchor="middle" x="1624.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">case</text>
<polyline fill="none" stroke="#000000" points="1649,-1180.5 1649,-1295.5 "/>
<text text-anchor="middle" x="1659.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1670,-1180.5 1670,-1295.5 "/>
<text text-anchor="middle" x="1764.5" y="-1280.3" font-family="Times,serif" font-size="14.00" fill="#000000">included_in_analysis</text>
<polyline fill="none" stroke="#000000" points="1670,-1272.5 1859,-1272.5 "/>
<text text-anchor="middle" x="1764.5" y="-1257.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_id</text>
<polyline fill="none" stroke="#000000" points="1670,-1249.5 1859,-1249.5 "/>
<text text-anchor="middle" x="1764.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000">case_id</text>
<polyline fill="none" stroke="#000000" points="1670,-1226.5 1859,-1226.5 "/>
<text text-anchor="middle" x="1764.5" y="-1211.3" font-family="Times,serif" font-size="14.00" fill="#000000">on_study_crf_submitted</text>
<polyline fill="none" stroke="#000000" points="1670,-1203.5 1859,-1203.5 "/>
<text text-anchor="middle" x="1764.5" y="-1188.3" font-family="Times,serif" font-size="14.00" fill="#000000">ineligible</text>
<polyline fill="none" stroke="#000000" points="1859,-1180.5 1859,-1295.5 "/>
<text text-anchor="middle" x="1869.5" y="-1234.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- stratification&#45;&gt;case -->
<g id="edge7" class="edge">
<title>stratification&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M268.0219,-1496.9444C309.2458,-1445.9222 372.5599,-1379.8478 445,-1347 547.0507,-1300.7253 1270.532,-1260.632 1589.5347,-1244.9919"/>
<polygon fill="#000000" stroke="#000000" points="1589.9651,-1248.4751 1599.7823,-1244.491 1589.6233,-1241.4834 1589.9651,-1248.4751"/>
<text text-anchor="middle" x="631" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- treatment -->
<g id="node2" class="node">
<title>treatment</title>
<path fill="none" stroke="#000000" d="M466.5,-1462.5C466.5,-1462.5 891.5,-1462.5 891.5,-1462.5 897.5,-1462.5 903.5,-1468.5 903.5,-1474.5 903.5,-1474.5 903.5,-1657.5 903.5,-1657.5 903.5,-1663.5 897.5,-1669.5 891.5,-1669.5 891.5,-1669.5 466.5,-1669.5 466.5,-1669.5 460.5,-1669.5 454.5,-1663.5 454.5,-1657.5 454.5,-1657.5 454.5,-1474.5 454.5,-1474.5 454.5,-1468.5 460.5,-1462.5 466.5,-1462.5"/>
<text text-anchor="middle" x="499" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment</text>
<polyline fill="none" stroke="#000000" points="543.5,-1462.5 543.5,-1669.5 "/>
<text text-anchor="middle" x="554" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="564.5,-1462.5 564.5,-1669.5 "/>
<text text-anchor="middle" x="723.5" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">specific_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="564.5,-1646.5 882.5,-1646.5 "/>
<text text-anchor="middle" x="723.5" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_surgical_procedure</text>
<polyline fill="none" stroke="#000000" points="564.5,-1623.5 882.5,-1623.5 "/>
<text text-anchor="middle" x="723.5" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_chemotherapy_regimen_received</text>
<polyline fill="none" stroke="#000000" points="564.5,-1600.5 882.5,-1600.5 "/>
<text text-anchor="middle" x="723.5" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">duration_of_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="564.5,-1577.5 882.5,-1577.5 "/>
<text text-anchor="middle" x="723.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">endocrine_therapy_discontinued</text>
<polyline fill="none" stroke="#000000" points="564.5,-1554.5 882.5,-1554.5 "/>
<text text-anchor="middle" x="723.5" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_endocrine_therapy_received</text>
<polyline fill="none" stroke="#000000" points="564.5,-1531.5 882.5,-1531.5 "/>
<text text-anchor="middle" x="723.5" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">received_chemotherapy</text>
<polyline fill="none" stroke="#000000" points="564.5,-1508.5 882.5,-1508.5 "/>
<text text-anchor="middle" x="723.5" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_last_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="564.5,-1485.5 882.5,-1485.5 "/>
<text text-anchor="middle" x="723.5" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">time_to_first_endocrine_therapy</text>
<polyline fill="none" stroke="#000000" points="882.5,-1462.5 882.5,-1669.5 "/>
<text text-anchor="middle" x="893" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- treatment&#45;&gt;case -->
<g id="edge8" class="edge">
<title>treatment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M763.2642,-1462.4981C803.9052,-1419.6953 856.1587,-1373.876 913,-1347 1029.6775,-1291.832 1384.7849,-1260.646 1589.7451,-1246.7906"/>
<polygon fill="#000000" stroke="#000000" points="1590.2517,-1250.2646 1599.9952,-1246.1037 1589.7835,-1243.2803 1590.2517,-1250.2646"/>
<text text-anchor="middle" x="1037" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- follow_up -->
<g id="node3" class="node">
<title>follow_up</title>
<path fill="none" stroke="#000000" d="M934,-1508.5C934,-1508.5 1266,-1508.5 1266,-1508.5 1272,-1508.5 1278,-1514.5 1278,-1520.5 1278,-1520.5 1278,-1611.5 1278,-1611.5 1278,-1617.5 1272,-1623.5 1266,-1623.5 1266,-1623.5 934,-1623.5 934,-1623.5 928,-1623.5 922,-1617.5 922,-1611.5 922,-1611.5 922,-1520.5 922,-1520.5 922,-1514.5 928,-1508.5 934,-1508.5"/>
<text text-anchor="middle" x="964.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up</text>
<polyline fill="none" stroke="#000000" points="1007,-1508.5 1007,-1623.5 "/>
<text text-anchor="middle" x="1017.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1028,-1508.5 1028,-1623.5 "/>
<text text-anchor="middle" x="1142.5" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_contact</text>
<polyline fill="none" stroke="#000000" points="1028,-1600.5 1257,-1600.5 "/>
<text text-anchor="middle" x="1142.5" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">contact_type</text>
<polyline fill="none" stroke="#000000" points="1028,-1577.5 1257,-1577.5 "/>
<text text-anchor="middle" x="1142.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">explain_unknown_status</text>
<polyline fill="none" stroke="#000000" points="1028,-1554.5 1257,-1554.5 "/>
<text text-anchor="middle" x="1142.5" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_status</text>
<polyline fill="none" stroke="#000000" points="1028,-1531.5 1257,-1531.5 "/>
<text text-anchor="middle" x="1142.5" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_since_last_contact</text>
<polyline fill="none" stroke="#000000" points="1257,-1508.5 1257,-1623.5 "/>
<text text-anchor="middle" x="1267.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- follow_up&#45;&gt;case -->
<g id="edge6" class="edge">
<title>follow_up&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1134.4652,-1508.0835C1167.3789,-1457.8638 1221.5779,-1387.1188 1287,-1347 1378.566,-1290.8489 1497.0203,-1263.6225 1589.8335,-1250.4218"/>
<polygon fill="#000000" stroke="#000000" points="1590.4478,-1253.8703 1599.8744,-1249.034 1589.4893,-1246.9362 1590.4478,-1253.8703"/>
<text text-anchor="middle" x="1370" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- enrollment -->
<g id="node4" class="node">
<title>enrollment</title>
<path fill="none" stroke="#000000" d="M1308,-1497C1308,-1497 1626,-1497 1626,-1497 1632,-1497 1638,-1503 1638,-1509 1638,-1509 1638,-1623 1638,-1623 1638,-1629 1632,-1635 1626,-1635 1626,-1635 1308,-1635 1308,-1635 1302,-1635 1296,-1629 1296,-1623 1296,-1623 1296,-1509 1296,-1509 1296,-1503 1302,-1497 1308,-1497"/>
<text text-anchor="middle" x="1343.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">enrollment</text>
<polyline fill="none" stroke="#000000" points="1391,-1497 1391,-1635 "/>
<text text-anchor="middle" x="1401.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1412,-1497 1412,-1635 "/>
<text text-anchor="middle" x="1514.5" y="-1619.8" font-family="Times,serif" font-size="14.00" fill="#000000">site_short_name</text>
<polyline fill="none" stroke="#000000" points="1412,-1612 1617,-1612 "/>
<text text-anchor="middle" x="1514.5" y="-1596.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_informed_consent</text>
<polyline fill="none" stroke="#000000" points="1412,-1589 1617,-1589 "/>
<text text-anchor="middle" x="1514.5" y="-1573.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_registration</text>
<polyline fill="none" stroke="#000000" points="1412,-1566 1617,-1566 "/>
<text text-anchor="middle" x="1514.5" y="-1550.8" font-family="Times,serif" font-size="14.00" fill="#000000">registering_institution</text>
<polyline fill="none" stroke="#000000" points="1412,-1543 1617,-1543 "/>
<text text-anchor="middle" x="1514.5" y="-1527.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="1412,-1520 1617,-1520 "/>
<text text-anchor="middle" x="1514.5" y="-1504.8" font-family="Times,serif" font-size="14.00" fill="#000000">patient_subgroup</text>
<polyline fill="none" stroke="#000000" points="1617,-1497 1617,-1635 "/>
<text text-anchor="middle" x="1627.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- enrollment&#45;&gt;case -->
<g id="edge4" class="edge">
<title>enrollment&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1523.4249,-1496.6875C1558.7372,-1453.475 1605.2902,-1396.806 1647,-1347 1658.8586,-1332.8396 1671.6616,-1317.7239 1683.8638,-1303.3984"/>
<polygon fill="#000000" stroke="#000000" points="1686.7461,-1305.4124 1690.5711,-1295.5321 1681.4195,-1300.8706 1686.7461,-1305.4124"/>
<text text-anchor="middle" x="1700" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- prior_surgery -->
<g id="node5" class="node">
<title>prior_surgery</title>
<path fill="none" stroke="#000000" d="M1494,-2374.5C1494,-2374.5 1840,-2374.5 1840,-2374.5 1846,-2374.5 1852,-2380.5 1852,-2386.5 1852,-2386.5 1852,-2500.5 1852,-2500.5 1852,-2506.5 1846,-2512.5 1840,-2512.5 1840,-2512.5 1494,-2512.5 1494,-2512.5 1488,-2512.5 1482,-2506.5 1482,-2500.5 1482,-2500.5 1482,-2386.5 1482,-2386.5 1482,-2380.5 1488,-2374.5 1494,-2374.5"/>
<text text-anchor="middle" x="1539.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_surgery</text>
<polyline fill="none" stroke="#000000" points="1597,-2374.5 1597,-2512.5 "/>
<text text-anchor="middle" x="1607.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1618,-2374.5 1618,-2512.5 "/>
<text text-anchor="middle" x="1724.5" y="-2497.3" font-family="Times,serif" font-size="14.00" fill="#000000">procedure</text>
<polyline fill="none" stroke="#000000" points="1618,-2489.5 1831,-2489.5 "/>
<text text-anchor="middle" x="1724.5" y="-2474.3" font-family="Times,serif" font-size="14.00" fill="#000000">anatomical_site_of_surgery</text>
<polyline fill="none" stroke="#000000" points="1618,-2466.5 1831,-2466.5 "/>
<text text-anchor="middle" x="1724.5" y="-2451.3" font-family="Times,serif" font-size="14.00" fill="#000000">residual_disease</text>
<polyline fill="none" stroke="#000000" points="1618,-2443.5 1831,-2443.5 "/>
<text text-anchor="middle" x="1724.5" y="-2428.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapeutic_indicator</text>
<polyline fill="none" stroke="#000000" points="1618,-2420.5 1831,-2420.5 "/>
<text text-anchor="middle" x="1724.5" y="-2405.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_finding</text>
<polyline fill="none" stroke="#000000" points="1618,-2397.5 1831,-2397.5 "/>
<text text-anchor="middle" x="1724.5" y="-2382.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_surgery</text>
<polyline fill="none" stroke="#000000" points="1831,-2374.5 1831,-2512.5 "/>
<text text-anchor="middle" x="1841.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_surgery&#45;&gt;enrollment -->
<g id="edge17" class="edge">
<title>prior_surgery&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M1651.2228,-2374.2777C1614.5505,-2213.3777 1523.7477,-1814.9805 1484.9946,-1644.9514"/>
<polygon fill="#000000" stroke="#000000" points="1488.3763,-1644.038 1482.7415,-1635.0658 1481.5513,-1645.5936 1488.3763,-1644.038"/>
<text text-anchor="middle" x="1669" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- prior_surgery&#45;&gt;prior_surgery -->
<g id="edge11" class="edge">
<title>prior_surgery&#45;&gt;prior_surgery</title>
<path fill="none" stroke="#000000" d="M1852.113,-2470.7602C1863.2907,-2464.2762 1870,-2455.1895 1870,-2443.5 1870,-2435.0982 1866.534,-2428.041 1860.434,-2422.3283"/>
<polygon fill="#000000" stroke="#000000" points="1862.2501,-2419.3204 1852.113,-2416.2398 1858.1165,-2424.9696 1862.2501,-2419.3204"/>
<text text-anchor="middle" x="1886" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- prior_therapy -->
<g id="node6" class="node">
<title>prior_therapy</title>
<path fill="none" stroke="#000000" d="M946,-2259.5C946,-2259.5 1402,-2259.5 1402,-2259.5 1408,-2259.5 1414,-2265.5 1414,-2271.5 1414,-2271.5 1414,-2615.5 1414,-2615.5 1414,-2621.5 1408,-2627.5 1402,-2627.5 1402,-2627.5 946,-2627.5 946,-2627.5 940,-2627.5 934,-2621.5 934,-2615.5 934,-2615.5 934,-2271.5 934,-2271.5 934,-2265.5 940,-2259.5 946,-2259.5"/>
<text text-anchor="middle" x="991.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy</text>
<polyline fill="none" stroke="#000000" points="1049,-2259.5 1049,-2627.5 "/>
<text text-anchor="middle" x="1059.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1070,-2259.5 1070,-2627.5 "/>
<text text-anchor="middle" x="1231.5" y="-2612.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_number_of_doses_any_therapy</text>
<polyline fill="none" stroke="#000000" points="1070,-2604.5 1393,-2604.5 "/>
<text text-anchor="middle" x="1231.5" y="-2589.3" font-family="Times,serif" font-size="14.00" fill="#000000">nonresponse_therapy_type</text>
<polyline fill="none" stroke="#000000" points="1070,-2581.5 1393,-2581.5 "/>
<text text-anchor="middle" x="1231.5" y="-2566.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose</text>
<polyline fill="none" stroke="#000000" points="1070,-2558.5 1393,-2558.5 "/>
<text text-anchor="middle" x="1231.5" y="-2543.3" font-family="Times,serif" font-size="14.00" fill="#000000">prior_therapy_type</text>
<polyline fill="none" stroke="#000000" points="1070,-2535.5 1393,-2535.5 "/>
<text text-anchor="middle" x="1231.5" y="-2520.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_last_dose_any_therapy</text>
<polyline fill="none" stroke="#000000" points="1070,-2512.5 1393,-2512.5 "/>
<text text-anchor="middle" x="1231.5" y="-2497.3" font-family="Times,serif" font-size="14.00" fill="#000000">number_of_prior_regimens_any_therapy</text>
<polyline fill="none" stroke="#000000" points="1070,-2489.5 1393,-2489.5 "/>
<text text-anchor="middle" x="1231.5" y="-2474.3" font-family="Times,serif" font-size="14.00" fill="#000000">best_response</text>
<polyline fill="none" stroke="#000000" points="1070,-2466.5 1393,-2466.5 "/>
<text text-anchor="middle" x="1231.5" y="-2451.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_at_site</text>
<polyline fill="none" stroke="#000000" points="1070,-2443.5 1393,-2443.5 "/>
<text text-anchor="middle" x="1231.5" y="-2428.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_performed_in_minimal_residual</text>
<polyline fill="none" stroke="#000000" points="1070,-2420.5 1393,-2420.5 "/>
<text text-anchor="middle" x="1231.5" y="-2405.3" font-family="Times,serif" font-size="14.00" fill="#000000">any_therapy</text>
<polyline fill="none" stroke="#000000" points="1070,-2397.5 1393,-2397.5 "/>
<text text-anchor="middle" x="1231.5" y="-2382.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_dose</text>
<polyline fill="none" stroke="#000000" points="1070,-2374.5 1393,-2374.5 "/>
<text text-anchor="middle" x="1231.5" y="-2359.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_schedule</text>
<polyline fill="none" stroke="#000000" points="1070,-2351.5 1393,-2351.5 "/>
<text text-anchor="middle" x="1231.5" y="-2336.3" font-family="Times,serif" font-size="14.00" fill="#000000">therapy_type</text>
<polyline fill="none" stroke="#000000" points="1070,-2328.5 1393,-2328.5 "/>
<text text-anchor="middle" x="1231.5" y="-2313.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_name</text>
<polyline fill="none" stroke="#000000" points="1070,-2305.5 1393,-2305.5 "/>
<text text-anchor="middle" x="1231.5" y="-2290.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_first_dose</text>
<polyline fill="none" stroke="#000000" points="1070,-2282.5 1393,-2282.5 "/>
<text text-anchor="middle" x="1231.5" y="-2267.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="1393,-2259.5 1393,-2627.5 "/>
<text text-anchor="middle" x="1403.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- prior_therapy&#45;&gt;enrollment -->
<g id="edge16" class="edge">
<title>prior_therapy&#45;&gt;enrollment</title>
<path fill="none" stroke="#000000" d="M1235.5117,-2259.2799C1298.9393,-2069.3216 1394.8574,-1782.0584 1440.7417,-1644.6404"/>
<polygon fill="#000000" stroke="#000000" points="1444.1104,-1645.6023 1443.9578,-1635.0086 1437.4708,-1643.3853 1444.1104,-1645.6023"/>
<text text-anchor="middle" x="1431" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">at_enrollment</text>
</g>
<!-- prior_therapy&#45;&gt;prior_therapy -->
<g id="edge12" class="edge">
<title>prior_therapy&#45;&gt;prior_therapy</title>
<path fill="none" stroke="#000000" d="M1414.2384,-2468.2536C1425.4387,-2462.0051 1432,-2453.7539 1432,-2443.5 1432,-2436.13 1428.6104,-2429.7946 1422.545,-2424.4938"/>
<polygon fill="#000000" stroke="#000000" points="1424.4534,-2421.5581 1414.2384,-2418.7464 1420.4704,-2427.3146 1424.4534,-2421.5581"/>
<text text-anchor="middle" x="1448" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- assay -->
<g id="node7" class="node">
<title>assay</title>
<path fill="none" stroke="#000000" d="M2231,-2425.5C2231,-2425.5 2263,-2425.5 2263,-2425.5 2269,-2425.5 2275,-2431.5 2275,-2437.5 2275,-2437.5 2275,-2449.5 2275,-2449.5 2275,-2455.5 2269,-2461.5 2263,-2461.5 2263,-2461.5 2231,-2461.5 2231,-2461.5 2225,-2461.5 2219,-2455.5 2219,-2449.5 2219,-2449.5 2219,-2437.5 2219,-2437.5 2219,-2431.5 2225,-2425.5 2231,-2425.5"/>
<text text-anchor="middle" x="2247" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">assay</text>
</g>
<!-- sample -->
<g id="node24" class="node">
<title>sample</title>
<path fill="none" stroke="#000000" d="M2035.5,-1347.5C2035.5,-1347.5 2458.5,-1347.5 2458.5,-1347.5 2464.5,-1347.5 2470.5,-1353.5 2470.5,-1359.5 2470.5,-1359.5 2470.5,-1772.5 2470.5,-1772.5 2470.5,-1778.5 2464.5,-1784.5 2458.5,-1784.5 2458.5,-1784.5 2035.5,-1784.5 2035.5,-1784.5 2029.5,-1784.5 2023.5,-1778.5 2023.5,-1772.5 2023.5,-1772.5 2023.5,-1359.5 2023.5,-1359.5 2023.5,-1353.5 2029.5,-1347.5 2035.5,-1347.5"/>
<text text-anchor="middle" x="2057.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample</text>
<polyline fill="none" stroke="#000000" points="2091.5,-1347.5 2091.5,-1784.5 "/>
<text text-anchor="middle" x="2102" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2112.5,-1347.5 2112.5,-1784.5 "/>
<text text-anchor="middle" x="2281" y="-1769.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_tumor</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1761.5 2449.5,-1761.5 "/>
<text text-anchor="middle" x="2281" y="-1746.3" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1738.5 2449.5,-1738.5 "/>
<text text-anchor="middle" x="2281" y="-1723.3" font-family="Times,serif" font-size="14.00" fill="#000000">non_tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1715.5 2449.5,-1715.5 "/>
<text text-anchor="middle" x="2281" y="-1700.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_sample_collection</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1692.5 2449.5,-1692.5 "/>
<text text-anchor="middle" x="2281" y="-1677.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_status_date</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1669.5 2449.5,-1669.5 "/>
<text text-anchor="middle" x="2281" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1646.5 2449.5,-1646.5 "/>
<text text-anchor="middle" x="2281" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">necropsy_sample</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1623.5 2449.5,-1623.5 "/>
<text text-anchor="middle" x="2281" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_pigmented_tumor</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1600.5 2449.5,-1600.5 "/>
<text text-anchor="middle" x="2281" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_stroma</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1577.5 2449.5,-1577.5 "/>
<text text-anchor="middle" x="2281" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1554.5 2449.5,-1554.5 "/>
<text text-anchor="middle" x="2281" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">total_tissue_area</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1531.5 2449.5,-1531.5 "/>
<text text-anchor="middle" x="2281" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">width_of_tumor</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1508.5 2449.5,-1508.5 "/>
<text text-anchor="middle" x="2281" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1485.5 2449.5,-1485.5 "/>
<text text-anchor="middle" x="2281" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">general_sample_pathology</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1462.5 2449.5,-1462.5 "/>
<text text-anchor="middle" x="2281" y="-1447.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_type</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1439.5 2449.5,-1439.5 "/>
<text text-anchor="middle" x="2281" y="-1424.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_tissue_area</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1416.5 2449.5,-1416.5 "/>
<text text-anchor="middle" x="2281" y="-1401.3" font-family="Times,serif" font-size="14.00" fill="#000000">sample_id</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1393.5 2449.5,-1393.5 "/>
<text text-anchor="middle" x="2281" y="-1378.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_tumor</text>
<polyline fill="none" stroke="#000000" points="2112.5,-1370.5 2449.5,-1370.5 "/>
<text text-anchor="middle" x="2281" y="-1355.3" font-family="Times,serif" font-size="14.00" fill="#000000">analysis_area_percentage_glass</text>
<polyline fill="none" stroke="#000000" points="2449.5,-1347.5 2449.5,-1784.5 "/>
<text text-anchor="middle" x="2460" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- assay&#45;&gt;sample -->
<g id="edge29" class="edge">
<title>assay&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2247,-2425.1722C2247,-2345.2645 2247,-2021.2117 2247,-1794.7844"/>
<polygon fill="#000000" stroke="#000000" points="2250.5001,-1794.7519 2247,-1784.7519 2243.5001,-1794.752 2250.5001,-1794.7519"/>
<text text-anchor="middle" x="2283.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- adverse_event -->
<g id="node8" class="node">
<title>adverse_event</title>
<path fill="none" stroke="#000000" d="M1712.5,-818C1712.5,-818 2107.5,-818 2107.5,-818 2113.5,-818 2119.5,-824 2119.5,-830 2119.5,-830 2119.5,-1036 2119.5,-1036 2119.5,-1042 2113.5,-1048 2107.5,-1048 2107.5,-1048 1712.5,-1048 1712.5,-1048 1706.5,-1048 1700.5,-1042 1700.5,-1036 1700.5,-1036 1700.5,-830 1700.5,-830 1700.5,-824 1706.5,-818 1712.5,-818"/>
<text text-anchor="middle" x="1760.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event</text>
<polyline fill="none" stroke="#000000" points="1820.5,-818 1820.5,-1048 "/>
<text text-anchor="middle" x="1831" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1841.5,-818 1841.5,-1048 "/>
<text text-anchor="middle" x="1970" y="-1032.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_description</text>
<polyline fill="none" stroke="#000000" points="1841.5,-1025 2098.5,-1025 "/>
<text text-anchor="middle" x="1970" y="-1009.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_other</text>
<polyline fill="none" stroke="#000000" points="1841.5,-1002 2098.5,-1002 "/>
<text text-anchor="middle" x="1970" y="-986.8" font-family="Times,serif" font-size="14.00" fill="#000000">unexpected_adverse_event</text>
<polyline fill="none" stroke="#000000" points="1841.5,-979 2098.5,-979 "/>
<text text-anchor="middle" x="1970" y="-963.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade</text>
<polyline fill="none" stroke="#000000" points="1841.5,-956 2098.5,-956 "/>
<text text-anchor="middle" x="1970" y="-940.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_agent_name</text>
<polyline fill="none" stroke="#000000" points="1841.5,-933 2098.5,-933 "/>
<text text-anchor="middle" x="1970" y="-917.8" font-family="Times,serif" font-size="14.00" fill="#000000">date_resolved</text>
<polyline fill="none" stroke="#000000" points="1841.5,-910 2098.5,-910 "/>
<text text-anchor="middle" x="1970" y="-894.8" font-family="Times,serif" font-size="14.00" fill="#000000">ae_dose</text>
<polyline fill="none" stroke="#000000" points="1841.5,-887 2098.5,-887 "/>
<text text-anchor="middle" x="1970" y="-871.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_attribution</text>
<polyline fill="none" stroke="#000000" points="1841.5,-864 2098.5,-864 "/>
<text text-anchor="middle" x="1970" y="-848.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_grade_description</text>
<polyline fill="none" stroke="#000000" points="1841.5,-841 2098.5,-841 "/>
<text text-anchor="middle" x="1970" y="-825.8" font-family="Times,serif" font-size="14.00" fill="#000000">adverse_event_term</text>
<polyline fill="none" stroke="#000000" points="2098.5,-818 2098.5,-1048 "/>
<text text-anchor="middle" x="2109" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- adverse_event&#45;&gt;adverse_event -->
<g id="edge13" class="edge">
<title>adverse_event&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M2119.7046,-960.2761C2130.876,-953.5862 2137.5,-944.4941 2137.5,-933 2137.5,-924.7386 2134.0781,-917.7181 2128.0052,-911.9385"/>
<polygon fill="#000000" stroke="#000000" points="2129.8073,-908.9155 2119.7046,-905.7239 2125.6119,-914.519 2129.8073,-908.9155"/>
<text text-anchor="middle" x="2153.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- agent -->
<g id="node25" class="node">
<title>agent</title>
<path fill="none" stroke="#000000" d="M1824.5,-644.5C1824.5,-644.5 1995.5,-644.5 1995.5,-644.5 2001.5,-644.5 2007.5,-650.5 2007.5,-656.5 2007.5,-656.5 2007.5,-668.5 2007.5,-668.5 2007.5,-674.5 2001.5,-680.5 1995.5,-680.5 1995.5,-680.5 1824.5,-680.5 1824.5,-680.5 1818.5,-680.5 1812.5,-674.5 1812.5,-668.5 1812.5,-668.5 1812.5,-656.5 1812.5,-656.5 1812.5,-650.5 1818.5,-644.5 1824.5,-644.5"/>
<text text-anchor="middle" x="1841" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">agent</text>
<polyline fill="none" stroke="#000000" points="1869.5,-644.5 1869.5,-680.5 "/>
<text text-anchor="middle" x="1880" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1890.5,-644.5 1890.5,-680.5 "/>
<text text-anchor="middle" x="1938.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="1986.5,-644.5 1986.5,-680.5 "/>
<text text-anchor="middle" x="1997" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- adverse_event&#45;&gt;agent -->
<g id="edge27" class="edge">
<title>adverse_event&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M1910,-817.8914C1910,-771.2747 1910,-721.3926 1910,-691.0697"/>
<polygon fill="#000000" stroke="#000000" points="1913.5001,-690.8252 1910,-680.8252 1906.5001,-690.8253 1913.5001,-690.8252"/>
<text text-anchor="middle" x="1941" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- study -->
<g id="node9" class="node">
<title>study</title>
<path fill="none" stroke="#000000" d="M1770,-236.5C1770,-236.5 2050,-236.5 2050,-236.5 2056,-236.5 2062,-242.5 2062,-248.5 2062,-248.5 2062,-454.5 2062,-454.5 2062,-460.5 2056,-466.5 2050,-466.5 2050,-466.5 1770,-466.5 1770,-466.5 1764,-466.5 1758,-460.5 1758,-454.5 1758,-454.5 1758,-248.5 1758,-248.5 1758,-242.5 1764,-236.5 1770,-236.5"/>
<text text-anchor="middle" x="1786" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000">study</text>
<polyline fill="none" stroke="#000000" points="1814,-236.5 1814,-466.5 "/>
<text text-anchor="middle" x="1824.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1835,-236.5 1835,-466.5 "/>
<text text-anchor="middle" x="1938" y="-451.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_term</text>
<polyline fill="none" stroke="#000000" points="1835,-443.5 2041,-443.5 "/>
<text text-anchor="middle" x="1938" y="-428.3" font-family="Times,serif" font-size="14.00" fill="#000000">dates_of_conduct</text>
<polyline fill="none" stroke="#000000" points="1835,-420.5 2041,-420.5 "/>
<text text-anchor="middle" x="1938" y="-405.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_description</text>
<polyline fill="none" stroke="#000000" points="1835,-397.5 2041,-397.5 "/>
<text text-anchor="middle" x="1938" y="-382.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_id</text>
<polyline fill="none" stroke="#000000" points="1835,-374.5 2041,-374.5 "/>
<text text-anchor="middle" x="1938" y="-359.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_type</text>
<polyline fill="none" stroke="#000000" points="1835,-351.5 2041,-351.5 "/>
<text text-anchor="middle" x="1938" y="-336.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_category</text>
<polyline fill="none" stroke="#000000" points="1835,-328.5 2041,-328.5 "/>
<text text-anchor="middle" x="1938" y="-313.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_su_category</text>
<polyline fill="none" stroke="#000000" points="1835,-305.5 2041,-305.5 "/>
<text text-anchor="middle" x="1938" y="-290.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_name</text>
<polyline fill="none" stroke="#000000" points="1835,-282.5 2041,-282.5 "/>
<text text-anchor="middle" x="1938" y="-267.3" font-family="Times,serif" font-size="14.00" fill="#000000">clinical_study_designation</text>
<polyline fill="none" stroke="#000000" points="1835,-259.5 2041,-259.5 "/>
<text text-anchor="middle" x="1938" y="-244.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_iacuc_approval</text>
<polyline fill="none" stroke="#000000" points="2041,-236.5 2041,-466.5 "/>
<text text-anchor="middle" x="2051.5" y="-347.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- program -->
<g id="node21" class="node">
<title>program</title>
<path fill="none" stroke="#000000" d="M1756,-.5C1756,-.5 2064,-.5 2064,-.5 2070,-.5 2076,-6.5 2076,-12.5 2076,-12.5 2076,-172.5 2076,-172.5 2076,-178.5 2070,-184.5 2064,-184.5 2064,-184.5 1756,-184.5 1756,-184.5 1750,-184.5 1744,-178.5 1744,-172.5 1744,-172.5 1744,-12.5 1744,-12.5 1744,-6.5 1750,-.5 1756,-.5"/>
<text text-anchor="middle" x="1783" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000">program</text>
<polyline fill="none" stroke="#000000" points="1822,-.5 1822,-184.5 "/>
<text text-anchor="middle" x="1832.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1843,-.5 1843,-184.5 "/>
<text text-anchor="middle" x="1949" y="-169.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_full_description</text>
<polyline fill="none" stroke="#000000" points="1843,-161.5 2055,-161.5 "/>
<text text-anchor="middle" x="1949" y="-146.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_sort_order</text>
<polyline fill="none" stroke="#000000" points="1843,-138.5 2055,-138.5 "/>
<text text-anchor="middle" x="1949" y="-123.3" font-family="Times,serif" font-size="14.00" fill="#000000">name</text>
<polyline fill="none" stroke="#000000" points="1843,-115.5 2055,-115.5 "/>
<text text-anchor="middle" x="1949" y="-100.3" font-family="Times,serif" font-size="14.00" fill="#000000">short_name</text>
<polyline fill="none" stroke="#000000" points="1843,-92.5 2055,-92.5 "/>
<text text-anchor="middle" x="1949" y="-77.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_external_url</text>
<polyline fill="none" stroke="#000000" points="1843,-69.5 2055,-69.5 "/>
<text text-anchor="middle" x="1949" y="-54.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_short_description</text>
<polyline fill="none" stroke="#000000" points="1843,-46.5 2055,-46.5 "/>
<text text-anchor="middle" x="1949" y="-31.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_name</text>
<polyline fill="none" stroke="#000000" points="1843,-23.5 2055,-23.5 "/>
<text text-anchor="middle" x="1949" y="-8.3" font-family="Times,serif" font-size="14.00" fill="#000000">program_acronym</text>
<polyline fill="none" stroke="#000000" points="2055,-.5 2055,-184.5 "/>
<text text-anchor="middle" x="2065.5" y="-88.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- study&#45;&gt;program -->
<g id="edge22" class="edge">
<title>study&#45;&gt;program</title>
<path fill="none" stroke="#000000" d="M1910,-236.3905C1910,-222.6101 1910,-208.6095 1910,-195.0235"/>
<polygon fill="#000000" stroke="#000000" points="1913.5001,-194.7254 1910,-184.7255 1906.5001,-194.7255 1913.5001,-194.7254"/>
<text text-anchor="middle" x="1950.5" y="-206.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- survival -->
<g id="node10" class="node">
<title>survival</title>
<path fill="none" stroke="#000000" d="M1668.5,-1416.5C1668.5,-1416.5 1993.5,-1416.5 1993.5,-1416.5 1999.5,-1416.5 2005.5,-1422.5 2005.5,-1428.5 2005.5,-1428.5 2005.5,-1703.5 2005.5,-1703.5 2005.5,-1709.5 1999.5,-1715.5 1993.5,-1715.5 1993.5,-1715.5 1668.5,-1715.5 1668.5,-1715.5 1662.5,-1715.5 1656.5,-1709.5 1656.5,-1703.5 1656.5,-1703.5 1656.5,-1428.5 1656.5,-1428.5 1656.5,-1422.5 1662.5,-1416.5 1668.5,-1416.5"/>
<text text-anchor="middle" x="1693.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival</text>
<polyline fill="none" stroke="#000000" points="1730.5,-1416.5 1730.5,-1715.5 "/>
<text text-anchor="middle" x="1741" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1751.5,-1416.5 1751.5,-1715.5 "/>
<text text-anchor="middle" x="1868" y="-1700.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1692.5 1984.5,-1692.5 "/>
<text text-anchor="middle" x="1868" y="-1677.3" font-family="Times,serif" font-size="14.00" fill="#000000">length_of_survival</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1669.5 1984.5,-1669.5 "/>
<text text-anchor="middle" x="1868" y="-1654.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_dfs_event</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1646.5 1984.5,-1646.5 "/>
<text text-anchor="middle" x="1868" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">survival_status</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1623.5 1984.5,-1623.5 "/>
<text text-anchor="middle" x="1868" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_indicator</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1600.5 1984.5,-1600.5 "/>
<text text-anchor="middle" x="1868" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">cause_of_death</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1577.5 1984.5,-1577.5 "/>
<text text-anchor="middle" x="1868" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_survival_interval</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1554.5 1984.5,-1554.5 "/>
<text text-anchor="middle" x="1868" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">consent_withdrawn</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1531.5 1984.5,-1531.5 "/>
<text text-anchor="middle" x="1868" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_free_event_indicator</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1508.5 1984.5,-1508.5 "/>
<text text-anchor="middle" x="1868" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">distant_recurrence_interval</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1485.5 1984.5,-1485.5 "/>
<text text-anchor="middle" x="1868" y="-1470.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_free_interval</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1462.5 1984.5,-1462.5 "/>
<text text-anchor="middle" x="1868" y="-1447.3" font-family="Times,serif" font-size="14.00" fill="#000000">lost_to_follow_up</text>
<polyline fill="none" stroke="#000000" points="1751.5,-1439.5 1984.5,-1439.5 "/>
<text text-anchor="middle" x="1868" y="-1424.3" font-family="Times,serif" font-size="14.00" fill="#000000">type_of_first_recurrence</text>
<polyline fill="none" stroke="#000000" points="1984.5,-1416.5 1984.5,-1715.5 "/>
<text text-anchor="middle" x="1995" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- survival&#45;&gt;case -->
<g id="edge9" class="edge">
<title>survival&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M1789.4944,-1416.3976C1778.7043,-1377.5055 1767.6121,-1337.5251 1758.6706,-1305.2961"/>
<polygon fill="#000000" stroke="#000000" points="1762.0134,-1304.2529 1755.9673,-1295.5526 1755.2682,-1306.1244 1762.0134,-1304.2529"/>
<text text-anchor="middle" x="1792" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- case&#45;&gt;adverse_event -->
<g id="edge1" class="edge">
<title>case&#45;&gt;adverse_event</title>
<path fill="none" stroke="#000000" d="M1772.1756,-1180.2733C1791.5824,-1145.455 1817.076,-1099.7166 1840.8536,-1057.0569"/>
<polygon fill="#000000" stroke="#000000" points="1843.9295,-1058.7272 1845.7409,-1048.2883 1837.8151,-1055.3191 1843.9295,-1058.7272"/>
<text text-anchor="middle" x="1860" y="-1150.8" font-family="Times,serif" font-size="14.00" fill="#000000">had_adverse_event</text>
</g>
<!-- case&#45;&gt;study -->
<g id="edge20" class="edge">
<title>case&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1682.1272,-1180.3245C1630.83,-1122.839 1564,-1029.4405 1564,-933 1564,-933 1564,-933 1564,-553 1564,-460.1924 1658.1078,-409.3821 1748.1643,-382.0064"/>
<polygon fill="#000000" stroke="#000000" points="1749.3878,-385.2946 1757.9876,-379.1064 1747.4058,-378.5811 1749.3878,-385.2946"/>
<text text-anchor="middle" x="1604.5" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- study_arm -->
<g id="node12" class="node">
<title>study_arm</title>
<path fill="none" stroke="#000000" d="M1725.5,-518.5C1725.5,-518.5 2094.5,-518.5 2094.5,-518.5 2100.5,-518.5 2106.5,-524.5 2106.5,-530.5 2106.5,-530.5 2106.5,-575.5 2106.5,-575.5 2106.5,-581.5 2100.5,-587.5 2094.5,-587.5 2094.5,-587.5 1725.5,-587.5 1725.5,-587.5 1719.5,-587.5 1713.5,-581.5 1713.5,-575.5 1713.5,-575.5 1713.5,-530.5 1713.5,-530.5 1713.5,-524.5 1719.5,-518.5 1725.5,-518.5"/>
<text text-anchor="middle" x="1759.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">study_arm</text>
<polyline fill="none" stroke="#000000" points="1805.5,-518.5 1805.5,-587.5 "/>
<text text-anchor="middle" x="1816" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="1826.5,-518.5 1826.5,-587.5 "/>
<text text-anchor="middle" x="1956" y="-572.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_arm_version</text>
<polyline fill="none" stroke="#000000" points="1826.5,-564.5 2085.5,-564.5 "/>
<text text-anchor="middle" x="1956" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm</text>
<polyline fill="none" stroke="#000000" points="1826.5,-541.5 2085.5,-541.5 "/>
<text text-anchor="middle" x="1956" y="-526.3" font-family="Times,serif" font-size="14.00" fill="#000000">ctep_treatment_assignment_code</text>
<polyline fill="none" stroke="#000000" points="2085.5,-518.5 2085.5,-587.5 "/>
<text text-anchor="middle" x="2096" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;study_arm -->
<g id="edge19" class="edge">
<title>case&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1708.6958,-1180.4355C1701.4201,-1164.2626 1694.7194,-1146.3451 1691,-1129 1654.471,-958.6503 1619.0085,-895.6525 1691,-737 1719.8057,-673.5189 1782.8717,-624.3306 1833.9628,-592.8484"/>
<polygon fill="#000000" stroke="#000000" points="1835.9557,-595.7334 1842.7006,-587.563 1832.3327,-589.7439 1835.9557,-595.7334"/>
<text text-anchor="middle" x="1749.5" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort -->
<g id="node22" class="node">
<title>cohort</title>
<path fill="none" stroke="#000000" d="M2037.5,-639.5C2037.5,-639.5 2270.5,-639.5 2270.5,-639.5 2276.5,-639.5 2282.5,-645.5 2282.5,-651.5 2282.5,-651.5 2282.5,-673.5 2282.5,-673.5 2282.5,-679.5 2276.5,-685.5 2270.5,-685.5 2270.5,-685.5 2037.5,-685.5 2037.5,-685.5 2031.5,-685.5 2025.5,-679.5 2025.5,-673.5 2025.5,-673.5 2025.5,-651.5 2025.5,-651.5 2025.5,-645.5 2031.5,-639.5 2037.5,-639.5"/>
<text text-anchor="middle" x="2057" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000">cohort</text>
<polyline fill="none" stroke="#000000" points="2088.5,-639.5 2088.5,-685.5 "/>
<text text-anchor="middle" x="2099" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2109.5,-639.5 2109.5,-685.5 "/>
<text text-anchor="middle" x="2185.5" y="-670.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_dose</text>
<polyline fill="none" stroke="#000000" points="2109.5,-662.5 2261.5,-662.5 "/>
<text text-anchor="middle" x="2185.5" y="-647.3" font-family="Times,serif" font-size="14.00" fill="#000000">cohort_description</text>
<polyline fill="none" stroke="#000000" points="2261.5,-639.5 2261.5,-685.5 "/>
<text text-anchor="middle" x="2272" y="-658.8" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- case&#45;&gt;cohort -->
<g id="edge21" class="edge">
<title>case&#45;&gt;cohort</title>
<path fill="none" stroke="#000000" d="M1880.456,-1232.0249C2131.748,-1219.8835 2637.1001,-1188.3165 2690,-1129 2805.96,-998.9744 2804.3999,-868.4004 2690,-737 2664.1819,-707.3452 2442.9299,-684.6171 2292.8805,-672.4374"/>
<polygon fill="#000000" stroke="#000000" points="2292.902,-668.9279 2282.6535,-671.6146 2292.3405,-675.9053 2292.902,-668.9279"/>
<text text-anchor="middle" x="2816.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge10" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1878.2748,-518.3873C1874.4789,-512.5972 1871.1814,-506.3849 1869,-500 1866.4161,-492.4368 1864.994,-484.6159 1864.4979,-476.7004"/>
<polygon fill="#000000" stroke="#000000" points="1867.9966,-476.5823 1864.3468,-466.636 1860.9974,-476.6874 1867.9966,-476.5823"/>
<text text-anchor="middle" x="1899.5" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study</text>
</g>
<!-- study_arm&#45;&gt;study -->
<g id="edge18" class="edge">
<title>study_arm&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M1925.0667,-518.4428C1927.1124,-512.4004 1928.8882,-506.0953 1930,-500 1931.3632,-492.5264 1932.1551,-484.8255 1932.4884,-477.0463"/>
<polygon fill="#000000" stroke="#000000" points="1935.9924,-476.8482 1932.6717,-466.7873 1928.9935,-476.7231 1935.9924,-476.8482"/>
<text text-anchor="middle" x="1972.5" y="-488.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- variant -->
<g id="node13" class="node">
<title>variant</title>
<path fill="none" stroke="#000000" d="M2704.5,-2679.5C2704.5,-2679.5 3029.5,-2679.5 3029.5,-2679.5 3035.5,-2679.5 3041.5,-2685.5 3041.5,-2691.5 3041.5,-2691.5 3041.5,-3334.5 3041.5,-3334.5 3041.5,-3340.5 3035.5,-3346.5 3029.5,-3346.5 3029.5,-3346.5 2704.5,-3346.5 2704.5,-3346.5 2698.5,-3346.5 2692.5,-3340.5 2692.5,-3334.5 2692.5,-3334.5 2692.5,-2691.5 2692.5,-2691.5 2692.5,-2685.5 2698.5,-2679.5 2704.5,-2679.5"/>
<text text-anchor="middle" x="2726.5" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant</text>
<polyline fill="none" stroke="#000000" points="2760.5,-2679.5 2760.5,-3346.5 "/>
<text text-anchor="middle" x="2771" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2781.5,-2679.5 2781.5,-3346.5 "/>
<text text-anchor="middle" x="2901" y="-3331.3" font-family="Times,serif" font-size="14.00" fill="#000000">read_depth</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3323.5 3020.5,-3323.5 "/>
<text text-anchor="middle" x="2901" y="-3308.3" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id_analysis_id</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3300.5 3020.5,-3300.5 "/>
<text text-anchor="middle" x="2901" y="-3285.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_alt</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3277.5 3020.5,-3277.5 "/>
<text text-anchor="middle" x="2901" y="-3262.3" font-family="Times,serif" font-size="14.00" fill="#000000">allele_frequency</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3254.5 3020.5,-3254.5 "/>
<text text-anchor="middle" x="2901" y="-3239.3" font-family="Times,serif" font-size="14.00" fill="#000000">hgvs</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3231.5 3020.5,-3231.5 "/>
<text text-anchor="middle" x="2901" y="-3216.3" font-family="Times,serif" font-size="14.00" fill="#000000">variant_type</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3208.5 3020.5,-3208.5 "/>
<text text-anchor="middle" x="2901" y="-3193.3" font-family="Times,serif" font-size="14.00" fill="#000000">ref_copy_number</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3185.5 3020.5,-3185.5 "/>
<text text-anchor="middle" x="2901" y="-3170.3" font-family="Times,serif" font-size="14.00" fill="#000000">function</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3162.5 3020.5,-3162.5 "/>
<text text-anchor="middle" x="2901" y="-3147.3" font-family="Times,serif" font-size="14.00" fill="#000000">raw_copy_number</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3139.5 3020.5,-3139.5 "/>
<text text-anchor="middle" x="2901" y="-3124.3" font-family="Times,serif" font-size="14.00" fill="#000000">confirmed</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3116.5 3020.5,-3116.5 "/>
<text text-anchor="middle" x="2901" y="-3101.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_95percent</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3093.5 3020.5,-3093.5 "/>
<text text-anchor="middle" x="2901" y="-3078.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_ref</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3070.5 3020.5,-3070.5 "/>
<text text-anchor="middle" x="2901" y="-3055.3" font-family="Times,serif" font-size="14.00" fill="#000000">exon</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3047.5 3020.5,-3047.5 "/>
<text text-anchor="middle" x="2901" y="-3032.3" font-family="Times,serif" font-size="14.00" fill="#000000">gene_name</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3024.5 3020.5,-3024.5 "/>
<text text-anchor="middle" x="2901" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">alternative_allele</text>
<polyline fill="none" stroke="#000000" points="2781.5,-3001.5 3020.5,-3001.5 "/>
<text text-anchor="middle" x="2901" y="-2986.3" font-family="Times,serif" font-size="14.00" fill="#000000">position</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2978.5 3020.5,-2978.5 "/>
<text text-anchor="middle" x="2901" y="-2963.3" font-family="Times,serif" font-size="14.00" fill="#000000">strand</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2955.5 3020.5,-2955.5 "/>
<text text-anchor="middle" x="2901" y="-2940.3" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2932.5 3020.5,-2932.5 "/>
<text text-anchor="middle" x="2901" y="-2917.3" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2909.5 3020.5,-2909.5 "/>
<text text-anchor="middle" x="2901" y="-2894.3" font-family="Times,serif" font-size="14.00" fill="#000000">aMOI</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2886.5 3020.5,-2886.5 "/>
<text text-anchor="middle" x="2901" y="-2871.3" font-family="Times,serif" font-size="14.00" fill="#000000">arm_specific</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2863.5 3020.5,-2863.5 "/>
<text text-anchor="middle" x="2901" y="-2848.3" font-family="Times,serif" font-size="14.00" fill="#000000">ocp_ref</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2840.5 3020.5,-2840.5 "/>
<text text-anchor="middle" x="2901" y="-2825.3" font-family="Times,serif" font-size="14.00" fill="#000000">copy_number</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2817.5 3020.5,-2817.5 "/>
<text text-anchor="middle" x="2901" y="-2802.3" font-family="Times,serif" font-size="14.00" fill="#000000">protein</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2794.5 3020.5,-2794.5 "/>
<text text-anchor="middle" x="2901" y="-2779.3" font-family="Times,serif" font-size="14.00" fill="#000000">cds_alt</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2771.5 3020.5,-2771.5 "/>
<text text-anchor="middle" x="2901" y="-2756.3" font-family="Times,serif" font-size="14.00" fill="#000000">chromosome</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2748.5 3020.5,-2748.5 "/>
<text text-anchor="middle" x="2901" y="-2733.3" font-family="Times,serif" font-size="14.00" fill="#000000">genome_reference</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2725.5 3020.5,-2725.5 "/>
<text text-anchor="middle" x="2901" y="-2710.3" font-family="Times,serif" font-size="14.00" fill="#000000">confidence_interval_05percent</text>
<polyline fill="none" stroke="#000000" points="2781.5,-2702.5 3020.5,-2702.5 "/>
<text text-anchor="middle" x="2901" y="-2687.3" font-family="Times,serif" font-size="14.00" fill="#000000">transcript</text>
<polyline fill="none" stroke="#000000" points="3020.5,-2679.5 3020.5,-3346.5 "/>
<text text-anchor="middle" x="3031" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file -->
<g id="node14" class="node">
<title>file</title>
<path fill="none" stroke="#000000" d="M2477.5,-2909.5C2477.5,-2909.5 2662.5,-2909.5 2662.5,-2909.5 2668.5,-2909.5 2674.5,-2915.5 2674.5,-2921.5 2674.5,-2921.5 2674.5,-3104.5 2674.5,-3104.5 2674.5,-3110.5 2668.5,-3116.5 2662.5,-3116.5 2662.5,-3116.5 2477.5,-3116.5 2477.5,-3116.5 2471.5,-3116.5 2465.5,-3110.5 2465.5,-3104.5 2465.5,-3104.5 2465.5,-2921.5 2465.5,-2921.5 2465.5,-2915.5 2471.5,-2909.5 2477.5,-2909.5"/>
<text text-anchor="middle" x="2485" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">file</text>
<polyline fill="none" stroke="#000000" points="2504.5,-2909.5 2504.5,-3116.5 "/>
<text text-anchor="middle" x="2515" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2525.5,-2909.5 2525.5,-3116.5 "/>
<text text-anchor="middle" x="2589.5" y="-3101.3" font-family="Times,serif" font-size="14.00" fill="#000000">md5sum</text>
<polyline fill="none" stroke="#000000" points="2525.5,-3093.5 2653.5,-3093.5 "/>
<text text-anchor="middle" x="2589.5" y="-3078.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_size</text>
<polyline fill="none" stroke="#000000" points="2525.5,-3070.5 2653.5,-3070.5 "/>
<text text-anchor="middle" x="2589.5" y="-3055.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_type</text>
<polyline fill="none" stroke="#000000" points="2525.5,-3047.5 2653.5,-3047.5 "/>
<text text-anchor="middle" x="2589.5" y="-3032.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_description</text>
<polyline fill="none" stroke="#000000" points="2525.5,-3024.5 2653.5,-3024.5 "/>
<text text-anchor="middle" x="2589.5" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">uuid</text>
<polyline fill="none" stroke="#000000" points="2525.5,-3001.5 2653.5,-3001.5 "/>
<text text-anchor="middle" x="2589.5" y="-2986.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_status</text>
<polyline fill="none" stroke="#000000" points="2525.5,-2978.5 2653.5,-2978.5 "/>
<text text-anchor="middle" x="2589.5" y="-2963.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_locations</text>
<polyline fill="none" stroke="#000000" points="2525.5,-2955.5 2653.5,-2955.5 "/>
<text text-anchor="middle" x="2589.5" y="-2940.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_format</text>
<polyline fill="none" stroke="#000000" points="2525.5,-2932.5 2653.5,-2932.5 "/>
<text text-anchor="middle" x="2589.5" y="-2917.3" font-family="Times,serif" font-size="14.00" fill="#000000">file_name</text>
<polyline fill="none" stroke="#000000" points="2653.5,-2909.5 2653.5,-3116.5 "/>
<text text-anchor="middle" x="2664" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;assay -->
<g id="edge30" class="edge">
<title>file&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M2552.7901,-2909.3887C2536.9783,-2838.831 2507.8442,-2746.3751 2456,-2679 2447.2048,-2667.57 2439.7373,-2670.6286 2429,-2661 2360.9267,-2599.9556 2295.843,-2513.022 2265.2334,-2469.8832"/>
<polygon fill="#000000" stroke="#000000" points="2268.0284,-2467.7733 2259.4082,-2461.6136 2262.3057,-2471.8045 2268.0284,-2467.7733"/>
<text text-anchor="middle" x="2459.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- diagnosis -->
<g id="node15" class="node">
<title>diagnosis</title>
<path fill="none" stroke="#000000" d="M2680.5,-1803.5C2680.5,-1803.5 3023.5,-1803.5 3023.5,-1803.5 3029.5,-1803.5 3035.5,-1809.5 3035.5,-1815.5 3035.5,-1815.5 3035.5,-2228.5 3035.5,-2228.5 3035.5,-2234.5 3029.5,-2240.5 3023.5,-2240.5 3023.5,-2240.5 2680.5,-2240.5 2680.5,-2240.5 2674.5,-2240.5 2668.5,-2234.5 2668.5,-2228.5 2668.5,-2228.5 2668.5,-1815.5 2668.5,-1815.5 2668.5,-1809.5 2674.5,-1803.5 2680.5,-1803.5"/>
<text text-anchor="middle" x="2710.5" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis</text>
<polyline fill="none" stroke="#000000" points="2752.5,-1803.5 2752.5,-2240.5 "/>
<text text-anchor="middle" x="2763" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2773.5,-1803.5 2773.5,-2240.5 "/>
<text text-anchor="middle" x="2894" y="-2225.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2217.5 3014.5,-2217.5 "/>
<text text-anchor="middle" x="2894" y="-2202.3" font-family="Times,serif" font-size="14.00" fill="#000000">progesterone_receptor_status</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2194.5 3014.5,-2194.5 "/>
<text text-anchor="middle" x="2894" y="-2179.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_histology_confirmation</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2171.5 3014.5,-2171.5 "/>
<text text-anchor="middle" x="2894" y="-2156.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2148.5 3014.5,-2148.5 "/>
<text text-anchor="middle" x="2894" y="-2133.3" font-family="Times,serif" font-size="14.00" fill="#000000">disease_term</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2125.5 3014.5,-2125.5 "/>
<text text-anchor="middle" x="2894" y="-2110.3" font-family="Times,serif" font-size="14.00" fill="#000000">treatment_data</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2102.5 3014.5,-2102.5 "/>
<text text-anchor="middle" x="2894" y="-2087.3" font-family="Times,serif" font-size="14.00" fill="#000000">follow_up_data</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2079.5 3014.5,-2079.5 "/>
<text text-anchor="middle" x="2894" y="-2064.3" font-family="Times,serif" font-size="14.00" fill="#000000">tumor_size_group</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2056.5 3014.5,-2056.5 "/>
<text text-anchor="middle" x="2894" y="-2041.3" font-family="Times,serif" font-size="14.00" fill="#000000">estrogen_receptor_status</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2033.5 3014.5,-2033.5 "/>
<text text-anchor="middle" x="2894" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000">diagnosis_code</text>
<polyline fill="none" stroke="#000000" points="2773.5,-2010.5 3014.5,-2010.5 "/>
<text text-anchor="middle" x="2894" y="-1995.3" font-family="Times,serif" font-size="14.00" fill="#000000">histological_grade</text>
<polyline fill="none" stroke="#000000" points="2773.5,-1987.5 3014.5,-1987.5 "/>
<text text-anchor="middle" x="2894" y="-1972.3" font-family="Times,serif" font-size="14.00" fill="#000000">recurrence_score</text>
<polyline fill="none" stroke="#000000" points="2773.5,-1964.5 3014.5,-1964.5 "/>
<text text-anchor="middle" x="2894" y="-1949.3" font-family="Times,serif" font-size="14.00" fill="#000000">primary_disease_site</text>
<polyline fill="none" stroke="#000000" points="2773.5,-1941.5 3014.5,-1941.5 "/>
<text text-anchor="middle" x="2894" y="-1926.3" font-family="Times,serif" font-size="14.00" fill="#000000">pathology_report</text>
<polyline fill="none" stroke="#000000" points="2773.5,-1918.5 3014.5,-1918.5 "/>
<text text-anchor="middle" x="2894" y="-1903.3" font-family="Times,serif" font-size="14.00" fill="#000000">nuclear_grade</text>
<polyline fill="none" stroke="#000000" points="2773.5,-1895.5 3014.5,-1895.5 "/>
<text text-anchor="middle" x="2894" y="-1880.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_diagnosis</text>
<polyline fill="none" stroke="#000000" points="2773.5,-1872.5 3014.5,-1872.5 "/>
<text text-anchor="middle" x="2894" y="-1857.3" font-family="Times,serif" font-size="14.00" fill="#000000">histology_cytopathology</text>
<polyline fill="none" stroke="#000000" points="2773.5,-1849.5 3014.5,-1849.5 "/>
<text text-anchor="middle" x="2894" y="-1834.3" font-family="Times,serif" font-size="14.00" fill="#000000">concurrent_disease_type</text>
<polyline fill="none" stroke="#000000" points="2773.5,-1826.5 3014.5,-1826.5 "/>
<text text-anchor="middle" x="2894" y="-1811.3" font-family="Times,serif" font-size="14.00" fill="#000000">stage_of_disease</text>
<polyline fill="none" stroke="#000000" points="3014.5,-1803.5 3014.5,-2240.5 "/>
<text text-anchor="middle" x="3025" y="-2018.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- file&#45;&gt;diagnosis -->
<g id="edge25" class="edge">
<title>file&#45;&gt;diagnosis</title>
<path fill="none" stroke="#000000" d="M2599.5133,-2909.2848C2643.6564,-2754.1579 2727.9893,-2457.7965 2786.9973,-2250.4314"/>
<polygon fill="#000000" stroke="#000000" points="2790.4172,-2251.2012 2789.7878,-2240.625 2783.6844,-2249.2852 2790.4172,-2251.2012"/>
<text text-anchor="middle" x="2726.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">from_diagnosis</text>
</g>
<!-- file&#45;&gt;sample -->
<g id="edge28" class="edge">
<title>file&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2553.0128,-2909.3031C2517.6598,-2698.9683 2430.5309,-2207.7671 2324,-1803 2323.2516,-1800.1563 2322.4886,-1797.2966 2321.7124,-1794.4236"/>
<polygon fill="#000000" stroke="#000000" points="2325.0416,-1793.329 2319.0242,-1784.6088 2318.2902,-1795.1782 2325.0416,-1793.329"/>
<text text-anchor="middle" x="2538.5" y="-2439.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_sample</text>
</g>
<!-- diagnosis&#45;&gt;case -->
<g id="edge5" class="edge">
<title>diagnosis&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2945.5029,-1803.2158C2992.1536,-1656.1045 3017.9773,-1467.7185 2908,-1347 2840.7012,-1273.1284 2190.043,-1248.4585 1890.0868,-1240.968"/>
<polygon fill="#000000" stroke="#000000" points="1890.0865,-1237.467 1880.0032,-1240.7194 1889.9139,-1244.4649 1890.0865,-1237.467"/>
<text text-anchor="middle" x="3012" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- image -->
<g id="node16" class="node">
<title>image</title>
<path fill="none" stroke="#000000" d="M1981,-2995C1981,-2995 2017,-2995 2017,-2995 2023,-2995 2029,-3001 2029,-3007 2029,-3007 2029,-3019 2029,-3019 2029,-3025 2023,-3031 2017,-3031 2017,-3031 1981,-3031 1981,-3031 1975,-3031 1969,-3025 1969,-3019 1969,-3019 1969,-3007 1969,-3007 1969,-3001 1975,-2995 1981,-2995"/>
<text text-anchor="middle" x="1999" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">image</text>
</g>
<!-- image&#45;&gt;assay -->
<g id="edge31" class="edge">
<title>image&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M1997.4449,-2994.9925C1993.7214,-2943.2348 1988.0116,-2790.6243 2038,-2679 2078.7622,-2587.9778 2167.5767,-2507.082 2215.2485,-2468.1098"/>
<polygon fill="#000000" stroke="#000000" points="2217.5127,-2470.7801 2223.0918,-2461.7732 2213.1136,-2465.3351 2217.5127,-2470.7801"/>
<text text-anchor="middle" x="2084.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- visit -->
<g id="node17" class="node">
<title>visit</title>
<path fill="none" stroke="#000000" d="M3071.5,-2990C3071.5,-2990 3246.5,-2990 3246.5,-2990 3252.5,-2990 3258.5,-2996 3258.5,-3002 3258.5,-3002 3258.5,-3024 3258.5,-3024 3258.5,-3030 3252.5,-3036 3246.5,-3036 3246.5,-3036 3071.5,-3036 3071.5,-3036 3065.5,-3036 3059.5,-3030 3059.5,-3024 3059.5,-3024 3059.5,-3002 3059.5,-3002 3059.5,-2996 3065.5,-2990 3071.5,-2990"/>
<text text-anchor="middle" x="3083" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">visit</text>
<polyline fill="none" stroke="#000000" points="3106.5,-2990 3106.5,-3036 "/>
<text text-anchor="middle" x="3117" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3127.5,-2990 3127.5,-3036 "/>
<text text-anchor="middle" x="3182.5" y="-3020.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_date</text>
<polyline fill="none" stroke="#000000" points="3127.5,-3013 3237.5,-3013 "/>
<text text-anchor="middle" x="3182.5" y="-2997.8" font-family="Times,serif" font-size="14.00" fill="#000000">visit_number</text>
<polyline fill="none" stroke="#000000" points="3237.5,-2990 3237.5,-3036 "/>
<text text-anchor="middle" x="3248" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- visit&#45;&gt;visit -->
<g id="edge14" class="edge">
<title>visit&#45;&gt;visit</title>
<path fill="none" stroke="#000000" d="M3171.2183,-3036.2371C3212.4427,-3101.6803 3276.5,-3093.9346 3276.5,-3013 3276.5,-2935.7012 3218.0686,-2925.1633 3176.9043,-2981.3865"/>
<polygon fill="#000000" stroke="#000000" points="3173.9389,-2979.5233 3171.2183,-2989.7629 3179.7306,-2983.4548 3173.9389,-2979.5233"/>
<text text-anchor="middle" x="3292.5" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- agent_administration -->
<g id="node18" class="node">
<title>agent_administration</title>
<path fill="none" stroke="#000000" d="M2199.5,-737.5C2199.5,-737.5 2668.5,-737.5 2668.5,-737.5 2674.5,-737.5 2680.5,-743.5 2680.5,-749.5 2680.5,-749.5 2680.5,-1116.5 2680.5,-1116.5 2680.5,-1122.5 2674.5,-1128.5 2668.5,-1128.5 2668.5,-1128.5 2199.5,-1128.5 2199.5,-1128.5 2193.5,-1128.5 2187.5,-1122.5 2187.5,-1116.5 2187.5,-1116.5 2187.5,-749.5 2187.5,-749.5 2187.5,-743.5 2193.5,-737.5 2199.5,-737.5"/>
<text text-anchor="middle" x="2272.5" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">agent_administration</text>
<polyline fill="none" stroke="#000000" points="2357.5,-737.5 2357.5,-1128.5 "/>
<text text-anchor="middle" x="2368" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2378.5,-737.5 2378.5,-1128.5 "/>
<text text-anchor="middle" x="2519" y="-1113.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2378.5,-1105.5 2659.5,-1105.5 "/>
<text text-anchor="middle" x="2519" y="-1090.3" font-family="Times,serif" font-size="14.00" fill="#000000">route_of_administration</text>
<polyline fill="none" stroke="#000000" points="2378.5,-1082.5 2659.5,-1082.5 "/>
<text text-anchor="middle" x="2519" y="-1067.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2378.5,-1059.5 2659.5,-1059.5 "/>
<text text-anchor="middle" x="2519" y="-1044.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2378.5,-1036.5 2659.5,-1036.5 "/>
<text text-anchor="middle" x="2519" y="-1021.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_units_of_measure</text>
<polyline fill="none" stroke="#000000" points="2378.5,-1013.5 2659.5,-1013.5 "/>
<text text-anchor="middle" x="2519" y="-998.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_lot_number</text>
<polyline fill="none" stroke="#000000" points="2378.5,-990.5 2659.5,-990.5 "/>
<text text-anchor="middle" x="2519" y="-975.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_missed_dose</text>
<polyline fill="none" stroke="#000000" points="2378.5,-967.5 2659.5,-967.5 "/>
<text text-anchor="middle" x="2519" y="-952.3" font-family="Times,serif" font-size="14.00" fill="#000000">start_time</text>
<polyline fill="none" stroke="#000000" points="2378.5,-944.5 2659.5,-944.5 "/>
<text text-anchor="middle" x="2519" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000">dose_level</text>
<polyline fill="none" stroke="#000000" points="2378.5,-921.5 2659.5,-921.5 "/>
<text text-anchor="middle" x="2519" y="-906.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_duration</text>
<polyline fill="none" stroke="#000000" points="2378.5,-898.5 2659.5,-898.5 "/>
<text text-anchor="middle" x="2519" y="-883.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication</text>
<polyline fill="none" stroke="#000000" points="2378.5,-875.5 2659.5,-875.5 "/>
<text text-anchor="middle" x="2519" y="-860.3" font-family="Times,serif" font-size="14.00" fill="#000000">missed_dose_amount</text>
<polyline fill="none" stroke="#000000" points="2378.5,-852.5 2659.5,-852.5 "/>
<text text-anchor="middle" x="2519" y="-837.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_missed_dose</text>
<polyline fill="none" stroke="#000000" points="2378.5,-829.5 2659.5,-829.5 "/>
<text text-anchor="middle" x="2519" y="-814.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_course_number</text>
<polyline fill="none" stroke="#000000" points="2378.5,-806.5 2659.5,-806.5 "/>
<text text-anchor="middle" x="2519" y="-791.3" font-family="Times,serif" font-size="14.00" fill="#000000">stop_time</text>
<polyline fill="none" stroke="#000000" points="2378.5,-783.5 2659.5,-783.5 "/>
<text text-anchor="middle" x="2519" y="-768.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_vial_id</text>
<polyline fill="none" stroke="#000000" points="2378.5,-760.5 2659.5,-760.5 "/>
<text text-anchor="middle" x="2519" y="-745.3" font-family="Times,serif" font-size="14.00" fill="#000000">medication_actual_dose</text>
<polyline fill="none" stroke="#000000" points="2659.5,-737.5 2659.5,-1128.5 "/>
<text text-anchor="middle" x="2670" y="-929.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- agent_administration&#45;&gt;agent -->
<g id="edge26" class="edge">
<title>agent_administration&#45;&gt;agent</title>
<path fill="none" stroke="#000000" d="M2187.3909,-741.7998C2184.2622,-740.1612 2181.1312,-738.5603 2178,-737 2146.2405,-721.1744 2062.6298,-698.9681 1997.1637,-682.9217"/>
<polygon fill="#000000" stroke="#000000" points="1997.7791,-679.4693 1987.2346,-680.5009 1996.1209,-686.2701 1997.7791,-679.4693"/>
<text text-anchor="middle" x="2160" y="-707.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_agent</text>
</g>
<!-- demographic -->
<g id="node19" class="node">
<title>demographic</title>
<path fill="none" stroke="#000000" d="M2551,-1485.5C2551,-1485.5 2887,-1485.5 2887,-1485.5 2893,-1485.5 2899,-1491.5 2899,-1497.5 2899,-1497.5 2899,-1634.5 2899,-1634.5 2899,-1640.5 2893,-1646.5 2887,-1646.5 2887,-1646.5 2551,-1646.5 2551,-1646.5 2545,-1646.5 2539,-1640.5 2539,-1634.5 2539,-1634.5 2539,-1497.5 2539,-1497.5 2539,-1491.5 2545,-1485.5 2551,-1485.5"/>
<text text-anchor="middle" x="2594" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">demographic</text>
<polyline fill="none" stroke="#000000" points="2649,-1485.5 2649,-1646.5 "/>
<text text-anchor="middle" x="2659.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2670,-1485.5 2670,-1646.5 "/>
<text text-anchor="middle" x="2774" y="-1631.3" font-family="Times,serif" font-size="14.00" fill="#000000">race</text>
<polyline fill="none" stroke="#000000" points="2670,-1623.5 2878,-1623.5 "/>
<text text-anchor="middle" x="2774" y="-1608.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_birth</text>
<polyline fill="none" stroke="#000000" points="2670,-1600.5 2878,-1600.5 "/>
<text text-anchor="middle" x="2774" y="-1585.3" font-family="Times,serif" font-size="14.00" fill="#000000">ethnicity</text>
<polyline fill="none" stroke="#000000" points="2670,-1577.5 2878,-1577.5 "/>
<text text-anchor="middle" x="2774" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">menopausal_status</text>
<polyline fill="none" stroke="#000000" points="2670,-1554.5 2878,-1554.5 "/>
<text text-anchor="middle" x="2774" y="-1539.3" font-family="Times,serif" font-size="14.00" fill="#000000">sex</text>
<polyline fill="none" stroke="#000000" points="2670,-1531.5 2878,-1531.5 "/>
<text text-anchor="middle" x="2774" y="-1516.3" font-family="Times,serif" font-size="14.00" fill="#000000">weight</text>
<polyline fill="none" stroke="#000000" points="2670,-1508.5 2878,-1508.5 "/>
<text text-anchor="middle" x="2774" y="-1493.3" font-family="Times,serif" font-size="14.00" fill="#000000">patient_age_at_enrollment</text>
<polyline fill="none" stroke="#000000" points="2878,-1485.5 2878,-1646.5 "/>
<text text-anchor="middle" x="2888.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- demographic&#45;&gt;case -->
<g id="edge3" class="edge">
<title>demographic&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2670.8632,-1485.2793C2637.588,-1436.9855 2588.7941,-1378.9632 2530,-1347 2422.6949,-1288.6639 2088.0614,-1258.964 1890.412,-1246.1374"/>
<polygon fill="#000000" stroke="#000000" points="1890.4323,-1242.6316 1880.2285,-1245.4836 1889.9837,-1249.6172 1890.4323,-1242.6316"/>
<text text-anchor="middle" x="2511" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- evaluation -->
<g id="node20" class="node">
<title>evaluation</title>
<path fill="none" stroke="#000000" d="M3339,-2995C3339,-2995 3599,-2995 3599,-2995 3605,-2995 3611,-3001 3611,-3007 3611,-3007 3611,-3019 3611,-3019 3611,-3025 3605,-3031 3599,-3031 3599,-3031 3339,-3031 3339,-3031 3333,-3031 3327,-3025 3327,-3019 3327,-3019 3327,-3007 3327,-3007 3327,-3001 3333,-2995 3339,-2995"/>
<text text-anchor="middle" x="3372.5" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">evaluation</text>
<polyline fill="none" stroke="#000000" points="3418,-2995 3418,-3031 "/>
<text text-anchor="middle" x="3428.5" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="3439,-2995 3439,-3031 "/>
<text text-anchor="middle" x="3514.5" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">date_of_evaluation</text>
<polyline fill="none" stroke="#000000" points="3590,-2995 3590,-3031 "/>
<text text-anchor="middle" x="3600.5" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- cohort&#45;&gt;study -->
<g id="edge23" class="edge">
<title>cohort&#45;&gt;study</title>
<path fill="none" stroke="#000000" d="M2152.1695,-639.4499C2148.8492,-609.3497 2139.7024,-556.0233 2115,-518 2102.3233,-498.4873 2086.6162,-480.1676 2069.5784,-463.3348"/>
<polygon fill="#000000" stroke="#000000" points="2071.8257,-460.6395 2062.2,-456.2127 2066.9642,-465.6759 2071.8257,-460.6395"/>
<text text-anchor="middle" x="2183.5" y="-549.3" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- cohort&#45;&gt;study_arm -->
<g id="edge24" class="edge">
<title>cohort&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M2096.3536,-639.4418C2082.1188,-633.5755 2066.9537,-627.179 2053,-621 2032.5101,-611.9266 2010.57,-601.7369 1990.1808,-592.0618"/>
<polygon fill="#000000" stroke="#000000" points="1991.4661,-588.7974 1980.9327,-587.6585 1988.4569,-595.1175 1991.4661,-588.7974"/>
<text text-anchor="middle" x="2093.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">member_of</text>
</g>
<!-- genomic_report -->
<g id="node23" class="node">
<title>genomic_report</title>
<path fill="none" stroke="#000000" d="M2059,-2875C2059,-2875 2435,-2875 2435,-2875 2441,-2875 2447,-2881 2447,-2887 2447,-2887 2447,-3139 2447,-3139 2447,-3145 2441,-3151 2435,-3151 2435,-3151 2059,-3151 2059,-3151 2053,-3151 2047,-3145 2047,-3139 2047,-3139 2047,-2887 2047,-2887 2047,-2881 2053,-2875 2059,-2875"/>
<text text-anchor="middle" x="2112" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000">genomic_report</text>
<polyline fill="none" stroke="#000000" points="2177,-2875 2177,-3151 "/>
<text text-anchor="middle" x="2187.5" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
<polyline fill="none" stroke="#000000" points="2198,-2875 2198,-3151 "/>
<text text-anchor="middle" x="2312" y="-3135.8" font-family="Times,serif" font-size="14.00" fill="#000000">status_date</text>
<polyline fill="none" stroke="#000000" points="2198,-3128 2426,-3128 "/>
<text text-anchor="middle" x="2312" y="-3112.8" font-family="Times,serif" font-size="14.00" fill="#000000">total_mois</text>
<polyline fill="none" stroke="#000000" points="2198,-3105 2426,-3105 "/>
<text text-anchor="middle" x="2312" y="-3089.8" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_received_date</text>
<polyline fill="none" stroke="#000000" points="2198,-3082 2426,-3082 "/>
<text text-anchor="middle" x="2312" y="-3066.8" font-family="Times,serif" font-size="14.00" fill="#000000">total_variants</text>
<polyline fill="none" stroke="#000000" points="2198,-3059 2426,-3059 "/>
<text text-anchor="middle" x="2312" y="-3043.8" font-family="Times,serif" font-size="14.00" fill="#000000">status</text>
<polyline fill="none" stroke="#000000" points="2198,-3036 2426,-3036 "/>
<text text-anchor="middle" x="2312" y="-3020.8" font-family="Times,serif" font-size="14.00" fill="#000000">molecular_id</text>
<polyline fill="none" stroke="#000000" points="2198,-3013 2426,-3013 "/>
<text text-anchor="middle" x="2312" y="-2997.8" font-family="Times,serif" font-size="14.00" fill="#000000">variant_report_type</text>
<polyline fill="none" stroke="#000000" points="2198,-2990 2426,-2990 "/>
<text text-anchor="middle" x="2312" y="-2974.8" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_mois</text>
<polyline fill="none" stroke="#000000" points="2198,-2967 2426,-2967 "/>
<text text-anchor="middle" x="2312" y="-2951.8" font-family="Times,serif" font-size="14.00" fill="#000000">surgical_event_id</text>
<polyline fill="none" stroke="#000000" points="2198,-2944 2426,-2944 "/>
<text text-anchor="middle" x="2312" y="-2928.8" font-family="Times,serif" font-size="14.00" fill="#000000">cellularity</text>
<polyline fill="none" stroke="#000000" points="2198,-2921 2426,-2921 "/>
<text text-anchor="middle" x="2312" y="-2905.8" font-family="Times,serif" font-size="14.00" fill="#000000">total_amois</text>
<polyline fill="none" stroke="#000000" points="2198,-2898 2426,-2898 "/>
<text text-anchor="middle" x="2312" y="-2882.8" font-family="Times,serif" font-size="14.00" fill="#000000">total_confirmed_amois</text>
<polyline fill="none" stroke="#000000" points="2426,-2875 2426,-3151 "/>
<text text-anchor="middle" x="2436.5" y="-3009.3" font-family="Times,serif" font-size="14.00" fill="#000000"> </text>
</g>
<!-- genomic_report&#45;&gt;assay -->
<g id="edge32" class="edge">
<title>genomic_report&#45;&gt;assay</title>
<path fill="none" stroke="#000000" d="M2247,-2874.7765C2247,-2739.812 2247,-2544.4822 2247,-2471.9824"/>
<polygon fill="#000000" stroke="#000000" points="2250.5001,-2471.8129 2247,-2461.813 2243.5001,-2471.813 2250.5001,-2471.8129"/>
<text text-anchor="middle" x="2277.5" y="-2649.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_assay</text>
</g>
<!-- sample&#45;&gt;case -->
<g id="edge2" class="edge">
<title>sample&#45;&gt;case</title>
<path fill="none" stroke="#000000" d="M2023.4693,-1353.1683C2020.3189,-1351.0685 2017.1618,-1349.0112 2014,-1347 1975.8482,-1322.7325 1931.4082,-1302.2358 1889.5598,-1285.7965"/>
<polygon fill="#000000" stroke="#000000" points="1890.7022,-1282.4857 1880.1132,-1282.1364 1888.1732,-1289.0129 1890.7022,-1282.4857"/>
<text text-anchor="middle" x="2007" y="-1317.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_case</text>
</g>
<!-- sample&#45;&gt;sample -->
<g id="edge15" class="edge">
<title>sample&#45;&gt;sample</title>
<path fill="none" stroke="#000000" d="M2470.5955,-1595.6213C2481.8572,-1588.2644 2488.5,-1578.3906 2488.5,-1566 2488.5,-1556.9006 2484.9175,-1549.1586 2478.5541,-1542.774"/>
<polygon fill="#000000" stroke="#000000" points="2480.583,-1539.9144 2470.5955,-1536.3787 2476.1982,-1545.3709 2480.583,-1539.9144"/>
<text text-anchor="middle" x="2504.5" y="-1562.3" font-family="Times,serif" font-size="14.00" fill="#000000">next</text>
</g>
<!-- agent&#45;&gt;study_arm -->
<g id="edge33" class="edge">
<title>agent&#45;&gt;study_arm</title>
<path fill="none" stroke="#000000" d="M1910,-644.4183C1910,-631.8613 1910,-614.5418 1910,-598.3523"/>
<polygon fill="#000000" stroke="#000000" points="1913.5001,-597.9381 1910,-587.9381 1906.5001,-597.9382 1913.5001,-597.9381"/>
<text text-anchor="middle" x="1958.5" y="-609.8" font-family="Times,serif" font-size="14.00" fill="#000000">of_study_arm</text>
</g>
</g>
</svg>
</div>
