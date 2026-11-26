# **CloudVault — Project Explanation**

**Full project name:** CloudVault — AI-Powered Enterprise Document Management and Workflow Automation Platform

## **1. What is CloudVault?**

Imagine a company has three offices: Toronto, Vancouver and Calgary. Each office has hundreds of employees working in different departments.

Every day, employees create invoices, contracts, reports and confidential documents.

The company faces several problems:

- Documents are scattered across different computers.
- Employees struggle to find important files.
- Confidential documents are sometimes shared with the wrong people.
- Managers spend time manually reviewing documents.
- Employees repeatedly perform the same administrative tasks.
- Multiple copies of the same document create confusion.

CloudVault is a centralized application that solves these problems through **secure file management, artificial intelligence and workflow automation.**

Think of it as a combination of:

| Existing application     | What we will take inspiration from |
| ------------------------ | ---------------------------------- |
| Google Drive             | File storage and sharing           |
| Microsoft SharePoint     | Enterprise document management     |
| Microsoft Power Automate | Workflow automation                |
| ChatGPT                  | Intelligent document assistant     |
| Microsoft Azure          | Cloud storage architecture         |

## **2. How will CloudVault work?**

Imagine an employee uploads an invoice without knowing where to save it.

**Employee uploads a file**

invoice_2026.pdf

**AI reads the document**

Identifies it as an invoice worth $6,000.

**CloudVault recommends a folder**

Toronto → Finance → Invoices → 2026

**Automation checks company rules**

Invoices above $5,000 require senior manager approval.

**Manager receives a notification**

Reviews and approves the invoice.

**Workflow completed**

File organized securely, database updated and activity recorded.

Instead of an employee performing every step manually, our application handles much of the work automatically.

## **3. Main features of CloudVault**

**1. Intelligent document management**

Upload, download, rename, move, share, preview and restore documents.

**2. Hierarchical file storage**

Organize documents by country, city, office, department and subfolder.

**3. User management and security**

Give administrators, managers, employees and guests different access permissions.

**4. Artificial intelligence**

Read documents, extract information, generate summaries and recommend folders.

**5. Workflow automation**

Allow administrators to create automatic business rules using a drag-and-drop interface.

**6. RAG document assistant**

Allow employees to ask questions about documents they are authorized to access.

**7. Version control**

Keep previous versions of documents and restore them when necessary.

**8. Analytics and monitoring**

Track document activity, storage consumption, automation performance and system health.

**9. Cloud-compatible infrastructure**

Simulate Azure storage and cloud infrastructure locally without a paid subscription.

## **4. What will we build in our first prototype?**

Imagine we are building a smart car. Before adding automatic driving, sensors and voice control, we need to make sure the car can actually move.

Similarly, our first CloudVault prototype will prove that our basic idea works.

Proposed prototype design — illustrative data, not an implemented application yet.

| Functionality     | Prototype                | Final project                        |
| ----------------- | ------------------------ | ------------------------------------ |
| Dashboard         | Basic                    | Interactive analytics                |
| File upload       | Local storage            | Azure-compatible storage             |
| Folder management | Basic folders            | Complete nested hierarchy            |
| File operations   | Upload, download, delete | Sharing, versioning, restoration     |
| Automation        | Predefined rules         | Visual workflow builder              |
| AI                | Not yet integrated       | Local LLM, OCR and RAG               |
| Database          | PostgreSQL               | PostgreSQL, MongoDB, Redis           |
| Security          | Local demo only          | Keycloak and RBAC                    |
| Cloud             | Local development        | Complete Docker-based infrastructure |

Nothing is being removed. We are building the foundation first.

## **5. How will the technologies communicate?**

**Frontend — React.js**

What the user sees and interacts with.

**REST API — Node.js + Express.js**

Receives requests and performs operations.

**PostgreSQL**

Stores users, folders and file information.

**File storage**

Stores the actual uploaded documents.

This is our initial prototype architecture. Later, we will connect Python, FastAPI, MongoDB, Redis, Azurite and our AI services.

## **6. Why is this a good full-stack developer project?**

| Skill                 | Practical implementation                             |
| --------------------- | ---------------------------------------------------- |
| Frontend development  | React, TypeScript, HTML, CSS                         |
| Backend development   | Node.js, Express.js, Python, FastAPI                 |
| UI/UX                 | Figma, responsive design, accessibility              |
| SQL                   | PostgreSQL, joins, transactions, recursive queries   |
| NoSQL                 | MongoDB and Redis                                    |
| OOP                   | Classes, objects, inheritance, encapsulation         |
| Software architecture | Controllers, services, repositories                  |
| Data structures       | Trees, graphs, queues, hash maps                     |
| Algorithms            | Searching, sorting, recursion, graph traversal       |
| AI engineering        | RAG, OCR, embeddings, LLM integration                |
| Automation            | Triggers, conditions, actions and background jobs    |
| Cloud engineering     | Azure SDK, Azurite, Docker, NGINX                    |
| Cybersecurity         | Authentication, authorization and file security      |
| Debugging             | VS Code, breakpoints, logging and exception handling |
| DevOps                | GitHub Actions, CI/CD, Prometheus, Grafana           |
| Software testing      | Jest, pytest, Playwright                             |

## **7. Professional project description**

You can use this description when introducing the planned project to someone.

CloudVault is an AI-powered enterprise document management and workflow automation platform designed to centralize, organize and secure business documents across multiple office locations and departments.

The platform will combine full-stack development, intelligent document processing, configurable workflow automation, role-based access control and semantic search. It will use React.js, TypeScript, Node.js, Python, PostgreSQL, MongoDB and Docker, with Azure-compatible storage through Microsoft Azurite.

CloudVault will follow an incremental development approach, beginning with a functional prototype and evolving into a complete, cloud-ready enterprise application.

## **8. Our project target**

Original development tasks

# **125**

AI and automation tasks

# **30**

Total tasks

# **155**

Total modules

# **31**

Prototype target

# **2–3 days**

Estimated full development

# **8–10 weeks**

Features removed

# **0**

Required cloud subscription

# **$0**

Estimated timeline with AI-assisted development. Local AI performance will depend on your computer's hardware.

**Our primary objective is to build a professional full-stack application that uses AI to solve real business problems, rather than simply building an AI chatbot.**
