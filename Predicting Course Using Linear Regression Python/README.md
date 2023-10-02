# Chapter 3: Design & Methodology

In this chapter, we will discuss the methodology used to develop the proposed project, which is a system built using Flask and employs the Linear Regression algorithm for predicting course demand and estimating future enrollment. We will also address the technical requirements of the system, including software, data, and hardware, and provide a detailed explanation of the system's design and architecture.

## 3.1 Software and Web Framework

The chosen software framework for this project is Flask, a lightweight and versatile web framework for Python. Flask was selected for its simplicity and flexibility, making it suitable for developing a web-based application with features such as admin controls, login, dashboard, prediction, and database management.

## 3.2 Data Points and Relevance

The data points used in this project include historical enrollment data for three courses: BSCS (Bachelor of Science in Computer Science), BSIT (Bachelor of Science in Information Technology), and BSIS (Bachelor of Science in Information Systems). These data points are crucial for training the Linear Regression algorithm to predict course demand and estimate future enrollment accurately.

## 3.3 System Development Diagrams

### 3.3.1 Input-Process-Output (IPO)

![Use Case Diagram](/assets/LRPC/ipo.png)

Input: Historical enrollment data for BSCS, BSIT, and BSIS.
Process: Training the Linear Regression algorithm.
Output: Predicted course demand and future enrollment numbers.

The relationship between predicting course demand and estimating future enrollment is that the prediction of course demand is a part of estimating future enrollment. By predicting course demand, we can make informed decisions about how many students are likely to enroll in each course in the future.

### 3.3.2 System Architecture

![Use Case Diagram](/assets/LRPC/system-architecture.png)
 
The system architecture follows a client-server approach, where the Flask application serves as the server. The integration of machine learning in the study involves the incorporation of the Linear Regression model for predictive analysis. The components and layers of the system include:
- **Presentation Layer:** The user interface accessible through the web browser.
- **Application Layer:** Implemented in Flask, handling user requests and responses.
- **Machine Learning Layer:** Housing the Linear Regression model for course demand prediction.
- **Database Layer:** Storing historical enrollment data and user information.

## 3.4 Use Case Diagram and Activity Diagram

### 3.4.1 Use Case Diagram

![Use Case Diagram](/assets/LRPC/use-case.png)

The Use Case Diagram illustrates the major processes of the system, including user interactions such as login, accessing the dashboard, and making predictions.

### 3.4.2 Activity Diagram

![Activity Diagram](/assets/LRPC/activity-diagram.png)

The Activity Diagram further clarifies the sequence of activities within the system, highlighting the steps involved in making predictions and managing the database.

## 3.5 Context Diagram and Data Flow Diagram (DFD)

### 3.5.1 Context Diagram

![Context Diagram](/assets/LRPC/context-diagram.png)

The Context Diagram provides an overview of the system's interactions with external entities. In this case, it shows how the system interacts with users and the database.

### 3.5.2 Data Flow Diagram (DFD)

![Data Flow Diagram](/assets/LRPC/data-flow.png)

The Data Flow Diagram depicts the flow of data within the system, including data input, processing, and output.

## 3.6 ERD and RAD Diagram
### 3.6.1 Entity Relationship Diagram (ERD)

![Entity Relationship Diagram](/assets/LRPC/erd.png)

An Entity Relationship Diagram (ERD) is a visual representation of the relationships between different entities in a system or database. In the context of our project, we have created an ERD to illustrate how various elements of our system interact with each other and how data is organized.

### 3.6.2 Rapid Application Development (RAD) Diagram

![Data Flow Diagram](/assets/LRPC/rad.png)

Rapid Application Development (RAD) is an approach to software development that prioritizes rapid prototyping and quick iterations. Here, we provide a RAD diagram outlining the development phases and key milestones of our project.

## 3.7 Technical Requirements

### 3.7.1 Data Requirements

The system relies on historical enrollment data for BSCS, BSIT, and BSIS as its primary data source. This data must be collected, cleaned, and formatted for use in training the Linear Regression model.

## 3.7.2 Hardware Requirements

| Component          | Requirement                                             |
| ------------------ | ------------------------------------------------------- |
| Processor          | Standard processor with adequate processing power.     |
| Memory (RAM)       | Sufficient RAM for running the web server and database management system efficiently. |
| Storage            | Adequate storage space for storing application files and database data. |
| Desktop or Laptop  | Any standard desktop or laptop computer with the necessary hardware components. |

## 3.7.3 Software Requirements

