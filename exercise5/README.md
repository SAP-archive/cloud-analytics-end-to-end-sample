# Exercise 5: Modeling in SAP Analytics Cloud

A model is a representation of the business data of an organization or business segment. The Modeler of SAP Analytics Cloud can be used to create, maintain, and load data into models.

When using a live data connection, the main part of the modeling is already done in the data source. So in SAP Analytics Cloud very little steps are needed.

For more information on models in SAP Analytics Cloud, please have a look at the help documentation: https://help.sap.com/doc/00f68c2e08b941f081002fd3691d86a7/release/en-US/c10af00a90cd43b6894f6767a47dff17.html

## Step 1: Creating a Model on a SAP HANA Live Data Connection

Go to the home screen of your SAP Analytics Cloud trial account

Via the main menu navigate to *Create > Model*

<img src="img/home-create.png" alt="home-create" width="40%">

To start your model choose *Get data from a datasource > Live Data connection*

<img src="img/liveData.png" alt="liveData" width="60%">

A pop-up shows up where you need to enter the following information:
- System Type: `SAP HANA` (use the dropdown menu)
- Connection: `cptrial` (use the dropdown menu)
- Data Source: `SIMPLEVIEW` (you can also select it with the help button on the right site)
- Name: `simpleModel`

<img src="img/createModel.png" alt="creteModel" width="60%">

A new screen shows up, where you can see the measures of your calculation view and a preview of the model on the right-hand side.

*Optional: If you are interested, you can also click on All Dimensions to view the dimensions of your calculation view.*

After exploring your model, click *Save Model*

<img src="img/model.png" alt="model" width="100%">

A success message should show up on the bottom of your screen.

Congratulations! You created your first model successfully. You can now go back to the home screen of your SAP Analytics Account.

Continue with [Exercise6](../exercise6/README.md)
