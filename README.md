# javascript_package_managers
Una presentación de manejadores de paquetes en Javascript

## Qué es un manejador de paquetes?

"Un manejador de paquetes es una colección de herramientas de software que
    automatiza los procesos de instalación, actualización, configuración y remoción de programas
    (librerias o frameworks en este caso)" - Wikipedia.

## Por qué un manejador de paquetes para Javascript?

   Nos guste o no Javascript se ha convertido en uno de los lenguajes mas diversificados de la web.
   A la fecha existen miles de framweworks y librerías basadas en Javascript.

## Frameworks y Librer&iacute;as basadas en Javascript

|Nombre|Uso/Propósito|
|-----|------|
|MariaJS|MVC framework|
|AureliaJS|UI framework|
|Lodash|Utility Framework|
|Meteor|Build env Framework|
|101|Utility Framework|
|ExpressJS|Server framework|
|RaphaelJS|Vector Graphics Library|
|BackboneJS|MVC framework|
|EmberJS|MVC framework|
|Jasmine|Testing framework|
|KnockoutJS|MVC framework|
|EnzymeJS|Testing framework|

Y much@s más ...
    Cómo manejo todas esas dependencias?
    Boilá y ahí entran en acción los manejadores de paquetes de Javascript

<img class="center" src="./images/days_without_a_javascript_framework.png" alt="memeloper" />

### dependencies:
Son dependencias indispensables para que la aplicación funcione.

### devDependencies:
Son dependencias utilizadas solo para desarrollo. Estas dependencias no se instalan si el Node ENV es producción.

### peerDependencies:
Son dependencias comunes entre las dependencias directas y las subdependencias de otras dependencias.

## Especificaciones Semvers</h1>
    - Patch releases: 1.0 or 1.0.x or ~1.0.4
    - Minor releases: 1 or 1.x or ^1.0.4
    - Major releases: * or x</p>
(npm Semver Calculator)[https://semver.npmjs.com/]

## Cuál es el manejador de paquetes m&aacute;s popular ahora mismo?
Voy a mencionar los más populares, algunos de ellos ya no tanto pero aún son mencionados

    - Bower
    - NPM
    - Yarn

## (Bower)[https://bower.io/]
<img class="logo" src="./images/bower_logo.png" alt="bower logo" />

### Características:

    - Para paquetes de Front-end
    - Se recomienda instalación con NPM
    - Soporta instalar paquetes sin conexión a Internet


### Principales comandos
 ```bash
    npm i -g bower
    bower init
    bower install (-S / -D) (--offline)
    bower cache (list / clean)
    bower list –paths
    bower update
    bower register
    bower search
 ```

## (NPM)[https://www.npmjs.com/]
<img class="logo" src="./images/npm_logo.png" alt="npm logo" />

### Características:

    - Para paquetes de Front-end & Back-end
    - Se recomienda instalación con Node or NVM
    - No soporta instalar paquetes sin conexión a Internet

### Principales comandos
  ```bash
    npm init (-y)
    npm install (-S / -D)
    npm list (--json=true / --depth=0)
    npm outdated
    npm uninstall
    npm publish
    npm dedupe
    npm unpublish
    npm repo
    npm root
    npm search
    npm version
  ```

## (Yarn)[https://yarnpkg.com/]
<img class="logo" src="./images/yarn_logo.png" alt="yarn logo" />

### Características:

    - Para paquetes de Front-end & Back-end
    - Se recomiendaba instalaci&oacute;n con NPM
    - Soporta instalar paquetes sin conexión a Internet

### Principales comandos
  ```bash
    yarn init (-y)
    yarn add (-D / -P / -O )
    yarn upgrade
    yarn remove
    yarn / yarn install
    yarn publish
    yarn info
    yarn ls (--json=true / --depth=0)
    yarn outdated
    yarn run &lt;script name&gt;
    yarn version
  ```

### Velocidad
  ```bash
    npm => react 0.14.8 => 15.9 seg
    yarn => react 0.14.8 => 8.56seg
  ```
