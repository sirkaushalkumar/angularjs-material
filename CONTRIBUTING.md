Guideline to contribute to the website
--------------------------------------

- We accept PRs only on `develop` branch. No PRs shall be accepted on `master` branch.

- We prefer small feature changes instead of bulk changes. That makes it easier for both the developer as well as reviewer. Smaller requests would have a faster turn-around time in the review-response cycle.

Workflow
--------

If you're new to git version control system, please follow these guidelines:

- Fork the repo.
- Clone your fork.
- Add upstream remote as
    ```git remote add upstream git@github.com:sirkaushalkumar/angularjs-material.git```

- Now create a feature branch to work on the bug/feature request like
    ```git checkout -b <feature-name>```

- Start working on the issue. Commit early; commit often.

- Open up a Pull Request with base branch as `develop` and compare branch as `feature-branch` of your fork.

- Once you get review, address those in next commits. If you get `LGTM` (Looks good to me) tag on your PR, it's time to get your PR merged. Congrats. 

- Last step is to just squash all your commits into one and briefly describe what you did. (Most of the time, the reviewer shall do this for you, but it would be good if you do it by yourself.)

- After squashing, you need to force push to your feature branch.
    ```git push origin <feature-name> -f```

- Once your PR is merged, it's time to delete the feature branch from your fork (Optional, just to keep your local repo clean)
    ```git branch -D <feature-name>```

- Since the master/develop of the original project may be ahead now, it's time to pull the changes from the upstream and update on your fork
    ```git pull upstream develop```
    ```git push origin develop```

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in
response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or
reject comments, commits, code, wiki edits, issues, and other contributions
that are not aligned to this Code of Conduct, or to ban temporarily or
permanently any contributor for other behaviors that they deem inappropriate,
threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces
when an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported by contacting the project team at [INSERT EMAIL ADDRESS]. All
complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good
faith may face temporary or permanent repercussions as determined by other
members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/
