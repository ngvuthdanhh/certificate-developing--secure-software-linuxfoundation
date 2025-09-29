# Case Studies – Developing Secure Software

## Case Study 1: Equifax Data Breach (2017)
- **Root Cause:** Unpatched Apache Struts vulnerability (CVE-2017-5638).  
- **Impact:** ~147 million records exposed.  
- **Lessons Learned:**  
  - Patch management and vulnerability scanning are critical.  
  - Supply chain components must be monitored continuously.  

---

## Case Study 2: SolarWinds Supply Chain Attack (2020)
- **Root Cause:** Compromised CI/CD pipeline leading to malicious code injection.  
- **Impact:** Thousands of organizations, including US government agencies.  
- **Lessons Learned:**  
  - CI/CD security must include artifact signing.  
  - Runtime monitoring is essential for detecting anomalous behavior.  

---

## Case Study 3: Heartbleed (OpenSSL, 2014)
- **Root Cause:** Buffer over-read vulnerability in OpenSSL’s heartbeat extension.  
- **Impact:** Widespread key and memory leaks across the Internet.  
- **Lessons Learned:**  
  - Critical libraries must undergo thorough code audits.  
  - Fuzzing and static analysis can help detect low-level memory issues.  

---

## Case Study 4: Uber Data Breach (2016)
- **Root Cause:** Hardcoded AWS credentials in GitHub repository.  
- **Impact:** 57 million user records compromised.  
- **Lessons Learned:**  
  - Secrets must never be committed to version control.  
  - Automated secrets scanning is a must in CI/CD.
