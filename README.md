 📚 Wiki-ICM

Bienvenido a **Wiki-ICM**, un repositorio colaborativo de material de estudio diseñado para estudiantes de la **Universidad de Concepción (UdeC)**, enfocado principalmente en la carrera de **Ingeniería Civil Matemática**.

El objetivo de este proyecto es centralizar apuntes, guías y bibliografía para facilitar el estudio y el intercambio de conocimiento entre generaciones.

## 📂 Contenido

Los recursos están organizados siguiendo la estructura curricular de la carrera:

* 📘 **Malla Ingeniería Civil Matemática:** Apuntes, guías, certámenes pasados y libros de los ramos obligatorios.
* 🛠 **Recursos Adicionales:** Bibliografía recomendada, herramientas de software y plantillas LaTeX.

## 🗂 Estructura de Carpetas

Para mantener la consistencia, el repositorio organiza los ramos por semestre y, dentro de cada uno, separa el material por año o por tipo de recurso (libros/certámenes).

La estructura sugerida es la siguiente:

```text
wiki-ICM/
├── Semestre_01/
│   ├── Ramo_01/
│   │   ├── 20xx/
│   │   │   ├── Apuntes/
│   │   │   └── Listados/
│   │   ├── 20yy/
│   │   ├── Certamenes/
│   │   └── Libros/
│   └── Ramo_02/
├── Semestre_02/
│   ├── Ramo_03/
│   └── ...
└── Recursos_Adicionales/
```

> **Nota:** La carpeta `Certamenes` dentro de cada ramo está pensada para recopilaciones globales. Si tienes una pauta específica de un año (ej. Pauta Certamen 1 2024), es preferible ponerla dentro de la carpeta del año `2024`.

## 📥 ¿Cómo descargar el material?

Este repositorio utiliza **Git LFS** (Large File Storage) debido al tamaño de los archivos (PDFs, imágenes, etc.). Es importante seguir estos pasos para descargar los archivos correctamente y no solo los enlaces simbólicos.

### Requisitos previos
1. Tener instalado **Git** ([Descargar aquí](https://git-scm.com/downloads)).

### Pasos de instalación

Abre tu terminal (o Git Bash en Windows) y ejecuta los siguientes comandos en orden:

```bash
# 1. Inicializar Git LFS
git lfs install

# 2. Clonar el repositorio
git clone https://github.com/wiki-ICM/wiki-ICM.git

# 3. Entrar a la carpeta
cd wiki-ICM
```

## 🤝 ¿Cómo aportar material?

¡Toda ayuda es bienvenida! Para mantener el orden del repositorio, actualmente gestionamos las contribuciones de forma directa.

1. **Contactar:** Envía un mensaje a cualquiera de los administradores que aparecen en la pestaña de Contributors.
2. **Formato:** Asegúrate de que el material siga la estructura de carpetas mencionada arriba.
    * Si es material nuevo (ej. apuntes de este año), crea la carpeta del año correspondiente (ej. `2025`).
    * Nombra los archivos claramente.

