# Aza-Diarylethenes (R04, R05, R06 & R07)

<table>
  <tr>
    <td align="left">
      <img src="https://github.com/CompPhotoChem/data_R04-R07/blob/main/img/R04_D.png" width="300px"><br>
      <b>R04</b> (<b>D-open</b>) <br>
    </td>
    <td align="left">
      <img src="https://github.com/CompPhotoChem/data_R04-R07/blob/main/img/R05_DF.png" width="300px"><br>
      <b>R05</b> (<b>D<sup>F</sup></b>) <br>
    </td>
  </tr>
  <tr>
    <td align="left">
      <img src="https://github.com/CompPhotoChem/data_R04-R07/blob/main/img/R06_K.png" width="300px"><br>
      <b>R06</b> (<b>K-open</b>)<br>
    </td>
    <td align="left">
      <img src="https://github.com/CompPhotoChem/data_R04-R07/blob/main/img/R07_KH.png" width="300px"><br>
      <b>R07</b> (<b>K<sup>H</sup></b>) <br>
    </td>
  </tr>
</table>

---

# [Static Data](https://github.com/CompPhotoChem/data_R04-R07/tree/main/static)

<details>
  <summary><strong>Ground-state equilibrium geometries</strong></summary>
  <br>
  
- **Molecules**: R04-R07 (open, closed and zwitterionic form/isomer)
- **Electronic structure code**: Orca 5
- **Level of Theory**: CAM-B3LYP/def2-TZVP/CPCM(MeOH)

<strong>Open Isomers</strong>

  - [R04-open (D-open)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R04_open.xyz)
  - [R05-open (D<sup>F</sup>-open)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R05_open.xyz)
  - [R06-open (K-open)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R06_open.xyz)
  - [R07-open (K<sup>H</sup>-open)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R07_open.xyz)

<strong>Closed Isomers</strong>

  - [R04-closed (D-closed)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R04_closed.xyz)
  - [R05-closed (D<sup>F</sup>-closed)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R05_closed.xyz)
  - [R06-closed (K-closed)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R06_closed.xyz)
  - [R07-closed (K<sup>H</sup>-closed)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R07_closed.xyz)

<strong>Zwitterionic Isomers</strong>

  - [R04-ZI (D-ZI)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R04_zi.xyz)
  - [R05-ZI (D<sup>F</sup>-ZI)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R05_zi.xyz)
  - [R06-ZI (K-ZI)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R06_zi.xyz)
  - [R07-ZI (K<sup>H</sup>-ZI)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/GS_minima/R07_zi.xyz)

</details>

<details>
  <summary><strong>Ground-state absorption properties</strong></summary>
  <br>

- **Electronic structure code**: R04 and R06 (open, closed and zwitterionic form/isomer)
- **Electronic structure code**: Orca 5
- **Level of Theory**: TD-CAM-B3LYP/def2-TZVP/CPCM(MeOH)

  <strong>R04</strong>

  - [R04-open (D-open)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/absorption/R04_open.dat)
  - [R04-closed (D-closed)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/absorption/R04_closed.dat)
  - [R04-ZI (D-ZI)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/absorption/R04_zi.dat)

  <strong>R06</strong>

  - [R06-open (K-open)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/absorption/R06_open.dat)
  - [R06-closed (K-closed)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/absorption/R06_closed.dat)
  - [R06-ZI (K-ZI)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/absorption/R06_zi.dat)

</details>

<details>
  <summary><strong>Relaxed Coordinate Scans in S<sub>0</sub> and S<sub>1</sub></strong></summary>
  <br>

- **Molecules**: R04 and R06 (paths: open ➜ closed; closed ➜ zwitterionic)
- **Electronic structure code**: Orca 5
- **Level of Theory**: TD-CAM-B3LYP/def2-TZVP/CPCM(MeOH)
- **Scan Coordinates**: distances
- **Roots**: S<sub>0</sub> and S<sub>1</sub>

- [Scan of C-N distance (R04 and R06)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/scans/C-N.dat)
- [Scan of C-S distance (R04 and R06)](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/scans/C-S.dat)

</details>


<details>
  <summary><strong>Minimum energy S<sub>0</sub>/S<sub>1</sub> conical intersections</strong></summary>
  <br>

- **Molecules**: R04 and R06 (MECI between open and closed)
- **Electronic structure code**: OpenQP
- **Level of Theory**: MRSF-TDDFT-DTCAM-AEE/6-31G*

  <strong>R04</strong>

  - [D-CI<sub><i>main</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R04_main.xyz)
  - [D-CI<sub><i>thio</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R04_thio.xyz)
  - [D-CI<sub><i>thio*</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R04_thio2.xyz)
  - [D-CI<sub><i>twist</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R04_twist.xyz)
  - [D-CI<sub><i>twist*</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R04_twist2.xyz)

<strong>R06</strong>

  - [K-CI<sub><i>main</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R06_main.xyz)
  - [K-CI<sub><i>thio</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R06_thio.xyz)
  - [K-CI<sub><i>thio*</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R06_thio2.xyz)
  - [K-CI<sub><i>thiazole</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R06_thiazole.xyz)
  - [K-CI<sub><i>thiazole*</i></sub>](https://github.com/CompPhotoChem/data_R04-R07/blob/main/static/MECI/R06_thiazole2.xyz)

</details>

---

# [Surface Hopping Data](https://github.com/CompPhotoChem/data_R04-R07/tree/main/dynamic)

The surface hopping data of R04 and R05 are provided in form of a shnitsel-dataset.

**Details about trajectory data**


