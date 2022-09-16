# Configurando Eslint

Descarga la extensión de "eslint" en tu editor o IDE favorito

#### 1. Paso

```
npm i -D -E eslint
pnpm i -D -E eslint
```

#### 2. Paso

```
npx eslint --init
```

#### 3. Paso

```
? How would you like to use ESLint?
To check syntax, find problems, and enforce code style
```

#### 4. Paso

```
? What type of modules does your project use?
JavaScript modules (import/export)
```

#### 5. Paso

```
? Which framework does your project use?
None of these
```

#### 6. Paso

```
? Does your project use TypeScript? No / Yes
No
```

#### 7. Paso

```
? Where does your code run? (Press <space> to select)
Browser
```

#### 8. Paso

```
? How would you like to define a style for your project?
Use a popular style guide
```

#### 9. Paso

```
? Which style guide do you want to follow?
Standard: https://github.com/standard/standard
```

#### 10. Paso

```
? What format do you want your config file to be in?
JavaScript
```

#### 11. Paso

```
? Would you like to install them now with npm?
Yes
```

#### 12. Paso

Agregar en el apartado de "extends" y agregar siguiente el código

```
extends: ['eslint:recommended', 'standard', 'eslint-config-prettier'],
```

#### 13. Paso

Agregar en el apartado de "rules" agregar el siguiente código

```
rules: {
  quotes: ['error', 'double'],
  semi: ['error', 'always'],
  'comma-dangle': ['error', 'only-multiline'],
  'space-before-function-paren': ['error', 'never'],
  'no-unused-vars': 'warn',
  'react/prop-types': 'off',
}
```

#### 14. Paso

Crear un archivo ".eslintignore" y agregar siguiente el código

```
dist
```
