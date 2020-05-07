# PROJECT: THE INTRICATION OF DOCKER-COMPOSE,JENKINS,GIT AND GITHUB
The project is splitted into three parts .Each of them are here to automate the work of operators and these are some of the overviews of what can be achieved by technology.
These are as follows:-
 
-   **Job1** - If Developer commit to *dev2* branch then Jenkins will start  downloading GitHub new data and deploy on  test environment.
- **Job2** - If Developer commit to *master* branch then Jenkins will start  and deploy on website (*master*) environment.
- **Job3** - Manually the QA team will check (test) for the website running in test environment, If it is running fine then master developer will merge the *dev2* branch to *master* branch and trigger job
## PRE-REQUISITES
  - Docker-CE
  - REDHAT:8
  - Docker
