# Installation-guides

This is an installation guide for different JavaScript technologies.

- Vanilla

## Installing a vanilla JavaScript project with vite

### _ First form _

## Create a project with npm or pnpm

#### 1. First step

```
npm init vite@latest

or

npm create vite@latest

or

pnpm create vite
```

#### 2. Second step

### Indicate the name of the project

```
? Project name: my-app
```

#### 3. Third step

### Select JavaScript technology (Vanilla)

```
> Vanilla
```

#### 4. Fourth step

### Select a variant (JavaScript or TypeScript)

```
> JavaScript
> TypeScript
```

#### 5. Fifth step

### Enter the project

```
cd my-app
```

#### 6. Sexth step

### Inside the project

```
npm i

or

npm install

or

pnpm i

or

pnpm install
```

#### 7. Seventh step

### Start or run the project

```
npm run dev

or

pnpm run dev
```

### _ Second form _

## Create a project with project name using a Vanilla.js template

#### 1. First step

```
npm create vite@latest my-app -- --template vanilla

or

pnpm create vite my-app -- --template vanilla

```

#### 2. Second step

### Enter the created project

```
cd my-app
```

#### 3. Third step

### Inside the project

```
npm i

or

npm install

or

pnpm install

or

pnpm i
```

#### 4. Fourth step

### Start or run the project

```
npm run dev

or

pnpm run dev
```

## package.json section

Scripts section add the following code

```
"scripts": {
  "dev": "vite", // Add "--port 3000" to change the port
  "build": "vite build --mode production",
  "preview": "vite preview",
  "format": "prettier --write",
  "lint": "eslint --fix . --ext .js"
}
```
