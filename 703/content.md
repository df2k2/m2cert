# Exam Objectives and Scope

[Table of Contents](./) | [Next Section](./1.md)

**Exam Guide: Adobe Certified Expert - Magento Commerce Developer (AD0-E703) ADOBE CERTIFIED EXPERT**

-----


## [Section 1: Magento Architecture & Customization Techniques (18%)](./1.md)

### **1.1**  Describe Magento’s module-based architecture

#### **Describe module limitations. How do different modules interact with each other? What side effects can come from this interaction?**

### **1.2**  Describe Magento’s directory structure

#### **Determine how to locate different types of files in Magento. Where are the files containing JavaScript, HTML, and PHP located? How do you find the files responsible for certain functionality?**

### **1.3**  Utilize configuration XML and variables scope

#### **Determine how to use configuration files in Magento. Which configuration files correspond to different features and functionality?**

### **1.4**  Demonstrate how to use dependency injection

#### **Describe Magento’s dependency injection approach and architecture. How are objects realized in Magento? Why is it important to have a centralized process creating object instances?**

#### **Identify how to use DI configuration files for customizing Magento. How can you override a native class, inject your class into another object, and use other techniques available in di.xml (such as virtualTypes)?**

### **1.5**  Demonstrate ability to use plugins

#### **Demonstrate how to design complex solutions using the plugin’s life cycle. How do multiple plugins interact, and how can their execution order be controlled? How do you debug a plugin if it doesn’t work?**

#### **Identify strengths and weaknesses of plugins. What are the limitations of using plugins for customization? In which cases should plugins be avoided?**

### **1.6**  Configure event observers and scheduled jobs

#### **Demonstrate how to configure observers. How do you make your observer only be active on the frontend or backend?**

#### **Demonstrate how to configure a scheduled job. Which parameters are used in configuration, and how can configuration interact with server configuration?**

#### **Identify the function and proper use of automatically available events, for example *_load_after, etc.**

### **1.7**  Utilize the CLI

#### **Describe the usage of bin/magento commands in the development cycle. Which commands are available? How are commands used in the development cycle?**

#### **Demonstrate an ability to create a deployment process. How does the application behave in different deployment modes, and how do these behaviors impact the deployment approach for PHP code, frontend assets, etc.?**

### **1.8**  Demonstrate the ability to manage the cache

#### **Describe cache types and the tools used to manage caches. How do you add dynamic content to pages served from the full page cache?**

#### **Describe how to operate with cache clearing. How would you clean the cache? In which case would you refresh cache/flash cache storage?**

#### **Describe how to clear the cache programmatically. What mechanisms are available for clearing all or part of the cache?**


## [Section 2: Request Flow Processing (12%)](./2.md)

### **2.1**  Utilize modes and application initialization

#### **Identify the steps for application initialization. How would you design a customization that should act on every request and capture output data regardless of the controller?**

#### **Describe how to use Magento modes. What are pros and cons of using developer mode/production mode? When do you use default mode? How do you enable/disable maintenance mode?**

#### **Describe front controller responsibilities. In which situations will the front controller be involved in execution, and how can it be used in the scope of customizations?**

### **2.2**  Demonstrate ability to process URLs in Magento

#### **Describe how Magento processes a given URL. How do you identify which module and controller corresponds to a given URL? What is necessary to create a custom URL structure?**

#### **Describe the URL rewrite process and its role in creating user-friendly URLs. How are user-friendly URLs established, and how are they customized?**

#### **Describe how action controllers and results function. How do controllers interact with another? How are different response types generated?**

### **2.3**  Demonstrate ability to customize request routing

#### **Describe request routing and flow in Magento. When is it necessary to create a new router or to customize existing routers? How do you handle custom 404 pages?**

### **2.4**  Determine the layout initialization process

#### **Determine how layout is compiled. How would you debug your layout.xml files and verify that the right layout instructions are used?**

#### **Determine how HTML output is rendered. How does Magento flush output, and what mechanisms exist to access and customize output?**

#### **Determine module layout XML schema. How do you add new elements to the pages introduced by a given module?**

#### **Demonstrate the ability to use layout fallback for customizations and debugging. How do you identify which exact layout.xml file is processed in a given scope? How does Magento treat layout XML files with the same names in different modules?**

#### **Identify the differences between admin and frontend scopes. What differences exist for layout initialization for the admin scope?**

### **2.5**  Determine the structure of block templates

#### **Identify and understand root templates, empty.xml, and page_layout. How are page structures defined, including number of columns, which basic containers are present, etc.?**

#### **Describe the role of blocks and templates in the request flow. In which situations would you create a new block or a new template?**


## [Section 3: Customizing the Magento UI (10%)](./3.md)

