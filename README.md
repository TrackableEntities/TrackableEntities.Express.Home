# Trackable Entities Express Home

**TrackableEntities.Express** is a re-write of the Trackable Entities project that includes both **C#** and **JavaScript** client and server libraries with support for **EF7** (Entity Framework for .NET Core) and possibly some **NoSQL** persistence frameworks.

This is where we'll begin initial discussions of design goals and how we're going to re-architect Trackable Entities for greater simplicity, modularity, extensibility and portability.

*Why a re-write?*  The original version of Trackable Entities was intended to provide both client and server libraries to support change tracking across service boundaries, as well as a set of T4 templates for generating entities from existing database schemas and Visual Studio extensions for building end-to-end solutions with multi-project templates.  The aim was to allow developers to create complete solutions with just a few clicks, both to make them more productive and also to help them learn some best practices for building n-tier apps with Entity Framework with EF and either WCF or ASP.NET Web API.

This was a lofty goal and required as much effort to build the tooling as it did to build the framework libraries.  However, much as changed over the past few years in the world software development, especially with the arrival of a cross-platform, cloud-friendly version of the .NET Framework called **.NET Core**, and also with the advance of next-generation JavaScript frameworks, such as **Angular 2** and **Aurelia**, and ability to develop .NET apps using a lightweight editor such as SublimeText or Visual Studio Code.

Trackable Entities needs to respond to these changes, and it provides an opportunity to sit back and ponder lessons learned from what we've done so far and do some things differently this time around.

To launch the discussion of **TrackableEntities.Express**, I'll create a Wiki on this Home repo, where I'll lay out a roadmap and some design goals.  Please jump in a contribute your ideas and suggestions!
