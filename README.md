# Rootin

![Capa](/Public/imgs/LogoComNomeLateral_FundoEscuro.png)


No ritmo do tempo, defina o valor de cada escolha! Aplicativo mobile que integra gerenciamento de tarefas com rastreamento de gastos, oferecendo insights visuais e personalizados por IA para te ajudar a alcançar autonomia financeira.

## Plano Estratégico

* A ideia do projeto nasceu com o objetivo de ser uma plataforma que garante que os usuários consigam aproveitar a vida cotidiana com consciência financeira, transformando hábitos diários em decisões inteligentes para um futuro financeiro próspero e autônomo.
* Nossa estratégia é baseada na crença de que a autonomia financeira não deve ser complexa ou entediante, mas sim agregada de forma intuitiva e divertida ao dia a dia.
* Ao juntarmos a gestão de tarefas com o rastreamento financeiro detalhado e inteligência artificial personalizada, o Rootin torna-se um parceiro importante na jornada financeira de seus usuários.

## Escopo do Trabalho

As atividades a serem realizadas consistem no desenvolvimento e lançamento de uma plataforma de gestão de rotina e finanças pessoais, chamada Rootin, para dispositivos móveis (iOS e Android), suportada por um sistema de back-end robusto e um módulo de inteligência artificial.

O escopo abrange as seguintes áreas principais:

### Desenvolvimento do Aplicativo Móvel (Front-end):

* **Gestão de Rotina:** Criação de tarefas diárias, semanais e mensais, definição de datas e horários, lembretes personalizáveis, categorização de tarefas.
* **Registro de Gastos Integrado à Rotina:** Função que permite vincular um gasto diretamente a tarefas concluídas (ex: "Mercado" → "R$X", com itens comprados).
* **Dashboard e Relatórios Visuais:** Tela para visualização do saldo atual, gastos diários, semanais e mensais.Gráficos e infográficos que mostram padrões de consumo (ex: "gastos com comida aos finais de semana").
* **Controle de Reservas:** Permite ao usuário indicar se o gasto veio do saldo principal ou de uma reserva específica.
* **Metas Financeiras:** Criação e acompanhamento visual de metas de economia (ex: "Viagem", "Carro").
* **Interface Amigável e Descontraída:** Design UI/UX que facilite o uso, com linguagem acessível e elementos visuais atraentes.

### Desenvolvimento do Sistema de Back-end e Banco de Dados:

* **Autenticação e Segurança:** Sistema de login seguro, proteção de dados do usuário e conformidade com normas de privacidade (LGPD).
* **Armazenamento de Dados:** Banco de dados otimizado para armazenar tarefas, registros financeiros, categorias, metas e perfis de usuário de forma segura e escalável.
* **Processamento de Dados:** Lógica para agregação, categorização e análise de dados de rotina e financeiros, alimentando os relatórios e a IA.

### Desenvolvimento do Módulo de Inteligência Artificial (RAI - Rootin Artificial Intelligence):

* **Análise de Padrões de Gastos:** Algoritmos para identificar tendências de consumo, picos de gastos e categorias de maior despesa (ex: "gastos maiores aos finais de semana com comida").
* **Alertas e Notificações Inteligentes:** Envio de alertas personalizados sobre desvios do orçamento, oportunidades de economia ou progresso em metas.
* **Sugestões Personalizadas:** Geração de recomendações acionáveis para otimização de gastos e rotinas (ex: "Que tal cozinhar mais em casa para economizar na categoria X?").
* **Acompanhamento de Metas com IA:** Feedback inteligente sobre o progresso das metas financeiras do usuário.
* **Educação Financeira Contínua:** Pequenas "pílulas" de conhecimento financeiro, entregues de forma contextualizada e descontraída pela IA.


## Empacotamento do Software

Os componentes da unidade de produto serão empacotados na mídia adequada para cada fase da distribuição.

* **Mídia de Empacotamento:** Os pacotes digitais do aplicativo móvel incluirão:
    * Arquivo .aab (Android App Bundle) ou .apk (Android Application Pack).
    * Arquivo .ipa (iOS App Store Package).

## Distribuição do Software

A distribuição será realizada pela internet, com foco em escalabilidade e segurança.

* **Canal de Distribuição:** O aplicativo será publicado e distribuído através da App Store (iOS) e Google Play Store (Android).
* **Processo de Instalação:** O processo de instalação será controlado pelo usuário, mas projetado para ser simples e acessível. Os usuários realizarão o download e a instalação diretamente das lojas de aplicativos.

## Auxílio e Assistência ao Usuário

O suporte será um pilar para alcançar as metas estratégicas do projeto, como ser referência em educação financeira personalizada.

