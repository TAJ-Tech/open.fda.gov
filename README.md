
# Iterative/Agile Approach to FDA Challenge Prototype – Pool 1
# 1. Identifying the Team

TAJ team (Role and name of individual) for developing the prototype consisted of:

1.	An overall lead as well as Product Manager/Owner – Mr. Kannan Venkataraman
2.	Visual Designer – Mr. Khaja Raziuddin
3.	User Researcher/Usability Tester – Mr. Shaji Thomas

Also, we had 3 of our own internal employees serve as the SMEs to show and develop the prototype. Our own Systems Administrator, was the 7th member of the team, who helped establish the development and hosting environment.  

# 2. Discussing and deciding the approach

The Team reviewed and discussed the FDA challenge as stated on the FDA web site in deciding the approach. Given the scale and size of this prototype, Kanban/SCRUM hybrid approach was adopted for quick turnarounds. Separate sprints were not adopted for this prototype as everything was accomplished in one development cycle, iteratively. Microsoft Word was sufficient to handle the product backlog tracking, eliminating the need for a separate ALM tool.  Requirements identified were broken into smaller stories or tasks, and creating a High Level Design, with subsequent steps and process to follow. The artifacts needed for executing the project were also identified.

We conducted our daily standup/conference call to discuss work items, monitor progress, and provide feedback to resolve all issues that arose. We also used emails and short phone calls and meetings for communication.

A daily time capture was mandated for everybody in the team to monitor the time taken for developing the prototype.
# 3. Identifying the Artifacts needed for the project
The following artifacts were identified for the prototype project
Documentation:
1.	Approach document (this document)
2.	Product Backlog/Requirements
3.	High Level Design
4.	Sprint Log (recurring 15 min meeting everyday )
5.	Time tracking at the item level in Product Backlog

Software working prototype URL:
- http://216.84.172.104/drug/event/

# 4. Identifying the Requirements (Product Backlog or Stories) and High Level Design
Microsoft Word was used for capture of Product Backlog of stories and tasks for the prototype. The stories and tasks were analyzed and implemented one at a time till the prototype was completed. SME’s feedback were included and reflected in the Development Backlog. 

A High Level Design was created and used as a base to build the prototype.

# 5. Identifying the process and steps needed 
An Agile and iterative process was used to identify needs and speed development. The Product Backlog had small stories and tasks that were implanted one by one.  Time was recorded for each of the stories and tasks. Immediate feedback was given after testing each new feature for either further improvisation or approval.

# 6. Daily Standups/conference calls and monitoring progress
Daily conference calls were scheduled using Outlook. As stories and tasks were converted into solutions, developed and tested, the status was updated in the Product Backlog document.

# 7. Setting up the environment

To get us started quickly, so we could focus on development and the prototype, we mirrored the FDA site (https://github.com/FDA/open.fda.gov explains how mirror the site) and then expanded on the code base to create our own, new prototype. To achieve this, we used both the open.fda.gov and the openFDA website.

# 8. Creating and analyzing stories
The items in the product backlog first start out as requirements. We discuss and analyze each of these requirements as a team. The requirements are then converted into stories for designing solutions.  

# 9. Designing solutions for stories

We converted each story into a design and then implemented it. By keeping the solution simple we avoided the need for a separate artifact.  The approach kept the design simple so that a separate artifact need not be created for every solution and the High Level Design document suffices. When needed, the design is explained and added to the artifacts.

# 10. Implementing the design 
Designs are implemented in code and tested out based on the solution.
The open.fda.gov website was forked and checked out from GitHub and was modified to include a new tab to display Spikes for a given drug query.
The following files were modified:
- _config.yml
- static/js/api-demo.js
- _includes/api-demo-drug-event.html

We reused existing code and the UI, including the c3.js library already used by open.fda.gov used for charting. 

# 11. Reviewing and improving the prototype
The team reviewed the prototype, tested functionality and suggested recommendations. See “Screen shot.docx” file for supporting documentation.   

# 12. Hosting and the GIT repository
The prototype has been hosted at http://216.84.172.104/drug/event/

The server runs Linux and Jekyll, and the actual software is also developed using open source

The code and all the artifacts (including this document) are at the GIT repository <GIT Repository name and link>
