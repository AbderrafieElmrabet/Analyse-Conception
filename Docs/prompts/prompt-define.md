Define the custom problem for this pkg_gestion_apprenant which exists in (Package 2: Learner management) for this application (Soli-LMS) without details.

description pkg_gestion_apprenant: They allow the trainer to track the learner's progress in the form of a table or graphic chart.

## Global empathy

### Training Manager

#### What they say

- "We have two tracks, each with its modules and competencies at different levels."
- "I need precise tracking of competencies and hourly rates."

#### What they do

- Manages training programs by defining the modules, competencies, and levels for each track.
- Searches for tools that centralize information to optimize competency and hourly rate management.

#### How they feel

- Overwhelmed by the amount of information to structure and track.
- Wants a simpler and more visual management of competencies to facilitate training tracking.

#### What they need

- Display the grade of each learner for each module.
- A clear and concise dashboard to visualize the modules, competencies, and their progress.
- A structured tool to organize competencies by level and hourly rate, with precise and accessible definitions.

---

### Trainer

#### What they say

- "I need to easily see and assess the learners' competencies."
- "The current tools, like Excel, make it hard to track progress."

#### What they do

- Assigns grades to learners' competencies, with specific levels for each competency.
- Reviews project progress and assigns briefs to align learning objectives.

#### How they feel

- Frustrated by the lack of tools to effectively track progress and assess competencies.
- Wants a more intuitive tool to track projects and facilitate communication with learners.

#### What they need

- A centralized interface to view, grade, and track competencies, and easily access briefs.
- Integrated project management features to track deliverables and communicate about progress.

---

### Learner

#### What they say

- "I need to track the status of my projects and see my validated competencies."
- "I need to be able to easily change the status of my projects."

#### What they do

- Works on their projects, submits deliverables for validation, and looks to improve their competencies.
- Regularly checks their dashboard to assess progress and find additional resources.

#### How they feel

- Sometimes lost due to the complexity of competencies and tracking their progress.
- Motivated but feels the need for visibility to better understand their learning journey.

#### What they need

- A clear and structured personal space where they can see their validated competencies and the status of their projects.
- Easy access to additional resources and regular feedback from the trainer to stay motivated.

---

In summary, each actor in the **Soli-LMS** system desires a smoother and centralized experience, with clear and intuitive tools that facilitate tracking of competencies, projects, and training.

## Global ideation

### **Ideation (Design Thinking) for Soli-LMS**

To solve the global problem, the ideation for Soli-LMS will be structured in several functional packages. Each package aims to address the specific needs of the users identified during the empathy phase.

---

### **Package 1: Competency and Module Management**

**Goal**: Centralize competency and module information to allow the Training Manager to track competencies and hourly rates.

- **Training Manager Dashboard**: An interface displaying the modules, competencies, levels, and hourly rates associated with each track.
- **Competency Management**: A system for ranking competencies by levels with an option to customize descriptions.
  - **pkg_competences**.
- **Progress Tracking**: Synthetic statistics on learners' progress in each competency and module.

---

### **Package 2: Trainer Interface**

**Goal**: Provide trainers with an intuitive space to assess and track learners' competencies.

- **Competency Tracking Interface**: A dashboard with quick access to learners' competencies by module, with options to grade and track competencies.
  - **pkg_suivi_competences**.
- **Assessment and Feedback**: A feature to assign competency levels and add comments.
  - **pkg_validation**.
- **Project and Brief Management**: A section for managing briefs and deliverables, with the ability to track project status and provide feedback.
  - **pkg_creation_projet**.
  - **pkg_suivi_projet**.
- **Alerts and Notifications**: A reminder system to notify learners about comments or project deadlines.

---

### **Package 3: Learner Space**

**Goal**: Allow learners to track their progress and competencies in a personalized and motivating space.

- **Learner Dashboard**: A simple interface to view validated competencies, project status, and access resources.
- **Project Tracking**: A dedicated section for learners to manage and change the status of their projects easily.
- **Supplementary Resources**: A library of resources tailored to competencies and levels.
- **Regular Feedback**: A space to view feedback from trainers and allow interactions to clarify competencies or project goals.

---

### **Package 4: Data Centralization and Reporting**

**Goal**: Gather all data to create detailed reports on learners' progress, competencies, and modules.

- **Report Generation**: Creation of customizable reports on competencies, hourly rates, and overall progress.
- **Summary Tables**: A summary table for the Training Manager with filters to visualize specific data by module, competency, or level.
- **Integration with Excel and Other Tools**: Export options to Excel or other formats to facilitate compatibility with existing tools.

---

### **Package 5: Communication and Collaboration**

**Goal**: Improve communication between the Training Manager, trainers, and learners to ensure continuous follow-up.

- **Integrated Messaging System**: An internal chat to allow direct communication between trainers and learners.
- **Comments and Tracking**: Trainers can add comments directly in learners' projects.
- **Notifications and Alerts**: Alerts to remind about deadlines, trainer feedback, or specific competency achievements.

---

### **Package 6: User Management**

**Goal**: Manage the information of trainers, learners, and the Training Manager, and ensure proper organization of roles and permissions.

#### Key Features:

- **Profile Creation and Management**: Creation of profiles for each user, with specific fields for trainer information (modules taught, track) and learner information (level, track, competencies).
- **Role and Permission Assignment**: Defining roles for each user (trainer, learner, Training Manager) and associated permissions.
- **User Activity Tracking**: Activity history for each user to allow the Training Manager to view trainer involvement and learner progress.
- **Cohort Management**: An option to organize learners into groups or cohorts to facilitate training management by the Training Manager.

---

### **Conclusion**

This package structure for Soli-LMS ideation provides solutions to the specific problems faced by each stakeholder:

- **For the Training Manager**: A centralized dashboard and detailed reports facilitate the management of competencies and hourly rates.
- **For Trainers**: An intuitive interface and tracking tools simplify the evaluation of learners and communication.
- **For Learners**: A clear personal space and competency and project tracking features help them better visualize their progress.

This modular approach ensures that each user finds the features suited to their role, promoting better management and effective progress tracking.