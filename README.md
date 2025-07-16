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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Initial Setup</h2>

Delete Maintenance Department:
Admin Panel -> Agents -> Departments → Delete "Maintenance" (do not archive).
Set SysAdmins as Top-Level Department:
Edit "SysAdmins" → Ensure "Top-Level" is selected.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Ticket 1: Critical Banking Outage</h2>

End-User (Leona) Creates Ticket

URL: http://localhost/osTicket
Subject: "Entire mobile/online banking system is down"
Help Topic: "Business Critical Outage"

Agent (Lerone) Reviews Ticket

Properties:
Priority: Low (Default)
Department: Support (Default)
SLA: None (Default)

Admin (Lerone) Escalates Ticket

Update Properties:
Priority: High
Department: Online Banking
SLA: Sev-A (1 hour, 24/7)

Resolution

Agent (Leorne):
Adds internal notes: "Restarted banking servers; monitoring."
Marks as Resolved.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Ticket 2: Adobe Upgrade Request</h2>

End-User (Ronaldo) Creates Ticket

Subject: "Accounting department needs Adobe upgrade, broken"
Help Topic: "Equipment Request"
Agent (Lerone) Processes Ticket

Update Properties:
SLA: Sev-B (4 hours, 24/7)
Department: Support
Workflow:
Communicates with user: "Upgrade scheduled for 2 PM."
Resolves after upgrade.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Ticket 3: CFO’s Laptop Issue</h2>

End-User (Messi) Creates Ticket

Subject: "CFO’s laptop will no longer turn on"
Help Topic: "Personal Computer Issues"
Agent (Lerone) Handles Ticket

Properties:
SLA: Sev-B (4 hours, 24/7)
Assigned To: Lerone
Resolution:
Replaced laptop battery; verified power-on.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h2>Ticket 4: Printer On 3rd Floor Not Printing</h2>

End-User (Ronaldo) Creates Ticket

Subject: "The hp printer outside conference room 3B isn't printing. Jobs are getting stuck in the queue."
Help Topic: "Print Jobs Stuck"
Agent (Lerone) Handles Ticket

Properties:
SLA: Sev-A (1 hours, 24/7)
Assigned To: Lerone
Resolution:
Connected remotely to the printer management console to clear the stuck print queue then went and ran physical tests on the printer to ensure it was working. 
</p>
<br />
