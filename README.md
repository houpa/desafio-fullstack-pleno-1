<a href="https://houpa.app/" aria-label="Houpa" class="d-block tooltipped tooltipped-s">
  <img itemprop="image" class="flex-shrink-0 mb-3 mr-3 mb-md-0 mr-md-4" src="https://avatars.githubusercontent.com/u/51490241?s=200&amp;v=4" width="100" height="100" alt="@houpa">
</a>

# Desafio - Desenvolvedor Fullstack Pleno 1
Seja bem-vindo! Este desafio foi projetado para avaliar a sua capacidade técnica como candidato à vaga de Desenvolvedor Fullstack Pleno 1.

## Instruções
- Faça um fork deste repositório;
- Serviço deve respeitar os princípios RESTFul;
- Criar um `README.md` (arquitetura, instruções de uso, entre outros);
- Após finalizar, submeta um pull request com um comentário informando o seu e-mail de contato e aguarde nossa avaliação.

## Proposta
Você deverá desenvolver um blog. Para isso, separaremos a proposta desse desafio em duas etapas:

### Back-end
Desenvolva uma API utilizando [Nestjs](https://nestjs.com/) e [Prisma](https://www.prisma.io/) que contenha as seguintes rotas:
- `/register` - [POST] - esta rota deve cadastrar um usuário e disparar um email de verificação;
- `/login` - [POST] - esta rota deve autenticar um usuário verificado;
- `/posts` - [POST] - esta rota deve cadastrar uma postagem mantendo a referência do autor. (requer autenticação);
- `/posts/{id}` - [PUT] - esta rota deve editar a postagem do ID especificado mantendo a referência do autor. (requer autenticação);
- `/posts` - [GET] - esta rota deve retornar a lista de todas as postagens ordenadas das mais recentes para as mais antigas com a possibilidade de inverter esta ordenação e de retornar apenas as postagens do usuário que fez a requisição (requer autenticação);
- `/posts/{id}` - [GET] - esta rota deve retornar a postagem do ID especificado com todos os seus dados  (requer autenticação);
- `/posts/{id}` - [DELETE] - esta rota deve remover a postagem do ID especificado sem apagar o registro do banco de dados (requer autenticação).

### Front-end

**Web:** Desenvolva uma aplicação web utilizando o [Next](https://nextjs.org/) e esta deve atender as seguintes histórias:
 - Eu como usuário desejo me cadastrar;
 - Eu como usuário desejo realizar login;
 - Eu como usuário autenticado desejo visualizar todas as postagens;
 - Eu como usuário autenticado desejo visualizar os detalhes de uma postagem;
 - Eu como usuário autenticado desejo visualizar todas as minhas postagens;
 - Eu como usuário autenticado desejo criar uma postagem;
 - Eu como usuário autenticado desejo editar uma postagem que eu criei;
 - Eu como usuário autenticado desejo deletar uma postagem que eu criei.

**Mobile:** Desenvolva um aplicativo utilizando o [React Native](https://reactnative.dev/), ou [Flutter](https://flutter.dev/), tendo as mesmas funcionalidades da aplicação web.

## Diferenciais
Consideraremos como diferenciais os seguintes pontos:
- Publicação do ambiente em um serviço cloud de hospedagens (Heroku, AWS, GCP, etc);
- Criação de testes unitários (back-end/front-end);
- Criação de testes de integração (back-end/front-end);
- Criação do front-end web com Material-UI;
- Clean architecture;
- DDD;
- Configurar a aplicação para rodar em um container;
- Documentação da API.

> **Observações:**
> - Suas aplicações web e mobile DEVEM se comunicar com sua API;
> - Você pode utilizar o banco de dados de sua preferência (relacional ou não relacional).

## Critérios para avaliação
- Usabilidade
- Criatividade
- Limpesa e organização do código
- Documentação de código
- Documentação do projeto (readme)
- Performance

## Dúvidas
Envie um email para vinicius.carvalho@houpa.app
