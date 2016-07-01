# README

## Usage

```sh
bin/retrieve-images

sudo bin/build-stick /dev/sdb

export PRESEED_LANGUAGE="fr"
export PRESEED_COUNTRY="FR"
export PRESEED_LOCALE="fr_FR.UTF-8"
export PRESEED_KEYMAP="fr"
export PRESEED_USER_FULLNAME="Morgan Auchede"
export PRESEED_USERNAME="morgan"
export PRESEED_TIMEZONE="Europe/Paris"
sudo -E bin/configure-stick /dev/sdb
```

## Contributing

1. Fork it.
2. Create your branch: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin my-new-feature`.
5. Submit a pull request.

## Links

* [automatiser une installation de debian (fr)](https://wiki.deimos.fr/Automatiser_une_installation_de_Debian)
* [debian wheezy keyboardless](http://stratusandtheswirl.blogspot.fr/2012/03/debian-testing-wheezy-keyboardless.html)
* [preseed example](https://www.debian.org/releases/jessie/example-preseed.txt)
* [preseed snippets (fr)](https://medspx.fr/blog/Debian/preseed_snippets/)