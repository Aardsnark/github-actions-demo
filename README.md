"Github Action Tutorial by TechWitTim, using sample Flask app"

Workflow goal: whenever something happens in the repo, run the tests in main_test.py before someone is allowed to merge their code in the main branch

1) Setup Branch Protection Rules (GitHub)
   2) Brances / Add rule 
      3) Branch Name Pattern (regeX match or branch name (e.g. 'main'))
      4) Require Pull Requests
      5) Require Status Checks
      6) Leave "Do not allow bypassing the above settings" unchecked, allows Admins to bypass rules for pull requests
   2) Create

3) Create Workflows