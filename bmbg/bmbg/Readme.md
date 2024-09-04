04.09.2024, 10:20:07

# Beta-Multiplier Bandgap

Beta-Multiplier Bandgap.

![bmbg](resources/bmbg.png "bmbg")

<br>

[🔗 Schematics](bmbg_sch.pdf)<br>

# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](bmbg_bmbg_netgen_comp.out)<br>

# SPECIFICATIONS

## Reference Voltage Curvature vs Temperature <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.21 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.74004,10.0,83.93267999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.74004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.93267999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.225 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.035 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.324389824000001,10.0,9.33704256,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.324389824000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.33704256" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.002 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.213 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.39555200000001,10.0,67.90454399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.39555200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.90454399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.225 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -24.66 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.52037,10.0,77.5885452,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.52037" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.5885452" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.142 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.533 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.48223999999996,10.0,106.07711999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.48223999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.07711999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.263 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.117 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.270839999999986,10.0,129.02988,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.270839999999986" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="129.02988" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.35 / 1.4 | V | 1237/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.229 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.284162048000001,10.0,18.6027168,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.284162048000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.6027168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 27.088 / 250.0 | mV | 1228/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.121 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.5474,10.0,126.61968000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.5474" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.61968000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.343 / 1.4 | V | 1237/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -130.421 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="67.17474,10.0,85.217352,10.0" style="stroke:green;stroke-width:2" /><circle cx="67.17474" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="85.217352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 170.289 / 1200.0 | uV/°C | 1249/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -83.256 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.743360000000077,10.0,100.69151999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.743360000000077" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.69151999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.824 / -70.0 | uA | 1233/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.208 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.7954,10.0,83.56835999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.7954" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="83.56835999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.224 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.614 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.05702016,10.0,52.31214336,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.05702016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="52.31214336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.561 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.205 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="61.95043199999997,10.0,67.00598399999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="61.95043199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.00598399999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.222 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.176 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.8344856,10.0,99.5339532,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.8344856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.5339532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 6.815 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.322 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.65535999999999,10.0,126.53855999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.65535999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.53855999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.263 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.075 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.830079999999978,10.0,125.17428,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.830079999999978" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="125.17428" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.339 / 1.4 | V | 1245/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.427 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.457016127999999,10.0,112.3027968,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.457016127999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="112.3027968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.976 / 25.0 | mV | 1242/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.106 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.27915999999999,10.0,123.65724000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.27915999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.65724000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.335 / 1.4 | V | 1244/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -6.085 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="53.093388,10.0,116.79708000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="53.093388" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="116.79708000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.61 / 20.0 | mV/V | 1244/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.568 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.87503999999998,10.0,117.47471999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.87503999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.47471999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -76.151 / -70.0 | uA | 1243/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 13.063 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.8101584,10.0,29.2364976,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.8101584" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.2364976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.22 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.616 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.773733248,10.0,7.156685120000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.773733248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.156685120000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.749 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -85.684 | <svg height="20" width="150"><polyline points="20.915641684014215,3,20.915641684014215,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.95782084200711,10.0,83.95782084200711,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,33.659933411698255,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="33.659933411698255" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -75.957 / -40 | dB | 5/60.0%/40.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.81 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.68907999999999,10.0,91.2247344,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.68907999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.2247344" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.38 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10 Hz":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.3_bmbg/batch_0/ff/ac_psrr.csv Index:0 <br>
> **FAIL:** group:hh file:work/sim/bmbg/bmbg_tb.3_bmbg/batch_0/hh/ac_psrr.csv Index:0 <br>
</details><br>


