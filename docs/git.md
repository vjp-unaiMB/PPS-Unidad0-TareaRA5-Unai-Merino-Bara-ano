# Git
## (Creación de repositorios)

Para la creación de neustro repositorio GIT de esta actividad seguiremos los siguientes pasos:

## Paso 0: Reubicación.

Para comenzar esta tarea es importante ubicarse y saber lo que haremos de allí en adelante. 

Estando dentro de la máquina kali, comenzaremos la actividad creando una nueva carpeta que llamaremos: `PPS-Unidad0-TareaRA5-Unai-Merino-Barañano`

Dentro de esta carpeta organizaremos nuestros archivos y alojaremos el repositorio de GIT local de este proyecto.



## Paso 1: Reutilización de material.

Copiaremos en el nuevo directorio algunos archivos del repositorio local de la actividad anterior *DevSecOps* quedándonos con la carpeta `/calculadora` y junto a ella otra carpeta `/docs` vacía.

![Img0](/Capturas/git-caps/cap1.png)

De momento la estructura de nuestro directorio corresponde a:

```
PPS-Unidad0-TareaRA5-Unai-Merino-Barañano
├── calculator/  
│   ├── __init__.py  
│   └── gui.py  
└──  docs/  
```

## Paso 2: Inicialización de repositorio.

Abriremos un terminal en Root y accederemos a la carpeta, desde donde ejecutaremos los siguientes comandos para:

1. Acceder a la carpeta `cd /home/PPSUnai/Desktop/PPS-Unidad0-TareaRA5-Unai-Merino-Barañano/`
1. Crear repo local `git config --global init.defaultBranch main
`
1. Inicializar Git `git init`

![Img1](/Capturas/git-caps/cap2.png)

De momento la estructura de nuestro directorio corresponde a:

```
PPS-Unidad0-TareaRA5-Unai-Merino-Barañano
├── calculator/  
│   ├── __init__.py  
│   └── gui.py  
├── docs/   
└── .github/  
    └── workflows/  
        └── deploy_docs.yml 
```