# 🔧 IoT-Based Predictive Maintenance System for Electric Motors

**Final Year Project (FYP)**  
**Institution:** [Your University Name]  
**Submission Date:** [Date]  
**Group Members:** Ahmad Hafizan Bin Ahmad Mohtar

---

## 📋 Quick Navigation

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Documentation](#documentation)
- [Results](#results)

---

## 📖 Project Overview

This project develops a **cost-effective IoT-based predictive maintenance prototype** for electric motors using machine learning and real-time sensor data analysis. The system targets small and medium-sized enterprises (SMEs) in Malaysia seeking affordable, scalable predictive maintenance solutions.

### Problem Statement
SMEs in Malaysia face barriers to adopting predictive maintenance due to:
- ❌ High cost of commercial solutions
- ❌ Limited technical expertise
- ❌ Lack of quality machine data
- ❌ Complex system integration requirements

### My Solution
A low-cost, accessible IoT system that enables **real-time equipment monitoring** and **early fault detection** using:
- 💰 Affordable components (ESP32, sensors)
- 🤖 Machine learning algorithms (Logistic Regression)
- 📊 Real-time IoT dashboards
- 🔧 Simple integration for SME machinery

---

## 🎯 Project Objectives

1. **Design a cost-effective IoT-based predictive maintenance prototype** for SME machinery
2. **Develop machine learning model** using vibration and temperature data with Logistic Regression
3. **Test system functionality** through simulated machine fault conditions
4. **Validate practical feasibility** for SME-scale applications

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🔴 **Real-time Monitoring** | Continuous vibration and temperature tracking |
| 🤖 **Predictive Analytics** | ML-based fault prediction (Normal vs. Faulty) |
| 💰 **Cost-Effective** | Uses affordable IoT components (~RM150-300) |
| 📊 **Live Dashboard** | Real-time visualization of motor health status |
| 📈 **RMS Analysis** | Root Mean Square vibration severity assessment |
| ✅ **Proof-of-Concept** | Demonstrates feasibility for SME adoption |

---

## 🛠️ Technology Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Microcontroller** | ESP32 | Data collection & IoT connectivity |
| **Vibration Sensor** | ADXL335 | Detects motor vibration levels |
| **Temperature Sensor** | DS18B20 | Monitors motor surface temperature |
| **Programming** | Arduino IDE, Python | Firmware and ML development |
| **ML Algorithm** | Logistic Regression | Binary classification (Normal/Faulty) |
| **Dashboard** | Python/Web Framework | Real-time data visualization |
| **Data Collection** | Self-collected | Controlled experimental setup |

---

## 📁 Project Structure

```
fyp-predictive-maintenance/
│
├── README.md (this file)
│
├── 📄 documentation/
│   ├── FYP_Report.md (Full technical report)
│   ├── project_proposal.pdf
│   ├── system_design.md
│   ├── data_collection_procedure.md
│   └── results_analysis.md
│
├── 🔌 hardware/
│   ├── circuit_diagrams/
│   │   ├── schematic.png
│   │   └── pcb_layout.pdf
│   ├── sensor_specifications/
│   │   ├── ADXL335_datasheet.pdf
│   │   └── DS18B20_datasheet.pdf
│   └── components_list.md
│
├── 💻 firmware/
│   ├── esp32_code/
│   │   ├── main.ino
│   │   ├── sensor_reader.ino
│   │   ├── wifi_connection.ino
│   │   └── data_transmission.ino
│   └── README.md (setup instructions)
│
├── 🤖 machine_learning/
│   ├── logistic_regression_model.py
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── model_evaluation.py
│   └── trained_model.pkl (serialized model)
│
├── 📊 data/
│   ├── raw_sensor_data/
│   │   ├── normal_operation_data.csv
│   │   ├── faulty_condition_1_imbalance.csv
│   │   └── faulty_condition_2_loose_mounting.csv
│   └── processed_datasets/
│       ├── training_data.csv
│       ├── testing_data.csv
│       └── validation_data.csv
│
├── 📈 dashboard/
│   ├── app.py (Streamlit application)
│   ├── requirements.txt
│   └── README.md (deployment guide)
│
├── 🧪 testing/
│   ├── unit_tests/
│   │   ├── test_sensor_reading.py
│   │   └── test_model_prediction.py
│   ├── integration_tests/
│   │   └── test_system_integration.py
│   └── results/
│       └── test_results.md
│
├── 📸 results/
│   ├── visualizations/
│   │   ├── model_performance_charts.png
│   │   ├── confusion_matrix.png
│   │   └── roc_curve.png
│   ├── experimental_results/
│   │   ├── baseline_results.txt
│   │   ├── optimized_results.txt
│   │   └── comparison_analysis.md
│   └── demo_videos/
│       └── system_demo.mp4 (coming soon)
│
├── 📚 references/
│   ├── papers.md (relevant research papers)
│   ├── tutorials.md (helpful resources)
│   └── references.bib (bibliography)
│
└── 🚀 deployment/
    ├── docker_config/ (containerization)
    ├── requirements.txt (dependencies)
    └── setup_guide.md (installation instructions)
```

---

## 🚀 Getting Started

### Prerequisites
- ESP32 development board
- ADXL335 accelerometer sensor
- DS18B20 temperature sensor
- Arduino IDE installed
- Python 3.8+
- Required Python packages (see requirements.txt)

### Quick Start

#### 1. Hardware Setup
See [`hardware/`](hardware/) for circuit diagrams and sensor specifications.

```
ESP32 Connections:
- VCC → 3.3V
- GND → GND
- ADXL335 → Analog pins (A0, A1, A2)
- DS18B20 → GPIO pin (e.g., GPIO4)
```

#### 2. Firmware Upload
```bash
cd firmware/esp32_code
# Open main.ino in Arduino IDE
# Select ESP32 board and COM port
# Upload code
```

#### 3. Data Collection
Follow the procedure in [`documentation/data_collection_procedure.md`](documentation/data_collection_procedure.md)

#### 4. Model Training
```bash
cd machine_learning
python model_training.py
```

#### 5. Run Dashboard
```bash
cd dashboard
pip install -r requirements.txt
streamlit run app.py
```

---

## 📊 Documentation

### Key Documents

| Document | Purpose | Status |
|----------|---------|--------|
| [FYP_Report.md](documentation/FYP_Report.md) | Complete technical report | ✅ Available |
| [System Design](documentation/system_design.md) | Architecture & design | ✅ Available |
| [Data Collection](documentation/data_collection_procedure.md) | Experimental procedure | ✅ Available |
| [Results Analysis](documentation/results_analysis.md) | Findings & discussion | ✅ Available |

### Detailed Sections
- **System Design:** Circuit design, component selection, integration approach
- **Data Collection:** Sensor calibration, experimental setup, fault condition creation
- **Model Development:** Preprocessing steps, training procedure, evaluation metrics
- **Results:** Performance metrics, visualizations, interpretation

---

## 📈 Key Results

### Model Performance
- **Accuracy:** 0.9864
- **Precision:** 0.9924
- **Recall:** 0.9701
- **F1-Score:** 0.9811

### System Capabilities
- ✅ Real-time vibration detection (±3g range)
- ✅ Temperature monitoring (0-100°C)
- ✅ Fault classification (Normal/Faulty)
- ✅ Data transmission via WiFi
- ✅ Dashboard visualization
- ✅ Alert system for faults

### Cost Analysis
| Component | Cost | Quantity | Total |
|-----------|------|----------|-------|
| ESP32 | RM 50 | 1 | RM 50 |
| ADXL335 | RM 30 | 1 | RM 30 |
| DS18B20 | RM 10 | 1 | RM 10 |
| PCB & Misc | RM 60 | 1 | RM 60 |
| **Total** | | | **RM 150** |

---

## 🧪 Testing & Validation

### Test Coverage
- ✅ Unit tests for sensor reading
- ✅ Integration tests for system components
- ✅ End-to-end system testing
- ✅ Model accuracy validation
- ✅ Real-world fault simulation

### Experimental Conditions
1. **Normal Operation:** Baseline data collection
2. **Fault Condition 1:** Motor imbalance simulation
3. **Fault Condition 2:** Loose mounting simulation
4. **Mixed Conditions:** Combined fault scenarios

---

## 📚 How to Use This Repository

### For Recruiters/Evaluators
1. Read [`documentation/FYP_Report.md`](documentation/FYP_Report.md) for complete project overview
2. Check [`results/`](results/) for visualizations and performance metrics
3. Review [`hardware/circuit_diagrams/`](hardware/circuit_diagrams/) for technical design

### For Developers/Replicators
1. Follow [`🚀 Getting Started`](#getting-started) section
2. Review hardware setup in [`hardware/`](hardware/)
3. Upload firmware from [`firmware/esp32_code/`](firmware/esp32_code/)
4. Train model using [`machine_learning/model_training.py`](machine_learning/model_training.py)
5. Deploy dashboard with [`dashboard/app.py`](dashboard/app.py)

### For Researchers
1. Check [`references/papers.md`](references/papers.md) for related work
2. Review [`machine_learning/`](machine_learning/) for ML methodology
3. Access raw data in [`data/raw_sensor_data/`](data/raw_sensor_data/)
4. Read [`documentation/results_analysis.md`](documentation/results_analysis.md) for detailed discussion

---

## 🎓 Academic Significance

This project demonstrates:
- ✅ **Industry 4.0 Implementation** for SMEs
- ✅ **IoT & Sensor Integration** practical application
- ✅ **Machine Learning** in predictive maintenance
- ✅ **Data-Driven Decision Making** for industrial applications
- ✅ **Cost-Effective Solutions** for emerging markets

---

## 🤝 Team & Acknowledgments

**Project Team:**
- Ahmad Hafizan Bin Ahmad Mohtar (Hardware & Firmware)
- Team Members (ML & Dashboard Development)

**Supervision:**
- [Supervisor Name & Title]

**Thanks to:**
- [Company/Organization] for industrial insights
- [Contributors] for technical support

---

## 📝 License

This project is available for educational and research purposes.

---

## 📧 Contact & Support

For questions, suggestions, or collaboration opportunities:
- 📧 Email: ahmadhafizan004@gmail.com
- 🔗 GitHub: [@ahmadhafizan004-art](https://github.com/ahmadhafizan004-art)
- 💼 LinkedIn: [Ahmad Hafizan Ahmad Mohtar](https://www.linkedin.com/in/ahmad-hafizan-ahmad-mohtar-290329270)

---

## 📅 Project Timeline

| Phase | Duration | Status |
|-------|----------|--------|
| Planning & Design | Month 1-2 | ✅ Completed |
| Hardware Development | Month 3 | ✅ Completed |
| Firmware Development | Month 4 | ✅ Completed |
| Data Collection | Month 5 | ✅ Completed |
| ML Model Development | Month 6 | ✅ Completed |
| Testing & Validation | Month 7 | ✅ Completed |
| Documentation | Month 8 | ✅ Completed |
| Final Submission | Month 8 | ✅ Completed |

---

**Last Updated:** June 2026  
**Status:** 🎓 Completed & Submitted  
**Repository:** [ahmadhafizan004-art/projects/fyp-predictive-maintenance](https://github.com/ahmadhafizan004-art/projects/tree/main/fyp-predictive-maintenance)
