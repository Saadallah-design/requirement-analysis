# Requirement Analysis in Software Development
Requirement Analysis repo for the ALX projects. Aim is to define and get acquianted with software development lifecycle.

## What is Requirement Analysis?
Requirement analysis is the process of identifying, documenting, and validating what a software system should do and the constraints under which it must operate.

It answers the question:
👉 “What problem are we solving, and what does the software need to achieve?”
👉 It is important for many reasons one of them is: It serves as the blueprint for design, coding, and testing.

### 💡 And Requirement Analysis is divided unto two types:
1. Functional Requirements
2. Non-Functional Requirements

## 💡 Why is Requirement Analysis Important?
The main takeway here is that the software you or your team is building must abide by certain rules and constrains.
You as an individual or team will allocate resources and your client allocates resources (money) for the final product which is the software in our case. Thus, agreeing on the **HOW**, **WHAT** and **WHY** of your software is a must. Some of the important roles of doing RA are:

1. Avoid misunderstandings between client and developers
    - Without clear requirements, developers and clients may have different ideas about what the system should do. RA makes sure everyone shares the same vision

2. Clear understanding of stakeholders needs
    - it ensures that all parties needs goes hand in hand; aligning  software features with business objectives (client needs) and user expectations (end users) which leads to delivering a product that satisfies users effectively. Ensuring the right solution.

3. This leads to Score definition and prevention of scope creep
    - Helps via setting clear project boundaries by defining what is included and exluded which in turn helps controlling costs and avoiding delays. Only building the features requires instead of building unrequired ones.

4. Saves time and money for both parties
    - Fixing mistakes during coding or testing is much more expensive than clarifying requirements early.

5. Better Project Planning and Cost Management
    -  With detailed requirements, project managers can estimate timelines, resources, and budgets more accurately, improving the overall planning and management of the project.

6. Improved Product Quality and User Satisfaction 
    - By explicitly capturing both functional and non-functional requirements, the final product is more likely to meet quality standards and end-user expectations, enhancing user satisfaction.

## 💡 Key Activities in Requirement Analysis

The process of Requirement Analysis starts with:
1. 📋 **Requirement gathering**
    - Gather detailed information about their needs and expectations. This can be done through interview, surveys/questionnaire, workshops, observation, or document analysis (reviewing exisiting docs and systems)

2. 📋 **Requirement elicitation**
    - With the provided insight from the first stage of data gathering, now it is time to really dig deep and ask what's the real problem that we're trying to solve. Differentiating between users needs, wants and real requirements. Also, sometime even clients may have conflicting / unclear requirements or hidden assumptions (things taken for granted and not communicated).

3. 📝 **Requirement documentation**
    - In this step, we formally record and document the requirements we've agreed upon with the stake holders and make sure that they're 
        * Clear
        * Consistent
        * Accessible
        * Traceable
    In this stage, functional (what the system should do) and non-functional (how; performance, security, usability, etc.) requirements are documented. This servces as a contract between stakeholders and developers.
    Moreover, in this stage user stories and use cases are built. 

4. 🔍 **Requirement analysis and modeling**
    - In this phase, requirements are prioritized based on their importance and impact. Their feasibility is being assessed in terms of technical, financial and time constraints. Some requirement might need a large budget that the client doesn't possess. Next, creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.

5. ✅ **Requirement validation**
    - After documenting and modeling the requirements comes the step of validating them with the stakehoders to ensure accuracy and completeness. 
    - Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
    - Establishing traceability matrices to ensure all requirements are addressed during development and testing.

6. We can also add Requirement maintenance/managing: as projects evove, requirements may change and this process ensures changes are tracked and controlled.

## 💡 Types of Requirements
As stated in the 3rd step of Requirement Analysis key activities, RA is divided unto two part:
1. ⚙️ **Functional Requirements**
    - Simply put: these determine what the system should do; system features and behaviors
    - Examples: User authentication, property search, booking system, user registration.
    * **Key Functional Requirements**:
        - ***Search Properties***: Users should be able to search for properties based on various criteria such as location, price, and availability.
        - User Registration: New users should be able to create an account with personal details and login credentials.
        - ***Property Listings:*** Display properties with essential details and images.
        - ***Booking System:*** Users should be able to book properties, view booking details, and manage their bookings.
        - ***User Authentication:*** Secure login and registration process for users.

2. 📏 **Non-Functional Requirements**
These describe how the system should perform and some examples for the airbnb clone project include: performance, scalability, usability, reliability.

* **Key Non-functional Requirements**:
        - ***Performance***: The system should load pages within 2 seconds and handle up to 1000 concurrent users.
        - ***Security***: Ensure data encryption, secure login, and protect against common vulnerabilities.
        - ***Scalability***: The system should be able to scale horizontally to handle increased traffic.
        - ***Usability***: The application should have an intuitive UI/UX, making it easy for users to navigate and perform tasks.
        - ***Reliability***: The system should have an uptime of 99.9% and recover quickly from any failures.

## 💡 Use Case Diagrams
We can say that use case diagrams are Visual representation of interactions between users and the system / software.
The sofware being developed has users/actors and these actors interact with the software/system to achieve a certain goal. The desired goal is the use case. 
For instance users can be: "guests" "admin" "registered user". Each user has different use cases or goals to achieve when interacting with the system. A guess wants to search properties, check their ratings, and at the end book the property and pay for it.

![Booking System Use Case Diagram] (/requirements-analysis/alx-booking-uc.png)
## 💡 Acceptance Criteria
Acceptance criteria are conditions that a feature must meet to be accepted by the stakeholders.
Before reaching this stage both developers and stakeholders need to define these criteria (check requirements validation). 
***These criteria need to be*** :
- Be specific and measurable.
- Include functional and non-functional aspects.
- Example for Booking System: “Users should be able to select available dates, confirm booking, and receive a confirmation email within 2 minutes.”

***Benefits of Acceptance Criteria:***
- Ensure all parties have a clear understanding of feature requirements.
- Provide a basis for testing and validation.
- Help in maintaining quality and meeting user expectations.