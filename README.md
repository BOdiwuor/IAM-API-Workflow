# IAM-API-Workflow
The goal of this project is to simulate the Identity Lifecycle Management process, including user onboarding, identity verification, access management, and user offboarding. The Postman API platform was used to send REST API requests to the ReqRes API and analyze the responses returned. During testing, I discovered that ReqRes functions as a mock API rather than a persistent backend database, meaning requests such as POST simulate successful user creation without permanently storing records. 

## Technologies Used
- Postman
- ReqRes API
- REST APIs
- JSON

## API Methods Practiced

| Method | Purpose |
|--------|---------|
| POST | Create/provision user |
| GET | Retrieve user |
| PATCH | Update user access |
|PUT | Update entire user record|
| DELETE | Deprovision user |


## IAM Concepts Demonstrated
- Identity lifecycle management
- User provisioning
- Access modification
- User deprovisioning
- API workflows

## Project Structure

iam-workflow-api/
│
├── screenshots/
├── postman/
└── README.md

## Lessons Learned
- Understanding REST API methods
- Working with JSON request bodies
- Understanding status codes
- Simulating IAM workflows
- Organizing API collections in Postman
