# GIT basics
This repository contains a list of useful git commands, markdown basics, git workflow and management. I will be updating this repo when I have time.

# Table of contents
1. <a href=#>Markdown basics</a>
2. <a href=#>Git Basics</a>
    * <a href=#>Setting up our git identity</a>
    * <a href=#>Basic commands</a>
    * <a href=#>Workflow</a>
    * <a href=#>Security</a>
3. <a  href=#>Generating SSH keys</a>
4. <a  href=#>Managing multiple SSH keys for different github accounts</a>


## Managing multiple SSH keys for different github accounts
If you have multiple github accounts for whatever reason you may run into issues with ssh keys. This is because a public/private key pair can only be used on one github account. You will not be able to use the same public key you used on one github account on another account. To resolve this issue we will need to generate an additional ssh key pair and create a ssh config file ```~/.ssh/config``` to help us switch identities depending on the repository. You will also need to ensure there is a known hosts file.
