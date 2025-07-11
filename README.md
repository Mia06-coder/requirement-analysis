# 📋 Requirement Analysis in Software Development

## 📝 Introduction  
This repository is dedicated to documenting the **Requirement Analysis phase** of the Software Development Life Cycle (SDLC) for a **Booking Management System**.  

The goal is to simulate a real-world project planning scenario by identifying, organising, and analysing system requirements. This structured approach ensures a clear roadmap for successful development and delivery.

## 📌 What is Requirement Analysis?

**Requirement Analysis** is a fundamental phase in the Software Development Life Cycle (SDLC) that involves identifying, gathering, and clearly defining the needs and expectations of stakeholders for a software system. This process sets the foundation for all subsequent stages of development, ensuring that the final product aligns with user goals and business objectives.

### 🎯 Importance in SDLC

- **Clarity and Direction**: Helps teams understand *what* needs to be built before *how* to build it.
- **Improves Communication**: Acts as a bridge between stakeholders, developers, designers, and testers.
- **Reduces Rework**: By clarifying expectations early, it minimises costly changes and misunderstandings later.
- **Supports Planning**: Provides input for estimating timelines, budgeting, and resource allocation.
- **Ensures Quality**: Establishes measurable acceptance criteria that guide testing and validation.

## ❓ Why is Requirement Analysis Important?

Requirement Analysis plays a vital role in the success of any software project. It provides a clear foundation for the entire development process and ensures alignment between the technical team and stakeholders.

### 🔑 Key Reasons

1. **Guides the Development Process**  
   Clearly defined requirements act as a roadmap for developers, reducing ambiguity and helping ensure the product meets expectations.

2. **Saves Time and Costs**  
   Identifying requirements early helps avoid unnecessary rework and scope creep, keeping the project within budget and on schedule.

3. **Ensures Stakeholder Satisfaction**  
   Involving users and stakeholders during requirement gathering guarantees the final solution addresses real needs, increasing satisfaction and usability.

## 🛠️ Key Activities in Requirement Analysis

The Requirement Analysis phase consists of several key activities that ensure a thorough understanding of what the software system should achieve:

- **Requirement Gathering**  
  Involves collecting information from stakeholders, users, and business documents to understand the needs of the system.

- **Requirement Elicitation**  
  Focuses on drawing out the actual requirements through techniques such as interviews, surveys, observations, and brainstorming sessions.

   **Requirement Documentation**  
  Organises and records the collected requirements in a clear, structured format, often in Software Requirement Specification (SRS) documents.

- **Requirement Analysis and Modeling**  
  Involves evaluating the gathered data, identifying gaps or conflicts, and using visual models like use case diagrams to represent system behaviour.

- **Requirement Validation**  
  Ensures the documented requirements are accurate, complete, and approved by all stakeholders before proceeding to design and development.

## 📐 Types of Requirements

### ✅ Functional Requirements  
Functional requirements specify **what the system should do**, i.e. the behaviours and features.

**Examples for Booking Management System**:  
- **User Registration & Login**: Users must create accounts and sign in.  
- **Search Properties**: Users can search for available properties by location and dates.  
- **Manage Listings**: Hosts can add, update, or delete property listings.  
- **Booking Flow**: Users select available rooms, proceed through booking, and receive notifications. 
### ⚙️ Non-functional Requirements  
Non-functional requirements define **how the system performs**, focusing on the system’s operation qualities.

**Examples for Booking Management System**:  
- **Low Latency**: Fast response times for search and booking operations. 
- **High Availability**: System remains operational even during peak usage.  
- **Scalability**: Able to handle increased load as user base or listings grow. 
- **Consistency**: Prevent double bookings by ensuring transactional accuracy.  

## 🧾 Use Case Diagrams

A **Use Case Diagram** is a visual representation of the interactions between users (actors) and the system. It outlines the key functionalities (use cases) that the system must support, making it easier to understand the scope and user behaviour.

### 🎯 Benefits of Use Case Diagrams
- Communicates how users interact with the system  
- Helps identify system boundaries and major features  
- Supports planning, design, and testing phases

<p align="center">
  <img src="./alx-booking-uc.png" alt="Use Case Diagram for Booking Management System" />
</p>
<p align="center"><strong>Figure 1:</strong> Use Case Diagram for Booking Management System</p>

## ✅ Acceptance Criteria

**Acceptance Criteria** are clearly defined conditions that a software feature must meet to be accepted by stakeholders. They serve as a checklist to determine whether the functionality behaves as expected and aligns with user needs.

### 🧠 Importance of Acceptance Criteria
- Helps developers and testers understand what’s expected
- Ensures alignment between business goals and technical implementation
- Provides measurable standards for verifying completion
- Reduces ambiguity and scope creep by defining success up front

---

### 🛒 Example: Checkout Feature – Acceptance Criteria

**Feature**: Complete Checkout Process  

**Acceptance Criteria**:
- ✅ The user must be able to proceed to checkout after selecting a property and dates.
- ✅ The system must display a summary of the booking (property name, dates, total cost).
- ✅ The user must be able to enter valid payment details and confirm the booking.
- ✅ Upon successful payment, the user receives a booking confirmation and reference number.
- ❌ If payment fails, the user is shown a clear error message and prompted to try again.

Each criterion helps ensure that the checkout experience is reliable, secure, and user-friendly.