* **Ajuda Proativa (via IA):** O principal meio de auxílio será a própria IA, fornecendo sugestões personalizadas.
* **Suporte Reativo:**
    * O lançamento contará com um suporte ao cliente inicial configurado.
    * A equipe realizará o monitoramento de performance e segurança para identificar e resolver problemas proativamente.

## Identificação de Tarefas

### Front-end Mobile
#### Gestão de Rotinas
- [ ] Implementar criação de tarefas recorrentes
- [ ] Desenvolver sistema de lembretes inteligentes
- [ ] Criar interface de categorização

#### Dashboard Financeiro
- [ ] Construir visualização de saldo atual
- [ ] Implementar gráficos de gastos (diários/semanais/mensais)
- [ ] Desenvolver módulo de metas financeiras

### Back-end
#### Autenticação e Segurança
- [ ] Implementar OAuth 2.0
- [ ] Configurar conformidade com LGPD
- [ ] Desenvolver criptografia de dados

#### Banco de Dados
- [ ] Modelar estrutura de dados
- [ ] Implementar queries otimizadas
- [ ] Configurar backups automáticos

### Módulo RAI (IA)
- [ ] Desenvolver algoritmos de análise de padrões
- [ ] Implementar sistema de alertas inteligentes
- [ ] Criar motor de recomendações personalizadas

## Empacotamento e Distribuição
| Plataforma | Formato | Tarefas |
|------------|---------|---------|
| Android    | .aab    | [ ] Configurar assinatura<br>[ ] Otimizar tamanho<br>[ ] Testar compatibilidade |
| iOS        | .ipa    | [ ] Configurar App Store Connect<br>[ ] Implementar TestFlight<br>[ ] Validar guidelines |

## Tarefas de Lançamento
1. **Pré-lançamento**
   - [ ] Testes beta com usuários reais
   - [ ] Campanha de pré-cadastro
   - [ ] Preparação de material de suporte

2. **Pós-lançamento**
   - [ ] Monitoramento de crash reports
   - [ ] Análise de métricas de uso
   - [ ] Programa de feedback contínuo

## Priorização

    title Cronograma de Prioridades
    dateFormat  YYYY-MM-DD
    section Core
    Autenticação       :done,    auth1, 2023-10-01, 15d
    Dashboard          :active,  dash1, 2023-10-16, 20d
    section IA
    Análise de Padrões :         ia1, 2023-11-05, 25d


## Como o Trabalho Será Medido
Para conseguirmos mensurar o tamanho do ROOTIN, iremos olhar o projeto de vários pontos
* Como a Medida Será Realizada:
    * Pontos de função: é um jeito de mensurar a quantidade de funcionalidades que o app vai entregar para o usuário, sem ver a tecnologia por trás. Exemplo: quantos dados o app vai receber (inputs), quantos resultados ele vai mostrar (outputs), etc.
    * Pontos de Features: aqui nós atribuímos um peso para cada funcionalidade que o ROOTIN vai ter a parte de "Gerenciar a Rotina" , o "Registro de Gastos Integrado" , o "Dashboard dos Relatórios" , a "Análise da IA dos Padrões de Gastos" , as "Metas Financeiras", etc.
* Dividido o Projeto em Pequenas Partes:
    * O Aplicativo no Celular (Front-end):
        * A parte de criar tarefas, colocar lembretes, categorizar.
        * Registrar os gastos e ligar eles às tarefas.
        * As telas bonitas dos relatórios e do seu saldo atual.
        * A função de controlar suas reservas de dinheiro.
        * As telas de metas financeiras.
        * Todo o visual e a facilidade de uso (UI/UX).
    * O Sistema por Trás (Back-end e Banco de Dados):
        * Onde você faz seu login seguro e seus dados são protegidos (LGPD). 
        * Onde todas as suas informações (tarefas, gastos, metas) são guardadas de forma segura e organizada. 
        * A "fábrica" que processa todos os dados para IA e os relatórios.
    * A Inteligência Artificial (RAI):
        * Os algoritmos que "aprendem" seus padrões de gasto. 
        * Os alertas e notificações que a IA vai te mandar. 
        * As sugestões personalizadas para você economizar. 
        * O feedback esperto da IA sobre suas metas.



# PM Identificar e Documentar Recursos
## Visão Integrada dos Recursos do Projeto

