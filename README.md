# Azure Fundamentals: NodeJS App Deployment

### Task 1: Create App Service in the Azure Portal

1. In the [Azure Portal](https://portal.azure.com/), select **+Create a resource** from the left menu, then search for **web app** or find it in the Popular Services menu.

2. Click **Create**.

    ![Create WebApp](images/create_webapp.png)

3. Set the following configuration on the Basics tab:

- **Subscription**: (Your Subscription) Select the subscription you are using for this hands-on lab.
- **Resource Group**: Select the **Create new** link, and enter `bocacode-app-rg` as the name of the new resource group.
- **Name**: Enter a globally unique name for your application. Example: bocacode-app-au
- **Publixh**: Select **Code**
- **Runtime Stack**: Select **Node 10.14**
- **Operating System**: Select **Linux**
- **Region**: Select **East US**
- **Linux Plan**: Select **Create New** and enter a unique name for the Service Plan

    ![Create WebApp](images/webapp_form.png)

4. Click **Review+Create**
