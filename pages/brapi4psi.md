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

# BrAPI4PSI
## IPK Phenosphere

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

<div class="grid grid-cols-2 gap-2">
    <img class="w-full" src="/assets/phenosphere.png">
    <img class="w-full" src="/assets/phenosphere-sim.png">
</div>

- Phenosphere can recreate single field season with similar plant growth and development progression
    - illumination, air temperature, relative air humidity, wind simulation, CO$_2$, automated watering, aerial and soil sensors
    - Heuermann et al., 2023; Nat. Comm. 14:5783

---

# BrAPI4PSI
## PhenoCrane System

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

<div class="grid grid-cols-2 gap-2">
    <img class="w-full" src="/assets/2024-10_PhenoSphere-Raps-1142__IPK_Leibniz-Institut-J._Himpe.jpeg">
    <img class="w-full" src="/assets/PhenoSphere_PhenoCrane3_IPK-Bähring.jpeg">
</div>

- PhenoCrane generates images daily for HTP using multiple camera modalities
    1. high-res RGB (architectural & color-related traits)
    1. 3D laser scanner (precise canopy height)
    1. FluorCam (Chlorophyll fluoresence)
    1. Visible-NIR hyperspec (score abiotic/biotic stresses)

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
  <img data-id="arc" class="w-1/8 absolute top-[60%] left-[22%]" src="/assets/arc.png" />
</div>

<v-clicks>
  <FancyArrow from="[data-id=wizard]@right" to="[data-id=psi]@left"/>
  <FancyArrow from="[data-id=psi]@bottom" to="[data-id=phenosphere]@top" two-way/>
  <FancyArrow from="[data-id=psi]@right" to="[data-id=brapi]@left"/>
  <FancyArrow from="[data-id=brapi]@top" to="[data-id=wizard]@top" arc="-0.25"/>
  <FancyArrow from="[data-id=wizard]@bottom" to="[data-id=arc]@top" />
</v-clicks>

---

# Results (so far)

<v-clicks>

- Extended the scope of the Use Case Pilot with the ISA Wizard for intuitive metadata annotation
- Development of new components for the ISA Wizard
    - Skippable protocols
    - Optional step explanations
    - BrAPI-enabled image importer
- Works of the use case can be reused by other HTP infrastructures using PSI hardware
- Started work on data deposition scripts

</v-clicks>