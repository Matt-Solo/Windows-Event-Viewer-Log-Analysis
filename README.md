# 🚨 Windows Event Investigation — Threat Detection & Analysis

## 🎯 Project Overview

This project demonstrates a structured **security investigation using Windows Event Logs** to identify suspicious activity, analyse authentication behaviour, and support incident response workflows.

The objective was to review critical Windows security events, detect potentially malicious patterns, and document findings in a way that reflects real-world **SOC analyst investigation processes**.

---

## 🧪 Environment

* Platform: Windows Event Viewer
* Log Sources:

  * Security Logs
  * System Logs
  * Application Logs
* Supporting Telemetry: Sysmon
* Focus Areas:

  * Authentication monitoring
  * Privileged activity
  * Account management events
  * Security event analysis

---

## 🔍 Investigation Process

### 1. Log Review

Reviewed key Windows log categories to identify activity relevant to security monitoring and incident response:

* Security
* System
* Application

---

### 2. Event Filtering

Filtered and analysed events associated with:

* Successful logons (**Event ID 4624**)
* Failed logons (**Event ID 4625**)
* Privileged logons (**Event ID 4672**)
* New account creation (**Event ID 4720**)
* Account enablement (**Event ID 4722**)
* Password-related activity (**Event ID 4723**)

---

### 3. Event Analysis

Examined event details including:

* Time of activity
* User account involved
* Logon type
* Privilege use
* Source host / IP context where available

This helped identify suspicious authentication behaviour and possible indicators of misuse or unauthorized access.

---

### 4. Threat Detection

Used event patterns to detect:

* Repeated failed authentication attempts
* Privileged access activity
* Unusual account lifecycle events
* Security-relevant changes requiring further investigation

---

### 5. Documentation

Captured screenshots, exported relevant logs, and documented key findings to support investigation notes and incident reporting.

---

## 📊 Key Findings

* Windows Event Logs provide critical visibility into authentication and account activity
* Failed logon and privileged access events are high-value indicators during investigations
* Structured filtering improves efficiency in identifying suspicious events
* Log review supports escalation decisions and evidence collection

---

## ⚠️ Security Relevance

This investigation highlights how Windows logs can help detect:

* Unauthorized access attempts
* Potential brute-force activity
* Suspicious account creation or enablement
* Misuse of elevated privileges

---

## 🛠️ Skills Demonstrated

* Windows log analysis
* Security event investigation
* Threat detection and triage
* Authentication monitoring
* Incident documentation
* Evidence collection for escalation

---

## 📸 Investigation Evidence ( https://github.com/Matt-Solo/Windows-Event-Viewer-Log-Analysis/tree/main ) 

This repository includes screenshots demonstrating:

* Log navigation and filtering
* Security-relevant event review
* Event detail analysis
* Investigation workflow documentation

---

## 🎯 Conclusion

This project demonstrates the ability to use **Windows Event Logs as an investigative data source** for threat detection and security monitoring, reflecting practical SOC analyst responsibilities in log review, analysis, and incident support.
