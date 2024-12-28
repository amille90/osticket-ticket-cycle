<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Cycle</h1>
In this project tutorial and walkthrough you will see various scenarios that take place during the cycle of a ticket, from the time its placed by a back-end user all the way to its completion from either a desk-agent or admin. user. You will also see the different characteristics of a ticket and use some of those characteristics to help organize and determine it's severity and priority.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- OsTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Computer Desktop/Laptop
- Wifi Connection
- Remote Desktop
- Azure Account
- OsTicket needs to already be installed
  
<h2>OsTicket Ticketing Cycle-Walkthrough Steps </h2>

Step 1: Make sure the osTicket-vm is turned on within Azure. Press the start button to turn on if truned off.
</p>
<p>
<img src="https://i.imgur.com/PXh8kmc.png"/>
</p>
<p>

</p>
<br />
Step 2: Log into the osTicket-vm remtote desktop and press connect.
</p>
<p>
<img src="https://i.imgur.com/dYanzYJ.png"/>
</p>
<p>

</p>
<br />
Step 3: Within the bookmark section of the internet hompage click open the helpdesk support center page. 
</p>
<p>
<img src="https://i.imgur.com/Rp1NH2e.png"/>
</p>
<p>

</p>
<br />
Step 4: Next click open the help desk agent/admin user page. 
</p>
<p>
<img src="https://i.imgur.com/BGEy0Pq.png"/>
</p>
<p>

</p>
<br />
Step 5: On the Support Center page click on Open a New Ticket. Here is where backend users/clients submit ticket requests/complaints to the helpdesk support team. 
</p>
<p>
<img src="https://i.imgur.com/6KLm5sN.png"/>
</p>
<p>

</p>
<br />
Step 6: Karen will be used in the first example. Insert Karen's email address, name , and phone number. For Help Topic select Report a Problem. 
</p>
<p>
<img src="https://i.imgur.com/igv0MEB.png"/>
</p>
<p>

</p>
<br />
Step 7: Further down on the screen fill in ticket details. For this particular scenerio the entire mobile/online banking system is down. Insert that in the Issue Summary box as the title and in the text box below that, fill in a more detailed but breif description of the problem. Press Create Ticket.
</p>
<p>
<img src="https://i.imgur.com/pFwkEYF.png"/>
</p>
<p>

</p>
<br />
Step 8: Next click open the helpdesk/admin user page. John the helpdesk agent will be taking a look at this ticket. Log in with his credentials created in the previouse project tutorial.
</p>
<p>
<img src="https://i.imgur.com/iwpVTJq.png"/>
</p>
<p>

</p>
<br />
Step 9: Click on the ticket subject line link to open it. As you can see it shows that the ticket was sent form Karen. At the top it shows that this is John's account.
</p>
<p>
<img src="https://i.imgur.com/EgRdQ3j.png"/>
</p>
<p>

</p>
<br />
Step 10: After carefully viewing the ticket, one of the first things John does is select a SLA-Plan. An SLA-Plan determines the severity and priority of a ticket. In this case the online banking outage a is an extremly urgent issue so John as set the plan to Sev-A. In the Drop down menu of SLA-Plan select Sev-A and make a note in the comment box. Click update.
</p>
<p>
<img src="https://i.imgur.com/19fEGc9.png"/>
</p>
<p>

</p>
<br />
Step 11: The SLA-Plan has been successfully created for this ticket order. 
</p>
<p>
<img src="https://i.imgur.com/11pwNXS.png"/>
</p>
<p>

</p>
<br />
Step 12: Next John goes to the 'Assign To/Unassigned' link.
</p>
<p>
<img src="https://i.imgur.com/UkxSyBi.png"/>
</p>
<p>

</p>
<br />
Step 13: John now escalates the ticket to the online banking department for this is a banking issue. So in the Assignee drop down menu select online banking and make a note to the online banking team what the problem is. Click on Assign.
</p>
<p>
<img src="https://i.imgur.com/ybA41yU.png"/>
</p>
<p>

</p>
<br />
Step 14: Next, John clicks on the Help Topic section. Make sure to click on link and set it to Report a Problem/Buisness Critical Outage. Make a note that no customers have access to the online banking portal. Make sure to press update. The ticket has successfully been assigned and escalated to someone in the banking department.
</p>
<p>
<img src="https://i.imgur.com/5lClrGA.png"/>
</p>
<p>

</p>. 
<br />
Step 15: Now that the ticket has been escalated to the banking department, log out of Johns account and log back into the deskagent/admin user page as Jane who works in the online banking support staff department.
</p>
<p>
<img src="https://i.imgur.com/fSpP5As.png"/>
</p>
<p>

