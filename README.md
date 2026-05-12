# Integration-AWS-IAM-to-SSO
Integration AWS IAM to SSO

SAML-security Azured Markup Language
|
|--> Service Provider --> AWS
|--> Identity Provider --> Active Directory

Identity Center IAM
settings--> actions --> change identity source --> External identity Provider --> download metadata file --> Next --> Goto Azure Active directory which in Azure console -->
click to Azure AD --> Enterprise Application --> Choose AWS Identity Center (SSO) --> At Menu Click "single-single-on" --> SAML --> Upload metadata file --> save -->
Go to SAML certificates download Federation Metadata XML --> go to Identity provider metadata --> upload AWS Identity center file --> Next --> Accept -->change Identity source --> change identity source  --> Automatic provising --> Enable --> save SCIM & Access taken in notepad 

Go to Azure portal --> Menu --> prvisioning --> automatic --> Enter the SCIM & secret Token from Notepad --> Test Connection --> After successfull test connection --> go to "Users & Groups" ---> Add users, click assign --> go to provisioning & start provisioning --> user will be added --> go to AWS IAM identity center --> Click Users, we can seethe user in this

