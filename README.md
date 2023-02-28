# Ascend-Hackathon

## Challenge: Detect Vehicle’s License Plate

Contoso Ltd. is a company that manages toll booths. It’s currently using a manual process to identify vehicle license plates and send the data to the billing software. The company plans to leverage the latest cloud technologies to automate the manual process. You’re tasked to build a Proof-of-Concept (POC) system to realize the following requirement:
- Contoso wants a consumption-based price model for its cloud resources and avoid the costs associated with operating and maintaining VMs. Hence it wants to adopt the serverless architecture for the new system.
- Contoso uses camera to capture the vehicle image and uploads the image to Azure Storage. This is outside the scope of POC.
- When a vehicle image is uploaded, the POC application should pick up the image and detect the license plate number.
- Contoso does not have the machine learning expertise, hence wants to take advantage of a pre-built artificial intelligence service that would allow them to accurately detect license plate numbers.
- The POC application should store the detected license plate numbers into a relational database. The record should capture the following data: toll booth ID, date & time, license plate text

## Notes ##
-	A license plate may contain extra texts in addition to the plate number. For simplicity, the POC application can concatenate all texts it detects from the image into a single line of string with space as delimiter.
-	The logic to capture toll booth ID is not important at this stage. The POC application can use any method to generate this data.

## Learning Modules ##
- xxx

## References ##
- [Transact-SQL reference (Database Engine)](https://learn.microsoft.com/en-us/sql/t-sql/language-reference?view=azuresqldb-current)
- [Create a Login for SQL Server](https://learn.microsoft.com/en-us/sql/relational-databases/security/authentication-access/create-a-login?view=azuresqldb-current)
- [Quickstart: Create a C# function in Azure using Visual Studio Code](https://learn.microsoft.com/en-us/azure/azure-functions/create-first-function-vs-code-csharp?tabs=in-process)
- [Connect Azure Functions to Azure Storage using Visual Studio Code](https://learn.microsoft.com/en-us/azure/azure-functions/functions-add-output-binding-storage-queue-vs-code?pivots=programming-language-csharp&tabs=in-process)
- [Quickstart: Computer Vision v3.2 GA Read](https://learn.microsoft.com/en-us/azure/cognitive-services/computer-vision/quickstarts-sdk/client-library?tabs=visual-studio&pivots=programming-language-csharp)
- [Use Azure Functions to connect to an Azure SQL Database](https://learn.microsoft.com/en-us/azure/azure-functions/functions-scenario-database-table-cleanup)
- [Quickstart: Create an integration workflow in multi-tenant Azure Logic Apps using the Azure portal](https://learn.microsoft.com/en-us/azure/logic-apps/quickstart-create-first-logic-app-workflow)
- [Reference guide to workflow expression functions in Azure Logic Apps and Power Automate](https://learn.microsoft.com/en-us/azure/logic-apps/workflow-definition-language-functions-reference)
