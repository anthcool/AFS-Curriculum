##### Developer training content put together for our development team at Associated Food Stores, Inc.
###### \*\**Channel content refers to custom arranged PluralSight course and external supplementary materials.*\*\*
---
# **[AFS IT Developer Curriculum Map](https://app.pluralsight.com/channels/details/8abdbc82-b0da-48ba-b8ee-669c3f7accac)**
### The main hub channel for AFS developers that comprises the various tools, concepts, languages, patterns, practices, and frameworks that are required knowledge to function and work in the AFS IT Development team.

#### Content you can skip is marked/suffixed with (***can skip***).

#### Table of Contents:

##### For all devs:
- [Getting Started](https://github.com/anthcool/AFS-Curriculum#getting-started)
- [The C# Language](https://github.com/anthcool/AFS-Curriculum#the-c-language)
- [Scripting with PowerShell](https://github.com/anthcool/AFS-Curriculum#scripting-with-powershell)
---
##### For specific devs:
- [Building for the Web](https://github.com/anthcool/AFS-Curriculum#building-for-the-web) (*for web devs*)
- [Building for Mobile Devices](https://github.com/anthcool/AFS-Curriculum#building-for-mobile-devices) (*for mobile devs*)
- [Building APIs](https://github.com/anthcool/AFS-Curriculum#building-apis) (*for API devs*)
---
##### For DevOps admins:
- [Azure DevOps Administration](https://github.com/anthcool/AFS-Curriculum#azure-devops-administration)
---
##### Supplementary content:
- [Helpful References](https://github.com/anthcool/AFS-Curriculum#helpful-references)

## [Getting Started](https://app.pluralsight.com/channels/details/a5878408-5c42-46a5-8f27-ee178d94b056)
### This channel contains links to tooling, documentation, and course materials to get you started developing applications.
- Downloads & Installs for Setting Up Your Development Environment Section
    - [Upgrade](https://www.microsoft.com/en-us/windows/windows-7-end-of-life-support-information) to Windows 10 (*using an Intel i7 CPU or better, 8GB+ RAM, w/a SSD if possible*)
    - [Download](https://www.microsoft.com/en-us/edge) New Chromium-based Microsoft Edge Browser (DO NOT USE Internet Explorer!)
    - [Visual Studio 2019 Professional](https://my.visualstudio.com/Benefits) (*Workloads to install: .NET Core cross-platform development, ASPNET and web development, Data storage and processing, Mobile development with .NET*)
    - [Pull Requests](https://marketplace.visualstudio.com/items?itemName=VSIDEVersionControlMSFT.pr4vs) for Visual Studio extension (*install this in VS 2019*)
    - [.NET Core SDK](https://dotnet.microsoft.com/download) (*download and install latest stable release*)
    - [Git](https://git-scm.com/) (*needed for version control while working with Azure Repos or repos via GitHub*)
    - [Visual Studio Code](https://code.visualstudio.com/) (*optional light-weight editor/IDE for those w/o a VS license or if desired*)
    - [C# extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp) for VS Code (*only need this if you are using VS Code*)
    - [Azure Repos extension](https://marketplace.visualstudio.com/items?itemName=ms-vsts.team) for VS Code (*only need this if you are using VS Code*)
    - [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download?view=sql-server-2017) (*option A:  will replace SSMS*)
    - [SQL Server Mgmt Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-2017) (*option B: older, heavier, slower*)
- [Visual Studio 2019](https://app.pluralsight.com/paths/skills/visual-studio-2019) Path

    Beginner:
    - What's New in VS 2019
    - VS 2019 Getting Started
    - VS 2019: Debugging
    ---
    Intermediate:
    - Using Git for Source Control in VS 2019
    - Testing .NET Code in VS 2019
    - Code Analysis in VS 2019
    - Migrating Apps and Services to Azure with VS 2019 (***can skip***)
    ---
    Advanced:
    - Play by Play: VS Live Share
    - Advanced Debugging w/VS 2019 (***can skip***)
    - Building Cloud-native Solutions for Azure w/VS 2019 (***can skip***)
- [Intro to Git & DevOps](https://app.pluralsight.com/channels/details/4b51cc20-92d4-47dc-b966-f4739bc5a5d3?s=1) Sub-channel
    - [Managing Source Code with Git](https://app.pluralsight.com/paths/skills/managing-source-code-with-git) Path
    
        Beginner:
        - Git: The Big Picture
        - Getting Started with Git
        ---
        Intermediate:
        - How Git Works
        - Working with Git Branches
        ---
        Advanced:
        - Mastering Git
        - Advanced Git Techniques
        - Git Administration
    - Using Git for Source Control in VS 2019
    - DevOps: The Big Picture

## [The C# Language](https://app.pluralsight.com/channels/details/61c4987e-b594-4c1c-92fa-082e0066e410)
### This channel helps you become proficient in the C# language, which is used for all kinds of development here at AFS.
- [Hello World](https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/tutorial-console?view=vs-2019): Create a simple C# console app in Visual Studio
- [C# Development Fundamentals](https://app.pluralsight.com/paths/skills/csharp) Path

    Beginner:
    - C# Fundamentals
    - C#: Using Variables and Conditionals
    - C#: Using Classes, Methods, Objects, and Loops
    - Beginning C# Collections
    - Object-Oriented Programming Fundamentals in C#
    - Add Features to Grade Book Application Using C#
    ---
    Intermediate:
    - C#: Using Linq Queries & Operators
    - LINQ Fundamentals
    - Dates and Times in .NET
    - Working with Nulls in C#
    - Error Handling in C# with Exceptions
    - Getting Started with Asynchronous Programming in .NET
    ---
    Advanced:
    - C# Interfaces
    - C# Extension Methods
    - C# Events, Delegates and Lambdas
    - Advanced C# Collections
    - C# Tips and Traps
    - C# Concurrent Collections
- [Consuming Data from an API](https://app.pluralsight.com/channels/details/710194ac-6b88-4ccd-b1aa-19fc62c9e2e2) Sub-channel
    - [C# Linq and Async Series](https://www.youtube.com/playlist?list=PLdo4fOcmZ0oXzJ3FC-ApBes-0klFN9kr9)
    - Getting Started with Asynchronous Programming in .NET
    - Using HttpClient to Consume APIs in .NET Core
    - [Serialize and deserialize JSON using C#](https://docs.microsoft.com/en-us/dotnet/standard/serialization/system-text-json-overview) (converting from JSON to C# objects and back again)
    - LINQ Fundamentals
- [C# Coding Practices](https://app.pluralsight.com/paths/skills/c-coding-practices) Path

    Beginner:
    - Clean Coding Principles in C#
    - Defensive Coding in C#
    ---
    Intermediate:
    - Refactoring for C# Developers
    ---
    Advanced:
    - SOLID Principles for C# Developers
- [C# Application Practices](https://app.pluralsight.com/paths/skills/c-application-design) Path

    Application Design Principles:
    - Clean Architecture: Patterns, Practices, and Principles
    - Getting Started with Dependency Injection in .NET
    ---
    C# Programming Paradigms:
    - Making Your C# Code More Object-Oriented
    - Applying Functional Principles in C# (***can skip***)
- [Design Patterns in C#](https://app.pluralsight.com/paths/skills/design-patterns-in-c) Path

    Behavioral:
    - *Various*
    ---
    Creational:
    - *Various*
    ---
    Structural:
    - *Various*
- Domain-Driven Design Fundamentals

## [Scripting with PowerShell](https://app.pluralsight.com/channels/details/a351a15f-80d1-4f46-b7f4-19d927f782d1?s=1)
### This channel teaches you all things PowerShell to help you automate tasks & understand configuration management skills through this powerful shell.
- [Windows PowerShell: Essentials](https://app.pluralsight.com/paths/skills/windows-powershell-essentials) Path

    Beginner:
    - PowerShell: Getting Started
    - Your First Day with PowerShell
    ---
    Intermediate:
    - Putting PowerShell to Work
    - PowerShell on the Network
    ---
    Advanced:
    - Automation with PowerShell Scripts
    - PowerShell Gotchas
- [Windows PowerShell: Scripting and Toolmaking](https://app.pluralsight.com/paths/skills/powershell-scripting-and-toolmaking) Path

    Beginner:
    - PowerShell Toolmaking Fundamentals
    - Building Advanced PowerShell Functions and Modules
    - Windows PowerShell Best Practices and Patterns
    ---
    Intermediate:
    - Reporting with PowerShell HTML and Enhanced HTML
    - Debugging PowerShell in VS Code
    - PowerShell Remoting Fundamentals
    - Accessing SQL Server Databases from PowerShell
    ---
    Advanced:
    - Building PowerShell GUIs in WPF for Free (***can skip***)
    - Testing PowerShell with Pester (***can skip***)
    - Infrastructure Testing with Pester (***can skip***)
    - Windows Workflows with PowerShell
    - Working with CSV Data in PowerShell
    - Working with XML Data in PowerShell

## [Building for the Web](https://app.pluralsight.com/channels/details/bf26bbfe-0cb5-4a51-a031-b09fe2d8e5d9)
### This channel will help teach you how to build for the web using both client and server-side technologies.
- [Client and Server Web Frameworks](https://app.pluralsight.com/channels/details/b11f0f26-c299-4ee5-bdb6-7132c873c0a0?s=1) Sub-channel
    - [Quick-start: Client-side Web Technologies](https://app.pluralsight.com/channels/details/39931d2e-bb2e-4b19-9ce2-f2c3149b2e47?s=1) Sub-channel
        - [Get set up to learn in VS Code](https://docs.microsoft.com/en-us/learn/modules/develop-web-apps-with-vs-code/)
        - [Frontend Masters Online Bootcamp](https://frontendmasters.com/bootcamp/)
        - Bootstrap 4 for the Developer
    - [ASP.NET Core](https://app.pluralsight.com/paths/skills/aspnet-core) Path
    
        Beginner:
        - ASPNET Core Fundamentals
        - Building Web Apps with ASPNET Core MVC (***can skip***)
        - Building an API with ASPNET Core (***can skip***)
        ---
        Intermediate:
        - Dependency Injection in ASPNET Core
        - Using Configuration and Options in .NET Core and ASPNET Core Apps
        - Effective Logging in ASPNET Core
        - ASPNET Core 3.0: The MVC Request Life Cycle (***can skip***)
        - Improving .NET Core MVC Apps Using Extension Points (***can skip***)
        ---
        Advanced:
        - Understanding ASPNET Core Security
        - Getting Started with ASPNET Core SignalR
        - ASPNET Core Tag Helpers and View Components
        - ASPNET Core Health Checks
    - Undertanding ASPNET Core 3.x
    - [Building Web Applications with Blazor](https://app.pluralsight.com/paths/skills/building-web-applications-with-blazor) Path
        
        Beginner:
        - Blazor: The Big Picture
        - Blazor: Getting Started
        ---
        Intermediate:
        - Designing and Building Enterprise Blazor Applications
        - Authentication and Authorization in Blazor Applications
        ---
        Advanced:
        - Creating Blazor Components
        - JavaScript Interop in Blazor Applications
    - Blazor for the Web Forms Developer: DEVintersection 2019
    - Securing Application Secrets in ASPNET Core
- [Securing Web Apps with Azure Active Directory](https://app.pluralsight.com/channels/details/53aa60cc-4e0f-4c4c-a856-be6ddd91ac35?s=1) Sub-channel
    - Getting Started with Azure Active Directory for Developers
    - Building Authorization in Azure Active Directory for Developers
    - Developing Web Applications and Web APIs Protected by Azure Active Directory

## [Building for Mobile Devices](https://app.pluralsight.com/channels/details/539e8644-3393-463d-a402-6d95624dc843)
### This channel helps teach you to use Xamarin.Forms to build native Android and iOS applications from a shared code-base using C# / .NET.
- MSFT Learn | Xamarin Courses ([suggested learning order](https://gist.github.com/anthcool/a8c6dde5f0f14124b2e6ccb37db2aaad))
- MSFT Learn | [Xamarin Courses](https://docs.microsoft.com/en-us/learn/browse/?products=xamarin)
- [Building Cross-Platform Apps with Xamarin Forms](https://app.pluralsight.com/paths/skills/building-cross-platform-apps-with-xamarin-forms) Path

    Beginner:
    - Xamarin Forms: The Big Picture
    - Introduction to Xamarin Forms
    ---
    Intermediate:
    - Building Xamarin Forms Applications with XAML
    - Data Binding in Xamarin Forms
    - Getting Started with Xamarin Essentials in Xamarin Forms
    - Creating List-based Screens in Xamarin Forms
    - Using the Xamarin Forms Shell
    - Working with Local Data in Xamarin Forms
    - Integrating Google Maps into Xamarin Forms Apps (***can skip***)
    - Building an Enterprise Mobile Application with Xamarin Forms
    - Xamarin Forms Localization (***can skip***)
- Add ASPNET Core's [Dependency Injection](https://montemagno.com/add-asp-net-cores-dependency-injection-into-xamarin-apps-with-hostbuilder/) to your Xamarin.Forms Apps

## [Building APIs](https://app.pluralsight.com/channels/details/32cdb759-f282-4bd2-abb9-5ed588b27c09)
### This channel helps teach you how to build REST-based asynchronous APIs with ASPNET Core and Entity Framework Core.
- [API Development in ASP.NET Core](https://app.pluralsight.com/paths/skills/api-development-in-aspnet-core) Path
    
    Beginner:
    - Designing RESTful Web APIs
    - Building a RESTful API with ASPNET Core 3
    - Implementing Advanced RESTful Concerns with ASPNET Core 3
    ---
    Intermediate:
    - Documenting an ASPNET Core API with OpenAPI/Swagger
    - Building an Async API with ASPNET Core
    - Using OpenAPI/Swagger for Testing and Code Generation in ASPNET Core
    ---
    Advanced:
    - Building GraphQL APIs with ASPNET Core (***can skip***)
- [Querying Data with T-SQL from SQL Server](https://app.pluralsight.com/paths/skills/querying-data-with-t-sql-from-sql-server) Path
    
    Beginner:
    - Querying Data Using T-SQL
    - Combining and Filtering Data with T-SQL
    ---
    Intermediate:
    - T-SQL Data Manipulation Playbook
    - Capturing Logic with Stored Procedures in T-SQL
    - T-SQL Functions Playbook
    ---
    Advanced:
    - Querying JSON, XML, and Temporal Data with T-SQL
    - Handling Errors in T-SQL

## [Azure DevOps Administration](https://app.pluralsight.com/channels/details/4a5cfda4-7b6d-40bd-b078-3cc56fca503d)
### Learn the basics of utilizing Azure DevOps Services to understand their part in the administration of our company's software development life cycles (SDLCs).
- [MSFT Learn | Azure DevOps Intro Learning Paths](https://docs.microsoft.com/en-us/learn/browse/?resource_type=learning%20path&products=azure-devops)
- [Microsoft Azure DevOps Engineer (AZ-400)](https://app.pluralsight.com/paths/certificate/microsoft-azure-devops-engineer-az-400) Path
    
    Implement DevOps Development Processes:
    - Microsoft Azure DevOps Engineer: Implement a Secure and Compliant Development Process
    - Microsoft Azure DevOps Engineer: Implement and Manage Azure Pipelines Infrastructure
    - Continuous Delivery and DevOps with Azure DevOps: Source Control with Git
    - Feature Toggles, Package Management and Versioning with Azure DevOps
    ---
    Implement Continuous Inetgration:
    - Microsoft Azure DevOps Engineer: Creating an Automated Build Workflow
    - Application Testing with Azure DevOps and Visual Studio 2019
    - Microsoft Azure DevOps Engineer: Monitoring Code Quality
    ---
    Implement Continuous Delivery:
    - Continuous Delivery and DevOps with Azure Devops: Release Pipelines
    - Microsoft Azure DevOps Engineer: Manage and Modularize Tasks and Templates
    - Microsoft Azure DevOps Engineer: Selecting and Implementing an Appropriate Deployment
    ---
    Implement Dependency Management:
    - Microsoft Azure DevOps Engineer: Inspecting and Identifying Code Dependencies
    - Inspecting Open Source Software Packages for Security and License Compliance
    ---
    Implement Application Infrastructure:
    - Microsoft Azure DevOps Engineer: Leveraging ARM Templates for Infrastructure
    - Microsoft Azure DevOps Engineer: Manage Azure Kubernetes Services Infrastructure
    - Microsoft Azure DevOps Engineer: Implementing Infrastructure Control and Compliance
    - Microsoft Azure DevOps Engineer: Provision Azure Resources
    - Microsoft Azure DevOps Engineer: Implement Imperative Virtual Machine Configuration Management
    ---
    Implement Continuous Feedback:
    - Microsoft Azure DevOps Engineer: Recommend and Design System Feedback Mechanisms
    - Microsoft Azure DevOps Engineer: Route System Feedback to Development Teams
    - Microsoft Azure DevOps Engineer: Optimize Feedback Mechanisms

---
## [Helpful References](https://app.pluralsight.com/channels/details/b385941c-b3c8-4973-a9b2-881a2bd45708)
### This channel contains a lot of helpful links to online tools, documentation, code examples, book suggestions, and other supplemental material to aid you throughout the curriculum.
- Legacy Code at AFS Section
    - [Working with Legacy Code](https://app.pluralsight.com/channels/details/6f655fbe-31f1-45ef-bccc-943d5814cb4f) Sub-channel
        - VBNET Fundamentals
        - Intro to ASPNET 4 WebForms
        - Intro to ASPNET Web Services
        - Querying Data with T-SQL from SQL Server Path
---
- Staying Current in Technologies Section
- Documentation Sites Section
- C# and NET Core Section
- Client-side Web Development Section
- ASPNET Core Development Section
- Mobile Development with Xamarin Forms Section
- Working with APIs and API Development Section
- Azure DevOps Administration Section

