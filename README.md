# Contributing
This repository contains information on how to contribute to this GitHub organization in the form of this README.md, other files, and documents and links.

This document should be considered a work in progress and will change as new standards and technologies emerge.
Please be sure to read this documentation on how to contribute so that we all can have a great experience!

Feel free to ask questions about anything in this document 

# History
This organization is a fork of the [TERRA REF](https://github.com/terraref) project (and might be thought of as TERRA REF 2.0).
The TERRA REF project was built up around the world's [largest mobile agricultural gantry sensing platform](https://terraref.org/).
As that project was wound down, ownership of the gantry was passed to the [University of Arizona (UA)](https://www.arizona.edu/).
This organization arose out of the need to adapt the processing pipeline to the UA [CyVerse](https://cyverse.org/) environment, and to extend it to support sensors mounted on drones, tractors, and carts.

As part of the technology associated with the gantry ownership transfer, a rework on the existing code was required.
Given the extent of the changes required and desired, this GitHub organization was created.
Some of the primary factors requiring changes are reduced support personell, different infrastructure, and leveraging HPC.
Some of the desired changes are simplifying transfer of technology (making it easy to run in alternate environments), standardization of workflow processes (encapsulated as 'extractors'), making contributions of scientific algorithms as easy as possible, and dynamic workflows.

# Reaching Goals
To reach the goals of providing a stable, flexible workflow that minimizes customization and easing the development of scientific algorithms, we are implementing constraints on how to contribute to the organization, and documenting our standards.

# Repositories
The organization of repositories for organizations/projects this size can be an issue.
One important way of managing this is to use appropriate naming conventions so that repos are easy to find.
Another aspect is to keep a repository's meaning clear; for example. don't combine administrative scripts with product code.



# Branches
There are several ways of handling branching in repositories.

For any repositories containing code, tests, scripts, and other executables we use a [master/develop methodology](https://git-scm.com/book/en/v2/Git-Branching-Branching-Workflows) with other branches for feature/issue development.
We also support pull requests from other organizations as well as personal repos.

For all other repositories, we strongly recommend using master/develop branching as above.
Please use a methodology that makes sense for your project and document the rules.

# Coding Standards
