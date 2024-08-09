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

 Create a couple of tickets as an external user (Customer):

  - Open your browser, and go to http://localhost/osticket/
  -  Click 'Open a New Ticket'
  -  Enter the customers Contact Information -> Email Address\ Full Name\ Help Topics (Choose from the ones created in post-installation or any)
  -  Fill out the 'Ticket Details' -> Issue Summary (create your own) -> Breif sentence in the empty detail box (create your own)
  - Click 'Create Ticket' 
  - Once the ticket is created you'll get an automatic thank you message from the Support Team


![image](https://github.com/user-attachments/assets/1258a44b-fa1d-4529-8fed-53cc237c3818)

![image](https://github.com/user-attachments/assets/6cad6fc0-6df0-490e-9ed7-197979548af7)

![image](https://github.com/user-attachments/assets/62e7ef55-a93f-4d28-b6b2-4ec8a7f0bf61)

![image](https://github.com/user-attachments/assets/285da751-7e15-45e6-a897-04089c871e28)







Work your Tickets!

- Close out your osTicket browser as an external user and log back in as an Agent (Help Desk Professional) -> http://localhost/osTicket/scp/login.php
  
   *Note: Log in is as Jane Doe or John Doe (Agents created from post-installation)

  ![image](https://github.com/user-attachments/assets/dc767bfb-2774-4006-9b25-0d6af780e931)
  
   *Note: If you do not see any tickets after logging in as an Agent, log back out and log back in with your admin credentials (the credentials created when installing osTicket)
           - Go to the Admin Panel -. Agents -> Select the Agent having trouble viewing tickets -> Go to the Access tab -> Add Extended Access -> Save Changes


  ![image](https://github.com/user-attachments/assets/fa269ce8-ee24-4577-9e70-b46ee221ceed)


  ![image](https://github.com/user-attachments/assets/c38a970c-eac6-4378-85c5-38c8211869af)




Congratulations, your troubleshoot was sucessful! Back to working tickets!

- Log out and log back in with your Jane Doe credentials
- Open a ticket (select either of the ones created)
- Make sure the the priority settings, and the SLA's are set on the tickets
- Assign the ticket to an agent
- Enter a brief note in the empty reponse box
- Post Reply 
    *Note: Only assign a ticket to a different department if it cannot be solved by the default assigned department.
- Go back to 'Open Tickets' to view the ticket you made updates on
- Click on the ticket you recently worked and set the Ticket Status to 'Resolved' indicating something was actually done
    *Note: Enter a brief note in the emppty detail box explaining what was done
     -Post Reply
- To view 'Closed' tickets, simply click 'Closed' and you should see the ticket that was just resolved

  ![image](https://github.com/user-attachments/assets/db5635f3-ee89-4648-b7ae-317c515a2576)

  ![image](https://github.com/user-attachments/assets/cef28729-e995-4a63-994b-e6613ccf5dd1)

  ![image](https://github.com/user-attachments/assets/b05a2ea2-88e0-4823-857a-8150db3517bc)

  ![image](https://github.com/user-attachments/assets/0664e905-c011-43b6-9ac5-54aee9a8560c)

  ![image](https://github.com/user-attachments/assets/9bc10ba6-1ed8-4c94-baab-1dd1cc6813dc)

  ![image](https://github.com/user-attachments/assets/e5c2e129-1fbf-43e9-8dde-bea86d1e2287)


Going back to Open Tickets: 

 - Select another ticket
 - Repeat the steps as needed and be sure to set the Priority and SLA appropriately
 - Assign to a different Agent, i.e John Doe
 - Enter a brief note in the empty reponse box
 - Post Reply
 - Click on Open Tickets and view that the ticket is now Assigned to John Doe
     *Note: If you need to delete a ticket, select the box next to the ticket number and click delete on the far righr (mini trash can
 

   ![image](https://github.com/user-attachments/assets/da0d6845-0c9c-4696-9ae5-e75ac39476c8)

   ![image](https://github.com/user-attachments/assets/397f4e26-2b0c-4f8a-a2b1-bb7509b67519)

   ![image](https://github.com/user-attachments/assets/5fa33be8-2ea7-4c2a-8486-3e09f2401e5e)


Work your last ticket:

- Select the ticket
- Repeat the steps as needed and be sure to set the Priority and SLA appropriately
- Assign to an Agent (either Jane or John)
- Enter a brief note in the empty reponse box
- Resolve the ticket if you are already signed in as the Agent assigned for the ticket

![image](https://github.com/user-attachments/assets/fe1f329f-a38f-4c0a-91b4-128a5d1a5b82)

![image](https://github.com/user-attachments/assets/a1fde081-cdf8-41e2-a095-86e1704da81e)


Log back in as John and resolve that ticket:
 - Select the ticket that was assigned
 - Look through the history of the ticket
 - Enter a brief note in the empty response box
 - Select the 'Ticket Status' as 'Resolved'
 - Post Reply
   
![image](https://github.com/user-attachments/assets/78de701e-544c-4ab5-8ad2-6c896e5bb75e)

![image](https://github.com/user-attachments/assets/933d71a2-d14b-4d6d-8ad5-c2ff8134a408)

![image](https://github.com/user-attachments/assets/6801c919-8ecd-4a85-81e6-06fc9711a004)

![image](https://github.com/user-attachments/assets/54543c7d-a101-48a3-8868-aebd873c06ba)

 *Note: If you were unable to select 'Resolve' under John Doe, log out and log back in with your admin credentials (created when osTicket was installed), go to 'Admin Panel' -> Agents -> Agents -> Select John Doe -> click the Access tab -> Change the 'View Only' access to 'Supreme Admin' -> Save Changes

 ![image](https://github.com/user-attachments/assets/e5afdcfd-9a05-4115-819d-5f89fa2f1130)

 ![image](https://github.com/user-attachments/assets/17dbaad5-3874-4bf5-8652-91ca919563bf)




Congratulations, all tickets have been resolved and/or closed!

![image](https://github.com/user-attachments/assets/2be288d2-f08e-471b-86dd-5be564f725c5)
