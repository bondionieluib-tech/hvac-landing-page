**HVAC Landing Page**

A responsive HVAC landing page project created as a portfolio and development project to explore modern website deployment, frontend development, lead capture, and business automation.

This project is designed around a fictional HVAC service company and focuses on creating a practical landing page that could eventually serve as the front end of an automated lead-generation and customer-support system.

**Project Overview**

The primary purpose of this project is to build and experiment with a functional HVAC service landing page while gradually integrating automation capabilities behind the website.

The current version focuses primarily on the landing page itself, using HTML and CSS with JavaScript functionality being introduced incrementally. Rather than building a large multi-page website, the project is intentionally centered around a single landing page that communicates the company's services, value proposition, and calls to action.

The project is currently being developed and tested, so some functionality may change as new technologies and integrations are introduced.

**Goals**

The main goals of this project are to:

- Build a clean and responsive HVAC landing page.
- Practice structuring and organizing a real-world website project.
- Learn Git and GitHub for version control.
- Learn and practice Vercel deployment workflows.
- Introduce JavaScript functionality where it provides practical value.
- Build a customer inquiry and lead-capture form.
- Connect the website to an n8n automation workflow.
- Experiment with webhooks, APIs, and external services.
- Develop a foundation for future AI and business automation features.

The project is also intended to document the learning process involved in moving from a basic static website toward a more connected business automation system.

**Planned Architecture**

The long-term concept for the project is to connect the landing page to an n8n workflow.

The intended flow is:

Website
   ↓
Customer Inquiry Form
   ↓
JavaScript / API Request
   ↓
n8n Webhook
   ↓
Lead Processing
   ├── Store Lead
   ├── Notify Staff
   ├── Send Confirmation
   └── Additional Automation

The initial automation will focus on successfully transmitting structured customer inquiry data from the website to an n8n webhook.

Additional integrations may be introduced after the basic form-to-webhook connection has been tested successfully.

**Current Features**

The current project includes a single-page HVAC landing page with sections intended to represent a fictional HVAC service business.

Planned and existing website elements include:

- Hero section
- HVAC service information
- Installation services
- Repair services
- Heating and cooling maintenance
- Duct and pipe cleaning
- Inspection services
- Water heater services
- Vent cleaning
- Smart home integration concepts
- HVAC-as-a-Service concept
- Customer calls to action
- Contact or inquiry functionality
- Responsive design

The exact content and structure may continue to change during development.

**Technology**

The project currently uses:

- HTML
- CSS
- JavaScript
- Git
- GitHub
- Vercel

Additional technologies will be introduced as the automation side of the project develops.

The planned automation layer will use:

- n8n
- Webhooks
- HTTP requests
- External APIs
- Potential data storage and notification services
- Development Approach

This project is being developed incrementally rather than attempting to implement every feature at once.

The initial priority is to establish a stable website and deployment workflow. After that, functionality will be added in smaller stages.

The planned development progression is:

Basic Landing Page
        ↓
Responsive Improvements
        ↓
Contact / Lead Form
        ↓
JavaScript Form Handling
        ↓
n8n Webhook
        ↓
Lead Processing
        ↓
Notifications / Storage
        ↓
Additional Automation

This approach makes it easier to test each component independently and troubleshoot issues such as browser restrictions, CORS, webhook communication, API requests, and deployment configuration.

**Deployment**

The website is intended to be deployed using Vercel.

The GitHub repository serves as the project's source of truth, while Vercel handles deployment and hosting.

The intended workflow is:

Local Development
      ↓
Git Commit
      ↓
GitHub
      ↓
Vercel Deployment
      ↓
Live Website

This allows changes to be developed locally, committed using Git, pushed to GitHub, and automatically deployed through the connected Vercel project.

**Project Status**

Status: In Development

The current version should be considered a development and portfolio project rather than a production website for a real HVAC company.

The website, content, frontend functionality, and automation workflows may change as the project evolves.

Current development priorities include:

- Refining the landing page
- Implementing the inquiry form
- Testing form submission
- Connecting the form to an n8n webhook
- Troubleshooting cross-origin and webhook communication
- Testing automation reliability
- Improving error handling
- Documenting the final workflow
- Portfolio Purpose

This project is intended to demonstrate more than frontend design.

The larger objective is to demonstrate how a simple business website can become the starting point for an automated business process.

The landing page represents the customer-facing portion of the system, while n8n will provide the automation layer responsible for processing information submitted through the website.

This project therefore provides an opportunity to practice several areas of modern digital operations, including frontend development, deployment, version control, webhooks, APIs, automation workflows, data handling, and eventually AI-assisted processes.

**Future Improvements**

Potential future improvements include:

- Improved form validation
- Lead qualification
- Automated email responses
- Internal lead notifications
- Google Sheets or database integration
- CRM integration
- Appointment scheduling
- AI-assisted lead classification
- Customer-support chat functionality
- n8n chat widget experimentation
- Improved error handling and logging
- Additional security considerations
- Custom domain deployment

These features will be added selectively as the project develops rather than being implemented all at once.

Disclaimer

This is a fictional portfolio and development project created for learning, experimentation, and demonstration purposes.

The HVAC company, services, branding, content, and business processes represented in this project are not intended to represent an actual operating company unless otherwise stated.

License

This project is primarily intended for portfolio and educational purposes. Additional licensing information may be added as the project develops.
