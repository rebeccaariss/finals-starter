## Organizations:
GET api/organizations - Retrieve a list of all organizations.
GET api/organizations/:id  - Retrieve details of a specific organization. 
PUT api/organizations/:id - Edit a specific organization.
GET /organizations/signup - Render a register page for organizations.
POST api/organizations - Create a new organization.
 
## Item_Requests:
GET  api/item-requests - Retrieve a list of all item requests.
GET api/item-requests/:id - Retrieve details of a specific item request.
PUT api/item-requests/:id  - Edit a specific item_request
POST api/item-requests - Create a new item request.
 
## Donations:
GET api/donations - Retrieve a list of all donations.
GET api/donations/:id - Retrieve details of a specific donation.
POST api/donations - Make a new donation.

## Projects

GET api/organizations/projects - Retrieve a list of all projects

GET api/organizations/projects/:id - Retrieve details of a specific project

PUT api/organizations/projects/:id - Edit a specific project

POST api/organizations/projects - Make a new project

## Volunteering options
GET  api/volunteer-opt  - Retrieve a list of all item volunteer options. 
GET api/volunteer-opt/:id  - Retrieve details of a specific volunteer option.
PUT api/volunteer-opt/:id  - Edit a specific volunteer option
POST api/volunteer-opt - Create a new volunteer option.

## Users:

GET users/login - This route renders the login form page

POST users/login - submit the form data

## Organizations

GET organizations/register - This route renders the register form page

POST organizations/register - submit the form data
