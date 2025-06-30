# 🚀 [PLC- Programable Logic Circuit]

<div align="center">
<div style="background-color: #000; padding: 20px; border-radius: 12px; display: inline-block;">
  <img src="./logo.jpg" alt="Ecocee Logo" width="120" height="120" />
</div>

  
  ### Internship Project at [Ecocee](https://ecocee.in)
  
  [![Website](https://img.shields.io/badge/Website-ecocee.in-blue?style=for-the-badge&logo=globe)](https://ecocee.in)
  [![Email](https://img.shields.io/badge/Contact-info%40ecocee.in-red?style=for-the-badge&logo=gmail)](mailto:info@ecocee.in)
  
</div>

---

## 📋 Project Overview

**Batch:** July 2025
**Team Number:** Team 01
**Internship Position:** Embedded Developer Intern
**Duration:** 12/06/2025 to 30/06/2025

### 👥 Team Members
| Name | Role | Email | LinkedIn |
|------|------|-------|----------|
| Amalkrishna O U | Team Lead/Developer   | amalkrishna34@gmail.com   | https://www.linkedin.com/in/amal-krishna-629168338?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app |
| Jaims Aldrin    | Developer/Researcher  | jaimsaldrin2211@gmail.com | |



### 🎯 Description
We invented PLC (Programable Logic Circuit) that used for industry for automation of equipment and machinaries that can use 12 Volt and 24 Volt of 32 individual machinaries .Here we use PWM for moter driving, All equipments are High power approx.20A to 50A power consuming devices.

In this project splite into 3 parts
1, Control Unit (ESP 32 Microcontroller,Switch selector)
2, PWM
3, High Power SMPS (20A -50A)( Optional by Custumization)

here control unit cascaded with 4 X 74HC595 ic for controling more equipment by less pin of microcontroller,
and a High power SMPS circuit either 12 Volt or 24 Volt for individual 32 SMPS by custumization
AND PWM for motor and light intencity controling

---

## 🔧 Technical Specifications



### **For Embedded Developer Intern Projects:**
- **Microcontroller/Platform:**  ESP32
- **Programming Languages:** C/C++
- **Communication Protocols:** I2C, SPI, UART, WiFi, Bluetooth,
- **Sensors/Components:** 74HC595
- **Development Environment:** Arduino IDE
---

## ⚙️ Project Working

### Architecture Overview
[Provide a high-level overview of how your project works. You can include diagrams, flowcharts, or system architecture images here.]

### Key Components
1. **Component 1:** Multi equipment contolling by cascading 74HC595 by n numberes, each IC can control 8 equiments
2. **Component 2:** Individual SMPS used for Working safely and high efficiency,
3. **Component 3:** Seperrate PWM circuit provided for esp proper working and easy management for maintanance
### Algorithm/Logic Flow
```
Step 1: Start
   ↓
Step 2: Check the database and select which equipment to to activate
   ↓
Step 3: Create an binary code for this value and write to 74HC595
   ↓
Step 4: Select individual equipment
```

---

## 🚀 Applications & Use Cases

### Primary Applications
- **Application 1:** Industrail Purposes
- **Application 2:** Multi tasking selector
- **Application 3:** Robotics parts

### Future Scope


## 📱 Demo & Results

### Screenshots/Images

### Performance Metrics
| Metric | Value |
|--------|-------|
| Accuracy/Efficiency | XX% |
| Processing Time | XX ms/s |
| Memory Usage | XX MB |
| [Other relevant metrics] | XX |

---

## 🛠️ Installation & Setup

### Prerequisites
```bash
# List required software, libraries, or hardware
- Python 3.x
- [Required libraries]
- [Hardware requirements if applicable]
```

### Installation Steps
```bash
# Clone the repository
git clone [your-repo-link]

# Navigate to project directory
cd [project-name]

# Install dependencies
pip install -r requirements.txt

# [Additional setup steps]
```

### Usage
```bash
# How to run the project
python main.py

# Or other execution commands
```

---

## 📊 Project Structure
```
project-name/
├── src/                    # Source code
├── data/                   # Dataset files
├── models/                 # Trained models
├── docs/                   # Documentation
├── tests/                  # Test files
├── requirements.txt        # Dependencies
└── README.md              # This file
```

---

## 🎓 Learning Outcomes

### Technical Skills Gained
- [Skill 1 - e.g., Machine Learning model development]
- [Skill 2 - e.g., Embedded programming]
- [Skill 3 - e.g., Data analysis and visualization]

### Tools & Technologies Mastered
- [Tool 1]
- [Tool 2]
- [Tool 3]

---

## 🤝 Acknowledgments

Special thanks to the **Ecocee team** for providing guidance and support throughout this internship project.

**Mentor:** [Mentor Name]  
**Team Number:** [Team #XX]  
**Team Size:** [Number of team members]

### 👨‍💼 Team Contributions
| Team Member | Primary Contributions |
|-------------|----------------------|
| [Member 1 Name] | [e.g., Project architecture, ML model development] |
| [Member 2 Name] | [e.g., Data preprocessing, testing] |
| [Member 3 Name] | [e.g., UI/UX design, documentation] |
| [Member 4 Name] | [e.g., Hardware integration, debugging] |

---

## 📞 Contact

**Company:** Ecocee  
**Website:** [ecocee.in](https://ecocee.in)  
**Email:** [info@ecocee.in](mailto:info@ecocee.in)

### 👥 Team Contacts
| Team Member | Email | LinkedIn | GitHub |
|-------------|-------|----------|--------|
| [Member 1 Name] | [email@example.com] | [LinkedIn] | [GitHub Profile] |
| [Member 2 Name] | [email@example.com] | [LinkedIn] | [GitHub Profile] |
| [Member 3 Name] | [email@example.com] | [LinkedIn] | [GitHub Profile] |
| [Member 4 Name] | [email@example.com] | [LinkedIn] | [GitHub Profile] |

---

<div align="center">
  
  **Made with ❤️ during internship at Ecocee**
  
  ⭐ **Star this repo if you found it helpful!** ⭐
  
</div>

---

## 📄 License

This project is developed as part of an internship program at Ecocee. Please refer to the company's guidelines for usage and distribution.

[Optional: Add specific license if applicable]
