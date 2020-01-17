# Excalidraw JSON

> This project is based on [**gae-init**](https://github.com/gae-init/gae-init).

## Requirements

- [Google App Engine SDK for Python][]
- [Node.js][], [Yarn][], [pip][], [virtualenv][]
- [macOS][] or [Linux][] or [Windows][]

Make sure you have all of the above or refer to the docs on how to [install the requirements](http://docs.gae-init.appspot.com/requirement/).

## Running the Development Environment

```bash
cd /path/to/excaliber-json
gulp
```

To test it visit `http://localhost:3000` in your browser.

---

For a complete list of commands:

```bash
gulp help
```

## Initializing or Resetting the project

```bash
cd /path/to/excaliber-json
yarn
gulp
```

If something goes wrong you can always do:

```bash
gulp reset
yarn
gulp
```

---

To install [Gulp][] as a global package:

```bash
yarn global add gulp-cli
```

## Local testing

If you wish to run an automated test script, there is an additional dependency which can be installed with:

```bash
pip install -r test-requirements.txt
```

A simple test script framework, following the approach from the [Google App Engine docs](https://cloud.google.com/appengine/docs/standard/python/tools/localunittesting#setup), can be run:

```bash
python main/runner.py --test-path tests ${HOME}/google-cloud-sdk/
```

This simply tests that the site can start up; that the index page exists (and returns an http response code of 200), and that a non-existent page returns an http response code of 404.

The test framework is easily extensible.

## Tech Stack

- [Google App Engine][], [NDB][]
- [Jinja2][], [Flask][], [Flask-RESTful][], [Flask-WTF][]
- [Less][]
- [Bootstrap][], [Font Awesome][], [Social Buttons][]
- [jQuery][], [Moment.js][]
- [OpenID][] sign in (Google, Facebook, Twitter and more)
- [Python 2.7][], [pip][], [virtualenv][]
- [Gulp][], [Bower][]

[bootstrap]: http://getbootstrap.com/
[bower]: http://bower.io/
[flask-restful]: https://flask-restful.readthedocs.org
[flask-wtf]: https://flask-wtf.readthedocs.org
[flask]: http://flask.pocoo.org/
[font awesome]: http://fortawesome.github.com/Font-Awesome/
[google app engine sdk for python]: https://developers.google.com/appengine/downloads
[google app engine]: https://developers.google.com/appengine/
[gulp]: http://gulpjs.com
[jinja2]: http://jinja.pocoo.org/docs/
[jquery]: https://jquery.com/
[less]: http://lesscss.org/
[linux]: http://www.ubuntu.com
[macos]: http://www.apple.com/macos/
[moment.js]: http://momentjs.com/
[ndb]: https://developers.google.com/appengine/docs/python/ndb/
[node.js]: http://nodejs.org/
[openid]: http://en.wikipedia.org/wiki/OpenID
[pip]: http://www.pip-installer.org/
[python 2.7]: https://developers.google.com/appengine/docs/python/python27/using27
[social buttons]: http://lipis.github.io/bootstrap-social/
[virtualenv]: http://www.virtualenv.org/
[windows]: http://windows.microsoft.com/
[yarn]: https://yarnpkg.com/
