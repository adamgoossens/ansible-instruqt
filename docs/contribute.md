# Contribute

We treat Ansible Automation Workshops just like we treat the Ansible Project.  Please help us!  Check out the [Issues](https://github.com/ansible/instruqt/issues) for a list of what we are working on.

## Table of Contents

* [Pull Requests ](#pull-requests)
   * [Create a fork!](#create-a-fork)
   * [Stay in Sync](#stay-in-sync)
      * [Configuring Your Remotes](#configuring-your-remotes)
      * [Rebasing Your Branch](#rebasing-your-branch)
      * [Updating your Pull Request](#updating-your-pull-request)
   * [Create a pull requests](#create-a-pull-requests)
* [Going Further](#going-further)

# Pull Requests

We take pull requests!  What is a pull request?

>Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch

More info on PRs: [https://help.github.com/en/articles/about-pull-requests](https://help.github.com/en/articles/about-pull-requests)

## Create a fork!

Create a fork on your own Github project (or your personal space)

[Github Documentation on Forking a repo](https://help.github.com/articles/fork-a-repo/)

## Stay in Sync

It is important to know how to keep your fork in sync with the upstream Workshops project.

### Configuring Your Remotes

Configure `ansible/workshops` as your upstream so you can stay in sync

```bash
git remote add upstream https://github.com/ansible/instruqt.git
```

### Rebasing Your Branch

Rebase the branch on your fork

```bash
git pull --rebase upstream devel
```

Check your status

```bash
git status
```

### Updating your Pull Request

```bash
git push --force
```

More info on docs.ansible.com: [Rebasing a Pull Request](http://docs.ansible.com/ansible/latest/dev_guide/developing_rebasing.html)

## Create a pull requests

**PULL REQUESTS MUST BE MADE INTO THE `DEVEL` BRANCH**

Make sure you are not behind (in sync) and then submit a PR to the Ansible Workshops.  
[Read the Pull Request Documentation on Github.com](https://help.github.com/articles/creating-a-pull-request/)

Just because you submit a PR, doesn't mean that it will get accepted.  Right now the QA process is manual for Workshops, so provide detailed directions on

 - WHY? Why did you make the change?
 - WHO? Who is this for?  If this is something for a limited audience it might not make sense for all users.
 - BEST PRACTICE?  Is this the "best" way to do this?  Link to documentation or examples where the way you solved your issue or improved the Ansible Workshops is the best practice for teaching or building workshops.

Being more descriptive is better, and has a higher change of getting merged upstream.  Communication is key!  Just b/c the PR doesn't get accepted right away doesn't mean it is not a good idea. Ansible Workshops have to balance many different types of users.  Thank you for contributing!

# Going Further

The following links will be helpful if you want to contribute code to the Ansible Workshops project, or any Ansible project:
- [Ansible Committer Guidelines](http://docs.ansible.com/ansible/latest/committer_guidelines.html)
- [Learning Git](https://git-scm.com/book/en/v2)
