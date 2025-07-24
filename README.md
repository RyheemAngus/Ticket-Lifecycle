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

<p>
<h2>Ticket 1: Critical Banking Outage</h2>

End-User (Leona) Creates Ticket

URL: http://localhost/osTicket
Subject: "Entire mobile/online banking system is down"
Help Topic: "Business Critical Outage"
<p>
<img width="736" height="725" alt="Image" src="https://github.com/user-attachments/assets/7b238b8c-9bf4-4802-8022-641215add7b6" />
</p>
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
<img width="842" height="963" alt="Image" src="https://github.com/user-attachments/assets/faa4c7a4-38cf-4f3a-b7f4-1000fcabcd90" />
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
<img width="971" height="1025" alt="Image" src="https://github.com/user-attachments/assets/a0113e84-6930-46f2-a37b-c5774e7b67cb" />
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
<p>
<img width="824" height="353" alt="Image" src="https://github.com/user-attachments/assets/b3118725-c192-498b-9f0e-0a9f6fc10b0b" />
</p>
<br />

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
<p>
<img width="2240" height="1260" alt="Image" src="https://github.com/user-attachments/assets/f95eaf97-19a3-41fe-ae9b-15325fc26f5e" />
</p>
<br />
