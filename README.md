# Cloud Provisioning & Microsoft Entra ID P2 Licensing

## Project Overview

In this lab, I practiced assigning a Microsoft Entra ID P2 license to a cloud-based user account.

Building on my previous user provisioning lab, I used the Microsoft 365 admin center to review available licenses, select a user for licensing, complete the assignment, and verify that the P2 license was active on the user's account.

## Technologies Used

- Microsoft Entra ID
- Microsoft 365 Admin Center
- Microsoft Azure
- Identity and Access Management (IAM)

## What I Practiced

- Reviewing available Microsoft Entra ID P2 licenses
- Identifying current license assignments
- Selecting a user for license assignment
- Assigning a P2 license to a cloud user
- Confirming that the license assignment was successful
- Verifying the license status directly on the user's account

## Step 1: Review Available P2 Licenses

I navigated to the licensing section of the **Microsoft 365 admin center** and reviewed the available Microsoft Entra ID P2 licenses.

At the beginning of the lab, **3 of 25 licenses were assigned**, leaving 22 licenses available.

![P2 License Overview](images/01-p2-license-overview.png)

## Step 2: Review Current License Assignments

I opened the Microsoft Entra ID P2 subscription to review the users who already had licenses assigned.

This also gave me access to the **Assign licenses** option for adding another user.

![Current P2 License Assignments](images/02-current-p2-license-assignments.png)

## Step 3: Select a User for Licensing

I selected **Taylor Morgan**, the test user I created in my previous Microsoft Entra ID lab, as the user who would receive the P2 license.

Before completing the assignment, I verified that the correct user and subscription were selected.

![Select User for P2 License](images/03-select-user-for-p2-license.png)

## Step 4: Confirm the License Assignment

After assigning the license, I returned to the P2 licensing page and confirmed that the number of assigned licenses increased from **3/25 to 4/25**.

Taylor Morgan also appeared in the list of licensed users.

![P2 License Assignment Confirmed](images/04-p2-license-assignment-confirmed.png)

## Step 5: Verify the License on the User Account

For final verification, I opened Taylor Morgan's licensing information in Microsoft Entra ID.

The account showed:

- **Product:** Microsoft Entra ID P2
- **State:** Active
- **Enabled Services:** 4/4
- **Assignment Path:** Direct

This confirmed that the P2 license was successfully assigned directly to the user.

![P2 License Verified on User](images/05-p2-license-verified-on-user.png)

## Skills Practiced

- Microsoft Entra ID
- Microsoft 365 Admin Center
- Identity and Access Management
- User Licensing
- License Assignment
- Cloud User Administration
- Account Verification
- Technical Documentation

## What I Learned

This lab helped me understand how licensing connects to user administration in a Microsoft cloud environment.

I practiced reviewing available licenses, assigning a license to a specific user, and verifying that the assignment was active and applied directly to the account.

Connecting this lab to my previous user provisioning project also helped me better understand the process of creating a cloud identity and then providing that user with the appropriate services and access.
