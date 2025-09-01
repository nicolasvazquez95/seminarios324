# Cómo hostear la página web en un servidor local

Actualmente, el sitio funciona con gh-pages + Jekyll. 
El código fuente de Jekyll está escrito en Ruby.
Con Jekyll, podemos generar un sitio web estático a partir de archivos Markdown y plantillas.

## Como hostear el sitio localmente

1. Instalar Ruby:
[Link al instalador](https://rubyinstaller.org/downloads/)

Se puede verificar la instalación de Ruby ejecutando el siguiente comando en la terminal:

```bash
ruby -v
```

1. Instalar bundler y Jekyll:

```bash
gem install bundler jekyll
```

Se puede verificar la instalación de bundler y Jekyll ejecutando el siguiente comando en la terminal:

```bash
bundle -v
jekyll -v
```

2. Iniciar el servidor Jekyll:

```bash
bundle exec jekyll serve
```

Esto iniciará un servidor local en `http://localhost:4000`, donde podrás ver tu sitio web.

Si es la primera vez, puede que sea necesario ejecutar `bundle install` para instalar las dependencias del proyecto.