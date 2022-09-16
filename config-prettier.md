# Configurando Prettier

Descarga la extensión de "prettier" en tu editor o IDE favorito

### 1. Paso

```
npm i -D -E prettier
pnpm i -D -E prettier

```

### 2. Paso

```
npm i -D -E eslint-config-prettier
pnpm i -D -E eslint-config-prettier
```

### 3. Paso

Crear un archivo ".prettierrc" y agregar siguiente el código

```
{
	"printWidth": 80,
	"useTabs": true,
	"semi": true,
	"singleQuote": true,
	"quoteProps": "as-needed",
	"jsxSingleQuote": true,
	"trailingComma": "es5",
	"bracketSpacing": true,
	"bracketSameLine": false,
	"arrowParens": "always"
}
```

### 4. Paso

Crear un archivo ".prettierignore" y agregar siguiente el código

```
dist
package-lock.json
```
