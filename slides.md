---
theme: mint
transition: fade
image: https://images.unsplash.com/photo-1648478066584-51e90edcb884?q=80&w=524&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
addons:
  - slidev-component-pager
  - slidev-addon-rabbit
  - fancy-arrow
  #- slidev-addon-python-runner
---

# Plant Data Commons

<div style="position: absolute; bottom: 1%; right: 1%; font-size: .5rem; font-style: italic;">
  Image by Marek Studzinski, Unsplash license
</div>



---
src: pages/pdc-gorc.md
---

---
layout: image-left
image: https://martinfowler.com/articles/data-mesh-principles/architecture.png
imageClass: h-3/4 relative translate-y-10
---

# Data Mesh

<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 3.5%;">
  <div style="
    width: 120px;
    height: 100px;
    background: #acdbaeff;
    position: relative;
    margin: 0 auto;
    clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-weight: bold;
    font-size: .5em;
    text-align: center;
    flex-direction: column;
    ">
    <img src="/assets/noun-governance-chart-6127970.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
    <span>Governance<br>Structure</span>
  </div>
</div>

- Organisation in four principles [1]
  - Domain-oriented decentralized data ownership and architecture
  - Data as a product
  - Self-serve data infrastructure as a platform
  - Federated computational governance


<div style="position: absolute; bottom: 1%;">
  <hr>
  <span style="font-size: .5rem;">[1] <a target="_blank" href="https://martinfowler.com/articles/data-mesh-principles.html">Data Mesh Principles by Zhamak Dehghani</a></span>
</div>

---

# Completing the LARA ARC
## Machine-actionable Usage Information
<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
    <div style="
      width: 120px;
      height: 100px;
      background: #106d13ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-interoperability-7759150.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Interoperability &<br>Standards</span>
    </div>
  </div>
</div>

<v-clicks>

- Project at the BioHackathon Germany on creation of data use agreements
- Open Digital Rights Language (ODRL) used as standardized, machine-actionable expression language of usage information
- Established NFDI Section ELSA Working Group LARA
  - Address questions in data and software licensing
  - Develop a tool to check and license data and software for research
  - Two main services identified (License Checker, ODRL Builder)

</v-clicks>

---
layout: image-right
image: /assets/odrl-builder-reproduction.png
---

# ODRL Builder
<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; right: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
    <div style="
      width: 120px;
      height: 100px;
      background: #106d13ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-interoperability-7759150.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Interoperability &<br>Standards</span>
    </div>
  </div>
</div>

- Questionnaire-based web application for the creation of data use agreements
- Utilization of ODRL
- Allows rendering of the data use agreement as a pdf file (human-readable format)
- Provides validation capabilities
- Integration into PLANTdataHUB (CI/CD workflow)

---

# Fragment-Level FAIRness
## Machine-actionable Plant Phenomics
<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
    <div style="
      width: 120px;
      height: 100px;
      background: #106d13ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-interoperability-7759150.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Interoperability &<br>Standards</span>
    </div>
  </div>
</div>

<v-clicks>

- **Fragment selector**: Precisely identify and reference specific parts of a dataset rather than just the whole file
  - e.g. single values, rows or columns
  - Enables fine-grained annotation, citation and reuse of data fragments

- **Data map**: Structured overview of the dataset, describing how each fragment is organized, what it represents, and how it can be accessed
  - Make it easier for both humans and machines to discover, interpret, and connect relevant data fragments.

- Together, fragment selectors and data maps enable machine-actionable, context-rich access to plant phenomics data

</v-clicks>

---

<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
    <div style="
      width: 120px;
      height: 100px;
      background: #106d13ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-interoperability-7759150.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Interoperability &<br>Standards</span>
    </div>
  </div>
</div>

<v-click>
  <FancyArrow from="(700, 80)" to="(850, 130)" arc="0.25" color="yellow"/>
  <div class="shadow-md" style="position: absolute; left: 50%; top: 2% ;width: 16.5em; background-color: #FBCC15; display: flex; flex-direction: column; padding: .5em; border-radius: 10px;">
    <span>Powdery Mildew Susceptibility?</span>
    <span>Photosynthetic Mass?</span>
    <span>Plant Maturity?</span>
  </div>
</v-click>

