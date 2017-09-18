# Creamos proyecto

  `ng new miscelaneos`
  
  # Que aprendemos en está sección 
  
  Esta sección esta llena de pequeñas cosas útiles que te ayudaran a mejorar la forma en la que usas Angular.
  
  A continuación veremos:
  
  Cambios en el estilo de algún elemento HTML utilizando variables en los componentes.
  Comprender y aplicar CSS en un determinado scope, sin afectar los demás componentes. 
  Adicionar y remover clases según variables o cualquier tipo de condición.
  Crearemos directivas personalizadas.
  Uso del ngSwitch.
  Crearemos una pequeña aplicación para el uso de rutas y rutas hijas.
  Comprenderemos el ciclo de vida de un componente o directiva.
  Entre otras cosas bien interesantes.
  
  # …or create a new repository on the command line
  
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/dktomaszenko/Miscelaneos.git
    git push -u origin master
    
  # …or push an existing repository from the command line
  
    git remote add origin https://github.com/dktomaszenko/Miscelaneos.git
    git push -u origin master

# Miscelaneos

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.7.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


## Creamos nuevo componente con (Angular-cli) 
con template y estilos en el mismo fichero

    ng g c components/ngStyle -it -is
