# cloud-analytics-end-to-end-sample
TechEd session: AIN623 - Deep Dive into SAP Analytics Cloud and SAP Cloud Platform.

## Description
The TechEd 2018 session AIN623 describes how to create a end-to-end analytics scenario using the trial accounts of SAP Cloud Platform and SAP Analytics Cloud.

The exercise documentation of this sample is completely self-contained and can therefore also be used after TechEd.

### Scenario Overview
In these exercises you will learn how to create your first end-to-end analytics scenario using SAP Cloud Platform and SAP Analytics Cloud.
Inside SAP Cloud Platform we will use SAP HANA as a database to store data and to create so called calculation views, to analyze the data.
With a live data connection, the calculation views are then consumed in SAP Analytics Cloud. The consumption happens in so call models. On top of these models a dashboard can then be build.

### Scenario Diagram

<img src="img/diagram1.JPG" alt="diagram1" width="60%">

This scenario diagram shows the full end-to-end scenario. In this case Twitter is used as a data source and data is written into a SAP HANA database in SAP Cloud Platform. Therefore, you can either use for example Cloud Platform Integration or you can write your own little application and run it on SAP Cloud Platform.
Once the data is inside the SAP HANA database, the different analytical engines are used to get more insights into the data.
On top of your data you can then launch any custom SAP Cloud Platform application, to display your data, or you can use SAP Cloud Platform Portal or SAP Smart Business Service, to analyze your data further.
The dashboarding option, which is used in this scenario, is to create a live data connection to SAP Analytics Cloud and use the modeling and story creating options there.
In between SAP Analytics Cloud and SAP Cloud Platform you can additionally use an Identity Provider, to enable SSO.


In the exercises described here, some of the options above are simplified, to save time:
1. The data is not coming live from Twitter, but it is coming from a csv file, which you have to upload into your SAP HANA database.
2. We only have a look at SAP Analytics Cloud as a dashboarding option. The other services like SAP Cloud Platform Portal are not relevant for the exercises.
3. SSO is not used.

The simplified scenario diagram showing only the exercise content could look like this:

<img src="img/diagram2.JPG" alt="diagram2" width="60%">

## NOTICE
This sample is a TechEd sample. The exercise descriptions of this sample are used during the TechEd session AIN623.

## Requirements

### For TechEd 2018
For attendees of SAP TechEd 2018, the session instructor will hand out log in information for SAP Cloud Platform trial accounts. Therefore you can skip Exercise 0 and start directly with [Exercise 1](./exercise1/README.md).

You can also use your own trial account. In this case please refer to [Exercise 0](./exercise0/README.md).

In Exercise 4 you are creating an SAP Analytics Cloud trial account. Therefore you need a company e-mail address, or you can contact your session instructor.

### For General Use
If you are following the exercises outside the TechEd session AIN623, you will need an SAP Cloud Platform trial or enterprise account (including SAP HANA) and an SAP Analytics Cloud trial or enterprise account.

[Exercise 0](./exercise0/README.md) describes how to create an SAP Cloud Platform account and how to create a HANA database there.

During Exercise 4 you are creating an SAP Analytics Cloud trial account. For this exercise a *company e-mail address* is required!

## Exercises
- [Exercise 0](./exercise0/README.md): This exercise is a prerequisite. You only need to follow these steps, if you don't have an SAP Cloud Platform trial account already.
- [Exercise 1](./exercise1/README.md): Manage roles and users. In this exercise you will learn, how to create new users in your SAP HANA database in SAP Cloud Platform and how to administer them.
- [Exercise 2](./exercise2/README.md): In this exercise you will learn how to import data with your web based development workbench.
- [Exercise 3](./exercise3/README.md): SAP HANA Modeling. In this exercise you will create your first calculation view and test it with the SQL console.
- [Exercise 4](./exercise4/README.md): Live Data Connection. In this exercise you are creating a live data connection from SAP Analytics Cloud to your SAP HANA database in SAP Cloud Platform.
- [Exercise 5](./exercise5/README.md): Modeling in SAP Analytics Cloud. How to create a model on top of your live data connection to SAP HANA will be explained in this exercise.
- [Exercise 6](./exercise6/README.md): Creating a story in SAP Analytics Cloud. In this exercise you will create your first story in SAP Analytics Cloud to get insights into your data.


## Download and Installation
The exercises for this session are entirely Cloud-based. You only need an internet browser on your machine.

**Attention**: SAP Analytics Cloud works best with Google Chrome. If you use other internet browsers, some features might not be supported!

## Configuration
None

## Limitations
When using SAP Analytics Cloud in other internet browsers than *Google Chrome*, not all features are supported. (For example creating a new live data connection is not possible)

## Known Issues
None so far...

## Support and Contributing
This project is provided "as-is": there is no guarantee that raised issues will be answered or addressed in future releases.

For more information and support on SAP Cloud Platform, please visit https://help.sap.com/viewer/p/CP

For more information and support on SAP Analytics Cloud, please visit https://help.sap.com/doc/00f68c2e08b941f081002fd3691d86a7/release/en-US/index.html

## License
This project is licensed under the SAP SAMPLE CODE LICENSE AGREEMENT except as noted otherwise in the [LICENSE](./LICENSE) file.
