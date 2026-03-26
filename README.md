# Cyber Security Concepts Guide (Buzzwords)
---

## 1. Triage (The "Emergency Room" Phase)

**Definition:**  
The process of quickly sorting through problems to decide which ones are the most urgent.

**In Cybersecurity:**  
In the first 20 minutes, don't try to fix everything. Triage the situation:
- What is the biggest threat?
- Is the hacker still inside?
- Is data currently leaking?

Fix the "bleeding" first.

---

## 2. CIA Triad (The "Core Goals" of Security)

This is the gold standard for explaining impact. Every hack breaks at least one of these:

- **Confidentiality:** Keeping secrets  
  *(Did they see private student files?)*

- **Integrity:** Keeping data accurate  
  *(Did they change grades or financial records?)*

- **Availability:** Keeping systems running  
  *(Did they crash the school website or Wi-Fi?)*

**Note for Judges:**  
> "Our impact assessment shows a total loss of Integrity because grades were modified."

---

## 3. The "Castle" Model

**Definition:**  
An older security strategy where you focus all your defense on the "outside" (the walls), assuming everyone inside the castle is trustworthy.

**The Flaw:**  
If a hacker gets past the front gate (e.g., stolen password), they have total *free rein* inside.

**The "Smart" Point:**  
> "The school relied on a 'Castle' model, which is why the hacker moved so easily once they were inside."

---

## 4. Defense-in-Depth (The "Layer Cake")

**Definition:**  
The modern version of the Castle. Instead of one big wall, you have multiple layers of security.

**The Logic:**  
If one layer fails (e.g., a teacher clicks a bad link), the next layer (e.g., antivirus or MFA) catches it.

It assumes failure will happen.

---

## 5. Moat and Perimeter

- **Perimeter:**  
  The digital boundary between the school's private network and the public Internet.

- **Moat:**  
  Tools like firewalls or email filters that sit on the perimeter. They block suspicious traffic before it reaches systems.

**The Fix:**  
> "We need to strengthen the perimeter by blocking all traffic from non-local IP addresses."

---

## 6. Segmentation (The "Fire Doors")

**Definition:**  
Dividing a large network into smaller, isolated sections.

**The Logic:**  
If a fire starts in one area, fire doors prevent it from spreading.

**In Cybersecurity:**  
If a student hacks the Library Wi-Fi, they should not be able to access the Principal’s computer.

**The "Smart" Point:**  
> "We recommend network segmentation so that a breach in the student Wi-Fi stays contained and cannot reach the grade database."
