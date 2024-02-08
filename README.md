# Is the baby here?

Just some slides using [reveal-md](https://github.com/webpro/reveal-md) stating if the baby is finally in prod.

## view changes locally

* to view the presentation locally the start of a server is needed
* docker
  * a `docker-compose.yml` is part of the repository
  * call `docker-compose up` and open [http://localhost:1948/slides.md]
* npm
  * install reveal-md within repository `npm install reveal-md`
  * and then call `./node_modules/.bin/reveal-md --preprocessor includes.js --css custom.css slides.md`
  * the browser should open automatically
