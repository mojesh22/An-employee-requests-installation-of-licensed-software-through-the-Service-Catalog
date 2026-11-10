# ServiceNow Automated Software Installation and License Request Management System

## Project Overview

The **Software Installation Request Management System** is a ServiceNow-based automation project designed to simplify and streamline the process of requesting software installations and licenses within an organization.

In a typical organization, employees may need different software applications to perform their daily responsibilities. Managing these requests manually can involve several steps, including collecting software requirements, obtaining manager approval, assigning fulfillment tasks to the technical support team, tracking request progress, and communicating updates to employees.

This project addresses these challenges by implementing an automated software request and approval process using **ServiceNow Service Catalog and Flow Designer**.

## Project Objectives

- Provide employees with a centralized Service Catalog item to request software installations or licenses.
- Collect essential software request information, including software name, version, business reason, and urgency.
- Automate the manager approval process.
- Automatically create a Catalog Task after the request is approved.
- Assign fulfillment tasks to the Software Support Team.
- Track fulfillment progress through task status updates.
- Send automatic email notifications to requesters based on the fulfillment status.

## Key Features

### 1. Service Catalog
A dedicated catalog item named **Software Installation Request** allows employees to submit software and license requests through ServiceNow.

### 2. Request Information Collection
The request form captures:
- Software name
- Required software version
- Business reason for the request
- Urgency level

### 3. Automated Manager Approval
When an employee submits a request, the workflow sends it to the employee's manager for review and approval.

### 4. Automatic Catalog Task Creation
Once the manager approves the request, ServiceNow automatically creates a Catalog Task and assigns it to the **Software Support Team**.

### 5. Fulfillment Status Tracking
The workflow monitors the Catalog Task status and responds to the following outcomes:

- **Pending:** Sends an email notification informing the requester that the requested license is unavailable and that obtaining a new license may take approximately one week.
- **Closed Complete:** Sends an email notification informing the requester that the fulfillment process has been completed.

### 6. Automated Email Notifications
Email notifications keep the requester informed about the progress and outcome of their software request.

## Technologies Used

- ServiceNow Platform
- Service Catalog
- Flow Designer / Workflow Studio
- Requested Item (RITM)
- Catalog Task (SCTASK)
- Approval Management
- Automated Email Notifications

## Project Workflow

1. Employee opens the Software Installation Request catalog item.
2. Employee enters the required software details and submits the request.
3. ServiceNow generates a Requested Item (RITM).
4. The workflow sends the request to the employee's manager for approval.
5. After approval, a Catalog Task is automatically created.
6. The Catalog Task is assigned to the Software Support Team.
7. The workflow monitors the task status.
8. An email notification is sent based on the fulfillment outcome.

## Expected Benefits

- Reduces manual coordination in software request management.
- Establishes a structured manager approval process.
- Automates task creation and assignment.
- Improves communication between employees and the support team.
- Provides visibility into software request progress.
- Reduces repetitive administrative work through workflow automation.

## Conclusion

This project demonstrates how ServiceNow can be used to automate an organization's software installation and license request process. By combining Service Catalog, approval management, Catalog Tasks, Flow Designer, and email notifications, the solution provides a more organized, transparent, and efficient approach to handling software requests.

---

**Project Name:** Software Installation Request Management System  
**Platform:** ServiceNow  
**Primary Automation Tool:** Flow Designer  
**Project Type:** ServiceNow Workflow Automation
