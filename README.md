# Lab 5: Static Code Analysis

###  Author
**Ananya A C**  
PES University  

---

###  Objective
To analyze and improve Python code quality, security, and style using three static analysis tools:
- **Pylint** – for code quality and best practices  
- **Bandit** – for security analysis  
- **Flake8** – for PEP8 formatting compliance  

---

###  Tools Used
- Python 3.12.1  
- Pylint  
- Bandit  
- Flake8  
- GitHub Codespaces  

---

###  Commands Executed
```bash
pylint inventory_system.py > pylint_report.txt
bandit -r inventory_system.py > bandit_report.txt
flake8 inventory_system.py > flake8_report.txt
