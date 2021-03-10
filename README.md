## Passos para criação do projeto

### Criando o arquivo package.json
yarn init -y

### Instalando o React
yarn add react

### Instalando o React DOM
yarn add react-dom

### Instalando o Babel
yarn add @babel/core @babel/cli @babel/preset-env -D

### Instalando o preset do Babel que entende o React
yarn add @babel/preset-react -D

### Criando o destino do código convertido pelo Babel a partir do index.js
yarn babel src/index.js --out-file dist/bundle.js

### Instalando o webpack
yarn add webpack webpack-cli webpack-dev-server -D

### Instalando o babel-loader para o webpack
yarn add babel-loader -D

### Instalando o webpack-html-plugin para o import do arquivo bundle.js
yarn add html-webpack-plugin -D

### Instalando o webpack devServer
yarn add webpack-dev-server -D

### Instalando o cross env
yarn add cross-env -D

### Loaders para compílação dos arquivos css
yarn add style-loader css-loader -D

### Loader do SASS
yarn add sass-loader -D

### Adicionando SASS
yarn add node-sass -D

### Instalando o React Refresh
yarn add -D @pmmmwh/react-refresh-webpack-plugin react-refresh

### Adicionando o Typescript como dependência de desenvolvimento
yarn add typescript @types/react @types/react-dom -D

### Inicializando o Typescript na aplicação
yarn tsc --init

### Configurando o Babel para interpretar o typescript
yarn add @babel/preset-typescript -D