### AIN623

# Prerequisite: Setting up the Development environment

## Step 1: Creating an SAP Cloud Platform Trial Account

- To create your SAP Cloud Platform Trial Account, please click this [link]( https://accounts.sap.com/ui/public/showRegisterForm?spName=https%3A%2F%2Fnwtrial.ondemand.com%2Fservices&targetUrl=&sourceUrl=). Provide all the necessary information there and click *Register*.
- A confirmation e-mail will be send to your provided e-mail address. Please confirm your e-mail address there.

## Step 2: Creating a SAP HANA database in your Trial Account

[Log on](https://accounts.sap.com/saml2/idp/sso/accounts.sap.com) to your SAP Cloud Platform trial account.

<img src="img/CP_LogOn.png" alt="LogOn" width="60%">

In the Cloud Platform cockpit please select *Neo Trial*.

<img src="img/Neo.png" alt="Neo" width="60%">

Navigate to *SAP HANA/SAP ASE > Databases & Schemas*

<img src="img/dbschema.png" alt="dbschema" width="60%">

Click New

<img src="img/newmdc.png" alt="new" width="60%">

Provide the Database ID *exercise* and the System User Password *Abcdef123456789*

Keep the Database System as *HANA MDC(<trial>)*

Make sure the button for “Web Access” is turned on. The “DP Server” and a user for SHINE are not needed. Therefore, make sure these buttons are turned off.

Click on Create to start the database creation.

<img src="img/createmdc.png" alt="CreateMDC" width="60%">

The creation of your database might take a couple of minutes. Therefore, please wait until the *Events* section gives you the message “Tenant DB creation finished successfully (created and configured)”

<img src="img/tenantSuccess.png" alt="tenantSuccess" width="60%">

Congratulations! You created your first SAP HANA database in your SAP Cloud Platform trial account!

Continue with [Exercise1](../exercise1/README.md)
