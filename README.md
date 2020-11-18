# das-github-template

This repo should be used as a template when creating new repos for the Apprenticeship Service

## Contents

* .github/CODEOWNERS - Defines required approvals for changes to files specified in the CODEOWNERS file
* azure/template.json - Azure ARM template should be used to provision resources on the Azure platform
* src/New-InitianlDotNetCoreProjects.ps1 - Creates project structure and adds project guids to the csproj files. Once the project structure has been created the script can be deleted.
* .gitignore - Intialised for Visual Studio
* azure-pipelines.yml - Azure Pipelines definition file
* GitVersion.yml - GitVersion configuration file
* LICENSE - License information file
* README.md - Populate with useful information about the repo, the projects it contains and how to get started.

### New-InitialDotNetCoreProjects.ps1

Projects created using this PowerShell script default to .NET Core 3.1 which is the latest LTS version supported by Microsoft and agreed for use in the service.

Example:

`.\New-InitialDotNetCoreProjects.ps1 -Prefix <project name> -ProjectType <project type>`

Supported project types are currently:

* mvc, web, webapp
* webapi
* console
* classlib
* function

# ProjectName

## Introduction

An introduction to the project goes here!

## Developer Setup

### Requirements

### Setup

### Config