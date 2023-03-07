# Shepard-Setups

# Alpha release! User feedback, code contributions and/or bug reports are greatly appreciated!

[Shepard](https://github.com/Jmevorach/New-Shepard) setups from the Shepard User Community for use by anyone.

If you add a setup please make sure to documentation inside the folder containing your setup so fellow Shepard users know how to run jobs on the setup and any other useful information! 

## Table of contents

- [Shepard-Setups](#shepard-setups)
  - [Getting Started Using These Setups](#getting-started-using-these-setups)
    - [Instantiating a Flock and Deploying Code to it](#instantiating-a-flock-and-deploying-code-to-it)
    - [Hello World Example](#hello-world-example)
  - [Joining the Shepard Dev Team](#joining-the-shepard-dev-team)
    - [How to Join the Team](#how-to-join-the-team)
    - [General Team rules](#general-team-rules)

## Getting Started Using These Setups 

### Instantiating a Flock and Deploying Code to it

Deploying your code to Shepard and instantiating a new flock or reconfiguring an existing flock is all accomplished with one command: ```shepard deploy```.

You can either use Shepard deploy with a deployment folder hosted publicly in the [Shepard-Setups](https://github.com/Jmevorach/Shepard-Setups) repository or use one hosted on your local machine.

The Shepard CLI will detect this for you automatically when you go to run Shepard deploy. If your argument to `path_to_deployment_folder` is an absolute filepath then Shepard CLI will look locally on your machine for a deployment folder. If `path_to_deployment_folder` is a string then Shepard CLI will check Shepard-Setups for a folder with the same name and use that as your deployment folder.

A properly formatted Shepard deployment folder is a directory containing two sub-directories; one named "code" and another named "infrastructure".

### Hello World Example
```
pip install shepard
shepard deploy --path_to_deployment_folder testing-setup
shepard batch_via_api --json_payload '{"an_example_variable_name":"an_example_variable_value"}'
```

## Joining the Shepard Dev Team

### How to Join the Team
Send an email to the Shepard Dev Team at shepard_dev_group@googlegroups.com. Ask that you be added to the Google user group and the github repos which are, for reference, this repo and the Shepard Setups repo. 

### General Team rules
1. Be nice to each other!
2. Have fun!