## n8n Customer Messaging Workflow
### Overview

This workflow is built in n8n. It runs on a schedule, fetches customer data from the datastore, edits fields, and then sends the data to the messenger.

### Steps

- Schedule Trigger → Workflow start hota hai.
- Customer Datastore → Sare customer records fetch karta hai.
- Edit Fields → Data ko modify karta hai.
- Customer Messenger → Final message bhejta hai.

### Import Workflow

To use this workflow:

- Open n8n → Create New Workflow
- Copy the contents of n8n project 2_safe.json
- In n8n, click on Paste JSON and paste the code
- Save & activate the workflow.

<img width="1920" height="954" alt="image" src="https://github.com/user-attachments/assets/bde8ec00-8afc-4697-9438-ad5ecaaaeb8c" />
