# Typescript
- Pode ser preciso Instalar parte de tipagem separado
    - Ex:

```sh
yarn add @types/express -D
```

- Node não entende ts nativamente
```sh
yarn add typescript -D
# gerar tsconfig.json
yarn tsc --init
```

- Converter ts em js
```sh
yarn tsc
```
- Joga os arquivos convertido por padrão na pasta atual
    - Não o aconselhavel, imaginando que 10 arquivos ts iram gerar 10 js
    - Alterar isso
```json
"outDir": "./your_path"
```