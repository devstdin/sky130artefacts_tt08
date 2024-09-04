04.09.2024, 10:20:07

# Vth Current Reference

10 uA current reference with source- and sink-port.

![vthref](resources/vthref.png "vthref")

<br>

[🔗 Schematics](vthref_sch.pdf)<br>

# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](vthref_vthref_netgen_comp.out)<br>

# SPECIFICATIONS

## Transient Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Startup Time | 0.0 / 0.005 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0358899696,10.0,5.0572052168,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.0358899696" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.0572052168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.008 / 20.0 | ms | 20/100.0%/0.0%/0.0% |  |

<br>


## DC Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.183 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.280950400000002,10.0,53.8264128,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.280950400000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.8264128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.353 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.181 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.0441424,10.0,56.808508800000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.0441424" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.808508800000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.374 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |

<br>


## DC Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.19 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.341798400000002,10.0,48.6072624,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.341798400000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="48.6072624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.317 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.192 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.637128,10.0,48.435844800000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.637128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="48.435844800000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.316 / 1.0 | uA | 500/100.0%/0.0%/0.0% |  |

<br>


## DC Specification (PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.19 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.3446784,10.0,55.1605152,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.3446784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="55.1605152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.362 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.175 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="28.153948800000002,10.0,58.377936,10.0" style="stroke:green;stroke-width:2" /><circle cx="28.153948800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="58.377936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.385 / 1.0 | uA | 20/100.0%/0.0%/0.0% |  |

<br>


## DC Specification (Monte Carlo, PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.193 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,72.66193642767786,17,72.66193642767786,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="37.83096821383893,10.0,37.83096821383893,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.47684698465406,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="16.47684698465406" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 2.067 / 1.0 | uA | 500/99.8%/0.2%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.194 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,74.30068290209624,17,74.30068290209624,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="38.65034145104812,10.0,38.65034145104812,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.825594568472425,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="16.825594568472425" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 2.02 / 1.0 | uA | 500/99.8%/0.2%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Sink)":<br>
> **FAIL:** group:ff_mm file:work/sim/vthref/vthref_tb.4_dcext/batch_4/ff_mm/dc.csv Index:4 <br>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Source)":<br>
> **FAIL:** group:ff_mm file:work/sim/vthref/vthref_tb.4_dcext/batch_4/ff_mm/dc.csv Index:4 <br>
</details><br>


# PERFORMANCE CHARACTERISTICS

## DC Performance<br>

| ![xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(viin)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(viin)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepv(x1.vs)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepv(x1.vs)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepv(x1.vp)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepv(x1.vp)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(_b.x1.xrsu.xsky130_fd_pr__res_xhigh_po_0p69.brend_i_)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9](xyplot_temp-sweepi(_b.x1.xrsu.xsky130_fd_pr__res_xhigh_po_0p69.brend_i_)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

| ![occtplot_temp-sweep_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9](occtplot_temp-sweep_('tt',_-2)__94b518e40830ed39bffc36cf7b5c0da9.png "") |
| :-- |
|  |
<br>

## DC Performance (Monte Carlo)<br>

| ![histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23bafb5ab45771cf23411b544f38b83c](histplot_sink_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23bafb5ab45771cf23411b544f38b83c.png "") |
| :-- |
|  |
<br>

| ![histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23bafb5ab45771cf23411b544f38b83c](histplot_source_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23bafb5ab45771cf23411b544f38b83c.png "") |
| :-- |
|  |
<br>

## AC Noise<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__07d296c7c9ff73db4dc3ee4d86457f8c](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__07d296c7c9ff73db4dc3ee4d86457f8c.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c0c96b36b0d28d09473c62b512f759e6](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c0c96b36b0d28d09473c62b512f759e6.png "") |
| :-- |
|  |
<br>

## DC Performance (PEX)<br>

| ![xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__b4be906a43536e413e158af68407b680](xyplot_temp-sweepi(visink)v(vdd)_('tt',_-2)__b4be906a43536e413e158af68407b680.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__b4be906a43536e413e158af68407b680](xyplot_temp-sweepi(visource)v(vdd)_('tt',_-2)__b4be906a43536e413e158af68407b680.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__b4be906a43536e413e158af68407b680](xyplot_temp-sweepi(visink)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__b4be906a43536e413e158af68407b680.png "") |
| :-- |
|  |
<br>

| ![xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__b4be906a43536e413e158af68407b680](xyplot_temp-sweepi(visource)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__b4be906a43536e413e158af68407b680.png "") |
| :-- |
|  |
<br>