# Atividade Prática: Modelagem de Classes
Atividade Prática: Bloco 2 - Typescript e POO: Modelagem de Classes

### Inicialização:
```bash
npm init -y
npm i -D typescript @types/node ts-node-dev
npx tsc --init
```

### Configurações:
`package.json` -> `scripts`  
```json
"start": "node ./dist/index.js",
"build": "tsc",
"dev": "ts-node-dev --respawn --transpile-only ./src/index.ts"
```

`tsconfig.json`  
```json
"target": "ES2022"
"rootDir": "./src"
"outDir": "./dist"
"exclude": ["node_modules"]
```

### Organização de Pastas:

>`.gitignore`   
> node_modules/

>`dist`  
> Pasta para os arquivos javascript

>`scr`  
> Pasta para os arquivos typescript  

### Arquivos `src`:
***Classes e Types***
> `PostoIpiranga`
>```typescript
>BombaCombustivel.ts
>Combustivel.ts
```
```typescript
Bola.ts
Calculadora.ts
Carro.ts
ContaCorrente.ts
Contador.ts
```
***Chamadas e Testes***
```typescript
Index.ts
```
