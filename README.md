# financial-data-analysis-project

SQL database design and data modeling project focused on relational database structure, entities, relationships, and business operations.

## Project Overview

This project combines relational database design with SQL-based exploratory analysis to investigate financial operations and identify opportunities to improve accounts receivable management and cash flow.

The project was developed around a consulting business and involved designing a relational database model and using the resulting data structure to analyze invoices, payments, customers, and cash flow.

## Project Objectives

- Design a relational database structure for a consulting organization
- Identify key business entities and their attributes
- Define primary and foreign key relationships
- Establish one-to-many and many-to-many relationships
- Use SQL-based analysis to investigate accounts receivable
- Identify overdue invoices and potential cash flow issues
- Develop data-driven recommendations for improving financial performance

## Database Design

The database model includes key business entities such as:

- Clients
- Consultants
- Projects
- Contracts
- Payments
- Invoices
- Time
- Locations
- Industries
- Project Status
- Payment Methods
- Specializations

The model establishes relationships between these entities to support both business operations and analytical reporting.

Examples of relationships include:

- Industry → Clients (1:M)
- Clients → Projects (1:M)
- Clients → Contracts (1:M)
- Projects ↔ Consultants (M:M)
- Projects → Time (1:M)
- Projects → Invoices (1:M)
- Invoices → Invoice Items (1:M)
- Invoices → Payments (1:M)

## SQL & Exploratory Data Analysis

The second part of the project focused on accounts receivable and cash flow.

SQL-based exploratory analysis was used to investigate overdue invoices and understand potential impacts on working capital.

### Key Finding

The analysis identified one currently overdue invoice:

**Harbor Retail 204 — $1,370**

This represented capital that was not immediately available to the organization.

The analysis also considered:

- Payment timing
- Client payment behavior
- Days to Collect (DSO)
- Percentage of invoices overdue
- Invoice aging
- Outstanding receivables

## Business Insight

Overdue invoices can restrict cash availability and potentially affect:

- Supplier payments
- Operating costs
- Funding for future projects
- Overall working capital

The analysis therefore focused on improving accounts receivable management rather than simply identifying individual overdue invoices.

## Recommended Solution

The project proposed a targeted **Accounts Receivable Optimization Program** focused on:

### Customer Management
- Automated payment reminders
- Early-payment incentives

### Invoice Process
- Flags for approaching due dates
- Partial upfront payments

### Payment Policies
- Encouraging faster payment methods
- Adjusting payment terms for higher-risk customers

## Expected Impact

The proposed approach aims to:

- Reduce overdue invoices
- Free working capital
- Improve project execution and budgeting
- Lower financial risk
- Reduce administrative effort
- Improve financial performance

## Skills Demonstrated

- SQL
- Relational Database Design
- Data Modeling
- Entity-Relationship Modeling
- Primary & Foreign Keys
- Database Relationships
- Exploratory Data Analysis
- Financial Data Analysis
- Accounts Receivable Analysis
- Business Analytics
- Data-Driven Decision Making

## Project Files

- [Financial Data Analysis Project](Financial%20Data%20Analysis%20Project.pdf)
- [Improving Cash Flow Presentation](Improving%20Cash%20Flow.pptx)
