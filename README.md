# help-desk-ticket-system


# Ticket System

## Overview
In this project, I deployed a Windows Server and used a Virtual Machine to access the server remotely. The server has users with unique passwords. These users are able to email a custom address directly to Zoho to submit help desk tickets. This repository outlines the system components.

## Architecture
Azure VM → Windows Server → Browser → Zoho Desk

## Windows Server Setup
VM Specs

## Zoho Desk Integration
Email-to-ticket
  User emails companyname@zoho.com
  Ticket enters the queue
  Admin assigns ticket to agent
  Agent resolves or escalates ticket and sends an update
  
## User Flow
During onboarding, admin sends user a zendesk invite
User accepts invite and creates a profile
  
## Security Considerations

## How to Reproduce

