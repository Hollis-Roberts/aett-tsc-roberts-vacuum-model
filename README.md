# Substrate Framework: Primary Foundations & Continuum Architecture

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21497378.svg)](https://doi.org/10.5281/zenodo.21497378)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.12](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![Release](https://img.shields.io/badge/Release-v11.0-brightgreen.svg)](https://github.com/hollis-roberts/aett-tsc-roberts-vacuum-model/releases/tag/v11.0)

An effective quantum hydrodynamic continuum field theory unifying subatomic rest mass generation, quantum topology, and cosmological expansion without relying on Higgs Yukawa couplings, non-local wave-function collapse, or spacetime curvature.

---

## 🌊 Executive Overview

The **Substrate Framework** formulates the physical vacuum as a pressurized, compressible elastic continuum field ($\rho_0 = 6.7 \times 10^{17}\text{ kg/m}^3$, $P_0 = 6.022 \times 10^{34}\text{ Pa}$). By establishing the **Dual-Frame Postulate**, physical reality is decoupled into two domains:

1. **3rd-Person Absolute Substrate Frame (The Timeless Sea, TSC):** A static 3D elastic background medium where worldlines exist as stationary topological vortex filaments carrying zero net intrinsic charge.
2. **1st-Person Observer Frame (The Timeline Hypersurface, $\Sigma$):** A 4D hypersurface membrane sweeping forward through the continuum field at metric wave speed $c = \sqrt{P_0 / \rho_0} \approx 2.9979 \times 10^8\text{ m/s}$. Physical observables emerge as dynamic intersection features as $\Sigma$ sweeps across stationary background worldlines.

---

## 🔬 Key Theoretical Results

* **Zero-Parameter Proton Mass Synthesis ($M_p = 938.27\text{ MeV}$):** Closed-form derivation from 3D bulk cavitation drag ($888.00\text{ MeV}$), bare constituent seeds ($8.99\text{ MeV}$), internal Phase D Coulomb self-energy ($1.56\text{ MeV}$), and the Master-Lock Identity ($M = 1.0442$).
* **Dual-Path Thermodynamic Convergence ($0.02\%$):** Agreement between microscopic acoustic impedance drag ($3 \times \mu_0 / \alpha = 887.99\text{ MeV}$) and macroscopic cavity enthalpy ($P_0 V_{\text{core}} / M - \Sigma\Omega_B = 887.82\text{ MeV}$).
* **Lepton Immunity Mechanism ($M_e = 0.511\text{ MeV}$):** Proof that Class 2 shallow surface crease electrons displace zero 3D bulk volume ($V_{\text{bulk}} = 0$), yielding $M_p / M_e = 1836.15$.
* **Neutron Beta-Decay Mass Splitting ($\Delta M = +1.293\text{ MeV}$):** Derivation of $+0.268\%$ core volume strain inducing a $-1.10\text{ MeV}$ drag relaxation in the $udd$ bound state ($M_n = 939.56\text{ MeV}$).
* **Double-Prism Hubble Tension Resolution:** Line-of-sight causal layer refraction stepping local expansion rates ($73.04\text{ km/s/Mpc}$) down across Tier 2 filaments ($69.95\text{ km/s/Mpc}$) and Tier 3 voids ($66.99\text{ km/s/Mpc}$).

---

## 📂 Repository Structure

```text
aett-tsc-roberts-vacuum-model/
├── v11.0/
│   ├── paper-1-substrate-mechanics.pdf         # Primary Foundations & Continuum Ontology
│   ├── sub-paper-a-hadronic-mass.pdf           # Hadronic Mass Synthesis & Lepton Immunity
│   ├── sub-paper-b-cosmology.pdf               # Cosmological Refraction & Hubble Tension
│   ├── sub-paper-c-quantum-topology.pdf        # Open Vector Flow-Tubes & L2 Space Protocols
│   └── substrate_verification.py               # Standalone First-Principles Verification Suite
├── v10.0/                                      # Previous Release Archive
├── archive/                                    # Historical Development Snapshots
├── CITATION.cff                                # Standardized Academic Citation Metadata
├── LICENSE                                     # MIT Open-Source License
└── README.md

## ⚙️ Automated Numerical Verification (`v11.0`)

Every equation and constant in the four-paper suite can be verified directly from Phase A baseline inputs using the standalone Python script (requires Python 3.8+, zero external dependencies):

```bash
python3 v11.0/substrate_verification.py

To auto-generate the Markdown parameter table:

python3 v11.0/substrate_verification.py --export-ledger

📊 Master Parameter Ledger (v11.0)Parameter / ConstantFirst-Principles FormulationComputed ValueSubstrate Mass Density ($\rho_0$)Baseline Continuum Density6.70e+17 kg/m³Relativistic Bulk Modulus ($P_0$)$P_0 = \rho_0 c^2$6.022e+34 PaMetric Wave Speed ($c$)$c = \sqrt{P_0 / \rho_0}$2.9979e+08 m/sMaster-Lock Identity ($M$)$(4/3)^{1/3}[1-f(\theta_C)][1+3g(n)]$1.04423D Bulk Cavitation Drag ($U_{\text{drag}}$)$`3(\mu_0/\alpha) \approx P_0 V_{\text{core}}/M - \Sigma\Omega_B`$888.00 MeVProton Rest Mass ($M_p$)$`(\Sigma\Omega_B + U_{\text{drag}} + E_C) \times M`$938.27 MeVNeutron Rest Mass ($M_n$)$`(\Sigma\Omega_B + U_{\text{relaxed}} + E_{\text{self}}) \times M`$939.56 MeV$n - p$ Mass Splitting ($\Delta M$)$M_n - M_p$+1.293 MeVElectron Rest Mass ($M_e$)$`\Omega_{\text{shallow}} \times M`$ ($L_c=1, V=0$)0.511 MeVProton-to-Electron Ratio ($M_p/M_e$)$`(\Sigma\Omega_B + U_{\text{drag}} + \Delta\Omega_b)/\Omega_{\text{shallow}}`$1836.15Tier 1 Expansion ($H_{\text{Local}}$)Phase D Local Host Rate (SH0ES)73.04 km/s/MpcTier 2 Expansion ($H_{\text{Tier 2}}$)$`H_{\text{Local}} / M`$ (TRGB / TDCOSMO)69.95 km/s/MpcTier 3 Expansion ($H_{\text{Tier 3}}$)$`H_{\text{Local}} / M^2`$ (Planck CMB)66.99 km/s/MpcQCD String Tension ($\sigma$)$`P_0 \cdot \pi R_{\text{core}}^2`$0.835 GeV/fm
