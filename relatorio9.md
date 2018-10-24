# Relatório Semanal - Semana X - 07/10 a 13/10

**Aluno:** Ricardo Hideki Hangai Kojo - NUSP 10295429

**Supervisor:** Renato Cordeiro Ferreira - NUSP 7990933

## Introdução

_Breve introdução das atividades executadas na semana, retomando o que foi feito na semana anterior_

**SEMANA DE BREAK**

Para o **Site do USPCodeLab** foram realizados últimos ajustes no MobileMenu. Também foi corrigido o deploy automático no _Netlify_, que estava com problemas na nova branch.

Para o **Brains**, houve problemas de compatibilidade com o Cypress, o que fez com que a ferramenta fosse deixada de lado. Devido ao _break_, não houve reunião.

A atividade mais significativa feita para o **HackathonUSP 2018.2** foi a criação de um design de camisetas para o USPCodeLab.

## Detalhamento de atividades por objetivo

### 1. Site do USPCodeLab

Foram ajeitados os efeitos de transição no componente MobileMenu, pelo CSS. Agora o componente está completamente pronto para ser utilizado no site.

Na branch _master_, estava configurado o deploy automático para o _Netlify_. No entanto, para a branch _v2_, o deploy ocorria com erros. Tais erros foram corrigidos diretamente nas configurações da plataforma e agora o deploy funciona normalmente. A branch _v2_ já está disponível no link https://v2--uspcodelab.netlify.com

### 2. Site da CodeLab Initiative

_Ainda não iniciado_

### 3. Brains

Não houve reunião, devido ao _break_.

Foi continuada a criação de testes para a plataforma. No entanto, ao tentar executar os testes dentro de um container do _Docker_, houve uma série de erros. Aparentemente, a ferramenta possui um problema de compatibilidade com o _Docker_ - vide _open issue_ no repositório do Github https://github.com/cypress-io/cypress-docker-images/issues/39

Sendo assim, a ferramenta foi descartada. A outra opção disponibilizada pelo _Vue CLI 3_ é o _Nightwatch_; utilização será estudada e avaliada.

### 4. HackathonUSP 2018.2

As atividades para o evento continuaram normalmente. Foram feitas discussões entre o USPCodeLab e o NEU.

Em especial, foi feita o design de uma nova camiseta para o grupo. Atualmente o grupo possui um tipo de camiseta, que foi feita e distribuída para os membros do grupo no primeiro semestre. Os integrantes que entraram no segundo semestre não possuem uma camiseta.

Sendo assim, a camiseta foi feita com um design parecido com a primeira, mudando a cor para preta e utilizando o logo em tons de cinza.

A intenção é que este design seja utilizado para encomendar camisetas para os novos membros e que estas camisetas estejam prontas até o dia do evento.

## Detalhamento de outras atividades relacionadas ao grupo

_Descrição mais precisa das atividades executadas durante a semana que são relacionadas ao grupo de extensão, mas não estão relacionadas aos objetivos descritos na proposta da disciplina._

## Previsão para próxima semana

_Baseado no andamento da semana atual, estimar o que pode ou não ser feito durante a próxima semana._

**Site do USPCodeLab** => substituir _bootstrap-vue_ pelo _Tailwind_ nos componentes.

**Brains** => nova reunião e estudos sobre outra ferramenta para testes.

**HackathonUSP** => continuação da organização para o evento e criação de designs, caso necessário.
