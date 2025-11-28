# GitActions
## (Workflow & MkDocs)

En este apartado añadiremos funcionalidad a nuestro proyecto mediante la configuración de MkDocs y Workflow.

## Paso 1: MkDocs

En este paso agregaremos a nuestro proyecto el fichero `mkdocs.yml` y lo configuraremos para que sirva nuestra documentación.

* Creamos el fichero ***hijo directo del directorio principal*** `nano mkdocs.yml`
* Rellenamos el fichero:

![img1](Capturas/gitActions-caps/cap1.png)

## Paso 2: Workflow

Nuestro archivo workflow nos permitirá ejecutar una serie de instrucciones al poner en servicio nuestro proyecto, para configurarlo seguiremos los siguientes pasos:

* Creamos la raíz de directorios necesarios  `mkdir -p .github/workflows`

* Dentro de la carpeta workflows creamos guardamos el siguiente archivo de configuración para pipeline: `nano /.github/workflows/CreacionDocumentacion.yml`

![img2](Capturas/gitActions-caps/cap2.png)


3. Confirmar, commitear y hacer push
bash
git add .github/workflows/ci.yml
git commit -m "Añadir workflow básico de GitHub Actions"
git push origin main
4. Verificar en GitHub
Entra al repo en GitHub → pestaña Actions.

Deberías ver el workflow “CI” ejecutándose en el último push; si algo falla, copia el log del job y lo revisamos.

Si tu actividad pide pasos específicos (tests, build de Docker, etc.), dime qué exige el enunciado de gitActions.md y se adapta el ci.yml a lo que te están pidiendo exactamente.


## RESULTADO FINAL:

```
PPS-Unidad0-TareaRA5-Unai-Merino-Barañano/
├── calculator
│   ├── __init__.py
│   └── gui.py
├── docs
│   ├── Capturas
│   │   └── ...
│   ├── conclusiones.md
│   ├── docker.md
│   ├── git.md
│   ├── gitActions.md
│   ├── gitPages.md
│   └── index.md
├── mkdocs.yml
├── requirements.txt  
└── .github
    └── workflows
        └── CreacionDocumentacion.yml

```