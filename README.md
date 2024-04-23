# Pass-in-web
Projeto feito durante tres dias na NLW-Unite da Rocketseat
O foco foi o desenvolvomento da parte do FrontEnd
O ambiente de trabalho utilizado foi o Linux

![Pass-in Demo](/public/projeto.png 'Pass-in Demo')

# Objetivo desse projeto:

1. Criar uma aplcação para gestão de participantes
2. Será possivel pegar a partir de um banco de dados as seguintes informações
2.1 Codigo de cadastro
2.2 Nome do participante
2.3 Data de inscrição
2.4 Data de checkin

# Tecnologias utilizadas
1. React.js
2. Typescript
3. Vite


# Instruções para utilizar a aplicação
Siga este roteiro para começar a usar esta aplicação
Obs: os dados da aplicação foram inseridos através de um banco de dados local em node.js

## Clonar esta aplicação
```
git clone git@github.com:brjatoba92/pass-in--web.git
```

## Instalar todas as dependencias
```
npm i
```

# Processo de construção

## Configurações iniciais

### Instalação do Node

```
https://nodejs.org/en/download/package-manager
```

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
nvm install 20
node -v
npm -v
```

### Instalação do Vite
1. Comando
```
npm create vite@latest
```
2. Passos
- nome do projeto
- selecionar o framework: React
- selecionar a variante: TypeScript

### Deletando arquivos e pastas
- README.md
- pasta assets
- App.css

### Arquivo App.tsx
- Remover as importações iniciais
- Remover todo o conteudo na função App() e colocar dentro somente um return com a tag de h1 com a frase Hello World
- Renomear a função para export function App(), para facilitar a referenciação em qualquer codigo através da chave
- Renomear arquivo para app.tsx

### Instalar todas as dependencias
```
npm i
```

### Executar a aplicação
```
npm run dev 
```

### Remover todo o conteudo do index.css

## Componentes (24min48s)
