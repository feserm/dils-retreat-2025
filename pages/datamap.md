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


<div class="absolute w-3/4 top-[20%]">

| **Plant**       | **TKW** | **PH** | **FT** | **PM** |
|-----------------|---------|--------|--------|--------|
| Barke           | 48.2    | 95     | 62     | 2      |
| Morex           | 45.7    | 102    | 65     | 3      |
| Golden Promise  | 43.5    | 88     | 60     | 4      |
| Scarlett        | 47.1    | 97     | 63     | 2      |
| Steptoe         | 44.8    | 100    | 67     | 5      |

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

---

<div class="absolute w-3/4 top-[20%]">

| **Plant**       | **Trait** | **Value** |
|-----------------|-----------|-----------|
| Barke           | TKW       | 48.2      |
| Barke           | PH        | 95        |
| Barke           | FT        | 62        |
| Barke           | PM        | 2         |
| ...             | ...       | ...       |


</div>

<v-click>
  <img class="top-[20%] left-[40%]" style="position: absolute; border-radius: 10px" src="https://i.redd.it/e9ehkgy9n3ed1.gif">
</v-click>

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

# Trait Definition within MIAPPE (classic)

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

<div class="text-sm text-gray-500 italic flex flex-col">
<span>

"The trait definition file includes the attributes from MIAPPE's Observed Variable section. The column headers are directly taken from MIAPPE, so no mapping is listed here."

</span>
<span>

"There should be one trait definition file per study. Its filename is indicated in the Study section of the Investigation file."

</span>
<span>

  "Additionally, you must use the `Comment[Trait Definition File]` to indicate the name of the file holding the descriptions of all observed variables."
  
</span>
</div>

---

# ARC Structure (classic)

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

<div class="flex justify-center">

<v-click>
  <FancyArrow from="[data-id=tdf]@right" to="(650, 100)" arc="0.25" color="blue"/>
  <div data-id="tdf" class="shadow-md" style="position: absolute; left: 20%; top: 15% ;width: 20em; background-color: #60A5FA; display: flex; flex-direction: column; padding: .5em; border-radius: 10px;">
    <table class="text-[.5rem] bg-white opacity-80 rounded">
      <thead>
        <tr>
          <th>Variable</th>
          <th>Trait</th>
          <th>Method</th>
          <th>Scale</th>
          <th>Scale Type</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>AWNS_LENGTH</td>
          <td>Awn Length</td>
          <td>Measurement</td>
          <td>cm</td>
          <td>numerical</td>
        </tr>
        <tr>
          <td>RACHILLA_HAIRS</td>
          <td>Rachilla Hair Length</td>
          <td>Estimation</td>
          <td>1:short;2:long</td>
          <td>ordinal</td>
        </tr>
      </tbody>
    </table>
  </div>
</v-click>

<v-click>
  <FancyArrow from="[data-id=datafile]@right" to="(745, 350)" arc="-0.25" color="blue"/>
  <div data-id="datafile" class="shadow-md" style="position: absolute; left: 40%; top: 50% ;width: 15em; background-color: #60A5FA; display: flex; flex-direction: column; padding: .5em; border-radius: 10px;">
    <table class="text-[.5rem] bg-white opacity-80 rounded">
      <thead>
        <tr>
          <th>Sample</th>
          <th>AWNS_LENGTH</th>
          <th>RACHILLA_HAIRS</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>HOR 13800_1</td>
          <td>18.0</td>
          <td>2</td>
        </tr>
        <tr>
          <td>HOR 8710_1</td>
          <td>9.0</td>
          <td>2</td>
        </tr>
        <tr>
          <td>HOR 10886_1</td>
          <td>20.0</td>
          <td>2</td>
        </tr>
      </tbody>
    </table>
  </div>
</v-click>


<v-click>
  <div class="shadow-md" style="position: absolute; left: 40%; top: 50% ;width: 15em; background-color: #60A5FA; display: flex; flex-direction: column; padding: .5em; border-radius: 10px;">
    <table class="text-[.5rem] bg-white opacity-80 rounded">
      <thead>
        <tr>
          <th>Sample</th>
          <th>Variable</th>
          <th>Value</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>HOR 13800_1</td>
          <td>AWNS_LENGTH</td>
          <td>18.0</td>
        </tr>
        <tr>
          <td>HOR 13800_1</td>
          <td>RACHILLA_HAIRS</td>
          <td>2</td>
        </tr>
        <tr>
          <td>HOR 8710_1</td>
          <td>AWNS_LENGTH</td>
          <td>9.0</td>
        </tr>
      </tbody>
    </table>
  </div>
</v-click>

