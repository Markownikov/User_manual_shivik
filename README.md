# Platform User Manual - Complete Navigation Guide

## Table of Contents
1. [Admin Login](#1-admin-login)
2. [Organization Setup](#2-organization-setup)
3. [Permissions Configuration](#3-permissions-configuration)
4. [User Onboarding](#4-user-onboarding)
5. [Attendance Configuration](#5-attendance-configuration)
6. [HR Management](#6-hr-management)
7. [Project Creation](#7-project-creation)
8. [Project Planning](#8-project-planning)
9. [Scheduling](#9-scheduling)
10. [Task Assignment](#10-task-assignment)
11. [Daily Progress Reporting (DPR)](#11-daily-progress-reporting-dpr)
12. [Real-Time Schedule Updates](#12-real-time-schedule-updates)
13. [Task Insights](#13-task-insights)
14. [Issue Management](#14-issue-management)
15. [Manager/Admin Controls](#15-manageradmin-controls)
16. [Resource Management](#16-resource-management)
17. [Vendor Management](#17-vendor-management)
18. [Dashboard Overview](#18-dashboard-overview)
19. [Notifications & Alerts](#19-notifications--alerts)

---

## 1. Admin Login

### Step-by-Step Process:
1. **Access Login Page**
   - Open the application URL in your browser
   - You will be directed to the login screen

2. **Enter Credentials**
   - Fill in your **Email Address** in the email field
   - Enter your **Password** in the password field
   - Click the **"Sign In"** button

3. **Successful Login**
   - After successful authentication, you will be redirected to the **Dashboard**
   - The main navigation sidebar will appear on the left side

---

## 2. Organization Setup

### Navigation Path: Dashboard → Team and Collaboration → Users

### 2.1 Creating Departments, Roles, and Users

#### Manual Creation:
1. **Access Users Module**
   - On the **left sidebar**, locate and click on **"Team and Collaboration"**
   - The **Users page** will automatically open

2. **Create Departments**
   - Look for the **"Departments"** section or tab
   - Click **"Add Department"** or **"+"** button
   - Fill in department details:
     - Department Name
     - Description (optional)
     - Department Code (if applicable)
   - Click **"Save"** to create the department

3. **Create Roles**
   - Navigate to the **"Roles"** section or tab
   - Click **"Add Role"** or **"+"** button
   - Fill in role details:
     - Role Name
     - Role Description
     - Permission Level
   - Click **"Save"** to create the role

4. **Create Users Individually**
   - Go to the **"Users"** section
   - Click **"Add User"** or **"+"** button
   - Fill in user details:
     - Full Name
     - Email Address (must be unique)
     - Mobile Number (must be unique)
     - Select Department (from dropdown)
     - Select Role (from dropdown)
   - Click **"Save"** to create the user

#### Bulk Upload Process:
1. **Access Bulk Upload**
   - In the Users page, look for the **"Bulk Upload"** button
   - Click on **"Bulk Upload"**

2. **Download Template**
   - Click the **"Download Template"** button
   - An Excel template will be downloaded to your computer

3. **Fill the Template**
   - Open the downloaded Excel file
   - Fill in the following columns:
     - **Name**: User's full name
     - **Email**: Unique email address
     - **Mobile**: Unique mobile number
     - **Department**: Department name
     - **Role**: Role name
   - Save the Excel file

4. **Upload Completed Template**
   - Return to the bulk upload section
   - Click **"Choose File"** or **"Browse"**
   - Select your completed Excel file
   - Click **"Upload"**
   - The system will automatically create users, departments, and roles

### 2.2 Setting Up Reporting Hierarchy

1. **Edit Individual User**
   - In the Users list, locate the user you want to edit
   - Click the **three dots (⋮)** next to the user's name
   - Select **"Edit"** from the dropdown menu

2. **Configure Reporting Structure**
   - In the edit form, look for **"Reporting To"** field
   - Select the manager/supervisor from the dropdown
   - Update any other necessary details
   - Click **"Update"** to save changes

3. **View Organization Chart**
   - Navigate to **"Organization Chart"** (usually under Team and Collaboration)
   - View the hierarchical structure of your organization
   - Verify reporting relationships are correctly established

---

## 3. Permissions Configuration

### Navigation Path: Dashboard → Team and Collaboration → Roles and Permission

1. **Access Permissions Module**
   - From the left sidebar, navigate to **"Team and Collaboration"**
   - Click on **"Roles and Permission"**

2. **Configure Role-wise Permissions**
   - Select a role from the roles list
   - Configure permissions for each module by toggling:
     - **Projects**: Read, Write, Update, Delete
     - **Tasks**: Read, Write, Update, Delete
     - **Users**: Read, Write, Update, Delete
     - **Reports**: Read, Write, Update, Delete
     - **DPR**: Read, Write, Update, Delete
   - Permissions are **automatically saved** when you toggle each option

3. **Apply Permissions**
   - Ensure all roles have appropriate permissions
   - Test permissions with different user accounts

---

## 4. User Onboarding

### 4.1 Sending Password Reset Notifications

#### Individual User Notification:
1. **Access User List**
   - Navigate to **Team and Collaboration → Users**

2. **Send Notification to Single User**
   - Click the **three dots (⋮)** next to a user's name
   - Select **"Notify"** from the dropdown
   - The system will send an email to the user with password setup instructions

#### Bulk User Notification:
1. **Select Multiple Users**
   - In the Users page, use checkboxes to select multiple users
   - Or use **"Select All"** if needed

2. **Send Bulk Notification**
   - Click the **"Notify Selected"** or **"Bulk Notify"** button
   - Confirm the action
   - All selected users will receive password setup emails

### 4.2 User Password Setup Process

1. **User Receives Email**
   - Users will receive an email with a password setup link
   - The email contains instructions and a secure link

2. **Password Creation**
   - Users click the link in the email
   - They are directed to a password creation page
   - Users create their new password following security guidelines
   - Click **"Set Password"** to complete setup

3. **First Login**
   - Users can now log in with their email and new password
   - For mobile app users, this enables push notifications

---

## 5. Attendance Configuration

### Navigation Path: Dashboard → Project Settings → Config → Attendance Configuration

1. **Access Attendance Settings**
   - From the left sidebar, go to **"Project Settings"**
   - Click on **"Config"**
   - Navigate to **"Attendance Configuration"****

2. **Geolocation Configuration**
   - Set up **work site locations**
   - Define **geofencing radius** for each location
   - Configure **GPS tolerance** settings

3. **Shift Configuration**
   - Create different **shift timings**
   - Set **start time** and **end time** for each shift
   - Configure **break times** if applicable
   - Assign **shifts to users** or departments


4. **Shift Assignment**
   - **Assign users to specific shifts** since there can be multiple shifts and locations
   - Navigate to **"Shift Assignment"** within the Config section
   - Select **users or departments** to assign
   - Choose **appropriate shift** from available options
   - Assign **location/site** for each user's shift
   - Configure **shift rotation** if applicable
   - Set **effective dates** for shift assignments

5. **Email Reports Configuration**
   - Access **"Email Reports"** tab within Attendance Management
   - Configure **automated email reports** for different stakeholders
   - **Report Types Available**:
     - **DPR Reports**: Daily progress summaries
     - **Attendance Reports**: Daily/weekly attendance summaries
   - **Email Settings**:
     - Select **report recipients** (managers, HR, admin)
     - Set **delivery schedule** (daily, weekly, monthly)
     - Configure **report format** (PDF, Excel, summary)
     - Define **report content** and level of detail
     - Set **automatic triggers** for critical situations

---

## 6. HR Management

### Navigation Path: Dashboard → HR Management

### 6.1 User Attendance Marking

1. **Access Attendance Module**
   - From the left sidebar, go to **"HR Management"**
   - Click on **"Attendance"**

2. **Mark Daily Attendance**
   - Users can mark their **daily attendance**
   - **Check-in** and **Check-out** functionality
   - **Geolocation verification** (based on configured settings)
   - **Time tracking** for working hours

3. **Attendance History**
   - View **personal attendance history**
   - Check **working hours** logged
   - Review **late arrivals** or **early departures**
   - Access **attendance reports**

### 6.2 HR Dashboard

1. **Access HR Dashboard**
   - In **"HR Management"**, click on **"Dashboard"**

2. **Attendance Overview**
   - View **team attendance summary**
   - Monitor **daily attendance rates**
   - Track **absenteeism patterns**
   - Identify **attendance compliance** issues

3. **Attendance Analytics**
   - **Graphical representation** of attendance data
   - **Weekly/Monthly trends**
   - **Department-wise attendance** comparison
   - **Individual performance** metrics

4. **Attendance Reports**
   - Generate **detailed attendance reports**
   - **Export data** for payroll processing
   - **Filter by date range**, department, or user
   - **Overtime tracking** and reporting

---

## 7. Project Creation

### Navigation Path: Dashboard → Projects → Create New Project

1. **Access Projects Module**
   - From the left sidebar,see at the bottom-most button is there , click on **"Projects"**(usually)
   - The projects list page will open

2. **Setup New Construction Project Workspace**
   - Click **"Create New Project"** button
   - Fill in the project creation form:
     - **Project Name**: e.g., "Skyline Towers Phase 1"
     - **Project Type**: Select from dropdown
     - **Location**: Enter "City, State"
     - **Company Logo**: Click to upload logo (SVG, PNG, JPG - max. 800x400px)
   - Use **"Clear Form"** to reset if needed
   - Click **"Cancel"** to abort or **"Create Project"** to proceed

3. **Project Configuration**
   - After creation, access **Project Settings → Config** from the sidebar
   - Configure **working days** (Monday-Friday, custom schedule)
   - Define **project calendar** (holidays, non-working days)

---

## 8. Project Planning

### Navigation Path: Dashboard → Projects → [Select Project] → Planning

### 8.1 Planning Options

#### Option 1: Import from MPP (Microsoft Project)
1. **Access Import Function**
   - In the project, navigate to **"Planning"** tab
   - Click **"Import from MPP"**

2. **Upload MPP File**
   - Click **"Choose File"** and select your .mpp file
   - Configure **import settings**
   - Click **"Import"** to process the file

3. **Review Imported Data**
   - Verify **tasks** are correctly imported
   - Check **dependencies** and **durations**
   - Confirm **resource assignments**

#### Option 2: Manual Creation
1. **Create Task Structure**
   - Click **"Add Task"** or **"+"** button
   - Fill in task details:
     - **Task Name**
     - **Expected Start Date**
     - **Expected Finish Date**
- This can be done manually and add indent and outdent to maintain hierarchy.

#### Option 3: AI Planning (Coming Soon)
- This feature will be available in future updates
- Will provide AI-assisted project planning capabilities

### 8.2 Project Configuration

1. **Working Days/Hours Setup**
   - Access **Project Settings → Project Config** from the sidebar
   - Define **project calendar**
   - Set **working days** (typically Monday-Friday)
   - Mark **holidays** and **non-working days**

2. **DPR Approval Configuration**
   - Navigate to **Project Settings → Approval Config**
   - Configure **DPR approval workflow**:
     - **Auto Approval**: DPRs are automatically approved upon submission
     - **Manual Approval**: DPRs require manager/admin approval before acceptance
   - Set **approval hierarchy** if using manual approval
   - Define **escalation rules** for pending approvals
   - Configure **approval timeouts** and **automatic escalation**


---

## 9. Scheduling

### Navigation Path: Dashboard → Projects → [Select Project] → Schedule

1. **Access Scheduler**
   - Navigate to your project
   - Click on the **"Schedule"** or **"Gantt Chart"** tab

2. **Validate Dependencies**
   - Review **task dependencies**
   - Check for **circular dependencies**
   - Ensure **logical task sequences**
   - Resolve any **scheduling conflicts**

3. **Gantt Chart Review**
   - View **project timeline** in Gantt chart
   - Check **critical path** (tasks that cannot be delayed)
   - Verify **resource allocation**
   - Identify **potential bottlenecks**

4. **Create Baseline (Optional)**
   - Once schedule is finalized, click **"Create Baseline"**
   - This saves the current schedule as a reference point
   - Useful for **progress tracking** and **variance analysis**

5. **Schedule Optimization**
   - Look for **resource conflicts**
   - Balance **workload distribution**
   - Optimize **task sequences**
   - Adjust **durations** if necessary

---

## 10. Task Assignment

### Navigation Path: Dashboard → Projects → [Select Project] → Schedule (MPP) / Assignments

### 10.1 Assigning Tasks in Schedule

1. **Access Schedule/MPP**
   - Go to your project
   - Navigate to **"Schedule"** or **"MPP"** section

2. **Assign Users in Resource Names Column**
   - In the schedule view, locate the **"Resource Names"** column
   - Click on the resource field for any task
   - Select **users** from the dropdown
   - Multiple users can be assigned to a single task

### 10.2 Viewing Assignment Details

1. **Access Assignments View**
   - From the sidebar, navigate to **Project Management → Assignments**
   - This is a **view-only** section for assignment details

2. **Filter and View Assignments**
   - Use filters to view assignments:
     - **My Team**: Tasks assigned to your team
     - **Everyone**: All task assignments
     - **This Week**: Assignments for current week
     - **Today**: Today's assignments
     - **Yesterday**: Previous day's assignments
   - View who is assigned to which tasks

### 10.3 Task Details and Management

1. **Access Task Details**
   - In the Assignments page, locate the task
   - Click the **"i" (info) icon** next to the task
   - Task details modal will open

2. **Manage Task Assignments**
   - In the task details modal:
     - **Add Document**: Attach relevant files
     - **Add Team Member**: Assign additional users
     - **Remove Team Member**: Unassign users
     - Update task information

3. **Notification Process**
   - Upon assignment, **users automatically receive notifications**
   - Notifications include:
     - **Task details**
     - **Timeline expectations**
     - **Deliverables required**

4. **Attendance Prompting**
   - Assigned users are **prompted to mark attendance** via mobile app
   - **Geolocation verification** ensures users are on-site
   - **Time tracking** begins with attendance marking

---

## 11. Daily Progress Reporting (DPR)

### Navigation Path: Mobile App → Login → Home Tab → DPR Tab → [Select Task] → Update DPR

### 11.1 Mobile App Access and Navigation

1. **Mobile App Login**
   - Open the **mobile application**
   - Enter your **email and password**
   - Click **"Sign In"** to login

2. **Home Tab Dashboard**
   - After login, the **Home tab** appears automatically
   - View the same dashboard elements as web version:
     - **S-Curve Analysis**
     - **Pending Approvals**
     - **Today's Targets**
     - **Task Progress Overview**
     - **Missing DPRs Alert**
     - **Team Performance Metrics**

3. **Navigate to DPR**
   - Switch to the **"DPR" tab** from the bottom navigation
   - View your assigned tasks requiring DPR submission

### 11.1 User DPR Submission

1. **Access Task for DPR**
   - In the **DPR tab**, view your task list
   - Select the **task** you want to update
   - Tap on the task to open DPR submission form

2. **Submit DPR Information**
   - Upload **progress photos** (before/during/after)
   - Add **written notes** about work completed
   - Enter **quantity measurements** (if applicable)
   - Record **materials used**
   - Note any **issues or delays**

3. **Submit for Approval**
   - Review all entered information
   - Tap **"Submit DPR"**
   - DPR status shows as **"Pending"** until approved

### 11.2 Mobile Task Details Access

1. **View Task Details on Mobile**
   - In the mobile app, **task details are accessible directly from the MyDPR tab**
   - **Note**: Schedule view is **only available on web** - mobile focuses on DPR and task execution

2. **Task Information Available in DPR tab**
   - **Task specifications** and requirements
   - **DPR submission history**
   - **Assigned team members**
   - **Attached documents** and drawings

### 11.3 DPR Approval Process

1. **Manager/Admin Review**
   - Managers access **"Team Tasks"** or **"DPR Reviews"**
   - Review submitted **photos and notes**
   - Verify **quantity measurements**
   - Check **progress against plan**

2. **Approval Actions**
   - **Approve**: DPR is accepted, progress updated in schedule
   - **Reject**: DPR sent back with comments for revision
   - **Request Clarification**: Ask for additional information

---

## 12. Real-Time Schedule Updates

### Navigation Path: Dashboard → Projects → [Select Project] → Live Schedule

1. **Automated Updates**
   - **Approved DPRs** automatically update actual dates in scheduler
   - **Progress percentages** are recalculated based on DPR data
   - **Schedule variances** are highlighted

2. **Impact Analysis**
   - System identifies **delayed tasks**
   - **Critical path** is recalculated
   - **Downstream impacts** are analyzed
   - **Recovery options** are suggested

3. **Real-time Monitoring**
   - **Live dashboard** shows current project status
   - **Progress indicators** update in real-time
   - **Alerts** are triggered for critical delays

---

## 13. Task Insights (WEB Platform)

### Navigation Path: Dashboard → Projects → [Select Project] → Schedule → [Select Level] → Right-click Task → Details

1. **Access Project Schedule**
   - Navigate to your **project**
   - Click on the **"Schedule"** section
   - **Note**: Tasks are not directly viewable - you must access them through the schedule

2. **Select Task Level and Access Details**
   - In the schedule view, **select the level** to view tasks for that specific level
   - Locate the task you want to view details for
   - **Right-click** on the task
   - A **context menu** will open
   - Select **"Details"** from the menu options

3. **View Task Details**
   - Task details modal/page will open
   - Access **"Task Insights"** or **"Details"** tab

2. **View DPR Timeline**
   - See **complete history** of DPR submissions
   - Track **progress over time**
   - View **photo timeline** of work progress

3. **AI Image Analysis** (if enabled)
   - System analyzes **uploaded photos** using AI
   - Identifies **work quality** and **progress accuracy**
   - Provides **insights** on work completion

4. **Required Work Information**
   - View **task specifications**
   - Check **resource requirements**
   - Review **quality standards**
   - Access **technical drawings** or documents

---

## 14. Issue Management

### Navigation Path: Dashboard → Projects → [Select Project] → Issues

1. **Raise New Issue**
   - Navigate to **"Issues"** section
   - Click **"Raise Issue"** or **"+"** button
   - Fill in issue details:
     - **Issue Title**
     - **Description**
     - **Priority Level** (High, Medium, Low)
     - **Affected Task(s)**
     - **Category** (Quality, Safety, Resource, etc.)

2. **Assign Issue**
   - Select **responsible user(s)**
   - Set **due date** for resolution
   - Attach **photos or documents**
   - Click **"Create Issue"**

3. **Issue Communication**
   - Add **comments** and **updates**
   - Attach **additional media**
   - **Tag relevant users** for notifications
   - Track **resolution progress**

4. **Issue Closure**
   - Mark issue as **"Resolved"**
   - Add **resolution notes**
   - Attach **proof of resolution** (photos)
   - Get **approval** from issue reporter

---

## 15. Manager/Admin Controls

### Navigation Path: Dashboard → Management → [Various Modules]

1. **Team Tasks Overview**
   - View **all team members' tasks**
   - Monitor **progress status**
   - Review **pending DPRs**
   - Identify **bottlenecks**

2. **DPR Management**
   - **Approve or reject** submitted DPRs
   - View **DPR timelines** for all tasks
   - **Bulk approve** multiple DPRs
   - **Export DPR reports**

3. **Status Changes**
   - **Update task statuses** (Not Started, In Progress, Completed)
   - **Reassign tasks** to different users
   - **Modify deadlines** if necessary
   - **Update priorities**

4. **Communication Hub**
   - **Send announcements** to team
   - **Start discussions** on specific tasks
   - **Share updates** and notifications
   - **Broadcast important information**

5. **Document Module**
   - Access **task-wise categorized documents**
   - **Upload specifications** and drawings
   - **Organize files** by project/task
   - **Control document access** permissions

---

## 16. Resource Management

### Navigation Path: Dashboard → Operations and Logistics → Resource Management

### 15.1 Resource List Management

1. **Access Resource Management**
   - From the left sidebar, navigate to **"Operations and Logistics"**
   - Click on **"Resource Management"**
   - Select **"Resource List"**

2. **Create Resource Categories**
   - Click **"Add Category"** or **"+"** button
   - Define category details:
     - **Category Name** (e.g., Equipment, Materials, Tools)
     - **Category Description**
     - **Category Code** (if applicable)
   - Save the category

3. **Create Resource Sets**
   - Within each category, create **resource sets**
   - Group related resources together
   - Define **set specifications** and **usage rules**

4. **Add Individual Resources**
   - For each category, add specific resources:
     - **Resource Name**
     - **Resource Code/ID**
     - **Specifications**
     - **Quantity Available**
     - **Unit of Measurement**
     - **Cost per Unit** (if applicable)

5. **Update Resource Information**
   - Edit existing resources
   - Update **quantities** and **availability**
   - Modify **specifications** as needed
   - Track **resource condition** and **maintenance**

### 15.2 Resource Attendance

1. **Access Resource Attendance**
   - In the same **"Operations and Logistics"** sidebar
   - Below **"Resource List"**, click on **"Resource Attendance"**

2. **Mark Resource Attendance**
   - Select **date** for attendance marking
   - Choose **project/site** location
   - Mark **resources present** on site:
     - **Equipment attendance**
     - **Material availability**
     - **Tool check-in/check-out**

3. **Resource Utilization Tracking**
   - Track **daily resource usage**
   - Monitor **resource efficiency**
   - Record **maintenance activities**
   - Document **resource issues** or **breakdowns**

---

## 17. Vendor Management

### Navigation Path: Dashboard → Vendors → Vendor Management

1. **Create Vendor Profiles**
   - Navigate to **"Vendors"** section
   - Click **"Add Vendor"** or **"+"** button
   - Fill in vendor details:
     - **Company Name**
     - **Contact Person**
     - **Email and Phone**
     - **Specialization/Services**
     - **Address and Location**

2. **Vendor Assignment**
   - Assign **vendors to specific tasks**
   - Define **vendor responsibilities**
   - Set **deliverable expectations**
   - Configure **payment terms**

3. **Vendor Performance Tracking**
   - Monitor **vendor task completion**
   - Track **quality of work**
   - Record **payment history**
   - Maintain **performance ratings**

---

## 18. Dashboard Overview

### Navigation Path: Dashboard (Landing Page)

1. **S-Curve Analysis**
   - View **planned vs actual progress**
   - **Visual progress tracking** over time
   - **Variance analysis** and trends
   - **Performance indicators**

2. **My Tasks Section**
   - **Personal task list** for logged-in user
   - **Priority sorting** and filtering
   - **Quick status updates**
   - **Deadline tracking**

3. **Team Tasks & Approvals**
   - **Team member task overview**
   - **Pending approvals** queue
   - **Team performance** metrics
   - **Workload distribution**

4. **Missing DPRs Alert**
   - **Red flags** for overdue DPRs
   - **User-wise missing DPR** list
   - **Automatic reminders** sent
   - **Compliance tracking**

5. **Today's Targets**
   - **Daily objectives** and goals
   - **Progress toward targets**
   - **Achievement metrics**
   - **Performance indicators**

6. **Task Progress & DPR Timelines**
   - **Visual progress indicators**
   - **Timeline views** of activities
   - **Milestone tracking**
   - **Completion forecasts**

---

## 19. Notifications & Alerts

### 19.1 Automated Triggers

1. **Delay Alerts**
   - **Task delays** beyond tolerance
   - **Critical path** impacts
   - **Schedule slippage** warnings
   - **Recovery action** suggestions

2. **Critical Task Notifications**
   - **High-priority task** updates
   - **Critical path** task alerts
   - **Deadline approaching** warnings
   - **Resource conflicts**

3. **Missing DPR Alerts**
   - **Overdue DPR** reminders
   - **Daily deadline** notifications
   - **Compliance warnings**
   - **Manager escalations**

4. **Absentee Notifications**
   - **Missing attendance** alerts
   - **Unauthorized absence** warnings
   - **Location compliance** issues
   - **Time tracking** discrepancies

### 19.2 Notification Channels

1. **Push Notifications**
   - **Mobile app** instant notifications
   - **Real-time alerts** for urgent matters
   - **Customizable notification** settings
   - **Priority-based** delivery

2. **Email Notifications**
   - **Daily digest** emails
   - **Weekly summary** reports
   - **Critical alert** emails
   - **Approval request** notifications

3. **Level-wise Notifications**
   - **Engineer Level**: Task assignments, DPR reminders
   - **Manager Level**: Team updates, approval requests
   - **Admin Level**: System alerts, compliance issues

---

## Troubleshooting & Support

### Common Issues and Solutions

1. **Login Issues**
   - Verify **email and password** accuracy
   - Check **internet connection**
   - Clear **browser cache**
   - Contact **system administrator**

2. **DPR Submission Problems**
   - Ensure **photos are properly sized**
   - Check **internet connectivity**
   - Verify **location services** are enabled
   - Restart the **mobile application**

3. **Notification Issues**
   - Check **notification permissions**
   - Verify **email settings**
   - Update **mobile application**
   - Review **notification preferences**

### Contact Information

- **Technical Support**: [hello@shivik.in]
- **Admin Contact**: [admin@shivik.in]
- **Emergency Hotline**: [+91 9266282435]

---

*This manual provides comprehensive guidance for all platform users. For additional assistance, please contact your system administrator or technical support team.*