</p>
<br />
Step 16: Click on the subject ticket link to open the ticket. 
</p>
<p>
<img src="https://i.imgur.com/9rS8aGQ.png"/>
</p>
<p>

</p>
<br />
Step 17: Go to the Assigned To tab and click on Online Banking. 
</p>
<p>
<img src="https://i.imgur.com/Jwij4GR.png"/>
</p>
<p>

</p>
<br />
Step 18: In the Assignee drop down menu Jane has assigned the ticket to herself and makes a note that she'll be taking this ticket. Select Jane Doe as the Assignee then click assign.
</p>
<p>
<img src="https://i.imgur.com/ryvsZb6.png"/>
</p>
<p>

</p>
<br />
Step 19: The ticket has successfully been assigned to Jane Doe and as you can see the 'Assigned to' section has been updated to Jane Doe/Online Banking.
</p>
<p>
<img src="https://i.imgur.com/7so3PX9.png"/>
</p>
<p>

</p>
<br />
Step 20: Further down in the post reply section Jane makes a note metioning what she suspects to be the problem and that she ran tests but will look further into the issue to see what the actual cause is. Click on Post Reply to send the note.
</p>
<p>
<img src="https://i.imgur.com/3Gl3ckh.png"/>
</p>
<p>

</p>
<br />
Step 21: Another note as been sent by Jane confirming the root cause of the issue and that a vendor has been notified for a proper fix. Online banking should be up and running. Click on Post Reply.
</p>
<p>
<img src="https://i.imgur.com/6072wna.png"/>
</p>
<p>

</p>
<br />
Step 22: Since problem as been resolved it's time to close out the ticket.
</p>
<p>
<img src="https://i.imgur.com/78ZhBdy.png"/>
</p>
<p>

</p>
<br />
Step 23: Go to the status line of the ticket and click on the open for the dropdown menu. Select Resovled not Closed. A closed ticket doesn't neccessarliy mean the problem has been resolved.
</p>
<p>
<img src="https://i.imgur.com/Ybsiycg.png"/>
</p>
<p>

</p>
<br />
Step 24: The close ticket box should come up with 'resolved' as the status. Click close at the bottom right.
</p>
<p>
<img src="https://i.imgur.com/9hG9HgF.png"/>
</p>
<p>

</p>
<br />
Step 25: Next, another ticket will be opened. Press Open a New Ticket on the Support Center Page. 
</p>
<p>
<img src="https://i.imgur.com/LnvRmVK.png"/>
</p>
<p>

</p>
<br />
Step 26: This time the supprot ticket will be coming from Ken. Enter in Ken's email address, name and phone number. 
</p>
<p>
<img src="https://i.imgur.com/7Jjh8MZ.png"/>
</p>
<p>

</p>
<br />
Step 27: For Help Topic select General Inquiry from the drop down menu. 
</p>
<p>
<img src="https://i.imgur.com/uNTj3j2.png"/>
</p>
<p>
 
</p>
<br />
Step 28: For this particular scenerio the accounting department needs an adobe upgrade/broken. Put this as the Issue Summary Title. And in the text box below just breifly expound a little more on what the issue is. Click Create Ticket.
</p>
<p>
<img src="https://i.imgur.com/tD2z4yv.png"/>
</p>
<p>

</p>
<br />
Step 29: Make sure to log back into the deskagent/admin user page with John's login credentials before opening the ticket. Once the page is open click on the subject link to open the ticket. 
</p>
<p>
<img src="https://i.imgur.com/WT2C2og.png"/>
</p>
<p>

</p>
<br />
Step 30: Click on the SLA-Plan and select Sev-C. Make a note that only two people can't access their Adobe accounts. The Sev-C plan is the least priority plan there is on this OsTicket installation. In this case since it's only two people expericing the issue then the problem isn't considered that severe. Make sure to press Update when done. 
</p>
<p>
<img src="https://i.imgur.com/PU2J3Dx.png"/>
</p>
<p>
 
</p>
<br />
Step 31: Next go to and click on the Assign line. In the drop down menu for Assignee select John Doe for he will be assigning this ticket to himself. Click asssign in the bottom right. 
</p>
<p>
<img src="https://i.imgur.com/YRDwUtg.png"/>
</p>
<p>

</p>
<br />
Step 32: John then create's a post reply restating what the problem is and mentions will call back for an update after lunch. Click on Post Reply.
</p>
<p>
<img src="https://i.imgur.com/LMITvxs.png"/>
</p>
<p>

</p>
<br />
Step 33: John sends another note in the post reply section stating that restarting the program fixed the issue and then clicks on Post reply.
</p>
<p>
<img src="https://i.imgur.com/wODH5K3.png"/>
</p>
<p>