<v-click>
  <FancyArrow from="(700, 450)" to="(770, 300)" arc="0.25" color="red"/>
  <div class="shadow-md" style="position: absolute; left: 55%; bottom: 2% ;width: 13em; background-color: #F87171; display: flex; flex-direction: column; padding: .5em; border-radius: 10px;">
    <span>What does this mean?</span>
    <span>Relative to sowing date?</span>
    <span>Relative to January 1st?</span>
  </div>
</v-click>

<v-click>
  <FancyArrow from="(500, 200)" to="(280, 135)" arc="-0.25" color="blue"/>
  <div class="shadow-md" style="position: absolute; left: 45%; top: 30%; width: 14em; background-color: #5FA5FA; display: flex; flex-direction: column; padding: .5em; border-radius: 10px;">
    <span>Those are varieties?!</span>
    <span>What samples are meant?</span>
    <span>Where can I find metadata?</span>
  </div>
</v-click>

<div class="flex justify-center items-center h-[45vh]">

| **Plant**       | **TKW** | **PH** | **FT** | **PM** |
|-----------------|---------|--------|--------|--------|
| Barke           | 48.2    | 95     | 62     | 2      |
| Morex           | 45.7    | 102    | 65     | 3      |
| Golden Promise  | 43.5    | 88     | 60     | 4      |
| Scarlett        | 47.1    | 97     | 63     | 2      |
| Steptoe         | 44.8    | 100    | 67     | 5      |

</div>

---


<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
    <div style="
      width: 120px;
      height: 100px;
      background: #106d13ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-interoperability-7759150.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Interoperability &<br>Standards</span>
    </div>
  </div>
</div>

<div class="flex justify-center items-center h-[45vh]">

| **Plant**       | **Trait** | **Value** |
|-----------------|-----------|-----------|
| Barke           | TKW       | 48.2      |
| Barke           | PH        | 95        |
| Barke           | FT        | 62        |
| Barke           | PM        | 2         |
| ...             | ...       | ...       |

<v-click>
  <img style="position: absolute; border-radius: 10px" src="https://i.redd.it/e9ehkgy9n3ed1.gif">
</v-click>

</div>

---

# How to fix this situation 
## (and MIAPPE incidentally)
<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
    <div style="
      width: 120px;
      height: 100px;
      background: #106d13ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-interoperability-7759150.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Interoperability &<br>Standards</span>
    </div>
  </div>
</div>

<div class="p-2">
<div class="flex flex-row gap-2">
  <div class="w-1/2 rounded p-2" style="font-size: 0.5em; background-color: #FBCC15">
  <b>Data Map</b>

  | **Data**       | **Explication**      | **Object Type** | **Unit** |
  |----------------|----------------------|-----------------|----------|
  |result.csv#col=1|Sample ID             |string           |          |
  |result.csv#col=2|[Thousand Kernel Weight](https://cropontology.org/rdf/CO_323:0000036)|[float](http://purl.obolibrary.org/obo/NCIT_C48150)            |[gram](http://purl.obolibrary.org/obo/UO_0000021)         |

  </div>

  <div class="w-1/2 rounded p-2" style="font-size: 0.5em; background-color: #5FA5FA">
  <b>Assay Annotation Table</b>

  | **Input[Sample Name]** | **Protocol REF** | **Parameter[Observation Date]** | **Output[Data]** |
  |------------------------|------------------|---------------------------------|------------------|
  |Barke-1-1               |Phenotyping       |01.05.25                         |result.csv#row=2  |
  |Morex-1-2               |Phenotyping       |01.05.25                         |result.csv#row=3  |

  </div>
</div>

<div style="font-size: .75rem">

| **Plant**       | **TKW** | **PH** | **FT** | **PM** |
|-----------------|---------|--------|--------|--------|
| Barke           | 48.2    | 95     | 62     | 2      |
| Morex           | 45.7    | 102    | 65     | 3      |
| Golden Promise  | 43.5    | 88     | 60     | 4      |
| Scarlett        | 47.1    | 97     | 63     | 2      |

</div>

<div class="border border-[#5FA5FA] absolute rounded-xl" style="width: 70%; height: 5%; top: 61.5%">
</div>
<div class="border border-[#FBCC15] absolute rounded-xl" style="width: 4%; height: 40%; top: 53%; left: 53.75%">
</div>
</div>

