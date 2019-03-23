# Reproduction Android9 Design Editor Issue
Production of android 9 designer issue - ClassNotFoundException
steps:

1. create new project with navigation drawer, minimum 5.1 (sdk 22)
2. Change targeting to Android 9
3. Upgrade nuget package Xamarin.Android.Support.Design to v28.0.0
4. Rebuild project - failed, had to long path and project names
5. Changed names
6. Rebuild project - succeeded
7. Open designer file, see the below error.


![alt text](https://github.com/Ruud-cb/Reproduction_Android9_DesignIssue/blob/master/ErrorMessage.png?raw=true)

8. verified by closing VS, deleting bin, obj and .vs folder, open VS, rebuild succeeded and still seing the designer issue.


### Visual studio installed versions:

Microsoft Visual Studio Enterprise 2017 
Version 15.9.9
VisualStudio.15.Release/15.9.9+28307.518
Microsoft .NET Framework
Version 4.7.03056

Installed Version: Enterprise

#### Xamarin

Xamarin   4.12.3.80 (d15-9@914127c74)

Xamarin Designer   4.16.13 (45a16efd4)

Xamarin Templates   1.1.128 (6f5ebb2)

Xamarin.Android SDK   9.1.7.0 (HEAD/ba9da7a76)

Xamarin.Android Reference Assemblies and MSBuild support.

Xamarin.iOS and Xamarin.Mac SDK   12.2.1.15 (d60abd1)

Xamarin.iOS and Xamarin.Mac Reference Assemblies and MSBuild support.

#### Others

Visual C++ 2017   00369-90013-12410-AA733

ASP.NET and Web Tools 2017   15.9.04012.0

ASP.NET Core Razor Language Services   15.8.31590

ASP.NET Web Frameworks and Tools 2017   5.2.60913.0

Azure App Service Tools v3.0.0   15.9.03024.0

Azure Data Lake Node   1.0

Azure Data Lake Tools for Visual Studio   2.3.3000.2

Azure Functions and Web Jobs Tools   15.9.02046.0

Azure Stream Analytics Tools for Visual Studio   2.3.3000.2

C# Tools   2.10.0-beta2-63501-03+b9fb1610c87cccc8ceb74a770dba261a58e39c4a

Common Azure Tools   1.10

Conveyor by Keyoti   1.0

Extensibility Message Bus   1.1.49 (remotes/origin/d15-8@ee674f3)

Fabric.DiagnosticEvents   1.0

JavaScript Language Service   2.0

JavaScript Project System   2.0

JavaScript UWP Project System   2.0

JetBrains ReSharper Ultimate 2017.3.1    Build 111.0.20171221.145902

Microsoft Azure HDInsight Azure Node   2.3.3000.2

Microsoft Azure Hive Query Language Service   2.3.3000.2

Microsoft Azure Service Fabric Tools for Visual Studio   2.4

Microsoft Azure Stream Analytics Language Service   2.3.3000.2

Microsoft Azure Stream Analytics Node   1.0

Microsoft Azure Tools   2.9

Microsoft Continuous Delivery Tools for Visual Studio   0.4

Microsoft JVM Debugger   1.0

Microsoft Library Manager   1.0

Microsoft MI-Based Debugger   1.0

Microsoft Visual C++ Wizards   1.0

Microsoft Visual Studio Tools for Containers   1.1

Microsoft Visual Studio VC Package   1.0

MLGen Package Extension   1.0

Mono Debugging for Visual Studio   4.13.12-pre (9bc9548)

Node.js Tools   1.4.21001.1 Commit Hash:8dd15923800d931b153ab9e4de74e42a74eba5e6

NuGet Package Manager   4.6.0

ProjectServicesPackage Extension   1.0

Redgate ReadyRoll   1.17.18155.10346

Redgate SQL Prompt   9.2.0.5601

ResourcePackage Extension   1.0

ResourcePackage Extension   1.0

ResXManager   1.34.1869.0

Snapshot Debugging Extension   1.0

SQL Server Data Tools   15.1.61903.01040

Test Adapter for Boost.Test   1.0

Test Adapter for Google Test   1.0

ToolWindowHostedEditor   1.0

TypeScript Tools   15.9.20918.2001

TypeScript Tools for Microsoft Visual Studio

VersionChanger Extension   1.0

Visual Basic Tools   2.10.0-beta2-63501-03+b9fb1610c87cccc8ceb74a770dba261a58e39c4a

Visual F# Tools 10.2 for F# 4.5   15.8.0.0.  Commit Hash: 6e26c5bacc8c4201e962f5bdde0a177f82f88691.

Microsoft Visual F# Tools 10.2 for F# 4.5

Visual Studio Code Debug Adapter Host Package   1.0

Visual Studio Tools for CMake   1.0

Visual Studio Tools for CMake

Visual Studio Tools for Containers   1.0

Visual Studio Tools for Containers

Visual Studio Tools for Universal Windows Apps   15.0.28307.489

VisualStudio.Mac   1.0

Mac Extension for Visual Studio



