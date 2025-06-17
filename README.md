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

<p>

![image](https://github.com/user-attachments/assets/9f2e275f-f185-4874-83b7-9c8fdc5202fe)

</p>
<p>
Before we create tickets as end users and observing all the ticket properties and responding to them as help desk professionals, first we will DELETE the Maintenance Department (not archive) (login as User: adminuser ; Password: Password1 ; Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php 

</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/2bb9f877-ffe2-47f6-9cd6-f0be5c64be5d)

</p>
<p>
As an end-user, create the following ticket. (End Users osTicket URL:
http://localhost/osTicket ) Issue Summary:  entire mobile/online banking system is down. ; Issue Description: My employees are reporting that users are no longer able to access the online banking portal. The ones who can occasionally access it, cannot log it. 
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/9f860c12-5767-4ee3-b3c4-8696f193f4cd)

</p>
<p>
As a Help Desk Agent (john), observe the ticket’s properties (in theory you would contact karen to get more information. Is it still down? etc.) (Priority, Department, SLA, Assigned To)

</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/277e6a51-4ec3-448a-b25d-dda2ce482095)

</p>
<p>
Set Properties to the ticket to Sev-A (1 hour, 24/7) and Comment: Wide Impact, customers unable to do online banking.
 (But before that First, set John to have all-access first in adminuser account in Agents, then login back as John)
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/d6cc591a-3dbb-4dfc-a969-f7ef41b46795)

</p>
<p>
In that same ticket update this property for Help Topic to Online Banking Department. And put this comment: No customers able to access online banking.

</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/490f5d11-cbdb-4096-8a6a-9241aa5600e3)

</p>
<p>
Attempt to observe the ticket again as “john”. Can you view or change? Ideal John shouldn’t be able to. (If John is able to see, then go to the adminuser account, and change John access to view-only) 

</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/f6e0b93f-757b-4cb7-b428-cb810f7f2028)

</p>
<p>
Assign to Jane Doe as John (Jane and the Admin (Not John) should be part of the Team for Online Banking, which the adminuser should do), and put this comment: “Customers not able to access online banking portal, assigning to online banking team.”
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/db809b56-97b9-44d2-a113-2eeb89fe1a4e)

</p>
<p>
Work the ticket to completion as jane. (She assigns the ticket to herself. Comment: “I’ll be taking this ticket.”

</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/3c99c4b7-43f7-4b0f-a8d8-0921fb3de840)

</p>
<p>
In Post Reply put this as Jane: I suspect the problem might be related to the recent updates. We tested them sufficiently, but 	I’m going to look into it further and roll the back if I determine that was the cause. 
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/0179c9f2-867d-49af-9696-2e5dcbff4991)

</p>
<p>
Next Post Reply from Jane: It was determined the root cause was the recent update. We rolled it back, notified the vendor, and are waiting for a proper fix. Online banking should now be up and running. 
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/e0131ad2-72b2-44c5-88f8-510124768e57)

</p>
<p>
Since the ticket is resolved, change the status of the ticket from Open to Resolved, then click closed. 
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/a363e1ca-694c-4f25-9aa4-bb67a8afba4a)

</p>
<p>
As an end-user, create the following ticket. Issue Summary: accounting department needs adobe upgrade, broken. Description: It looks like many people in the account department can’t use their adobe software.
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/56ad425c-3a41-46f3-bfc6-e7e0dd3f2f43)

</p>
<p>
As a Help Desk Agent (john), observe the ticket’s properties. (Priority, Department, SLA, Assigned To). Set SLA Properties to the ticket Sev-C (Business Hours, 24/5). Comment: Only 2 people unable to open adobe reader, classifying as Sev-C.


</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
