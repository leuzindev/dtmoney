<p align="center">
  <h1 align="center"><a href="https://ignite-dt-money.netlify.app/">DT Money :rocket: </a></h1>
</p>

<p align="center" margin-top="25px" >
  <img alt="GitHub Language Count" src="https://img.shields.io/github/languages/count/andreviapiana/DTMoney" />

  <img alt="GitHub Top Language" src="https://img.shields.io/github/languages/top/andreviapiana/DTMoney" />
</p>


Este é o resultado de um estudo aprofundado de React.js.

___

## 💻 Sobre
A ideia deste projeto é criar um controle financeiro para o usuário. Nele o usuário pode adicionar as entradas e saídas financeiras do seu dia-a-dia. É possível ainda utilizar o campo de busca da página para filtrar por itens ou categorias específicas.

Por "trás dos panos" o projeto apresenta diversas funcionalidades, fazendo uso do React Hook Form e Zod nos formulários e utilizando Context para facilitar o uso de variáveis. O projeto possuí ainda otimizações para evitar renderizações desnecessárias nos componentes.

___

## 🎨 Layout
A página em formato desktop é vista na imagem abaixo:

![Capa](https://user-images.githubusercontent.com/106932234/217977248-680d1f67-054b-4290-8bba-548154d18012.png)

___

## 🛠 Tecnologias

As seguintes tecnologias foram empregadas na criação deste projeto:

- [ReactJs](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [React Hook Form](https://react-hook-form.com/)
- [Styled Components](https://styled-components.com/)
- [Zod](https://zod.dev/)

___

## 🚀 Como utilizar

Clone o projeto para o local desejado em seu computador.

```bash
$ git clone git@github.com:andreviapiana/DTMoney.git
```
___

#### 🚧 Executando o Projeto
```bash

# Navegue até o diretório
$ cd DTMoney

# Instale as dependências necessárias
$ npm install

# Agora inicie o servidor do FrontEnd
$ npm run dev

# O terminal irá exibir o endereço local onde a aplicação está sendo executada. Basta digitar o mesmo endereço em seu navegador preferido. O endereço usado na criação do projeto foi este:

  http://localhost:5173/
```

#### 🚧 Deseja Executar o BackEnd localmente?

O BackEnd roda nativamente através do meu servidor JSON. Caso deseje rodar ele localmente em sua máquina, siga os passos:

```bash

# Navegue até o diretório
$ cd DTMoney/src/lib

# Abra o arquivo AXIOS.TS que está no diretório acima

# Faça a inversão dos itens que ficam comentados, de modo que os endereços ficarão assim:
baseURL: 'http://localhost:3000',
// baseURL: 'https://my-json-server.typicode.com/andreviapiana/dtmoney',

# Então inicie o servidor do BackEnd
$ npm run dev:server
```

___


[O resultado FINAL pode ser visto aqui](https://ignite-dt-money.netlify.app/)

___


Made with ❤️ by André Viapiana 👋🏽 [Get in Touch!](https://www.linkedin.com/in/andreviapiana/)

---