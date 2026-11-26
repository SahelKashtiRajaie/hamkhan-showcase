# Hamkhan Integrated Management & Operations System
## Detailed Project Documentation

## 1. Introduction

Hamkhan is an integrated web-based operational management system designed to centralize and automate the organization's educational, administrative, marketing, sales, and internal coordination processes.

The platform was developed as one unified application using Google Apps Script, Google Sheets, HTML, CSS, and JavaScript. It integrates with Google Workspace services, Telegram, the Hamkhan website, and AI-assisted workflows.

The main objective is to replace fragmented operational processes with connected workflows, structured information, automated communication, and management dashboards.

---

## 2. System Modules

### 2.1. Centralized Access Hub

This module provides a centralized directory of organizational links and resources.

Each resource can include:
- Title and URL
- Resource type, such as Google Sheets, Google Docs, Google Drive, web applications, websites, and social media platforms
- Organizational category or team function
- Authorized users
- Review frequency
- Active or inactive status
- Display order
- Importance indicator
- Description and access instructions

Users can search, add, edit, and archive resources.

**Operational value:** Reduces scattered links, simplifies access to organizational resources, and clarifies where and how each tool should be used.

### 2.2. Instructor Registration and Profiles

Instructors can register through a dedicated form and submit their professional information, including a profile photo.

Their information is stored as a reusable profile. Once registered, instructors can submit new course or event proposals without repeatedly entering their personal details.

**Operational value:** Creates a standardized instructor database and reduces repetitive administrative work.

### 2.3. Course and Event Brief Submission

Instructors can submit structured briefs for proposed courses and events.

The submission process includes:
- Course or event information
- Relevant descriptions and details
- Venue selection from an existing database
- The ability to introduce a new venue
- Submission of corrections or updates

After submission, the system sends a Telegram notification containing a brief summary and a relevant hashtag.

**Operational value:** Standardizes proposal collection, improves information completeness, and creates a traceable submission process.

### 2.4. Educational Program Calendar

The system includes a Jalali calendar for monitoring courses and their individual sessions.

Calendar capabilities include:
- Color-coded course genres
- Course and event names
- Event type identification
- Session numbering, such as session 2 of 8
- Individual session time slots
- Search by course name
- Filtering between courses and Gap-o-Danje events
- Calendar synchronization and refresh

The calendar highlights the third-to-last and final sessions of each course. These milestones help the team begin renewal and instructor coordination before a course ends.

When a session is canceled, it is displayed with strikethrough formatting, and a replacement session is appended to the end of the course schedule.

**Operational value:** Improves schedule visibility, supports session-level monitoring, and enables proactive course renewal planning.

### 2.5. Sequential Brief Review

This module consolidates submitted instructor briefs into a sequential view.

It enables the team to review proposals in one place, compare submissions, and plan upcoming educational programs.

**Operational value:** Reduces the need to review proposals across multiple disconnected records.

### 2.6. Final Course Information and Publication

After a course is approved, staff can complete and manage its final publication information.

Available fields include:
- Final course information
- Poster
- Website description
- Website page link
- Telegram group link
- Website registration link

Posters are automatically stored in a dedicated Google Drive folder.

When required, the system can generate a Google Meet link for online sessions.

Important updates to publication information can also be announced through Telegram.

**Operational value:** Centralizes publication preparation and keeps promotional assets and registration links organized.

### 2.7. Session Operations and Reporting

The system supports operational reporting for every scheduled session.

Staff can:
- Mark a session as completed or canceled
- Record cancellation reasons
- Enter session reports
- Document challenges and operational issues
- Upload visual or video reports

Reports and media can be shared through Telegram with relevant hashtags.

The system also includes AI-assisted report editing. A draft can be generated and reviewed by the user, who can approve it, cancel it, or request changes before publication.

When a report is edited, the update is communicated with an edit-related hashtag.

Updates to finalized course information, including posters and website or registration links, can also be announced.

**Operational value:** Creates a structured record of educational activities, improves reporting consistency, and supports operational transparency.

### 2.8. Social Media and Content Management

The content management module supports planning and monitoring content across:
- Telegram
- Instagram
- LinkedIn

Each content item can include:
- Platform
- Format
- Topic
- Objective
- Additional details
- Planned publication date

Platform-specific properties are also supported, including Telegram pin status and Instagram Highlight status. Instagram content formats can include Stories, Reels, and other formats.

Content is displayed in a Jalali calendar with distinct visual indicators for each platform. Public holidays and relevant occasions are also displayed.

After publication, users can enter performance statistics.

The analytics dashboard supports:
- Date and month filtering
- Number of content items produced
- Top-performing content
- Current-month and previous-month comparisons
- View statistics
- Telegram hashtag frequency and performance
- Custom filtering

**Operational value:** Connects content planning with performance analysis and supports data-informed social media decisions.

### 2.9. Course Analytics Dashboard

The course dashboard provides an overview of educational operations.

It includes:
- Total course count
- New, scheduled, completed, and canceled courses
- Analysis by genre and format
- Book-based versus article-based courses
- Planned versus canceled sessions
- Paid versus free programs
- Course versus Gap-o-Danje distribution

