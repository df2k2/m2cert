# Exam Objectives and Scope

[Table of Contents](./) | [Next Section](./1.md)

-----


## [Section 1: Magento Architecture & Customization Techniques (33%)](./1.md)

### **1.1**  Describe the Magento module-based architecture

#### **Describe module architecture. What are the significant steps to add a new module? What are the different Composer package types? When would you place a module in the app/code folder versus another location?**

### **1.2**  Describe the Magento directory structure

#### **Describe the Magento directory structure. What are the naming conventions, and how are namespaces established? How can you identify the files responsible for some functionality?**

### **1.3**  Utilize configuration and configuration variables scope

#### **Determine how to use configuration files in Magento. Which configuration files are important in the development cycle?**

#### **Describe development in the context of website and store scopes. How do you identify the configuration scope for a given variable? How do native Magento scopes (for example, price or inventory) affect development and decision-making processes?**

#### **Demonstrate an ability to add different values for different scopes. How can you fetch a system configuration value programmatically? How can you override system configuration values for a given store using XML configuration?**

### **1.4**  Demonstrate how to use dependency injection (DI)

#### **Demonstrate the ability to use the dependency injection concept in Magento development. How are objects realized in code? Why is it important to have a centralized object creation process?**

#### **Identify how to use DI configuration files for customizing Magento. How can you override a native class, inject your class into another object, and use other techniques available in di.xml (for example, virtualTypes)?**

#### **Given a scenario, determine how to obtain an object using the ObjectManager object. How would you obtain a class instance from different places in the code?**

### **1.5**  Demonstrate ability to use plugins

#### **Demonstrate an understanding of plugins. How are plugins used in core code? How can they be used for customizations?**

### **1.6**  Configure event observers and scheduled jobs

#### **Demonstrate how to create a customization using an event observer. How are observers registered? How are they scoped for frontend or backend? How are automatic events created, and how should they be used? How are scheduled jobs configured?**

### **1.7**  Utilize the CLI

#### **Describe the usage of bin/magento commands in the development cycle. Which commands are available? How are commands used in the development cycle?**

### **1.8**  Describe how extensions are installed and configured

#### **How would you install and verify an extension by a customer’s request?**


## [Section 2: Request Flow Processing (7%)](./2.md)

### **2.1**  Describe how to use Magento modes

#### **Understand the pros and cons of using developer mode or production mode. How do you enable/disable maintenance mode?**

### **2.2**  Demonstrate the ability to create a frontend controller with different response types (HTML / JSON / redirect)

#### **How do you identify which module/controller corresponds to a given URL? What would you do to create a given URL?**

### **2.3**  Demonstrate how to use URL rewrites for a catalog product view to a different URL

#### **How is the user-friendly URL of a product or category defined? How can you change it? How do you determine which page corresponds to a given user-friendly URL?**


## [Section 3: Customizing the Magento UI (15%)](./3.md)

### **3.1**  Demonstrate the ability to customize the Magento UI using themes

#### **Demonstrate the ability to customize the Magento UI using themes. When would you create a new theme? How do you define theme hierarchy for a project?**

### **3.2**  Demonstrate an ability to create UI customizations using a combination of a block and template

#### **How do you assign a template to a block? How do you assign a different template to a native block?**

### **3.3**  Identify the uses of different types of blocks

#### **When would you use non-template block types?**

### **3.4**  Describe the elements of the Magento layout XML schema, including the major XML directives

#### **How do you use layout XML directives in your customizations? How do you register a new layout file?**

### **3.5**  Create and add code and markup to a given page

#### **How do you add new content to existing pages using layout XML?**


## [Section 4: Working with Databases in Magneto (18%)](./4.md)

### **4.1**  Describe the basic concepts of models, resource models, and collections

#### **What are the responsibilities of each of the ORM object types? How do they relate to one another?**

### **4.2**  Describe how entity load and save occurs

#### **How do you use the native Magento save/load process in the development process?**

### **4.3**  Describe how to filter, sort, and specify the selected values for collections and repositories

#### **How do you select a subset of records from the database?**

### **4.4**  Demonstrate an ability to use declarative schema

#### **How do you add a column using declarative schema? How do you modify a table added by another module? How do you delete a column? How do you add an index or foreign key using declarative schema? How do you manipulate data using data patches? What is the purpose of schema patches?**


## [Section 5: Developing with Adminhtml (11%)](./5.md)

### **5.1**  Create a controller for an admin router

#### **How would you create an admin controller? How do you ensure the right level of security for a new controller?**

### **5.2**  Define basic terms and elements of system configuration, including scopes, website, store, store view

#### **How would you add a new system configuration option? What is the difference in this process for different option types (secret, file)?**

### **5.3**  Define / identify basic terms and elements of ACL

#### **How would you add a new ACL resource to a new entity? How do you manage the existing ACL hierarchy?**

### **5.4**  Set up a menu item

#### **How do you add a new menu item to a given tab? How do you add a new tab to the Admin menu?**

### **5.5**  Create appropriate permissions for users

#### **How are menu items related to ACL permissions? How do you add a new user with given set of permissions?**


## [Section 6: Customizing Magento Business Logic (16%)](./6.md)

### **6.1**  Identify/describe standard product types (simple, configurable, bundled, etc.)

#### **How would you obtain a product of a specific type, and what tools (in general) does a product type model provide?**

### **6.2**  Describe category properties in Magento

#### **How do you create and manage categories?**

### **6.3**  Define how products are related to the category

#### **How do you assign and unassign products to categories?**

### **6.4**  Describe the difference in behavior of different product types in the cart

#### **How are configurable and bundle products rendered? How can you create a custom shopping cart renderer?**

### **6.5**  Describe native shipment functionality in Magento

#### **How do you customize the shipment step of order management?**

### **6.6**  Describe and customize operations available in the customer account area

#### **How would you add another tab in the “My Account” section? How do you customize the order history page?**

### **6.7**  Add or modify customer attributes

#### **How do you add or modify customer attributes in a setup script?**

### **6.8**  Customize the customer address

#### **How do you add another field to the customer address entity using a setup script?**


