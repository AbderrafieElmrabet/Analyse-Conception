### **Ideation (Design Thinking) for Soli-LMS**

To solve the overall problem, the ideation for Soli-LMS will be structured into multiple functional packages. Each package aims to address the specific needs of users identified during the empathy phase.

---

### **Package 1: Competency and Module Management**

**Objective**: Centralize information on competencies and modules to allow the Training Manager to track competencies and hourly rates.

- **Training Manager Dashboard**: An interface that displays modules, competencies, levels, and hourly rates associated with each program.
- **Competency Management**: A system for organizing competencies by levels with an option to customize descriptions.
  - **pkg_competencies**.
- **Progress Tracking**: Synthetic statistics on learners' progress in each competency and module.

---

### **Package 2: Instructor Interface**

**Objective**: Provide instructors with an intuitive space to assess and monitor learners' competencies.

- **Competency Tracking Interface**: A dashboard with quick access to learners' competencies by module, with options to rate and monitor competencies.
  - **pkg_competency_tracking**.
- **Evaluation and Feedback**: A feature to assign competency levels and add comments.
  - **pkg_validation**.
- **Project and Brief Management**: A section for managing briefs and deliverables, with the ability to track project status and provide feedback.
  - **pkg_project_creation**.
  - **pkg_project_tracking**.
- **Alerts and Notifications**: A reminder system to notify learners of comments or project deadlines.

---

### **Package 3: Learner Space**

**Objective**: Enable learners to track their progress and competencies in a personalized and motivating space.

- **Learner Dashboard**: A simple interface to view their validated competencies, project status, and access resources.
- **Project Tracking**: A dedicated section for learners to manage and change the status of their projects easily.
- **Supplementary Resources**: A library of resources personalized based on competencies and levels.
- **Regular Feedback**: A space to view instructor feedback and enable interactions to clarify competencies or project objectives.

---

### **Package 4: Data Centralization and Reporting**

**Objective**: Gather all data to create detailed reports on learners' progress, competencies, and modules.

- **Report Generation**: Creation of customizable reports on competencies, hourly rates, and overall progress.
- **Summary Tables**: A summary table for the Training Manager, with filters to view specific data by module, competency, or level.
- **Excel Integration...