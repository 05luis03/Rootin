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

# PM Identificar Tarefas

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

# PM Estabelecer a Equipe de Trabalho

# PM Estimar Início e Término das Tarefas

# PM Estimativa de Esforço e Custo

# PM Identificar e Documentar os Riscos

# PM Estratégia de Controle de Versão

# PM Integração do Plano do Projeto

# PM Descrever os Elementos no Plano de Projeto

