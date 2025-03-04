# Chapter 2.0 - Get familiar with SAPUI5 Adaptation Project Generator

By the end of this chapter you will have generated Adaptation Project which will be needed for the upcoming steps.

## Start the Adaptation Project Wizard 
   1. Log onto SAP Business Application Studio (BAS) and access your SAP Fiori development space.

   2. Click the menu icon -> New Project from Template, select SAPUI5 Adaptation Project template, and choose the Start button.
<img src="img/template-wizard.png" width="800">

## Create Apdaptation Project
After the wizard is started there are several steps that needs to be completed in order to create Adaptation Project.

### 1. Configuration

   1. Enter the Configuration information required for your adaptation project:
         - From the Select System dropdown list select the system you want to use.
         - From the dropdown list in the Select Application field, choose "Demo App for Travel V2 (sap.demo.travel.v2)" the SAP Fiori application that will be as the basis for your application variant.
         - To enhance the application with additional capabilities and logic, you need to select the No option in answer to Enable Safe Mode?
   2. Press the Next button.
<img src="img/configuration.png" width="1000" />

### 2. Basic Information

   1. Enter the Basic Information required for your adaptation project:
      - Project name: uniquely identifiable name "demo.travel.appvar.{your unique number}"
      - Application title: uniquely identifiable name "Demo Travel {your unique number}"
      - Project folder path: choose the project folder from the current opened workspace in the which the project should be created. 
   2. Press the Finish button.
<img src="img/basic-information.png" width="1000" />

As soon as your SAPUI5 Adaptation Project has been created, the following message is displayed “The project has been generated and will be saved for future use.” You can view the adaptation project when you open the folder specified in Basic Information step.

## Add Fiori Launchpad and Deploy configurations.

After the project is generated. We should add Fiori Launchpad and Deploy configurations to the already created Adaptation Project.


   NOTE: If you had difficulties in creating package and transport request from [Chapter 1.3](/chapters/1.3-create-package-adt/) you can use the following data:
   - Package: Z_UI5CON_HANDSON
   - Transport Request: TRLK911207
  
   <img src="img/deployment-configuration.png" width="1000" />
   





Continue to [Chapter 3.0 - Get familiar with Control Property Editor!](/chapters/3.0-get-fam-with-cpe/)
