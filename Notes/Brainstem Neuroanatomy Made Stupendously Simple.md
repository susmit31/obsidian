# Skills to Achieve
For commonly tested stroke variants, we have to
- Locate lesions (\*\*\*)
- Predict functional deficits (in addition to the ones mentioned in the vignette) (\*\*)
- Identify arteries involved (\*\*)
## Why?
To motivate the forthcoming study plan and the previously stated target skills, we'll take a look at a table differentiating between common brainstem stroke syndromes.

### Key Brainstem Syndromes Distilled

| **Syndrome**                | **Location**                                                               | **Artery**                                      | **CN(s) Involved**                        | **Tract(s) Involved**                                                                             | **Key Features**                                                                                                                      |
| --------------------------- | -------------------------------------------------------------------------- | ----------------------------------------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| **Claude Syndrome**         | **Midbrain** (Red nucleus, superior cerebellar peduncle, CN III fascicles) | **Posterior cerebral artery (PCA)**             | **Oculomotor nerve (CN III)**             | **Corticospinal tract**, **Superior cerebellar peduncle**                                         | - **Contra hemiparesis** <br> - **Contra ataxia** <br> - **i3**                                                                       |
| **Weber Syndrome**          | **Midbrain** (Cerebral peduncle, CN III fascicles)                         | **Paramedian branches of basilar artery**       | **Oculomotor nerve (CN III)**             | **Corticospinal tract**                                                                           | - **Contra hemiparesis** <br> - **i3c7u**                                                                                             |
| **Parinaud Syndrome**       | **Midbrain** (Dorsal midbrain, tectum)                                     | **Superior cerebellar artery** (br. of basilar) | **None** (gaze center only)               | **Pretectal area**, **Vertical gaze center**                                                      | - **Paralysis of upgaze** <br> - **Light-near dissociation** <br> - **Eyelid retraction (Collier sign)**                              |
| **Millard-Gubler Syndrome** | **Pons** (Ventral pons, CN VI & VII fascicles)                             | **Basilar artery**                              | **Abducens (CN VI)**, **Facial (CN VII)** | **Corticospinal tract**                                                                           | -**Contra hemiparesis**<br>- **i6, i7**                                                                                               |
| **Wallenberg Syndrome**     | **Medulla** ("Walls" of medulla = Lateral medulla)                         | **PICA**, **Vertebral artery**                  | **CN V nucleus**, **CN IX**, **CN X**     | **Spinothalamic tract**, **Spinal trigeminal tract**, **Vestibular nuclei**, **Nucleus ambiguus** | - **Ipsi facial pain/temp loss** <br> - **Contra body pain/temp loss** <br> - **Dysphagia, hoarseness** <br> - **Vertigo, nystagmus** |

# Skills-Oriented Study Plan
We have to master the following topics in order to hammer down the aforementioned skills:
- Know the **basic sensory and motor tracts** including their pathways and functions
	- Tracts:
		- Corticospinal
		- Spinothalamic
		- Dorsal column-medial lemniscal system (DCMLS)
		- Corticobulbar
	- Pathways: must know where each of these tracts
		- Decussate (if it does)
		- is located in
			- Cerebral cortex
			- Int. capsule
			- Midbrain
			- Pons
			- Medulla
			- Spinal cord
- Know the **locations of the cranial nerve nuclei**
- Know the anatomical and/or vascular supply-based **subdivisions** in **cross sections** of the different areas of the **brainstem**
	- Midbrain: Crus, tegmentum, tectum (from A to P)
	- Pons
	- Medulla
- Know the **arterial supply** of the different parts
# Tracts
## Corticospinal tract
### Functions
- Convey all motor signals to voluntary muscles
### Pathway

```mermaid
flowchart TD
    PreGyrus[Precentral gyrus] --> Corona[Corona radiata]
    Corona --> PLCap[Posterior limb of internal capsule]
    PLCap --> CerebralPed[Cerebral peduncle<br/> @crus cerebri,<br/> midbrain]
    CerebralPed2[Cerebral peduncle]
    CerebralPed2 --> VPons[Ventral pons]
    VPons --> InfPyr[Anteroinferior part of the pyramids]
    InfPyr -->|85%| LCT[Lateral<br/> corticospinal<br/> tract]
    InfPyr --> |15%| ACT[Anterior<br/> corticospinal<br/> tract]

```
## Spinothalamic tract
### Functions
- **Anterior**: Crude touch, pressure
- **Lateral**: Pain, temperature
### Pathway
```mermaid
flowchart TD
	Cross[Cross within 2 segments] --> LMedulla[Lateral medulla - ascend as spinal lemniscus]
	LMedulla --> LPons[Dorsolateral pons]
	LPons --> _[Posterior Tegmentum of midbrain i.e. immediately adjacent to the aqueduct]
	Midbrain[Midbrain @tegmentum]
	Midbrain --> VPL[Ventral Posterolateral Thalamus]
	VPL --> PLICap[Posterior limb of internal capsule]
	PLICap --> PCGyrus[Post central gyrus]
```

