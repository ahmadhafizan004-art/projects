# Ahmad Hafizan's Project Portfolio

Welcome to my professional portfolio repository! This space showcases my final year projects (FYP), group projects, and other significant work completed during my academic journey at Universiti Teknologi MARA (UiTM).

## 📋 Quick Navigation

- [About Me](#about-me)
- [Main Projects](#main-projects)
- [Technologies & Skills](#technologies--skills)
- [Project Highlights](#project-highlights)
- [Get In Touch](#get-in-touch)

---

## 👤 About Me

I'm Ahmad Hafizan, a Computer Science student at **Universiti Teknologi MARA (UiTM)** passionate about:
- 🔧 **IoT & Embedded Systems** - Hardware integration, sensor technology, real-time systems
- 🤖 **Machine Learning & Data Science** - Predictive modeling, data analysis, classification
- 📊 **Data Analytics & Visualization** - Business intelligence, dashboards, insights
- 🏭 **Industry 4.0** - Predictive maintenance, smart manufacturing, digital transformation
- 💻 **Software Development** - Full-stack applications, system design, automation

**Currently seeking**: Internship opportunities in IoT, Data Science, or Software Development

---

## 🎯 Main Projects

### 1. **VibeSense: IoT-Based Predictive Maintenance System** 🏆
**Type:** Final Year Project (FYP) - Bachelor of Computer Science  
**Duration:** 2023-2027 | **Status:** ✅ In Progress

#### Project Overview
An IoT-based predictive maintenance prototype for electric motors in SMEs using Logistic Regression. The system monitors machine health in real-time using vibration and temperature sensors connected to an ESP32 microcontroller.

#### 🎯 Objectives
1. Design a cost-effective IoT-based predictive maintenance prototype for SME machinery
2. Develop ML model using vibration and temperature data with Logistic Regression
3. Test system functionality through simulated fault conditions

#### 🛠️ Technology Stack

| Category | Technologies |
|----------|---------------|
| **Hardware** | ESP32, ADXL335 (Vibration Sensor), DS18B20 (Temperature Sensor) |
| **Firmware** | Arduino IDE, C/C++ |
| **Backend** | Python, scikit-learn, joblib |
| **Frontend** | Dash, Plotly, HTML/CSS |
| **Data Processing** | Pandas, NumPy |
| **IoT Platform** | ThingSpeak |
| **ML Algorithm** | Logistic Regression |

#### ✨ Key Features
- 🔴 **Real-time Monitoring** - Continuous vibration & temperature tracking
- 🤖 **ML-Based Fault Detection** - Normal vs Faulty classification
- 💰 **Cost-Effective** - ~RM150-300 total hardware cost
- 📊 **Live Dashboard** - Real-time IoT data visualization
- 📈 **RMS Analysis** - Vibration severity assessment
- ✅ **SME-Oriented** - Proof-of-concept for accessibility

#### 📂 Repository Structure
```
fyp-predictive-maintenance/
├── README.md
├── documentation/
│   ├── VibeSense_Chapter_1_to_3.md
│   ├── project_proposal.pdf
│   └── system_design.md
├── hardware/
│   ├── circuit_diagrams/
│   └── sensor_specifications/
├── firmware/
│   └── esp32_code/
│       ├── main.ino
│       ├── sensor_reader.ino
│       └── data_transmission.ino
├── software/
│   ├── app.py
│   ├── requirements.txt
│   ├── logistic_regression_model.pkl
│   └── baseline_config.json
├── data/
│   ├── VibeSense_raw.csv
│   ├── VibeSense_preprocessed.csv
│   └── VibeSense_cleaned.csv
└── results/
    ├── model_performance.png
    └── confusion_matrix.png
```

#### 📊 Expected Results
- Binary classification: Normal vs Faulty states
- Real-time vibration & temperature monitoring
- Fault probability scoring for maintenance decisions
- Web-based dashboard for IoT visualization

---

### 2. **Career Pathway Prediction System** 🎓
**Type:** Group Project - CSC649 (Big Data & Machine Learning)  
**Duration:** 2026 | **Status:** ✅ Completed

#### Project Overview
A machine learning-based career recommendation system that predicts whether graduates will continue studies, seek employment, or pursue entrepreneurship based on survey data.

#### 🎯 Key Achievements
- 📋 Survey dataset: 500+ respondents from Malaysia
- 🤖 Multiple ML models evaluated: Random Forest (81% accuracy), Logistic Regression, SVM, KNN
- 📊 Comprehensive data analysis with 16+ visualizations
- 🎯 Accurate career pathway classification

#### 🛠️ Technologies
- **Languages**: Python
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn
- **Techniques**: Feature engineering, cross-validation, hyperparameter tuning
- **Tools**: Jupyter Notebook, Google Forms

#### 📈 Results
- **Best Model**: Random Forest (81% accuracy)
- **Features**: 19 relevant input variables (demographics, financial status, preferences)
- **Output**: 3 career pathways (Continue Studies, Employment, Start Own Business)

**Report**: `CAREER_PATHWAY_ML_PROJECT.md`

---

### 3. **Power BI Dashboard** 📊
**Type:** Business Intelligence Project  
**Status:** 🔄 In Portfolio

Interactive Power BI dashboard for business analytics and data-driven decision-making, demonstrating proficiency in data visualization and ETL processes.

**Features:**
- Interactive visualizations and KPI tracking
- Real-time data insights
- Custom reports and analytics

---

### 4. **Tableau Data Visualization Dashboard** 📈
**Type:** Advanced Analytics Project  
**Status:** 🔄 In Portfolio

Sophisticated Tableau dashboards showcasing data storytelling and advanced visualization techniques.

**Capabilities:**
- Multi-dimensional data analysis
- Geographic and demographic visualization
- Trend analysis and forecasting

---

## 🛠️ Technologies & Skills

### Hardware & IoT
- **Microcontrollers**: ESP32, Arduino
- **Sensors**: ADXL335 (Vibration), DS18B20 (Temperature), DHT22 (Humidity)
- **IoT Platforms**: ThingSpeak, MQTT
- **Communication**: Wi-Fi, Bluetooth

### Programming Languages
- **Primary**: Python, SQL
- **Embedded**: C/C++, Arduino IDE
- **Web**: HTML, CSS, JavaScript
- **Others**: Java

### Data Science & ML
- **Algorithms**: Logistic Regression, Random Forest, SVM, KNN, XGBoost
- **Techniques**: Feature engineering, preprocessing, cross-validation, hyperparameter tuning
- **Libraries**: scikit-learn, pandas, NumPy, matplotlib, seaborn, Plotly
- **Evaluation**: Accuracy, Precision, Recall, F1-Score, ROC-AUC

### Data Visualization & Analytics
- **Tools**: Power BI, Tableau, Plotly, Dash
- **Techniques**: Real-time dashboards, interactive charts, heatmaps, scatter plots
- **Types**: Line charts, bar charts, 3D visualizations, geographic maps

### Databases & Cloud
- **Databases**: MySQL, MongoDB, Firebase
- **Cloud Platforms**: ThingSpeak, local servers
- **Version Control**: Git, GitHub

---

## 📊 Project Highlights

### VibeSense Specifications
- **Cost**: ~RM150-300 (vs RM5000+ for commercial systems)
- **Sensors**: 2 types (vibration + temperature)
- **Connectivity**: WiFi-enabled real-time transmission
- **ML Model**: Lightweight Logistic Regression suitable for edge devices
- **Dashboard**: Web-based real-time visualization

### Career Prediction Results
- **Dataset Size**: 500+ responses
- **Accuracy Range**: 78-81% across models
- **Features**: 19 carefully engineered input variables
- **Classes**: 3-way classification (studies, employment, entrepreneurship)

---

## 📁 Repository Structure

```
ahmadhafizan004-art/projects/
│
├── README.md (this file)
├── CAREER_PATHWAY_ML_PROJECT.md
│
├── fyp-predictive-maintenance/
│   ├── README.md
│   ├── documentation/
│   ├── hardware/
│   ├── firmware/
│   ├── software/
│   ├── data/
│   └── results/
│
├── power-bi-dashboard/
│   └── [Dashboard files]
│
└── tableau-dashboard/
    └── [Visualization files]
```

---

## 🚀 Quick Start

### Explore VibeSense
1. Review `fyp-predictive-maintenance/README.md`
2. Check `documentation/` for technical details
3. View hardware setup in `hardware/`
4. Run Python scripts in `software/`

### View Career Prediction Study
1. Open `CAREER_PATHWAY_ML_PROJECT.md`
2. Explore model comparisons and results
3. Review data visualizations and insights

---

## 💡 Key Learnings

✅ **IoT & Embedded Systems**
- Real-time sensor integration and data acquisition
- Microcontroller programming and WiFi connectivity
- Low-cost hardware implementation strategies

✅ **Machine Learning**
- Algorithm selection based on constraints
- Model evaluation and optimization
- Feature engineering and preprocessing

✅ **Data Science**
- Survey design and data collection
- Exploratory data analysis and visualization
- Predictive modeling and classification

✅ **Project Management**
- Multi-phase project execution
- Team collaboration and coordination
- Documentation and reporting

---

## 📞 Contact & Connect

| Channel | Link |
|---------|------|
| **Email** | ahmadhafizan004@gmail.com |
| **GitHub** | [@ahmadhafizan004-art](https://github.com/ahmadhafizan004-art) |
| **LinkedIn** | [Ahmad Hafizan Ahmad Mohtar](https://www.linkedin.com/in/ahmad-hafizan-ahmad-mohtar-290329270) |
| **Matric** | 2023214052 |
| **University** | Universiti Teknologi MARA (UiTM) |

---

## 📜 Academic Details

- **Program**: Bachelor of Computer Science (Hons.)
- **Faculty**: Faculty of Computer and Mathematical Sciences
- **Supervisor**: Ms. Nor Fadilah Binti Tahar
- **FYP Title**: VibeSense: An IoT-Based Predictive Maintenance Prototype for Electric Motors in SMEs Using Logistic Regression

---

## 📄 License

These projects are available for educational and portfolio purposes. Feel free to explore the documentation and code.

---

## 🌟 Thank You!

Thank you for visiting my portfolio! I'm passionate about technology and continuous learning. If you have any questions, collaboration opportunities, or would like to discuss my projects, please feel free to reach out.

**Looking forward to connecting with you!** 🚀

---

**Last Updated**: June 8, 2026  
**Status**: ✅ Actively Maintained & Growing
