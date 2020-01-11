Repositorio con la imagen de reveal.js.

Esta imagen se utiliza como base para construir las diapositivas de los diferentes cursos.

## Construir la imagen

```bash
> DOCKER_BUILDKIT=1 docker build -f Dockerfile -t hub.docker.com/becorecode/revealjs:3.8.0 reveal.js-3.8.0
```
