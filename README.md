# Prioritizing Tests for the COVID-19 Virus

![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-orange)
![Status](https://img.shields.io/badge/status-finished-brightgreen)

## Introduction

This repository presents a novel approach to COVID-19 testing that enhances laboratory efficiency and reduces virus transmission rates. By prioritizing individuals based on their risk profiles rather than random selection, this method enables targeted containment measures. 

A simulation compares the effectiveness of this risk-based approach across two populations, both identical at time t_0, with a fixed daily test limit. Untested individuals remain contagious per infection distribution parameters, while identified cases are isolated to prevent further spread. Our goal is to demonstrate the benefits of this approach in curtailing COVID-19 transmission.

---

# Matrisk-Pooling Algorithm - Efficient Pooling for COVID-19 Tests 🚀🧪

The **Matrisk-Pooling Algorithm** is a high-efficiency testing solution that organizes samples by risk to minimize tests while accurately identifying infected individuals. This adaptable algorithm remains effective even in high-prevalence scenarios, making it suitable for COVID-19 and other infectious diseases.

## ✨ Key Advantages
- **Rapid Identification**: Enables swift detection within pools, accelerating containment.
- **Resource Efficiency**: Optimizes testing resources, reducing costs and laboratory workload.
- **Adaptability**: Effective across infection rates, maintaining accuracy in diverse conditions.

---

## 📋 Table of Contents

- [Method Overview](#method-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Data and Results](#data-and-results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🧠 Method Overview

The Matrisk-Pooling Algorithm operates through a three-step process to efficiently identify COVID-19 positive cases while conserving testing resources.

### Step 1: Risk Assessment
Individuals are ranked by their infection probability based on predefined risk factors. This stage ensures the pooling process targets high-risk samples.

![Risk Assessment](https://your-image-url.com/risk_assessment.png)

### Step 2: Matrix Pooling
Samples are arranged in a matrix structure, allowing pooled testing of rows and columns. This matrix layout reduces the number of tests required while ensuring accuracy.

![Matrix Pooling](https://your-image-url.com/matrix_pooling.png)

### Step 3: Identifying Infected Patients
Based on the pooled test results, individuals likely to be infected are identified. This step allows for further testing if necessary, achieving both speed and precision.

![Identifying Patients](https://your-image-url.com/identifying_patients.png)

---

## 🔥 Features

- **Risk-based Pooling**: Utilizes individual risk scores to create a targeted matrix of samples.
- **Scalability**: Efficiently tests large populations, even with high infection rates.
- **Resource Optimization**: Reduces laboratory time and test materials.
- **Versatility**: Adaptable for testing various diseases beyond COVID-19.

---

## 🚀 Quick Start

### Installation

To set up the project locally, clone the repository and install required packages. Ensure you have Python and pip installed.

```bash
# Clone the repository
git clone https://github.com/Eliorsh/Covid19MatriskPooling.git
cd your-repo-name

# Install dependencies
pip install -r requirements.txt
