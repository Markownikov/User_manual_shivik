# Shivik Platform User Manual
## Complete Navigation & Operational Guide

**Version:** 2.0  
**Date:** February 2026  
**Document Status:** Published

---

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
20. [Troubleshooting & Support](#troubleshooting--support)

---

## 1. Admin Login

### Step-by-Step Process:
1.  **Access Login Page**
    *   Open the Shivik Platform URL in your web browser.
    *   You will be directed to the authentication screen.

2.  **Enter Credentials**
    *   Enter your **Email Address**.
    *   Enter your **Password**.
    *   Click the **"Sign In"** button.

3.  **Successful Login**
    *   Upon authentication, you will be redirected to the **Shivik Dashboard**.
    *   The main navigation sidebar will be visible on the left.

---

## 2. Organization Setup

> 📍 **Navigation Path:** `Dashboard` → `Team and Collaboration` → `Users`

### 2.1 Creating Departments, Roles, and Users

#### Option A: Manual Creation
1.  **Access Users Module:** Locate **"Team and Collaboration"** on the left sidebar and select the **Users** page.
2.  **Create Departments:**
    *   Click the **"Departments"** tab.
    *   Click **"Add Department"** (or the **"+"** button).
    *   Enter: *Department Name*, *Description*, and *Code*.
    *   Click **"Save"**.
3.  **Create Roles:**
    *   Click the **"Roles"** tab.
    *   Click **"Add Role"**.
    *   Enter: *Role Name*, *Description*, and *Permission Level*.
    *   Click **"Save"**.
4.  **Create Users:**
    *   Click the **"Users"** tab.
    *   Click **"Add User"**.
    *   Enter: *Full Name*, *Email* (Unique), *Mobile* (Unique), *Department*, and *Role*.
    *   Click **"Save"**.

#### Option B: Bulk Upload Process
1.  **Access Bulk Upload:** Click the **"Bulk Upload"** button on the Users page.
2.  **Download Template:** Select **"Download Template"** to get the required Excel format.
3.  **Fill Data:** Input Name, Email, Mobile, Department, and Role in the Excel sheet.
4.  **Upload:** Select the completed file and click **"Upload"**. The system will auto-create the entities.

### 2.2 Setting Up Reporting Hierarchy
1.  **Edit User:** Click the **three dots (⋮)** next to a user’s name and select **"Edit"**.
2.  **Configure Reporting:** Locate the **"Reporting To"** field and select the supervisor.
3.  **Verify:** Navigate to **"Organization Chart"** to visualize and verify the structure.

---

## 3. Permissions Configuration

> 📍 **Navigation Path:** `Dashboard` → `Team and Collaboration` → `Roles and Permission`

1.  **Select Role:** Choose a role from the list.
2.  **Toggle Permissions:** Enable/Disable access for specific Shivik modules:
    *   *Modules:* Projects, Tasks, Users, Reports, DPR.
    *   *Actions:* Read, Write, Update, Delete.
3.  **Save:** Changes are saved automatically upon toggling.

---

## 4. User Onboarding

### 4.1 Sending Password Reset Notifications
*   **Individual:** Go to **Users**, click **(⋮)** next to a user, and select **"Notify"**.
*   **Bulk:** Select multiple users using checkboxes and click **"Notify Selected"**.

### 4.2 User Password Setup
1.  **Email Reception:** User receives an email with a secure setup link.
2.  **Creation:** User clicks the link and defines a new password.
3.  **Access:** User logs in via Web or the Shivik Mobile App using the new credentials.

---

## 5. Attendance Configuration

> 📍 **Navigation Path:** `Dashboard` → `Project Settings` → `Config` → `Attendance Configuration`

### Configuration Steps:
1.  **Geolocation:** Define work sites, geofencing radius, and GPS tolerance.
2.  **Shift Creation:** Set start/end times and break durations.
3.  **Shift Assignment:**
    *   Navigate to **"Shift Assignment"**.
    *   Select Users/Departments.
    *   Assign specific Shift and Site Location.
    *   Set Effective Dates.
4.  **Email Reports:** Configure automated PDF/Excel reports for managers (Daily/Weekly).

---

## 6. HR Management

> 📍 **Navigation Path:** `Dashboard` → `HR Management`

### 6.1 User Attendance Marking
*   **Actions:** Check-in/Check-out with Geolocation.
*   **History:** Users can view their own working hours and late arrivals.

### 6.2 HR Dashboard
*   **Overview:** Monitor team attendance rates and absenteeism.
*   **Analytics:** View graphical trends (Weekly/Monthly) by department.
*   **Reports:** Export detailed data for payroll processing.

---

## 7. Project Creation

> 📍 **Navigation Path:** `Dashboard` → `Projects` → `Create New Project`

1.  **Initiate:** Click the **"Projects"** module (bottom of sidebar), then **"Create New Project"**.
2.  **Details:**
    *   *Name:* e.g., "Skyline Towers Phase 1".
    *   *Type:* Select from dropdown.
    *   *Location:* City, State.
    *   *Logo:* Upload project branding (Max 800x400px).
3.  **Configure:** Go to **Project Settings → Config** to set Working Days and Calendars.

---

## 8. Project Planning

> 📍 **Navigation Path:** `Dashboard` → `Projects` → `[Select Project]` → `Planning`

### Planning Methods:
*   **Option 1: Import MPP:** Upload a Microsoft Project file to auto-populate tasks, dependencies, and resources.
*   **Option 2: Manual Creation:** Use the **"Add Task"** button to define tasks, dates, and hierarchy (indent/outdent).
*   **Option 3: AI Planning:** (Feature coming in future updates).

### Approval Configuration:
*   Navigate to **Project Settings → Approval Config**.
*   Set DPR Approval flow (Auto vs. Manual) and Escalation hierarchies.

---

## 9. Scheduling

> 📍 **Navigation Path:** `Dashboard` → `Projects` → `[Select Project]` → `Schedule`

1.  **Review Gantt Chart:** visual timeline of the project.
2.  **Validate:** Check dependencies, circular logic, and critical paths.
3.  **Baseline:** Click **"Create Baseline"** to save the initial schedule for future variance tracking.
4.  **Optimize:** Adjust durations and resolve resource conflicts.

---

## 10. Task Assignment

### 10.1 Assigning Tasks
*   **Via Schedule:** In the Gantt view, use the **"Resource Names"** column to select users.
*   **Via Task Details:** Open a task and use **"Add Team Member"**.

### 10.2 Management & Notifications
*   **View Assignments:** Go to **Project Management → Assignments** to filter by Team, Day, or Week.
*   **User Alerts:** Assigned users receive instant notifications regarding deliverables and timelines.
*   **Attendance:** Assignment prompts users to mark attendance at the specific site.

---

## 11. Daily Progress Reporting (DPR)

> 📱 **Platform:** Shivik Mobile Application

### 11.1 Mobile Workflow
1.  **Login:** Access the mobile app.
2.  **Navigate:** Go to the **"DPR"** tab.
3.  **Select Task:** Tap a task from your assigned list.
4.  **Update:**
    *   Upload Photos (Before/During/After).
    *   Add Notes & Quantity Measurements.
    *   Record Material Usage.
5.  **Submit:** Tap **"Submit DPR"**.

### 11.2 Approval Process (Web)
*   **Manager Role:** Review "Team Tasks" or "DPR Reviews".
*   **Actions:** Approve (Updates Schedule), Reject (Returns for Revision), or Request Clarification.

---

## 12. Real-Time Schedule Updates

*   **Automation:** Approved DPRs automatically update "Actual" dates and percentages in the Shivik Scheduler.
*   **Analysis:** System recalculates the Critical Path and highlights variances.
*   **Monitoring:** Live dashboards reflect immediate project status changes.

---

## 13. Task Insights (Web)

> 📍 **Navigation Path:** `Schedule` → `Right-click Task` → `Details`

*   **Timeline:** View complete DPR history and photo logs.
*   **AI Analysis:** (If enabled) Automated quality and progress assessment of uploaded photos.
*   **Resources:** Access technical drawings, specs, and quality standards attached to the task.

---

## 14. Issue Management

> 📍 **Navigation Path:** `Dashboard` → `Projects` → `[Select Project]` → `Issues`

1.  **Raise Issue:** Click **"Raise Issue"**. Define Title, Priority, Affected Task, and Category.
2.  **Assign:** Select responsible user and due date.
3.  **Track:** Use comments and media attachments to document the resolution process.
4.  **Close:** Mark as "Resolved" with proof of completion.

---

## 15. Manager/Admin Controls

*   **Team Tasks:** Overview of all member workloads and status.
*   **DPR Management:** Bulk approval/rejection and timeline views.
*   **Communication:** Broadcast announcements or start task-specific discussions.
*   **Documents:** Centralized repository for project specifications and drawings.

---

## 16. Resource Management

> 📍 **Navigation Path:** `Dashboard` → `Operations and Logistics` → `Resource Management`

### 16.1 Resource Setup
1.  **Categories:** Create groups (e.g., Equipment, Materials).
2.  **Inventory:** Add individual resources with specific codes, costs, and specifications.

### 16.2 Tracking
*   **Attendance:** Mark equipment/resources as "Present" at specific sites.
*   **Utilization:** Track daily usage, efficiency, and maintenance logs.

---

## 17. Vendor Management

> 📍 **Navigation Path:** `Dashboard` → `Vendors`

1.  **Onboard:** Create profiles with contact details and specializations.
2.  **Assign:** Link vendors to specific project tasks or deliverables.
3.  **Evaluate:** Track completion rates, quality of work, and payment history.

---

## 18. Dashboard Overview

The Shivik landing page provides a high-level operational view:

*   **S-Curve Analysis:** Visual Planned vs. Actual progress.
*   **My Tasks:** Personal priority list.
*   **Team Performance:** Metrics on approvals and workload.
*   **Missing DPRs:** Alerts for non-compliance.
*   **Today's Targets:** Daily goals and achievement metrics.

---

## 19. Notifications & Alerts

### Automated Triggers
*   **Delays:** Critical path impacts and schedule slippage.
*   **Compliance:** Overdue DPRs and missing attendance.
*   **Urgent:** Safety issues or high-priority task updates.

### Channels
*   **Push:** Instant mobile alerts.
*   **Email:** Daily digests and critical summaries.
*   **In-App:** Dashboard banners and badge counters.

---

## Troubleshooting & Support

### Common Solutions
*   **Login Failures:** Verify credentials and internet connection.
*   **DPR Upload Errors:** Ensure photos are standard formats and check connectivity.
*   **Missing Notifications:** Check device permissions and app settings.

### Contact Information

| Department | Contact Email | Phone |
| :--- | :--- | :--- |
| **Technical Support** | hello@shivik.in | - |
| **Admin Inquiries** | admin@shivik.in | - |
| **Emergency Hotline** | - | +91 9266282435 |

---
*© 2026 Shivik Platform. All rights reserved.*
