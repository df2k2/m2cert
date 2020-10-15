# Exam Objectives and Scope

[Table of Contents](./) | [Next Section](./1.md)

-----

Adobe AD0-E706 Adobe Certified Expert-Magento Commerce Cloud Developer ADOBE CERTIFIED EXPERT
Photo
Introduction

This exam is for a Magento 2 developer/architect with 6 to 12 months of experience developing for Magento Commerce Cloud. Ideally the person taking this exam will have worked on at least two Magento Commerce Cloud implementations.

This exam will validate the skills and knowledge needed required to deploy, test, troubleshoot, and operate in the Magento Cloud environment, including how to leverage Cloud platform features to enhance your project operations and performance. The exam will also validate the skills on troubleshooting and integrations.

By passing this exam, the test taker will receive the Adobe Certified Expert-Magento Commerce Cloud Developer certification

Adobe certification exams are developed with the participation of subject matter experts worldwide, following industry standards in developing fair and valid tests. Visit our FAQ page for more information.
Photo

Are you an Adobe partner?

An official Adobe Certified Expert designation acknowledges your established expertise to help current and future business clients succeed!

Partners receive a 33% discount on all certification exam pricing. Email spphelp@adobe.com to request your discount(s).

Where to start? Check out the Partner Learner Journey from the Adobe Solution Partner Program today.
Photo
Exam Guide Sections:

#### **Exam information**

#### **Minimum candidate experience**

#### **Exam objectives and scope**

#### **Online sample test**

#### **Preparing for the exam**


Exam Information

#### **Exam number: AD0-E706**

#### **Exam name: Adobe Certified Expert-Magento Commerce Cloud Developer**

#### **Certificate level: Certified Expert**

#### **Status: Active**

#### **Available languages: English**

#### **Number of questions: 60**

#### **Formats: Multiple choice**

#### **Duration: 120 minutes**

#### **Delivery: Onsite/Online proctored (requires camera access) or test center proctored**

#### **Passing mark: 62%**

#### **Price: $295 USD**


Schedule your Exam
Minimum Candidate Experience

This exam is for a developer/architect with 6 to 12 months of experience developing for Magento Commerce Cloud. Ideally the person taking this exam will have worked on at least two Magento Commerce Cloud implementations.
Exam Objectives and Scope
## [Section 1: Commerce Cloud Fundamentals (13%)](./1.md)

### **1.1**  Describe the features and functions of Magento Commerce Cloud

#### **What is Magento Cloud?**

#### **Cloud platform overview and features**

### **1.2**  Determine how to locate settings with Cloud Admin UI

#### **Locate project settings, user management, and project variables pages**

#### **Locate environments, access links, and logs**

#### **Locate environment settings**

### **1.3**  Demonstrate the ability to manage users

#### **Add SSH key**

#### **Add users to a project and manage their roles**

### **1.4**  Determine the difference between Magento Cloud plans

#### **Starter plan vs. Pro differences**

### **1.5**  Determine how different environment types operate

#### **Determine differences in environment types: Integration, staging, production**


## [Section 2: Local Environment (9%)](./2.md)

### **2.1**  Demonstrate ability to set up local development

#### **Software you need to have locally for developing a Magento Cloud project**

### **2.2**  Given a scenario, demonstrate ability to use the Magento-cloud CLI tool

#### **Install Magento-cloud CLI. Retrieve project info**

#### **Manage project and environments**

#### **Connect to database and SSH**

#### **Build the project locally**


## [Section 3: Cloud Configuration (13%)](./3.md)

### **3.1**  Determine how to configure Cloud

#### **How to configure different redirects in this file, which types of redirects should not be configured here**

#### **How to add these configurations to Staging or Production environments. Magento On-Premises installation migration**

#### **How to migrate an existing Magento installation into Magento Cloud: Code base, database, media migration**

### **3.2**  Determine how to configure a planned service

#### **How to configure a service that is planned to be added to the environment**

### **3.3**  Demonstrate ability to add to your environment

#### **Which configurations you can add to your environment and how to do it**

#### **What to configure in this file, on which environments these configurations are applied, how to add these configurations to environments where this file is not read**


## [Section 4: Service Configuration (5%)](./4.md)

### **4.1**  Demonstrate ability to create service configurations

#### **How to add system services: MySQL, Redis, Elasticsearch, RabbitMQ**

### **4.2**  Demonstrate ability to use Slave connections

#### **How to leverage slave connections to MySQL, Redis**


## [Section 5: Deployment Process (10%)](./5.md)

### **5.1**  Determine the processes during deployment

#### **Describe all processes that are running during deployment: Build, deploy and post-deploy phases. Explain why downtime occurs on your project**

#### **What role every process/phase plays and how to impact every process**

