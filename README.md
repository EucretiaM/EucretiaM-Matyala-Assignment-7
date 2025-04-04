# Math Booster

## Introduction
Math Booster is a web and app-based platform designed to help primary and high school learners improve their mathematics performance. The system addresses poor mathematics marks at the primary school level and the high dropout rate from Grade 10 to Grade 12. Math Booster provides interactive learning tools, AI-powered assistance, and real-time teacher-learner engagement, all within a secure and user-friendly platform.

## Stakeholder Concerns
### **Key Stakeholders and Their Concerns**
- **Students:** Need easy access to learning materials, feedback, and a safe communication platform.
- **Teachers:** Require tools to upload assignments, track performance, and analyze learner progress.
- **Parents:** Want visibility into their child’s progress and assurance of a safe digital environment.
- **Administrators:** Concerned with secure access control, compliance with regulations, and efficient user management.
- **Developers:** Need a scalable, high-performance system that integrates AI and databases effectively.
- **Education Officials:** Expect alignment with the curriculum and measurable learning improvements.

## Functional Requirements
1. **User Authentication**
   - Secure login/registration via third-party API
   - Role-based access (teachers vs learners)

2. **Assignment Management**
   - Teachers can upload assignments
   - Learners can submit assignments
   - Notifications for new tasks

3. **Marking and Feedback**
   - Teachers can evaluate work within the platform
   - Feedback and memos visible in student profiles

4. **Performance Tracking**
   - Graphical performance analytics
   - AI-generated performance recommendations

5. **Communication**
   - Secure real-time chat (no external platforms like WhatsApp)
   
6. **Leaderboards**
   - Display top-performing learners

7. **AI-Powered Search**
   - AI-assisted search for math-related topics and questions

8. **Math Editor**
   - Built-in math symbol editor or VS Code-style interface for working with equations

## Non-Functional Requirements
- **Security:** End-to-end encryption, POPIA & GDPR compliance
- **Performance:** Fast response times (<2 seconds load time)
- **Scalability:** Designed for growing user and content volume
- **Reliability:** 99.9% uptime with automatic backups
- **Usability:** Mobile-responsive, intuitive UI
- **Maintainability:** Modular design, well-documented code
- **Hosting:** Secure cloud-based infrastructure (AWS/Azure/Firebase)

---

# **Kanban Board Templates**

## **Introduction to the Kanban Board Templates**
In agile development and project management, Kanban boards help visualize workflow, track tasks, and improve efficiency. Different templates cater to various team needs, including basic task tracking, automated workflows, and team planning. Below is a structured comparison of these Kanban board templates.

## **Overview of the Kanban Board Templates**
1. **Basic Kanban**
   - Simple task management with three main columns: **Todo, In Progress, Done**
   - Suitable for small teams or personal projects
   - Manual task movement

2. **Automated Kanban**
   - Workflow automation with task assignments and due dates
   - Predefined rules for status updates
   - Ideal for teams that need efficient task tracking

3. **Team Planning Kanban**
   - Supports collaborative projects with multiple members
   - Includes detailed backlog management and prioritization
   - Enhances visibility across different development stages

### **Key Status Categories**
| Status        | Description                              | Task Count |
|--------------|----------------------------------|------------|
| Todo        | Tasks not yet started                 | 0          |
| In Progress | Tasks currently being worked on       | 0          |
| Done        | Completed tasks                       | 0          |

## **Key Objectives**
- **Enhance Workflow Visibility:** Clear task status tracking
- **Improve Task Management:** Efficient tracking and prioritization
- **Facilitate Collaboration:** Supports teamwork and transparency
- **Streamline Automation:** Reduces manual workload through automated updates

## **Target Audience**
- **Project Managers** – Need efficient team tracking
- **Agile Teams** – Require structured task visualization
- **Developers & Designers** – Manage iterative tasks
- **Freelancers & Small Teams** – Benefit from a lightweight task board

---

## **Documentation**
### **User Documentation**
- **Getting Started Guide:** Instructions for setting up and using Kanban templates
- **Task Management Guide:** Best practices for effective task handling

### **Developer Documentation**
- **API Reference:** Endpoints for interacting with Kanban boards
- **Customization Guide:** Steps to modify templates for specific workflows

### **Specification Documentation**
- **System Architecture:** Overview of the Kanban board structure
- **Data Models:** Database schema and workflow representations

### **Additional Resources**
- **Performance Benchmarks:** Metrics for board efficiency
- **Change Log:** Version history and updates

## **Custom Kanban Board Creation**
1. **Added ‘Testing’ Column**
   - **Purpose:** Align with QA requirements for verification before deployment
   - **Benefit:** Ensures tasks are properly tested before release

2. **Added ‘Block’ Column**
   - **Purpose:** Track tasks with dependencies or missing information
   - **Benefit:** Identifies roadblocks early for smoother workflows

3. **Separated ‘Done’ from ‘Testing’**
   - **Purpose:** Distinguish implemented tasks from those needing validation
   - **Benefit:** Prevents premature closure of tasks

4. **Maintained ‘Todo’ and ‘In Progress’ Columns**
   - **Purpose:** Organize tasks based on development state
   - **Benefit:** Provides a structured workflow

5. **Task Categorization Using Draft Labels**
   - **Purpose:** Indicate early-stage tasks before active development
   - **Benefit:** Improves visibility into initial project phases

6. **Explicit Task Descriptions**
   - **Purpose:** Provide clarity on task requirements (e.g., ‘Develop upload button’)
   - **Benefit:** Enhances collaboration and understanding

7. **Linked Issues**
   - **Purpose:** Align development tasks with user story requirements
   - **Benefit:** Tracks progress against initial user needs

These customizations enhance workflow visibility, streamline QA processes, and improve efficiency in handling blocked tasks.

---

## **Contributors**
- Math Booster Development Team
- Agile Project Management Experts

## **License**
This project is licensed under the MIT License - see the LICENSE file for details.


