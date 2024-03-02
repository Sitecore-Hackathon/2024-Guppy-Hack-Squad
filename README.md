# Sitecore Hackathon 2024

![Hackathon Logo](docs/images/hackathon.png?raw=true "Hackathon Logo")

## Team name

Guppy Hack Squad

## Category

Best Module for XM/XP or XM Cloud

## Description

### Purpose

This script facilitates the generation of a Next.js component file from a Sitecore JSON rendering item, providing a streamlined process for incorporating essential fields and parameters. By leveraging this script, users can create Next.js components with all the datasource template fields in the component prop type and these fields rendered on the screen, enhancing development efficiency. The common Headless SXA rendering parameters are also included when needed. This tool is designed to empower developers by automating the tedious aspects of component boilerplate creation, accelerating the time to market.

### Initial Problems

- Ensuring the consistency between the datasource template fields and the component's prop type is time consuming.
- Writing all the boilerplate code for a new component is time consuming when the datasouce template has many fields.

### How it helps

It offers several benefits to developers working with Next.js, JSS, and Headless SXA with Sitecore JSON rendering items:

  1. Streamlined Component Generation
  2. Incorporation of Essential Fields
  3. Empowerment Through Automation
  4. Reduce Manual Effort in Development
  5. Reducing the Likelihood of Errors
  6. Time Saving

### Capabilities

- Generate prop type from datasource template fields
  - Generate comments for unsupported field types
- Generate render function skeleton with all the datasource template fields
  - Generate comments for unsupported field types
- Generate the required import statements
- Support for common Headless SXA rendering parameters
  - Rendering ID
  - Grid parameters
  - Styles
- Support for `withDatasourceCheck()` HOC

### Limitations

- Does not generate placeholders code
- Does not generate code for extra rendering parameters
- Does not support JSON rendering integrated GraphQL query
- Does not generate code for all the headless SXA variants of a rendering

## Video link

[Check out the video on YouTube](https://youtu.be/pnwKSHv-_bU)

## Pre-requisites and Dependencies

Either:

- A Sitecore 10.3.1 XM/XP instance with the following modules pre-installed:
  - Sitecore PowerShell Extensions (SPE)
  - Sitecore Headless Services
  - Sitecore Headless SXA
- A Sitecore XM Cloud instance

## Installation instructions

1. Download the ["Nextjs-Component-Generator-1.0.zip" package](https://github.com/Sitecore-Hackathon/2024-Guppy-Hack-Squad/releases/download/v1.0.0/Nextjs-Component-Generator-1.0.zip)
2. In your dowloads folder, open the properties of the "Nextjs-Component-Generator-1.0.zip" file

   ![File explorer](docs/images/fileexplorer.png?raw=true "File explorer")

3. If there is an "Unblock" checkbox in the bottom right corner, ensure it is checked, then click the "OK" button.

   ![Unblock](docs/images/unblock.png?raw=true "Unblock")

4. Use the Sitecore Installation wizard to install the downloaded package.

## Usage instructions

Once you've completed the above setup,

1. In the Content Editor, navigate to a JSON rendering item.
2. Right-click on the item.
3. Open the "Scripts" context menu.
4. Click on the "Generate Next.js Component" context menu item.

   ![Step 1](docs/images/Step1.png?raw=true "Step 1")

5. The generated code will be displayed in a dialog.

   ![Step 2](docs/images/Step2.png?raw=true "Step 2")

6. Note the component file name and location above the generated code.
7. Copy the generated code in your clipboard.
8. In your front-end project code editor, create the new TSX file at the suggested location.
9. Paste the generated code into your new file.
10. Adjust the code based on your designs and modify the HTML markup around the fields.

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
