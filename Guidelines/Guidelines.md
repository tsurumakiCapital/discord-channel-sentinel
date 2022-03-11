# discord-channel-sentinel

This is a project aimed to learn and apply software development skills and best practices at a level of a small team, through building a useful small project.

**Description of the project**

We have an (unmanned) channel keeping receiving regular messages from another app. Would like to have a bot in that channel keeping watching new messages, and send an alert email to a predetermined address. This app consists of the following components:

* An active bot installed in a channel specified by the user
* Keep receiving messages in a VM/container.
* Send an email using a third-party service if the message stream is interrupted.

**Practices to be applied**

We classify the practices into the following categories according to when they are applied

1. **Things to fix before starting coding**

    * Preparation: environment setup
    * Determine a software architecture
    * Coding styles and rules

2. **Rules to follow when writing scripts**

    * Coding efficiently
    * Before each commit

3. **Automate works after each commit**

    * Implement CI/CD workflows and know what happens
    * Automate doc generation using sphinx


## Practices
Here is the detailed list of practices we are going to follow

### 1.Things to fix before starting coding

#### Preparation: environment setup
Set up a new python virtual environment for this project.

Config files added at this step are listed below, make sure you
understand the purposes of them and how to add them to your new project.

1. `.gitignore` ([templates](https://github.com/github/gitignore))
2. `.gitattributes` (([templates](https://github.com/alexkaratarakis/gitattributes)))

#### Determine a software architecture

to be added

#### Coding styles and rules

See `CodingStyles.md` for details.
 

### 2.Rules to follow when writing scripts

Packaging the scripts.
Write unit test for all the functions.

#### Coding efficiently

#### Before each commit

### Automate works after each commit

#### Implement CI/CD workflows and know what happens
We will use GitHub Actions for now. Other players include:
* CircleCI
* semaphore
* ...

#### Automate doc generation using sphinx


#### README for your project

Use [readme.so](readme.so) to reduce your workloads.


## References
[Intermediate Research Software Development in Python](https://carpentries-incubator.github.io/python-intermediate-development/)
