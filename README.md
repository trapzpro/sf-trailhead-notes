# sf-trailhead-notes
Salesforce Trailhead Notes


## General Notes
This repo will just be tracking links and info as I work through trailmizes, badges, super badges, etc. 

Work with Leads and Opportunities
 []
 https://trailhead.salesforce.com/content/learn/modules/lex_salesforce_tour/lex_salesforce_tour_sales?trailmix_creator_id=plafonte&trailmix_slug=welcome-to-salesforce

Check Out Reports, Dashboards, Feeds, and More
[]
https://trailhead.salesforce.com/content/learn/modules/lex_salesforce_tour/lex_salesforce_tour_more?trailmix_creator_id=plafonte&trailmix_slug=welcome-to-salesforce



Blockchain 
[]
https://trailhead.salesforce.com/content/learn/modules/technologies-and-trends-of-the-fourth-industrial-revolution/understand-the-technologies-changing-the-digital-world?trail_id=4th-industrial-revolution&trailmix_creator_id=plafonte&trailmix_slug=welcome-to-salesforce

"Blockchain Applications
Blockchain is the new big data. Everyone is talking about it, and no one seems to really know what it is.

Let’s start there. Blockchain is just a way of recording and sharing data in such a way that the same data is visible to everyone. Further, blockchain ensures that the data cannot be changed without everyone knowing exactly who did what.

Blockchain technology fosters trust between two parties, even if those people are anonymous. To say it more technically, blockchain is a shared, programmable, decentralized, cryptographically secure ledger for storing digital objects and transactions. No single user or institution controls blockchain applications. Anyone can scrutinize them.

For example, Bitcoin is an example of a blockchain application. Bitcoin is a digital currency, with a public ledger for all transactions. In addition to digital currency, blockchain technology can handle any transaction that is expressible as computer code. Possible scenarios include:

Insurance claims
Votes
Real estate titles
Driver’s licenses
Someday, voting and national identities can perhaps be supported through blockchain technologies. Blockchain can possibly even be used to trace where your products came from and that they are not fakes. Blockchain is so revolutionary, people are discovering new applications for it every day.

"

-----
When Will the Future Arrive?
According to the World Economic Forum Technology Tipping Points and Societal Impact report, the following technology tipping points could occur by 2025:

10% of people wearing clothes connected to the Internet
The first robotic pharmacist in the US
The first 3D-printed car in production
5% of consumer products printed in 3D
90% of the population with regular access to the Internet
Driverless cars equaling 10% of all cars on US roads
The first transplant of a 3D-printed liver
Over 50% of Internet traffic to homes for appliances and devices
The first city with more than 50,000 people and no traffic lights
The first AI machine on a corporate board of directors
What 

----


Grow Your Business with Sales Cloud
Learning Objectives
After completing this unit, you’ll be able to:

List ways Sales Cloud can help improve your lead management.
Describe how Sales Cloud can make your sales team more productive.
Explain how the Salesforce mobile app can make your team a mobile powerhouse.
[]
https://trailhead.salesforce.com/content/learn/modules/sales-cloud-platform-quick-look/grow-your-business-with-the-sales-cloud-platform?trail_id=crm&trailmix_creator_id=plafonte&trailmix_slug=welcome-to-salesforce


Levels of Data Access
You can configure access to data in Salesforce at four main levels.

Organization
At the highest level, you can secure access to your organization by maintaining a list of authorized users, setting password policies, and limiting login access to certain hours and certain locations.
Objects
Object–level security provides the simplest way to control which users have access to which data. By setting permissions on a particular type of object, you can prevent a group of users from creating, viewing, editing, or deleting any records of that object. For example, you can use object permissions to ensure that interviewers can view positions and job applications but not edit or delete them.
Fields
You can use field–level security to restrict access to certain fields, even for objects a user has access to. For example, you can make the salary field in a position object invisible to interviewers but visible to hiring managers and recruiters.
Records
To control data with greater precision, you can allow particular users to view an object, but then restrict the individual object records they're allowed to see. For example, record–level access allows interviewers to see and edit their own reviews, without exposing the reviews of other interviewers. You can manage record–level access in the following ways.
Organization–wide defaults specify the default level of access users have to each others' records. You use organization–wide sharing settings to lock down your data to the most restrictive level, and then use the other sharing tools to selectively give access to other users. For example, you can give all employees access to an object called Candidate to allow anyone to add a candidate to the database. But you can restrict access to Positions so that anyone can see the jobs available but only the employees with the proper permissions can edit them.
Role hierarchies open up access to those higher in the hierarchy so they inherit access to all records owned by users below them in the hierarchy. Role hierarchies don't have to match your organization chart exactly. Instead, each role in the hierarchy represents a level of data access that a user or group of users needs. For example, you can restrict access to Candidates by setting the organization–wide default to Private, but allow recruiters to view and edit the candidate records that they own. Recruiters can't see candidate records they don't own because recruiters are all at the same level in the role hierarchy. However, hiring managers can be given read/write access to all candidate records because they are at a higher level in the role hierarchy than recruiters.
Sharing rules enable you to make automatic exceptions to organization–wide defaults for particular groups of users, to give them access to records they don't own or can't normally see. Sharing rules, like role hierarchies, are only used to give more users access to records—they can't be stricter than your organization–wide default settings. For example, you can allow all employees to view Positions, but use sharing rules to grant full editing access to employees in a role or group called Hiring Managers.
Manual sharing allows owners of particular records to share them with other users. Although manual sharing isn't automated like organization–wide sharing settings, role hierarchies, or sharing rules, it can be useful in some situations, for example, if a recruiter going on vacation needs to temporarily assign ownership of a job application to another employee.

https://trailhead.salesforce.com/content/learn/modules/lex_implementation_user_setup_mgmt/lex_implementation_user_setup_mgmt_configure_user_access?trail_id=lex_admin_implementation&trailmix_creator_id=plafonte&trailmix_slug=welcome-to-salesforce

Control What Your Users Can Access
Learning Objectives
After completing this unit, you’ll be able to:
Describe the difference between object and field level security
Describe how to set org–wide default sharing settingsControl What Your Users Can Access
Learning Objectives
After completing this unit, you’ll be able to:
Describe the difference between object and field level security
Describe how to set org–wide default sharing settings
[]
https://trailhead.salesforce.com/en/content/learn/modules/lex_implementation_user_setup_mgmt/lex_implementation_user_setup_mgmt_configure_user_access?trail_id=lex_admin_implementation&trailmix_creator_id=plafonte&trailmix_slug=welcome-to-salesforce

