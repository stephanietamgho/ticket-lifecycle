<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Ticket Creation Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Ticket Creation
- Assignment and Communication
- Working the Issue and Resolution

<h2>Lifecycle Stages</h2>

<h3>1. TICKET CREATION</h3>
<p>
<img src="https://i.imgur.com/LO0UJ6V.png" height="40%" width="40%" alt=" osTicket ticket creation"/>
</p>
<p>
+ Go to the end user's osTicket website: http://localhost/osTicket/ and as an end user, click on "Open a new ticket".
</p>
<br />
<br />

<p>
<img src="https://i.imgur.com/p8ONmBF.png" height="50%" width="50%" alt="osTicket ticket creation"/>
</p>
<p>
+ Enter your full name, email address and your concers/request. </p>
<p>
+ Here for the purpose of the demo, Suzy Breeze is a user I created as an Agent in osTicket agent's site. She choses the subject topic, a summary and more detail of the issue she's encountering. Then she clicks on "Create Ticket".
</p>
<br />
<br />


<p><h3> 2. & 3. ASSIGNMENT AND COMMUNICATION </h3></p>
<p>
<img src="https://i.imgur.com/FAvGHoX.png" height="40%" width="40%" alt="osTicket ticket assignment"/>
</p>
<p>
+ As the responding Agent, I log on osTicket's Agent portal.
</p>
<br />
<br />


<p>
<img src="https://i.imgur.com/tQ1YEOP.png" height="50%" width="50%" alt="osTicket ticket assignment"/>
</p>
<p>
+ Your screen will display all the tickets that were created by users. </p>
<p>
+ You can see one who's already assigned to John in Maintenance Department as created in the post installation tutorial.</p>
<p>
+ Let's open the one Suzy has just created that isn't currently assigned.
</p>
<br />
<br />


<p>
<img src="https://i.imgur.com/mHPafGy.png" height="50%" width="50%" alt="osTicket ticket assignment"/>
</p>
<p>
+ Here is Suzy's ticket in full view. No one in the Support Team has been assigned this ticket yet. </p>
<p>
+ The Priority is set to Normal but will need to change to the severity of the issue. Due to the nature of the issue, it was already determined as a SEV-A isuue with a SLA of 1 hour.
</p>
<br />
<br />


<p>
<img src="https://i.imgur.com/JOcHcyW.png" height="50%" width="50%" alt="osTicket ticket assignment"/>
</p>
<p>
<img src="https://i.imgur.com/2Goo8YW.png" height="30%" width="30%" alt="osTicket ticket assignment"/>
</p>
<p>
+ Here I'm assigning the ticket to Agent "Stephanie Tam" and updating it to "Emergency".
</p>
<br />
<br />

<p>
<img src="https://i.imgur.com/JhbWa9S.png" height="50%" width="50%" alt="osTicket ticket assignment"/>
</p>
<p>
+ Upon making changes during the assignement phase, you may notice osticket created a thread with the updates made.
</p>
<br />
<br />


<p>
<img src="https://i.imgur.com/4mefWK1.png" height="50%" width="50%" alt="osTicket ticket assignment"/>
</p>
<p>
+ During the communication phase, I, as the assigned Agent of this ticket, responds to the user, Suzy, to acknowledge her message and give her an update. 
</p>
<br />
<br />


<p><h3> 4. WORKING THE ISSUE AND RESOLUTION </h3></p>
<p>
<img src="https://i.imgur.com/z18eJi1.png" height="50%" width="50%" alt="Working the issue osticket"/>
</p>
<p>
+ Upon investigation, the one of the load balancer was failing. </p>
<p>
+ Thus, I add another reply to the thread stating that the Sys Admin fixed the incident to update Ms. Suzy and the whole system. I then select "Resolved" to close the ticket.
</p>
<br />
<br />


<p>
<img src="https://i.imgur.com/ChPjzbx.png.png" height="40%" width="40%" alt="osTicket Resolution step"/>
</p>
<p><img src="https://i.imgur.com/T3X2pOu.png" height="40%" width="40%" alt="osTicket Resolution step"/>
</p>
<p>
+ Back to the main dashboard, we notice Suzy's ticket disappeared. It now appears on the "Closed" folder.
</p>
<br />
<br />


<p><h2> VOILÀ 😊 </h2></p>
