# Oppidum

PC-less DevOps setup, main goal is to migrate completely from local terminal to remote.

## Why?

There are two main reasons:

1. **Docker Desktop**

   Running Docker on Mac OS or Windows is pain, not to mention new [licencing](https://www.docker.com/pricing/faq) policy. With remote development this is not the case as we use native docker on linux.

2. **Environment setup**

   With defined remote environment we are guaranteed that migrating to new machine will not lead to lost setup.

3. **Work everywhere**

   With remote environment we can use slower devices like tablets without caring on platform performance and architecture.

## How?

Currently I have choosen [Gitpod](https://gitpod.io/) as best balance of UX, OSS and cost. This repo is my main environment with all configuration and tools I use as DevOps. For specific projects I will use their respective repositories.
