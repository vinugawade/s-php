# s-php :- version switcher for linux

![OS](https://img.shields.io/badge/Linux-white?style=flat-square&logo=linux&logoColor=black)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![GitHub](https://img.shields.io/github/license/vinugawade/s-php?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/vinugawade/s-php?style=flat-square)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/vinugawade/s-php?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/vinugawade/s-php?style=flat-square)

If you're on linux system with PHP installed via apt, you may be looking for an easy way to switch between PHP versions (5.6, 7.0, 7.1, 7.2 etc) without executing multiple commands manually. Well, this package is it.

## Installation

```bash
git clone git@github.com:vinugawade/s-php.git
```

Move the script using below command

```bash
sudo mv /location/of/file /usr/local/bin
```

Allowing everyone to execute the script, enter:

```bash
sudo chmod +x /location/of/file

OR

sudo chmod 0755 /location/of/file

```

Add `/usr/local/bin` to your `$PATH`. If you use the Bash shell, you can do this by running this command:

```bash
export PATH=$PATH:/usr/local/bin

OR

export PATH=$PATH:/location/of/file
```

This will set the variable name: potentially in a file called `~/.bash_profile`, `~/.bashrc` or `~/.profile`. The difference between these files is (primarily) when they get read by the shell. If you're not sure where to put it, then `~/.bashrc` is a good choice.

> **You may need to restart your shell for this to take effect.**

## Usage

```bash
s-php 5.6
s-php 7.0
s-php 7.1
s-php 7.2
s-php 7.3
s-php 8.0
s-php 8.1
```

## Screenshot

![Screenshot of s-php script](https://user-images.githubusercontent.com/65772870/184223193-4ebf4ae1-b06b-454c-9572-6716355a8624.png)

## About Me

Connect with me :-
<p align="left">
<a href="https://github.com/vinugawade" target="_blank"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" alt="vinugawade" height="30" width="40" /></a>
<a href="https://twitter.com/vinugawade" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="vinugawade" height="30" width="40" /></a>
<a href="https://linkedin.com/in/vinu-gawade" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="vinu-gawade" height="30" width="40" /></a>
<a href="https://instagram.com/vinugawadevr" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="vinugawadevr" height="30" width="40" /></a>
</p>

![Made With](https://ForTheBadge.com/images/badges/built-with-love.svg)