## DCMLS
### Functions
- Fine touch, vibration
### Pathway
```mermaid
flowchart TD
	DCol[Dorsal Column] --> Medulla[Continue as fasciculus gracilis and cuneatus, upto posterosuperior part of medulla]
	Medulla --> Decuss[Decussation at<br/> superior medulla<br/>beginning of <br/>medial lemniscus]
	Decuss2[Decussation at<br/> superior medulla]
	Decuss2 --> MLem[Medial lemniscus from<br/> medial-superior medulla<br/> upto lateral midbrain<br/> at superior colliculus]
	MLem --> |Head<br/> sensations|VPM[Ventral<br/> Postero-Medial<br/> Thalamus]
	MLem --> |Neck, trunk,<br/> limbs|VPL[Ventral<br/> Postero-Lateral<br/> Thalamus]
```

# 🧠 Blood Supply of the Midbrain — Clinical Overview (Updated with Red Nucleus)

| Artery                        | Supplied Territory                             | Key Structures                                 | Clinical Correlates                             |
|------------------------------|-------------------------------------------------|------------------------------------------------|--------------------------------------------------|
| **Posterior Cerebral Artery** (PCA) <br> — paramedian & short circumferential branches | Anteromedial & medial tegmentum                | - **Cerebral peduncle** <br> - **Oculomotor nerve fascicles** <br> - **Substantia nigra** <br> - **Red nucleus** | **Weber syndrome** (CN III palsy + contralateral hemiparesis) <br> **Claude syndrome** (CN III palsy + contralateral ataxia/tremor) <br> **Benedikt syndrome** (CN III palsy + contralateral tremor + choreoathetosis) |
| **Quadrigeminal artery** <br> (branch of PCA) | Dorsal midbrain (tectum)                        | - **Superior & inferior colliculi** <br> - **Pretectal area** | **Parinaud syndrome** (upgaze palsy, light-near dissociation, convergence-retraction nystagmus) |
| **Posterior choroidal arteries** (PCA branches) | Posterior/dorsal midbrain + thalamus           | - Pretectum <br> - Pineal region structures <br> - Thalamic pulvinar | Can contribute to **Parinaud syndrome** or **thalamic syndromes** |
| **Superior Cerebellar Artery** (SCA) | Lateral & inferior midbrain, esp. caudal tectum | - Inferior colliculus <br> - Superior cerebellar peduncle <br> - Decussation of dentatorubrothalamic fibers | May overlap in **Claude syndrome** (via cerebellar pathways) <br> Rarely contributes to **Parinaud** if inferior colliculus involved |
| **Basilar artery (top end)** | Ventral midbrain                                 | - Basis pedunculi <br> - CN III rootlets       | Can cause **Weber-like syndromes** due to overlap with PCA territory |

---

### 🧠 Named Midbrain Stroke Syndromes (Refreshed)

| Syndrome          | Lesion Site                              | Artery Involved             | Key Features                                       |
|------------------|------------------------------------------|-----------------------------|----------------------------------------------------|
| **Weber**        | Cerebral peduncle + CN III fascicles      | PCA (paramedian branch)     | CN III palsy + contralateral hemiplegia            |
| **Claude**       | **Red nucleus** + CN III fascicles        | PCA (paramedian) ± SCA      | CN III palsy + contralateral ataxia/tremor         |
| **Benedikt**     | Red nucleus + **medial tegmentum**        | PCA (paramedian)            | CN III palsy + contralateral tremor + athetosis    |
| **Parinaud**     | **Pretectal area** and **superior colliculi** | Quadrigeminal / Posterior choroidal | Vertical gaze palsy, convergence-retraction nystagmus, light-near dissociation |

---

💡 **Clinical Insight**:  
If a patient has **CN III palsy + contralateral cerebellar signs (ataxia, tremor)** → suspect **red nucleus involvement** = **Claude or Benedikt syndrome** → Think **PCA (paramedian branches)** ± **SCA** if cerebellar fibers are more involved.

