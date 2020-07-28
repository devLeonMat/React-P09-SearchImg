# React-P09-SearchImg

## Proyecto para buscar imagenes con el api de pixaby
### stack:
1. React
2. Hooks
3. Bootstrap 5 Beta
4. Rest API

```bash
RUN
$ npm start

http://localhost:3000/
```

Registrate y genera un key

https://pixabay.com/api/docs/

```bash
const key = 'key';  // pegar aqui el key
const url = `https://pixabay.com/api/?key=${key}&q=${busqueda}&per_page=${imagenesPorPagina}&page=${paginaActual}`;
```
