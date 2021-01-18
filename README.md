# Seleção de estágio 2021

> Projeto de seleção de estágio do ano de 2021

Antes de iniciar a leitura do projeto é importante dizer que a resolução completa ou parcial do projeto não garante que você foi muito bem ou muito mal. Visto que o projeto é dividido em duas partes, frontend e backend, foque no que você tiver maior familiaridade.

Por exemplo, se você é bom com frontend, procure fazê-lo da melhor forma possível de acordo com o que você aprendeu estudando o framework. Nesse caso o backend será descartado na hora da avaliação, mas os critérios do frontend será maior. Isso vale para o backend.

Nada impede você de desenvolver o frontend e backend.

### Período de entrega

O período de entrega será 1 semana apartir do dia da confirmação do recebimento. Por exemplo, se recebeu em 18/01/2021 você tem 7 dias (1 semana) para entregar o projeto, no caso até dia 24/01/2021 23h:59m. Posso entregar depois? Pode, mas não garantimos nada.

### Entrega do projeto

- Você vai criar um fork deste projeto.
- Colocar o código fonte do seu projeto dentro da pasta frontend ou backend, de acordo com o que você escolheu fazer.
- Mandar um email para `desenvolvimento@parnamirim.rn.gov.br` com o assunto: `Seu nome - PROJETO SELEÇÃO DE ESTAGIO 2021`. No corpo da mensagem o link para o seu fork.

Não apague este README.md, se tiver observações crie um arquivo README.md dentro da pasta do seu projeto com orientações de execução do mesmo.

## Projeto

> Você será o responsável pelo desenvolvimento da plataforma de vendas de uma loja de carros.

**Problema**

Olá eu sou Maykon o dono da loja de carros, e eu gostaria de ter um sistema no qual eu possa cadastrar veículos e disponibilizá-los para os meus clientes em uma página pública onde terá uma lista dos veículos, e quando o usuário clicar em um determinado veículo ele possa ver os detalhes deste veículo.

Para isso eu quero poder cadastrar um veículo com uma imagem e as informações básicas dele. Além disso eu quero poder visualizar os dados dos veículos já cadastrados e editar se for necessário.

**Proposta**

De acordo com as necessidades do nosso cliente podemos identificar que teremos dois módulos principais, são eles:

- Visualização pública dos veículos a venda: Neste módulo o sistema deverá disponibilizar uma lista dos veículos cadastrados e quando selecionado um item da lista deverá mostrar os detalhes do mesmo.

- Administração do sistema: Neste módulo o sistema deverá disponibilizar uma ferramenta de administração dos veículos, basicamente será um CRUD, contendo obrigatoriamente os dados a seguir:

  - Foto
  - Tipo do veículo
  - Marca
  - Modelo
  - Ano
  - Preço

Procurar manter um código limpo e coeso evitando a realização do POG’s (Programação orientada a Gambiarra).

### Frontend

O projeto frontend **deve** ser feito utilizando o framework [Angular](https://angular.io/). O framework de estilo **deve** ser o [Bootstrap](https://getbootstrap.com/).

Você será responsável pelo desenvolvimento da interface do usuário. A estrutura do projeto, os nomes dos componentes, módulos e rotas são de sua escolha. As boas práticas do uso do framework são indispensáveis e terão PESO na avaliação. O bom uso do [Rxjs](https://rxjs-dev.firebaseapp.com/guide/overview) também faz parte das boas práticas. Você **deve** fazer requisições para alguma API pra recuperar os dados. Você pode usar alguma biblioteca para _mockar_ o backend, algumas opções: [json-server](https://github.com/typicode/json-server), [MirageJS](https://miragejs.com/), [Exemplo usando o MirageJS com Angular](https://github.com/smkamranqadri/angular-mirage-sample)

### Backend

O projeto backend **deve** ser feito utilizando o framework [Spring Boot](https://spring.io/projects/spring-boot).

Você será responsável pelo desenvolvimento da API Rest desta aplicação. A estrutura do projeto e os nomes das URIs são de sua escolha. As boas práticas de orientação a objeto são indispensáveis e terão PESO na avaliação. O banco de dados deverá ser o PostgreSQL.
