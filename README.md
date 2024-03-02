# Sitecore Hackathon 2024

![Hackathon Logo](docs/images/hackathon.png?raw=true "Hackathon Logo")

## Team name

Guppy Hack Squad

## Category

Best Module for XM/XP or XM Cloud

## Description

### Purpose

This script facilitates the generation of a Next.js component file from a Sitecore JSON rendering item, providing a streamlined process for incorporating essential fields and parameters. By leveraging this script, users can create Next.js components with all the datasource template fields in the component prop type and these fields rendered on the screen, enhancing development efficiency. The common Headless SXA rendering parameters are also included when needed. This tool is designed to empower developers by automating the tedious aspects of component boilerplate creation, accelerating the time to market.

### Problem solved

### How it helps

### Capabilities

- Generate prop type
  - Generate comments for unsupported field types
- Generate render function skeleton with all fields
  - Generate comments for unsupported field types
- Generate the required import statements
  - Support common Headless SXA rendering parameters (Rendering ID, Grid parameters, Styles)

### Limitations

- Placeholders
- Extra rendering parameters
- Integrated GraphQL query
- Headless SXA variants

## Video link

⟹ Provide a video highlighing your Hackathon module submission and provide a link to the video. You can use any video hosting, file share or even upload the video to this repository. _Just remember to update the link below_

⟹ [Replace this Video link](#video-link)

## Pre-requisites and Dependencies

- Sitecore PowerShell Extensions (SPE)
- Sitecore Headless Services
- Sitecore Headless SXA

## Installation instructions

⟹ Write a short clear step-wise instruction on how to install your module.

> _A simple well-described installation process is required to win the Hackathon._  
> Feel free to use any of the following tools/formats as part of the installation:
> - Sitecore Package files
> - Docker image builds
> - Sitecore CLI
> - msbuild
> - npm / yarn
> 
> _Do not use_
> - TDS
> - Unicorn
 
for example:

1. Use the Sitecore Installation wizard to install the [package](#link-to-package)
2. ...
3. profit

## Usage instructions

⟹ Provide documentation about your module, how do the users use your module, where are things located, what do the icons mean, are there any secret shortcuts etc.

## Comments

If you'd like to make additional comments that is important for your module entry.

## Development

### Setup

1. In an ADMIN terminal:

    ```ps1
    .\init.ps1 -InitEnv -LicenseXmlPath "C:\path\to\license.xml" -AdminPassword "DesiredAdminPassword"
    ```

2. Restart your terminal and run:

    ```ps1
    .\up.ps1
    ```