#### **How Magento Cloud deploys Magento. What every script does on every deployment phase**

#### **How to extend these scripts and best practices for doing so**

#### **Describe the ways to retrieve logs for phases and its scripts**

### **5.2**  Demonstrate the ability to create Magento Cloud script configurations

#### **Which configurations you can set in .magento.env.yaml, and Cloud environment configurations that are not described in the units about SCD and service configurations**


## [Section 6: Static Content Deployment (10%)](./6.md)

### **6.1**  Demonstrate ability to move SCD to build phase

#### **Describe the default process of generating SCD and how it impacts downtime**

#### **Describe the reason for moving generation static content to the build phase. Consider the way to do this and show the result (timeline)**

#### **Determine additional configuration that helps decrease deployment time (SKIP_HTML_MINIFICATION)**

#### **Display time measurements**

### **6.2**  Demonstrate ability to avoid SCD on both phases

#### **What are causes for avoiding SCD**

#### **Describe the way to do this in all cases, and the expected result**

### **6.3**  Describe how to generate static content on demand

#### **Describe the default Magento behavior in Production mode and why the new "mode" was added**

#### **How does Magento behave when it is set to this "mode"?**

#### **Know when users can use this configuration and how it works from the Cloud side**

#### **Display time measurements**


## [Section 7: Development (20%)](./7.md)

### **7.1**  Demonstrate ability to change configurations

#### **What are the sources of Magento configuration, and which priorities have different sources of Magento configuration?**

### **7.2**  Demonstrate ability to change a locale

#### **Know how to change a locale on Cloud**

### **7.3**  Demonstrate ability to add extensions

#### **Know how to install Magento extensions and themes (limitations, read-only filesystem, etc.)**

### **7.4**  Demonstrate ability to enable / disable a module

#### **Know how to enable or disable a module on Cloud**

### **7.5**  Demonstrate ability to set up a multisite configuration

#### **Know how to setup multisite configuration: Adding and configuring new websites in Magento; Nginx configuration through the .magento.app.yaml for multisite setup; how to route websites through the magento- vars.php**

### **7.6**  Demonstrate ability to use variables

#### **When do you need to use variables; which configurations you can change using variables**

#### **What is the difference between variables and environment variables**

#### **What is the difference between project and environment level variables**


## [Section 8: Troubleshooting (10%)](./8.md)

### **8.1**  Demonstrate ability to locate and use logs

#### **Locate the Magento application logs**

#### **Locate system services logs on integration and Starter environments**

#### **Locate system services logs on Pro environments**

### **8.2**  Demonstrate ability to create snapshots and backups

### **8.3**  Demonstrate ability to debug

#### **How to use XDebug on Cloud**

### **8.4**  Demonstrate ability to apply Magento fixes in patches

### **8.5**  Describe branch synchronization

#### **Describe branch synchronization and merge**


## [Section 9: Go Live and Maintenance (10%)](./9.md)

### **9.1**  Demonstrate ability to configure DNS

#### **DNS configuration when you're going live**

### **9.2**  Demonstrate ability to set up and configure Fastly

### **9.3**  Demonstrate ability to upgrade to a new version

#### **Upgrade of Magento and ece-tools to newer versions**

### **9.4**  Demonstrate ability to upsize

#### **How to upsize the environment**


Online Sample Test (not available)

The sample test allows you to see the type and format of questions that you will encounter in the actual exam. There is no sign on needed. The results of the sample test are not stored, and do not predict your actual test results.
Photo

#### **Mark your answer in each question.**

#### **Use the link “Send Comments for this Question” to provide specific feedback.**

#### **Click Next on the upper portion of the screen to save your answer and move to the next question. You may return and revise your question within the specified time.**

#### **On the last question, click Submit Exam to submit all your answers.**

#### **Complete the short survey. Click Submit.**

#### **Click “Take Me to My Results” to view your sample test result details.**


Preparing for the Exam

You are not required to complete training before taking the exam, and training alone will not provide you with the knowledge and skills required to pass the exam. A combination of training and successful, on-the-job experience are critical to providing you with the repository needed to pass the exam.

Recommended Preparation:

#### **No prerequisites**

#### **We recommend taking the Magento Commerce Cloud for Developers course as a first step in preparing for this exam**

#### **Hands-on experience with customization and implementation of Magento Commerce Cloud**

#### **No hard-copy or online materials may be referenced during the exam**


Questions and Inquiries?

Please contact the Adobe Credential Program Customer Support team.

The content of this exam guide is subject to changes and updates. Last update August 2020
Appreciate

Credits:

Created with an image by Tomasz Zajda - "Alloy Car Wheel Closeup"
Terms of Service Privacy Policy Report Abuse

