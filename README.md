# FISL 15 - Mozilla Web Science Lab

This is the slide deck for my talk about [Mozilla Web Science
Lab](http://mozillascience.org/) at [FISL 15](http://softwarelivre.org/fisl15).

To view it just open [index.html](index.html).

## License

CC-BY.

## Dependencies included

- [shower](https://github.com/shower/shower)
  - directory: `shower`
  - license: MIT

## Translations

It's use [Translate
Toolkit](http://docs.translatehouse.org/projects/translate-toolkit/en/latest/index.html)
for the translation of the slides.

### Generate translated slides

~~~
$ make generate LANG='xx'
~~~

where `xx` is the code of desired language.

### Manage translations

To create a new translation:

~~~
$ make create LANG='xx'
~~~

To update/merge a translation:

~~~
$ make update LANG='xx'
~~~
