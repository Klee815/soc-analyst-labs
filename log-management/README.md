# 🔍 Log Management Investigation (LetsDefend)

---

## 📌 Objective

Investigate suspicious activity using SIEM log management and identify compromised hosts.

---

## 🧪 Scenario

A suspicious file execution was detected:

* **File:** nmap
* **MD5 Hash:** `83e0cfc95de1153d405e839e53d408f5`

---

## 🔎 Investigation Process

1. Accessed Log Management (SIEM) in LetsDefend
2. Identified that initial logs were **network-based**
3. Switched to **endpoint/process logs**
4. Performed searches using:

   * `83e0` (partial hash)
   * `nmap` (keyword)
5. Located the relevant log entry
6. Verified file execution details

---

## 🖥️ Findings

* **Hostname:** (PUT YOUR ANSWER HERE)
* **File Name:** nmap
* **Hash:** `83e0cfc95de1153d405e839e53d408f5`

---

## ⚠️ Analysis

The execution of **nmap** suggests potential reconnaissance activity, which is often an early stage of a cyber attack.

---

## 🛡️ Recommendations

* Isolate the affected host
* Monitor network activity
* Perform a full endpoint scan
* Investigate possible lateral movement

---

## 📸 Evidence

<img width="968" height="473" alt="logmanagement1" src="https://github.com/user-attachments/assets/fc739709-91c4-4e46-96a1-5f85561b6dfd" />


---

## ✅ Conclusion

The investigation confirmed that a reconnaissance tool was executed on the host, indicating potential malicious activity.

---
