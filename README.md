# Team-Management-suite

A full-stack web application for managing teams and their members, featuring a React.js frontend and a Node.js backend. Allows users to add members with details like name, unique ID, team ID, and optional image uploads via file or camera. Integrated with MongoDB for efficient data management.

## Prerequisites

Before running the project, make sure you have the following installed:
Node.js (version X or above),npm or Yarn (for managing dependencies),MongoDB
## Implemented Features:
### Structure:
 1.	Database Used: MongoDB
 2.	Schema:
-	Organization\
	name: Name of the organization \
	organizationId: Unique identifier for the organization \
	location: Location of the organization \
-Team\
	name: Name of the team \
	organizationId: Reference to the Organization \
	teamId: Unique identifier for the team 
- Member\
	name: Name of the member \
	uniqueId: Unique identifier for the member \
	teamId: Reference to the Team \
	image: Path to the uploaded image 


### Getting Started
Follow the steps below to get the project up and running on your local machine:
1. Download the Zip file
2. Install package like mongoose,express,nodemon,multer etc
3. Run the Backend using "nodemon index.js"
   
