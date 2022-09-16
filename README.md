# Installation-guides

This is an installation guide for different JavaScript technologies. [Vanilla, React, Css, etc ]

## Instalación de un proyecto JavaScript vanilla con vite

### _ Primera forma _

## Crear un proyecto con npm | pnpm

#### 1. Paso

```
npm init vite@latest

npm create vite@latest

pnpm create vite
```

#### 2. Paso

### Indicar el nombre del proyecto

```
? Project name: my-app
```

#### 3. Paso

### Seleccionar la tecnologia JavaScript (vanilla)

```
> Vanilla
```

#### 4. Paso

### Select a variant (JavaScript | TypeScript)

```
> JavaScript
> TypeScript
```

#### 5. Paso

### Ingresar al proyecto

```
cd my-app
```

#### 6. Paso

### Dentro del proyecto

```
npm i
npm install
```

#### 7. Paso

### Arrancar el proyecto

```
npm run dev
pnpm run dev
```

### _ Segunda forma _

## Crear un proyecto con nombre del proyecto usando una plantilla vanilla

#### 1. Paso

```
npm create vite@latest my-app -- --template vanilla

pnpm create vite my-app -- --template vanilla

```

#### 2. Paso

### Ingresar al proyecto creado

```
cd my-app
```

#### 3. Paso

### Dentro del proyecto

```
npm i
npm install
```

### Arrancar el proyecto

```
npm run dev
```

## Apartado de package.json

Apartado de scripts

```
"scripts": {
  "dev": "vite", // Agregar "--port 3000" para cambiar el puerto
  "build": "vite build --mode production",
  "preview": "vite preview",
  "format": "prettier --write",
  "lint": "eslint --fix . --ext .js"
}
```
