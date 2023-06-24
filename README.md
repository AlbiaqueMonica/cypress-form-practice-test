# cypress-form-practice-test
Testing on registration functionality through a web form


CÓMO EMPEZAR:

Clona el Proyecto:

git clone https://github.com/AlbiaqueMonica/cypress-form-practice-test.git

Instala todas las dependencias:

npm ci

(el commando ci es para instalar todas las Dependencias Locked del Proyecto)

Para abrir la App de Cypress, corre el comando:

npm test

También puede usar 'npx cypress open' (ya que en Package.json tenemos la variable "test" como el "cypress open") para abrir Cypress.

Para correr pruebas y generar Reportes XML y HTML, ejecuta:

npm run file */**/<filename>

donde la variable "file" es: cypress run --browser chrome --reporter cypress-multi-reporters --reporter-options configFile=jsconfig.json --record --key {key} --spec
