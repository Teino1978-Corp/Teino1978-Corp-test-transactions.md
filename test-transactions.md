## DocTypes

```
Accounts - Account
Accounts - Accounts Settings
Accounts - Bank Reconciliation
Accounts - Budget Distribution
Accounts - C-Form
Accounts - Chart of Accounts
Accounts - Cost Center
Accounts - Fiscal Year
Accounts - GL Entry
Accounts - Journal Voucher
Accounts - Mode of Payment
Accounts - Payment to Invoice Matching Tool
Accounts - Period Closing Voucher
Accounts - POS Setting
Accounts - Pricing Rule
Accounts - Purchase Invoice
Accounts - Purchase Taxes and Charges Master
Accounts - Sales Invoice
Accounts - Sales Taxes and Charges Master
Accounts - Shipping Rule
Buying - Buying Settings
Buying - Purchase Common
Buying - Purchase Order
Buying - Quality Inspection
Buying - Supplier
Buying - Supplier Quotation
Contacts - Party Type
Core - Bulk Email
Core - Comment
Core - Communication
Core - Custom Field
Core - Custom Script
Core - Customize Form
Core - DocType
Core - Event
Core - File Data
Core - Letter Head
Core - Module Def
Core - Notification Count
Core - Outgoing Email Settings
Core - Page
Core - Patch Log
Core - Print Format
Core - Property Setter
Core - Report
Core - Role
Core - Scheduler Log
Core - Social Login Keys
Core - System Settings
Core - Tag
Core - ToDo
Core - User
Core - Version
Core - Workflow
Core - Workflow Action
Core - Workflow State
Home - Feed
HR - Appraisal
HR - Appraisal Template
HR - Attendance
HR - Branch
HR - Deduction Type
HR - Department
HR - Designation
HR - Earning Type
HR - Employee
HR - Employment Type
HR - Expense Claim
HR - Expense Claim Type
HR - Grade
HR - Holiday List
HR - HR Settings
HR - Job Applicant
HR - Job Opening
HR - Leave Allocation
HR - Leave Application
HR - Leave Block List
HR - Leave Control Panel
HR - Leave Type
HR - Salary Manager
HR - Salary Slip
HR - Salary Structure
HR - Upload Attendance
Manufacturing - BOM
Manufacturing - BOM Replace Tool
Manufacturing - Production Order
Manufacturing - Production Planning Tool
Manufacturing - Workstation
Projects - Activity Type
Projects - Project
Projects - Task
Projects - Time Log
Projects - Time Log Batch
Selling - Campaign
Selling - Customer
Selling - Industry Type
Selling - Installation Note
Selling - Lead
Selling - Opportunity
Selling - Quotation
Selling - Sales BOM
Selling - Sales Order
Selling - Selling Settings
Selling - SMS Center
Setup - Authorization Control
Setup - Authorization Rule
Setup - Backup Manager
Setup - Brand
Setup - Company
Setup - Contact Control
Setup - Country
Setup - Currency
Setup - Currency Exchange
Setup - Customer Group
Setup - Email Digest
Setup - Features Setup
Setup - Global Defaults
Setup - Item Group
Setup - Jobs Email Settings
Setup - Naming Series
Setup - Notification Control
Setup - Print Heading
Setup - Quotation Lost Reason
Setup - Sales Email Settings
Setup - Sales Partner
Setup - Sales Person
Setup - SMS Settings
Setup - Supplier Type
Setup - Terms and Conditions
Setup - Territory
Setup - UOM
Shopping Cart - Shopping Cart Settings
Stock - Batch
Stock - Bin
Stock - Delivery Note
Stock - Item
Stock - Item Price
Stock - Landed Cost Wizard
Stock - Material Request
Stock - Packing Slip
Stock - Price List
Stock - Purchase Receipt
Stock - Serial No
Stock - Stock Entry
Stock - Stock Ledger Entry
Stock - Stock Reconciliation
Stock - Stock Settings
Stock - Stock UOM Replace Utility
Stock - Warehouse
Support - Customer Issue
Support - Maintenance Schedule
Support - Maintenance Visit
Support - Newsletter
Support - Support Email Settings
Support - Support Ticket
Utilities - Address
Utilities - Contact
Utilities - Note
Utilities - Rename Tool
Utilities - SMS Control
Utilities - SMS Log
Website - About Us Settings
Website - Blog Category
Website - Blog Post
Website - Blog Settings
Website - Blogger
Website - Contact Us Settings
Website - Post
Website - Style Settings
Website - User Vote
Website - Web Page
Website - Website Group
Website - Website Route
Website - Website Route Permission
Website - Website Script
Website - Website Settings
Website - Website Slideshow
Website - Website Template
```

## Pages

```
Accounts Browser
activity
applications
data-import-tool
desktop
financial-analytics
messages
modules_setup
permission-manager
purchase-analytics
Sales Browser
sales-analytics
sales-funnel
setup-wizard
sitemap-browser
stock-ageing
stock-analytics
stock-balance
stock-ledger
stock-level
support-analytics
trial-balance
user-properties
```

## Test Workflow feature

## Transaction Sequences

```
lead/customer - opportunity/quotation - sales order - sales invoice and delivery note - payment
lead/customer - opportunity/quotation - sales order - sales invoice - delivery note - payment
lead/customer - opportunity/quotation - sales order - delivery note - sales invoice - payment
lead/customer - opportunity/quotation - sales order - pos sales invoice
customer - pos sales invoice
customer - invoice - delivery note
customer - delivery note - invoice
customer - sales order
customer - invoice without item codes - payment
customer - opportunity/quotation - sales order - payment - delivery note - sales invoice
customer - opportunity/quotation - sales order - payment - sales invoice - delivery note

supplier - supplier quotation - purchase order - purchase invoice - purchase receipt - payment
supplier - supplier quotation - purchase order - purchase receipt - purchase invoice - payment
supplier - supplier quotation - purchase order - purchase invoice and purchase receipt - payment
supplier - payment - invoice - receipt
supplier - payment - receipt - invoice
supplier - invoice
supplier - receipt
```

## Permissions

```
Check what restricted users can do. Create and use users with only these roles:

Support Team
Material User
Projects User
Employee
HR User
Purchase User
Sales User
Accounts User
```