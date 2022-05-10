# Assignment 1: Client-Side Tooling

## Source Code Control
In addition to [Git](https://git-scm.com/), additional version control systems include:\
[Subversion(SVN)](https://subversion.apache.org/): A centralized version control system\
[Mercurial](https://www.mercurial-scm.org/): A distributed version control system\
Both of these tools would be used in the same manner as Git; tracking changes to source code as development projects evolve, develop, and require revision and branching.

## Deployment Tools
[Kubernetes](https://kubernetes.io/docs/home/) is a tool for automatically starting, stopping, and restarting applications that run in containers across a distributed system, frequently a cloud-based system.
A developer would use this tool to automate manual processes for keeping applications online.\
[Docker](https://docs.docker.com/) is a tool for creating and running applications in containers - isolated environments that share host machine resources. 
A developer would use this tool to create reproducible computing environments with relatively secure separation while minimizing the required overhead to run applications in those environments.
Containerized applications strike a balance between security, reproducibility, and resource-intensity that oftentimes are preferable to virtual machines.

## Linters
[Trunk](https://docs.trunk.io/) is a multi-language tool that orchestrates management of linters and code formatters between development and deployment environments.
A developer would use this tool to synchronize linting and formatting with other developers on a team (to ensure that everyone is coding to the same standards) and with automatic formatting tools in the deployment toolchain (to ensure that development matches deployment).
