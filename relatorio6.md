# Relatório Semanal - Semana 6 - 16/08 a 22/08

**Aluno:** Ricardo Hideki Hangai Kojo - NUSP 10295429

**Supervisor:** Renato Cordeiro Ferreira - NUSP 7990933

## Introdução

*Breve introdução das atividades executadas na semana, retomando o que foi feito na semana anterior*

Para o **site do USPCodeLab**, foi passado o conteúdo antigo para a nova página. Como a página antiga utilizava Vue + Nuxt, algumas dependência ainda precisam ser resolvidas.

Houve a reunião semanal do **Brains**, na qual foram discutidas as atividades feitas e próximas atividades. Foi criado um componente Vue com uma template para geração de PDF, terminando a história de cliente atribuída a mim na semana anterior.

Para o **HackathonUSP 2018.2**, foram feitos vários contatos buscando patrocínios para o evento. O controle e gestão dos patrocínios será feita junto ao NEU em uma tabela do Google Drive.

## Detalhamento de atividades por objetivo

### 1. Site do USPCodeLab

Os componentes da versão anterior foram passados para o novo projeto. Foram instaladas as seguintes dependências:
* bootstrap-vue;
* vue-scrollto;
* Fonts Awesome.
Foram removidas dependências não necessárias como *vue-cli-plugin-auto-routing*.

Estilo e rotas foram adaptados para o novo projeto e estão funcionando.

O único elemento que não funcionou foi o *b-carousel* do *bootstrap-vue*, devido a uma incompatibilidade com o *vue-loader*. O problema deve ser resolvido na próxima semana com o pacote *vue-carousel*.

### 2. Site da CodeLab Initiative

*Ainda não iniciado*

### 3. Brains

Foi criado um componente *PDF.vue* com um template de PDF que deve ser usado para imprimir os projetos de IC e seus respectivos conteúdos.

O template foi criado usando a biblioteca **pdfmake**. Ao contrário do que foi dito no último relatório, o pacote **jsPDF** não atendia ao que era necessário, já que as funções que eu usaria estão *deprecated* e não funcionam.

Durante a reunião foi feito um *stand-up meeting* e após foram criadas novas histórias e atividades da próxima iteração.

### 4. HackathonUSP 2018.2

Fui atrás de patrocinadores para o evento através do *LinkedIn* e contatos de amigos. As seguintes empresas foram contatadas:
* bbchain;
* Minuto Seguro;
* NerdCoins;
* Neon;
* Next;
* Noverde;
* Saffe - foi marcada uma reunião no *habitat do inovaBra* para ver um possível parceria;
* Youse Seguros.

## Detalhamento de outras atividades relacionadas ao grupo

*Descrição mais precisa das atividades executadas durante a semana que são relacionadas ao grupo de extensão, mas não estão relacionadas aos objetivos descritos na proposta da disciplina.*

## Previsão para próxima semana

*Baseado no andamento da semana atual, estimar o que pode ou não ser feito durante a próxima semana.*

**Site do USPCodeLab:** resolver incompatibilidades das dependências, deixar de usar *bootstrap-vue* e começar a criar um *design system* para o **USPCodeLab**.

**Brains:** reunião semanala e continuação do projeto.

**HackathonUSP 2018.2:** fazer mais contatos e continuar procura por patrocinadores.