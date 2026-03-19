**Aashray**
Real-time income protection for gig workers  

Aashray is a real-time income protection system for Q-commerce delivery partners.

It combines:
- **Parametric insurance** → for major disruptions  
- **GigSave (micro-savings)** → for everyday income gaps  

→ Together, they ensure workers don’t lose income — whether it’s a bad day or a complete shutdown.

## 👤 Who are we solving for?

Ram, 26, Blinkit delivery partner in Greater noida

- Earns ₹600–900/day  
- Works long hours  
- No fixed salary  

If rain hits, AQI spikes, or his zone shuts down →  
**Income instantly drops to zero**

No fallback. No protection.


## 📍 The real problem

Most solutions treat income loss as a **rare event**.

But in reality:
- Some days are slow  
- Some days are partially disrupted  
- Some days are completely lost  

Workers don’t just need insurance —  
they need **continuous income stability**

# 💡 Our Approach

Aashray is designed as a **2-layer protection system**:

### Layer 1 — GigSave (Daily Protection)
Handles small, frequent income gaps  

### Layer 2 — Insurance (Event Protection)
Handles major disruptions automatically  

# 🪙 GigSave — Daily Income Stability

GigSave is a built-in micro-savings system.

### How it works:
- 5% of daily earnings is saved automatically  
- 95% is paid instantly to the worker  

At the end of the day:

If earnings fall below a minimum level →  
GigSave automatically fills the gap  

### 💡 Example

- Daily target: ₹650  
- Actual earnings: ₹490  
- Gap: ₹160  

GigSave pays ₹160 instantly.

No claim. No friction.

### 🧠 Why GigSave matters

Most income loss is:
- Small  
- Frequent  
- Stressful  

GigSave solves these without involving insurance.

# 🛡️ Insurance — Major Disruption Protection

For larger events, Aashray uses **parametric triggers**.

### Triggers:
- 🌧️ Heavy rainfall  
- 🌫️ AQI > 400  
- 🔥 Extreme heat  
- 🚧 Zone lockdown  
- 🏬 Dark store closure  

When triggered:
→ System automatically detects  
→ Verifies conditions  
→ Pays worker instantly  

# 🔄 Combined Workflow


Worker onboarded
↓
Weekly plan activated
↓
Daily earnings tracked
↓
5% → GigSave wallet
↓
Evening income check

IF small gap:
→ GigSave covers

IF large gap + disruption:
→ GigSave + Insurance payout

# 💰 Weekly Premium Model

| Plan | Price | Coverage |
|------|------|----------|
| Basic | ₹29 | ₹600 |
| Standard | ₹49 | ₹1200 |
| Pro | ₹89 | ₹2500 |

### Pricing adjusts based on:
- Zone risk  
- Seasonal conditions  
- Worker history  
- Claim patterns  

# ⚡ Parametric Trigger Logic

We rely on real-world data:

- Weather APIs  
- AQI APIs  
- Traffic/zone data  
- Platform signals  

👉 Important:
> No single signal is trusted — everything is cross-validated

# 🤖 AI/ML Integration

We use AI where it adds real value:

### 1. Premium Calculation
- Model: XGBoost  
- Inputs: zone, season, history  

### 2. Risk Profiling
- Model: Clustering  
- Output: plan tier  

### 3. Fraud Detection (core system)
We analyze:
- GPS authenticity  
- Movement behavior (sensor data)  
- Platform activity  
- Network consistency  

Output:
→ Internal **confidence score before payout**

# 🛡️ Fraud Prevention Approach

We assume fraud will happen.

So instead of trusting inputs, we validate behavior:

- Does the user move like a rider?  
- Were they active before disruption?  
- Does network location match GPS?  
- Are multiple users behaving identically?  

We also detect:
- Sudden claim spikes  
- Coordinated patterns  

### Important:
> If uncertain, we don’t block immediately  
→ Partial payout + review system  

# 📱 Platform Choice

- **Mobile app (React Native)** → primary for workers  
- **Web dashboard (React)** → admin & monitoring  

Reason:
> Workers are mobile-first and need instant interaction

# 🏗️ Tech Stack

### Frontend
- React Native  
- React.js  

### Backend
- Node.js + Express  
- PostgreSQL  
- Redis  

### AI/ML
- Python (XGBoost, Scikit-learn)  

### Integrations
- Weather APIs  
- AQI APIs  
- Maps  
- Razorpay (payments)  

# 🚀 Development Plan

### Phase 1
- Onboarding  
- Weekly plans  
- Mock triggers  

### Phase 2
- GigSave system  
- Auto payout engine  
- Basic fraud detection  

### Phase 3
- Advanced fraud system  
- Dashboard  
- Full simulation  

---

# 💼 Business Model

- Weekly premiums  
- GigSave float  
- Platform partnerships  

# 🧠 Final Thought

Aashray is not just about insurance.

It’s about making sure a worker doesn’t worry about  
“what happens if today goes bad.”

Because for gig workers, stability matters more than coverage.

## 👥 Team

Ram dwivedi
Harsh Shukla
Aditya raj shukla
Satyam singh
Satyam singh

## 🔗 Repository

(Add your GitHub link here)
