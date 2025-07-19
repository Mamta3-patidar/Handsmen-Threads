HandsMen Threads Salesforce DX Project///
Welcome to the HandsMen Threads Salesforce DX project! This repository contains all metadata and automation for managing customers, orders, products, inventory, and marketing campaigns in Salesforce.

Overview
This project provides a custom Salesforce solution for:

Customers: Manage customer records, loyalty status, and contact details.

Orders: Track orders, statuses, and enforce business rules on quantities and amounts.

Products: Maintain product catalog, pricing, and stock levels.

Inventory: Monitor inventory per product and warehouse, with automated restocking and alerts.

Marketing Campaigns: Associate campaigns with customers and track campaign dates.
Key Features

Validation Rules: Ensure data quality for emails, amounts, and stock quantities.
Automation:
Flows:
Loyalty status auto-update based on purchases.
Order confirmation email alerts.
Low stock email alerts.
Apex Classes:
Batch job for inventory restocking.
Order trigger handler for quantity validation.
Profiles & Permissions: Admin profile with full access to all custom objects and fields.
Getting Started
Clone this repository and open in VS Code.
Authorize your Salesforce org:
sfdx auth:web:login -a <your-org-alias>
Create a scratch org:
sfdx force:org:create -f config/project-scratch-def.json -a handsmen-scratch
Push source to the org:
sfdx force:source:push -u handsmen-scratch
Assign the Admin profile to your user if needed.
Deployment
Deploy changes using Salesforce DX commands or CI/CD pipelines.
See Salesforce DX Project Configuration for details on sfdx-project.json.
Documentation & Resources
Salesforce Extensions for VS Code
Salesforce CLI Setup Guide
Salesforce DX Developer Guide
Salesforce CLI Command Reference
For questions or contributions, please open an issue or submit a pull request.

Products: Maintain product catalog, pricing, and stock levels.
Inventory: Monitor inventory per product and warehouse, with automated restocking and alerts.
Marketing Campaigns: Associate campaigns with customers and track campaign dates.
Key Features
Validation Rules: Ensure data quality for emails, amounts, and stock quantities.
Automation:
Flows:
Loyalty status auto-update based on purchases.
Order confirmation email alerts.
Low stock email alerts.
Apex Classes:
Batch job for inventory restocking.
Order trigger handler for quantity validation.
Profiles & Permissions: Admin profile with full access to all custom objects and fields.
Getting Started
Clone this repository and open in VS Code.
Authorize your Salesforce org:
sfdx auth:web:login -a <your-org-alias>
Create a scratch org:
sfdx force:org:create -f config/project-scratch-def.json -a handsmen-scratch
Push source to the org:
sfdx force:source:push -u handsmen-scratch
Assign the Admin profile to your user if needed.
Deployment
Deploy changes using Salesforce DX commands or CI/CD pipelines.
See Salesforce DX Project Configuration for details on sfdx-project.json.
Documentation & Resources
Salesforce Extensions for VS Code
Salesforce CLI Setup Guide
Salesforce DX Developer Guide
Salesforce CLI Command Reference
For questions or contributions, please open an issue or submit# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

How Do You Plan to Deploy Your Changes?
Do you want to deploy a set of changes, or create a self-contained application? Choose a development model.

Configure Your Salesforce DX Project
The sfdx-project.json file contains useful configuration information for your project. See Salesforce DX Project Configuration in the Salesforce DX Developer Guide for details about this file.

Read All About It
Salesforce Extensions Documentation
Salesforce CLI Setup Guide
Salesforce DX Developer Guide
Salesforce CLI Command Reference
