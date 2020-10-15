# Exam Objectives and Scope

[Table of Contents](./) | [Next Section](./1.md)

-----


## [Section 1: Magento Order Management functionality (7%)](./1.md)

### **1.1**  Demonstrate ability to use the Magento Order Management API

#### **What is the Magento Order Management API used for?**

#### **Which protocol is the Magento Order Management API using to the external system?**

#### **What kind of messages is the Magento Order Management API using?**

### **1.2**  Given a scenario, determine which values are needed to register your application

### **1.3**  Understand the difference between sync and async messages


## [Section 2: Integration flow (7%)](./2.md)

### **2.1**  Demonstrate ability to determine the current flows to be integrated between Magento Order Management and Magento Commerce

### **2.2**  Identify the actions needed based on messaging within the integration flow

#### **Which message will Magento Order Management receive to create orders?**

#### **Which message will Magento Order Management deliver to update Magento Commerce orders?**

#### **Which message will Magento Order Management deliver to create a shipment in Magento Commerce?**

#### **Which message will Magento Order Management receive to authorize a payment?**

#### **What are the actions needed around these messages?**


## [Section 3: Plans and environment (5%)](./3.md)

### **3.1**  Demonstrate ability to create a tunnel between the local environment and Magento Order Management

### **3.2**  Demonstrate ability to access the local environment

#### **Magento Order Management pricing: License fees for Core Magento Order Management and Store Fulfillment, Onboarding fee + TAM support, Services Offerings (as needed)**


## [Section 4: Integrations (23%)](./4.md)

### **4.1**  Demonstrate ability to design an integration

#### **Integration overview and review of system architecture diagram**

#### **Best practices for integrating with Magento Order Management**

#### **If you want to receive the shipment-request from Magento Order Management what integration should be designed?**

#### **If you want to receive a payment notification form Magento Order Management what integration should be designed?**

### **4.2**  Determine the actions needed for an integration based on messaging

#### **If you are receiving payment notifications which message should you expect?**

#### **If you are receiving shipment notifications which message should you expect?**

#### **If you are sending information about shipments which message will you send to Magento Order Management to notify that a shipment was canceled or shipped?**

#### **Which message does Magento Commerce receive from Magento Order Management?**

#### **Which message does Magento Order Management use to update inventory from sources?**

#### **magento.inventory.aggregate_stock_management.updated: What is it used for? Which integration is it receiving? What information should the message lines_shipped include?**

### **4.3**  Determine how to register integrations properly with Magento Order Management

### **4.4**  Determine how to integrate inventory sources with Magento Order Management

#### **Types of inventory integrations (delta, nonzero, full) and strategies (adjustment, snapshot, etc.)**

### **4.5**  Demonstrate knowledge of sales channel integrations

### **4.6**  Determine how to perform shipping integration and receive carrier information for orders

### **4.7**  Describe how to use carrier integration

### **4.8**  Define a customer service integration

#### **Other types of integrations (reporting, CRM, PIM, etc.)**

#### **Define how to use the customer service APIs to perform order actions in a third-party tool**

### **4.9**  Determine how to use a custom payment integration


## [Section 5: Troubleshooting (10%)](./5.md)

### **5.1**  Demonstrate ability to troubleshoot issues coming from an integration

### **5.2**  Determine alerts and guardrails during the integration testing cycle

### **5.3**  Determine how to subscribe to and properly use the Magento Status pages


## [Section 6: Magento Commerce Collector (18%)](./6.md)

### **6.1**  Demonstrate ability to configure the Magento Commerce Connector

#### **Which configuration must be added to the env.php file and which command must be run to register Magento Commerce to the Magento Order Management API?**

#### **If stock is not received, where should you go to start investigating the problem?**

#### **Which configuration is needed to send orders from Magento Commerce to Magento Order Management?**

### **6.2**  Demonstrate ability to synchronize stock between Magento Commerce and Magento Order Management

#### **If you want to synchronize stock between Magento Commerce and Magento Order Management, which kind of configuration do you need to add?**

#### **How do you manage a stock aggregate page to create an association with a website and aggregates?**

### **6.3**  Identify and determine messages within the Connector

#### **Which message is sent to Magento Order Management to synchronize the catalog?**

#### **How can you do a FULL catalog export?**

### **6.4**  Demonstrate ability to create automatic messages and notifications

#### **Which message sent from Magento Order Management will automatically create invoices and shipments in Magento Commerce?**


## [Section 7: Magento Order Management knowledge (13%)](./7.md)

### **7.1**  Identify the differences between soft allocation and hard allocation

### **7.2**  Identify the differences between source-stock message in mode NONZERO or FULL

### **7.3**  Identify the difference between a refund and return

### **7.5**  Identify the difference between In-store pickup and ship from store

### **7.6**  Determine the use of pick-confirm in Magento Order Management

### **7.7**  Understand special order types


## [Section 8: Connector (12%)](./8.md)

### **8.1**  Demonstrate ability to customize the connector

### **8.2**  Demonstrate ability to update a new version of the connector

### **8.3**  Demonstrate an ability to install and configure with the Magento Commerce Connector

### **8.4**  Determine how to configure the Magento Commerce back office to work with the connector


## [Section 9: Deployment process (5%)](./9.md)

### **9.1**  Demonstrate ability to perform application testing

### **9.2**  Identify pre-launch activities



