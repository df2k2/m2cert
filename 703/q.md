# Sample Test

[Last Section](./10.md) | [Sample Question Answers](./a.md)

------


The sample questions allows you to see the type and format of questions that you will encounter in the actual exam. The results of the sample questions do not predict your actual test results.

## Question 1

A merchant asks you to create a module that is able to process URLs with a custom structure that can contain any combination of a product type code, a partial name, and a 4-digit year in any order. The request path will look like this: /product/:type-code/:name-part/:year Which layer in the Magento request processing flow is suited for this kind of customization?

A. Front controller

B. Router

C. Action controller

D. HTTP Response

## Question 2

While integrating a merchant’s product information management system with Magento, you create a module MyCompany_MerchantPim that adds a catalog product EAV attribute pim_entity_id programmatically. In which type of setup script do you create the EAV attribute?

A) Setup/InstallSchema.php

B) Setup/UpgradeSchema.php

C) Setup/InstallEntity.php

D) Setup/UpgradeData.php


## Question 3

You are facing a bug, which is supposedly caused by the customization of

\Magento\Catalog\Api\ProductRepositoryInterface::save().

To resolve the issue, you decide to find all logic which customizes this method. Which two places do you search for customization declarations? (Choose 2)

A. */di.xml

B. */config.xml

C. */events.xml

D. */plugins.xml

## Question 4

You are implementing a customization of the sales management within a module MyCompany_MySalesProcess. You have created several event observers to add the custom functionality. Each observer is a separate class, but they require some common functionality. How do you implement the common functionality in the event observers, keeping maintainability and testability in mind?

A. You create a trait with the common methods and use the trait in the observer classes.

B. You create an abstract class AbstractObserver with the common methods and extend the observer classes from it.

C. You create a regular class implementing the common functionality as public static methods and call those from the observers.

D. You create a regular class implementing the common functionality as public methods and use constructor injection to make them available to the observers.

## Question 5

A custom module is performing an optimized custom query for quote items. The class applies the query customizations on the select object of a quote item collection instance.
Photo

You are tasked to resolve an issue where the query sometimes does not deliver the expected results. You have debugged the problem and found another class is also using a quote item collection and is loading the collection before the custom module. How do you resolve the issue, keeping maintainability in mind?

A. You change the argument type to \Magento\Quote\Model\ResourceModel\Quote\Item\CollectionFactory and instantiate the collection using $collectionFactory->create();

B. You remove the constructor argument and use ObjectManager::getInstance()->create(\Magento\Quote\Model\ResourceModel\Quote\Item\Collection::class) to instantiate the collection instead.

C. You inject \Magento\Framework\DB\Select instead of the collection and perform the desired query independently of the collection.

D. You inject \Magento\Quote\Api\CartItemRepositoryInterface because low level query customizations are not allowed.

## Question 6

In a custom module you implement the interface \Magento\Framework\App\Config\DataInterface.
Photo

What version constraint for magento/framework do you add to your module’s composer.json file?

A. major

B. minor

C. patch

D. stable
