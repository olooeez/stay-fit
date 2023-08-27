# stay-fit

O stay-fit é um projeto de aplicação web desenvolvido em React, MaterialUI e utiliza a RapidAPI para fornecer uma plataforma que facilita a busca e exploração de exercícios físicos com base no nome e na parte do corpo que deseja treinar.

## Demo

[![Demo do stay-fit](https://i.postimg.cc/vT8K1GJc/foto-1.png)](https://postimg.cc/TLS0FvY6)

Você pode achar uma live-demo clicando [aqui](https://stay-fit-reactjs.netlify.app).

## Pré-requisitos

Antes de começar, verifique se você possui os seguintes requisitos instalados em sua máquina:

1. **Node.js**: O Node.js é uma plataforma que permite a execução de código JavaScript no servidor. Você pode baixar o Node.js no [site oficial](https://nodejs.org/) e seguir as instruções de instalação para o seu sistema operacional.

2. **NPM**: O NPM é o gerenciador de pacotes do Node.js. Ele é instalado junto com o Node.js e é necessário para instalar as dependências do projeto.

## Instalação e Desenvolvimento

### Passo 1: Clonar o repositório

Clone este repositório para a pasta desejada em sua máquina:

```bash
git clone https://github.com/olooeez/stay-fit.git
```

### Passo 2: Instalar as dependências

Navegue até o diretório do projeto e instale as dependências usando o NPM:

```
cd stay-fit
npm install
```

### Passo 3: Configurar a RapidAPI

O stay-fit utiliza a RapidAPI para obter os detalhes dos exercícios. Certifique-se de ter uma conta na RapidAPI e obtenha a chave de API necessária para fazer as requisições. Você precisará configurar essa chave no arquivo .env na raiz do projeto da seguinte maneira:

```
REACT_APP_RAPIDAPI_KEY=SuaChaveDaRapidAPI
```

### Passo 4: Executar a aplicação

Após configurar a chave da RapidAPI, você pode iniciar a aplicação localmente com o seguinte comando:

```
npm start
```

A aplicação estará disponível em seu navegador no [locahost:3000](http://localhost:3000).

## Contribuindo

Se desejar contribuir para este projeto, sinta-se à vontade para abrir um pull request. Estamos abertos a todas as formas de contribuição!

## Licença

Este projeto está licenciado sob a [Licença Apache 2.0](https://github.com/olooeez/stay-fit/blob/main/LICENSE). Consulte o arquivo LICENSE para obter mais detalhes.
