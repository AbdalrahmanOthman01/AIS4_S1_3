# 🚀 AIS4_S1_3 — DEPI Team Project

<div align="center">

### Data Analysis · Machine Learning · Visualization · Flask Web Development

A Python-based data-driven application that combines data analysis, visualization, machine learning, and web development through an interactive Flask interface.

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

<br>

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github&logoColor=white)](https://github.com/AbdalrahmanOthman01/AIS4_S1_3)
![Project](https://img.shields.io/badge/Project-DEPI--Team-6C63FF?style=flat)
![License](https://img.shields.io/badge/License-MIT-2EA44F?style=flat)

</div>

---

## 📑 Table of Contents

- [🚀 Project Overview](#-project-overview)
- [🧰 Features](#-features)
- [🛠️ Technologies](#️-technologies)
- [📁 Project Structure](#-project-structure)
- [👥 Team Members & Contributions](#-team-members--contributions)
- [📽️ Project Presentation & Demo](#️-project-presentation--demo)
- [📂 Directory Guide](#-directory-guide)
- [⚙️ Installation](#️-installation)
- [▶️ Usage](#️-usage)
- [📊 Data Analysis Workflow](#-data-analysis-workflow)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🚀 Project Overview

**AIS4_S1_3** is a collaborative project developed by a team participating in the **Digital Egypt Pioneers Initiative (DEPI)**.

The project demonstrates a data science workflow that integrates data exploration, preprocessing, visualization, model development, and web application deployment.

Using Python's data science ecosystem and the Flask framework, the application provides a web interface for interacting with the project's functionality and presenting data-driven results.

### 🎯 Project Objectives

- Explore and understand structured datasets.
- Prepare and preprocess data for further analysis.
- Build and evaluate machine learning models.
- Visualize data and communicate meaningful insights.
- Integrate project functionality into a Flask web application.

---

## 🧰 Features

<table>
<tr>
<td width="50%">

### 📊 Exploratory Data Analysis

Explore datasets using Jupyter Notebooks and investigate distributions, patterns, and relationships between features.

</td>
<td width="50%">

### 📈 Data Visualization

Create charts and visual representations to communicate patterns and analytical findings.

</td>
</tr>
<tr>
<td width="50%">

### 🧠 Model Development

Organize model-building, training, and testing workflows to evaluate predictive performance.

</td>
<td width="50%">

### 🌐 Flask Web Application

Provide a web interface that connects project functionality with user interaction.

</td>
</tr>
<tr>
<td colspan="2">

### 📁 Dataset Management

Include the project dataset in a compressed archive (`data.rar`) for local setup, subject to the availability of the required extraction tools.

</td>
</tr>
</table>

---

## 🛠️ Technologies

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical computing |
| Matplotlib | Data visualization |
| Flask | Web application development |
| Jupyter Notebook | Data exploration and experimentation |
| HTML, CSS, JavaScript | Frontend technologies, where applicable |
| Git & GitHub | Version control and collaboration |

---

## 📁 Project Structure

```text
AIS4_S1_3/
│
├── assets/
│   ├── DEPI Presentation.pdf
│   └── DEPI_Demo.mp4
│
├── Notebooks/
├── models/
├── static/
├── templates/
│
├── app.py
├── eda_utils.py
├── requirements.txt
├── data.rar
└── README.md
```

> **Note:** The directory structure above represents the intended project layout. Actual files and folders may vary depending on the latest repository contents.

---

## 👥 Team Members & Contributions

| Team Member | Responsibilities |
|---|---|
| **Mohamed Omar** | Data Overview & Preprocessing |
| **Habiba Maged** | Data Visualization |
| **Esraa Yaser** | Model Building, Training & Testing |
| **Abdalrahman Hossam** | Application Deployment |

### 🤝 Team Collaboration

The project was developed collaboratively, with each team member contributing to a different stage of the workflow, from data preparation and visualization to model development and application deployment.

---

## 📽️ Project Presentation & Demo

Explore the project presentation and watch the application demonstration.

- 📑 **[View the DEPI Presentation](assets/DEPI%20Presentation.pdf)** — Project overview, workflow, and presentation slides.
- 🎬 **[Watch the Project Demo](assets/DEPI_Demo.mp4)** — Video demonstration of the application.

> Ensure both files are uploaded to the `assets/` directory in the repository for these links to work.

---

## 📂 Directory Guide

| File / Directory | Description |
|---|---|
| `assets/` | Project presentation and demo video |
| `Notebooks/` | Data exploration, experimentation, and analysis |
| `models/` | Model files and related resources |
| `static/` | Static frontend assets, such as CSS, JavaScript, and images |
| `templates/` | HTML templates for the Flask application |
| `app.py` | Main Flask application entry point |
| `eda_utils.py` | Utility functions for exploratory data analysis |
| `requirements.txt` | Python package dependencies |
| `data.rar` | Compressed dataset archive |
| `README.md` | Project documentation |

---

## ⚙️ Installation

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/AbdalrahmanOthman01/AIS4_S1_3.git
cd AIS4_S1_3
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Environment

**Windows — PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

**Windows — Command Prompt:**

```bat
venv\Scripts\activate.bat
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### 5. Prepare the Dataset

If the application requires the dataset:

1. Locate `data.rar` in the project directory.
2. Extract the archive using a compatible extraction tool.
3. Place the extracted files in the directory expected by the application.

Make sure the dataset paths in the project code match the extracted file locations.

---

## ▶️ Usage

After installing the dependencies and preparing the required data, start the Flask application:

```bash
python app.py
```

Open your browser and navigate to:

**http://127.0.0.1:5000/**

If the application uses a different host or port, follow the configuration defined in `app.py`.

---

## 📊 Data Analysis Workflow

The project follows a workflow that connects data preparation, analysis, model development, and application delivery.

1. **Data Overview** — Inspect the dataset structure, columns, data types, and initial statistics.
2. **Data Preprocessing** — Handle missing values, prepare features, and perform the required transformations.
3. **Exploratory Data Analysis** — Investigate distributions, patterns, and relationships within the data.
4. **Data Visualization** — Present relevant findings through charts and plots.
5. **Model Building** — Develop and train the selected machine learning model.
6. **Model Evaluation** — Test the model and assess its performance using appropriate evaluation metrics.
7. **Application Deployment** — Integrate the project components into the Flask application.

---

## 🤝 Contributing

Contributions and improvements are welcome.

### Step 1 — Fork the Repository

Create a fork of the repository on GitHub.

### Step 2 — Create a Feature Branch

```bash
git checkout -b feature/your-feature
```

### Step 3 — Commit Your Changes

```bash
git add .
git commit -m "Describe your changes"
```

### Step 4 — Push Your Branch

```bash
git push origin feature/your-feature
```

### Step 5 — Open a Pull Request

Open a pull request describing your changes and their purpose.

---

## 📄 License

This project is distributed under the **MIT License**.

If the repository includes an MIT license file, refer to `LICENSE` for the complete terms.

For more information, visit the [MIT License page](https://opensource.org/licenses/MIT).

---

<div align="center">

### 💜 AIS4_S1_3 — DEPI Team Project

**Data Analysis · Machine Learning · Visualization · Web Development**

Built collaboratively with Python and Flask.

<br>

[![Explore Repository](https://img.shields.io/badge/Explore_the_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AbdalrahmanOthman01/AIS4_S1_3)

</div>
