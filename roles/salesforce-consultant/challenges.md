# getNEXT Salesforce Consultant Assignment

Hello and welcome, these are our assignments for the Salesforce Consultant role.

In order to proceed with the interview, we would like you to pick just **one** of the below options and follow the instructions.

The options are designed to be completed within a short time frame, you will be judged on your ability to communicate clearly and
the quality of your implementation. We will also be judging based on ability to gather accurate requirements, quality of outcome, solutions ability to scale and _attention to detail_.

The implementation should also include at minimum:

- A description of how your implementation works and how to use it
- An explanation of why you chose this design and why it was the best one
- If there are multiple options, a user friendly description of the pros / cons of each option

If you are unsure which Option to pick, Option 2 is the best default choice.

Remember to treat these as if they were real customers genuinely making these requests and respond appropriately.

---

For any of the scenarios which require to implement something within Salesforce we recommend creating a brand new [Salesforce Developer org](https://developer.salesforce.com/signup) and sharing credentials with us to access

## Option 1 🏂 Pure Consulting

### Scenario

A customer has approached us to implement a brand new Salesforce instance. They are a Home Care provider with about 50 staff in total. 15 Call Centre agents / admins and 35 carers

### Inventory

- 15 Call Centre Agents
- 35 Registered Carers
- 0 Salesforce Licences
- No data required to import

### Budget

None given, but budget is always a constraint and should be factored into your solution choice

### Objectives

The objective of this particular option is that it's a pure consulting gig. So no implementation work needs to be given. So you will showcase your abilities by asking _the right questions_ and then formulating a good plan on how to tackle their particular challenges.

You may notice that their current pain-points or why they are choosing Salesforce are not listed here...

There's also a lot of flexibility in what kind of solution you can do here, we won't be judging too much in which direction you go for as long as you have good reasoning for why you did go in this direction.

Any questions asked about this will be answered as if it was the customer, we will only know as much as the customer would realistically know unless guided to finding out the right answer

## Option 2 🚴 Vanilla Implementation

### Scenario

A customer approaches us with an existing Salesforce implementation that they've been loving for about 3 years. They haven't made many customisations on their org if any at all. But they are looking to increase the number of users and incorporate a new division into their Salesforce org.

This customer is an IT provider and they've been using Salesforce for managing their Leads, Accounts, Contacts and Sales (Opportunities) to date for their Cloud Solution customers.

The department that is now joining their Salesforce instance is the Software Development department who have a list of current pain-points with Salesforce that they would like addressed before joining:

- They have their own customer data and they need to track the below, but it's important that the existing Cloud Solution customer records do not see this data:
  - When the original Lead came into the system
  - Xero Contact Id
  - Type of Project
  - Which developers are working on an Opportunity
- The ability to clone Opportunities with Opportunity Products (I'm aware that Salesforce is introducing this feature natively in [Spring 2020](https://releasenotes.docs.salesforce.com/en-us/spring20/release-notes/rn_general_clone_with_related.htm), please pretend this feature does not exist 😀)
  - Only required fields need to be copied
- Whenever a new Contact is added to an Account, all of that Accounts Opportunities `amount` should double
- Email notification to the manager whenever a sale is closed

### Inventory

- Salesforce Sales Cloud
  - 30 Users

### Budget

No change, new users are already purchased

### Objectives

Compared to Option 1, this has a relatively detailed list of requirements, so the burden of finding out information isn't as great. But there's still a few things that require more detail in order to implement correctly.

We also have a reasonably clear idea of what the outcome should look like but we are happy to see smart deviations from that outcome 😀.

Any questions asked about this will be answered as if it was the customer, we will only know as much as the customer would realistically know.
