# s-php :- version switcher for linux

![OS](https://img.shields.io/badge/Linux-white?style=flat-square&logo=linux&logoColor=black)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![GitHub issues](https://img.shields.io/github/issues/vinugawade/s-php?style=flat-square)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/vinugawade/s-php?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/vinugawade/s-php?style=flat-square)

If you're on linux system with PHP installed via apt, you may be looking for an easy way to switch between PHP versions (5.6, 7.0, 7.1, 7.2 etc) without executing multiple commands manually. Well, this package is it.

## Installation

Clone [this](https://github.com/vinugawade/s-php) repository to your local machine using below command.

```bash
git clone https://github.com/vinugawade/s-php.git
```

Move the script using below command.

```bash
sudo mv /location/of/file /usr/local/bin
```

Allow everyone to execute the script, use below command.

```bash
sudo chmod +x /location/of/file
```

OR

```bash
sudo chmod 0755 /location/of/file
```

Add `/usr/local/bin` to your `$PATH`. If you use the `Bash` shell,Then you can do this by running below command.

```bash
export PATH=$PATH:/usr/local/bin
```

OR

```bash
export PATH=$PATH:/location/of/file
```

This will set the variable name: potentially in a file called `~/.bash_profile`, `~/.bashrc` or `~/.profile`. The difference between these files is (primarily) when they get read by the shell. If you're not sure where to put it, then `~/.bashrc` is a good choice.

> **You may need to restart your shell for this to take effect.**

## Usage

Now you can use the script from anywhere in `Terminal`. below are some examples.

```bash
s-php 5.6
```

```bash
s-php 7.4
```

```bash
s-php 8.0
```

Check below attached `GIF`.
![Run s-php script](https://raw.githubusercontent.com/vinugawade/s-php/7e6100d0f54c87ecc397ca320de737ad6df87e1f/docs/assets/images/Use_of_script.gif)

## Mac User?

> **Check this** :- [sphp](https://github.com/jschaedl/sphp-osx) Repository.

## Contribution

### Step 1

- **Option 1**
  - 🍴 Fork this repo!

- **Option 2**
  - 👯 Clone [this](https://github.com/vinugawade/s-php) repository to your local machine.

### Step 2

- Make Changes! 🔨 ✏️ ⌨️

### Step 3

- 🔃 Create a new `Pull Request`.

## Maintainer ✨

Connect with me :-
<p align="left">
<a href="https://github.com/vinugawade" target="_blank"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" alt="vinugawade" height="30" width="40" /></a>
<a href="https://twitter.com/vinugawade" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="vinugawade" height="30" width="40" /></a>
<a href="https://linkedin.com/in/vinu-gawade" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="vinu-gawade" height="30" width="40" /></a>
<a href="https://instagram.com/vinugawadevr" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="vinugawadevr" height="30" width="40" /></a>
</p>

![Made With](https://ForTheBadge.com/images/badges/built-with-love.svg)

By [Vinay Gawade](https://github.com/vinugawade).

<a href="https://www.linkedin.com/in/vinu-gawade" target="_blank"><img src="https://raw.githubusercontent.com/vinugawade/s-php/7e6100d0f54c87ecc397ca320de737ad6df87e1f/docs/assets/images/media/LinkedIn.png" alt="LinkedIn QR" width="150"></a>
<a href="https://twitter.com/VinuGawade" target="_blank"><img src="https://raw.githubusercontent.com/vinugawade/s-php/7e6100d0f54c87ecc397ca320de737ad6df87e1f/docs/assets/images/media/Bmc.png" alt="Buy Me Coffe QR" width="150"></a>
<a href="https://twitter.com/VinuGawade" target="_blank"><img src="https://raw.githubusercontent.com/vinugawade/s-php/7e6100d0f54c87ecc397ca320de737ad6df87e1f/docs/assets/images/media/Twitter.png" alt="Twitter QR" width="150"></a>

<a href="https://www.buymeacoffee.com/vinaygawade" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

---

## License

Check [here](LICENSE).

![LICENSE](https://img.shields.io/github/license/vinugawade/ur-cache-cleaner?style=flat-square)
