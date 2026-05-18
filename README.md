# Power Automate Invoice Data Extraction Lab
### [YouTube Demonstration]https://youtu.be/A_TgANeEj3o
## Project Overview

This lab demonstrates how to use Microsoft Power Automate and Azure AI Document Intelligence to automate invoice processing.

The goal of this project is to simulate a real-world RPA-style business workflow where invoices are uploaded to a cloud folder, key invoice fields are extracted automatically, and the results are stored in a structured format for tracking and reporting.

This lab shows how workflow automation, cloud storage, and AI-powered document processing can reduce manual data entry and improve business efficiency.

## Technologies Used

- Microsoft Power Automate
- Azure AI Document Intelligence
- Azure Storage Account
- Azure Table Storage
- OneDrive or SharePoint
- PDF invoices
- Microsoft Outlook
- Microsoft Azure Portal

## Skills Demonstrated

- Robotic Process Automation workflow design
- Cloud-based document processing
- AI-powered invoice data extraction
- Azure resource deployment
- Structured data storage
- Power Automate cloud flows
- File-based automation triggers
- Business process automation
- Error reduction through automation
- Basic cloud administration

## Business Use Case

Many companies receive invoices through email, OneDrive, SharePoint, or internal upload systems. Manually opening each invoice, reading the invoice number, vendor name, invoice date, and total amount takes time and creates room for human error.

This lab automates that process.

When a new invoice PDF is uploaded to a monitored folder, Power Automate starts a flow. The flow sends the invoice to Azure AI Document Intelligence, extracts important invoice fields, stores the data in Azure Table Storage, and sends a confirmation email.

This creates a repeatable workflow that could be used by accounting, finance, operations, or IT teams.

## Lab Objectives

- Create sample invoice PDFs
- Upload invoices to a OneDrive or SharePoint folder
- Create an Azure AI Document Intelligence resource
- Use the prebuilt invoice model to extract invoice data
- Build a Power Automate flow that triggers when a new file is uploaded
- Store extracted invoice data in Azure Table Storage
- Send an email notification after processing
- Test the full automation from upload to data storage
