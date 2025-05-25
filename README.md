# Ticket-Lifecycle
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

  In this lab, I practice creating support tickets from the perspective of an end user. I also review each ticket's details and respond to them as if I were a help desk technician.

<h2>Lifecycle Stages</h2>

<p>
  
![image](https://github.com/user-attachments/assets/3fec7061-35dc-4097-895a-3e3fb06a5310)

</p>
<p>
To begin, I am going to create a new ticket as an end user, Karen.
When users experience a technical problem or need help with a service, they can report the issue by submitting a support ticket. This ticket includes important information such as the type of problem, how it is affecting them, and any steps they may have already taken to resolve it. For instance, if a customer discovers that the online banking platform is completely unavailable, they can create a new support ticket and select the category "Business Critical Outage." This helps the support team understand the urgency and seriousness of the issue, as outages like these can affect many users and disrupt important transactions. Once submitted, the help desk team reviews the ticket, prioritizes it based on its severity, and begins working to resolve the issue as quickly as possible.

![image](https://github.com/user-attachments/assets/4ec87747-a8db-4f5a-8047-51495f1c58c3)

I went to the osTicket and logged in as Agent John to see the ticket created by Karen. Agents use the Agent Panel to view, update, and prioritize active support tickets. It helps them track progress and respond efficiently. Queue managers oversee ticket flow, ensuring high-priority issues are assigned to the right agents for quick and effective resolution.

![image](https://github.com/user-attachments/assets/e335a72a-bc43-466b-9b2d-9ca6fdb1790d)

As a Help Desk Agent, I will review each ticket’s priority, assigned department, SLA (Service Level Agreement), and assign an agent. If needed, I’ll route the ticket to the correct department. If the issue appears critical, I’ll contact the requester for more details and set the appropriate SLA to ensure timely resolution.   

![image](https://github.com/user-attachments/assets/e9567846-8094-47ab-8c6e-301b3f1d68fc)

This ticket is classified as an "Emergency" due to its serious impact on a vital business function. As the agent addresses the problem, the SLA is adjusted to "Sev-A" to reflect the issue’s critical nature and the need for a swift response. During the installation of this osTicket, I set "Sev-A" to 1 hour to contact the person and 24/7. 

![image](https://github.com/user-attachments/assets/f0b94ee4-0e23-4eb8-8a27-4f98d9ac38d3)

I updated the help topic to Report a problem / Business Critical Outage.

![image](https://github.com/user-attachments/assets/06819b5a-b24d-4e49-999d-e57ad8f49002)

When I refreshed the ticket, I could see all the updates.

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/a2543d12-eb4c-41ef-847d-eadb8763e33a)

</p>
<p>

I logged out as John and logged  in as Jane. 

![image](https://github.com/user-attachments/assets/eb54354c-2492-41a0-8595-182228c5a3ca)

Here, as Jane, I will work the ticket to completion. The screenshot above shows me reporting my suspicion to the team after checking the problem at the backend. 
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/3288fc5e-b78a-430d-9459-ab6d79830d51)

</p>
<p>
  
I went to Status and set the ticket to resolved. The ticket was closed after it was determined that a recent update caused the issue. Once resolved, the vendor was informed, and users could log in successfully without any further problems. The status was changed to "Resolved," and the user was notified of the solution.

![image](https://github.com/user-attachments/assets/0c0145aa-595e-4ab3-92d2-bb943c5aabc1)

As an end-user, I created the following ticket: Accounting department needs Adobe upgrade, broken

![image](https://github.com/user-attachments/assets/4e1d384f-64f5-40eb-bbb3-e7a9bc0fc4a4)

I logged in as John to observe the ticket. 

![image](https://github.com/user-attachments/assets/1341788e-17e8-4b84-88d5-2903602ed89a)

Here I can see the ticket I created. 

![image](https://github.com/user-attachments/assets/a05c04f5-1b6f-456c-ad56-25f2c36b9116)

When I opened it, I saw the complaint. So, I will contact Ken to get more info, and through that, for example, I confirmed that there are only 2 people who are having this issue.

![image](https://github.com/user-attachments/assets/3e7f801a-d1b2-42f0-87a8-f8b555787243)

With that information, I can set the SLA to Ser-C, which indicates it's not too bad. 

![image](https://github.com/user-attachments/assets/f0e47bc7-53a2-43df-93a9-a6461b9fc5ae) 

The ticket is successfully assigned to John Doe.

![image](https://github.com/user-attachments/assets/1d630fbc-f989-4761-a55b-6755402ad7cd)

So, these are all the conversations going on at the backend. The customer can see this, so be aware of this. 

![image](https://github.com/user-attachments/assets/8464c152-0f62-4e19-ab94-f3f84b80e5dd)

I went to the status and fixed the ticket as resolved. 

![image](https://github.com/user-attachments/assets/03efc6e1-4c4c-4422-be71-49e3b9cb7b1a)

The ticket is officially resolved.

</p>
<br />
