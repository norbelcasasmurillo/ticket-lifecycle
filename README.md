<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


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
![image](https://github.com/user-attachments/assets/9ef4cd10-a58b-460e-b7e2-4a7bb5657234)

</p>
<br />

<p align="center">
A prestep before this step, set John to have all-access first in adminuser account in Agents. Go to Admin Panel -> Agents -> John Doe -> Access -> Change "View-Only" to "All Access" -> Click Save Changes. Then login back as John.

- **Username:** adminuser
- **Password:** Password1
- **Username:** john
- **Password:** Password1
- Then on john's account, set these new properties setting for Karen's open ticket:
- **SLA Plan:** Sev-A (1 hour, 24/7)
- **Comment:** Wide Impact, customers unable to do online banking.
- Then click update.

</p>
<p>

![image](https://github.com/user-attachments/assets/c02e185b-6d01-4552-ab11-c674114fed3e)

![image](https://github.com/user-attachments/assets/d273fb0c-63a1-4c6e-9062-7a2d26788582)

</p>
<br />

<p align="center">
  
In that same ticket update these property: 

- **Assigned to:** Jane / Online Banking (Then click "Assign")
- **Comment (for Assigned to):** Customers not able to access online banking portal, assigning to online banking team.
- And 
- **Help Topic:** Report a Problem / Business Critical Outage
- **Comment (for Help Topic):** No customers able to access online banking.
  
</p>
<p>

![image](https://github.com/user-attachments/assets/a2d153d7-47d2-4f4b-9ed0-1b690ce77817)

</p>
<br />


<p align="center">
Work the ticket to completion as jane. 
  
- **Username:** jane
- **Password:** Password1
</p>
<p>

![image](https://github.com/user-attachments/assets/cbcbf60e-bc2b-445e-b31d-1e1b955774b2)

</p>
<br />

<p align="center">
Within the ticket, at the bottom of the page where it says "Post Reply" put this as Jane:
  
- **Post-Reply:** I suspect the problem might be related to the recent updates. We tested them sufficiently, but 	I’m going to look into it further and roll the back if I determine that was the cause. 
- Then click Post Reply.
</p>
<p>

![image](https://github.com/user-attachments/assets/fe4390c5-cf1e-4ea1-9478-7a52d795cfd7)

</p>
<br />

<p align="center">
Put this Next Post Reply from Jane: 

- **Post Reply:** It was determined the root cause was the recent update. We rolled it back, notified the vendor, and are waiting for a proper fix. Online banking should now be up and running. 
- Then click Post Reply
</p>
<p>

![image](https://github.com/user-attachments/assets/185c9f35-f694-4336-b648-77168f2cb706)
</p>
<br />

<p align="center">
Since the ticket is resolved, change the status of the ticket:

- **Status:** Resolved
- Then click "Close". 

</p>
<p>

![image](https://github.com/user-attachments/assets/328100a8-2805-440a-b4c9-9cae4696dd6b)
</p>
<br />

<p align="center">
As an end-user, create the following ticket. 

- **Link:** http://localhost/osTicket/open.php (Then click on "Open a New Ticket")
- **E-mail Address:** ken@lognpacific.com
- **Full Name:** Ken
- **Help Topic:** General Inquiry / Other
- **Issue Summary:** accounting department needs adobe upgrade, broken.
- **Issue Description:** It looks like many people in the account department can’t use their adobe software.
- Then click "Create Ticket". 
</p>
<p>

![image](https://github.com/user-attachments/assets/d367cf1b-68c7-4e77-acae-662db5d9e7da)
![image](https://github.com/user-attachments/assets/c60597a4-0aac-4809-8281-8c7aab928884)

</p>
<br />

<p align="center">
As a Help Desk Agent (john), observe the ticket’s properties such as "Priority", "Department", "SLA", "Assigned To", etc. Then, change SLA Properties.

- **Username:** john
- **Password:** Password1
- **SLA Plan:** Sev-C
- **Comment (from SLA Plan)**: Only 2 people unable to open adobe reader, classifying as Sev-C.
 

</p>
<p>

![image](https://github.com/user-attachments/assets/d8d9bb87-5159-4914-8f32-b6632ecf02c9)

</p>
<br />

<p align="center">
Since the ticket department is support, work the ticket to completion as john. Assign to self as John. 

- **Assigned to:** John
- Then click "Assign".
</p>
<p>

![image](https://github.com/user-attachments/assets/0521fee5-b7ee-48c2-ade1-a06b737b5edf)
</p>
<br />

<p align="center">
Note: Cx means Customer

- **Post Reply:** Cx states only 2 people in the accounting department are unable to open and use adobe reader. Cx testing restart, will call back after lunch.
- Then click "Post Reply".

</p>
<p>

![image](https://github.com/user-attachments/assets/a40ca1e5-c1a1-4486-a1e3-a1d2b0eacbdd)

</p>
<br />

<p align="center">
Imagine a few hours passed and you were notified the following, then you create another Post Reply:

- **Next Post Reply:** Cx states that restart fixed issue, closing out ticket.
- Then click "Post Reply".
- **Caution:** If your company has internal notes, similar to osTicket, then avoid saying anything you don’t want the customer to see. Since you never know if they might see it. Make them as nice as possible. 

</p>
<p>

![image](https://github.com/user-attachments/assets/dee08844-ed77-4381-891f-9679e1fd17e9)

</p>
<br />

<p align="center">
Resolve ticket.

- **Status:** Resolved
- Then click "Close".

</p>
<p>

![image](https://github.com/user-attachments/assets/90592c21-92db-45ef-be15-be1e0e046f78)

</p>
<br />

<p align="center">
As an end-user, create the following ticket. 

- **Email:** karen@lognpacific.com
- **Full Name:** Karen
- **Help Topic:** Report a Problem / Personal Computer Issues
- **Issue Summary:** CFO’s laptop will no longer turn on.
- **Issue Description:** Laptop won’t power on, despite pressing the power button.
- Then click "Create Ticket. 

</p>
<p>

![image](https://github.com/user-attachments/assets/3d3906f1-4814-485d-aa27-02fb26d00545)
![image](https://github.com/user-attachments/assets/d310efce-65be-4e66-b0d7-192746231b01)

</p>
<br />

<p align="center">
As a Help Desk Agent (john), observe the ticket’s properties. 

- **Username:** john
- **Password:** Passsword1
- **Priority:** Emergency
- **Department:** Support
- **SLA Plan:** Sev-B
- **Comment (for SLA Plan):** May reclassify after getting more info.
- **Assigned To:** To self (John)
- Note: In real life, call the CFO, see in person, or contact Karen. 

</p>
<p>

![image](https://github.com/user-attachments/assets/52227052-96df-4244-b948-0b57aecf3209)

</p>
<br />

<p align="center">
Work the ticket to completion as john. 
  
- **Post Reply:** CFO’s laptop was not charging due to broken charger, brought new charger, now successfully charging. 
- Then click Post Reply.
</p>
<p>

![image](https://github.com/user-attachments/assets/ec343702-40f3-4810-b670-896e45a2625a)

</p>
<br />

<p align="center">
Resolve the ticket since it was solved. 

- **Status:** Resolved
- **Comment:** Charger was broken, because of this, the battery was dead and unable to turn on.


</p>
<p>

![image](https://github.com/user-attachments/assets/27df2415-923e-463f-ad27-34b0484da8f8)


</p>
<br />

<h3 align="center">Conclusion</h3>

<p align="center">

**Well done on completing the lab!**
- Throughout this lab, we explored the full functionality of osTicket in managing the complete lifecycle of a help desk ticket. This hands-on experience has provided valuable insight into real-world ticketing workflows.
- Before you finish, don’t forget to **shut down your Azure virtual machine** to avoid any unnecessary charges. If you’ve completed all your work and no longer need the environment, you can safely delete the entire resource group to stop any ongoing storage costs.
</p>
