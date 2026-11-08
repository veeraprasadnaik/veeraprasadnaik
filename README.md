<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=230&section=header&text=Veera%20Prasad%20Naik%20K&fontSize=48&fontColor=22d3ee&fontAlignY=36&desc=Building%20Secure%20Hardware%20for%20Quantum%20Communication&descSize=20&descColor=ffffff&descAlignY=58&animation=fadeIn" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=22D3EE&center=true&vCenter=true&width=800&lines=Welcome+to+my+Digital+Space+%F0%9F%91%8B;QKD+%7C+PQC+%7C+LDPC;ASIC%2FVLSI+%7C+FPGA+RTL+Design+%26+Verification;RISC-V+SoC+%7C+AMBA+%7C+CDC+%7C+Synthesis;Cadence+Genus+%26+Innovus" alt="Typing SVG" />
</a>

<br/>

**QKD, PQC & LDPC | ASIC/VLSI | FPGA RTL Design & Verification | RISC-V SoC | SystemVerilog | AMBA | CDC | Synthesis | Genus & Innovus**

<br/>

<a href="https://www.linkedin.com/in/k-veera-prasad-naik2342353463576"><img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:YOUR_EMAIL@gmail.com"><img src="https://img.shields.io/badge/EMAIL-REACH%20OUT-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/veeraprasadnaik"><img src="https://img.shields.io/badge/GITHUB-FOLLOW-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=veeraprasadnaik&label=PROFILE%20VIEWS&color=9333ea&style=for-the-badge" />
<img src="https://img.shields.io/github/followers/veeraprasadnaik?label=FOLLOWERS&style=for-the-badge&color=0e75b6" />

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c5364&height=3" width="100%" />

## 👨‍💻 About Me

Electronics and Communication Engineering student specializing at the boundary of **VLSI Design, RTL Architecture, and Post-Quantum / QKD Hardware Security**. I focus on high-throughput digital logic, ultra-low-latency control platforms, and hardware-accelerated cryptographic primitives for next-generation quantum networks.

📍 Tirupati, India

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c5364&height=3" width="100%" />

## 🔐 Quantum Key Distribution (QKD) Hardware

- **Post-Processing Acceleration:** RTL architecture for sifting, QBER estimation, high-throughput LDPC error correction, and Toeplitz matrix-based privacy amplification
- **Protocols:** BB84, E91, and decoy-state multi-intensity protocols
- **Network Subsystems:** multi-channel time-tagging logic for single-photon counting modules (SPCMs), low-jitter clock alignment, and CDC synchronization across optical links

```mermaid
flowchart LR
    A["SPCM Photon Detection"] --> B["Time-Tagging & Clock Alignment"]
    B --> C["Sifting"]
    C --> D["QBER Estimation"]
    D --> E["LDPC Error Correction"]
    E --> F["Privacy Amplification (Toeplitz)"]
    F --> G["Secret Key"]
    style A fill:#0f2027,stroke:#22d3ee,color:#ffffff
    style B fill:#0f2027,stroke:#22d3ee,color:#ffffff
    style C fill:#0f2027,stroke:#22d3ee,color:#ffffff
    style D fill:#0f2027,stroke:#22d3ee,color:#ffffff
    style E fill:#0f2027,stroke:#8b5cf6,color:#ffffff
    style F fill:#0f2027,stroke:#8b5cf6,color:#ffffff
    style G fill:#0e75b6,stroke:#22d3ee,color:#ffffff
```

<div align="center">
  <img src="./Gemini_Generated_Image_ixeivixeivixeivi.png" width="90%" />
  <br/>
  <sub>Conceptual QKD system setup (AI-generated illustration): Alice Tx, Bob Rx, FPGA key generation and SNSPD detection</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c5364&height=3" width="100%" />

## 🛡️ Post-Quantum Cryptography (PQC) & Hardware Security

- **Lattice-Based Accelerators:** ML-KEM (Kyber) and ML-DSA (Dilithium) with NTT multiplier pipelines and Barrett/Montgomery reduction
- **Secure SoC Design:** RISC-V core integration with memory-mapped crypto-coprocessors over AMBA AXI4/AHB/APB, with side-channel countermeasures

