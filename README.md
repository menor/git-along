# git-along
Rules and advice to work together well and 'get along' (a little better everyday) 😉😉

## Pull Requests ##
You can create a pull request as a way to ask for someone to have a look and review your code even if the branch is not ready for merging. This way the person you ask for help can pull your branch and experiment with it in their own environment, apart from having more time to work on the issue, and be able to see the changes you made to the code isolated.

You should assign a `Work in Progress` label to that pull request, so the assigned person knows that the pull request is meant to ask for help and not ready to be merged yet.

## Collaboration branches ##
Sometimes you need to work on an feature in a team (e.g., one that involves a backend and a frontend part).  
In this case you should follow these guidelines:  
- One collaborator branches out from master and names the new branch `<issue number>-<feature name>`
- All collaborators then branch out from that issue branch and create the pull requests to that branch instead of master.
- When the main feature branch is ready, the pull request is created from that branch to master.

## Labels ##

###Subject  labels###
Subject labels are the ones related to which part of the application is affected by the issue. Expect to get more labels added to this one as the app grows. Color is SteelBlue (#4682B4)

**Labels**  
- `admin`  
- `analytics`  
- `api`  
- `bookings`  
- `emails`  
- `feedback`  
- `guests`  
- `ipad`  
- `newsletters`  
- `tickets`  
- `settings`  
- `widget`  

### Workflow labels###
Workflow labels define the position of an issue or PR in out process:

**Needs action labels**  
Color: gold (#FFD700)  
- `split into tasks`: Issue voted as a Project.  
- `discussion needed`: Needs agreement on how to solve it.  
- `review backend`  
- `review frontend`  
- `review product`  

**Approved labels**  
Color: paleGreen (#98FB98)  
- `backend approved`  
- `frontend approved`  
- `product approved`  

**Rejected labels**  
Color: firebrick (#B22222)  
- `backend rejected`  
- `frontend rejected`  
- `product rejected`  
- `blocked`: Depends on something else before it can be acted on.  
- `needs gif`: On interface changes the PR should include a gif with the new behavior.  

**Situation labels**  
Color: whitesmoke (#F5F5F5)  
- `on test`: It's on the test server.  
- `in progress`: Someone is working on it.  
- `sprint ready`: Ready to estimate.  

**Special Labels**  
color: forestGreen (#228B22)  
- `ready for merge` : Title says it all.  
- `merged`: Merged into master.  
- `deployed`: Deployed into production.  

`Work in Progress`: used for pull requests that are still not ready to be merged but are created because you need help or in-between review.
