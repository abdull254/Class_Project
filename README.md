# ⚽ World Cup 2026 & Soccer Adoption in the U.S.

## 📌 Project Overview
This project studies whether hosting the **2026 FIFA World Cup** will increase soccer adoption in U.S. cities.

The main idea is to compare:
- **Host cities** (e.g., Los Angeles, New York, Dallas)
- vs **Non-host cities** (e.g., Chicago, Minneapolis, Phoenix)

We also use insights from the **1994 World Cup** to understand long-term effects and predict what may happen **5–15 years after 2026**.

---

## 🎯 Research Question
**Does hosting the 2026 FIFA World Cup increase soccer adoption in U.S. cities compared to non-host cities?**

---

## 💡 Motivation
Most research focuses on:
- economic impact (jobs, tourism, GDP)

This project focuses on:
- **soccer adoption**
  - interest
  - participation
  - fan engagement

This is less studied and more relevant to long-term growth of soccer in the U.S.

---

## 📊 Data Sources

### 1. Google Trends (Main Data)
- Tool: Google Trends
- Data:
  - “soccer”
  - “youth soccer”
  - “MLS”
  - “soccer club”
- Level: city / metro
- Frequency: weekly

---

### 2. MLS Attendance 
- Source: MLS official stats, FBref
- Data:
  - attendance per match
  - mapped to cities

---

### 3. Youth Soccer Participation 
- Source: US Youth Soccer reports
- Data:
  - number of registered players
  - state-level estimates

---

### 4. Control Variables
- Source: U.S. Census
- Data:
  - population
  - median income

---

## 🏙️ Cities

### Host Cities (Treatment Group)
- New York
- Los Angeles
- Dallas
- Houston
- Atlanta
- Miami
- Seattle
- San Francisco
- Boston
- Philadelphia
- Kansas City

### Non-Host Cities (Control Group)
- Chicago
- Minneapolis
- Phoenix
- Denver
- Detroit
- San Diego

---

## 🧪 Methodology

### Difference-in-Differences (DiD)

We estimate:

Soccer Adoption = β0 + β1(Host) + β2(Post2026) + β3(Host × Post2026) + error

- **Host** = 1 if city is a host city
- **Post2026** = 1 after World Cup
- **β3** = treatment effect (main result)

---

## 📈 Variables

### Dependent Variable (Soccer Adoption)
- Google Trends score (0–100)
- Optional:
  - MLS attendance
  - youth participation

---

### Independent Variables
- Host city indicator
- Time (before vs after 2026)
- Interaction term (Host × Post)

---

##  Expected Results

### Short-term (0–2 years)
- increase in search interest
- increase in attention

### Medium-term (3–7 years)
- growth in participation
- increase in attendance

### Long-term (8–15 years)
- sustained growth only if infrastructure supports it

---

## 🧠 Key Insight

Unlike 1994, the 2026 World Cup happens in a **more developed soccer ecosystem**.

👉 Therefore, it is expected to:
- **accelerate growth**
- not just create it

---

## ⚙️ How to Run

### Install dependencies
pip install pytrends pandas
