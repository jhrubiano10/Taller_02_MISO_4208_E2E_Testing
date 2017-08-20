# Taller 02 MISO-4208 E2E Testing - Webdriver.io

Las pruebas se encuentran en el archivo [tests]/[specs] se siguieron los pasos para el despliegue 
de estas pruebas como se muestra en la [guía] del taller, pero al ejecutar el comando `wdio wdio.conf.js` me indicaba que el 
patron no concidía con el esperado, intente cambiar el patron en el archivo de configuración, pero siempre salía el mismo error.

![error](https://github.com/jhrubiano10/Taller_02_MISO_4208_E2E_Testing/blob/master/images/webdriver_no_funciona_comando.gif?raw=true)

Por lo que se ejecutó las pruebas con el comando `wdio --spec tests/specs/nombretest.spec.js` 

Para las pruebas se seleccionaron dos casos como son:

## Crear usuario

* [Crear un usuario]

![web01](https://github.com/jhrubiano10/Taller_02_MISO_4208_E2E_Testing/blob/master/images/webdriver_Crea_usuario.gif?raw=true)

## Filtrar cursos.

* [Filtrar cursos]

![web02](https://github.com/jhrubiano10/Taller_02_MISO_4208_E2E_Testing/blob/master/images/webdriver_Filtrar_cursos.gif?raw=true)


### Autor
* Jorge Rubaino [@ostjh]
* Código: 201510711

License
----
MIT

[@ostjh]:https://twitter.com/ostjh

[tests]:https://github.com/jhrubiano10/Taller_02_MISO_4208_E2E_Testing/tree/master/webdriver-io/tests/specs
[specs]:https://github.com/jhrubiano10/Taller_02_MISO_4208_E2E_Testing/tree/master/webdriver-io/tests/specs
[guía]:https://miso-4208-labs.gitlab.io/talleres/taller-2-e2e-testing.html#3-webdriverio
[Crear un usuario]:https://github.com/jhrubiano10/Taller_02_MISO_4208_E2E_Testing/blob/master/webdriver-io/tests/specs/createuser.spec.js
[Filtrar cursos]:https://github.com/jhrubiano10/Taller_02_MISO_4208_E2E_Testing/blob/master/webdriver-io/tests/specs/filtercourses.spec.js
