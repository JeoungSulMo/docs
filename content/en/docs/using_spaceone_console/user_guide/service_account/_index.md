---
title: "Service Account"
linkTitle: "Service Account"
weight: 9
url_dash_board: "" 
date: 2021-06-10
description: >
    Credential information for each cloud providers.
---
# Service Account

## Overall

On the service account page, users can easily manage credentials for each service provider. Multi cloud resources are collected based on these credentials.

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_01.png)

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_02.png)


1. A list of **Service Providers**
2. Adding  **Service Account**
3. Deleting **Service Account** /Changing **Project**/Connecting to **Console**
4. **Details**, **Tag**/**Credentials** Management, **Member**

SpaceONE supports the following service providers:

* Alibaba Cloud
* AWS
* Azure
* Google 
* Hyper Billing
* Oracle Cloud
* SpaceONE

## Adding Service Account

Users can add a **Service Account** simply by selecting a service provider and clicking the **+ Add** button.

For the upcoming steps, we will focus on AWS\`s IAM.

To add a **Service Account**, users need to fill in the **Name** and **Account ID** fields first.

### Base Information

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_03.png)

* Name : Name of **Service Account**
* Account ID : Root Account ID \(12-digits\)
* Tags : Additional **Service Account**\`s tag

### Credentials

Two types of **Service Accounts** are available: aws\_access\_key, aws\_assume\_role\.

#### aws\_access\_key  

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_04.png)

* AWS Access Key \(Required\) : Access Key from IAM (Read Only policy is strongly recommended.)
* AWS Secret Key \(Required\) : Secret key from IAM

#### aws\_assume\_role

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_05.png)

* AWS Access Key \(Required\) : Access key from IAM to assume a role
* AWS Secret Key \(Required\) : Secret key from IAM to assume a role
* Role ARN \(Required\) : Role ARN of an assumed role from IAM

### Selecting Project

Select the project in which a **Service Account** will be placed. Collected resources from the **Service Account** will be included to the project automatically.

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_06.png)

* To create a **Project**, click the **+ Create Project** button.

* For a more detailed process on creating a project, refer to the link below.

<div class="my-4">
<a class="btn btn-secondary"
    href="/docs/guides/user_guide/project/project_group_management/"
    target="_blank"
    rel="noopener"
    >Project Group Management</a>
</div>

* Select a project you need, then click the **Save** button.

## Deleting Service Account/Changing Project 

Users can delete a **Service Account** or change a **Project** linked to a certain **Service Account**.

Select the target **Service Account**, then click **Action &gt; Delete/Change Project**.

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_07.png)

### Deleting Service Account

Enter the name of the **Service Account** you want to delete, then click the **Confirm** button.

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_08.png)

### Changing Project

Select the project you want to newly link a **Service Account**, then click the **Confirm** button.

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_09.png)

## Link to AWS Console

Select the target **Service Account**, then click **Action &gt; Connect to Console**.

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_10.png)

To access AWS console, users must be logged into AWS console in advance. \(AWS Console SSO is not available.\)

## Status Tab

Using the **Status** tab, users can browse details of a **Service Account**.

### Details 

Users can see detailed information of a **Service Account** on the **Details** tab. 

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_11.png)

### Tag

By clicking the **Edit** button, **Tags** for a **Service Account** can be added or deleted.

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_12.png)

Afer clicking the **+ Add Tags** button, fill in the **Key** and **Value** fields, then click the **Save** button. 

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_13.png)

### Credentials

**Credentials** that contain key information can be added or deleted.

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_14.png)

### Member

On the **Member** tab, users can see who is participating in the project.

![](/docs/using_spaceone_console/user_guide/service_account/service_account_img/service_account_img_15.png)