---
layout: image-right
image: /assets/phenoapp-datafile.png
---

# PhenoApp
<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; right: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
    <div style="
      width: 120px;
      height: 100px;
      background: #106d13ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-interoperability-7759150.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Interoperability &<br>Standards</span>
    </div>
  </div>
</div>

<div style="position: absolute; right: 20%; top: 1%; font-size: .5rem; font-style: italic;">
  Internship project of Alexander Cichacki
</div>

- Having a well annotated ARC allows programmatic access to the research object
- Development of a web application
  - Visual exploration of phenomic data
  - Overview of the status of the investigation
  - Identity by provenance visualization

---

# BrAPI4PSI
## Automated Plant Phenotyping Facilities
<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
    <div style="
      width: 120px;
      height: 100px;
      background: #106d13ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-interoperability-7759150.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Interoperability &<br>Standards</span>
    </div>
  </div>
</div>

<v-clicks>

- Starting Point
  - Proprietary systems used to store and analyze image data
  - Vendor lock-in hinders **reuse** and **FAIR compliance**
  - Integration of **open, standardized** Access through **Breeding API (BrAPI)**

- Goal
  - Implementation of BrAPI endpoints by PSI
  - Development of processes to integrate this data into **FAIR Digital Objects**

</v-clicks>

---

<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
    <div style="
      width: 120px;
      height: 100px;
      background: #106d13ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-interoperability-7759150.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Interoperability &<br>Standards</span>
    </div>
  </div>
</div>

<div class="">
  <img data-id="wizard" class="w-1/8 absolute top-[15%] left-[22%]" src="https://github.com/IPK-BIT/isa-wizard/blob/main/data/logo.png?raw=true"/>
  <div data-id="psi" class="w-1/8 h-20 bg-neutral-300 rounded border border-black p-2 text-center flex items-center justify-center absolute top-[19%] left-[50.5%]">PSI System</div>
  <img data-id="brapi" class="w-1/8 absolute top-[15%] left-[80%]" src="https://avatars.githubusercontent.com/u/7597119?s=280&v=4">
  <img data-id="phenosphere" class="w-1/3 absolute top-[42%] left-[40%]" src="https://www.ipk-gatersleben.de/fileadmin/content-presse/Foto/PhenoSphere/2024/Phenosphere_Raps-5834__IPK_Leibniz-Institut-J.-S._Himpe.JPG"/>
  <img data-id="arc" class="w-1/8 absolute top-[60%] left-[22%]" src="https://www.nfdi4plants.org/_astro/toolbox-hero.C9LAvQUr_Z2gN18y.svg" />
</div>

<v-clicks>
  <FancyArrow from="[data-id=wizard]@right" to="[data-id=psi]@left"/>
  <FancyArrow from="[data-id=psi]@bottom" to="[data-id=phenosphere]@top" two-way/>
  <FancyArrow from="[data-id=psi]@right" to="[data-id=brapi]@left"/>
  <FancyArrow from="[data-id=brapi]@top" to="[data-id=wizard]@top" arc="-0.25"/>
  <FancyArrow from="[data-id=wizard]@bottom" to="[data-id=arc]@top" />
</v-clicks>

---

# Monitoring of Key Performance Indicators for ELIXIR(-DE) Services
<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px">
    <div style="
      width: 120px;
      height: 100px;
      background: #42a846ff;
      position: relative;
      margin: 0 auto;
      clip-path: polygon(25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%, 0% 50%);
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-weight: bold;
      font-size: .5em;
      text-align: center;
      flex-direction: column;
      ">
      <img src="/assets/noun-metrics-7736200.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
      <span>Metrics</span>
    </div>
  </div>
</div>

<v-clicks>

- Setup of Scorpion instance within Working Group Service and Service Monitoring (SAM)
  - Started monitoring of services with volunteers from GCBN and Bioinfra.Prot
  - Use of Scorpion to facilitate service portfolio management and reporting duties within de.NBI
  - Automation of KPI submission from Matomo instances
- Presented Scorpion at BioHackathon Europe within project on identifying solutions for monitoring of KPIs of ELIXIR services
  - Results will feedback into development of Scorpion (KPI ontology, pull approach, etc.)
- Scorpion paper in review for publication in Journal of Integrative Bioinformatics

</v-clicks>

---
layout: end
---

# Thank you for your attention!