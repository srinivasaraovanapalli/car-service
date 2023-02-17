# car-service
step1:- created spring boot project "car-service" in local workspace
step2:- run below commands -> git init
                           -> git status
                           -> git add .
                           -> git commit -m "initial commit"
                           -> git status
step3:- open github -> create new repository with different name example->sri-projects
                    -> add README.me file
                    -> create repository
                    -> copy the project clone url
step4:- execute git commands on car-service project -> git remote add origin https://github.com/srinivasaraovanapalli/sri-projects.git
                                                    -> git push -f origin master (before this command try to run git pull)
step5:- now this code with saved into repository with out car-service name 
step6:- if we need car-service as a repository name, execute 
        -> git remote rename origin upstream below commands
        -> git remote add origin https://github.com/srinivasaraovanapalli/car-service.git
        -> git push -f origin master
        
        
