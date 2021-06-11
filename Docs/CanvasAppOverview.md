# Power Apps Canvas App

Purpose of this app is to foster teamwork by letting owners-to-be of Microsoft Teams teams make smarter decisions on how a team can work in Teams. Usually, a business consultant would talk a team through assets that are available in Teams and Microsoft 365 and answer all question with 'it depends'. They would explain that people usually 

* confuse chat with task assignment "could you please"
* confuse email with status reports "per my last email"
* confuse SharePoint with a dumpster for any file in the world "can you migrate this pile of mess to someone else's computer?"

and show them what channels are made for, how a team can work with metadata on files and how stying on track works with Microsoft Lists. The Business consultant would ask them if they wanted more learning material pinned to their brand new team and if they wanted the team of they dreams already be created for them, so that it works from Day 1. 

This is, what Provisiongenie does: 

## High level overview on what the Canvas App does

* Short upskilling nuggets in Pop Ups so that owner can make informed decisions on channels, metadata and tools to use
* Questionnaire to get information on 
  * Teams Name, Teams Description and logged in User to provision the Team itself
  * Channels 
  * Name of SharePoint list & columns 
  * Name of SharePoint library & columns 
  * if Owner additionally wants a SharePoint list for taskmanagement and a "Welcome package"
* Patch 5 Dataverse tables with the information we got by user

## How do I get the app? 

* To get the entire solution as-is, please head over to our Deployment Guide
* To contribute to it, please see our [Contribution Guide](https://github.com/ProvisionGenie/ProvisionGenie/blob/main/CONTRIBUTING.md)
* If you like to reverse-engineer it, please take [this basic documentation](https://github.com/ProvisionGenie/ProvisionGenie/blob/main/Docs/HowToBuildTheCanvasApp) as a first start. Please note, that this is not a full tutorial on how to rebuild the canvas app, but it should explain how things work on a high level. 
* You can also download the .msapp file from here and import this app into your environment - please note that this won't give you the full experience, as the entire process of provisioning does not run in this canvas app but in Azure Logic Apps flows which get triggered by new rows in different tables in Dataverse.
