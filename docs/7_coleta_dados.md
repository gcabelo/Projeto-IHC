# Identificação de Necessidades dos Usuários e Requisitos de IHC

## 1. Que dados coletar?
Com base na análise das personas e do domínio do projeto, os dados a serem coletados dos usuários dividem-se nas seguintes categorias:

- Dados sobre o Usuário: Perfil demográfico, como idade (ex: Matheus, 21 anos) , nível de formação (ex: estudante de Ciência da Computação) , e familiaridade com a linguagem técnica do domínio (informática, engenharia e futebol).

- Dados sobre Tecnologia: Nível de experiência com computadores, habilidades em programação, análise de dados e o uso de ferramentas específicas de software, como dashboards (ex: Power BI) e ambientes de simulação de robôs.

- Dados sobre Conhecimento do Domínio: O nível de compreensão que o usuário possui sobre as regras, estratégias e táticas do Futebol de Robôs , bem como seu conhecimento sobre tendências em IA e robótica.

- Dados sobre Tarefas: Quais são os objetivos principais do usuário (ex: melhorar o desempenho do time) e quais tarefas ele executa para isso (ex: análise de dados em tempo real, desenvolvimento de novas abordagens táticas, colaboração com o técnico).

- Dados sobre Motivações e Valores: O que inspira o usuário (ex: paixão por futebol e tecnologia) , sua atitude perante desafios (ex: determinação) e o que ele valoriza no ambiente de equipe (ex: colaboração, inovação e trabalho em equipe).

## 2. De quem coletar?
Os dados serão coletados primariamente dos atores (personas) definidos no projeto, que representam os usuários-alvo da interface:

- Usuário Primário: Desenvolvedores e integrantes da equipe técnica do time de Futebol de Robôs, representados pela persona Matheus Oliveira. Eles são os principais analistas que irão interagir diretamente com os dashboards para extrair insights.

- Usuário Secundário: O técnico da equipe, representado pela persona Carlos. Ele é o tomador de decisão que consome os relatórios gerados e também pode interagir com a ferramenta para configurar métricas  e validar estratégias.

## 3. Aspectos Éticos

Sim, o projeto deverá considerar aspectos éticos. A natureza dos dados coletados (estratégias táticas e dados de desempenho) é altamente sensível e competitiva.

A abordagem ética do projeto será baseada nos seguintes pilares:

- Privacidade e Confidencialidade: É fundamental garantir a privacidade das informações. Medidas de armazenamento seguro de dados devem ser implementadas para proteger as estratégias e o desempenho das equipes.

- Consentimento Informado: Será necessário obter o consentimento explícito dos técnicos e membros da equipe para a utilização de seus dados (logs de partidas, estratégias) para fins de análise.

- Uso Voluntário: A utilização da ferramenta de análise deve ser estritamente voluntária. Os membros da equipe devem ter a liberdade de decidir se desejam ou não participar.

- Transparência: Os usuários serão informados de maneira clara e transparente sobre como a ferramenta funciona, quais dados exatamente estão sendo coletados e como eles serão processados e utilizados para gerar as análises e padrões.

## 4. Ferramentas de Coleta de Dados
Foram selecionadas três técnicas distintas para a coleta de dados e identificação de necessidades.

- Técnica 1: Questionário (Survey)

Nome do Instrumento: Questionário de Perfil de Usuário.

Objetivo de Aplicação: Coletar dados quantitativos e demográficos dos usuários (conforme definido na seção "Que dados coletar?"). O objetivo é traçar o perfil tecnológico (nível de experiência com análise de dados e dashboards) e de domínio (nível de conhecimento sobre Futebol de Robôs) dos participantes, além de validar suas motivações.


Como Aplicar: 

O questionário deve ser enviado digitalmente aos participantes (desenvolvedores e técnico da equipe) antes de qualquer entrevista ou sessão de observação. As respostas devem ser anônimas (se o grupo de usuários for grande) ou confidenciais (se for pequeno, como neste caso) e individuais, para evitar conflitos de grupo.

Instrumento: Link do Google Forms criado para o projeto:

