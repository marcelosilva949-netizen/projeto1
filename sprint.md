# Plano de Sprints do MVP

## 1. Visão geral

Este documento descreve as fases de implementação do projeto, desde a ideação inicial até a entrega do MVP concluído. O objetivo é transformar a ideia em um produto funcional, com desenvolvimento incremental, validação contínua e foco em entregar valor real para a instituição de ensino.

O projeto está centrado em uma solução de segurança para instituições de ensino, integrando monitoramento por câmeras, controle de acesso e apoio de inteligência artificial para alertas e identificação de riscos.

A abordagem será por sprints, com entregas planejadas, testes e validações em cada etapa. Dessa forma, o time consegue evoluir o produto de forma organizada, reduzir riscos e garantir que o MVP entregue esteja alinhado com a necessidade real do usuário.

---

## 2. Objetivo do planejamento por sprints

O planejamento por sprints permite:

- dividir o desenvolvimento em etapas menores e executáveis;
- validar hipóteses com rapidez;
- reduzir riscos de retrabalho;
- priorizar as funcionalidades mais importantes do MVP;
- medir progresso de forma concreta;
- preparar a base para evoluções futuras.

---

## 3. Fase 1 - Ideação e definição do problema

### Objetivo
Definir claramente a dor do cliente, o público-alvo, a proposta de valor e o escopo inicial do produto.

### Atividades
- levantamento da dor do cliente;
- análise do contexto de segurança em instituições de ensino;
- identificação dos principais problemas observados;
- definição do público-alvo;
- descrição da proposta de solução;
- validação da viabilidade do projeto.

### Entregáveis
- documento de dor e contexto do projeto;
- descrição do problema;
- definição do público-alvo;
- visão geral da solução;
- lista inicial de necessidades do usuário.

### Resultado esperado
A equipe deve compreender exatamente o que será solucionado e por que o produto é relevante.

---

## 4. Fase 2 - Pesquisa e análise de requisitos

### Objetivo
Transformar a ideia em requisitos claros, priorizados e compreensíveis para o desenvolvimento.

### Atividades
- entrevista ou validação com usuários e stakeholders;
- análise de cenários reais de segurança escolar;
- levantamento de requisitos funcionais;
- levantamento de requisitos não funcionais;
- organização das prioridades do MVP;
- definição das regras de negócio principais.

### Requisitos principais a definir
- quem serão os usuários do sistema;
- quais áreas serão monitoradas;
- como os acessos serão controlados;
- quais alertas serão gerados;
- quais eventos precisam ser registrados;
- qual será a experiência do operador e do gestor.

### Entregáveis
- requisitos funcionais do MVP;
- requisitos não funcionais;
- backlog inicial priorizado;
- casos de uso principais;
- mapa de fluxo de uso do sistema.

### Resultado esperado
O projeto deve ter um escopo bem definido, com foco nas funcionalidades essenciais para a primeira entrega.

---

## 5. Fase 3 - Definição da arquitetura e proposta técnica

### Objetivo
Escolher a base tecnológica e estruturar a solução para que o MVP seja viável, escalável e fácil de evoluir.

### Atividades
- definição da arquitetura geral do sistema;
- escolha de tecnologias do frontend, backend, banco de dados e IA;
- modelagem dos componentes principais;
- definição da comunicação entre módulos;
- planejamento de integrações com câmeras e alertas;
- estruturação do ambiente de desenvolvimento.

### Arquitetura proposta
- Frontend: interface para gestão, monitoramento e dashboard;
- Backend: API para autenticação, regras de negócio e integrações;
- Banco de dados: armazenamento de usuários, acessos, eventos e registros;
- Camada de IA: análise de imagens e detecção de eventos suspeitos;
- Integração com câmeras e alertas: visualização e notificação.

### Entregáveis
- arquitetura do sistema;
- diagrama de componentes;
- definição de tecnologias;
- estrutura inicial da aplicação;
- plano de integração.

### Resultado esperado
A solução deve possuir uma base técnica consistente, mantendo o desenvolvimento organizado e preparado para crescimento.

---

## 6. Fase 4 - Planejamento do MVP

