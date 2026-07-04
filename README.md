## 📌 Module 1 : Introduction to Cyber Defense blue team intro
### Room 1: Junior security Analyst Intro
* **Core Task:** Simulating a triage shift. Monitored a mock SIEM dashboard to identify unauthorized SSH connection attempts.
*  **Key Concepts:** Investigating alerts by identifying the malicious source IP address and escalating to Tier 2/senior Analyst.
*   **Artifact:** Capyured the flag THM{until-we-meet-again} after configuring a firewall rule to block the atacker.
*<img width="1051" height="731" alt="image" src="https://github.com/user-attachments/assets/1939d22a-cadc-48fd-9798-f42f7c66b130" />

### 2. SOC role in Blue Team
* **Core Tak:** Exploring the internal structure of a Security Operations Center.
*  **Key Concept:** Understanding the triage pipeline(LOGS➡ SIEM➡Alert➡Analyst Triage➡Remediation).
*   **Takeway:** communication and rapid documentation are just as vitalas technical analyst during a live breach.

  ### 3, Humans Vs. Atack Vectors
  * **Core Task:** Analysing real world phishing and social engineering methods.
  *  **Key Concept:**Atack vectors target human behaiviour (urgency,fear,curiosity) to bypass perimeter technical controls.
  *   **Defense strategy:** Email header analysis,scanning atchements hashes, and user awareness training.
<img width="826" height="552" alt="image" src="https://github.com/user-attachments/assets/7f45c3c6-8598-45bb-aee8-37447f796fff" />

### 4. System as Atack vectors 
* **Core Task:** Inspecting how vulnerabilities inside an operatin system are targeted.
*  **Key Cocenpt:** Weak system configurations, unpatched software, and exposed open ports give atackers a foothold.
*   **Defense strategy:** Patch management, endpoint detection, and implementig the principle of last privilege.
*   
    ---
## 📌 Module 2 Soc team internals

### 1. SOC L1 Alert triage 
* **Core task:** Learning how alerts are generated, how to read metadata, and to classify severity
* **key Concepts :** True positive vs. False poitive classification.Figuring out if an alert is actual malicious activity or a benign network activity.
*  **Metric Focused:** Reducing **MTTA (Mean time to acknowledge)** by spotting incoming alerts quickly.
*  <img width="1876" height="873" alt="image" src="https://github.com/user-attachments/assets/a2368f94-04e5-45ed-aae6-0a0bcbd17568" />

### 2. SOC L1 Alert Reporting
* **Core Task:** Documenting findings and writing professional incident escalation forms.
* **Key Concept:** The 5 W's (Who, What, When, Where, Why). An analyst must write reports clearly enough for both technicians and managers to understand.
* **Takeaway:** Proper documentation is critical because this data is what a Tier 2 analyst uses during active incident response.

### 3. SOC Workbooks and Lookups
* **Core Task:** Utilizing lookup tables and corporate playbooks to automatically enrich raw security alerts.
* **Key Concept:** Identity and Asset Inventory. You cannot judge if a login is suspicious without looking up *who* owns the account and *what* the machine's normal function is.

### 4. SOC Metrics and Objectives
* **Core Task:** Exploring how a SOC measures its daily operational effectiveness and health.
* **Key Numbers to Remember:**
  * **MTTD (Mean Time to Detect):** Average time from the start of an attack to the tool detection (Target: < 5 mins).
  * **MTTA (Mean Time to Acknowledge):** Time it takes an analyst to pick up the ticket (Target: < 10 mins).
  * **False Positive Rate:** Needs to stay balanced to avoid analyst "alert fatigue".
    
 ### 5. SOC Simulator: Introduction to Phishing
* **Core Task:** Running a practical simulation managing a security queue under pressure.
* **Key Action:** Triage realistic phishing emails, check email header routing, scan attachment hashes, and isolate targeted user endpoints.
  <img width="1024" height="880" alt="image" src="https://github.com/user-attachments/assets/74e3fcdf-6b58-440a-a0f5-4a106fff95e2" />

    


  
