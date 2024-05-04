+++
title = "Salesforce Developer Virtual Internship"
date  = 2023-10-01
author = "gowra pavan"
+++

## CHAPTER 1: EXECUTIVE SUMMARY

### Learning Objectives:
1. Understand the Salesforce Platform Architecture.
2. Develop Salesforce Objects and Fields Using Apex Code.
3. Design and Implement Visualforce Pages for Custom User Interfaces.
4. Integrate Salesforce Applications with External Systems.
5. Deploy and Secure Salesforce Applications.

### Learning Outcomes:
1. Understand the key components of the Salesforce platform.
2. Write Apex code to create and manage Salesforce objects.
3. Build custom user interfaces using Visualforce.
4. Consume external data using the Salesforce APIs.
5. Deploy Salesforce applications to Heroku.
6. Implement Salesforce security best practices.
7. Develop a functional Salesforce application.

This report is about my 8 weeks virtual internship program with Smart Internz. In this comprehensive report, I have discussed about every major aspect of the company which I observed and perceived during my virtual internship program. 
During my virtual internship program, I have learned and mainly worked on Apex Specialist, Process Automation Specialist and Developer Superset. All the details have been discussed in detail. All the policies and procedures of the company have been discussed in detail. 
Salesforce developers play a critical role in driving innovation and improving business operations through Salesforce applications. With the growing demand for Salesforce expertise, aspiring developers can embark on a rewarding career path that offers ample opportunities for growth and advancement. By acquiring the necessary skills and knowledge, Salesforce developers can contribute significantly to the success of organizations across diverse industries.

## CHAPTER 2: OVERVIEW OF THE ORGANIZATION

### A. Introduction of the Organization
#### What Is Salesforce?
Salesforce is your customer success platform, designed to help you sell, service, market, analyse, and connect with your customers. 
Salesforce has everything you need to run your business from anywhere. Using standard products and features, you can manage relationships with prospects and customers, collaborate and engage with employees and partners, and store your data securely in the cloud. 
Salesforce is the world‘s #1 CRM (Customer Relationship Management) where it unites Marketing, Sales, Commerce, IT etc teams to their customers to deliver a better service. We are determined to teach this emerging Technology in a very realistic and fun way. We have organized the challenges in such a way that the learner will be able to learn Salesforce in a very enthusiastic and fun way with a limited time participation. This program consists of live sessions, Hands-on practical activities, mentoring support and working on super badges on Trailhead platform. In order to help all beginners understand the Salesforce ecosystem and its products, we have curated a few best modules on the Trailhead platform that will help you to get ready for the Bootcamp.

#### B. Vision, Mission and Values of the Organization
#### Vision:
To provide the world's most innovative and trusted customer relationship management (CRM) platform that enables companies to connect with their customers in a whole new way.

#### Mission:
Salesforce's mission is to help companies of every size and industry connect with their customers in new ways using cloud, mobile, social, and artificial intelligence technologies. Salesforce aims to make technology more accessible, user-friendly, and affordable for businesses, non-profits, and governments worldwide.

#### Values:
Salesforce is driven by its core values that are deeply ingrained in its culture and guide its decisions, actions, and interactions with customers, partners, employees, and communities. These values include:
- Trust
- Customer Success
- Innovation
- Equality
- Giving Back

### C. Policy of the Organization, in relation with the intern role 
Salesforce, as a global technology company, has a strong commitment to fostering a diverse and inclusive workplace. Their policy in relation to intern roles is to provide an environment where interns can develop their skills and gain valuable experience while contributing to the company's mission.
Salesforce believes that interns should be treated with respect, provided with equal opportunities and fair compensation, and given access to resources and tools that will enable them to succeed in their roles. They also encourage interns to be proactive and take ownership of their work, and provide opportunities for mentorship and professional development.
In terms of specific policies related to internships, Salesforce has a code of conduct that all employees, including interns, are expected to follow. This code includes guidelines for ethical behaviour, professionalism, and respect for others.
Salesforce also has a policy of non-discrimination, and interns are expected to adhere to this policy as well. This means that interns will not be discriminated against based on factors such as race, ethnicity, gender, sexual orientation, religion, or age.
Overall, Salesforce's policy regarding intern roles is centred around providing a supportive and inclusive environment where interns can learn and grow, while also contributing to the company's success.

### D. Organizational Structure 
Salesforce is a large organization with a complex organizational structure. At the top of the hierarchy is the Chief Executive Officer (CEO), who is responsible for setting the overall strategy and direction of the company. Under the CEO are several executive vice presidents who are responsible for different business units, such as Sales, Marketing, and Operations.
Salesforce's organizational structure is divided into three main groups: Customer Success, Technology, and Products.
Customer Success: This group is responsible for ensuring that customers are successful in their use of Salesforce products. It includes teams focused on customer service, customer success management, and training.
Technology: This group is responsible for the development and maintenance of the Salesforce platform, as well as the infrastructure and systems that support it. It includes teams focused on engineering, data science, and security.
Products: This group is responsible for the development and delivery of Salesforce's product offerings. It includes teams focused on product management, product marketing, and product development.

