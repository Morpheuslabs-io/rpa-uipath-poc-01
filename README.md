# rpa-uipath-poc-01
This is a UiPath RPA POC for outlet payment reconciliation process.

Preparation to run the POC:

1. Have UiPath Sudio (community edition) on your Windows machine (PC or Laptop)
2. Use a Gmail account "uipathpoc01@gmail.com" dedicted for running this poc. The Gmain account is with IMAP enabled and also able to run less secured application (for POC). This has already be done for the account.
3. Download the sub-folders and files of the POC folder into C:\POC on your PC / Laptop
4. Download the UiPath project files into your C:\POC_UiPath folder
5. Open the "main" project file in C:\POC_UiPath in UiPath Studio and repair the dependencies as prompted in the UiPath Studio.

Execute the POC:

1. Login to the Gmail "uipathpoc01@gmail.com"
2. Mark the 3 emails for "Outlut records", "Credit report" and "Bank statement" in Gmail account as "Unread"
3. Start "Debug" to run the reconciliation process in UiPath Studio. This may take few minites, you can see the steps executed from output in UiPath Studio.
4. Check the exception reports and reconcilation reports in C:\POC\OutPut folder.

For the detailed info about the POC scenario, processing steps and the high level solution beyond the POC, refer to the POC PDF document in this repository.