Detailed records include session information, instructor-level completed and canceled session counts, operational challenges, and cancellation records.

**Operational value:** Provides management with a consolidated view of program performance and operational status.

### 2.10. CRM and Lead Management

The CRM module manages prospective participants and their follow-up processes.

The workflow is as follows:

1. A team member registers a new lead.
2. The lead enters the management panel.
3. A manager assigns the lead to a team member.
4. The assigned team member follows up and updates the lead's status.
5. The system records the lead's progress and outcome.

The individual dashboard displays assigned leads and their follow-up statuses, including progress, registration, and cancellation.

The management dashboard provides aggregated information about:
- Conversion to registration
- Cancellations
- Follow-up activities
- Lead status and history
- Individual team member performance

Managers can also assign follow-up tasks to team members.

Telegram notifications are sent for new leads and newly assigned tasks.

**Operational value:** Improves lead accountability, reduces missed follow-ups, and makes conversion performance measurable.

### 2.11. Financial and Sales Management

The financial dashboard provides revenue and registration information by course and instructor.

It includes course names, registration counts, and purchased subscription types.

A separate dashboard tracks overall sales team performance.

The system also supports manual participant registration when a participant cannot complete registration through the website.

In this workflow:
1. A Hamyar team member enters participant information.
2. The relevant course and subscription type are selected.
3. The payment receipt is uploaded.
4. The receipt is automatically stored in a dedicated Google Drive folder.
5. The registration is recorded in the CRM.

**Operational value:** Consolidates online and manual sales records and reduces gaps in financial and registration reporting.

### 2.12. Attendance and Participant Management

Hamyar team members can select a course and record attendance for each participant.

The attendance interface also provides:
- Participant notes
- Access to previous notes
- Purchased subscription type
- Remaining subscription capacity
- Refund status and refund-related actions

**Operational value:** Connects attendance records with participant history and subscription information.

### 2.13. Internal Meetings and Task Management

The system includes a separate calendar for internal meetings, work sessions, and tasks.

Meeting creation supports:
- Meeting type
- Recurrence settings
- Participants
- Participant email addresses
- Automatic Google Meet link generation
- Automatic calendar invitations when participant emails are provided

Meeting minutes can be recorded and processed with AI assistance.

The AI-assisted workflow helps organize meeting minutes into:
- Suggestions
- Decisions
- Action items and tasks

Users can review and edit the generated output before saving it.

When saved:
- Extracted tasks are transferred to the task management section.
- The complete meeting minutes and extracted items are stored.
- Meeting minutes are communicated through Telegram.

Tasks support:
- Owner
- Deadline
- Description
- Priority
- Status
- Subtasks with their own properties

Tasks and subtasks are also displayed in the calendar.

A dashboard provides analysis of meeting-derived action items and task progress.

**Operational value:** Converts meeting discussions into assigned, time-bound actions and connects decision-making with execution.

### 2.14. Telegram Automation and Daily Report

Telegram acts as an operational notification channel across the platform.

Notifications can cover:
- New instructor submissions
- Brief updates
- Final course information
- Session cancellations
- Session reports and challenges
- Uploaded media
- Report edits
- New leads
- Assigned tasks
- Meeting minutes

Hashtags distinguish notification categories.

The Daily Report provides a daily operational overview, including:
- Meetings scheduled for the day
- Sales for each course
- Registration channel, including website, bot, and manual registration
- Registration type, including single-session, all-session, and monthly subscriptions
- Courses currently open for registration

The system also reads website-related emails and extracts registration information and links for reporting.

**Operational value:** Reduces the need to manually inspect multiple panels and communication channels to understand daily operations.

---

## 3. Technology and Integrations

| Technology | Role |
|---|---|
| Google Apps Script | Application backend and workflow automation |
| Google Sheets | Structured data management |
| HTML, CSS, JavaScript | User interface and client-side functionality |
| Google Drive | File and poster storage |
| Google Meet | Online meeting integration |
| Telegram Bot API | Operational notifications and reporting |
| Hamkhan Website | Website and registration integration |
| AI Services | Report editing and meeting-minutes processing |

---

## 4. Overall Architecture

Hamkhan is one unified web application rather than a collection of unrelated applications.

Its modules share data and workflows to connect educational operations, content management, CRM, sales, attendance, meetings, and reporting.

The application combines:
- Centralized operational interfaces
- Structured data storage
- Automated workflows
- File management
- External service integrations
- Analytics and reporting

---

## 5. Business and Operational Impact

The platform is designed to improve organizational operations through:

- Centralized access to internal resources
- Standardized data collection
- Reduced repetitive administrative tasks
- Improved scheduling and session tracking
- More consistent reporting
- Better lead follow-up accountability
- Consolidated sales and attendance information
- Structured meeting-to-task workflows
- Automated communication
- More accessible operational analytics

---

## 6. Project Scope and Documentation Note

This repository is intended as a portfolio showcase and documentation resource.

It describes the system's modules, workflows, integrations, and operational objectives. It does not contain the production source code or confidential organizational data.

Screenshots and a demonstration video may be added separately to illustrate the application interface and workflows.

*Documentation describes the implemented system based on its project requirements and operational design. Availability of individual features may depend on the deployed configuration and connected services.*
