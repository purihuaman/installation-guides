# Configuring Prettier

Download the "prettier" extension in your favorite editor or IDE

### 1. First step

```
npm i -D -E prettier

or

pnpm i -D -E prettier

```

### 2. Second step

```
npm i -D -E eslint-config-prettier

or

pnpm i -D -E eslint-config-prettier
```

### 3. Third step

Create a ".prettierrc" file and add following code

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

### 4. Fourth step

Create a ".prettierrc" file and add following code

```
dist
package-lock.json
```
