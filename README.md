# Requirement Analysis

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, documenting, and managing the needs and expectations of stakeholders for a software project. It is the **first and most critical phase** of the Software Development Life Cycle (SDLC), as it lays the foundation for all subsequent stages such as design, development, testing, and deployment.

In this stage, analysts and developers work together with stakeholders (clients, end-users, and business managers) to understand *what the system should do* and *how it should perform*.  
This process ensures that the software being developed aligns with business goals and user expectations.

**Importance in SDLC:**
- It defines the project scope clearly.
- Prevents costly rework by detecting misunderstandings early.
- Improves communication between stakeholders and developers.
- Serves as the baseline for system design, development, and testing.

---

## Why is Requirement Analysis Important?

Requirement Analysis is critical to the success of any software project because it ensures clarity, alignment, and precision from the beginning.

**Key reasons include:**

1. **Prevents Miscommunication**  
   It ensures that both clients and developers share a common understanding of the project’s objectives and functionality.

2. **Reduces Development Costs and Time**  
   Detecting issues early in the requirement phase prevents expensive changes during later stages of the SDLC.

3. **Improves Product Quality**  
   Well-defined requirements lead to systems that meet user needs accurately and perform efficiently in real-world environments.

---

## Key Activities in Requirement Analysis

The Requirement Analysis process typically includes five main activities:

- **Requirement Gathering**  
  Collecting initial information about what stakeholders expect from the system.

- **Requirement Elicitation**  
  Engaging stakeholders through interviews, surveys, and workshops to uncover detailed needs and constraints.

- **Requirement Documentation**  
  Recording gathered requirements in a structured and understandable format such as Software Requirement Specification (SRS).

- **Requirement Analysis and Modeling**  
  Evaluating, refining, and modeling the requirements using tools like data flow diagrams, use case diagrams, and user stories.

- **Requirement Validation**  
  Ensuring that all documented requirements are complete, consistent, feasible, and meet business objectives.

---

## Types of Requirements

### **Functional Requirements**

Functional Requirements describe *what the system should do*. They define the core features and operations that fulfill user needs.

**Example (for the Booking Management System):**
- Users can create and manage booking accounts.
- The system should allow users to search available rooms or properties.
- Admins can approve or reject booking requests.
- The system must generate booking confirmation emails automatically.

### **Non-functional Requirements**

Non-functional Requirements define *how the system performs its functions*. They relate to system attributes such as performance, usability, reliability, and security.

**Example (for the Booking Management System):**
- The system should load booking search results within 3 seconds.
- It should support up to 10,000 simultaneous users.
- The website should be accessible from both desktop and mobile devices.
- User data must be encrypted to ensure privacy and security.

---

## Use Case Diagrams

A **Use Case Diagram** visually represents the interaction between **actors** (users or systems) and **use cases** (functionalities) within the system.  
It helps in understanding system boundaries, identifying user roles, and visualizing key functionalities.

**Benefits:**
- Simplifies complex requirements into visual form.
- Enhances communication between technical and non-technical stakeholders.
- Aids in validating that all user interactions are captured.

### **Use Case Diagram for Booking Management System**

**Actors:**
- Customer
- Admin
- Payment Gateway

**Use Cases:**
- Register Account
- Search Rooms
- Make Booking
- Process Payment
- Manage Bookings
- Approve/Reject Booking
- Generate Reports

**Diagram:**
![Booking Management System Use Case Diagram](https://github.com/RebiLee001/requirement-analysis/blob/main/images/alx-booking-uc.png)

---

## Acceptance Criteria

**Acceptance Criteria** define the specific conditions that a software feature must meet to be accepted by the stakeholders.  
They act as benchmarks to verify that a requirement has been implemented correctly and fulfills user expectations.

**Importance:**
- Ensures clarity on what “done” means for a feature.
- Serves as the foundation for test case creation.
- Prevents ambiguity and scope creep.
- Helps validate that the system meets business needs.

**Example – Checkout Feature in Booking Management System:**

| **Acceptance Criteria** | **Description** |
|--------------------------|-----------------|
| 1. User Authentication | Only logged-in users can proceed to checkout. |
| 2. Price Accuracy | The system displays the total booking cost with correct tax and discount calculations. |
| 3. Payment Confirmation | After successful payment, a confirmation message and email are sent to the user. |
| 4. Error Handling | If the payment fails, an error message is displayed with retry options. |
| 5. Data Security | Payment details are encrypted and comply with security standards. |

---

✅ **Files included in repository:**
- `README.md` (this document)  
- `alx-booking-uc.png` (Use Case Diagram image)
