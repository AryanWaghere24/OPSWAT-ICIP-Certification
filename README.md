# OPSWAT Academy — Introduction to Critical Infrastructure Protection (ICIP)

![OPSWAT Badge](https://img.shields.io/badge/OPSWAT-ICIP%20Certified-6C3483?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## What This Is -

This repository documents my study notes and key takeaways from the **OPSWAT ICIP (Introduction to Critical Infrastructure Protection)** certification course.

The course is designed for IT professionals, cybersecurity students, and anyone looking to understand how national-level infrastructure is protected — both physically and in cyberspace. It's a foundational cert that bridges the gap between traditional IT security and the OT/ICS (Operational Technology / Industrial Control Systems) world.

---

## Course Structure - 

The course consists of two modules:
- **Module 1:** Critical Infrastructure Protection Fundamentals
- **Module 2:** ICIP Exam

---

## Key Concepts Covered - 

### 1. What is Critical Infrastructure Protection (CIP)?
CIP refers to the protection of assets, systems, and networks — physical or virtual — so vital to a nation that their disruption would have a **debilitating effect** on:
- National security
- Economic stability
- Public health or safety

> The definition evolved over time to include **cyber threats**, not just physical ones.

---

### 2. Governing Directives - 

| Directive | Full Name | Purpose |
|-----------|-----------|---------|
| **PPD-21** | Presidential Policy Directive 21 | Current framework for CI Security & Resilience |
| **HSPD-7** | Homeland Security Presidential Directive 7 | Original directive — established the 16 sectors |

---

### 3. The 16 Critical Infrastructure Sectors - 

Defined by the U.S. Department of Homeland Security (DHS):

| # | Sector | Key Note |
|---|--------|----------|
| 1 | Information Technology | Collaborative threat assessment; works with Communications sector |
| 2 | Critical Manufacturing | Cross-sector domino effect if disrupted |
| 3 | Chemical | DHS = Chemical Sector SRMA |
| 4 | Water & Wastewater Systems | Safe water = prerequisite for public health |
| 5 | Dams | Irrigates 10% cropland, protects 43% population, generates 60% Pacific NW electricity |
| 6 | Transportation Systems | Only sector with Co-SRMAs: DHS + DOT |
| 7 | Energy | PPD-21 "enabling function" — powers all other sectors; 80%+ privately owned |
| 8 | Nuclear Reactors, Materials & Waste | Covers civilian nuclear including medical isotopes |
| 9 | Commercial Facilities | Open public access = key vulnerability |
| 10 | Government Facilities | Physical + cyber elements; federal/state/local/tribal + overseas |
| 11 | Financial Services | Ranges from community banks to global institutions |
| 12 | Healthcare & Public Health | Privately owned; healthcare = local, public health = all gov levels |
| 13 | Food & Agriculture | ~1/5 of U.S. economic activity; 2.1M farms, 935K restaurants, 200K+ facilities |
| 14 | Defense Industrial Base | Worldwide; 100,000+ companies; mobilize, deploy, sustain military ops |
| 15 | Emergency Services | Prevention, Preparedness, Response, Recovery; paid + volunteer |
| 16 | Communications | PPD-21 "enabling function" — like Energy, all sectors depend on it |

> **Only two sectors** hold PPD-21's "enabling function" designation: **Energy** and **Communications**.

---

### 4. Cybersecurity in CI - 

CIP covers security from **physical to electronic**. The course focuses on three core cybersecurity areas:

| Topic | What It Means |
|-------|---------------|
| **Malware Mitigation** | Detecting and neutralizing malicious software in CI environments |
| **Device Compliance** | Ensuring all connected devices meet security standards |
| **Access Control** | Managing and restricting who can access critical systems |

**Why CI is more vulnerable today:**
CI was originally designed to operate in isolation. As global demand increased, systems became interconnected — creating a much larger attack surface across sectors and the internet.

---

## Real-World Case Studies - 

These attacks were covered in the course and demonstrate exactly why CIP matters:

| Year | Incident | What Happened | Impact |
|------|----------|---------------|--------|
| **2013** | Bowman Avenue Dam, NY | Iranian hackers breached the system | Gained control of floodgates |
| **2016** | Ukrainian Power Grid | Coordinated cyberattack | 700,000 people lost power in mid-December |
| **2017** | Saudi Petrochemical Plant | **Triton** malware deployed | Took over Safety Instrument Systems (SIS) — designed to cause physical harm |
| **2021** | Colonial Pipeline, USA | Ransomware attack | 45%+ of U.S. East Coast fuel supply (gas, diesel, jet fuel) went offline |

> The **Triton** malware case is particularly significant — it was the first malware specifically engineered to target industrial safety systems, not just disrupt operations but potentially cause physical disasters.

---

## Real-World Relevance - 

These concepts aren't academic. Here's how they map to real work:

- **Penetration testers and red teams** working on OT/ICS engagements need to understand which sectors they're dealing with and the regulatory frameworks around them.
- **SOC analysts** monitoring industrial networks need to recognize that a breach in CI doesn't just mean data exfiltration — it can mean physical consequences.
- **Compliance teams** in energy, healthcare, or finance need to understand their sector-specific SRMA responsibilities under PPD-21.
- **IT professionals transitioning to OT** will find this course a solid foundation before going deeper into ICS-specific security (ISA/IEC 62443, NERC CIP, etc.).

---

## Key Takeaways - 

After completing this course, you should understand:

1. What qualifies something as "critical infrastructure" — the **debilitating effect** standard
2. The difference between **PPD-21** and **HSPD-7** and why it matters
3. All **16 CI sectors**, their unique characteristics, and which agencies oversee them
4. Why **Energy and Communications** are foundational to every other sector
5. How real-world attacks on CI have evolved — from physical to fully cyber
6. The three pillars of CIP cybersecurity: **Malware Mitigation, Device Compliance, Access Control**
7. Why interconnectivity of modern CI systems creates both opportunity and serious risk

---

## Personal Notes - 

> *This section contains my own observations and thoughts from going through the course.*

<!-- Add your personal notes below -->

- The 16 sectors weren't just a list to memorize — each one has a 
  real dependency on the others. If one goes down, others follow.

- The Triton malware case (2017) was the most alarming — it wasn't 
  built to steal data, it was built to cause physical explosions.

- Colonial Pipeline (2021) showed that ransomware isn't just an IT 
  problem anymore — it shut down fuel for millions of people.

- Energy and Communications being "enabling functions" makes sense — 
  nothing else works without them.

- Surprised to learn that 80%+ of energy infrastructure is privately 
  owned — meaning security depends heavily on private companies, not 
  just the government.

- The shift from isolated CI systems to internet-connected ones is 
  the root cause of most modern CI vulnerabilities.

- Takeaway: OT/ICS security is where traditional IT security meets 
  the physical world — and the stakes are much higher.
---

## Resources - 

- [OPSWAT Academy](https://learn.opswatacademy.com)
- [CISA — Critical Infrastructure Sectors](https://www.cisa.gov/topics/critical-infrastructure-security-and-resilience/critical-infrastructure-sectors)
- [PPD-21 Full Text](https://obamawhitehouse.archives.gov/the-press-office/2013/02/12/presidential-policy-directive-critical-infrastructure-security-and-resil)
- [HSPD-7](https://www.dhs.gov/homeland-security-presidential-directive-7)

---

## Certificate - 

> OPSWAT ICIP Certification — Issued [May 2026]

<!-- Add your certificate image or link here -->
![Description](image-url)

---

*Notes compiled during active study — not official OPSWAT material.*
