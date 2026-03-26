# Cyber Security Concepts Guide (Buzzwords)
---

## 1. Triage (The "Emergency Room" Phase)

**Definition:**  
The process of quickly sorting through problems to decide which ones are the most urgent.

**In Cybersecurity:**  
In the first moments of an incident, don't try to fix everything. Triage the situation:
- What is the biggest threat?
- Is the attacker still inside?
- Is data currently leaking?

Fix the most critical issues first.

---

## 2. CIA Triad (The "Core Goals" of Security)

This is the gold standard for explaining impact. Every incident affects at least one of these:

- **Confidentiality:** Keeping data private  
  *(Was sensitive information exposed?)*

- **Integrity:** Keeping data accurate  
  *(Was data altered or tampered with?)*

- **Availability:** Keeping systems accessible  
  *(Were systems disrupted or taken offline?)*

**Example Statement:**  
> "Our assessment shows a loss of Integrity because data was modified."

---

## 3. The "Castle" Model

**Definition:**  
An older security approach where defenses focus mainly on the outer boundary, assuming internal users are trustworthy.

**The Flaw:**  
If an attacker gets past the perimeter (e.g., via stolen credentials), they can move freely inside.

**Key Insight:**  
> "A perimeter-focused model increases risk if internal access is not controlled."

---

## 4. Defense-in-Depth (The "Layer Cake")

**Definition:**  
A layered security approach using multiple controls at different levels.

**The Logic:**  
If one layer fails (e.g., a phishing attack succeeds), other layers (e.g., endpoint protection, MFA) help stop the threat.

It assumes that failures can happen and prepares for them.

---

## 5. Moat and Perimeter

- **Perimeter:**  
  The boundary between a private network and external networks (e.g., the internet).

- **Moat:**  
  Security controls such as firewalls, intrusion detection systems, or email filters that protect the perimeter.

**Improvement Idea:**  
> "Strengthen perimeter defenses by restricting unnecessary external access."

---

## 6. Segmentation (The "Fire Doors")

**Definition:**  
Dividing a network into smaller, isolated sections.

**The Logic:**  
If a breach occurs in one segment, it should not spread to others.

**In Cybersecurity:**  
Access between systems should be limited based on need.

**Key Insight:**  
> "Network segmentation helps contain breaches and reduces overall impact."
