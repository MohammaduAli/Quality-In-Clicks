# Quality-In-Clicks
Quality in clicks (QiC) is a Windows based application which helps Testers/QA Engineers to automate the manual processes in MicroFocus ALM/Quality Center Application

![image](https://user-images.githubusercontent.com/64326474/188650470-073af74f-a3dd-4591-958c-7daf2fcc7db3.png)

Introduction:
QiC tool is developed using .net framework and is used primarily in Test execution, Test Management and Defect management phases by Software Testers and this user-friendly tool automates all the manual activities done within each of the above-mentioned testing phases in MicroFocus ALM/Quality Center Tool. 

This QiC tool can be used in all testing projects across all the domains. This saves huge effort spent on manual steps/process done in test execution and defect management phases by completing those tasks just in clicks. QiC addresses the testing needs of business users such as testers, SMEs and other technical users. Practical challenges faced in assuring quality testing inspires to develop this tool. No additional effort required in using this tool which is unique and make this tool different from others. Approximately 2460 dollars/day can be saved by taking an example of a typical project with 60 active members involved in test execution phase who executes an average of 12 medium test cases per day.      
The purpose of this document is to assist users to practice and successfully use this tool. We have identified fews tasks that we perform with MicroFocus ALM and how QiC tool will help in accomplishing those tasks efficiently with step-by-step explanation and screenshots. Below is a glance of this QiC tool.

![image](https://user-images.githubusercontent.com/64326474/188654367-24f4e2f9-7421-4a2c-b910-c1f61d8aace5.png)

How to Get Started with the Tool:
1.	Open the QiC tool either by double clicking on the desktop icon or getting it from the Start menu	
2.	Enter the ALM URL “https://<ALM Platform server name> [<: portnumber>]/qcbin” in the "QC URL" field then enter ALM credentials and click on Authenticate. On successful authentication the domain and project drop down lists the corresponding values.
![image](https://user-images.githubusercontent.com/64326474/188665552-5d122088-6b53-4b2a-81f2-d0ce8293b3aa.png)

3.	Select your desired Domain and Project Name from the dropdown list and click on Login button
![image](https://user-images.githubusercontent.com/64326474/188670417-af04b429-13bc-45d2-94a5-7b0d5313a7b7.png)

4.	Once login button is clicked, the tool will show the Test lab structure of the selected project
![image](https://user-images.githubusercontent.com/64326474/188711939-d27134cc-8f9e-4461-bcfa-448af9008ca3.png)

5.	User can navigate and locate the desired test case by drilling down/expanding through various test set folders and test sets just by clicking on it

![image](https://user-images.githubusercontent.com/64326474/188723673-16207b90-059a-42ed-95f3-d86ee7192edc.png)

6.	This tool is having a feature of differtiating each test case by colors based on its execution status as given below,
![image](https://user-images.githubusercontent.com/64326474/188671735-d3f85bab-fd1e-4c97-b21d-5a42bbfe9cb2.png)

Screen capture Module:
•	Select any desired test case for which test execution screen shots to be captured – Now user could see three new buttons namely [Record], [Pass] and [Fail] in addition to the already available [Close] button
For instance, a “No Run” status test case has been selected by the user in the below screen shot

![image](https://user-images.githubusercontent.com/64326474/188723847-0d7ea306-7f45-4ea1-85af-5ee7e143ca39.png)

•	Click on the [Record] button which will open an empty word document and a new window named “Screen capture”
This Screen Capture window will display test steps of the selected test case, fetched from the corresponding test plan path, along with the guidelines to capture snapshots like below
Page Up – To capture the whole screen as we do it using [Print Screen] option without navigating to the word document 
Page Down – Opens a pop-up window where user can enter comments for the corresponding snap in the execution document

![image](https://user-images.githubusercontent.com/64326474/188724026-148dece6-959c-4bef-91f4-a8016f052461.png)

Note: Using this feature, user can skip the conventional steps like 
a.	opening a word document, 
b.	saving it with a desired test case name, 
c.	navigating between the application and the execution document for pasting the snaps captured using [Print Screen] option

![image](https://user-images.githubusercontent.com/64326474/188724175-270c6ec1-fa93-45fd-b695-0774240025ba.png)

After taking all required snaps related to the test case, user can close the Screen Capture window which will auto save the document inside the specified folder path 
Now the tool will automatically highlight the execution recorded test case in red color and the user can track completed activities in the status bar as shown in the below snap

![image](https://user-images.githubusercontent.com/64326474/188724440-64e5677d-3fa7-499a-a98c-63a0fe8794a4.png)

Double click on the test case – the word document saved with the test case name will open and allows the user to edit and save if required

![image](https://user-images.githubusercontent.com/64326474/188724570-249b8529-8574-49ce-9709-19d111d809cc.png)

•	Now we could see some more new dropdown options in the [Record] button and also a new button named [Attach to Test] will get enabled next to the [Record] button
The dropdown options in [Record] button holds the options 1. Restart and 2. Resume

![image](https://user-images.githubusercontent.com/64326474/188724668-703b4400-80b1-49e8-a9c9-d445270ece0e.png)

1.	Restart – Clicking on this option will allow the user to do same screen capture procedure as described above where the existing screen shot document will be overriden by the new snaps. This option will help user while re-executing the same test case.
2.	Resume – Clicking on this option will allow the user to do same screen capture procedure, But here the existing screen shot document related to selected test case will not get overriden, instead the newly taken snaps and comments entered will get tracked in the same document as a continuation followed by the old snaps

Attachment Module:
•	Click on the [Attach to Test] button to attach the related screen shot document, taken using [Record] option, to the corresponding test case available in ALM/QCs test lab path
Doing this action will make the respective test case to get highlighted in blue color and also the user can track the series of activities completed in the status bar as shown in the below snap

![image](https://user-images.githubusercontent.com/64326474/188724891-4ba533ef-d5d9-4676-a18d-69929afa6ba2.png)

Test Execution Module – Passing a test case:
•	After the user confirms that the test case must be passed, click on the [Pass] button which will have dropdown options within it namely 1. Run Only and 2. Run and Upload

![image](https://user-images.githubusercontent.com/64326474/188725114-7b7f65e0-6ff4-494f-9754-fec2ba78d859.png)

1.	Run Only – Click on this option will just initiate a new (fresh) run and execute the corresponding test case by filling the actual results for each of the test steps (copying the content from expected results and making needed changes in it like replacing terms like should be, must be, should, must with appropriate words) 
Doing this action will make the respective test case to get highlighted in green color and also the user can track the completed activities in the status bar with corresponding Run id as shown in the below snap

![image](https://user-images.githubusercontent.com/64326474/188725220-8b6f27db-53f0-42f1-a75f-48cac5eb0a66.png)

2.	Run and Upload – Click on this option will do the same action as like Run Only option, Also in addition to that the corresponding screen shot document will be uploaded in to the newly initiated test case Run 
Test Execution Module – Failing a test case:
•	After user confirms that a test case has to be failed, click on the [Fail] button which will have dropdown options within it namely 1. Raise and Link Defect and 2. Link Existing Defect

![image](https://user-images.githubusercontent.com/64326474/188725373-dba1ae14-4a88-4e3f-8547-2bf1fc1306fe.png)

1.	Raise and Link Defect - Click on this option will open a new window named “Failed Reason” which will have test case steps imported from corressponding test case’s test plan path followed by a balloon notification as shown in below snaps

![image](https://user-images.githubusercontent.com/64326474/188725480-494949cc-1330-402c-b792-6bf204f8d5a1.png)

![image](https://user-images.githubusercontent.com/64326474/188725586-ca59d73b-209c-427d-b797-38448208bcc0.png)

The user can select the test case step that needs to be failed and enter a reason for failing that step, then by clicking on the [Continue] button will open a new window named “New Defect” followed by a balloon notification as shown in below snaps

![image](https://user-images.githubusercontent.com/64326474/188725665-9cfaa3db-30b9-4b59-9072-0311dea35b8c.png)

![image](https://user-images.githubusercontent.com/64326474/188725702-ae0c0670-87ed-461c-b805-2ed058c0aab7.png)

This New Defect window will display all the fields available for raising a defect normally in ALM/QC and the mandatory fields of the corresponding project will be highlighted in red color
The dropdown controls will display the list of values options with respect to the selected project. The textbox fields not included with dropdown options will remember the entered content in the successive launches of New Defect module
Incorrect values/data entered over any of the mandatory textboxes will be highlighted with a blinking exclamatory symbol

![image](https://user-images.githubusercontent.com/64326474/188725915-954f42e4-9a40-4805-b27f-78446d8385be.png)

Click on [Submit] button after filling all the mandatory inputs, user will be shown a pop-up with the defect id raised and linked to the corressponding test case
Note: This will initiate a new/fresh run and execute the corresponding test case by filling the actual results for each of the test steps (copying the content from expected results, making necessary changes in it like replacing terms like should be, must be, should, must with appropriate words and passing the step) till the step selected in the Failed Reason window and failing that step with the failure reason entered
Doing this action will make the respective test case to get highlighted in red color and also the user can track the completed activities in the status bar with corresponding Run id as shown in the below snap

2.	Link Existing Defect - Click on this option will open a new window named “Failed Reason” which will have test case steps imported from corressponding test case’s test plan path followed by a balloon notification as shown in below snaps

![image](https://user-images.githubusercontent.com/64326474/188726033-374f48dd-9b2f-4ed4-807c-910140d9c650.png)

![image](https://user-images.githubusercontent.com/64326474/188726179-c6304d26-26d1-4656-a664-df643a23ea85.png)

Here user is allowed to select the test case step that needs to be failed and enter the reason for failing that step, then by clicking on the [Continue] button will open up a new pop-up window named “Link Existing Defect”

![image](https://user-images.githubusercontent.com/64326474/188726310-c9b314c9-9fe9-4879-a722-5df400efac04.png)

In this window, the user will be populated with a textbox to enter the desired defect id to be mapped with the test case. User will also see a checkbox named “Attach Snapshot document” only if the selected test case holds screen shot document taken using [Record] functionality 
Once the user is done with entering desired defect id to be mapped and click on [Link] button, the corresponding test case will be failed and linked with the entered defect id with attachment if the checkbox is enabled. This action will also get tracked in that test case’s status bar
Note: This will initiate a new/fresh run execute the corresponding test case by filling the actual results for each of the test steps (copying the content from expected results, making needed changes in it like replacing terms like should be, must be, should, must with appropriate words and passing the step) till the step selected in the Failed Reason pop-up screen and failing that step with the failure reason entered
Doing this action will highlight the respective test case in red color and the user can track the completed activities in the status bar with corresponding Run id as shown in the below snap

![image](https://user-images.githubusercontent.com/64326474/188726644-4081d24e-88ed-44f5-864e-e4c9603f490c.png)

![image](https://user-images.githubusercontent.com/64326474/188726777-6e2549c8-570a-4de6-9ccd-55a75d013b8e.png)


Special Note:
By default, the drive selected for saving the screen shot document will be C: drive, and the user can change the drive any time using drive selection icon as given in the below snap

![image](https://user-images.githubusercontent.com/64326474/188726934-6e241c97-f901-43dd-b5a2-b6bddc4bec29.png)

