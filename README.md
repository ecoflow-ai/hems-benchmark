# 🏠⚡ Smart HEMS Benchmarking Platform
## Accelerating Transparency in Home & Community Energy Management

<div align="center">

![EcoFlow](resources/images/ef_logo.png)
![TUM](resources/images/tum_logo.png)
![Stanford](resources/images/stanford_doerr_logo.png)

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8+-brightgreen.svg)](https://python.org)
[![GPU](https://img.shields.io/badge/GPU-Enabled-green.svg)](https://developer.nvidia.com/cuda-zone)
[![Nature Energy](https://img.shields.io/badge/Published-Nature%20Energy-red.svg)](https://nature.com/articles)
[![Open Source](https://img.shields.io/badge/Open%20Source-Dec%202025-yellow.svg)](#roadmap)

</div>

> **🎯 Mission**: Creating the world's first comprehensive, open-source benchmarking platform for Home Energy Management Systems (HEMS), enabling transparent comparison and optimization of distributed energy resources across global markets.

---

## 🌍 Market Context & Opportunity

The distributed energy resources market is experiencing unprecedented growth, creating urgent need for standardized evaluation frameworks.

### 📈 Explosive Market Growth

<div align="center">


</div>

**Key Market Drivers:**
- **Solar PV**: Projected to be the largest renewable source by 2030 (~80% of capacity growth) [IEA]
![PV Market Growth](resources/images/pv_growth_iea.png)
- **Residential BESS**: Growing from 3 GWh (2020) to 122 GWh (2030) in Europe alone [McKinsey & Company]
![European BESS Growth](resources/images/bess_growth_mckinsey.png)
- **Investment Surge**: Falling costs + rising electricity prices + government incentives

### 🔄 The Three Challenge

Current HEMS evaluation suffers from fragmentation across three distinct domains:

<div align="center">

![Three World Problem](resources/images/three_phase_problem.png)

</div>



---

## 🏗️ Framework Architecture

### 🔄 Complete Lifecycle Optimization

Our platform addresses the entire DER lifecycle through three integrated optimization phases:


| Phase | Time Horizon | Key Decisions | Optimization Focus |
|-------|--------------|---------------|-------------------|
| **📍 Location & Sizing** | 1-15 years | Installation location, capacity | Cost reduction, backup power |
| **🏠 HEMS Evaluation** | 1 day | Charging/discharging behavior | Self-consumption, comfort |
| **⚡ Grid Support** | 1 year | VPP capacity allocation | Additional revenue streams |

### 🤖 Systematic Modeling Framework

<div align="center">

![AI Framework](resources/images/modeling_framework.png)

</div>

**Advanced Capabilities:**
- **🎯 Uncertainty Quantification**: PV generation, load forecasting, price volatility
- **🧠 AI Integration**: Machine learning-based optimization algorithms
- **📊 Multi-Objective**: Cost, reliability, comfort, environmental impact
- **⚡ Real-Time Control**: Adaptive strategies for dynamic conditions

---

## 🌎 Preliminary Results

### 🇺🇸 United States

Comprehensive evaluation across all US counties with complete utility mapping and policy scenario analysis.


**Non-Export Setting**

<div align="center">

![US NonExport](resources/images/us_non_export_setting_all.png)

</div>

**NEM Setting**
<div align="center">

![NEM Results](resources/images/us_nem_setting_all.png)

</div>


### 🇩🇪 Germany

<div align="center">

![Germany Analysis](resources/images/germany_all_update.png)

</div>


---

## 🎯 HEMS Performance Evaluation

### 🇺🇸 Time-of-Use (US Case)

**Configuration**: 10kWp PV + 10kWh ESS + TOU

<div align="center">

![US HEMS Results](resources/images/hems_tou_us.png)

</div>


### 🇬🇧 Dynamic Tariff (UK Case)

**Configuration**: 10kWp PV + 20kWh ESS + Octopus Dynamic Tariff
<div align="center">

![UK HEMS Results](resources/images/hems_dynamic_uk.png)

</div>

### 🇩🇪 Dynamic Tariff (Germany Case)

**Configuration**: 10kWp PV + 10kWh ESS + Dynamic Tariff

<div align="center">

![Germany HEMS Results](resources/images/hems_dynamic_germany.png)

</div>


---

## 🔧 Platform Integration & API 

<div align="center">

![Platform Integration](resources/images/platform_architecture.jpg)

</div>

Our platform provides seamless integration through five key stages:

1. **📋 Benchmark Topology**: System configuration definition
2. **⚙️ Benchmark Configuration**: Parameter optimization setup  
3. **📊 Predicted Data**: Day-ahead forecasting integration
4. **🧠 HEMS Algorithms**: Multi-algorithm testing framework
5. **📈 Ranking & Analysis**: Performance evaluation and comparison

### 🌐 Topology

<div align="center">

![Platform Integration](resources/images/platform_topology.png)

</div>

### 🌐 Configuration

<div align="center">

![Platform Integration](resources/images/platform_configuration_update.png)

</div>

### 🔄 HMES Algorithms Comparison

<div align="center">

![HEMS Comparison](resources/images/platfrom_hems_alg_framework.png)

</div>

**Supported Algorithms:**
- **Baseline**: Grid-only, Grid+PV, Self-consumption
- **Advanced**: AI-TOU, Battery health-aware, MPC, Robust-X

**Sensitivity Analysis:**
<div align="center">

![HEMS Sensitivity](resources/images/platfrom_sensitivity.png)

</div>

- PV capacity optimization
- ESS capacity optimization  
- Load consumption scaling
- Grid export limit configuration

### 📊 HEMS Ranking (illustration)

<div align="center">

![HEMS Result Table](resources/images/platform_result_table.png)

</div>

<div align="center">

![HEMS Result Sensitivity](resources/images/platfrom_result_sensitivity.png)

</div>

---

## 🔬 PhyLFlex HEMS Benchmarking Suite
 
<div align="center">

![PhyLFlex Overview](resources/images/phylflex_logo.png)

</div>

### 🌟 Three-Tier Validation Strategy


| Benchmark Type | Question | Focus | Validation Method |
|----------------|----------|-------|------------------|
| **🔬 Research** | What *could* be possible? | Algorithms & forecasts | Laboratory emulation |
| **⚖️ Regulatory** | What *should* be possible? | Compliance & grid stability | iMSys integration |
| **🌍 Real-World** | What *is* currently possible? | Interoperability & claims | Field demonstrations |

**The research benchmark**

<div align="center">

![COSES Could](resources/images/coses_could.png)

</div>

**The iMySys benchmark**
<div align="center">

![COSES Should](resources/images/coses_should.png)

</div>

**The real-world benchmark**
<div align="center">

![COSES Should](resources/images/coses_currently.png)

</div>


## 🗺️ Roadmap & Collaboration

<div align="center">

![Roadmap](resources/images/opensource_roadmap.png)

</div>

---

## 📄 License & Legal

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.


---

<div align="center">

## 🚀 Ready to Transform Energy Management?

**Join the global movement toward transparent, standardized Smart HEMS benchmarking!**

[![Get Started](https://img.shields.io/badge/Get%20Started-Now-brightgreen.svg?style=for-the-badge)](#quick-start-guide)
[![View Demo](https://img.shields.io/badge/View%20Demo-Live-blue.svg?style=for-the-badge)](https://demo.hemsbenchmark.org)
[![Join Community](https://img.shields.io/badge/Join%20Community-Discord-purple.svg?style=for-the-badge)](https://discord.gg/hemsbenchmark)

**🌐 Explore, Contribute, and Innovate with Smart HEMS Benchmarking!** <br>
Email: ricky.li@ecoflow.com; xiaoke.yang@ecoflow.com; jawen.zhang@ecoflow.com; xianyuan.wang@ecoflow.com

</div>
---

*Last updated: September 2025*