[https://forms.gle/68AAMYpYyyjE6qht6 ](https://forms.gle/mmL4kXFmPFzfjHJ28)

- Técnica 2: Estudo de Campo (Observação)

Nome do Instrumento: Roteiro de Estudo de Campo (Observação Contextual).

Objetivo de Aplicação: Coletar informações qualitativas valiosas diretamente dos usuários em seu ambiente real (laboratório ou local de treino). O objetivo é entender suas motivações, expectativas , fluxos de trabalho atuais, identificar barreiras no processo de análise de desempenho  e descobrir necessidades não articuladas (que o usuário não sabe que tem).

Como Aplicar: 

O pesquisador deve se deslocar até o local onde a equipe realiza suas análises (ex: laboratório de robótica). Ele deve assumir um papel de observador "passivo", anotando o processo de análise de uma partida sem interferir. O foco é registrar:

Quais ferramentas são usadas atualmente (ex: planilhas, scripts próprios).

Quais são os principais "gargalos" e pontos de frustração (ex: demora para processar, dificuldade em comparar dados).

Como a informação flui entre o analista (Matheus) e o técnico (Carlos).

Instrumento (Roteiro de Observação):

Local: Laboratório da Robo FEI / Área de treinamento.

Atores: Analista (Matheus), Técnico (Carlos).

- Técnica 3: Entrevista

Nome do Instrumento: Entrevista.

Objetivo de Aplicação: Coletar dados qualitativos sobre as "dores" e necessidades. Enquanto o Questionário nos dá o "o quê" (dados demográficos e superficiais) e o Estudo de Campo  nos mostra "como" eles trabalham, a Entrevista nos revela o "porquê". Ela é fundamental para entender o contexto, as frustrações atuais e as expectativas em relação à nova ferramenta.

Como Aplicar:

A entrevista deve ser agendada individualmente com os representantes das personas (ex: um desenvolvedor real do time, como o "Matheus" , e o técnico, como o "Carlos" ). É importante que sejam separados para evitar que a opinião do técnico influencie a do analista.

A sessão deve durar de 30 a 45 minutos em um local reservado (laboratório ou sala de reunião).

O entrevistador deve explicar o objetivo (entender as necessidades para construir uma ferramenta melhor), garantir a confidencialidade  e pedir permissão para gravar o áudio (para facilitar a análise posterior).

O entrevistador seguirá o roteiro de perguntas-chave, mas terá a liberdade de fazer novas perguntas com base nas respostas do usuário (ex: "Você pode me dar um exemplo disso?", "Por que isso é um problema?").

Instrumento:

1. Abertura e Contexto Atual (Tarefas)

"Obrigado por seu tempo. Nosso objetivo é entender melhor seu dia a dia para criar uma ferramenta de análise que seja realmente útil."

"Me conte como é o processo de vocês hoje, após uma partida de robôs. Por onde você começa a análise?"

"Quais ferramentas você usa atualmente para fazer isso?"

2. Identificação de Dores e Necessidades

"O que mais te frustra nesse processo atual? O que toma mais tempo ou é mais difícil de fazer?" 

"Existe alguma informação que você gostaria de ter, mas que hoje é muito difícil ou impossível de conseguir com os logs?"

"Pense na última vez que vocês perderam um jogo que achavam que iam ganhar. Quais dados você gostaria de ter tido acesso durante o jogo para talvez mudar o resultado?"

3. Validação de Requisitos e Priorização

"No nosso projeto, estamos pensando em visualizações como 'Posse de Bola por Partida' e 'Classificação de Times' (Ofensivo/Defensivo). Quão importantes são essas métricas para você, de 0 a 10?"

"Se o dashboard inicial só pudesse mostrar 3 gráficos, quais seriam os 3 mais essenciais para sua tomada de decisão?"

"Com que frequência você acha que usaria essa ferramenta? (ex: diariamente, após cada jogo, semanalmente?)"

4. Fechamento

"Há algo que eu não perguntei que você acha fundamental para o sucesso dessa ferramenta?"

"Você teria interesse em testar um protótipo inicial quando estiver pronto?"

