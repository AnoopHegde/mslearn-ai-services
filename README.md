# mslearn-ai-services
Lab files for Azure AI Services modules

# Lab1: Get Started with Azure AI Services
  -  AI -102T00 A Designing and Implementing a Microsoft Azure AI Solution

  1. Login to Azure portal https://portal.azure.com
  2. Create a new Resource group  ->  AzureAI-RG
  3. Navigate to Azure AI Services -> Create an Azure AI Services multi-service account

     Subscription
     ResourceGroup: AzureAI-RG
     Region:    westeurope
     Name   :   npd-azureai
     Pricing Tier : standard 50
  4. Select the required checkbox and select all the default configuration.
  5. Deploy the New Azure AI Services.
  6. copy the keys and API's

     KEY1: a7ed6e41502941abb077da5d7c856e4d
     KEY2: a85ae8cb0a524cdeaa485f0f129cb5bb
     Location: westeurope
     API: https://npd-azureai.openai.azure.com/

  7. Navigate to code -> LabFiles -> 01-use-azure-ai-services
     Note: Run either in dotnet C# or Python

     C#:  appsetting.json
     Python: .env

     code
     C# Program.cs
     Python: rest-client.py

  8. cd Python -> pip install python-dotenv && python rest-client.py 
  9. Update the newly created keys and API's under  rest-client folder 
  10. open rest-client folder as integrated terminal and run the above commands  