O documento centraliza a visão de todos os recursos necessários ao projeto Rootin, estabelecendo que seu sucesso depende da alocação e integração de três categorias principais. A primeira é o **recurso humano**, com uma equipe multidisciplinar de papéis definidos, desde a gestão até o desenvolvimento e suporte. A segunda abrange os **recursos materiais e tecnológicos**, como hardware, a infraestrutura de nuvem escalável e as ferramentas de desenvolvimento e licenciamento.Por fim, são definidos os **recursos normativos**, que incluem a adesão a padrões de segurança como LGPD e ISO 27001, e a processos de trabalho como o Gitflow.
# PM Estabelecer a Equipe de Trabalho
## Equipe do Projeto Rootin e Suas Responsabilidades

* **Gerente de Projeto:** Guia o projeto, define o escopo e garante a eficiência na execução para atender aos objetivos de negócio.
* **Designer UI/UX:** Cria a arquitetura da informação e o design visual e interativo do aplicativo.
* **Desenvolvedores de Front-end:** Implementam a interface e as funcionalidades do aplicativo móvel (iOS & Android).
* **Desenvolvedores de Back-end:** Constroem e mantêm o sistema central de autenticação, segurança, banco de dados e processamento de dados.
* **Desenvolvedores de IA (RAI):** Desenvolvem os algoritmos de análise de gastos, alertas e sugestões personalizadas.
* **Analistas de Qualidade / Testadores:** Validam o produto, realizam testes com usuários na Fase Beta e garantem um lançamento "sem bugs críticos".
* **Equipe de Suporte ao Cliente:** Operam o suporte ao usuário final e monitoram a performance e segurança da aplicação de forma proativa.

# PM Estimar Início e Término das Tarefas
O cronograma do projeto Rootin descreve como o desenvolvimento será executado, controlado e encerrado, com uma duração total estimada de 21 semanas, entre agosto e dezembro. O projeto está dividido em fases principais: Planejamento (3 semanas), Desenvolvimento de Back-end (8 semanas), Front-end (7 semanas) e IA (6 semanas), seguidas por Integração (2 semanas), Testes Beta (4 semanas) e Lançamento (1 semana). O controle do projeto será feito com o sistema de versão Git e ferramentas de gerenciamento como Jira, Trello ou Asana. Os principais riscos considerados são atrasos no cronograma, segurança de dados e baixa aceitação do usuário.

![NetworkDiagram](/Public/imgs/NetworkDiagram.png)

# PM Estimativa de Esforço e Custo
![EAP](/Public/imgs/EAP.PNG)

A Estrutura Analítica do Projeto (EAP), representada visualmente no seu diagrama, é a fundação para a estimativa de esforço e custo. Ela decompõe o escopo total do projeto em fases e pacotes de trabalho menores, como o desenvolvimento do Back-end , Front-end  e do módulo de Inteligência Artificial. Para cada um desses pacotes, são alocados recursos e competências críticas específicas. A estimativa detalhada do custo é então calculada com base no esforço previsto para estes recursos, somando-se também os custos de produtos externos  e a mitigação de riscos, formando assim uma base sólida para o orçamento final do projeto.

## Identificar e Documentar os Riscos
### Objetivo
Mapear riscos potenciais e estabelecer planos de mitigação para garantir o sucesso do projeto.

### Riscos Técnicos

| Risco | Probabilidade | Impacto | Plano de Mitigação | Plano de Contingência |
|-------|--------------|---------|--------------------|-----------------------|
| **Integração de módulos** | Alta | Crítico | • Testes de integração contínuos<br>• APIs bem documentadas<br>• Ambiente sandbox para testes | • Squad dedicado a integrações<br>• Buffer de tempo no cronograma |
| **Segurança de dados** | Alta | Crítico | • Criptografia AES-256<br>• Pentests mensais<br>• Conformidade LGPD | • Plano de resposta a incidentes<br>• Seguro contra vazamentos |
| **Escalabilidade do back-end** | Média | Alto | • Load testing semanal<br>• Arquitetura microserviços<br>• Auto-scaling configurado | • Parceria com provedor cloud<br>• Plano de otimização emergencial |

### Riscos de Projeto

| Risco | Probabilidade | Impacto | Mitigação | Contingência |
|-------|--------------|---------|-----------|--------------|
| **Atrasos no cronograma** | Alta | Alto | • Sprints curtos (2 semanas)<br>• Daily standups<br>• Critical path analysis | • Priorização MVP<br>• Hora-extra controlada |
| **Estouro de orçamento** | Média | Alto | • Controle financeiro semanal<br>• Reserve de contingência (15%)<br>• Revisão trimestral | • Redução de escopo não-crítico<br>• Busca de investimento adicional |

### Riscos de Mercado

