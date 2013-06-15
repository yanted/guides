# Deployment/release guidelines

* Always inform client (if there's one) after a release (unless project has continuous deployment)
* Always deploy green master, no red master, no green feature branch
* Deploy to staging/beta servers to test code in a production-like environment first
* Deployment must be possible by running a single command (from local machine)
* Deployment must be possible by clicking a link in [Jenkins](http://jenkins-ci.org)
* Deployment must take less than 1 minute actual interaction, preferably less
  than 10 seconds
* Everyone in the team must be able to deploy, every time
* Write release notes/history and add them to the repository
* Always tag releases (if not handled by deployment)
* Use semantic versioning if versioning is needed
* Use feature switches if it makes sense
