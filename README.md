# Build the popular ‘Hot Dog’ or ‘Not Hot Dog’ app in 30 mins using Machine Learning

This Github repository is instructions for the instructor led Student Lab at Microsoft Build 2019. 

* **Session Title:** Build the popular ‘Hot Dog’ or ‘Not Hot Dog’ app in 30 mins using Machine Learning
* **Session Abstract:** Have you watched the hilarious clip from Silicon Valley when the team created a camera app that recognizes ‘hot dogs’ and ‘not hot dogs’? Want to know how you can build something similar in just 30 mins and explain to your friends how it works? Come along to this interactive session where you will learn how machine learning can power an application to recognize objects in a picture. Finally, turn your project into a live web app after the session with step-by-step instructions online.

## So lets build a Hot Dog, Not Hot Dog classification application ...

1. Please visit the website: [https://www.customvision.ai/](https://www.customvision.ai/). This is a website where we can build a machine learning classifier using no code.

![Custom Vision Website](instructions/customvision.JPG "Custom Vision Website")

2. Please choose the **'Sign In'** button and enter your Azure account email address username and password

On the **'Stay signed in?'** page select **No**

> You will encounter a **permissions window**. This is making sure that you are happy for the Custom Vision website to access your Azure subscription. We will use this access to create a machine learning project instance.

> When you see this pop up please accept **Yes**

![Permissions Requested pop up](instructions/permission-requested.JPG "Permissions Requested pop up")

Then finally please accept the terms of service. Check the box and click the **I Agree** button

![Terms of Service Pop Up](instructions/terms-of-service.JPG "Terms of Service Pop Up")

3. Now everything is setup you should land on a blank page with the **NEW PROJECT** box below. Select the **NEW PROJECT** button

![New Project Page](instructions/create-new-project.JPG "New Project Page")

4. A **Create New Project** window should open. Enter the details below:
* Name: Hot Dog or Not
* Description: A classifier to understand if there are hot dogs in an image or other food

For the **Resource Group** box, we need to create a new one of these. Select the **create new** link.

![Create Project input](instructions/project-name.JPG "Create Project input")

5. After clicking create new the **Create New Resource Group** window will open. Enter the details below:
* Name: application
* Azure Subscription: Choose the subscription you have setup today
* Location: West US 2
* Pricing Tier: SO

The select the **Create resource** button

![Create resource group](instructions/resource-group.JPG "Create resource group")

6. Once complete, you will return to the **Create new project** window and more options will appear. Select the details below:
* Project Types: Classification
* Classification Types: Multiclass (single tag per image)
* Domains: Food

Then select the **Create project** button

![Create Project complete](instructions/select-settings.JPG "Create Project complete")






