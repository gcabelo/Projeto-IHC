
# 1) Cenários de Interação

## Cenário 1: Matheus 
## Cenário de Interação 

Matheus Oliveira, desenvolvedor no time de Futebol de Robôs da FEI, enfrenta a pressão do próximo Campeonato Nacional. Seu objetivo é conduzir o time à vitória, e ele utiliza seu notebook e software de análise de desempenho para coletar dados das partidas anteriores e planejar ajustes táticos com base nos relatórios. Matheus acredita que os relatórios serão fundamentais para alcançar o sucesso no torneio. 

## Refinamento Cenário de Interação 

**Em um dia de treinamento ensolarado na FEI, Matheus Oliveira, desenvolvedor no time de Futebol de Robôs da FEI, se encontra imerso em seu papel de desenvolvedor no time de Futebol de Robôs.** O time está se preparando para o próximo Campeonato Nacional , e Matheus sente a pressão da competição crescendo a cada dia [3]. Seu objetivo principal é conduzir o time à vitória [1], mas ele sabe que isso requer mais do que apenas habilidades técnicas [3].

**Com seu notebook e software de análise de desempenho [4] em mãos, Matheus coleta dados das partidas anteriores do time. Ele observa cada movimento dos robôs, cada decisão tática e cada resultado. Esses dados são então transformados em relatórios detalhados, destacando os pontos fortes e fracos do time.** Conforme Matheus examina os relatórios, ele começa a notar padrões e tendências nas estratégias utilizadas até agora [5]. Algumas delas funcionaram de forma eficaz, enquanto outras levaram a resultados adversos. Com base nessa análise, Matheus identifica áreas de melhoria e começa a planejar como ajustar as táticas do time para otimizar o desempenho [5].


Seu objetivo é claro: **utiliza os insights dos relatórios para criar estratégias mais sólidas, ajustar a formação dos robôs e garantir que o time esteja melhor preparado do que nunca para a competição [1].** Com determinação e foco, Matheus acredita que os relatórios serão a chave para levar o time da FEI à vitória no Campeonato Nacional de Futebol de Robôs [7].

(Legenda de refinamento: 1. Por que, 2. Em que situações, 3. Características dos atores, 4. Como alcançam atualmente, 5. Como realizam, 6. Eventos que disparam, 7. Como sabem se foi concluído) 

## Cenário 2: Carlos 
## Cenário de interação 

Carlos, um técnico dedicado, está na temporada de Futebol de Robôs, onde sua equipe compete em partidas importantes. Ele reconhece a importância dos relatórios de desempenho para melhorar o time, usando dados das partidas anteriores para ajustar estratégias e formações. Carlos busca a vitória nas competições futuras, confiando na análise dos relatórios como parte fundamental de sua estratégia. 

## Refinamento Cenário de Interação 

Carlos, um técnico dedicado [3], encontra-se em meio à temporada de Futebol de Robôs [2], onde sua equipe está competindo em várias partidas importantes. **Consciente da necessidade de melhorar o desempenho do time [1],** ele decide incorporar relatórios de desempenho em sua estratégia.

**Ao usar os dados detalhados das partidas anteriores [4], Carlos identifica padrões e tendências nas táticas de sua equipe, bem como nas dos adversários [5]. Ele percebe que os relatórios são valiosos para tomar decisões informadas sobre como ajustar a formação e as estratégias táticas de sua equipe, com o objetivo de alcançar um desempenho ainda melhor nas competições futuras [6].** Com determinação e foco, Carlos espera que os relatórios sejam a chave para levar seu time à vitória nas próximas partidas [7].


(Legenda de refinamento: 1. Por que, 2. Em que situações, 3. Características dos atores, 4. Como alcançam atualmente, 5. Como realizam, 6. Eventos que disparam, 7. Como sabem se foi concluído) 

## Cenário 3: Brenda 
## Cenário de interação 

Brenda Bonatto, uma jovem desenvolvedora de Futebol de Robôs, busca a vitória na competição regional **com a ajuda de relatórios de desempenho. Durante o treinamento, ela utiliza dados de partidas anteriores para aprimorar a estratégia de sua equipe. Brenda e sua equipe alcançaram o objetivo ao identificar áreas de melhoria nos relatórios e se preparam para a competição sob pressão.** 


## Refinamento Cenário de Interação 

Brenda Bonatto é uma jovem desenvolvedora que busca levar seu time de Futebol de Robôs à vitória na próxima competição regional [1]. **Ela reconhece a importância dos relatórios de desempenho para alcançar esse objetivo e aproveita os dados das partidas anteriores para melhorar a estratégia de sua equipe [4].**

Durante a preparação para a competição regional de Futebol de Robôs, Brenda e sua equipe estão treinando intensamente para vencer [2]. As características de Brenda, como seu conhecimento técnico e dedicação [3], auxiliam na análise dos relatórios e na formulação de estratégias. Brenda e sua equipe alcançaram o objetivo de melhorar o desempenho do time utilizando os insights dos relatórios de desempenho. Eles realizam isso revisando cuidadosamente os dados das partidas e identificando áreas de melhoria [5].


