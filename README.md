# AI Tool Governance & Access Management

## Overview

This portfolio project simulates how a technology operations team could manage enterprise AI tools across an organization. It focuses on four operational areas: tool inventory, access management, use-case tracking, and adoption/utilization reporting.

The project was designed to demonstrate practical skills related to technology operations, identity and access management (IAM), AI governance, data quality, spreadsheet analysis, process documentation, and operational reporting.

## Business Scenario

An organization is using multiple AI tools across engineering, sales, marketing, customer success, and operations. As adoption grows, the company needs a structured way to answer questions such as:

- Which AI tools are currently in use?
- Who owns each tool?
- How many licenses are being paid for and how many are actually being used?
- What business purpose does each tool support?
- How are employee access requests approved and provisioned?
- Which tools are underutilized?
- When should user access be reviewed or removed?

This workbook creates a lightweight governance model to address those questions.

## Workbook Structure

### 1. AI Tool Inventory

Tracks the organization's AI tools and key governance information, including tool and vendor, department, business and technical owners, total licenses, active users, monthly licensing cost, approval status, data risk, primary business use case, last review date, and utilization rate.

The utilization rate is calculated as:

`Active Users / Total Licenses`

This helps identify tools with unused capacity or low adoption.

### 2. Access Requests

Models an access-management workflow for employees requesting AI tools. The worksheet tracks request ID, employee and department, requested tool, request date, manager approval, security review, license availability, provisioning status, provisioned date, and access review date.

This represents a basic identity lifecycle process from request through approval, provisioning, review, and eventual deprovisioning.

### 3. Use Case Index

Documents why each AI tool is being used by the organization, including the business need, expected benefit, adoption level, and status. This helps connect technology spending to actual business needs.

### 4. Dashboard

Summarizes the operational health of the AI-tool environment using KPIs and charts, including total AI tools, approved tools, total licenses, active users, overall utilization, pending access requests, underutilized tools, and monthly licensing cost.

### 5. Access Lifecycle

Documents the full access-management process:

`Request → Manager Approval → Security Review → License Check → Provisioning → Adoption/Usage → Access Review → Deprovisioning`

The workflow includes governance principles such as least privilege, periodic access reviews, and license recovery.

## Skills Demonstrated

- Technology operations
- AI tool governance
- Identity and access management concepts
- Access request workflows
- User provisioning and deprovisioning concepts
- Least-privilege access
- License utilization analysis
- KPI development
- Microsoft Excel
- Dashboard creation
- Data organization and quality
- Process documentation
- Operational reporting
- Business and technical communication

## Key Takeaways

This project demonstrates how structured operational processes can help an organization manage a growing portfolio of AI tools. By combining inventory management, access controls, use-case documentation, utilization metrics, and periodic reviews, technology teams can improve visibility, control costs, reduce unnecessary access, and support responsible AI adoption.

## Files

- `AI_Tool_Governance_Access_Management_Project.xlsx` — complete project workbook

## Project Status

Version 1.0 — Portfolio project with simulated enterprise data for demonstration purposes.

## Author

Edward Johnson  
Cybersecurity Technology Student  
GitHub: [trustz3ro](https://github.com/trustz3ro)
