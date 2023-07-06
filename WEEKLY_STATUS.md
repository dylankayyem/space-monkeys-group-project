## Space Monkies Weekly Status Updates

### Meeting 1: 6/21/2023

Attendees: Michael Becker, Travis Byrne, Cyro Freire de Lima, David Hughes, Dylan Kayyem

Scrum Master: David Hughes

**Progress on the project from the previous sprint:**

1. Scheduled weekly meeting time and set up Zoom meeting: Thursdays @ 7:30PM MST

2. Created Slack workspace

3. Created Project Proposal Document

4. Created Github Repository

5. Created Trello Board

6. Created Google Drive folder

7. Shared Personal User Manuals for each team member via Slack

8. Created Project Scope Ideation document

9. Created Meeting Agenda template

10. Trello Board Snapshot

**What went well?**

Building out the tools to communicate and collaborate with each other (Trello, Slack, Github, Google Drive, Zoom)
User manuals - learning about each other’s work and communication styles
Everyone showed up to weekly meetings and participated

**What didn’t work?**

Having a clear path forward for next week
Kicking off coding for project

**How can the team improve?**

Maybe start to assign some tasks to people if everyone agrees so that we improve Communication and organization ahead of time

**Choose new scrum master for next sprint**

Mike!

**Initial project feature ideas:**

<u>Features:</u>
1. Store data

2. User retrieves data

3. Visualize data

<u>Architecture Brainstorm:</u>

Welcome Interface

1. Hospital Blood Transactions

   •	Blood donation entry

   •	Transfusion entry

2. Find available blood

   •	Search/View any hospital’s inventory

      a) Proceed to checkout
        
   •	Optimal match search

      a) Proceed to checkout
    
3. Complications

   •	Record
    
   •	Search


### Meeting 2: 6/29/2023

Attendees: Michael Becker, Travis Byrne, Cyro Freire de Lima, David Hughes, Dylan Kayyem

Scrum Master: Michael Becker

#### Weekly Info
Weekly Standup (~5 minutes total for all team members) Each team member must provide the following:

•	What did you do last week?

1. Project Mock 

2. Database Mock

3. Reviewed other mocks

4. Reached out to professor about services for front end and back end: do stuff locally

5. Updated Git to not have .ipynb file

•	What are you doing this week?

1. Markdown file in Git

2. Working on Milestone 3 due next week

3. Finalize outline for application architecture

4. Looking for user stories

•	Are any obstacles stopping you?

1. Waiting on decision for today’s meeting to start html

2. Watching course videos

#### End-of-Sprint Demonstration (~10 minutes)
<u>Progress on the project from the previous week:<u>

•	Work completed tonight will be updated in markdown file and pushed to Git

•	User stories, come up with your own before next week

<u>What we have achieved for the sprint:<u>

We finalized the initial application architecture, finalized the initial database architecture, decided who would be using the application, agreed on assumptions:

**Who would be using the site?**

1. Hospital/bank administrator

**Assumptions**

1. Assumed the application is stored on a server that only hospital/bank administrators can access application

2. Secure login is already established

3. All hospitals are already in database so no need to ever create a new one with our system

4. Automated dispose of expiration (list by date of donation, 42 days after donation shelf life)

5. Minimum stock levels (can’t go below a certain threshold)

6. Home button on every subsequent page

7. Each transaction is one unit


**Proposed Application Architecture**

Welcome Interface with About page (Who is eligible to donate blood?, etc.)

1. Hospital Blood Transactions

    • Blood donation

    • Transfusion (need to make sure blood is in bank)

    • Sending blood from one hospital to another (checkout)

2. Find available blood

    • Show all hospitals in one visual

    • More detailed view of specific hospitals inventory with search/list

        - Go to send to blood to another hospital page(button at bottom of page)
        
3. Complications

    • Report

    • View reports for specific hospital and blood type


**Proposed Database Architecture**

<u>Blood Banks and Hospitals Table</u>
    
    - Hospital ID
    - Type
    - Name
    - City
    - State
    - A+ Inventory
    - A- Inventory
    - B+ Inventory
    - B- Inventory
    - AB+ Inventory
    - AB- Inventory
    - O+ Inventory
    - O- Inventory

    
<u>Donor Table</u>
    
    - Donor ID
    - Name
    - Blood Type
    
    
<u>Patient Table</u>
    
    - Patient ID
    - Name
    - Blood Type
    
    
<u>Transaction Table</u>
    
    - Transaction ID
    - Donation
    - Transfusion
    - Transport
    - Date
    - Donor ID
    - Patient ID
    - Medical Professional
    - Hospital ID
    
    
<u>Complication Table</u>
    
    - Transaction ID
    - Comments

#### Sprint Retrospective (~5 minutes)
What went well:

•	Everyone had great mock ups and attempted the project

•	Helpful to have visuals for everyone to discuss

What didn't work:

•	Different platforms made it more difficult for people to view others work

How can the team improve:
    
•	Keep working as a team

### Meeting 3: 7/6/2023

Attendees: Michael Becker, Travis Byrne, Cyro Freire de Lima, David Hughes, Dylan Kayyem

Scrum Master: Michael Becker