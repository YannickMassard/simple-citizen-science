# Overview

This project uses the __Cvless__ Jekyll theme as a template. 
See the [template](https://cvless.netlify.app) to get a better sense of what the theme looks like.

The main aesthetic feature of the theme is the use of [particles.js](https://vincentgarreau.com/particles.js/) in the home and the 404 pages.

## Installation

1.  Clone this repository.
2.  Rename it to `[username].github.io`.
3.  Start editing!

## Local Development

This repo includes a docker-compose file that allows you to quickly setup a container running Jekyll. If you don't already have Docker and docker-compose installed, you can install them using the following guides from Docker:

**Install Guides**
* [Docker](https://docs.docker.com/get-docker/)
* [docker-compose](https://docs.docker.com/compose/install/)

To start the container simply run:

```
docker-compose up
```

Alternatively you can run the container without docker-compose using the following command on Mac/Linux:

```
docker run -p 4000:4000 -v $(pwd):/site bretfisher/jekyll-serve
```

## Credits

The theme draws in one way or another from the following projects:

-   [Bootstrap](https://getbootstrap.com/)
-   [Hack](https://sourcefoundry.org/hack/)
-   [Iconoir](https://iconoir.com/)
-   [Open Color](https://yeun.github.io/open-color/)
-   [Particles.js](https://vincentgarreau.com/particles.js/)
-   [Piazzolla](https://piazzolla.huertatipografica.com/)
-   [Poole](https://getpoole.com/)

## Bugs

If you find any problem using this theme, please [open an issue](https://github.com/piazzai/cvless/issues).