# 🧠 Brainstem Blood Supply — Medulla & Pons

---

## 🧠 MEDULLA

| Artery                          | Supplied Territory                      | Key Structures                                                                 | Clinical Syndromes                                      |
|---------------------------------|------------------------------------------|---------------------------------------------------------------------------------|----------------------------------------------------------|
| **Anterior spinal artery**      | Anteromedial medulla                     | - Pyramids (corticospinal tract) <br> - Medial lemniscus <br> - CN XII nucleus/fascicles | **Medial medullary syndrome (Dejerine)**<br>—Contralateral hemiparesis<br>—Contralateral proprioception loss<br>—Ipsilateral tongue weakness |
| **Posterior inferior cerebellar artery (PICA)** | Lateral medulla                        | - Spinothalamic tract <br> - Spinal trigeminal nucleus <br> - Vestibular nuclei <br> - Nucleus ambiguus <br> - Inferior cerebellar peduncle | **Lateral medullary syndrome (Wallenberg)**<br>—Dysphagia, hoarseness<br>—Contralateral body pain/temp loss<br>—Ipsilateral face pain/temp loss<br>—Vertigo, nystagmus, ataxia |
| **Vertebral artery** (direct branches) | Lateral & ventrolateral medulla        | Often overlaps with PICA territory; supplies similar areas                       | Can mimic Wallenberg; large infarcts may affect both medial & lateral areas |

---

## 🧠 PONS

| Artery                              | Supplied Territory                    | Key Structures                                                                 | Clinical Syndromes                                      |
|-------------------------------------|----------------------------------------|---------------------------------------------------------------------------------|----------------------------------------------------------|
| **Paramedian branches of basilar artery** | Anteromedial pons                     | - Corticospinal tract <br> - Medial lemniscus <br> - CN VI nucleus/fascicles <br> - CN VII fascicles (sometimes) | **Medial pontine syndrome (Foville or Raymond)**<br>—Contralateral hemiparesis<br>—Contralateral vibration/proprioception loss<br>—Ipsilateral CN VI or VII palsy |
| **Short circumferential branches (basilar)** | Anterolateral pons                   | - Middle cerebellar peduncle <br> - Pontine nuclei <br> - CN V motor/sensory roots | Rarely isolated infarcts; may contribute to **ataxia, facial weakness** |
| **Long circumferential branches (AICA)** | Lateral caudal pons                  | - Spinothalamic tract <br> - Spinal trigeminal nucleus <br> - Vestibular nuclei <br> - CN VII nucleus/fibers <br> - Inferior cerebellar peduncle | **Lateral pontine syndrome (AICA infarct)**<br>—Facial paralysis<br>—Hearing loss<br>—Vertigo, nausea<br>—Contralateral pain/temp loss |
| **Superior cerebellar artery (SCA)** | Dorsolateral rostral pons + cerebellum | - Superior cerebellar peduncle <br> - Lateral lemniscus <br> - Cerebellar structures | May cause **ataxia**, dysmetria, contralateral sensory changes; overlaps with midbrain in some infarcts |

---

## 🧠 Summary of Named Brainstem Syndromes

| Syndrome                 | Level     | Territory Affected           | Artery                       | Key Features |
|--------------------------|-----------|-------------------------------|------------------------------|--------------|
| **Medial medullary (Dejerine)** | Medulla   | Anteromedial                  | Anterior spinal              | Hemiparesis, proprioception loss, tongue deviation |
| **Lateral medullary (Wallenberg)** | Medulla   | Lateral                       | PICA                         | Dysphagia, ataxia, Horner's, pain/temp loss        |
| **Medial pontine (Foville/Raymond)** | Pons      | Anteromedial                  | Paramedian basilar           | CN VI/ VII palsy, hemiparesis                      |
| **Lateral pontine (AICA)**        | Pons      | Lateral caudal                | AICA                         | CN VII palsy, vertigo, hearing loss, ataxia        |

---

🧠 **Key Clinical Pearls**:
- Medial = **motor** → corticospinal tract + CN nuclei → hemiparesis + cranial nerve palsy.
- Lateral = **sensory + cerebellar + autonomic** → ataxia, vertigo, Horner’s, dissociated sensory loss.
- CN localization helps determine level:  
  - CN XII = medulla  
  - CN VI/VII = pons  
  - CN III = midbrain


