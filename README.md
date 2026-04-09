<div align="center">
  <img src="pitch_deck_web/pitch_drone_hero.png" alt="UFLY AI Hero" width="800"/>
  
  # UFLY AI 🦅
  **The World's First Deep Reinforcement Learning Pilot for Heavy Cargo Delivery**
  
  [![License](https://img.shields.io/badge/License-Proprietary-blue.svg)](#)
  [![Status](https://img.shields.io/badge/Status-Simulated_Phase_3-green.svg)](#)
  [![AI](https://img.shields.io/badge/AI-PPO_Reinforcement_Learning-orange.svg)](#)
</div>

<br>

> *"We are not just building a drone. We are building the autonomous brain that will unlock the skies for the next billion people."*

---

## ⛰️ The Problem: The Logistics Gap
The logistics revolution has bypassed the world's most challenging terrains. For over 600 million people living in rural and mountainous regions (such as Southwest China), the booming e-commerce market is a distant promise. 

Roads are winding, dangerous, and slow. A delivery van making 200 km of straight-line progress must drive 300 km of mountain switchbacks, taking **over 7 hours** and operating at a **40-60% cost premium**. While urban centers enjoy 2-hour delivery, rural communities are forced to wait up to a week. 

Demand for fast delivery is inevitable. The roads, however, have reached their limit.

## 🚀 The Solution: Bypass the Mountains
**UFLY AI** is an autonomous, fixed-wing aluminum cargo drone designed to bypass the mountains entirely. Flying point-to-point in a straight line at 198 km/h, it turns a 7-hour treacherous drive into a **1-hour direct flight**.

- 📦 **400 kg Payload:** Built for heavy logistics, not just light parcels.
- ⚡ **6x Faster:** Eliminates winding roads and traffic.
- 🌍 **60% Less CO₂ & 50% Less Fuel:** Drastically reduces the carbon footprint of rural logistics.
- 🏭 **Ultra-Low Cost Structure:** Engineered strictly to CS-23 standards using **CNC 6061-T6 Aluminum**. We rejected expensive carbon-fiber entirely to bring the unit cost under $150K, enabling massive fleet scaling.

---

## 🧠 Our Ambition: The AI Pilot
The hardware gets us in the air, but the software is our true revolution. **We are building the first fully autonomous, Deep Reinforcement Learning (DRL) AI pilot capable of entirely replacing the human remote operator.**

Training a neural network to fly a 1,200kg heavy aircraft is notoriously unstable. Traditional simulators lack the aerodynamic fidelity to teach an AI how to survive a stall. To solve this, we:

1. **Built a Custom Physics Engine:** We modeled the non-linear CL-alpha stall curve and sigmoidal dynamics of the NACA 4412 airfoil from scratch. 
2. **4D Continuous Control Space:** Our PPO agent simultaneously controls ailerons, elevator, rudder, and throttle at 100Hz, perceiving the world through a 20-dimensional MDP (Virtual IMU, Pitot, Barometer, GPS).
3. **3-Phase Curriculum Learning:** We engineered a phased learning curriculum. The AI learns stabilization first, then coordinated banked navigation, and finally multi-waypoint mission execution under intense crosswinds.

**The result?** The AI doesn't just blindly follow waypoints—it *understands* how to fly, recovering from aggressive turbulence and reacting instantly without human intervention. Every flight generates data, feeding a compounding **Data Flywheel** that makes our AI pilot exponentially smarter.

---

## 🗺️ How We Will Make It Happen (Roadmap)

- [x] **Phase A (Digital Twin):** Complete structural engineering, CS-23 V-n diagrams, custom physics engine, and successful 600K-step AI training in simulation. *(We are here)*
- [ ] **Phase B (Subscale Validation):** Build a 1:4 scale prototype. Prove "Sim-to-Real" transfer of our AI by flying physical avionics in real-world weather.
- [ ] **Phase C (Full-Scale Hardware):** Manufacture the first 1,200kg aluminum prototype, perform experimental flight tests, and validate the CNC manufacturing line.
- [ ] **Phase D (Fleet Deployment):** Launch the first commercial "Logistics as a Service" pilot on a high-cost mountain route. Expand the AI capability globally.

---

## 🤝 Join the Mission
We are at the intersection of classical aerospace engineering and cutting-edge artificial intelligence. We are currently raising our **Pre-Seed Round** to take our AI from the digital twin to physical airspace.

If you are a deep-tech investor, an embedded systems engineer, or a logistics partner eager to revolutionize the supply chain, let's talk.

**Connect with the Founder:** Unai Picot 
📧 unaipicot@gmail.com
💼 [LinkedIn](https://linkedin.com/in/unai-picot-8383a624b)
Phone Number: +34 672242834   (Spain)
              +86 18601933209 (China)
