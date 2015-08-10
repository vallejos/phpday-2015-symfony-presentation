
[English Instructions](#english) - [Instrucciones en Español](#spanish)


# <a name="spanish">Introduccion a Symfony 2, PHPday UY 2015</a>

Esta presentación utiliza [reveal.js](https://github.com/hakimel/reveal.js) (Requiere Node.js y Grunt.js)

Basicamente necesitas:

1. clonar este repositorio `git clone git@github.com:vallejos/phpday-2015-symfony-presentation`
2. ejecutar `grunt serve`

La presentación estara disponible yendo a `http://localhost:8000` en el navegador.

En caso de obtener algún error, consultar la sección [Installation](#installation) de la documentación de reveal.js


# <a name="english">Symfony 2 Introduction, PHPday UY 2015</a>

This presentation uses [reveal.js](https://github.com/hakimel/reveal.js) (Requires Node.js and Grunt.js)

You basically need to:

1. clone this repository `git clone git@github.com:vallejos/phpday-2015-symfony-presentation`
2. run `grunt serve`

The presentation will be available on `http://localhost:8000` in yor browser.

If you get any error, please see the [Installation](#installation) section of reveal.js documentation.


# <a name="installation">Installation</a>

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Basic setup

The core of reveal.js is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1. Download the latest version of reveal.js from <https://github.com/hakimel/reveal.js/releases>

2. Unzip and replace the example contents in index.html with your own

3. Open index.html in a browser to view it


### Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the reveal.js repository
   ```sh
   $ git clone https://github.com/hakimel/reveal.js.git
   ```

5. Navigate to the reveal.js folder
   ```sh
   $ cd reveal.js
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.


## License

MIT licensed

Copyright (C) 2015 Hakim El Hattab, http://hakim.se