### Objetivo
Definir o escopo mínimo viável que será entregue na primeira versão funcional.

### Atividades
- priorização de funcionalidades;
- definição do escopo do MVP;
- organização em backlog;
- identificação das entregas por sprint;
- definição de critérios de aceitação;
- análise de riscos e dependências.

### Elementos do MVP
- autenticação e perfis de usuário;
- cadastro de usuários e áreas;
- monitoramento de câmeras;
- controle de acessos;
- registro de alertas;
- dashboard com visão geral;
- IA básica para suporte à segurança.

### Entregáveis
- backlog do MVP;
- lista de histórias de usuário;
- critérios de aceite;
- roadmap inicial.

### Resultado esperado
O time passa a trabalhar com um objetivo claro: entregar uma primeira versão útil, funcional e demonstrável.

---

## 7. Sprint 1 - Setup inicial e estrutura base do projeto

### Objetivo
Preparar o ambiente de desenvolvimento e criar a base do projeto.

### Atividades
- criação do repositório;
- configuração do ambiente de desenvolvimento;
- estruturação de pastas do projeto;
- definição de padrões de organização;
- criação do projeto base do backend e frontend;
- configuração de banco de dados;
- versionamento e controle de código.

### Entregáveis
- repositório configurado;
- ambiente funcional para desenvolvimento;
- aplicação base inicial;
- estrutura de documentação do projeto.

### Critérios de sucesso
- o projeto consegue rodar localmente;
- a equipe consegue desenvolver em conjunto;
- a base para as próximas fases está pronta.

---

## 8. Sprint 2 - Autenticação, usuários e perfis

### Objetivo
Implementar a base de gestão de usuários e permissões.

### Atividades
- cadastro de usuários;
- autenticação de login;
- controle de perfis;
- autorização por papel (admin, operador, gestor, etc.);
- cadastro de instituições e áreas;
- gestão de usuários por nível de acesso.

### Entregáveis
- sistema de login funcional;
- gestão de usuários;
- perfis com permissões definidas;
- estrutura inicial de segurança da aplicação.

### Critérios de sucesso
- diferentes perfis conseguem acessar apenas aquilo que lhes é permitido;
- a autenticação está segura e funcional.

---

## 9. Sprint 3 - Gestão de câmeras e áreas monitoradas

### Objetivo
Criar o módulo que organiza visualmente as áreas de vigilância da instituição.

### Atividades
- cadastro de câmeras;
- classificação por setor ou área;
- organização de câmeras por campus, entrada, corredor ou ambiente;
- fluxo de visualização de imagens em tempo real;
- criação de mapa básico de monitoramento.

### Entregáveis
- painel de câmeras;
- áreas monitoradas cadastradas;
- visualização básica das câmeras;
- estrutura para futuras integrações com sensores e alertas.

### Critérios de sucesso
- o operador consegue localizar rapidamente a câmera correta;
- a interface permite monitorar áreas de interesse da instituição.

---

## 10. Sprint 4 - Controle de acesso e registros de movimentação

### Objetivo
Implementar o módulo responsável por registrar entradas, saídas e acessos autorizados ou bloqueados.

### Atividades
- cadastro de regras de acesso;
- registro de usuários autorizados;
- controle de entrada e saída;
- bloqueio de acessos indevidos;
- registro de eventos de acesso;
- histórico de movimentação.

### Entregáveis
- módulo de acesso funcional;
- registros de movimentação salvos;
- mecanismo de bloqueio e autorização;
- painel com histórico de acessos.

### Critérios de sucesso
- a instituição consegue identificar quem entrou ou saiu, quando e em qual local;
- o sistema registra eventos de forma confiável.

---

## 11. Sprint 5 - Alertas, notificações e eventos críticos

### Objetivo
Permitir que o sistema avise a equipe responsável quando houver risco ou comportamento suspeito.

### Atividades
- criação de regras de alerta;
- detecção de eventos relevantes;
- envio de notificações para painel ou e-mail;
- organização do histórico de alertas;
- status dos eventos por gravidade.

### Tipos de alertas
- acesso não autorizado;
- tentativa de entrada em área restrita;
- presença suspeita em local inadequado;
- movimentação fora do horário permitido.

