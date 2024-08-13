# Introduction

## Lab 1: Basic usage and introduction to UML Models and Diagrams

What we want to achieve in this lab a short introduction how to use DevOps Model Architect. You will get an overview how to use the Modeling Perspective and a simple intro into UML Models and Diagrams.

### Switch to Modeling Perspective

1. After a fresh installation of Eclipse you will get the Welcome Page
   1. ![Welcome Page](images/0000_Eclipse_Welcome.png)
2. Next switch to the Modeling Perspective
   1. Click on the Menu "Window" on top of Eclipse
   2. ![Menu Window](images/0000_1_Perspective.png)
   3. Click on Open Perspective then on Other
   4. ![Open Perspective Other](images/0000_2_Perspective.png)
   5. Dialog opens with list of perspectives
   6. ![Open Perspective Other](images/0000_3_Perspective.png)
   7. Scroll down and Select "Modeling" from the list
   8. ![Open Perspective Other](images/0000_4_Perspective.png)
   9. The Modeling Perspetive opens. You can also switch Perspectives using the icon on the top right corner
   10. ![Open Perspective Other](images/0000_5_Perspective.png)

### Create a project

1. Click on Create a new Model Project or Create Project
   1. ![Create a new Project](images/0001_1_Create_Model_Project.png)
   2. ![Create a new Project](images/0001_1_Create_Project.png)
2. In the case you selected "Create a Project" a wizard will be shown.
3. Search and select the modeling project type
   1. ![Select Projecttype](images/0001_2_SelectProjectType.png)
   2. ![Select Modelingproject](images/0001_3_ModelingProject.png)
4. Provide a name for your new project.
   1. ![Projectname](images/0001_4_ProjectName.png)
5. Select "General" from Categegories and "Blank Package" from Templates
   1. ![BlankPackage](images/0001_5_BlankPackage.png)
6. Have a look at your freshly created new Project
   1. ![Freshly created Project](images/0001_6_NewlyCreatedProject.png)

### Basic UML Models and Basic UML Diagrams

1. If Project is collapsed, click on the > symbols to uncollapse Project and Elements
   1. ![Project Explorer](images/0001_7_project_explorer.png)
   2. ![Uncollapse Project](images/0001_8_uncollapse_project.png)
   3. ![Uncollapse Models](images/0001_9_uncollapse_models.png)
2. Add new Class to Model by right clicking the Package and select the class entry in the UML menu
   1. ![Right Click on Package](images/0002_1_add_uml_element.png)
   2. ![Right Click on Package](images/0002_2_add_class.png)
3. This creates a fresh new class. Name this new class "Customer"
   1. ![Newly created class](images/0002_3_newly_created_class.png)
   2. ![name class Customer](images/0002_4_name_class.png)
4. Next add a new attribute to this class using the context menue of the element and name it "custID"
   1. ![add attribute to class](images/0002_5_add_attribute_to_class.png)
   2. ![newly created attribute](images/0002_6_newly_created_attribute.png)
   3. ![name attribute](images/0002_7_name_attribute.png)
5. Now create an additional attribute and name it "custName"
   1. ![name attribute](images/0002_8_add_another_attribute_and_name.png)
6. Create a new Diagram to manage all customer related model artifacts and name it "CustomerStore_Class"
   1. ![create new diagram for customer](images/0003_1_add_class_diagram.png)
   2. ![newly created diagram](images/0003_2_newly_created_diagram.png)
   3. ![name the new diagram](images/0003_3_name_diagram.png)
7. Add our "Customer" class to this diagram by using the context menue of the item
   1. ![add class to diagram using context menu](images/0003_4_add_existing_class_to_diagram.png)
   2. ![class is added to diagram](images/0003_5_existing_class_added.png)
8. Don't forget to save all your changes!

### How to import existing artifacts

1. Right click Project to open context menu and select Import
   1. ![Context Menue for importing](images/0004_1_ImportArtifact.png)
2. In this lab we want to import from the filesystem, please select "file system" in the wizard dialog
   1. ![Wizard - select "file system"](images/0004_2_ImportFileSystem.png)
   2. click on Next
3. In the file system dialog browse for the "Simple-Model" folder from your repository
   1. ![File System dialog](images/0004_3_SelectDirectory_1.png)
   2. click on Browse and select "Simple-Model"
   3. ![Select folder](images/0004_3_SelectDirectory_2.png)
   4. click on Open
4. The Import dialog opens
   1. ![Import Simple-Model](images/0004_4_ImportModel_1.png)
5. Select the folder on the left (checkbox) and the model element will be automatically selected.
   1. ![Import Simple-Model folder selected](images/0004_4_ImportModel_2.png)
6. Click on Finish to start the import
7. The modeling artifact is imported and "SimpleUMLModel" is shown.
   1. ![Import Result](images/0004_5_ImportResult.png)
8. Doublelick on the newly created Model and a migration dialog will open as the artifacts were created with older version.
   1. ![Profile Migration 1](images/0004_6_OpenModel_1.png)
   2. Just accept the default settings and the diagram will be opened
   3. ![open simple model 1](images/0004_6_OpenModel_2.png)
9. To have a better view, right click on the canvas to open context menue ans select "Arrange All"
   1. ![Arrange on canvas](images/0004_6_OpenModel_3.png)
   2. ![result of new arrangement](images/0004_6_OpenModel_4.png)

### How to add a new UML artifact to existing diagram

1. Adding new UML artifacts to a diagram can be done by using the "Palette" or the context menue of the diagram.
2. First we will use the "Palette"
   1. On the right side of DevOps Model Architect you will find the "Palette" menue.
   2. Click on "Class" entry to get all UML class types available
      1. ![Add new Class from Palette](images/0004_7_AddModelElement_1.png)
   3. Drag and drop the "Class" element from the Palette to the open diagram.
   4. A fresh new class is added and the name is selected for change. Change the name to "APPF2"
      1. ![new class and name](images/0004_7_AddModelElement_2.png)
   5. Now we want to create a relationship from "APPF2" to "AppFunction1"
      1. click and drag the "incomming" icon to "AppFunction1"
      2. ![new class and name](images/0004_7_AddModelElement_3.png)
      3. ![new class and name](images/0004_7_AddModelElement_4.png)
   6. A new dialog opens and use "Create Instance" type
      1. ![new relation](images/0004_7_AddModelElement_5.png)
   7. The relation "create instance" is established between these two elements
      1. ![final relation](images/0004_7_AddModelElement_6.png)
   8. Do not forget to save your changes!

## Conclusion of Lab 1

In this Lab we have been introduced how to use DevOps Model Architect to create a project, work on simple diagrams and import existing artifacts.