A necessidade de alcançar o objetivo surge conforme a competição regional se aproxima, e a equipe sente a pressão de conquistar o primeiro lugar [6]. **Após eles utilizarem o sistema, observam o desempenho do time na competição e percebem que se saíram melhor do que nas edições anteriores [7].**

(Legenda de refinamento: 1. Por que, 2. Em que situações, 3. Características dos atores, 4. Como alcançam atualmente, 5. Como realizam, 6. Eventos que disparam, 7. Como sabem se foi concluído) 

2) Design Centrado na Comunicação

Nome do Cenário: Verificar classificação de times 


| tópico \> subtópico (diálogo) | falas e signos |
| :--- | :--- |
| Verificar classificação de times | U: Preciso da classificação de um dos times de futebol de robôs. |
| \> Informar dados do Time | D: Qual o time e quais as datas de partidas que você busca? Qual a quantidade de chutes ao gol que o time tem? Qual a quantidade de defesas que o time fez? <br> U: Preciso do time de robôs da FEI, com os dados referente ao primeiro semestre de 2023. |
| \> Consultar dados necessários | D: Aqui estão os dados. |
| \> Informar dados do Time | U: Preciso de um gráfico que represente especificamente cada mês deste primeiro semestre de 2023. |
| \> Sugerir visualização | D: Qual tipo de visualização você busca atingir? A utilização de gráficos em barra lhe supri? Ou a utilização de gráficos de linha que mais completa sua análise? Temos variedade de visualizações que podem ser utilizadas. <br> U: Prefiro um gráfico de linha, pois acho que ele representaria melhor as tendências ao longo dos meses. Estou interessado em visualizar como certos valores mudaram com o tempo e acho que um gráfico de linha daria uma visão clara disso. <br> D: Entendi, visualização disponível para análise. |

Nome do Cenário: Analisar previsão de vitória dos times () 


| tópico \> subtópico (diálogo) | falas e signos |
| :--- | :--- |
| Analisar previsão de vitória dos times | U: Estou precisando de dados históricos de desempenho de alguns times de futebol para analisar e fazer previsões de vitórias para os próximos jogos. |
| \> Informar dados do Time | D: Claro. De quais times você está precisando dos dados e de qual período exatamente? <br> U: Preciso dos dados dos últimos 2 anos dos times A, B e C. Estou interessado em informações como número de vitórias, derrotas, empates, gols marcados e gols sofridos. |
| \> Consultar dados necessários | D: Entendi. Você está procurando por dados agregados por temporada ou precisa de detalhes de cada partida individual? <br> U: Agregados por temporada seria ótimo, mas se tiver dados de cada partida, poderia ser útil também para uma análise mais detalhada. |
| \> visualizar dados do Time | U: Preciso de um gráfico que consiga passar os valores da previsão de vitória que analisei. |
| \> Sugerir visualização | D: Para esse tipo de visualização, o gráfico de pizza assim como o de rosca são boas escolhas. <br> U: Perfeito, isso deve dar uma boa visão geral. |

Nome do Cenário: Verificar padrões dos times  


| tópico \> subtópico (diálogo) | falas e signos |
| :--- | :--- |
| Verificar padrões dos times | U: Preciso identificar padrões dentro dos times de robôs. |
| \> Informar dados do Time | D: Quais Times você deseja consultar? Quais as métricas que deseja? <br> U: Quero verificar os Times da FEI, MAUÁ e Mackenzie, com as métricas de posicionamento de robôs e porcentagem de posse de bola. |
| \> Consultar dados necessários | D: Entendi. Você está procurando por detalhes de cada partida individual? <br> U: dados de cada partida seria ótimo, mas se tiver agregados por temporada, poderia ser útil também para uma análise mais ampla. <br> D: Dados encaminhados, isso deve dar uma boa visão geral. |
3) Mapa de Objetivos
Abaixo está o diagrama de consolidação (Mapa de Objetivos Papéis) do projeto: 

<img width="940" height="560" alt="image" src="https://github.com/user-attachments/assets/f038d9d1-df00-4280-a9cd-bc21cb1ee13a" />


4) Esquema Conceitual de Signos
A seguir está a tabela única consolidada, criada a partir dos dados do projeto: 

| Signo | Origem | Observações | Tipo de conteúdo | Restrição sobre o conteúdo | Valor default | Prevenção | Recuperação |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Usuário (U)** | U | Informação sobre preferências e interações | Dados pessoais ou preferências individuais | Restrições de privacidade | Padrões de configuração | PP: Instruções para login seguro | RA: Procedimentos de recuperação de conta |
| **Times** | Logs | Dados processados e resultados de análise | Relatórios gerados automaticamente | - | - | - | - |
| **Verificar Classificação de Times** | U ou M | Informações sobre a posição do time | Classificação na tabela | Restrições de frequência | - | AL: Restrições sobre a frequência de solicitações | RA: Instruções para lidar com resultados inesperados |
| **Analisar previsão de vitória dos times** | U ou M | Probabilidades e análises estatísticas | Previsões de vitória | - | - | - | RA: Instruções para lidar com resultados inesperados |
| **Verificar padrões dos times** | U ou M | Tendências e comportamentos recorrentes |
