# getNEXT Cloud Engineer Assignment

Hello and welcome, these are our assignments for the Cloud Engineer role.

In order to proceed with the interview, we would like you to pick just **one** of the below options and follow the instructions.

The options are designed to be completed within a short time frame, you will be judged on your ability to communicate clearly and
the quality of your implementation design. We will not be judging formatting, so really focus on the content (text, images and graphs) more than presentation.

The implementation design should include at minimum these parts:

- A detailed description of what the end solution would look like
- Rough steps required to fulfill it
- An explanation of why you chose this design and why it was the best one
- If there are multiple options, a user friendly description of the pros / cons of each option
- _Bonus:_ Provide an Infrastructure as Code implementation of your solution (Examples, Cloud Formation, Azure Resource Manager, Terraform, Anisable, Pulumi, Chef, Puppet, etc)

If you are unsure which Option to pick, Option 2 is the best default choice.

## Option 1 🏂 Lift and Shift

### Scenario

`Example Co` have been hearing all about the benefits of the ☁cloud☁ lately. They have an aging internal infrastructure and no IT staff to run it. They do not know much about their infrastructure.

### Inventory

**Melbourne**

- 1x server
- 10 staff

**Sydney**

- 1x server
- 10 staff

### Budget

- No more than \$1,000/m

### Objectives

The customer in this scenario doesn't have much knowledge of their infrastructure. So this will allow you to showcase your ability to gather information from the customer and consult with them to craft the best solution with limited information by _asking the right questions_

We will act as the customer in this scenario and will be unable to give you any information we think would be unrealistic for the customer to know without guidance.

## Option 2 🚴 New Office

### Scenario

`Example Co` have been rapidly expanding and they are moving to a new office. They are going to purchase brand new hardware to kit out the new office. Unfortunately, only the newly starting staff are going to the new office. Everyone else is still going to be working from the old office 😢.

Additionally, they are going to be rolling out Office 365 for all staff and this will become the primary location for all collaboration and file sharing

The new office currently has no networking setup.

### Inventory

**Old Office**

- 10 staff
- 1x Blade Server with the following specifications:
  - HP Proliant BL460C G9
  - 2 x E5-2650 V3 CPUs
  - 128Gb RAM
  - 2 x 500Gb HDDs
  - 650FLB 10/20Gb NIC
  - Running Microsoft Server 2008R2 & Active Directory
- 10Mbps down / 10Mbps up TPG Internet
- Cisco SG110-16 (16 port gigabit, unmanaged, poe)
- UniFI UAP (Wireless AP)
- 10x Microsoft Surface Pro 2's, 4GB/128GB (bought in 2014)

**New Office**

- 10 staff

### Budget

- IT Budget for the financial year is \$30,000

### Objectives

The customer is reasonably knowledgeable of their IT inventory but do not know enough to make the best decisions in terms of choosing an internet provider, networking or hardware for PCs.

They also need help in migrating to Office 365 from their existing setup

_Note:_ There's still some key questions required to be answered for this to work well, make sure to read the scenarios and inventory thoroughly and pretend `Example Co` is a real business.

## Option 3 🏓 True Cloud Solution

### Scenario

`Example Co` have a team of developers creating an application which uses blob storage (AWS S3 / Azure Blob Storage) and a PostgreSQL database

The software can handle up to 100 concurrent users per 1GB of memory or so

The users are mostly in Australia

### Inventory

- The Software
- An AWS / Azure account

### Budget

- No more than \$1000/m for Azure / AWS

### Objectives

The solution must be able to scale based on user load and must be monitored. The ideal goal is to have 99.995% uptime. Security should be considered, if there's nothing indicating thoughts on security that will be an automatic failure.

If new requirements are required from the application in order for it to scale, they can be accommodated by thd development team, but they must be known and included in the solution.

_Bonus:_ Also provide a solution to allow updates to the application (safe to make assumptions about steps required to update the application)
