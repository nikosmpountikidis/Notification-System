# Notification-System

This Jupyter Notebook automates the process of notifying clients when their bills are close to the expiration date.

## Features

- Imports client billing data from a Google Sheet.
- Processes and cleans the data to ensure accuracy.
- Identifies clients with bills nearing expiration.
- Generates and sends email notifications to these clients.
- Updates the status of sent notifications.

## Notebook Overview

### 1. Data Import & Preparation
- Load client billing data.
- Verify and adjust data types as needed.

### 2. Bill Analysis
- Identify unique clients and bill categories.
- Visualize the distribution of different bill types and client-specific bill counts.

### 3. Notification System
- Detect bills nearing expiration.
- Generate personalized email notifications for affected clients.
- Include information about other active bills in the notifications.

### 4. Status Update
- Mark clients whose notifications have been successfully sent.