```mermaid {theme: 'forest', scale: .55}
flowchart LR
  arc[BRIDGE Core 50]
  i([Investigation])
  s[Studies]
  a[Assays]
  arc-->s
  arc-->a
  arc-->i
  s1[spike-investigation-2015]
  s-->s1
  s1tdf([tdf.tsv])
  s1-->s1tdf
  s1s([Study])
  s1p[Protocols]
  s1-->s1s
  s1-->s1p
  s1pg([growth.md])
  s1p-->s1pg
  a1[tmp]
  a-->a1
  a1p[Protocols]
  a1d[Dataset]
  a1a([Assay])
  a1-->a1p
  a1-->a1d
  a1-->a1a
  a1pp([phenotyping.md])
  a1pi([imaging.md])
  a1p-->a1pp
  a1p-->a1pi
  a1dd([df.csv])
  a1dp[Photos]
  a1d-->a1dd
  a1d-->a1dp
  a1dp1([HOR_10886.jpg])
  a1dp2([...])
  a1dp-->a1dp1
  a1dp-->a1dp2
```

</div>


---

# Trait Definition within MIAPPE (improved)

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

<div class="grid grid-cols-2 gap-6">

<div>
  <h3 class="text-yellow-700 font-bold mb-2">Problem</h3>
  <ul class="list-disc pl-6 mb-2">
    <li>In ARCs, Assays are not embedded in a Study.</li>
    <li>How can we ensure the linking between the Trait Definition File (in the Study) and the Data File (in the Assay)?</li>
  </ul>
  <h4 class="text-green-700 font-semibold mb-1">Solution</h4>
  <ul class="list-disc pl-6">
    <li>Trait Definition needs to be part of an Assay.</li>
    <li>Use the Datamap to annotate the meaning of the variables.</li>
  </ul>
</div>

<div>
  <h3 class="text-yellow-700 font-bold mb-2">Problem</h3>
  <ul class="list-disc pl-6 mb-2">
    <li>Datamap not expandable to structure of the Trait Definition File.</li>
    <li>Headers are predefined and Comments should not be the option of choice.</li>
  </ul>
  <h4 class="text-green-700 font-semibold mb-1">Solution</h4>
  <ul class="list-disc pl-6">
    <li>Use the ontology-annotated Explication to point to an ontology term.</li>
    <li>If no public ontology terms are available, define them yourself in a local ontology file.</li>
  </ul>
</div>

</div>



---

# ARC Structure (improved)

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
<div class="flex justify-center">

<v-click>
  <FancyArrow from="[data-id=tdf]@right" to="(725, 330)" arc="-0.25" color="blue"/>
    <div data-id="tdf" class="shadow-md" style="position: absolute; left: 40%; top: 2% ;width: 15em; background-color: #60A5FA; display: flex; flex-direction: column; padding: .5em; border-radius: 10px;">
    <pre class="text-[.5rem] bg-white opacity-80 rounded p-2">
format-version: 1.2
ontology: local-trait-definition<br>
[Term]
id: LOCAL:0000001
name: Observation Variable
def: "Root term for all observation variable" []<br>
[Term]
id: LOCAL:0000002
name: Trait
def: "Root term for all traits" []<br>
[Term]
id: LOCAL:0000003
name: Method
def: "Root term for all methods" []<br>
[Term]
id: LOCAL:0000004
name: Scale
def: "Root term for all scales." []
  </pre>
  </div>
</v-click>

<v-click>
  <FancyArrow from="[data-id=datafile]@right" to="(750, 380)" arc="-0.25" color="blue"/>
  <div data-id="datafile" class="shadow-md" style="position: absolute; left: 40%; top: 60% ;width: 15em; background-color: #60A5FA; display: flex; flex-direction: column; padding: .5em; border-radius: 10px;">
    <table class="text-[.5rem] bg-white opacity-80 rounded">
      <thead>
        <tr>
          <th>Sample</th>
          <th>AWNS_LENGTH</th>
          <th>RACHILLA_HAIRS</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>HOR 13800_1</td>
          <td>18.0</td>
          <td>2</td>
        </tr>
        <tr>
          <td>HOR 8710_1</td>
          <td>9.0</td>
          <td>2</td>
        </tr>
        <tr>
          <td>HOR 10886_1</td>
          <td>20.0</td>
          <td>2</td>
        </tr>
      </tbody>
    </table>
  </div>
</v-click>


