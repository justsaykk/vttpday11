# Day 11 Notes

### CLI commands for springboot
1. To complile: `./mvnw package` <br/>
2. To run: `./mvnw spring-boot:run` <br/>
3. To run with args: `./mvn spring-boot:run -Dspring-boot.run.arguments=“--port=3000 --logLevel=TRACE”` <br/>

### How to update a git branch

1. Switch to the branch that needs to be updated using: `git checkout <branchname>` <br/>
2. Merge the other branch using: `git merge <other branchname>` <br/>
3. Push the updates to remote repo: `git push -u origin <branchname>` <br/>

### How to deploy to Heroku

1. Install Heroku CLI (google it!) <br/>
2. Go to branch that needs deployment using: `git checkout <branchname>` <br/>
3. Login to heroku via CLI and follow instructions: `heroku login` <br/>
4. Create heroku app if needed using: `heroku apps:create` <br/>
5. Check that there is a remote heroku repo: `git remote -v` <br/>
6. Push to heroku: `git push heroku main` or `git push heroku master` <br/>
