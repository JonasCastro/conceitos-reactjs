<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
 Solução do Desafio 03: Conceitos do ReactJS
</h3>

<blockquote align="center"><a href="https://github.com/Rocketseat/gostack-template-conceitos-reactjs">Template para iniciar o desafio</a></blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/jonascastro/conceitos-reactjs?color=%2304D361">

  <a href="https://www.linkedin.com/in/jonas-castro-b4044111a/">
    <img alt="Made by JonasCastro" src="https://img.shields.io/badge/made%20by-JonasCastro-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
   <a href="https://github.com/Rocketseat/gostack-template-conceitos-reactjs">
    <img alt="Template by Rocketseat" src="https://img.shields.io/badge/Template%20by-Rocketseat-%2304D361">
  </a>
  
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#funcionalidades-da-aplicação">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#checkered_flag-execute-o-projeto-localmente">Execute o projeto localmente</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o desafio

Esse desafio,tem como objetivo criar uma aplicação para treinar os conceitos de ReactJS!

A aplicação consome a <a href="https://github.com/JonasCastro/conceitos-nodejs">API</a> de repositórios do seu portfólio.

### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Cria uma lista com o campo **title** de todos os repositórios que estão cadastrados na <a href="https://github.com/JonasCastro/conceitos-nodejs">API</a>.

- **`Adicionar um repositório a sua API`**: Adiciona um novo item na <a href="https://github.com/JonasCastro/conceitos-nodejs">API</a> através de um botão com o texto **Adicionar** e, após a criação, exibe o nome do item cadastrada.

- **`Remover um repositório da sua API`**: Para cada item da lista existe um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do frontend e da <a href="https://github.com/JonasCastro/conceitos-nodejs">API</a>.

### Testes da aplicação

- **`should be able to add new repository`**: Para que esse teste passe, a aplicação deve permitir que um repositório seja adicionado ao backend e listado no frontend dentro de uma `LI`.

- **`should be able to remove repository`**: Para que esse teste passe, a aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `LI` do repositório adicionado, o item seja removido da listagem.

### :checkered_flag: Execute o projeto localmente:

```bash
# Clone este repositório
$ git clone https://github.com/JonasCastro/conceitos-reactjs.git

# Acesse a pasta do projeto no terminal/cmd
$ cd conceitos-reactjs

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn start

# O servidor inciará na porta:3000 - 
# Acesse http://localhost:3000

# Para executar os testes da aplicação
$ yarn test
 
```

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
- Feito com :blue_heart: by Jonas Castro :wave: [Stay in touch!](https://www.linkedin.com/in/jonas-castro-b4044111a/)
- Template Feito com 💜 by Rocketseat :wave: [Entre na nossa comunidade!](https://discordapp.com/invite/gCRAFhc)
