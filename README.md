# requirement-analysis

# requirement-analysis

# 📘 Requirement Analysis in Software Development

This repository is created as part of the ALX Software Engineering program to simulate a real-world requirement analysis phase for a **booking management system**. It serves as the blueprint for future development of both frontend and backend functionalities by outlining the system’s goals, use cases, requirement types, acceptance criteria, and key diagrams.

---

## 🔍 What is Requirement Analysis?

Requirement Analysis is a foundational phase in the Software Development Life Cycle (SDLC). It involves identifying, gathering, analyzing, and documenting the needs and expectations of stakeholders for a proposed software system. The goal is to ensure that the software product meets user needs and business objectives clearly and unambiguously.

This phase helps reduce ambiguity, scope creep, and rework during development. It defines **what** should be built before deciding **how** to build it.

---

## 💡 Why is Requirement Analysis Important?

1. **Defines Clear Scope**  
   Prevents misunderstandings and scope creep by ensuring all stakeholders agree on what is to be built.

2. **Improves Planning and Estimation**  
   Clear requirements allow for more accurate timeline and resource estimates.

3. **Enhances Communication**  
   Provides a reference point for developers, designers, QA, and clients.

---

## 🧩 Key Activities in Requirement Analysis

- **Requirement Gathering**  
  Collecting requirements from stakeholders using interviews, surveys, or observations.

- **Requirement Elicitation**  
  Digging deeper into what users need through brainstorming, prototyping, and use case scenarios.

- **Requirement Documentation**  
  Creating structured documentation such as SRS (Software Requirement Specification) and user stories.

- **Requirement Analysis and Modeling**  
  Categorizing and prioritizing requirements, and creating diagrams to visualize them.

- **Requirement Validation**  
  Verifying requirements with stakeholders to ensure completeness, clarity, and correctness.

---

## 🗂️ Types of Requirements

### ✅ Functional Requirements

These define what the system **should do** — the features and functions.

Examples for the booking system:

- Users can register and log in.
- Users can search for available properties.
- Users can book a property and receive confirmation.
- Admin can add or remove listings.

### ⚙️ Non-functional Requirements

These define **how the system performs** — constraints and qualities.

Examples:

- The booking form must load within 2 seconds.
- The system must handle 1000 concurrent users.
- All user data must be encrypted at rest and in transit.
- System uptime should be at least 99.9%.

---

## 🎭 Use Case Diagrams

Use Case Diagrams visually represent actors (users) and their interactions with the system.

**Actors**:

- Guest User
- Registered User
- Admin

**Use Cases**:

- Register/Login
- Search Properties
- Book Property
- Cancel Booking
- Manage Listings (Admin)
- Process Payment

![Use Case Diagram](alx-booking-uc.png)

---

## ✅ Acceptance Criteria

Acceptance Criteria define specific conditions a feature must meet to be accepted.

### Example: Checkout Feature

**Feature**: Complete Booking Checkout

**Acceptance Criteria**:

- Given a user is logged in and selects a property with valid dates
- When they enter payment details and click "Book Now"
- Then the system should:
  - Validate the data
  - Process payment successfully
  - Generate a booking ID
  - Show a confirmation screen
  - Send an email confirmation within 1 minute

---

## ✅ Repo Info

- GitHub Repository: `requirement-analysis`
- Status: 🚧 In Progress (Frontend + Backend Combined)
