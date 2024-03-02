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

This addresses the challenge of ensuring consistency between the datasource template fields and the component's prop type, reducing the likelihood of errors.

### How it helps

It offers several benefits to developers working with Next.js and Sitecore JSON rendering items:

  1. Streamlined Component Generation
  2. Incorporation of Essential Fields
  4. Empowerment Through Automation
  5. Reduce Manual Effort in Development

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

Once you've completed the above setup,

1. Navigate to any folder in your renderings, then right-click on the component and choose --> Scripts. Generate Next.JS Component
![Step 1](docs/images/Step1.png?raw=true "Step 1")

2. Once you click, the scripts will be executed, and you will be able to see result in action.
![Step 2](docs/images/Step2.png?raw=true "Step 2")

3. Then you can simply copy and paste it into any of your favorite code platforms.

4. After that, the developer can adjust the code based on the design provide and can modified the html mark oin the fields.

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