</p>
<br />
Step 34: For this next step click on the post internal notes tab. This tab is where only internal deskagent and sysadmin employees can see notes, not the client/customer/or backend user. It's still important to keep comments liberal and respectable.
</p>
<p>
<img src="https://i.imgur.com/XrFjWtZ.png"/>
</p>
<p>

</p>
<br />
Step 35: As you can see John sends an internal note to another agent in the department. Make sure to click Post Note at the bottom. 
</p>
<p>
<img src="https://i.imgur.com/o4FvEb2.png"/>
</p>
<p>

</p>
<br />
Step 36: Now that ticket has been resolved click on the status dropdown menu link.
</p>
<p>
<img src="https://i.imgur.com/ZDqDoFI.png"/>
</p>
<p>

</p>
<br />
Step 37: Click on resolved. 
</p>
<p>
<img src="https://i.imgur.com/oGwPkX8.png"/>
</p>
<p>

</p>
<br />
Step 38: Status should be set to Resolved. Add in a breif note in the text box below describing the current status (optional). Then press close.
</p>
<p>
<img src="https://i.imgur.com/r8QKP8a.png"/>
</p>
<p>

</p>
<br />
Step 39: Last and final scenerio, go back onto the Support Center home page. Click on Open A New Ticket. 
</p>
<p>
<img src="https://i.imgur.com/LoqtpJr.png"/>
</p>
<p>

</p>
<br />
Step 40: Backend user Karen will be sending in the ticket. Make sure to add in her email, name and phone number.
</p>
<p>
<img src="https://i.imgur.com/ieYt9UO.png"/>
</p>
<p>

</p>
<br />
Step 41: For Help Topic Select Report a Problem/ Personal Computer Issues.
</p>
<p>
<img src="https://i.imgur.com/7xhYn5V.png"/>
</p>
<p>

</p>
<br />
Step 42: Underneath Ticket details for Issue Summary the CFO's laptop will no longer turn on. Enter that in the Issue Summary title box. Press Create Ticket.
</p>
<p>
<img src="https://i.imgur.com/kXe7ond.png"/>
</p>
<p>

</p>
<br />
Step 43: Make sure to be logged into the deskagent/admin page account as John. Click on the Subject line to open the ticket. 
</p>
<p>
<img src="https://i.imgur.com/IZDFi3w.png"/>
</p>
<p>

</p>
<br />
Step 44: Set the priority level to Emergency.
</p>
<p>
<img src="https://i.imgur.com/ds53uxT.png"/>
</p>
<p>

</p>
<br />
Step 45: For the SLA Plan set to Sev-B since this might possibly be a slightly severe issue but not that much. 
</p>
<p>
<img src="https://i.imgur.com/Wyx4jvM.png"/>
</p>
<p>

</p>
<br />
Step 46: Make a note that SLA plan may get reclassified. Press Update.
</p>
<p>
<img src="https://i.imgur.com/p9Nqzbc.png"/>
</p>
<p>

</p>
<br />
Step 47: Go to the Assigned to line and click on the dropdown menu. John Doe will be taking the ticket himself. Select his name. 
</p>
<p>
<img src="https://i.imgur.com/Q0ZNYmH.png"/>
</p>
<p>

</p>
<br />
Step 48: Click the Assign button. 
</p>
<p>
<img src="https://i.imgur.com/HT6Lzpy.png"/>
</p>
<p>

</p>
<br />
Step 49: In the post reply section John sends a note about CFO's broken charger and that being the root cause as to why his laptop wouldn't turn on. Make sure to click on Post Reply. 
</p>
<p>
<img src="https://i.imgur.com/FipdLkj.png"/>
</p>
<p>

</p>
<br />
Step 50: 
Next, go to status and click on the 'open' link to bring up the drop down menu.
</p>
<p>
<img src="https://i.imgur.com/QIO20qM.png"/>
</p>
<p>

</p>
<br />
Step 51: Click on Resolved.
</p>
<p>
<img src="https://i.imgur.com/4MJCCWv.png"/>
</p>
<p>

</p>
<br />
Step 52: Resolved should be selected and make a note in the text box the status of the issue. Click on the Close button. 
</p>
<p>
<img src="https://i.imgur.com/GSkbptD.png"/>
</p>
<p>

</p>
<br />
Step 53: The ticket has successfully been resolved and closed. If you want to see all the previouse resloved and closed out tickets you must first log out of Johns account as a desk agent and log back in as the admin user. Helpdesk agents accounts weren't programmed to see resolved and closed out tickets on their user dashboard only admin users. 
</p>
This here concludes the project tutorial and walkthrough steps of different scenerios that take place during the life-cycle of a ticket within the osTicket Ticketing software program.
</p>
<p>
<img src="https://i.imgur.com/HsdCivl.png"/>
</p>
<p>

</p>
<br />


