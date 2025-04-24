# Continuous Integration with GitHub Actions & SonarQube

This project was developed as part of the **Full Cycle 3.0** course, focused on implementing **Continuous Integration (CI)** using **GitHub Actions** and integrating **SonarQube** to ensure code quality through automated analysis.

## 🚀 What I Learned

- How to create and configure CI pipelines using **GitHub Actions**
- The structure and syntax of **YAML** files for automation
- How to set up **SonarQube** locally for code analysis
- How to integrate SonarQube with **GitHub** using the **cloud version**
- Best practices to improve **code quality**, **automation**, and **development workflows**

## 🔧 Tools & Technologies

- **GitHub Actions** for Continuous Integration
- **SonarQube** (Local and Cloud)
- **YAML** for CI workflow configuration
- **Docker** (optional – for local setup of SonarQube)
- **Go** – programmer language

## 📁 Project Structure

```bash
.github/
└── workflows/
    └── ci.yml          # CI pipeline configuration

sonarqube/
└── docker-compose.yml  # Local SonarQube setup (optional)

README.md