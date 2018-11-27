# Relatório Semanal - Semana 14 - 11/11 a 17/11

**Aluno:** Ricardo Hideki Hangai Kojo - NUSP 10295429

**Supervisor:** Renato Cordeiro Ferreira - NUSP 7990933

## Introdução

**SEMANA DE BREAK**

_Breve introdução das atividades executadas na semana, retomando o que foi feito na semana anterior_

Para o **site do USPCodeLab**, foram feitos ajustes relacionados à acessibilidade do site.

Não houve atividades relacionadas ao **Brains**, dada a _semana de break_.

Neste relatório, estarão presentes os detalhes sobre o dia do evento do **HackathonUSP 2018.2**.

Ademais, o pôster foi criado, impresso e anexado no IME-USP.

## Detalhamento de atividades por objetivo

### 1. Site do USPCodeLab

O supervisor recomendou rodar a nova versão do site na plataforma https://web.dev, do _Google_. Dada uma URL, a plataforma analisa seu site nos seguintes aspectos: performance, acessibilidade, boas práticas e SEO. A plataforma também oferece um relatório mais detalhado, apontando quais partes do código pecam em seus respectivos aspectos.

Ao rodar a nova versão do site, https://v2--uspcodelab.netlify.com, o único aspecto que teve uma nota ruim foi `acessibilidade`. As notas foram as seguintes:

- Performance: `95`
- Acessibilidade: `43`
- Boas práticas: `100`
- SEO: `90`

Assim, foram feitas alterações focando na questão de acessibilidade. No entanto, algumas questões estavam relacionadas à biblioteca `vue-fontawesome`, que não apresenta todas as funcionalidades da biblioteca original. Em particular, a funcionalidade relacionada à acessibilidade não está funcionando, vide _open-issue_ https://github.com/FortAwesome/vue-fontawesome/issues/63, na qual fiz um comentário pedindo para que seja corrigida.

Sendo assim, após as alterações, as notas foram as seguintes:

- Performance: `95`
- Acessibilidade: `66`
- Boas práticas: `100`
- SEO: `100`

Com uma breve melhoria na questão de acessibilidade. Caso os problemas com a biblioteca sejam resolvidos, certamente a nota subirá para algo próximo da nota máxima.

Além disso, foi criada uma página para _404 Not Found_.

### 2. Site da CodeLab Initiative

_Ainda não iniciado_

### 3. Brains

Não houve reunião semanal nem atividades durante essa semana.

### 4. HackathonUSP 2018.2

No dia do evento, cheguei ao meio-dia de sábado (10/11). Devido à um evento do CAEM, várias salas do IME estavam ocupadas até às 13h. Logo, não podíamos arrumar a sala para o _hacakthon_ até o evento do CAEM terminar.

Terminado o evento do CAEM, todos os membros do grupo presentes ajudaram a arrumar as salas que seriam utilizadas para o evento:

- B5
  - sala principal, na qual os participantes ficariam;
  - foram trazidas mesas do Arquivo Morto e cadeiras do auditório do CCSL;
  - rede elétrica foi adaptada utilizando extensores e réguas para prover energia para todas as mesas.
- B2
  - sala de depósito da comida;
  - todas as cadeiras foram retiradas e colocadas na B4.
- B3
  - sala dos patrocinadores;
  - todas as cadeiras foram retiradas e colocadas na B4.
- B4
  - depósito de cadeiras das outras.
- B6
  - sala de descanso;
  - foram trazidas cadeiras, bancos e outros móveis do CCSL.
- B7
  - sala dos membros da organização;
  - algumas mesas e cadeiras foram levadas à B5 para comportar pessoas q ficaram sem mesa.

Após arrumar todo o espaço necessário para o evento, ajudei a receber os patrocinadores e carregar os brindes que trouxeram até a sala B3.

Depois disso, o evento correu normalmente. Os participantes foram chegando, passavam pela mesa de recepção, no qual seu nome era checado, recebiam uma camiseta do evento e um brinde do _PagSeguro_, um dos patrocinadores do evento.

O evento iniciou com um certo atrasado. Começou com uma palestra do Paulo da PRP, seguida de breves palestras do USPCodeLab, NEU e Hardware Livre, e por último palestras dos patrocinadores da categoria _Gold_.

Após todas as apresentações, iniciou-se o desenvolvimento dos projetos. Em geral, os membros da organização do evento ficaram de prontidão para executar tarefas sob demanda. Em particular, trabalhei no recebimento das pizzas, organização das mesas de alimentação e reposição de alimentos nas mesas. Além disso, tirei fotos do evento, conversei um pouco com o pessoal que veio em nome dos patrocinadores, entregando cartões do USPCodeLab e convidando-os para as refeições que oferecemos.

Durante a madrugada, acabei dormindo das 5h da manhã até as 11h, perto do almoço. Após o almoço e o encerramento das atividades, houve as apresentações das ideias, julgamento, entrega dos prêmios e encerramento do _HackathonUSP 2018.2_.

Após o encerramento do evento, os participantes se retiraram e reorganizamos tudo: todas as salas foram reorganizadas como estavam anteriormente, mesas e outros móveis foram retornados, lixo foi recolhido e levado.

Dada a _semana de break_, muitos membros não estavam presentes para ocorrer uma reunião de _feeback_ do evento, que foi adiada para a próxima semana.

## Detalhamento de outras atividades relacionadas ao grupo

_Descrição mais precisa das atividades executadas durante a semana que são relacionadas ao grupo de extensão, mas não estão relacionadas aos objetivos descritos na proposta da disciplina._

Pôster, que é parte da avaliação da matéria, foi impresso e colado na segunda-feira, dia 12/11.

## Previsão para próxima semana

_Baseado no andamento da semana atual, estimar o que pode ou não ser feito durante a próxima semana._

**Site do USPCodeLab** => finalização da página de 404 e início da página do _dev.camp()_

**Brains** => não há atividades previstas

**HackathonUSP 2018.2** => reunião de _feedback_ do evento