### **3.1**  Demonstrate ability to utilize themes and the template structure

#### **Demonstrate the ability to customize the Magento UI using themes. When would you create a new theme? How do you define theme hierarchy for your project?**

#### **Demonstrate the ability to customize/debug templates using the template fallback process. How do you identify which exact theme file is used in different situations? How can you override native files?**

### **3.2**  Determine how to use blocks

#### **Demonstrate an understanding of block architecture and its use in development. Which objects are accessible from the block? What is the typical block’s role?**

#### **Identify the stages in the lifecycle of a block. In what cases would you put your code in the _prepareLayout(), _beforeToHtml(), and _toHtml() methods? How would you use events fired in the abstract block?**

#### **Describe how blocks are rendered and cached.**

#### **Identify the uses of different types of blocks. When would you use non-template block types? In what situation should you use a template block or other block types?**

### **3.3**  Demonstrate ability to use layout and XML schema

#### **Describe the elements of the Magento layout XML schema, including the major XML directives. How do you use layout XML directives in your customizations?**

#### **Describe how to create a new layout XML file.**

#### **Describe how to pass variables from layout to block.**

### **3.4**  Utilize JavaScript in Magento

#### **Describe different types and uses of JavaScript modules. Which JavaScript modules are suited for which tasks?**

#### **Describe UI components. In which situation would you use UiComponent versus a regular JavaScript module?**

#### **Describe the use of requirejs-config.js, x-magento-init, and data-mage-init.**


## [Section 4: Working with Databases in Magento (7%)](./4.md)

### **4.1**  Demonstrate ability to use data-related classes

#### **Describe repositories and data API classes. How do you obtain an object or set of objects from the database using a repository? How do you configure and create a SearchCriteria instance using the builder? How do you use Data/Api classes?**

#### **Describe how to create and register new entities. How do you add a new table to the database?**

#### **Describe the entity load and save process.**

#### **Describe how to extend existing entities. What mechanisms are available to extend existing classes, for example by adding a new attribute, a new field in the database, or a new related entity?**

#### **Describe how to filter, sort, and specify the selected values for collections and repositories. How do you select a subset of records from the database?**

#### **Describe the database abstraction layer for Magento. What type of exceptions does the database layer throw? What additional functionality does Magento provide over Zend_Adapter?**

### **4.2**  Demonstrate an ability to use declarative schema

#### **Demonstrate use of schema. How to manipulate columns and keys using declarative schema? What is the purpose of whitelisting? How to use Data and Schema patches? How to manage dependencies between patch files?**


## [Section 5: using the Entity-Attribute-Value (EAV) Model (8%)](./5.md)

### **5.1**  Demonstrate ability to use EAV model concepts

#### **Describe the EAV hierarchy structure. What happens when a new attribute is added to the system? What is the role of attribute sets and attribute groups? How are attributes presented in the admin?**

#### **Describe how EAV data storage works in Magento. Which additional options do you have when saving EAV entities? How do you create customizations based on changes to attribute values?**

#### **Describe the key differences between EAV and flat table collections. In which situations would you use EAV for a new entity? What are the pros and cons of EAV architecture?**

### **5.2**  Demonstrate ability to use EAV entity load and save


#### **Describe the EAV load and save process and differences from the flat table load and save process. What happens when an EAV entity has too many attributes? How does the number of websites/stores affect the EAV load/save process? How would you customize the load and save process for an EAV entity in the situations described here?**

### **5.3**  Demonstrate ability to manage attributes


#### **Describe EAV attributes, including the frontend/source/backend structure. How would you add dropdown/multiselect attributes? What other possibilities do you have when adding an attribute (to a product, for example)?**

#### **Describe how to implement the interface for attribute frontend models. What is the purpose of this interface? How can you render your attribute value on the frontend?**

#### **Identify the purpose and describe how to implement the interface for attribute source models. For a given dropdown/multiselect attribute, how can you specify and manipulate its list of options?**

#### **Identify the purpose and describe how to implement the interface for attribute backend models. How (and why) would you create a backend model for an attribute?**

#### **Describe how to create and customize attributes. How would you add a new attribute to the product, category, or customer entities? What is the difference between adding a new attribute and modifying an existing one?**


## [Section 6: Developing with Adminhtml (10%)](./6.md)

### **6.1**  Describe common structure/architecture

#### **Describe the difference between Adminhtml and frontend. What additional tools and requirements exist in the admin?**

### **6.2**  Define form and grid widgets


#### **Define form structure, form templates, grids, grid containers, and elements. What steps are needed to display a grid or form?**

#### **Describe the grid and form workflow. How is data provided to the grid or form? How can this be process be customized or extended?**

