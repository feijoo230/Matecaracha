# Academia Matecaracha

Este es el repositorio del sitio web de la Academia Matecaracha, un proyecto creado con Jekyll.

## Cómo usar Jekyll

Jekyll es un generador de sitios estáticos que te permite crear sitios web de forma sencilla. A continuación, se detallan los comandos básicos para trabajar con Jekyll en este proyecto.

### Prerrequisitos

Antes de empezar, asegúrate de tener instalados:

- **Ruby:** [Instrucciones de instalación](https://www.ruby-lang.org/es/documentation/installation/)
- **Bundler:** Una vez que tengas Ruby, instala Bundler con el siguiente comando:

```bash
gem install bundler
```

### Instalación de dependencias

Para instalar todas las dependencias necesarias para este proyecto, ejecuta el siguiente comando en la raíz del repositorio:

```bash
bundle install
```

### Ejecutar el sitio en local

Para ver el sitio en tu máquina local, puedes usar el siguiente comando:

```bash
bundle exec jekyll serve
```

Una vez que el servidor esté en funcionamiento, podrás ver el sitio en la siguiente dirección: [http://localhost:4000](http://localhost:4000)

El servidor se recargará automáticamente cada vez que hagas un cambio en los archivos del proyecto.

### Publicar en GitHub Pages

Este proyecto está configurado para ser publicado en GitHub Pages. Cada vez que hagas un cambio en la rama `main`, GitHub Pages se encargará de actualizar el sitio web.

El sitio estará disponible en la siguiente dirección: [https://feijoo230.github.io/matecaracha/](https://feijoo230.github.io/matecaracha/)