## CHAPTER 3: INTRODUCTION TO SALESFORCE COMPONENTS

### A. Create a Trailhead Playground
#### What Is a Trailhead Playground?
A Trailhead Playground is an org we can use to complete hands-on challenges and try out new features and customizations. Much like a real playground, a Trailhead Playground lets us play around and make customizations without impacting anything else.
We can do almost anything to our Trailhead Playground, and it comes with a set of Trailhead-specific data that we can use when completing challenges. Trailhead Playgrounds have some limits, but for the most part they give us the same customization options as a production org. And although we can outgrow a real-life playground, our Trailhead Playground never expires, as long as we keep using it.
Follow Along with Trail Together
A Trailhead Playground is a DE org, but specifically for Trailhead. Trailhead Playgrounds come with Trailhead-specific data, and a pre-installed package that we use to test your hands-on challenges. Trailhead Playgrounds also include tools to make some of the tasks you’ll find yourself completing often easier, such as finding your username and resetting your password, and installing managed packages.

#### Creating our First Trailhead Playground
Once we've created a Trailhead account with our Salesforce account or a linked social account. A Trailhead Playground is created automatically and linked to our Trailhead account.
In every hands-on challenge and project step verification, we'll see the name of a hands-on org and a Launch button. Trailhead automatically chooses our most recently used org or, if we've tried the challenge before, the org we last used for that particular challenge. If we've never used a hands-on org before, Trailhead defaults to our most recently created playground.

# Adding a List View Component

Now that you have a page, you can add components. For your first component, drag a List View component onto the page.

1. In the Desktop drop-down list, click Tablet - Portrait. The canvas's preview layout changes from the standard single column to two columns.
2. From the Standard Components menu on the left, drag the List View to the left column.
3. Set the properties of this component using the Properties list in the right sidebar.
   - In the Object drop-down list, select Account.
   - In the Filter drop-down list, select My Accounts.
   - In the Number of Records to Display field, enter 7.
   
![Number of Records in New Lightning App](link-to-image)

Click Save and then click Not Yet in the popup window. We will activate this page in a later step.

# Basics of Apex

Apex is a programming language that uses Java-like syntax and acts like database stored procedures. Apex enables developers to add business logic to system events, such as button clicks, updates of related records, and Visualforce pages.

As a language, Apex is:
- **Hosted:*** Apex is saved, compiled, and executed on the server—the Lightning Platform.
- **Object oriented:** Apex supports classes, interfaces, and inheritance.
- **Strongly typed:** Apex validates references to objects at compile time.
- **Multitenant aware:** Because Apex runs in a multitenant platform, it guards closely against runaway code by enforcing limits, which prevent code from monopolizing shared resources.
- **Integrated with the database:** It is straightforward to access and manipulate records. Apex provides direct access to records and their fields, and provides statements and query languages to manipulate those records.
- **Data focused:** Apex provides transactional access to the database, allowing you to roll back operations.
- **Easy to use:** Apex is based on familiar Java idioms.
- **Easy to test:** Apex provides built-in support for unit test creation, execution, and code coverage. Salesforce ensures that all custom Apex code works as expected by executing all unit tests prior to any platform upgrades.
- **Versioned:** Custom Apex code can be saved against different versions of the API.

![Apex Usage](link-to-image)

## Apex Language Highlights

Like other object-oriented programming languages, these are some of the language constructs that Apex supports:
- Classes, interfaces, properties, and collections (including arrays).
- Object and array notation.
- Expressions, variables, and constants.
- Conditional statements (if-then-else) and control flow statements (for loops and while loops).

Unlike other object-oriented programming languages, Apex supports:
- Cloud development as Apex is stored, compiled, and executed in the cloud.
- Triggers, which are similar to triggers in database systems.
- Database statements that allow you to make direct database calls and query languages to query and search data.
- Transactions and rollbacks.
- The global access modifier, which is more permissive than the public modifier and allows access across namespaces and applications.
- Versioning of custom code.

# Apex Triggers

Apex triggers enable you to perform custom actions before or after events to records in Salesforce, such as insertions, updates, or deletions. Just like database systems support triggers, Apex provides trigger support for managing records.

Typically, you use triggers to perform operations based on specific conditions, to modify related records or restrict certain operations from happening. You can use triggers to do anything you can do in Apex, including executing SOQL and DML or calling custom Apex methods.

