# das-github-template

This repo should be used as a template when creating new repos for the Apprenticeship Service

## Contents

### azure/template.json
Azure ARM template should be used to provision resources on the Azure platform

### New-InitialDotNetCoreProjects.ps1

Projects created using this PowerShell script default to .NET Core 3.1 which is the latest LTS version supported by Microsoft and agreed for use in the service.

Example:

`.\New-InitialDotNetCoreProjects.ps1 -Prefix <project name> -ProjectType <project type>`

The PowerShell script creates the project structure and adds project guids to the csproj files for use with SonarCloud.

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