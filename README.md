# Altamont Sample Interview Project
Thank you for taking the time to apply to Altamont Company.  To better understand our tech stack and what daily tasks would look like, this sample project has been prepared.

Completion of this is not timed; 100% completion is not required - or even expected.  Instead, this is meant as a starting point for the conversation of what programming duties look like.  Anything left incomplete isn't a demerit but an opportunity to learn and discuss.  It is highly unlikely any candidate would have experience in every single technology we use - what's important is a willingness to learn and a tenacity to overcome unexpected problems.

---

## Summary
This sample project is simple: **create a Vue Frontend app which features a Flask (or FastAPI) backend with some sort of database access using Docker/docker-compose.**

The app that you create is at your discretion - something like a calculator, tic tac toe, or simple chat system are all fine examples.  We use Docker and docker-compose for our system deployments - if you wish to create a Kubernetes deployment, that is fine but certainly not required.

We currently use Vue 2, but if Vue 3 is more familiar to you, please feel free to use it.  We use Bootstrap, but any styling framework is optional.

Our development philosophy heavily emphasizes Test Driven Development, so testing and coverage is a critical component.

### System Components
- Docker/Docker Compose (or K8 manifest for the overly ambitious)
- Python3 Flask or FastAPI backend.  This should be a separate container.
- Some kind of database connection (Mongo, MySQL, SQLite, etc).  This should be a separate container.
- Vue frontend app.  This can be it's own container or can be developed locally.  We use Bootstrap for styling, but that's an optional addition
- Testing with PyTest and Jest for backend and frontend respectively.  We rely on code coverage as our main testing metric.
- [Optional] Load balancer proxy (something like Nginx, Traefik, or Caddy)

## Submission
We use Git and specifically Github fairly extensively.  Please fork this repository and then open a pull request with your project, so we can discuss it.

There is no time limit.  Take your time and understand the technologies in use.  If there is anything you don't understand, please don't hesitate to ask.  Google is your friend!

---

Thank you for your interest in Altamont Company.  Please remember this project is not meant as a bar for entry - the purpose is for you to understand the technologies the position uses and facilitate further discussion.

Any questions, please contact Chester Enright at cenright AT altamontco DOT com.

Thank you!