<v-click>
  <div class="shadow-md" style="position: absolute; left: 40%; top: 60% ;width: 15em; background-color: #60A5FA; display: flex; flex-direction: column; padding: .5em; border-radius: 10px;">
    <table class="text-[.5rem] bg-white opacity-80 rounded">
      <thead>
        <tr>
          <th>Sample</th>
          <th>Variable</th>
          <th>Value</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>HOR 13800_1</td>
          <td>AWNS_LENGTH</td>
          <td>18.0</td>
        </tr>
        <tr>
          <td>HOR 13800_1</td>
          <td>RACHILLA_HAIRS</td>
          <td>2</td>
        </tr>
        <tr>
          <td>HOR 8710_1</td>
          <td>AWNS_LENGTH</td>
          <td>9.0</td>
        </tr>
      </tbody>
    </table>
  </div>
</v-click>



```mermaid {theme: 'forest', scale: .55}
flowchart LR
  arc[BRIDGE Core 50]
  i([Investigation])
  s[Studies]
  a[Assays]
  arc-->s
  arc-->a
  arc-->i
  s1[spike-investigation-2015]
  s-->s1
  s1s([Study])
  s1p[Protocols]
  s1-->s1s
  s1-->s1p
  s1pg([growth.md])
  s1p-->s1pg
  a1[tmp]
  a-->a1
  a1p[Protocols]
  a1d[Dataset]
  a1a([Assay])
  a1dm([Datamap])
  a1-->a1p
  a1-->a1d
  a1-->a1a
  a1-->a1dm
  a1pp([phenotyping.md])
  a1pi([imaging.md])
  a1po([trait-definition.obo])
  a1p-->a1pp
  a1p-->a1pi
  a1p-->a1po
  a1dd([df.csv])
  a1dp[Photos]
  a1d-->a1dd
  a1d-->a1dp
  a1dp1([HOR_10886.jpg])
  a1dp2([...])
  a1dp-->a1dp1
  a1dp-->a1dp2
```

</div>

---

# The BRIDGE Core 50 ARC

<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
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
        <img src="/assets/noun-definition-7826197.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
        <span>Research Object</span>
    </div>
  </div>
</div>

<div class="p-4 rounded-xl bg-gradient-to-br from-yellow-50 to-blue-50 shadow-lg border border-gray-100">

<div class="mb-4">
  <span class="">BRIDGE provides data from <a target="_blank" href="https://doi.org/10.1038/s41588-018-0266-x" class="text-blue-500 hover:text-blue-700">Milner et al. (2019)</a>, covering molecular passport data for the IPK barley germplasm collection and additional accessions.</span>
</div>

<ul class="list-disc pl-6 space-y-2 text-base text-gray-800">
  <li>
    <span class="font-semibold text-yellow-700">Data includes:</span>
    <ul class="list-[circle] pl-6 space-y-1">
      <li>Passport data for <span class="font-bold text-blue-800">22,626</span> germplasm samples</li>
      <li>Phenotypic data for <span class="font-bold text-blue-800">9,527</span> samples</li>
      <li>SNP matrices for <span class="font-bold text-blue-800">1,052,403</span> variants</li>
      <li>Genetic diversity visualizations (<span class="italic">PCA</span>, <span class="italic">t-SNE</span>)</li>
      <li>GWAS Manhattan plots</li>
    </ul>
  </li>
  <li>
    <span class="font-semibold text-yellow-700">Selection of three core sets using <span class="font-mono bg-gray-100 px-1 rounded">CoreHunter3</span>:</span>
    <ul class="list-[circle] pl-6 space-y-1">
      <li><span class="font-bold text-blue-800">Core 50</span></li>
      <li><span class="font-bold text-blue-800">Core 200</span></li>
      <li><span class="font-bold text-blue-800">Core 1000</span></li>
    </ul>
  </li>
</ul>

</div>

---
layout: image-right
image: /assets/bridge-pca-core50.png
---

# BRIDGE Core 50 Dataset

<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; right: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
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
        <img src="/assets/noun-definition-7826197.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
        <span>Research Object</span>
    </div>
  </div>
</div>

