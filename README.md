# mule4-hello-world-impl

## Scope of this Project 
---
This hello-world project explains the best CI / CD practices. 

### CI Approach
---
- CI refers to Continuous Integration. Continuous integration is a DevOps software development practice where developers regularly merge their code changes 
into a central repository, after which automated builds and tests are run.

>Continuous integration refers to the build and unit testing stages of the software release process. 
 Every revision that is committed triggers an automated build and test.
 
- This Continuous Integration requires setting up a good repository branching strategy. Our strategy includes the below list of the branches. 
	* feature - feature branches for every feature or bug 
	* qa - Intermediate branch before the code is being shipped to master
	* master - Production code based branch tracked with the >Git tags.
	
<picture>
  <img alt="Shows an illustrated Branching strategy with a nice diagram." src="/exchange-docs/ci-cd-branching-pipeline-strategy.jpeg">
</picture>
 
