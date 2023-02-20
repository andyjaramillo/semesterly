# Documentation Quiz

Please visit the [docs](https://semesterly-v2.readthedocs.io/en/latest/index.html) and
answer the following questions.

1. What is the command I run to get the courses from Fall 2021?
python manage.py ingest jhu --years 2021 --terms Fall
1. How do I then load those courses into my database?
python manage.py digest [SCHOOLCODE]
1. How do I get a terminal running in my docker container?
 docker start --attach --interactive 
1. Where do I store data such as passwords or secrets that I don’t want to commit?
semesterly/dev_credentials.py
1. What branch do I create a new branch off of when developing?
 branch off of develop 
1. If I want to start on a feature called myfeature, what should the branch name be?
feature/your-branch-name
1. What is the preferred format for commit messages?
"Topic: Message"
1. What linters do we run against our code?
ESLint style guideline as configured in our .eslintrc.js file
1. What is a FeatureFlowView?
It connects the endpoint with incoming requested json data.

When you are done answering the questions, create a PR for a discussion of your answers.