<div class="grid gap-8">

  <div class="flex flex-col justify-left gap-2">
    <span class="text-yellow-700 font-bold text-base whitespace-nowrap">🌍 By Country:</span>
    <span class="flex flex-wrap gap-1">
      <span class="bg-yellow-100 rounded px-2 py-0.5">Germany <b>(6)</b></span>
      <span class="bg-yellow-100 rounded px-2 py-0.5">Turkey <b>(5)</b></span>
      <span class="bg-yellow-100 rounded px-2 py-0.5">Ethiopia <b>(4)</b></span>
      <span class="bg-yellow-100 rounded px-2 py-0.5">Nepal <b>(4)</b></span>
      <span class="bg-yellow-100 rounded px-2 py-0.5">USA <b>(3)</b></span>
      <span class="bg-yellow-100 rounded px-2 py-0.5">Egypt <b>(3)</b></span>
      <span class="bg-yellow-100 rounded px-2 py-0.5">UdSSR <b>(3)</b></span>
      <span class="bg-yellow-100 rounded px-2 py-0.5">India <b>(2)</b></span>
      <span class="bg-yellow-100 rounded px-2 py-0.5">Iran <b>(2)</b></span>
      <span class="bg-yellow-100 rounded px-2 py-0.5">China <b>(2)</b></span>
      <span class="bg-yellow-50 rounded px-2 py-0.5" title="Russian Federation, Ukraine, Poland, Czechoslovakia (formerly), Libyan Arab Jamahiriya, Pakistan, Tschad, Afghanistan, Spain, Italy, Switzerland, Peru, Georgia">Others <b>(13 w/ 1 ea.)</b></span>
      <span class="bg-gray-200 rounded px-2 py-0.5">Unknown <b>(3)</b></span>
    </span>
  </div>

  <div class="flex flex-col justify-left gap-2">
    <span class="text-blue-700 font-bold text-base whitespace-nowrap">🌱 By Status:</span>
    <span class="flex flex-wrap gap-1">
      <span class="bg-blue-100 rounded px-2 py-0.5">Traditional cultivar/landrace <b>(36)</b></span>
      <span class="bg-blue-200 rounded px-2 py-0.5">Advanced/improved cultivar <b>(14)</b></span>
    </span>
  </div>

  <div class="flex flex-col justify-left gap-2">
    <span class="text-green-700 font-bold text-base whitespace-nowrap">🌾 By Annuality:</span>
    <span class="flex flex-wrap gap-1">
      <span class="bg-green-200 rounded px-2 py-0.5">Spring <b>(38)</b></span>
      <span class="bg-green-100 rounded px-2 py-0.5">Winter <b>(10)</b></span>
      <span class="bg-green-50 rounded px-2 py-0.5">Intermediate <b>(1)</b></span>
    </span>
  </div>

</div>

<!-- ::right::

<figure>
  <img src="/assets/bridge-pca-core50.png"/>
  <figcaption class="w-full text-justify italic text-xs mt-2 text-gray-500">Genetic Diversity of the BRIDGE dataset, highlighted in green is the core 50 set.</figcaption>
</figure> -->

---

# Phenotyping Data (Numerical)

<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
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
        <img src="/assets/noun-definition-7826197.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
        <span>Research Object</span>
    </div>
  </div>
</div>

<div class="flex gap-16">
<div>

- Observation Variable: `AWNS_LENGTH`
  - Trait: `Awn` `Length`
  - Method: `Measurement`
  - Scale: `cm`

<div class="bg-yellow-50 border border-gray-600 rounded mt-4">

| Sample      | AWNS_LENGTH |
|-------------|-------------|
| HOR 13800_1 | 18.0        |
| HOR 8710_1  | 9.0         |
| HOR 10886_1 | 20.0        |

</div>

</div>
<div>

<PlotlyFigure
  src="https://raw.githubusercontent.com/IPK-BIT/arc-datasteward-circle-miappe/refs/heads/main/snippets/plotly-figures/awn-length.json"
  width="300px"
  height="400px"
  :fontSize="10"
/>

</div>
</div>


---

# Phenotyping Data (Categorical)

<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; left: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
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
        <img src="/assets/noun-definition-7826197.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
        <span>Research Object</span>
    </div>
  </div>
</div>
<div class="flex gap-16">
<div>

- Observation Variable: `RACHILLA_HAIRS`
  - Trait: `Rachilla Hair` `Length`
  - Method: `Estimation`
  - Scale: `1:short;2:long`

<div class="bg-yellow-50 border border-gray-600 rounded mt-4">

| Sample      | RACHILLA_HAIRS |
|-------------|----------------|
| HOR 13800_1 | 2              |
| HOR 8710_1  | 2              |
| HOR 10886_1 | 2              |

</div>

</div>
<div>

<PlotlyFigure
  src="https://raw.githubusercontent.com/IPK-BIT/arc-datasteward-circle-miappe/refs/heads/main/snippets/plotly-figures/rachilla-hairs.json"
  width="300px"
  height="400px"
  :fontSize="10"
/>

</div>
</div>


---
layout: image-right
image: https://raw.githubusercontent.com/feserm/dils-retreat-2025/refs/heads/main/assets/phenoapp-datafile.png
---

# PhenoApp
<div style="width: 120px; margin-bottom: 10px; position: absolute; top: 5%; right: 4%; z-index: 1;">
  <div style="width: 120px; margin-bottom: 10px;">
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
        <img src="/assets/noun-service-tool-7713609.svg" alt="Metrics Icon" style="width:50px; filter: invert(1) brightness(2);" />
        <span>Services & Tools</span>
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
