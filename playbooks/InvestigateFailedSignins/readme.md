# Copilot-For-Security-Investigate-FailedSignins

## Overview
This playbook stands as a cornerstone in our security operations, dedicated to identifying users with multiple failed sign-ins and conducting in-depth investigations into associated IP addresses using threat intelligence sources. In addition to this, it meticulously analyzes various risk factors linked to the user, including their membership group status, device compliance, and other pertinent issues

## Pre-deployment Instructions

Prior to beginning the installation process, it's crucial to confirm that you have met the following prerequisites:
• The user that will deploy this Logic app need to have a Contributor Role.
• You enabled the Security Copilot license on your tenant
• The user authenticated within the CoPilot logic app action and has permission to send emails.
Define the email you want the daily logic app to be sent too

## Deployment

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FKwachSean%2FSecurityCopilot%2Fmain%2Fplaybooks%2FThreatBulletinCopilot%2Fazuredeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>

</a>


### Post-Deployment Instructions

1. Select the freaquency on how many times you want the Logic App to run 
2. Authenticate the Copilot Prompts with a User that has Access to Security Copilot 
3. Proceed to run the Logic app and Prepare for the results 

