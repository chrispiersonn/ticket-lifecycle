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

![Screenshot 2025-02-03 154738](https://github.com/user-attachments/assets/968ac72a-85c6-43aa-b3ad-fd7bbb9e32ef)

[Admin/Analyst Login Page](http://localhost/osTicket/scp/login.php)

[End Users osTicket URL](http://localhost/osTicket)

In this lab, we will be creating tickets as end users
Observing all the ticket properties and responding to them as help desk professionals
<br />

![image](https://github.com/user-attachments/assets/7be6d45c-c076-4b12-8a21-5c4944604b31)
<p>
1) Intake – The process of receiving and logging a ticket, where key details such as issue type, priority, and requester information are recorded.
<br />

![image](https://github.com/user-attachments/assets/f38e6e99-b2bb-4d45-a1ca-d74b23c143bc)
<p>
2) Assignment and Communication – The ticket is assigned to the appropriate team or individual, and initial communication is sent to acknowledge receipt and provide updates.
</p>
<br />

![image](https://github.com/user-attachments/assets/8f4a8a9f-662f-4dc7-912d-687e0242959f)
<p>
3) Working the Issue – The assigned team actively investigates, troubleshoots, and works toward resolving the issue, with ongoing updates as needed.
</p>
<br />

![image](https://github.com/user-attachments/assets/99893117-65a4-44c9-be7b-9187d94b2920)
![image](https://github.com/user-attachments/assets/362b2ab8-65f5-40a0-a9fb-196491f3e5f9)
<p>
4) Resolution – The issue is resolved, the solution is documented, and the ticket is closed after confirming with the requester that the problem is fixed.
</p>
<br />

![image](https://github.com/user-attachments/assets/fd004fd6-3334-424c-af40-31196c7f83a5)
<p>
Practice Tickets:

As an end-user, create the following ticket
entire mobile/online banking system is down

As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
Sev-A (1 hour, 24/7)
Online Banking Department

Attempt to observe the ticket again as “john”. Can you view or change?

Work the ticket to completion as jane

------------

As an end-user, create the following ticket
accounting department needs adobe upgrade, broken

As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To

Set Properties to the ticket
Sev-B (4 hours, 24/7)
Support

Work the ticket to completion as john

-------------
