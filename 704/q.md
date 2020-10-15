# Sample Questions

[Last Section](./6.md) | [Sample Question Answers](./a.md)

------

The sample questions allows you to see the type and format of questions that you will encounter in the actual exam. The results of the sample questions do not predict your actual test results.


## Question 1

In your phtml template file you need to output a URL inside a JavaScript context.

var url = '<?= /* code here */ ?>';

Which two methods allow you to keep the output XSS-safe?

A. escapeUrl

B. escapeHtmlAttr

C. escapeHtml

D. escapeJs


## Question 2

You are working on a custom form in the Admin and the form is too lengthy. To organize the form better, you decide to group the fields into multiple tabs. How do you achieve this?

A. Create a plugin for the method MyCompany\MyModule\Block\Adminhtml\Form\Edit\Tabs::toHtml()

B. Add the fields into <tab> nodes in the customer_account_edit.xml layout file

C. Add the fields into a <fieldset> node in the existing form in the ui_component XML file

D. Add a new form for the field group in the ui_component XML file

## Question 3

You are making some changes to your existing action controller
Photo

You want to inject a new dependency to the controller, but you encounter the following error after flushing the cache and reloading the page: Recoverable Error: Argument 2 passed to MyCompany\MyModule\Controller\Index\Index:: construct() must be an instance of <new dependency class> … How do you fix the error?

A. New dependencies must be added at the end of the constructor signature because dependencies cannot be added in the middle of existing constructors

B. Remove the generated child class from generated/code that is calling the parent constructor with the old signature

C. Clean the config cache that contains all constructor signatures

D. Configure the new argument in di.xml for the controller class


## Question 4

You are working with an OMS that requires you to add an attribute to the order API. How do you add a field to the existing sales API?

A. You update Magento\Sales\Api\OrderManagementInterface and

Magento\Sales\Api\Data\OrderInterface to add your field

B. You add an extension attribute to Magento\Sales\Api\Data\OrderInterface to include the new field

C. You create an install script to add a column to the sales table and Magento will automatically pull in the information

D. You create an etc/webapi.xml file and add the new field as an item to the route, as shown in the following code:
Photo


## Question 5

You are exploring the customer segment module and find this code in frontend/di.xml:
Photo

What effect does this plugin have for customer segments?

A. It passes the segment information to the Knockout JS model from the customer session

B. It passes the segment information to the HttpContext from the customer session

C. It cleans the intermediate data of the segment-website and the segment-customer mapping in the tables to improve performance

D. It cleans the segment and customer related entities from the session
