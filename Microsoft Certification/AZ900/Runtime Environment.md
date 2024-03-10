A Runtime Environment is a software or instructions that are executed while your program is running. A runtime generally means **what programming language and libraries and framework you are using.**

A runtime for Azure App Services will be a predefined container that has your programming language and commonly used library for that language installed.

Azure App Services will generally have multiple versions of a programming language, but it's common for a cloud provider to stop supporting older versions so you keep current and forces customer to keep good security practices by having latest patches.

Some examples of runtime would be:
- .NET;
- .NET Core;
- Java;
- Ruby;
- Node.js;
- PHP;
- Python.

But if your runtime isn't in one of the predefined options, Azure App Service **allows you to define custom containers**. You create your own Docker Container, put it on Azure Container Registry and then deploy your container Image to Azure App Service.