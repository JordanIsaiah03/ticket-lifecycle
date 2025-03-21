# osTicket-Ticket-Lifecycle
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

In this tutorial, we outline the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

osTicket Lifecycle Stages

These are the different stages of a ticket through its creation to resolution

- Intake: The ticket is created by the user or an agent. 
- Assignment and Communication: The ticket is assigned to a department or agent, with communication with the user.
- Working the Issue: The agent works on resolving the issue and/or provides necessary updates.
- Resolution: The ticket is resolved and closed after verification with the user. 

Prioritizing Tickets Through SLAs (Service Level Agreements)

-SLAs are the crucial piece that ensures that tickets are resolved within specific timeframes, dependent
upon the issue's severity. Below are the different severity levels, each aligning with its specific SLA to prioritize and
resolve tickets efficiently and effectively: 

-Sev-A (1 hour, 24/7): The hightest priority for critical issues, and in this case, the toll system network
was down. This SLA requires a resolution within 1 hour, and this ticket was escalated up to the SysAdmins
team for 24/7 resolution. 
-Sev-B (4 hours, 24/7): Important, yet less urgent issues, for in this case, the CLM (Cash Logistics Manager) was not 
working properly, due to a network error. This SLA ensures a 4-hour response and resolve, yet is still available for 
24 hours. 
-Sev-C (8 hours, business day): The lower priority issues are under this level, such as resetting the password in the 
video. 

-Adhering to these SLAs ensures that the more severe issues in osTicket are prioritized immediately, while
making sure tha the lower level issues are handled effectively. 

-Triaging Tickets

We demonstrated how the tickets are evaluated either solve the problem, or to escalate to a higher level 
of support. Triaging is the element needed to make that things are moving efficiently and in a timely manner. 

Solving Problems and Closing Tickets

We demonstrated how each issue is addressed, the solution provided to the user, and the ticket is marked as 
closed once fully resolved. 
