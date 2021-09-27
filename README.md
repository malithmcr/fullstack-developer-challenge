# Sapera (Mid)Frontend Developer Challenge

> Hello, thank you for taking on our challenge! We hope that you'll enjoy creating an awesome project and join the Sapera team.

**Note:** Please don't fork this repository, or create a pull request against it. Otherwise other applicants may take inspiration from it. Once the coding challenge is completed, you can submit your github repository url via email.

## The Process


Create a new repo wherever you like. Can be GitHub/GitLab etc..,

The project should be contained in one repository (monorepo), Example:

```bash
├── server
├── client
├── docker-compose.yml
└── README.md # documentation
```

You can keep API (Backend) code in the `server` folder and UI code in the `client` folder (This is just an example but you can decide however you want).
After you completing the project, Send us an email and we will have it reviewed

## The Challenge

#### Build a job listings web appliaction

Create a very simple web application that shows list of job opportunities and a Rest APIs where you can get all the job data. Jobs should be filterable by Location, Department and Type. As a reference you can follow Sapera [job page](https://sapera.com/en/career)


### Acceptance Criteria
- Your React app fetches data from the API you created and displays it in the UI
- Your API has two endpoints. One for getting list of jobs and one for filtering.
- When user filter a job, Your react app fetches data from the filtering endpoint.
- Your app is easy to install and run locally
- The code is clean, well-structured and easy to understand
- It's up to you to decide about the database setup(if needed).


### Bonus  (not required but nice-to-have)
- Using Redux or any State managment library.
- Unit tests for both React and PHP code.
- Dockerize your app. This way we can run both API and UI in a single command. `docker-compose up`.

### Stack and technical requisites

- Use React.js or any React framwork.
- Feel free to use any CSS or SCSS framwork.
- Use PHP for the rest API
 
__You don’t have to worry about:__

- An admin panel
- Detailed(Single) Job page
- Deployment
- CI configuration
- Secret Management
