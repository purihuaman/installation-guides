# Configurando Eslint

Descarga la extensión de "eslint" en tu editor o IDE favorito

#### 1. First step

```
npm i -D -E eslint

or

pnpm i -D -E eslint
```

#### 2. Second step

```
npx eslint --init
```

#### 3. Third step

```
? How would you like to use ESLint?
To check syntax, find problems, and enforce code style
```

#### 4. Fourth step

```
? What type of modules does your project use?
JavaScript modules (import/export)
```

#### 5. Fifth step

```
? Which framework does your project use?
None of these
```

#### 6. Sixth step

```
? Does your project use TypeScript? No / Yes
No
```

#### 7. Seventh step

```
? Where does your code run? (Press <space> to select)
Browser
```

#### 8. Eighth step

```
? How would you like to define a style for your project?
Use a popular style guide
```

#### 9. Ninth step

```
? Which style guide do you want to follow?
Standard: https://github.com/standard/standard
```

#### 10. Tenth step

```
? What format do you want your config file to be in?
JavaScript
```

#### 11. eleventh step

```
? Would you like to install them now with npm?
Yes
```

#### 12. Twelfth step

Add the following code in the "extends" section, depending on the technology in Vanilla or React.js or Vue.js

```
extends: ['eslint:recommended', 'standard', 'eslint-config-prettier'],

or

extends: [ 'plugin:react/recommended', 'plugin:react/jsx-runtime', 'standard', 'eslint-config-prettier', ],
```

#### 13. Thirteenth step

In the generated file of ".eslintrc.js" add the following code

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

#### 14. Fourteenth step

Create a ".eslintrc.js" file and add following code

```
dist
```
