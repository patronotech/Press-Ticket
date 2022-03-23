# Press-Ticket

<p align="center">
  <a href="https://www.codefactor.io/repository/github/rtenorioh/press-ticket"><img src="https://www.codefactor.io/repository/github/rtenorioh/press-ticket/badge" alt="CodeFactor" /></a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/rtenorioh/Press-Ticket">

  <a href="https://github.com/rtenorioh/Press-Ticket/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/rtenorioh/Press-Ticket">
  </a>
      
   <a href="https://github.com/rtenorioh/Press-Ticket/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/rtenorioh/Press-Ticket">
  </a>

  <a href="https://github.com/rtenorioh/Press-Ticket/network">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/rtenorioh/Press-Ticket">
  </a>

  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/rtenorioh/Press-Ticket">

  <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/rtenorioh/Press-Ticket">

  <img alt="GitHub Release Date" src="https://img.shields.io/github/release-date/rtenorioh/Press-Ticket">
</p>

## Manual de Instalação
- [INSTALL.md](https://github.com/rtenorioh/Press-Ticket/blob/main/INSTALL.md)

## Changelog

### 22/03/2022
-[Remoção do nome da saudação](https://github.com/rtenorioh/Press-Ticket/commit/d30a856bdb5afbf2614e1fe5093ce2839490b72c); e
-[Mostrar a conexão que está sendo usada no momento](https://github.com/rtenorioh/Press-Ticket/commit/6165724a8f9394780421f275664cffd5f9096bbe).

### 20/03/2022

- [Alterado a API Token de Configurações para API](https://github.com/rtenorioh/Press-Ticket/commit/c97914ca52d88d4855a352165649fc667a42c33f);
- [Retirada do Usuário no Modal de Transferência](https://github.com/rtenorioh/Press-Ticket/commit/576c1c093ab1457aa40718e5a60ade6259b5cca1);
- [Mensagem automática de transferência de setor](https://github.com/rtenorioh/Press-Ticket/commit/e6c1dce9b76cb5f3db226f460e01f6fc6e988d0c);
- [Atualização do layout da página de Tickets](https://github.com/rtenorioh/Press-Ticket/commit/0fc3a882775d9ed5f98c3cc49e718e42924a2925);
- [Correção - Ticket encerrado voltando para aguardando](https://github.com/rtenorioh/Press-Ticket/commit/a594b33baee5ad8f52b8306500a0b2e17d2438c5);
- [Atualizado o Cliente com LocalAuth](https://github.com/rtenorioh/Press-Ticket/commit/470b727b6e0c6fa030ab7c7a6f9952d7838f1c44); e
- [Add Configuração para o tempo de criação de novo Ticket](https://github.com/rtenorioh/Press-Ticket/commit/f47da2cee41654af6b54c4fa28857cec2a2cf9d0?diff=unified) [caso de tela branca ao acessar a página de configurações, rodar o seguinte código no mysql: ```INSERT INTO `Settings` (`key`, `value`, `createdAt`, `updatedAt`) VALUES ('timeCreateNewTicket', '10', '2022-02-16 11:28:51.000000', '2022-02-16 11:28:51.000000');```].

### 19/03/2022
- [Add Separador API e Add Documentação Internamente](https://github.com/rtenorioh/Press-Ticket/commit/8dddb9afe2304a0dfb7cd3415a2dd0ad3db970c4).

### 17/03/2022
- [Correções](https://github.com/rtenorioh/Press-Ticket/commit/a6a148f6bf5bde061c314c619bba127ad374d98f).

### 16/03/2022
- [Remover o Header da Swagger](https://github.com/rtenorioh/Press-Ticket/commit/c8290bc9286e9974bf443cb0117104c2fa4c3adc);
- [Limitação de usuários e conexões pelo .env](https://github.com/rtenorioh/Press-Ticket/commit/a40e6c34d2fbb1d71f19216f97f0486c2101757d); e
- [Correções no layout das conexões.](https://github.com/rtenorioh/Press-Ticket/commit/dd1a9bad3875b9e33971d96b24820c92ce4e233f).

### 15/03/2022
- [Add Página de Documentação da API](https://github.com/rtenorioh/Press-Ticket/commit/d9ee5505d90c36f176a75db44153faf1742cc237); e
- [Add Página de Uso da API](https://github.com/rtenorioh/Press-Ticket/commit/5404c22a7aed614af2eca3adf81f461dfcd5bd65).

### 14/03/2022
- Add CodeFactor; e
- Correções.

### 13/03/2022
- [Implementado autorização para o User poder trocar de senha](https://github.com/rtenorioh/Press-Ticket/commit/6fab280989f3ba5e2ada91380ad0db285b90d7ba);
- Removido o caption que era enviado junto com a imagem;
- Ignorar mensagens de grupos [caso de tela branca ao acessar a página de configurações, rodar o seguinte código no mysql: ```INSERT INTO `Settings` (`key`, `value`, `createdAt`, `updatedAt`) VALUES ('CheckMsgIsGroup', 'enabled', '2022-03-02 17:17:00.000000', '2022-03-02 17:17:00.000000');``` ];
- Customização da página de configurações (trocando select por swicher); e
- Ignorando chamadas de vídeo/áudio [caso de tela branca ao acessar a página de configurações, rodar o seguinte código no mysql: ```INSERT INTO `Settings` (`key`, `value`, `createdAt`, `updatedAt`) VALUES ('call', 'disabled', '2022-03-13 18:00:00.000000', '2022-03-13 18:00:00.000000');``` ].

### 12/03/2022

- Sistema base;
- Habilitado para MD;
- Usando MySql ao invés de Docker;
- Implementado função de aparecer ```digitando...``` antes de enviar a lista de setores;
- Implentado a inclusão do nome do usuário na msg de boas vindas;
- Criado uma variável no arquivo de tradução para alterar o nome Press Ticket;
- Na página de contatos o botão importar contatos está disponível apenas para Admin; e
- Conexões foi movido para a área administrativa.