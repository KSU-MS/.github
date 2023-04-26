KSU MS general workflow---------------------


main- code which has been tested and known good, cannot directly push, must make a pull request and then have it approved

testing- combine all branches into this to test with other ongoing changes if ready to push to main

legacy- code pulled from elsewhere and snapshotted with the orginal version of the code


Workflow for implementing new features-----------------------
 
Create issue detailing new idea

Create branch for new idea, link to issue

Make the code

Pull request new branch to testing branch

Test code as a whole on testing branch

if work, pull request testing to main to solidify changes
