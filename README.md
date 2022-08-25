# Apuntes importantes de TS

## Instalar como dependencia dentro del proyecto

```
npm install typescript --save-dev
```


## Transpilar a una version por defecto

```
npx tsc src/demo.ts
```

## Transpilar a la version es6 y los archivos .js enviarlos a la carpeta dist

```
npx tsc src/*.ts --target es6 --outDir dist
```

## Ejecutar archivos trascopilados


```
node dist/01-hello.js
```

## Crear el tsconfig.json

```json
npx tsc --init
```

## Ejecutar cada vez que se realiza un cambio

```
npx tsc --watch
```

Nota: El código TS no es leído por navegadores ni servidores. Lo que se hace es transpilarlo a JS.