| Risco | Probabilidade | Impacto | Estratégia | Plano B |
|-------|--------------|---------|------------|---------|
| **Baixa aceitação do usuário** | Média | Alto | • Beta testing com 500 usuários<br>• Pesquisas NPS semanais<br>• Programa de feedback | • Pivotar funcionalidades<br>• Campanha de marketing agressiva |
| **Rejeição nas app stores** | Baixa | Médio | • Pré-validação com guidelines<br>• Consultoria especializada<br>• Testes em ambiente staging | • Correções rápidas<br>• Appeal técnico<br>• Planos de publicação alternativos |

## Estratégia de Controle de Versão
### Objetivo
Estabelecer uma estratégia robusta de controle de versão para o desenvolvimento do aplicativo Rootin, garantindo rastreabilidade e colaboração eficiente.

### Ferramentas e Infraestrutura
- **Sistema de Controle**: Git (distribuído)
- **Plataforma de Hospedagem**:
  - GitHub/GitLab
  - Inclui:
    - Rastreamento de issues
    - Pipelines de CI/CD
    - Ferramentas de revisão de código

### Estratégia de Branching (Gitflow)
| Tipo de Branch  | Convenção de Nomeação   | Finalidade                      | Destino de Merge |
|-----------------|-------------------------|--------------------------------|------------------|
| **main**        | `main`                  | Código estável em produção     | -                |
| **develop**     | `develop`               | Branch de integração           | main             |
| **feature**     | `feature/[nome]`        | Desenvolvimento de funcionalidades | develop       |
| **release**     | `release/[versão]`      | Preparação de lançamentos      | main + develop   |
| **hotfix**      | `hotfix/[descrição]`    | Correções críticas em produção | main + develop   |


### Tipos de Commit
| Tipo       | Descrição                          | Exemplo                          |
|------------|------------------------------------|----------------------------------|
| `feat`     | Nova funcionalidade                | `feat(auth): adiciona login OAuth2` |
| `fix`      | Correção de bug                    | `fix(ui): alinhamento de botões` |
| `docs`     | Mudanças na documentação           | `docs: atualiza referência da API` |
| `refactor` | Reestruturação de código           | `refactor: serviço de pagamentos` |
| `test`     | Mudanças relacionadas a testes     | `test: adiciona testes unitários` |

### Processo de Code Review
1. **Pré-requisitos**:
   - Todos os testes passando
   - Documentação atualizada
   - Conformidade com padrões de código

2. **Checklist de Revisão**:
   - [ ] Funcionalidade do código
   - [ ] Impacto na performance
   - [ ] Considerações de segurança
   - [ ] Cobertura de testes

3. **Aprovação**:
   - Mínimo de 2 aprovações necessárias
   - Pipeline de CI deve passar
   - Aprovação do Product Owner para funcionalidades

### Versionamento (SemVer)
Formato: `MAIOR.MENOR.PATCH`

- **MAIOR**: Mudanças incompatíveis
- **MENOR**: Funcionalidades compatíveis
- **PATCH**: Correções de bugs compatíveis

Exemplo: `v2.1.3`
- 2 = Versão principal (mudanças incompatíveis)
- 1 = Versão menor (novas funcionalidades)
- 3 = Patch (correções de bugs)

### Gerenciamento de Releases
1. Criar branch de release a partir de develop
2. Atualizar versão em:
   - `package.json`
   - Documentação
   - CHANGELOG.md
3. Realizar testes finais
4. Merge para main e tag da versão
5. Deploy em produção

### Boas Práticas
- Commits atômicos (uma mudança lógica por commit)
- Push frequente para o repositório remoto
- Limpeza de branches após merge
- Commits assinados para mudanças críticas
- Geração de changelog convencional


## Integração do Plano do Projeto

# Visão Geral
Estratégia para alinhamento dos componentes do projeto (tarefas, riscos, versão e qualidade) garantindo coordenação entre todas as áreas do desenvolvimento do aplicativo Rootin.

# Componentes Integrados

| Componente               | Objetivo                              | Responsável          |
|--------------------------|---------------------------------------|----------------------|
| Plano de Tarefas         | Gerenciar atividades e dependências   | Scrum Master         |
| Gestão de Riscos         | Identificar e mitigar ameaças         | Risk Manager         |
| Controle de Versão       | Versionamento do código               | Tech Lead            |
| Plano de Comunicação     | Alinhamento entre stakeholders        | Product Owner        |
| Gestão de Recursos       | Alocação de equipe e infraestrutura   | Project Manager      |

# Estratégias de Integração
### Tarefas ↔ Riscos

    A[Tarefa Complexa] --> B[Identifica Risco]
    B --> C[Plano de Mitigação]
    C --> D[Nova Tarefa de Segurança]
