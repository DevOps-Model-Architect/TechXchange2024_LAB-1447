# Lab 1

## Basic usage and introduction to UML Models and Diagrams

What we want to achieve in this lab a short introduction how to use DevOps Model Architect. You will get an overview how to use the Modeling Perspective and a simple intro into UML Models and Diagrams.

### Start DevOps Model Architect and Switch to Modeling Perspective

1. Doubleclick on the icon for "IBM DevOps Model Architect" on the Desktop

   ![dma](images/Lab_0/0000_0_1_Desktop_1.png)

2. Select a workspace folder for Eclipse. You can for example call it `dma_workspace_YOURNAME`.

   ![Eclipse Workspace Dialog](images/Lab_1/0000_1_Workspace_Dialog.png)

3. The first time you open a new workspace you will get the Welcome Page. Close it by pressing the **Workbench** button in the upper right corner.

   ![Welcome Page](images/Lab_1/0000_1_Eclipse_Welcome.png)

4. Next switch to the Modeling Perspective
   1. Click on the Menu "Window" on top of Eclipse

      ![Menu Window](images/Lab_1/0000_1_Perspective_1.png)

   2. Click on Open Perspective then on Other

      ![Open Perspective Other](images/Lab_1/0000_1_Perspective_2.png)

   3. Dialog opens with list of perspectives

      ![Open Perspective Other](images/Lab_1/0000_1_Perspective_3.png)

   4. Scroll down and Select "Modeling" from the list

      ![Open Perspective Other](images/Lab_1/0000_1_Perspective_4.png)

   5. The Modeling Perspetive opens. You can also switch Perspectives using the icon on the top right corner

      ![Open Perspective Other](images/Lab_1/0000_1_Perspective_5.png)

### Create a project

1. Click on Create a new Model Project or Create Project

   ![Create a new Project](images/Lab_1/0001_1_Create_Model_Project.png)

   ![Create a new Project](images/Lab_1/0001_1_Create_Project.png)

2. In the case you selected "Create a Project" a wizard will be shown.
3. Search and select the modeling project type

   ![Select Projecttype](images/Lab_1/0001_2_SelectProjectType.png)

   ![Select Modelingproject](images/Lab_1/0001_3_ModelingProject.png)

4. Provide a name for your new project.

   ![Projectname](images/Lab_1/0001_4_ProjectName.png)

5. Select "General" from Categegories and "Blank Package" from Templates

   ![BlankPackage](images/Lab_1/0001_5_BlankPackage.png)

6. Have a look at your freshly created new Project

   ![Freshly created Project](images/Lab_1/0001_6_NewlyCreatedProject.png)

### Basic UML Models and Basic UML Diagrams

1. If Project is collapsed, click on the > symbols to expand Project and Elements

   ![Project Explorer](images/Lab_1/0001_7_project_explorer.png)

   ![Uncollapse Project](images/Lab_1/0001_8_uncollapse_project.png)

   ![Uncollapse Models](images/Lab_1/0001_9_uncollapse_models.png)

2. Add new Class to Model by right clicking the Package and select the class entry in the UML menu

   ![Right Click on Package](images/Lab_1/0002_1_add_uml_element.png)

   ![Right Click on Package](images/Lab_1/0002_2_add_class.png)

3. This creates a fresh new class. Name this new class "Customer"

   ![Newly created class](images/Lab_1/0002_3_newly_created_class.png)

   ![name class Customer](images/Lab_1/0002_4_name_class.png)

4. Next add a new attribute to this class using the context menu of the element and name it "custID"

   ![add attribute to class](images/Lab_1/0002_5_add_attribute_to_class.png)

   ![newly created attribute](images/Lab_1/0002_6_newly_created_attribute.png)

   ![name attribute](images/Lab_1/0002_7_name_attribute.png)

5. Now create an additional attribute and name it "custName"

   ![name attribute](images/Lab_1/0002_8_add_another_attribute_and_name.png)

6. Create a new Diagram to manage all customer related model artifacts and name it "CustomerStore_Class"

   ![create new diagram for customer](images/Lab_1/0003_1_add_class_diagram.png)

   ![newly created diagram](images/Lab_1/0003_2_newly_created_diagram.png)

   ![name the new diagram](images/Lab_1/0003_3_name_diagram.png)

7. Add our "Customer" class to this diagram by using the context menu of the item

   ![add class to diagram using context menu](images/Lab_1/0003_4_add_existing_class_to_diagram.png)

   ![class is added to diagram](images/Lab_1/0003_5_existing_class_added.png)

8. Don't forget to save all your changes!

### How to import existing artifacts

1. Right click Project to open context menu and select Import

   ![Context Menue for importing](images/Lab_1/0004_1_ImportArtifact.png)

2. In this lab we want to import from the filesystem, please select "file system" in the wizard dialog

   ![Wizard - select "file system"](images/Lab_1/0004_2_ImportFileSystem.png)

   click on **Next**
3. In the file system dialog browse for the "Simple-Model" folder from your repository

   ![File System dialog](images/Lab_1/0004_3_SelectDirectory_1.png)

   click on **Browse** and select "Simple-Model"

   ![Select folder](images/Lab_1/0004_3_SelectDirectory_2.png)

   click on **Open**
4. The Import dialog opens

   ![Import Simple-Model](images/Lab_1/0004_4_ImportModel_1.png)

5. Select the folder on the left (checkbox) and the model file will be automatically selected.

   ![Import Simple-Model folder selected](images/Lab_1/0004_4_ImportModel_2.png)

6. Click on **Finish** to start the import
7. The modeling artifact is imported and "SimpleUMLModel" is shown.

   ![Import Result](images/Lab_1/0004_5_ImportResult.png)

8. Double-click on the newly created Model and a migration dialog will open as the artifacts were created with older version.

   ![Profile Migration 1](images/Lab_1/0004_6_OpenModel_1.png)

   Just accept the default settings and the diagram will be opened

   ![open simple model 1](images/Lab_1/0004_6_OpenModel_2.png)

9. To have a better view, right click on the canvas to open context menu and select "Arrange All"

   ![Arrange on canvas](images/Lab_1/0004_6_OpenModel_3.png)

   ![result of new arrangement](images/Lab_1/0004_6_OpenModel_4.png)

### How to add a new UML artifact to existing diagram

1. Adding new UML artifacts to a diagram can be done by using the "Palette" or the context menue of the diagram.
2. First we will use the "Palette"
   1. On the right side of DevOps Model Architect you will find the "Palette" menue.
   2. Click on "Class" entry to get all UML class types available

      ![Add new Class from Palette](images/Lab_1/0004_7_AddModelElement_1.png)

   3. Drag and drop the "Class" element from the Palette to the open diagram.
   4. A fresh new class is added and the name is selected for change. Change the name to "APPF2"

      ![new class and name](images/Lab_1/0004_7_AddModelElement_2.png)

   5. Now we want to create a relationship from "APPF2" to "AppFunction1"
      1. click and drag the "incoming" icon to "AppFunction1"

      ![new class and name](images/Lab_1/0004_7_AddModelElement_3.png)

      ![new class and name](images/Lab_1/0004_7_AddModelElement_4.png)

   6. A new dialog opens and use "Create Instance" type

      ![new relation](images/Lab_1/0004_7_AddModelElement_5.png)

   7. The relation "create instance" is established between these two elements

      ![final relation](images/Lab_1/0004_7_AddModelElement_6.png)

   8. Do not forget to save your changes!

## Conclusion of Lab 1

In this Lab we have been introduced how to use DevOps Model Architect to create a project, work on simple diagrams and import existing artifacts.
