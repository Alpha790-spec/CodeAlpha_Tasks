# Phishing Awareness Training

A comprehensive operational security guide and training documentation covering social engineering tactics, psychological manipulation triggers, technical detection red flags, and incident response protocols[cite: 1].

---

## 📌 Project Overview

Phishing accounts for over 90% of initial enterprise network compromises[cite: 1]. As technical defenses like Next-Gen Firewalls (NGFW) and Endpoint Detection & Response (EDR) solutions advance, attackers increasingly focus on human engineering[cite: 1]. 

This project provides a structured **Phishing Awareness Training Protocol** designed to equip organizational personnel with the skills needed to detect, neutralize, and safely report social engineering attempts[cite: 1].

* **Student ID:** `CA/DF1/260758`[cite: 1]
* **Training Duration:** 15–20 Minutes[cite: 1]
* **Target Audience:** All Staff & Personnel (Mandatory Core)[cite: 1]

---

## 🎯 Key Learning Objectives

* **Understand Social Engineering Vectors:** Identify common attack methods including Spear Phishing, Whaling, Smishing, Vishing, and Clone Phishing[cite: 1].
* **Recognize Psychological Triggers:** Understand how attackers exploit urgency, fear, authority, and curiosity to bypass critical evaluation[cite: 1].
* **Detect Technical Red Flags:** Safely inspect embedded URLs, typosquatting domains, sender headers, and unsafe attachment types[cite: 1].
* **Execute Incident Response:** Apply the 3-Step containment protocol when encountering or interacting with threats[cite: 1].

---

## 🔍 Core Attack Vectors Covered

| Vector Type | Attack Methodology & Description |
| :--- | :--- |
| **Spear Phishing** | Highly customized attacks targeting specific individuals or teams using Open-Source Intelligence (OSINT) gathered from social platforms and corporate sites[cite: 1]. |
| **Whaling (CEO Fraud)** | High-level executive impersonation intended to trick employees into approving unauthorized transfers or releasing sensitive records[cite: 1]. |
| **Smishing & Vishing** | Social engineering executed via SMS text messages (Smishing) or voice calls (Vishing)[cite: 1]. |
| **Clone Phishing** | Re-creating a legitimate, previously delivered email containing links or attachments and swapping them with malicious payloads[cite: 1]. |

---

## 🧠 Psychological Manipulation Triggers

* **Urgency:** Imposes artificial deadlines to force fast execution and prevent independent consultation[cite: 1].
* **Fear:** Threatens severe consequences (e.g., legal action, job termination) to induce panic[cite: 1].
* **Authority:** Impersonates corporate leaders or IT directors to leverage workplace deference[cite: 1].
* **Greed / Curiosity:** Offers fake bonuses, confidential lists, or gift cards to prompt impulsive actions[cite: 1].

---

## ⚠️ Red Flag Detection & Inspection Checklist

| Category | Inspection Focus & Anomaly Details | Risk Level |
| :--- | :--- | :--- |
| **Sender Address & Typosquatting** | Look-alike domains replacing characters with similar-looking symbols (e.g., `paypa1.com`)[cite: 1]. | **CRITICAL**[cite: 1] |
| **Embedded Links** | URL destination mismatch upon hovering cursor over hyperlink text[cite: 1]. | **CRITICAL**[cite: 1] |
| **High-Risk Attachments** | Double extensions (e.g., `Document.pdf.exe`), compressed archives (`.zip`), or macro-enabled Office files (`.docm`, `.xlsm`)[cite: 1]. | **CRITICAL**[cite: 1] |
| **Out-of-Band Payment Requests** | Unsolicited demands for wire transfers, gift cards, or banking detail modifications[cite: 1]. | **CRITICAL**[cite: 1] |
| **Generic Salutations** | Mass distribution indicators such as "Dear Customer" or "Valued Employee"[cite: 1]. | **MEDIUM**[cite: 1] |
| **Inconsistent Tone / Grammar** | Uncharacteristic language or awkward syntax from known internal contacts[cite: 1]. | **MEDIUM**[cite: 1] |

---

## 🛠️ Link Inspection Guidelines

1. **Never click** a link directly in an unverified or suspicious email[cite: 1].
2. **Hover over** the hyperlink text using your mouse cursor to reveal the actual destination web address[cite: 1].
3. **Analyze the primary domain** (the segment directly before `.com` or `.org`). For example, `security.company.com` is legitimate, whereas `company.com.attacker-site.com` belongs to `attacker-site.com`[cite: 1].
4. **Navigate manually** via official browser bookmarks if you suspect any anomaly[cite: 1].

---

## 🚨 Incident Response Protocol

If a suspicious email is identified, personnel must strictly follow the standard **3-Step Response Workflow**:

1. **DO NOT ENGAGE:** Do not click links, open attachments, reply, or forward the message to coworkers[cite: 1].
2. **REPORT IMMEDIATELY:** Use the integrated "Report Phishing" client button or forward the suspicious message as an attachment to `security@company.com`[cite: 1].
3. **CONTAIN IMPACT:** If credentials were exposed or a file was executed, immediately disconnect Wi-Fi/Ethernet connections and call the Security Operations Hotline[cite: 1].
