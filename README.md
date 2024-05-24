# Nikitha_CypressTest
added recently to work on tendable
worked on tendable.com used Cypress Framework - in Javascript language Steps to run test project:

Create an account in gitHub
Create a repository for the project
Copy the link and then go to cmd then give commands like cd desktop and git clone
Empty repo created
then in editor (i am using VScode), open terminal and give git init
project with package.json and others can be seen
Add cypess using npm cypress --save --dev
Now add tests in e2e by adding regression, smoke folders as user wish
Add page objects by adding folder t0 cypress project and ass objects inside it
Add test data in fixtures
Add commands in commands.js
Add scripts which to run in Package.json file
Add configuration files in cypress.config.js
Now in terminal give commands as mkdir .github, mkdir workflows
then directory is created
inside it, add built.yml files
their can be 'n' no. of yml files for running single spec or pararrel job execution file or to run a foler/suite
in yml file give the code extracting from git official site and under name:
after creating yml files give commands in terminal like git status, git add , git commit and git push
Now we can see in git>actions>workflow> under cypress run > execution goes on
it has many components like what is the suite /file runned, report, logs etc
give name: my-artifact, path: in the script of yml and add, commit, push then reports section added in gitHub actions
we can use that reports for the screenshot and vedios
if we want to see failed reports, add if: always() in the above 21st point , so failed reports can also be seen (as we have created bug report in the tendale test scenario, we can add this screenshot for that bug report)
just attach this report to the bug reports and can be sent to the dev/related team via jira or any agile managment tool. We can also simplicly send the ticket/defect ID by attaching files and providing all the steps created in bug report .
git commit -m "added all about what is the test process in cypress"
