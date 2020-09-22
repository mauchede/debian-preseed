# README

Automating Debian installation

⚠️ This project is no longer maintained. ⚠️

## Usage

```sh
bin/retrieve-images

sudo bin/build-stick /dev/sdb

export PRESEED_COUNTRY=FR
export PRESEED_HOSTNAME=my-debian-computer
export PRESEED_KEYMAP=fr
export PRESEED_LANGUAGE=fr
export PRESEED_LOCALE=fr_FR.UTF-8
export PRESEED_PASSWORD=PASSWORD
export PRESEED_USER_FULLNAME="Morgan Auchede"
export PRESEED_USERNAME=morgan
export PRESEED_TIMEZONE=Europe/Paris

sudo -E bin/configure-stick /dev/sdb
```

## Links

* [automatiser une installation de debian (fr)](https://wiki.deimos.fr/Automatiser_une_installation_de_Debian)
* [debian wheezy keyboardless](http://stratusandtheswirl.blogspot.fr/2012/03/debian-testing-wheezy-keyboardless.html)
* [mauchede/version-lister](https://gitlab.com/mauchede/version-lister)
* [preseed example](https://www.debian.org/releases/jessie/example-preseed.txt)
* [preseed snippets (fr)](https://medspx.fr/blog/Debian/preseed_snippets/)
