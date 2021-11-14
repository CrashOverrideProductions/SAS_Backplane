# SAS Backplane <img align="right" src="https://github.com/CrashOverrideProductions/SAS_Backplane/blob/main/RepoImages/logosml.png?raw=true">

### Project: PCB + 3D Printable SAS Dock <img alt="" align="right" src="https://img.shields.io/badge/Status-Prototype%20Phase-informational?style=flat&logoColor=white&color=73398D" />


<!-- Repo Cover Image -->
<p style="background-color:rgba(22,22,22,1.00)" align="center">
<img align="center" src="https://github.com/CrashOverrideProductions/SAS_Backplane/blob/main/RepoImages/tempheader.png?raw=true" />
</p>

<!-- Repo Stats -->
<img align="center" src="https://img.shields.io/github/commit-activity/m/CrashOverrideProductions/SAS_Backplane"> <img align="center" src="https://img.shields.io/github/last-commit/CrashOverrideProductions/SAS_Backplane"> <img align="center" src="https://img.shields.io/github/languages/code-size/CrashOverrideProductions/SAS_Backplane"> <img align="center" src="https://img.shields.io/github/directory-file-count/CrashOverrideProductions/SAS_Backplane">

### Details
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras ultrices tortor mi, quis porttitor turpis rhoncus sed. Donec ultrices ipsum vel justo interdum rhoncus. Aenean vel velit non nisi pretium tincidunt sed ac arcu.

### Concept?
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras ultrices tortor mi, quis porttitor turpis rhoncus sed. Donec ultrices ipsum vel justo interdum rhoncus. Aenean vel velit non nisi pretium tincidunt sed ac arcu. Fusce porttitor, augue sit amet aliquet tempus, mauris nibh faucibus ligula, et volutpat nibh urna varius dolor. Ut vestibulum ante et mauris malesuada condimentum. Suspendisse viverra est ut ligula viverra, ut viverra turpis faucibus. Integer condimentum imperdiet nunc quis fermentum. Maecenas non quam vitae enim tempus iaculis finibus et felis. Cras ex ipsum, dapibus quis nulla in, imperdiet aliquam risus. Quisque eleifend vel sem et fringilla. Pellentesque in magna at nunc aliquet vestibulum. Maecenas suscipit dui eget nisl egestas, eu sodales risus finibus. Nam lorem enim, faucibus ac leo ac, consectetur blandit sem.

Nunc semper metus orci, non egestas odio cursus et. Curabitur luctus purus augue, sed porttitor urna pellentesque et. Curabitur elementum consequat nisi nec maximus. Nunc nec nisl risus. Morbi condimentum, leo finibus porta pulvinar, dui massa ornare turpis, at volutpat nulla dui ornare sem. Fusce nec quam hendrerit, rhoncus libero eu, faucibus ligula. Cras euismod tempor justo, in porttitor sapien tristique vel. Nulla ligula libero, vehicula ac magna vel, cursus luctus nisi. Nulla sollicitudin blandit felis, ac eleifend erat gravida at. Vestibulum sem ipsum, porta nec ante in, congue iaculis leo. Maecenas tincidunt, ex quis euismod laoreet, justo mauris lacinia lectus, vel mollis ipsum eros eget mi. Praesent fringilla faucibus neque nec porta. 

---
### Power Requirements

| Drive          | Type | Form | Peak A | Peak W | Idle W |
|----------------|------|:----:|:------:|:------:|:------:|
| ST500DM0009    | SATA | 3.5  | 2.00 A |        | 5.3 W  |
| ST2000DM008    | SATA | 3.5  | 2.50 A |        | 8.5 W  |
| ST4000DM005    | SATA | 3.5  | 2.00 A |        | 5.6 W  |
| WD5000AZLX     | SATA | 3.5  | 2.00 A |        | 3.3 W  |
| WD20EZAZ       | SATA | 3.5  | 1.31 A |        | 4.1 W  |
| WD60EZRZ       | SATA | 3.5  | 1.75 A |        | 5.3 W  |
| ST14000NM0018  | SAS  | 3.5  |        | 10.0 W | 6.0 W  |
| ST14000NM0448  | SAS  | 3.5  |        | 6.4 W  | 5.7 W  |
| MBC2036RC      | SAS  | 2.5  | 2.0A   | 9.0 W  | 5.3 W  |


---
### Connector Pinouts

#### Data Connector 

| Pin # | Pin Name  | Desc           |
|:-----:|-----------|----------------|
| S1    | GROUND 	| Primary signal |
| S2 	| RP+ 	    | Primary signal |
| S3 	| RP- 	    | Primary signal |
| S4 	| GROUND 	| Primary signal |
| S5 	| TP- 	    | Primary signal |
| S6 	| TP+ 	    | Primary signal |
| S7 	| GROUND 	| Primary signal |


| Pin # | Pin Name  | Desc               |
|:-----:|-----------|--------------------|
| S8 	| GROUND 	| Secondary signal * |
| S9 	| RS+ 	    | Secondary signal * |
| S10 	| RS- 	    | Secondary signal * |
| S11 	| GROUND 	| Secondary signal * |
| S12 	| TS- 	    | Secondary signal * |
| S13 	| TS+ 	    | Secondary signal * |
| S14 	| GROUND 	| Secondary signal * |

(*) S8 through S14 are no-connects on single-port implementations


#### Power Connector 
| Pin # | Pin Name  | Desc      |
|:-----:|-----------|-----------|
| P1    | +3.3V     |           |	 
| P2    | +3.3V     |           |
| P3    | +3.3V     | precharge |
| P4 	| GROUND    |           |
| P5 	| GROUND    |           |	 
| P6 	| GROUND    |           | 	 
| P7 	| +5V 	    | precharge |
| P8 	| +5V       |           | 	 
| P9 	| +5V       |           |	 
| P10 	| GROUND    |           | 	 
| P11 	| READY LED |           | 	 
| P12 	| GROUND    |           | 	 
| P13 	| +12V 	    | precharge |
| P14 	| +12V      |           |	 
| P15 	| +12V      |           | 	 

#### SFF-8087 Connector

---
<!-- To Do List -->
### To Do List
- [ ] Complete Readme.md
- [ ] Research Concept
- [ ] Build & Test Prototype
- [ ] Design Schematic
- [ ] Design Board
- [ ] Order Prototype PCBs
- [ ] Design 3D Print Shell

---