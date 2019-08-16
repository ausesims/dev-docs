# DEVELOPMENT PROTOCOL & PROCEDUREES

# GIT / GITHUB REPO STRUCTURE

Each project repo is structured into phases of development. The master branch will only contain newly released code
after it has been proven stable. Therefore, for all intended purposes visitors and users are pointed to the "release"
branch by default for each project since the "release" branch will contain the most recent code.

Because of this structure it will not be unusual for the "master" branch to contain code of an earlier version than
the "release" branch.

# BRANCH LIST AND DEFINATIONS

 Branches should show the following pattern for each project from start to finish, to maintenance.

#staging
This is where the first phase of developing the code is started. A place to get the code off the ground and into
development. Staging exists solely for the purpose when development has not started, all of the information is
pieced together, and meetings are held on how to proceeded with development of the project.

#development/dev-core
Where development of the application or project starts. This phase is entered after everything is completed from
the staging phase. A framework of the code and project should be completed, and a direction on where the project
code is heading.

#unit
This is the stage before Alpha. It is this stage where unit testing is executed to see if the code is fit for use
with the application or the project.

#alpha
Alpha is the next phase after the "unit" stage and the phase where testing takes place via in-house methods. 

#beta
Beta is the stage after "alpha" is completed. The product is made available to the public or other entity for
further testing. All major bugs should be weeded-out before this stage begins.

#rc
The release candidate branch contains code which is ready for public use but may still have a few issues which
were not caught in the beta phase.

#gr
The general release branch is the branch which contains the latest extensively tested version version of code.
