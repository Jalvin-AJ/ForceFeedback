# ForceFeedback
An affordable driving simulator designed for safe pre-road driver training. The current prototype focuses on realistic vehicle controls and simulation, with planned upgrades toward AI-based driver behavior analysis, adaptive scenarios, readiness scoring, Indian traffic simulation, and intelligent performance feedback.
![App Logo](https://github.com/Jalvin-AJ/ForceFeedback/blob/main/ForceFeedback.jpg)
Demo Vid: https://drive.google.com/file/d/14MEvnV9VndrbAsr3WGM7JVr0jKsl2z1y/view?usp=sharing
BTS Here: https://drive.google.com/file/d/1iZs3s1Pc8D1n-AB1ijvtXK-4YFh4U_ja/view?usp=sharing

# AI-Assisted Human-Centric Driver Readiness Simulator

An affordable driving simulator designed to help beginner drivers practice essential driving skills in a safe and controlled environment before entering real-world traffic.

## 🚗 About the Project

Learning to drive can be stressful, especially during the first few sessions. Beginners are often exposed to real traffic before they are comfortable with vehicle control, which can lead to hesitation, panic reactions, poor decision-making, and unsafe situations.

This project started as a low-cost driving simulator that allows learners to practice basic driving interactions without the risks associated with real-road training.

The long-term goal is to upgrade the simulator into an **intelligent driver readiness and human-assistive training platform** that can understand how a learner drives and adapt the training accordingly.

---

## 🎯 Problem

Traditional driving training depends heavily on real-road practice. This creates several problems:

- Beginners have limited opportunities for safe practice.
- Mistakes during early training happen in real traffic.
- Learners may experience fear and hesitation.
- Training is generally the same for every learner.
- Driving performance is difficult to measure objectively.
- Instructors have limited data about a learner's behaviour outside individual training sessions.
- Advanced driving simulators are often expensive and inaccessible to smaller training centres.

The project aims to address this gap by providing an affordable platform for **pre-road driver training**.

---

## 💡 Current System

The current version is a working prototype of a low-cost driving simulator.

The present setup focuses on:

- Steering input
- Accelerator and brake controls
- Realistic driving interaction
- Simulator-based road practice
- Hardware interfacing and control
- Basic vehicle simulation

The current prototype serves as the foundation for the next stage of development.

> **Current status:** Working prototype / early development stage.

---

## 🚀 Planned Intelligent Upgrade

The next phase of the project will focus on converting the current simulator into an **AI-assisted driver readiness system**.

Instead of treating the simulator only as a virtual vehicle, the upgraded system will treat the **learner as the primary focus**.

The system will collect driving behaviour data and use it to understand how the learner responds to different situations.

### Planned Features

#### 1. Driver Behavior Profiling

The system will analyse patterns such as:

- Steering stability
- Braking behaviour
- Acceleration control
- Reaction time
- Repeated driving errors
- Response to unexpected situations

This can be used to create an individual driving behaviour profile for each learner.

---

#### 2. Micro-Mistake Detection

The system will identify small driving mistakes that may not be obvious during normal training.

Examples include:

- Late braking
- Excessive steering corrections
- Lane deviation
- Delayed response to hazards
- Repeated hesitation
- Sudden acceleration or braking

The objective is to identify weak habits early so they can be corrected before real-road driving.

---

#### 3. Adaptive Scenario Difficulty

The simulator will gradually change the difficulty according to the learner's performance.

For example:

**Beginner / struggling learner**
→ Low traffic  
→ Simple roads  
→ Fewer simultaneous hazards

**Improving learner**
→ Higher traffic density  
→ Junctions  
→ Pedestrians  
→ Unexpected vehicles

**Advanced learner**
→ Night driving  
→ Rain  
→ Complex intersections  
→ Multiple simultaneous hazards

This creates a personalised training path instead of giving every learner the same experience.

---

#### 4. Driver Readiness Score (DRI)

A Driver Readiness Index will be developed to provide an objective view of learner performance.

Possible parameters include:

- Reaction time
- Steering stability
- Braking performance
- Hazard response
- Driving consistency
- Error frequency
- Improvement across sessions

The system can provide a score along with individual strengths and weaknesses.

The score will be used as a **training indicator**, not as an official driving licence or certification.

---

#### 5. Indian Traffic Behaviour Simulation

The simulator will focus on traffic situations that learners commonly experience in Indian road environments.

Possible scenarios include:

- Two-wheelers entering from unexpected directions
- Sudden pedestrian crossings
- Auto-rickshaw behaviour
- Sudden lane changes
- Crowded intersections
- Narrow roads
- Mixed traffic
- Unpredictable road users

The goal is to prepare learners for uncertainty rather than only ideal driving conditions.

---

#### 6. AI Scenario Generator

Instead of relying only on fixed scenarios, the future system will generate varied training situations based on parameters such as:

- Traffic density
- Road type
- Weather
- Time of day
- Hazard frequency
- Learner performance

This will make each training session less predictable and improve the learner's ability to respond to unfamiliar situations.

---

#### 7. Post-Drive AI Performance Analysis

After every session, the system will provide a structured performance report.

For example:

- Areas where the learner performed well
- Repeated mistakes
- Reaction-time trends
- Braking behaviour
- Steering stability
- Improvement compared with previous sessions
- Recommended areas for the next training session

The aim is to turn every simulation session into measurable learning data.

---

#### 8. Driving School Instructor Dashboard

A future software dashboard will allow instructors and training centres to monitor learners.

Possible information:

- Individual learner profiles
- Readiness score
- Training history
- Weak skill areas
- Progress over multiple sessions
- Scenario performance
- Recommended training modules

This can help driving schools move from subjective assessment toward **data-supported training**.

---

## 🧠 Proposed System Architecture

```text
                 ┌─────────────────────┐
                 │     Learner          │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Driving Controls     │
                 │ Steering / Pedals    │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Simulation Engine    │
                 │ Roads / Traffic /    │
                 │ Weather / Hazards    │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Behaviour Data       │
                 │ Collection           │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ AI / ML Analysis     │
                 │ Behaviour Profiling  │
                 │ Error Detection      │
                 └──────────┬──────────┘
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
      ┌────────────┐ ┌──────────────┐ ┌───────────────┐
      │ Readiness  │ │ Adaptive     │ │ Performance   │
      │ Score      │ │ Training     │ │ Feedback      │
      └────────────┘ └──────┬───────┘ └───────────────┘
                             │
                             ▼
                    Next Training Scenario