#### **Describe how to create a simple form and grid for a custom entity. Given a specific entity with different types of fields (text, dropdown, image, file, date, and so on) how would you create a grid and a form?**

### **6.3**  Define system configuration XML and configuration scope


#### **Define basic terms and elements of system configuration XML, including scopes. How would you add a new system configuration option? What is the difference in this process for different option types (secret, file)?**

#### **Describe system configuration data retrieval. How do you access system configuration options programmatically?**

### **6.4**  Utilize ACL to set menu items and permissions


#### **Describe how to set up a menu item and permissions. How would you add a new menu item in a given tab? How would you add a new tab in the Admin menu? How do menu items relate to ACL permissions?**

#### **Describe how to check for permissions in the permissions management tree structures. How would you add a new user with a given set of permissions? How can you do that programmatically?**


## [Section 7: Customizing the Catalog (12%)](./7.md)

### **7.1**  Demonstrate ability to use products and product types


#### **Identify/describe standard product types (simple, configurable, bundled, etc.). How would you obtain a product of a specific type? What tools (in general) does a product type model provide? What additional functionality is available for each of the different product types?**

### **7.2**  Describe price functionality


#### **Identify the basic concepts of price generation in Magento. How would you identify what is composing the final price of the product? How can you customize the price calculation process?**

#### **Describe how price is rendered in Magento. How would you render price in a given place on the page, and how would you modify how the price is rendered?**

### **7.3**  Demonstrate ability to use and customize categories

#### **Describe category properties and features. How do you create and manage categories?**

#### **Describe the category hierarchy tree structure implementation (the internal structure inside the database). What is the meaning of parent_id 0? How are paths constructed? Which attribute values are required to display a new category in the store? What kind of strategies can you suggest for organizing products into categories?**

### **7.4**  Determine and manage catalog rules


#### **Identify how to implement catalog price rules. When would you use catalog price rules? How do they impact performance? How would you debug problems with catalog price rules?**


## [Section 8: Customizing the Checkout Process (13%)](./8.md)

### **8.1**  Demonstrate ability to use quote, quote item, address, and shopping cart rules in checkout


#### **Describe how to modify these models and effectively use them in customizations.**

#### **Describe how to customize the process of adding a product to the cart. Which different scenarios should you take into account?**

### **8.2**  Demonstrate ability to use totals models


#### **Describe how to modify the price calculation process in the shopping cart. How can you add a custom totals model or modify existing totals models?**

### **8.3**  Demonstrate ability to customize the shopping cart


#### **Describe how to implement shopping cart rules. What is the difference between sales rules and catalog rules? How do sales rules affect performance? What are the limitations of the native sales rules engine?**

#### **Describe add-to-cart logic in different scenarios. What is the difference in adding a product to the cart from the product page, from the wishlist, by clicking Reorder, and during quotes merge?**

#### **Describe the difference in behavior of different product types in the shopping cart. How are configurable and bundle products rendered? How can you create a custom shopping cart renderer?**

#### **Describe the available shopping cart operations. Which operations are available to the customer on the cart page? How can you customize cart edit functionality? How would you create an extension that deletes one item if another was deleted? How do you add a field to the shipping address?**

### **8.4**  Demonstrate ability to customize shipping and payment methods

#### **Describe shipping methods architecture. How can you create a new shipping method? What is the relationship between carriers and rates?**

#### **Describe how to troubleshoot shipping methods and rate results. Where do shipping rates come from? How can you debug the wrong shipping rate being returned?**

#### **Describe how to troubleshoot payment methods. What types of payment methods exist? What are the different payment flows?**


## [Section 9: Sales Operations (5%)](./9.md)

### **9.1**  Demonstrate ability to customize sales operations

#### **Describe how to modify order processing and integrate it with a third-party ERP system.**

#### **Describe how to modify order processing flow. How would you add new states and statuses for an order? How do you change the behavior of existing states and statuses?**

#### **Described how to customize invoices. How would you customize invoice generation, capturing, and management?**

#### **Describe refund functionality in Magento. Which refund types are available, and how are they used?**


## [Section 10: Customer Management (5%)](./10.md)

### **10.1**  Demonstrate ability to customize My Account

#### **Describe how to customize the “My Account” section. How do you add a menu item? How would you customize the “Order History” page?**

### **10.2**  Demonstrate ability to customize customer functionality

#### **Describe how to add or modify customer attributes.**

#### **Describe how to extend the customer entity. How would you extend the customer entity using the extension attributes mechanism?**

#### **Describe how to customize the customer address. How would you add another field into the customer address?**

#### **Describe customer groups and their role in different business processes. What is the role of customer groups? What functionality do they affect?**

#### **Describe Magento functionality related to VAT. How do you customize VAT functionality?**

