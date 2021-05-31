# Sendinblue Full Stack Developer Challenge

> Hello, thank you for taking on our challenge! We hope that you'll enjoy creating an awesome project and join the Sendinblue team.

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

The `server` and `client` directories should have their own simple `Dockerfile`, so that they can be built and run individually.

The `docker-compose.yml` file should define all the services, which will be automatically built and started upon calling `docker-compose up`.


After you completing the project, Send us an email and we will have it reviewed

## The Challenge

#### Build a job listings web appliaction

Create a very simple web application that shows list of job opportunities and a Rest APIs where you can get all the job data. Jobs should be filterable by Location, Department and Type. As a reference you can follow sendinblue [job page](https://jobs.sendinblue.com/en/tech#Tech)


### Acceptance Criteria
- Your React app fetches data from the API you created and displays it in the UI
- Your API has two endpoints. One for getting list of jobs and one for filtering.
- Your app is easy to install and run locally
- The code is clean, well-structured and easy to understand


### Bonus
- Using Redux or any State managment library.
- Unit tests for both React and PHP code.

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