| Software Component             | Purpose                                                 |
| ------------------------------ | ------------------------------------------------------- |
| Operating System (OS)          | Any modern operating system such as Windows, macOS, or Linux that supports Python and Flask. |
| Python                         | Python programming language for developing the Flask application. |
| Flask                          | Flask web framework for building the web-based system.  |
| NumPy and scikit-learn         | Python libraries for implementing the Linear Regression algorithm. |
| Database Management System     | A relational database management system (MySQL) for storing and managing historical enrollment data. |

# Chapter 4: Design & Methodology

## 4.1 Research Design

The research design for this project follows a mixed-method approach, combining both quantitative and qualitative research methods. This approach is essential to develop and evaluate the predictive model accurately while understanding user requirements and feedback.

### 4.1.1 Quantitative Research

**Objective:** To predict course demand and estimate future enrollment accurately.

**Method:** Employing the Linear Regression algorithm on historical enrollment data.

**Data Collection:** Gathering enrollment data for BSCS, BSIT, and BSIS.

**Data Analysis:** Using statistical metrics to evaluate the accuracy of the prediction model.

## 4.2 Requirements Analysis

Requirements analysis is a crucial phase in system development, involving the identification, documentation, and validation of system requirements. It helps ensure that the developed system meets user needs and expectations.

### 4.2.1 Requirements Documentation

### Functional Requirements

### Admin Controls

The system must provide administrators with the capability to modify student data and register new students, plates, and accounts.

### Login

Users must be able to log in securely with appropriate authentication mechanisms.

### Dashboard

The system shall display the following information on the dashboard:

#### Total Students

Presenting a pie chart representing the distribution of students across three courses (BSCS, BSIT, BSIS).

#### Yearly Enrollees

Displaying a graph showcasing the number of students enrolled per year, along with an average enrollment figure.

#### Semestral Data

Visualizing enrollment data per semester, categorized by course and year.

### Predict

The system should have the ability to generate predictions, including:

#### Expected Students for a Specified Date

Predict the number of students expected for a specified date.

#### The Most In-Demand Course

Determine the most in-demand course among BSCS, BSIT, and BSIS.

### Dataset

The system should include a data management module where data can be modified and stored securely.

## Non-Functional Requirements

### Performance

The system must be responsive and capable of handling concurrent users without significant performance degradation.

### Security

Data should be stored securely with encryption and access restricted to authorized users.

### User Interface Design

The user interface should be intuitive and user-friendly for administrators.

## User Requirements

### Administrator Interface

Administrators should have access to a simple and user-friendly interface for data modification and prediction generation.

### Prediction Accuracy

Users expect accurate and reliable predictions.

### Secure Access

Users should access the system securely using login credentials.


## 4.3 Technical Background

The Technical Background section provides essential technical context for the project.

## 4.4 Design of Software System/Process

The design phase involves creating detailed system blueprints, including database schema, user interfaces, and system workflows.

### 4.4.1 Database Schema

![Data Flow Diagram](/assets/LRPC/database-schema.png)

#### Database Schema

The database schema outlines the structure of the database, including tables for storing historical enrollment data, user information, and prediction results.

### 4.4.2 User Interface Design

![User Interface Design](/assets/LRPC/user-interface-design.png)

#### User Interface Design

The user interface design focuses on creating a user-friendly dashboard for users to interact with the system, providing easy access to predictions and data management.

### 4.4.3 Process Flow Diagram 

![Process Flow Diagram](/assets/LRPC/process.png)

## 4.5 Development & Testing

### 4.5.1 Development

The development phase involves implementing the Flask application, integrating the Linear Regression model, and creating the user interface.

### 4.5.2 Testing

Testing includes:

- **Unit Testing:** Testing individual components and functions for correctness.

- **Integration Testing:** Ensuring that different parts of the system work together.

- **User Acceptance Testing:** Involving users to validate that the system meets their needs and expectations.

## 4.6 Description of Prototype

A prototype of the system will be developed to gather user feedback and make necessary improvements. The prototype will include the core functionalities of prediction and data management.

## 4.7 Implementation Plan

The implementation plan outlines the schedule and milestones for the project, including development, testing, and deployment phases.

## 4.8 Population of the Study

The population of the study includes students and administrators who will interact with the system. Students will use the system to access course predictions, while administrators will manage the system and database.

## 4.9 Data Collection and Instrument

Data collection methods include surveys and interviews to gather user feedback. Surveys will be conducted online, and interviews will be scheduled with key stakeholders.

## 4.10 Data Sampling

Data sampling will be performed on historical enrollment data to create a representative dataset for training the Linear Regression model. This dataset will be used to make predictions and estimate future enrollment accurately.