## PSRR+ Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -109.979 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.100184615384617,10.0,135.90402184615385,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.100184615384617" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.90402184615385" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.017 / 10 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 6.127 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.4118896,10.0,94.68353760000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.4118896" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="94.68353760000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.101 / 20 | dB | 1238/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.79904000000005,10.0,88.08456,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.79904000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.08456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.236 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 4.879 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.8102988159999995,10.0,9.99930432,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.8102988159999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="9.99930432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.152 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.223 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="67.198656,10.0,70.76582400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="67.198656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.76582400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.235 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / 22.468 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.348092,10.0,80.4980886,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.348092" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.4980886" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 91.635 / 1200.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -79.306 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.660479999999986,10.0,106.83935999999993,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.660479999999986" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.83935999999993" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.183 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.124 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.736839999999994,10.0,137.82288000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.736839999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.82288000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.375 / 1.4 | V | 1234/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.363 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.784997568,10.0,27.22619712,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.784997568" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.22619712" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.059 / 250.0 | mV | 1237/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.127 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.64296000000003,10.0,133.90428000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.64296000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="133.90428000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.364 / 1.4 | V | 1234/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -180.83 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.1502,10.0,92.15916600000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.1502" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="92.15916600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 285.986 / 1200.0 | uV/°C | 1243/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -85.0 / -82.705 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.03008000000002,10.0,105.97151999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.03008000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.97151999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.274 / -70.0 | uA | 1232/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.221 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.63271999999998,10.0,88.18932000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.63271999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.18932000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.237 / 1.4 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.847 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.39656576,10.0,54.73169472,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.39656576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="54.73169472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.981 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.22 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.408096,10.0,70.206816,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.408096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.206816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.233 / 1.5 | V | 15/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / 2.252 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="83.10692999999999,10.0,100.6472676,10.0" style="stroke:green;stroke-width:2" /><circle cx="83.10692999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.6472676" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 7.124 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -91.18 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.33456000000002,10.0,126.91967999999994,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.33456000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.91967999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -74.183 / -70.0 | uA | 15/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.113 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.56516000000002,10.0,135.45912,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.56516000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.45912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.368 / 1.4 | V | 1207/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.589 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.394290816,10.0,128.08139519999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.394290816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="128.08139519999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 21.716 / 25.0 | mV | 1204/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.113 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.852079999999994,10.0,133.78116,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.852079999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="133.78116" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.363 / 1.4 | V | 1208/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -7.004 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.787148,10.0,122.666124,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.787148" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.666124" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.241 / 20.0 | mV/V | 1207/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -100.0 / -83.824 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.64671999999999,10.0,117.21887999999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.64671999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.21887999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -76.204 / -70.0 | uA | 1210/100.0%/0.0%/0.0% |  |

<br>


## Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 13.306 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.1604816,10.0,29.7831072,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.1604816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="29.7831072" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.599 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.626 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.803040992,10.0,7.19759696,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.803040992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.19759696" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.763 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -82.707 | <svg height="20" width="150"><polyline points="12.1265492299803,3,12.1265492299803,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.56327461499015,10.0,79.56327461499015,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,29.1614032458607,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="29.1614032458607" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -74.948 / -40 | dB | 5/80.0%/20.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 9.148 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="94.9105824,10.0,103.64136,10.0" style="stroke:green;stroke-width:2" /><circle cx="94.9105824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.64136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.967 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10 Hz":<br>
> **FAIL:** group:ff file:work/sim/bmbg/bmbg_tb.3_bmbg_ext/batch_0/ff/ac_psrr.csv Index:0 <br>
</details><br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -112.245 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.590153846153841,10.0,135.98300027446155,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.590153846153841" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="135.98300027446155" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.054 / 10 | dB | 1250/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 8.178 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="90.2556096,10.0,107.94561599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="90.2556096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.94561599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.864 / 20 | dB | 1216/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## Voltage Curvature vs Temperature Performance<br>

| ![xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59](xyplot_temp-sweepv(vref)v(vdd)_('tt',_-2)__3516055f01315a7484bbe87ee259fa59.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs Temperature Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__cf833be0701160a7712cddd77481464c.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance<br>

| ![xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6](xyplot_v(v-sweep)v(vref)v(temperature)_('tt',_-2)__9f73b4634d7c74906f13921966826cc6.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo)<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__17ebde026e8bf0947f3a71096d2eacc2.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs Temperature Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f](histplot_vref_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f](histplot_vref_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6f8de2b3acb370cfea404af72ded0d3f.png "") |
| :-- |
|  |
<br>

## Voltage Curvature vs VDD Performance (Monte Carlo) [PEX]<br>

| ![histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba](histplot_vref_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba](histplot_vref_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba](histplot_vref_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba.png "") |
| :-- |
|  |
<br>

| ![histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba](histplot_vref_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__23063f8b3a96f11bfb8cf90f24a845ba.png "") |
| :-- |
|  |
<br>
