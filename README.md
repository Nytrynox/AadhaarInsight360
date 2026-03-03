<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=ff6e96&height=220&section=header&text=AadhaarInsight360&fontSize=42&fontAlignY=35&desc=API%20/%20Backend%20Service&descAlignY=55&fontColor=ffffff" alt="Header"/>

<p align="center">
  <img src="https://img.shields.io/badge/Type-API%20%2F%20Backend%20Service-ff6e96?style=for-the-badge&logo=target&logoColor=black" alt="Type" />
  <img src="https://img.shields.io/badge/Language-Python-ff6e96?style=for-the-badge&logo=code&logoColor=black" alt="Language" />
  <img src="https://img.shields.io/badge/Files-37-161b22?style=for-the-badge&logo=files&logoColor=ff6e96" alt="Files" />
  <img src="https://img.shields.io/badge/License-PROPRIETARY-ff0000?style=for-the-badge&logo=shield&logoColor=white" alt="License" />
</p>

  <img src="https://img.shields.io/badge/Streamlit-161b22?style=flat-square&logo=streamlit&logoColor=ff6e96" alt="Streamlit" />


</div>

---

## Overview

> AadhaarInsight360 is a comprehensive data analytics platform built for the UIDAI Data Hackathon 2026. It provides real-time insights into Aadhaar enrolment and update activities across India

**AadhaarInsight360** is a proprietary api / backend service system engineered by **Karthik Idikuda**. It leverages Streamlit for its core functionality.

<br/>

## System Architecture

```mermaid
graph LR;
    A["Client Request"] -->|HTTP/REST| B["Streamlit Router"];
    B -->|Middleware| C{"Authentication & Validation"};
    C -->|Authorized| D["Controller / Handler"];
    D -->|Query| E[(Data Store)];
    D -->|Response| F["JSON Serializer"];
    F -->|HTTP 200| A;
    
    classDef api fill:#0d1117,stroke:#f78166,stroke-width:2px,color:#fff;
    classDef data fill:#161b22,stroke:#7ee787,stroke-width:2px,color:#fff;
    class A,B,C api;
    class D,E,F data;
```

<br/>

## Project Structure

```
AadhaarInsight360/
  .DS_Store
  LICENSE
  README.md
  app.py
  icons.py
  profile.jpeg
  requirements.txt
  styles.py
  uidai_logo.png
  utils.py
  __pycache__/
    icons.cpython-311.pyc
    styles.cpython-311.pyc
    utils.cpython-311.pyc
  api_data_aadhar_biometric/
    api_data_aadhar_biometric_0_500000.csv
    api_data_aadhar_biometric_1000000_1500000.csv
    api_data_aadhar_biometric_1500000_1861108.csv
    api_data_aadhar_biometric_500000_1000000.csv
  api_data_aadhar_demographic/
    api_data_aadhar_demographic_0_500000.csv
    api_data_aadhar_demographic_1000000_1500000.csv
    api_data_aadhar_demographic_1500000_2000000.csv
    api_data_aadhar_demographic_2000000_2071700.csv
    api_data_aadhar_demographic_500000_1000000.csv
  api_data_aadhar_enrolment/
    api_data_aadhar_enrolment_0_500000.csv
    api_data_aadhar_enrolment_1000000_1006029.csv
    api_data_aadhar_enrolment_500000_1000000.csv
  page_modules/
    anomaly_detection.py
    biometrics.py
    dashboard.py
    demographics.py
    enrolment.py
```

<br/>

## Technical Specifications

| Attribute | Detail |
|:---|:---|
| **Primary Language** | `Python` |
| **Project Category** | `API / Backend Service` |
| **Total Source Files** | `37` |
| **Frameworks** | `Streamlit` |
| **Key Dependencies** | `numpy` | `scikit-learn` | `pandas` | `plotly` | `streamlit` | `python-dateutil` | `openpyxl` |
| **Intellectual Property** | `Strictly Proprietary` |

<br/>

## STRICT LEGAL WARNING & LICENSE

> **PROPRIETARY AND CONFIDENTIAL**

This software and all associated documentation are the **exclusive property of Karthik Idikuda**.

- **NO PERMISSION IS GRANTED** to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of this software without explicit, written consent from the author.
- **UNAUTHORIZED USE WILL RESULT IN SEVERE LEGAL ACTION.** Any individual or organization found using, referencing, or deploying this code without paying the required licensing fees will face immediate litigation, financial penalties, and potentially criminal prosecution where applicable by law.
- **TO OBTAIN A LEGAL LICENSE**, you must directly contact Karthik Idikuda to negotiate payment terms.

*By accessing this repository, you acknowledge and accept these strict proprietary terms.*

---

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=600&size=18&pause=1000&color=FF6E96&center=true&vCenter=true&width=535&lines=Engineered+by+Karthik+Idikuda;API+%2F+Backend+Service+Architecture;Strict+Proprietary+License" alt="Typing SVG" />
</div>

<!-- TRACKING: S0ktQWFkaGFhckluc2lnaHQzNjAtVFJBQ0s= -->