### Entregáveis
- mecanismo de alertas ativo;
- painel de ocorrências;
- registro histórico de eventos.

### Critérios de sucesso
- o sistema identifica eventos relevantes e comunica o usuário de forma clara.

---

## 12. Sprint 6 - Dashboard e visão administrativa

### Objetivo
Entrega de uma visão geral para gestores e administradores da instituição.

### Atividades
- desenvolvimento do painel principal;
- indicadores de segurança e acessos;
- gráficos e estatísticas;
- acompanhamento de eventos por período;
- status das câmeras e áreas monitoradas;
- visão geral da operação.

### Entregáveis
- dashboard funcional;
- gráficos e indicadores;
- visão agregada do ambiente institucional;
- painel para tomada de decisão.

### Critérios de sucesso
- gestores conseguem entender rapidamente o estado da segurança da instituição;
- as métricas devem ser úteis e relevantes para a operação.

---

## 13. Sprint 7 - Inteligência artificial e apoio analítico

### Objetivo
Adicionar um primeiro nível de inteligência artificial para apoiar a detecção de padrões e riscos.

### Atividades
- integração com serviço de visão computacional;
- análise de movimentação suspeita;
- identificação de presença em áreas proibidas;
- geração de alertas inteligentes;
- refinamento dos dados de eventos.

### Entregáveis
- módulo de IA funcional;
- apoio na análise de imagem e risco;
- alertas com base em comportamento detectado.

### Critérios de sucesso
- a IA deve agregar valor detectando riscos de forma útil;
- o sistema deve reduzir o trabalho manual de monitoramento.

---

## 14. Sprint 8 - Integração, testes e validação do MVP

### Objetivo
Garantir que o sistema funcione de forma integrada, estável e coerente.

### Atividades
- testes de integração entre módulos;
- testes funcionais de fluxo principal;
- validação do login, câmeras, acessos e alertas;
- correção de erros e ajustes de usabilidade;
- validação com usuário real ou stakeholder;
- refinamento final da interface.

### Entregáveis
- MVP estável;
- testes executados;
- correções aplicadas;
- versão pronta para apresentação.

### Critérios de sucesso
- fluxo principal do sistema funciona corretamente;
- usuário consegue operar a aplicação de forma clara;
- produto atende ao problema central definido.

---

## 15. Fase 9 - Entrega do MVP e avaliação

### Objetivo
Entregar uma versão funcional do produto que demonstra valor real ao cliente.

### Atividades
- revisão final do produto;
- preparação de apresentação do MVP;
- validação com stakeholders;
- coleta de feedback;
- avaliação de melhorias futuras;
- planejamento do próximo estágio de evolução.

### Entregáveis
- MVP concluído;
- apresentação final;
- documento com feedback e melhorias;
- roadmap para versão posterior.

### Resultado esperado
O cliente visualiza uma solução funcional, útil e com potencial para evoluir em versões futuras.

---

## 16. Critérios gerais de sucesso do projeto

O projeto será bem-sucedido se:

- a solução atende ao problema de segurança escolar;
- a interface é clara e funcional;
- câmeras e acessos são gerenciados em um ambiente único;
- alertas ajudam a responder rápido a incidentes;
- a IA agrega valor sem complicar a operação;
- a solução demonstra viabilidade para futuro desenvolvimento.

---

## 17. Roadmap futuro após o MVP

Após a conclusão do MVP, o projeto pode evoluir para:

- integração com mais tipos de sensores;
- análise mais avançada com IA e reconhecimento de padrões;
- alertas em tempo real via celular e e-mail;
- módulos de relatórios avançados;
- expansão para outras instituições e campus;
- integração com sistemas de gestão acadêmica.

---

## 18. Conclusão

Este plano por sprints permite transformar a ideia inicial em um produto concreto, funcional e alinhado com a necessidade real de segurança em instituições de ensino. A proposta está estruturada para entregar valor desde as primeiras fases, com foco em um MVP eficiente, útil e passível de evolução.

A estratégia é começar com o essencial, validar as hipóteses, melhorar a experiência e preparar o produto para crescer em versões futuras.