```mermaid
flowchart LR
    CPU["RISC-V Core"] <-->|"AXI4 / AHB / APB"| BUS["AMBA Interconnect"]
    BUS <--> KEM["ML-KEM (Kyber)"]
    BUS <--> DSA["ML-DSA (Dilithium)"]
    KEM --> NTT["NTT Multiplier Pipeline + Barrett/Montgomery"]
    DSA --> NTT
    style CPU fill:#0f2027,stroke:#22d3ee,color:#ffffff
    style BUS fill:#0f2027,stroke:#8b5cf6,color:#ffffff
    style KEM fill:#0f2027,stroke:#22d3ee,color:#ffffff
    style DSA fill:#0f2027,stroke:#22d3ee,color:#ffffff
    style NTT fill:#0e75b6,stroke:#22d3ee,color:#ffffff
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c5364&height=3" width="100%" />

## ⚙️ ASIC & FPGA Implementation Flow

- **Front-End:** SystemVerilog/Verilog microarchitectures, parameterizable FSMs, and testbenches in ModelSim and Vivado Simulator
- **Physical Design:** RTL-to-GDSII using Cadence Genus (synthesis) and Cadence Innovus (floorplanning, place-and-route, STA, timing closure)

```mermaid
flowchart LR
    R["RTL Design"] --> S["Simulation & Verification"]
    S --> G["Synthesis (Genus)"]
    G --> F["Floorplan (Innovus)"]
    F --> P["Place & Route"]
    P --> T["STA & Timing Closure"]
    T --> D["GDSII"]
    style R fill:#0f2027,stroke:#22d3ee,color:#ffffff
    style S fill:#0f2027,stroke:#22d3ee,color:#ffffff
    style G fill:#0f2027,stroke:#8b5cf6,color:#ffffff
    style F fill:#0f2027,stroke:#8b5cf6,color:#ffffff
    style P fill:#0f2027,stroke:#8b5cf6,color:#ffffff
    style T fill:#0f2027,stroke:#8b5cf6,color:#ffffff
    style D fill:#0e75b6,stroke:#22d3ee,color:#ffffff
```

### 🧱 Physical Design: Cadence Innovus

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="./innovus_1.png" width="100%" />
      <br/>
      <sub>Floorplan with memory macro placement</sub>
    </td>
    <td align="center" width="50%">
      <img src="./innovus_2.png" width="100%" />
      <br/>
      <sub>Floorplan with net connectivity (flight lines) view</sub>
    </td>
  </tr>
</table>

### 🧪 RTL Simulation: RAM/ROM Memory System (Vivado)

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="./RAM_ROM_Simulation_.png" width="100%" />
      <br/>
      <sub>Simulation waveform: clk, we, sel, addr, din, dout</sub>
    </td>
    <td align="center" width="50%">
      <img src="./RAM_ROM_TIMING_ANALYSIS_.png" width="100%" />
      <br/>
      <sub>Timing waveform: write, then read-back across memory select</sub>
    </td>
  </tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c5364&height=3" width="100%" />

## 🛠️ Technical Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,python,git,github,linux,vscode&theme=dark" />

</div>

**HDL & Verification**

![Verilog](https://img.shields.io/badge/Verilog_HDL-1F6FEB?style=for-the-badge)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-8250DF?style=for-the-badge)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-0E75B6?style=for-the-badge)

**EDA Tools**

![Vivado](https://img.shields.io/badge/Xilinx_Vivado-E34F26?style=for-the-badge&logo=xilinx&logoColor=white)
![Genus](https://img.shields.io/badge/Cadence_Genus-D29922?style=for-the-badge)
![Innovus](https://img.shields.io/badge/Cadence_Innovus-D29922?style=for-the-badge)
![Design Compiler](https://img.shields.io/badge/Synopsys_Design_Compiler-6E40C9?style=for-the-badge)

**Quantum Simulation**

![NetSquid](https://img.shields.io/badge/NetSquid-0891B2?style=for-the-badge)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=for-the-badge&logo=qiskit&logoColor=white)
![QuNetSim](https://img.shields.io/badge/QuNetSim-0E75B6?style=for-the-badge)

**Circuit & PCB**

![SPICE](https://img.shields.io/badge/SPICE-238636?style=for-the-badge)
![Altium](https://img.shields.io/badge/Altium_Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white)

**Protocols**

![AXI4](https://img.shields.io/badge/AMBA_AXI4-E34F26?style=for-the-badge)
![AHB](https://img.shields.io/badge/AMBA_AHB-D29922?style=for-the-badge)
![APB](https://img.shields.io/badge/AMBA_APB-238636?style=for-the-badge)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c5364&height=3" width="100%" />

## 🚀 Featured Projects

| Project | Description | Tech |
|---|---|---|
| RAM/ROM Memory System | Memory system with write/read and select logic, verified with a testbench in Vivado | Verilog |
| Physical Design (Innovus) | Floorplan and placement with memory macros | Cadence Innovus |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c5364&height=3" width="100%" />

## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=veeraprasadnaik&show_icons=true&theme=tokyonight&hide_border=true" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=veeraprasadnaik&layout=compact&theme=tokyonight&hide_border=true" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=veeraprasadnaik&theme=tokyonight&hide_border=true" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=veeraprasadnaik&theme=onedark&no-frame=true&row=1&column=6" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=veeraprasadnaik&theme=tokyo-night&hide_border=true" width="100%" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=100&section=footer" width="100%" />

</div>
