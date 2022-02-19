# Food 4 Lives
# Partner Organization: Food4Lives
[Food for Lives](https://food4lives.org/) is a nonprofit organization, based in Atlanta, Georgia, that serves the homeless community by providing free access to meal services, protective shelter, and educational resources.  Like most nonprofits, Food for Lives relies heavily on the generosity of donors and service volunteers.  Yet as essential as charitable donations are to the normal functioning of this organization, it is imperative that Food for Lives maintains a consistent and meaningful supply of volunteers to effectively serve the needs of the homeless.  In order to meet this objective, Food for Lives has stressed to our development team the importance of informing prior, current, and prospective volunteers of the dynamic needs of the homeless community in a timely and reliable manner.

## Problem Statement / Partner’s Needs + Challenges
As it stands, Food for Lives relies on a variety of different social media platforms (Facebook, Instagram, Slack, Clubhouse), several messaging services (e-mail, phone texting, instant messaging), and the company website to communicate the current needs of the organization to the public and to coordinate events with volunteers.  This complicated and cumbersome system of communication has become somewhat of a logistical nightmare that stifles the ability of Food for Lives to maintain and grow the pool of volunteers.  Most notably, the current system makes it difficult to provide volunteers with on demand information regarding the location and specific details of individual volunteer events.  This predicament is exacerbated by the fact that the personnel at Food for Lives lack the technical expertise to make regular updates to their company website; The site was developed by a third party.  Furthermore, Food for Lives has expressed their dismay with their inability to share a visual presentation of individual volunteer events that is easily accessible to volunteers and donors: Many volunteers prepare thousands of meals offsite yet have been unable to observe a single instance of their contributions in action.  Therefore, our partner organization has communicated their need for a unified communication platform that can be updated regularly with pertinent information regarding the organization and specific volunteer events.  Additionally, the organization needs a medium that would allow volunteers to easily communicate with each other during the course of volunteer events.

## Proposed Solution / Project Solution
We are planning to develop a mobile application that would work for both Android and Apple devices.  Although our primary target audience for this app would be volunteers, we will also incorporate information that would allow users to donate funds to the organization. Our application would include a social media feed, an instant messaging tool, a schedule of volunteer events with the exact location, and user profiles. 

## Incorporating Feedback
We will schedule weekly meetings with our partner organization contact, Powell Harris. During these weekly meetings, Tuesday at 7pm, we will ask for meaningful feedback and provide status of incorporating prior feedback into our application. Additionally, we will request feedback from our TA, Shivam Rustogi, during his office hours.  

## Software Development Life Cycle 
Our plan for development is to utilize Github as our repository. We already created an organization account called food4lives. Our work items will be tracked in Github and pull requests (PRs) will be created to incorporate our changes into the main branch. These pull requests will be reviewed and approved by other members of the team before merging. In evaluation, the team will test the application and volunteers can test during the beta release. We will also meet with our partner organization to gather feedback iteratively. For our deployment phase, we will work with the partner organization to deploy the apps to the app store. Overall, we plan to work in agile.

## Initial Design Architecture
For our initial design architecture, we are using Flutter for the frontend and AWS Amplify for the backend. AWS Amplify will be used for authentication, backend, and hosting the database. AWS Amplify also holds the schema for the data. Flutter will utilize the data held in Amplify and be used on the client side to create the UI for the app. 

## Team Members 
- Cyndi Chin - UI / UX, Front-End Development 
- Renil Abdulkader - Back-End Development, Authentication
- Michael Rojas - Project Management

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQo7pznALUM1vouZ35UvNtAuS-Pc0ZM2R0kHXlHR-xVYfY17Ub_brtS6aoVPA6vtSf2v5QdzmoWYL3b/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