Use triggers to perform tasks that can’t be done by using the point-and-click tools in the Salesforce user interface. For example, if validating a field value or updating a field on a record, use validation rules and flows. Use Apex triggers if performance and scale is important, if your logic is too complex for the point-and-click tools, or if you're executing CPU-intensive operations.

Triggers can be defined for top-level standard objects, such as Account or Contact, custom objects, and some standard child objects. Triggers are active by default when created. Salesforce automatically fires active triggers when the specified database events occur.

## Trigger Syntax

The syntax of a trigger definition is different from a class definition’s syntax. A trigger definition starts with the trigger keyword. It is then followed by the name of the trigger, the Salesforce object that the trigger is associated with, and the conditions under which it fires. A trigger has the following syntax:

To execute a trigger before or after insert, update, delete, and undelete operations, specify multiple trigger events in a comma-separated list. The events you can specify are:
- before insert
- before update
- before delete
- after insert
- after update
- after delete
- after undelete

## Trigger Example

This simple trigger fires before you insert an account and writes a message to the debug log.
1. In the Developer Console, click File | New | Apex Trigger.
2. Enter Hello World Trigger for the trigger name, and then select Account for the subjects. Click Submit.
3. Replace the default code with the following.
4. To save, press Ctrl+S.
5. To test the trigger, create an account.
   - Click Debug | Open Execute Anonymous Window.
   - In the new window, add the following and then click Execute.
6. In the debug log, find the Hello World! statement. The log also shows that the trigger has been executed.

## Types of Triggers

There are two types of triggers.
- **Before triggers** are used to update or validate record values before they’re saved to the database.
- **After triggers** are used to access field values that are set by the system (such as a record's Id or Last Modified Date field), and to affect changes in other records. The records that fire the after trigger are read-only.

# Apex Classes

Apex classes are the building blocks of Salesforce development. They are used to implement business logic, such as creating and updating records, sending emails, and integrating with external systems. Apex classes are written in the Apex programming language, which is a strongly typed, object-oriented language that is similar to Java.

### Example of an Apex class:
```apex
public class AccountCreator {
    public static Account create Account (String name) {
        Account = new Account ();
        account. Name = name;
        insert account;
        return account;
    }
}
```
# Lightning Web Components

Lightning Web Components (LWC) is a modern programming model for creating Lightning components in Salesforce. It leverages web standards and can seamlessly coexist with the Aura programming model while offering superior performance. To start developing with LWC, set up Salesforce DX and use Visual Studio Code as your code editor.

## Install the Command Line Interface (CLI)

Use the Salesforce CLI to manage the full lifecycle of your Salesforce applications. Install the CLI from [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli). Confirm the installation by running   ` sf update` in the command line.

## Install Salesforce Extensions for Visual Studio Code

Visual Studio Code is the preferred code editor for Salesforce developers. Install the Salesforce Extension Pack from the Extensions panel in Visual Studio Code.

## Create a Lightning Web Component

### Create a Salesforce DX Project

1. Open the Command Palette in Visual Studio Code.
2. Type SFDX and select "SFDX: Create Project".
3. Accept the default options and name your project "Hello World Lightning Web Component".
4. Choose a folder to store the project and create it.

### Authorize Your Trailhead Playground

1. Open the Command Palette.
2. Type SFDX and select "SFDX: Authorize an Org".
3. Follow the prompts to log in using your Trailhead Playground credentials.

### Create a Lightning Web Component

1. Open the Command Palette.
2. Type SFDX and select "SFDX: Create Lightning Web Component".
3. Enter "helloWorld" as the component name.
4. Accept the default file path.
5. View the newly created files in Visual Studio Code.

6. Copy the following code into `helloWorld.html`:

```html
<template>
   <lightning-card title="HelloWorld" icon-name="custom:custom14">
     <div class="slds-m-around_medium">
       <p>Hello, {greeting}!</p>
       <lightning-input label="Name" value={greeting} onchange={changeHandler}></lightning-input>
     </div>
   </lightning-card>
</template>
```
7.  Copy the following code into `helloWorld.js`:

```javascript
import { LightningElement } from 'lwc';

export default class HelloWorld extends LightningElement {
  greeting = 'World';

  changeHandler(event) {
    this.greeting = event.target.value;
  }
}

```

### Visualforce Developer super badge:
  This super badge assesses your ability to develop and maintain Visualforce pages. Visualforce is a declarative language that can be used to create user interfaces for Salesforce applications.
	

![Example Image](/images/profile.jpg)





                 Fig :4a Apex specialist                             Fig :4b Flow Elements and Resources Specialist

 

                                                         

           Fig :4c Screen Flow Specialist                               Fig :4d Process Automation Specialist






                          

                                                        Fig :4e Developer Super Set

