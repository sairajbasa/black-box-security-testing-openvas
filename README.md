# 🔐 Black Box Security Testing Using OpenVAS

## 📌 Project Overview

This project demonstrates **Black Box Security Testing and Vulnerability Assessment using OpenVAS**.

The objective was to assess a deliberately vulnerable target environment, identify security vulnerabilities, analyze their severity, and document the findings along with recommended remediation measures.

The project was performed as part of an academic cybersecurity project using **OpenVAS / Greenbone Vulnerability Management (GVM)** and a vulnerable **Metasploitable** environment.

---

## 🎯 Project Objectives

The main objectives of this project were:

* 🔍 Perform Black Box Security Testing
* 🛡️ Conduct vulnerability assessment using OpenVAS
* 🎯 Identify vulnerabilities in the target system
* 📊 Analyze and prioritize vulnerabilities based on severity
* 📄 Generate and analyze vulnerability scan reports
* 🔎 Understand potential attack surfaces
* 💡 Document security findings and remediation recommendations
* 🧪 Gain practical exposure to vulnerability assessment methodologies

---

## 🛠️ Tools & Technologies

| Category                 | Technology                 |
| ------------------------ | -------------------------- |
| 🔐 Vulnerability Scanner | OpenVAS / Greenbone        |
| 🐳 Deployment            | Docker                     |
| 🐧 Operating System      | Linux                      |
| 🧪 Target Environment    | Metasploitable             |
| 🔎 Testing Methodology   | Black Box Security Testing |
| 📊 Assessment            | Vulnerability Assessment   |
| 📄 Reporting             | OpenVAS Scan Reports       |

---

## 🔎 What is OpenVAS?

**OpenVAS (Open Vulnerability Assessment Scanner)** is a vulnerability scanning solution used to identify security vulnerabilities in systems and networks.

It supports different types of vulnerability assessments, including authenticated and unauthenticated testing, and uses regularly updated vulnerability feeds to perform security checks.

OpenVAS is part of the **Greenbone Vulnerability Management (GVM)** ecosystem.

For this project, OpenVAS was used to scan the target environment and identify vulnerabilities based on the available vulnerability tests.

---

## 🐳 OpenVAS Installation

For this project, OpenVAS was deployed using **Docker**.

Using a containerized deployment simplified the installation process by providing the required application environment and dependencies.

### General Deployment Flow

```text
💻 Linux System
      │
      ▼
🐳 Docker
      │
      ▼
🔐 OpenVAS / GVM
      │
      ▼
📡 Vulnerability Feed Updates
      │
      ▼
🎯 Target System
      │
      ▼
🔍 Vulnerability Scan
      │
      ▼
📊 Scan Results
```

After installation, the vulnerability feeds needed to be synchronized before performing the assessment.

The feed status was monitored through the OpenVAS / Greenbone administration interface.

Depending on system resources and feed size, the initial synchronization can take considerable time.

---

## 🖥️ OpenVAS Dashboard

After the OpenVAS environment was successfully deployed and the required feeds were updated, the web interface was used to configure and manage vulnerability scans.

The dashboard provided access to:

* 🎯 Target configuration
* 🔍 Scan configuration
* ▶️ Scan execution
* 📊 Vulnerability results
* 📄 Reports
* ⚙️ Administration and feed status

---

# 🧪 Testing Methodology

The project followed a structured Black Box Security Testing methodology.

```text
1️⃣ Identify Target
        ↓
2️⃣ Build Scan Profile
        ↓
3️⃣ Launch & Monitor Scan
        ↓
4️⃣ Analyze Results
        ↓
5️⃣ Document Findings
        ↓
6️⃣ Recommend Remediation
```

---

## 1️⃣ Identify the Target

The first step was to determine the system to be assessed and define the scope of testing.

For this academic project, a deliberately vulnerable **Metasploitable** environment was used as the target.

```text
👨‍💻 Tester
     │
     │ Black Box Assessment
     ▼
🎯 Metasploitable
     │
     ▼
🔍 OpenVAS Scanner
```

The use of a deliberately vulnerable environment allowed the security assessment to be performed safely for educational purposes.

---

## 2️⃣ Build the Scan Profile

A scan configuration was created based on the target environment.

The configuration included:

* 🎯 Target definition
* 🔍 Scan configuration
* 📝 Target description
* ⚙️ Scan parameters
* ⏰ Scheduling options

