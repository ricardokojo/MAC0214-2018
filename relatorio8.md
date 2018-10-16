# Relatório Semanal - Semana 8 - 30/09 a 06/10

**Aluno:** Ricardo Hideki Hangai Kojo - NUSP 10295429

**Supervisor:** Renato Cordeiro Ferreira - NUSP 7990933

## Introdução

_Breve introdução das atividades executadas na semana, retomando o que foi feito na semana anterior_

Na semana passada foram settadas as variáveis para o _design system_ e, a partir delas, foi criado um componente Button para o **Site do USPCodeLab**. Nesta semana, foi criado um componente MobileMenu, sem _bootstrap-vue_. Além disso, os _Flat Icons_ criados no site foram alterados para uma versão mais colorida.

Houve a reunião semanal do **Brains** e criação de testes E2E para cadastro e login.

Não houve respostas dos contatos feitos nas últimas semanas para o **HackathonUSP 2018.2**. Houve uma visita à **IBM** para o **BlueTalks**, relacionado ao **BlueHack**, um _hackathon_ da _IBM_. Além disso, foram criadas 4 chamadas para o evento, para serem mostradas nos relógios de rua da USP.

Como atividade extra, foi criada uma nova capa para a página do Facebook.

## Detalhamento de atividades por objetivo

### 1. Site do USPCodeLab

O MenuMobile foi criado usando _FlexBox_, _JavaScript puro_ e um plugin chamado _v-scroll-lock_. O MenuMobile foi criado para ser utilizado apenas quando o usuário entra no site usando um dispositivo móvel. O menu consiste em um botão centralizado perto da margem de baixo do celular, que abre o menu propriamente dito, cobrindo a tela e mostrando as opções de outras páginas do site (que ainda não foram criadas).

Além disso, o site possuía 4 _FlatIcons_ representando as etapas da _dev.journey()_. Foram adicionados mais 2 ícones representando as novas etapas: _dev.hire()_ e _dev.camp()_. Ademais, os ícones antigos foram alterados. Eles eram ícones com linhas em laranja e foram transformados em linhas pretas com detalhes em laranja.

Por último, após conversas com o supervisor, decidimos por utilizar a _framework_ **Tailwind** como substituto do _bootstrap-vue_.

### 2. Site da CodeLab Initiative

_Ainda não iniciado_

### 3. Brains

Assim como na última semana, foi feita a reunião semanal com um _stand-up meeting_.

Também foram criados teste _end-to-end_ utilizando _Cypress_ para testar as funcionalidades de Cadastro e Login de usuários. Os testes foram criados a partir do teste básico que vem como parte de um projeto _Vue CLI 3_ com _Cypress_. Basicamente, o teste acessa a _home_ do site, clica no botão _Cadastro_, preenche os campos, cadastra um usuário. A partir daí ocorre o redirecionamento para a página de _Login_, preenchimento dos dados e então o acesso ao sistema.

### 4. HackathonUSP 2018.2

Não houve respostas dos contatos feitos anteriormente. Ao conversar com outros membros do grupo, chegamos à conclusão de que o maior problema da aquisição de patrocínio no 2º semestre é que muitas empresas fecham o orçamento no início do ano. Assim, muitas das respostas foram negativas, porém com interesse em eventos posteriores.

Nesta semana, também ocorreu um _BlueTalks_, evento da **IBM** que serviu como um _warm-up_ para o _BlueHack_: um _hackathon_ da IBM em conjunto com outras empresas/organizações. Cada empresa/organização propõe um desafio e os participantes podem escolher apenas 1 deles para trabalhar.

Junto com a Bruna, outra membro do grupo, ao _BlueTalks_, onde conversamos com organizadores e outros participantes. Apresentamos o grupo e o **HackathonUSP**. Não conseguimos novos patrocínios, mas criamos interesse vindo de diversas empresas e da própria IBM.

Por último, foram criadas 4 imagens com uma chamada para o evento. Essas imagens foram enviadas para um contato do membro do grupo, para que fossem mostradas nos relógios de rua da universidade. As imagens possuiam as dimensões 400x300 ou 700x300: uma imagem 400x300 apenas com logo, uma 400x300 com logo e chamada, uma 700x300 apenas com logo e uma 700x300 com logo e chamada.

## Detalhamento de outras atividades relacionadas ao grupo

_Descrição mais precisa das atividades executadas durante a semana que são relacionadas ao grupo de extensão, mas não estão relacionadas aos objetivos descritos na proposta da disciplina._

Como parte da inauguração do **USPCodeLab Sanca**, uma _branch_ do grupo no campus São Carlos, decidimos atualizar a capa do Facebook.

A nova capa foi criada utilizando _Photoshop CC_, com o logo centralizado e um plano de fundo com `{...}, [...]; e () => {` distribuídos de forma diagonal, com as cores do grupo: preto e laranja.

## Previsão para próxima semana

_Baseado no andamento da semana atual, estimar o que pode ou não ser feito durante a próxima semana._

**Site do USPCodeLab** => estudos sobre o _Tailwind_ e início da utilização da _framework_ no site;

**Brains** => Continuação de criação de testes para o sistema;

**HackathonUSP 2018.2** => Com a aproximação do evento, os patrocínios foram praticamente fechados. Sendo assim, a contribuição vai ser participar da organização e discussões sobre o evento.
