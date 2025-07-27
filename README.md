
# 🚗 WhatNext Vision Motors – Salesforce CRM Automation Project

📘 Project Overview

WhatsNext Vision Motors is a visionary automotive brand focused on delivering innovation, customer satisfaction, and digital excellence. This Salesforce CRM project was built to modernize and automate critical business operations such as vehicle ordering, stock validation, dealer assignment, and customer engagement.

The project leverages Salesforce’s declarative and programmatic tools (Flows, Apex, Batch Apex) to streamline vehicle sales, reduce manual intervention, and provide real-time insights to management through reports and dashboards.


🎯 Objectives

- Prevent customers from placing orders for vehicles that are out of stock.
- Automatically assign the nearest authorized dealer based on customer location.
- Schedule and send reminder emails for test drives.
- Maintain real-time stock levels and automatically confirm pending orders when inventory is updated.
- Empower staff and leadership with real-time reporting and dashboards.


🧱 Tech Stack

| Technology            | Purpose                                                  |
|-----------------------|----------------------------------------------------------|
| Salesforce CRM        | Core platform for building data models and UI           |
| Lightning App Builder | Create unified app navigation with custom tabs           |
| Flow Builder          | Automate dealer assignment and test drive reminders      |
| Apex (Trigger & Class)| Enforce stock validation and order update logic          |
| Batch Apex            | Process large volumes of pending orders automatically    |
| Scheduled Apex        | Run nightly jobs to confirm orders and deduct stock      |
| SOQL                  | Query Salesforce objects in Apex                         |
| Email Alerts          | Send automated test drive reminders to customers         |
| Reports & Dashboards  | Track stock, dealer performance, and customer activity   |


⚙️ Key Features

- Auto-Assign Nearest Dealer: Automatically assigns a dealer to an order based on customer address using Flows.
- Stock Validation Trigger: Prevents order placement if the selected vehicle is out of stock.
- Real-Time Stock Deduction: Confirms orders and deducts stock through Apex Triggers.
- Batch Job for Order Fulfillment: Confirms pending orders overnight if stock becomes available.
- Scheduled Test Drive Reminders: Sends emails 1 day prior to the scheduled test drive.
- Custom App: A Lightning App with intuitive navigation for admin and staff.
- Reports & Dashboards: Real-time visualizations of sales, inventory, and customer activities.

✅ Results

- 🔄 100% automated dealer assignment and test drive workflows  
- 📉 70% reduction in manual errors during order placement  
- 📬 Improved customer communication with automated emails  
- 📊 Centralized analytics via dashboards  
- ⏱️ Increased operational efficiency and staff productivity


## 📁 Folder Structure

```plaintext
📌 Folder Structure: WhatNext Vision Motors/
├── Data Management-Objects/
├── Data Management-Tabs/
├── Data Management-App Manager/
├── Data Management-Fields/
│   ├── Vehicle/
│   ├── Vehicle_Order/
│   ├── Vehicle_Customer/
│   ├── Vehicle_Dealer/
│   ├── Vehicle_Test_Drive/
│   └── Vehicle_Service_Request/
├── Automation/
│   ├── Auto_Assign_Dealer_flow/
│   └── Test_Drive_Reminder_flow/
├── Apex and Batch Class/
│   ├── VehicleOrderTriggerHandler.apxc
│   ├── VehicleOrderTrigger.apxt
│   ├── VehicleOrderBatch.apxc
│   └── VehicleOrderBatchScheduler.apxc

```

