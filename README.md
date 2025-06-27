<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p align="center">
Before we create tickets as end users and observing all the ticket properties and responding to them as help desk professionals. 
Login as:
  
- **User:** adminuser
- **Password:** Password1  
- **Admin/Analyst Login Page:**  http://localhost/osTicket/scp/login.php
- Go to Admin Panel -> Agents -> Departments
- Then select "Maintenance Department", then click "More", then click "Delete".

</p>
<p>

![image](https://github.com/user-attachments/assets/88a7ea45-07ed-4fa4-8399-9c96930e3f21)

</p>
<br />

<p align="center">
Open this link, then click on "Open a New Ticket":

- **End Users osTicket URL:** http://localhost/osTicket
- As an end-user, create the following ticket:
- **E-mail Address:** karen@lognpacific.com
- **Full Name:** Karen
- **Help Topic:** Report a Problem 
- **Issue Summary:**  Entire mobile/online banking system is down
- **Issue Description:** My employees are reporting that users are no longer able to access the online banking portal. The ones who can occasionally access it, cannot log it. 
- Click **Create Ticket**
</p>
<p>

![image](https://github.com/user-attachments/assets/c1f90ab5-c682-4d7b-9780-5c291ab80b31)
![image](https://github.com/user-attachments/assets/a7a6453b-f717-44d3-b882-783aac1ada9f)


</p>
<br />

<p align="center">
As a Help Desk Agent John:

- **Link:** http://localhost/osTicket/scp/login.php
- **Username:** john
- **Password:** Password1
- Observe the ticket’s properties such as "Priority", "Department", "SLA", "Assigned To", etc. (In theory you would contact karen to get more information. Is it still down? etc.) 

</p>
<p>

![image](https://github.com/user-attachments/assets/59848694-87c0-4947-ab69-a70720a7aa52)

</p>
<br />

<p align="center">
Set Properties to the ticket to Sev-A (1 hour, 24/7) and Comment: Wide Impact, customers unable to do online banking.
(But before that First, set John to have all-access first in adminuser account in Agents, then login back as John)

</p>
<p>

![image](https://github.com/user-attachments/assets/277e6a51-4ec3-448a-b25d-dda2ce482095)

</p>
<br />

<p align="center">
In that same ticket update this property for Help Topic to Online Banking Department. And put this comment: No customers able to access online banking.

</p>
<p>

![image](https://github.com/user-attachments/assets/d6cc591a-3dbb-4dfc-a969-f7ef41b46795)

</p>
<br />

<p align="center">
Attempt to observe the ticket again as “john”. Can you view or change? Ideal John shouldn’t be able to. (If John is able to see, then go to the adminuser account, and change John access to view-only) 

</p>
<p>

![image](https://github.com/user-attachments/assets/490f5d11-cbdb-4096-8a6a-9241aa5600e3)

</p>
<br />

<p align="center">
Assign to Jane Doe as John (Jane and the Admin (Not John) should be part of the Team for Online Banking, which the adminuser should do), and put this comment: “Customers not able to access online banking portal, assigning to online banking team.”

</p>
<p>

![image](https://github.com/user-attachments/assets/f6e0b93f-757b-4cb7-b428-cb810f7f2028)

</p>
<br />

<p align="center">
Work the ticket to completion as jane. (She assigns the ticket to herself. Comment: “I’ll be taking this ticket.”

</p>
<p>

![image](https://github.com/user-attachments/assets/db809b56-97b9-44d2-a113-2eeb89fe1a4e)

</p>
<br />

<p align="center">
In Post Reply put this as Jane: I suspect the problem might be related to the recent updates. We tested them sufficiently, but 	I’m going to look into it further and roll the back if I determine that was the cause. 

</p>
<p>

![image](https://github.com/user-attachments/assets/3c99c4b7-43f7-4b0f-a8d8-0921fb3de840)

</p>
<br />

<p align="center">
Next Post Reply from Jane: It was determined the root cause was the recent update. We rolled it back, notified the vendor, and are waiting for a proper fix. Online banking should now be up and running. 

</p>
<p>

![image](https://github.com/user-attachments/assets/0179c9f2-867d-49af-9696-2e5dcbff4991)
</p>
<br />

<p align="center">
Since the ticket is resolved, change the status of the ticket from Open to Resolved, then click closed. 

</p>
<p>

![image](https://github.com/user-attachments/assets/e0131ad2-72b2-44c5-88f8-510124768e57)
</p>
<br />

<p align="center">
As an end-user, create the following ticket. Issue Summary: accounting department needs adobe upgrade, broken. Description: It looks like many people in the account department can’t use their adobe software.

</p>
<p>

![image](https://github.com/user-attachments/assets/a363e1ca-694c-4f25-9aa4-bb67a8afba4a)
</p>
<br />

<p align="center">
As a Help Desk Agent (john), observe the ticket’s properties. (Priority, Department, SLA, Assigned To). Set SLA Properties to the ticket Sev-C (Business Hours, 24/5). Comment: Only 2 people unable to open adobe reader, classifying as Sev-C.

</p>
<p>

![image](https://github.com/user-attachments/assets/56ad425c-3a41-46f3-bfc6-e7e0dd3f2f43)

</p>
<br />

<p align="center">
Since the ticket department is support, work the ticket to completion as john. Assign to self as John. 

</p>
<p>

![image](https://github.com/user-attachments/assets/2c2dc9ed-86f7-4f4b-a717-c41efcef5ebb)
</p>
<br />

<p align="center">
Post Reply: (Cx means Customer) Cx states only 2 people in the accounting department are unable to open and use adobe reader. Cx testing restart, will call back after lunch.

</p>
<p>

![image](https://github.com/user-attachments/assets/4af13c3c-c525-4334-8fc8-1b3e129ea5b8)

</p>
<br />

<p align="center">
Next Post Reply (Imagine a few hours passed and you were notified the following): Cx states that restart fixed issue, closing out ticket. Caution: If your company has internal notes, similar to osTicket, then avoid saying anything you don’t want the customer to see. Since you never know if they might see it. Make them as nice as possible. 

</p>
<p>

![image](https://github.com/user-attachments/assets/5ddaaa2b-94ce-426c-8c05-b89bfcc66821)
![image](https://github.com/user-attachments/assets/7e2cb5b7-6fea-4d84-8570-079233bd60fa)

</p>
<br />

<p align="center">
Resolve ticket.

</p>
<p>

![image](https://github.com/user-attachments/assets/4224cb3d-1e96-4475-89e4-db34dba73aab)

</p>
<br />

<p align="center">
As an end-user, create the following ticket. Issue Summary: CFO’s laptop will no longer turn on. Issue Description: Laptop won’t power on, despite pressing the power button.

</p>
<p>

![image](https://github.com/user-attachments/assets/624fcf9d-681d-4384-81f4-315da65d7f9c)

</p>
<br />

<p align="center">
As a Help Desk Agent (john), observe the ticket’s properties. Priority -> emergency ; Department = Support ; SLA -> Sev-B ; Comment: May reclassify after getting more info. ; Assigned To -> To self (John) ; Note ; In real life, call the CFO, see in person, or contact karen. 

</p>
<p>

![image](https://github.com/user-attachments/assets/f1f4849c-eb8e-4806-b5ac-9950c6b3cf39)

</p>
<br />

<p align="center">
Set Properties to the ticket to Sev-B (4 hours, 24/7) and Support. Work the ticket to completion as john. Post Reply: CFO’s laptop was not charging due to broken charger, brought new charger, now successfully charging. 

</p>
<p>

![image](https://github.com/user-attachments/assets/005df50f-532d-40ca-bc81-c4f83bd1d8c5)

</p>
<br />

<p align="center">
Close Ticket since it was solved. Comment: Charger was broken, because of this, the battery was dead and unable to turn on. ; Make sure, that all closed tickets are assigned to the right department, example like business critical outage should belong to sysadmins, meaning then john can’t see it. You could also give John limited access to.

</p>
<p>

![image](https://github.com/user-attachments/assets/fdface83-162d-44cf-aaef-00d9fa25a67c)

</p>
<br />
