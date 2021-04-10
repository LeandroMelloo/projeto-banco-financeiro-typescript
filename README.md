# projeto_banco_financeiro_typescript
Projeto Banco Financeiro com Typescript

# Comando para instalação do Typescript
npm install typescript@2.3.3 --save-dev

# Configuração do Typescript
1° criar um arquivo tsconfig.json

2° configurar o arquivo tsconfig.json
{
    "compilerOptions": {
        "target": "es6",
        "outDir": "app/js",
        "noEmitOnError": true
    },
    "include": [
        "app/ts/**/*"
    ]
}

3° configurar no package.json dentro de scripts
"compile": "tsc"

4° rodar o comando
npm run compile

5° alterar a compilação dinamica da aplicação, configurar no package.json dentro de scripts
"start": "tsc -w"

6° rodar o comando:
npm start
