# GOMITO ARTIFICIALE

## 🇮🇹 ITALIANO

### DESCRIZIONE DEL PROGETTO

Questo progetto, sviluppato per il corso di "Meccanica Applicata alle Macchine" del Politecnico di Milano, analizza e modella un sistema meccanico di gomito artificiale per amputati, azionato da un motore elettrico brushless. Il sistema replica il movimento di flesso-estensione del gomito tramite un meccanismo composto da una vite a ricircolo di sfere e un sistema a glifo oscillante, riducendo attriti, rumorosità e peso complessivo dell'articolazione. Il progetto comprende analisi dettagliate di cinematica, dinamica, azionamento del motore e risposta vibrazionale del sistema.

### CONTENUTI DEL PROGETTO

### CONTENUTI DEL PROGETTO

- **Schema cinematico** comprensivo di tre parti principali: il glifo (meccanismo con asta e corsoio), il quadrilatero articolato (bilancieri e biella) e l'avambraccio (corpo rigido con baricentro e massa concentrata).
<p align="center">
  <img src="img/schema_cinematico.jpg" alt="Schema cinematico" width="600"/>
</p>

- **Analisi cinematica**, con calcoli di velocità, accelerazioni lineari e angolari dei punti principali del sistema mediante MATLAB.
<p align="center">
  <img src="img/schema_cinematico_velocità_accelerazione.jpg" alt="Analisi cinematica" width="600"/>
</p>

- **Legge di moto**, descrizione e simulazione del movimento della protesi nel tempo.
<p align="center">
  <img src="img/legge_moto.jpg" alt="Legge di moto" width="600"/>
</p>

- **Analisi dinamica**, determinazione delle coppie motrici e forze necessarie tramite equilibri dinamici.
<p align="center">
  <img src="img/forze.jpg" alt="Analisi dinamica" width="600"/>
</p>

- **Azionamento motore**, calcolo della coppia ideale, potenza assorbita e capacità massima di sollevamento.
<p align="center">
  <img src="img/azionamento_motore.jpg" alt="Azionamento motore" width="600"/>
</p>

- **Studio delle vibrazioni**, inclusa la definizione e simulazione della risposta dinamica del sistema a forzanti esterne armoniche.

<p align="center">
  <img src="img/funzione_trasferimento.jpg" alt="Funzione di trasferimento" width="600"/><br/>
  <img src="img/coeff_trasmissibilità.jpg" alt="Coefficiente di trasmissibilità" width="600"/><br/>
  <img src="img/risposta_smorzata.jpg" alt="Risposta smorzata" width="600"/><br/>
  <img src="img/risposta_c1.jpg" alt="Risposta a C1" width="600"/><br/>
  <img src="img/risposta_c2.jpg" alt="Risposta a C2" width="600"/><br/>
  <img src="img/risposta_totale.jpg" alt="Risposta totale" width="600"/>
</p>

  

### FILE PRINCIPALI

- `main.m`: Script MATLAB completo che implementa tutte le analisi sopracitate.
- `Report-ITA.pdf`: Relazione tecnica contenente la procedura completa, immagini e risultati dell'elaborato che implementa tutte le analisi sopracitate.

### STRUMENTI

- MATLAB per simulazioni numeriche e analisi.

### RISULTATI CHIAVE

- Coppia motrice ideale: **0.25652 N·m**
- Massa sollevabile dal paziente: **15.7167 kg**
- Frequenza propria del sistema: **0.079615 Hz**
- Range ideale frequenze elettrostimolazione: **≥ 0.16 Hz**

### AUTORE

Francesco Santambrogio  
Meccanica Applicata alle Macchine – Politecnico di Milano, 2021

---

## 🇬🇧 ENGLISH

### PROJECT DESCRIPTION

This project, developed as part of the "Applied Mechanics" course at Politecnico di Milano, analyzes and models an artificial elbow system for amputees powered by a brushless DC motor. The system replicates elbow flexion-extension through a mechanism consisting of a ball-screw transmission and oscillating glyph, minimizing friction, noise, and joint weight. The project includes detailed analyses of kinematics, dynamics, motor actuation, and vibration response.

### PROJECT CONTENTS

### PROJECT CONTENTS

- **Kinematic scheme**, including three main components: the glyph (mechanism with rod and slider), the articulated quadrilateral (rockers and connecting rod), and the forearm (rigid body with center of mass and concentrated mass).
<p align="center">
  <img src="img/schema_cinematico.jpg" alt="Kinematic scheme" width="600"/>
</p>

- **Kinematic analysis**, including linear and angular velocities and accelerations calculations of critical points using MATLAB.
<p align="center">
  <img src="img/schema_cinematico_velocità_accelerazione.jpg" alt="Kinematic analysis" width="600"/>
</p>

- **Motion law**, describing and simulating the prosthesis movement over time.
<p align="center">
  <img src="img/legge_moto.jpg" alt="Motion law" width="600"/>
</p>

- **Dynamic analysis**, determining required driving torque and equilibrium forces through dynamic equilibrium equations.
<p align="center">
  <img src="img/forze.jpg" alt="Dynamic analysis" width="600"/>
</p>

- **Motor actuation analysis**, calculating ideal torque, absorbed power, and maximum lifting capacity.
<p align="center">
  <img src="img/azionamento_motore.jpg" alt="Motor actuation analysis" width="600"/>
</p>

- **Vibration study**, defining and simulating the dynamic system response to external harmonic forces.

<p align="center">
  <img src="img/funzione_trasferimento.jpg" alt="Transfer function" width="600"/><br/>
  <img src="img/coeff_trasmissibilità.jpg" alt="Transmissibility coefficient" width="600"/><br/>
  <img src="img/risposta_smorzata.jpg" alt="Damped response" width="600"/><br/>
  <img src="img/risposta_c1.jpg" alt="Response to C1" width="600"/><br/>
  <img src="img/risposta_c2.jpg" alt="Response to C2" width="600"/><br/>
  <img src="img/risposta_totale.jpg" alt="Total response" width="600"/>
</p>



### MAIN FILES

- `main.m`: Complete MATLAB script implementing all described analyses.
- `Report-ITA.pdf`: Technical report including full procedure, images, and results of the study implementing all the described analyses.

### TOOLS

- MATLAB for numerical simulations and analyses.

### KEY RESULTS

- Ideal driving torque: **0.25652 N·m**
- Mass that can be lifted by the patient: **15.7167 kg**
- Natural frequency of the system: **0.079615 Hz**
- Ideal frequency range for electrostimulation: **≥ 0.16 Hz**

### AUTHOR

Francesco Santambrogio  
Applied Mechanics – Politecnico di Milano, 2021