The appropriate scan configuration was selected based on the requirements of the assessment.

---

## 3️⃣ Launch & Monitor the Scan

After configuring the target and scan profile, the vulnerability assessment was launched.

The scan process was monitored through the OpenVAS dashboard.

```text
🎯 Target
   │
   ▼
⚙️ Scan Configuration
   │
   ▼
▶️ Start Scan
   │
   ▼
🔍 Vulnerability Tests
   │
   ▼
📊 Results
```

The scan required significant time to complete because OpenVAS performs a large number of vulnerability checks against the target.

---

## 4️⃣ Analyze the Results

After the scan completed, the generated results were analyzed.

The findings were categorized according to their severity, allowing the vulnerabilities to be prioritized.

Typical severity categories include:

```text
🔴 Critical
🟠 High
🟡 Medium
🔵 Low
⚪ Informational
```

The Metasploitable target intentionally contains numerous vulnerabilities, so the scan produced a significant number of findings.

---

# 📊 Results

The vulnerability assessment identified multiple security weaknesses in the target environment.

Because **Metasploitable is intentionally designed as a vulnerable system**, the scan identified numerous vulnerabilities, including high- and critical-severity findings.

The OpenVAS report provided information such as:

* 🔍 Vulnerability identification
* ⚠️ Severity level
* 🎯 Affected service or component
* 📝 Vulnerability description
* 🔎 Technical details
* 💡 Recommended remediation information

The scan results were further reviewed to understand the potential security impact of the identified vulnerabilities.

---

# 📄 Reporting

A key part of the project was analyzing the automated OpenVAS results and documenting the findings.

Rather than relying only on the automatically generated scanner report, the assessment documentation focused on:

* 🔎 Identifying important findings
* 📊 Understanding vulnerability severity
* 📝 Documenting affected components
* ⚠️ Explaining potential security impact
* 💡 Providing remediation recommendations

This helped demonstrate that vulnerability assessment involves not only running a scanner but also **understanding, prioritizing, and communicating the findings**.

---

# 🧠 Key Learnings

Through this project, I gained practical exposure to:

* 🔐 Vulnerability Assessment
* 🧪 Black Box Security Testing
* 🛠️ OpenVAS / GVM
* 🐳 Deploying security tools using Docker
* 🐧 Linux environments
* 📊 Vulnerability severity analysis
* 📄 Security assessment reporting
* 🎯 Understanding attack surfaces
* 💡 Security remediation concepts

---

# 📁 Project Structure

```text
black-box-security-testing-openvas/
│
├── 📄 README.md
│
├── 📁 documentation/
│   └── Project-Documentation.pdf
│
├── 📁 reports/
│   └── Sanitized-OpenVAS-Report.pdf
│
├── 📁 presentation/
│   └── Black-Box-Security-Testing-Presentation.pdf
│
└── 📁 demo/
    └── video-link.txt
```

---

# 🎥 Project Demonstration

A demonstration video of the project is available here:

👉 **[Watch Project Demonstration](YOUR_VIDEO_LINK_HERE)**

> Replace `YOUR_VIDEO_LINK_HERE` with the actual video URL.

---

# 📚 Project Documentation

Additional project materials are available in the repository:

* 📄 [Project Documentation](documentation/Project-Documentation.pdf)
* 📊 [OpenVAS Scan Report](reports/Sanitized-OpenVAS-Report.pdf)
* 🎞️ [Project Presentation](presentation/Black-Box-Security-Testing-Presentation.pdf)

> Only sanitized versions of the original academic documents should be published in this repository.

---

# ⚠️ Disclaimer

This project was conducted for **academic and educational purposes** using an intentionally vulnerable testing environment.

Security testing and vulnerability scanning should only be performed against systems for which you have explicit authorization.

No unauthorized systems were intentionally targeted as part of this project.

---

# 👨‍💻 Author

**Sairaj Basa**

🎓 B.Tech – Computer Science and Engineering (Cybersecurity)

🔗 GitHub: https://github.com/sairajbasa

---

## ⭐ Project Highlights

```text
🔐 Cybersecurity
      +
🔎 Vulnerability Assessment
      +
🧪 Black Box Testing
      +
🐳 Docker
      +
🐧 Linux
      +
📊 Security Reporting
```

This project demonstrates practical exposure to identifying, analyzing, and documenting security vulnerabilities using an industry-recognized vulnerability assessment platform.
