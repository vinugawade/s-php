# PHP version switcher for Linux

If you're on Linux with PHP installed via apt, you may be looking for an easy way to switch between PHP versions (5.6, 7.0, 7.1, 7.2 etc). Well, this package is it.

Installation:

```
git clone git@github.com:vinugawade/s-php.git
```

Add `/usr/local/bin` to your `$PATH`. If you use the Bash shell, you can do this by running this command:

```
echo 'export PATH="/usr/local/bin:$PATH"' >> $HOME/.bashrc
```

You may need to restart your shell for this to take effect.

Usage:

```
./s-php/s-php 5.6
./s-php/s-php 7.0
./s-php/s-php 7.1
./s-php/s-php 7.2
./s-php/s-php 7.3
./s-php/s-php 8.0
./s-php/s-php 8.1
```
