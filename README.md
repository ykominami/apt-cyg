# apt-cyg

apt-cyg is a command-line installer for Cygwin which cooperates with Cygwin
Setup and uses the same repository. The syntax is similar to apt-get. Usage
examples:

* `apt-cyg install <package names>` to install packages
* `apt-cyg remove <package names>` to remove packages
* `apt-cyg update` to update setup.ini
* `apt-cyg list [pattern(s)]` to list packages matching given pattern. If no
  pattern is given, list all installed packages.
* `apt-cyg show <pattern(s)>` to show packages matching patterns
* `apt-cyg search <commands or files>` to locate parent packages

## Quick start

apt-cyg is a simple script. Once you have a copy, make it executable:

```
chmod +x /bin/apt-cyg
```

Optionally place apt-cyg in a bin/ folder on your `$PATH`.

Then use apt-cyg, for example:

```
apt-cyg install nano
```

## Contributing

This project has been re-published on GitHub to make contributing easier. Feel
free to fork and modify this script.

The [Google Code project](http://apt-cyg.googlecode.com) also has a list of
open issues.

## Changelog

### v0.59

* Added xz archives support

### v0.58

* Added multiarch support

### v0.57

* Tagged Google Code SVN repo status
=======
[2013-10-23] added xz archives support, autor: ernierasta
