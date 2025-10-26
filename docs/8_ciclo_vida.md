
# CICLO DE VIDA DE ENGENHARIA DE USABILIDADE

## 1. Características da Plataforma

| Característica | Descrição |
| :---- | :---- |
| **Descrição do Software** | O software é uma plataforma de Business Intelligence (BI) e Data Analytics. Seu objetivo é ingerir, processar e analisar logs de partidas de Futebol de Robôs, oferecendo visualizações gráficas (dashboards), filtros interativos e ferramentas para configuração personalizada de métricas táticas e estratégicas. |
| **Descrição do Hardware** | A interface principal (dashboard) é projetada para ser utilizada em computadores de mesa (`PC`) e notebooks (`Laptop`), que são os dispositivos padrão em ambientes de laboratório e para desenvolvedores. O hardware deve ser capaz de suportar o processamento de grandes volumes de dados de log, sendo recomendado o uso de monitores de alta resolução para a visualização eficiente de múltiplos gráficos. |
| **LISTA DE Capacidades da Plataforma (com explicação)** | **1. Ingestão e Processamento de Logs:** Capacidade de importar logs de partidas em formatos específicos (`.log`, `.csv`) e processá-los automaticamente, transformando dados brutos de sensores (posição, velocidade, interação) em métricas táticas. **2. Configuração de Métricas:** Permite aos usuários avançados (Técnico/Analista) definir ou ajustar o peso de métricas personalizadas (ex: o que é um "chute a gol" ou qual a importância da "posse de bola" na classificação tática). **3. Visualização Interativa:** Oferece dashboards dinâmicos com filtros de tempo, adversário e tipo de análise, permitindo ao usuário manipular os dados em tempo real. |
| **LISTA DE Restrições da Plataforma (com explicação)** | **1. Dependência de Logs Estruturados:** O sistema só funcionará corretamente se os logs gerados pelos robôs e pelo sistema de simulação estiverem em um formato padronizado e esperado. Logs corrompidos ou em formatos desconhecidos interromperão a análise. **2. Requisitos de Processamento:** O hardware cliente (PC ou Notebook) pode ter restrições de processamento ou memória ao lidar com a análise de logs muito longos ou ao realizar comparações complexas entre múltiplos jogos. **3. Ambiente de Uso Específico:** A plataforma é restrita ao domínio do Futebol de Robôs. Suas métricas e classificações não são aplicáveis ao futebol humano, limitando o público-alvo a desenvolvedores, analistas e técnicos de robótica. |

## 2. Princípios Gerais do Projeto (INCREMENTAR TABELA)

| Nome | Descrição | Link |
| :---- | :---- | :---- |
| **Descrição do Contexto** | A plataforma será utilizada em um ambiente altamente técnico e competitivo (Futebol de Robôs). O contexto de uso é a análise tática pós-jogo e o planejamento estratégico. A interface precisa ser extremamente eficiente e fornecer *insights* de forma rápida e precisa, pois os usuários (analistas e técnicos) trabalham sob pressão por resultados e o tempo de análise entre as partidas é limitado. | **Contexto Competitivo/Técnico** |
| Lei Geral de Proteção de Dados (LGPD) - Lei n.º 13.709/2018 | A LGPD é a legislação brasileira que regulamenta o tratamento de dados pessoais no Brasil. É importante para o projeto porque estabelece regras sobre como os dados dos usuários devem ser coletados, armazenados, processados e protegidos, garantindo sua privacidade e segurança. | [https://www.planalto.gov.br/ccivil\_03/\_ato2015-2018/2018/lei/l13709.htm](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm) |
| Lei n.º 10.098/2000 - Lei da Acessibilidade | Esta lei brasileira estabelece normas gerais e critérios básicos para a promoção da acessibilidade das pessoas com deficiência ou com mobilidade reduzida. É importante para o projeto porque define diretrizes para tornar produtos e serviços, incluindo interfaces de usuário, acessíveis a todos os usuários, independentemente de suas habilidades físicas ou cognitivas. | [https://www.planalto.gov.br/ccivil\_03/leis/l10098.htm](https://www.planalto.gov.br/ccivil_03/leis/l10098.htm) |
| ABNT NBR ISO 9241 Ergonomia da interação humano-sistema | Esta série de normas brasileiras, baseadas nas normas ISO 9241, fornece diretrizes e orientações para o design centrado no usuário de sistemas interativos, incluindo a concepção de interfaces de usuário. A parte 210 aborda o processo de design centrado no humano, enquanto a parte 11 fornece orientações específicas sobre usabilidade. Essas normas são importantes para o projeto porque estabelecem princípios e métodos para garantir que a interface do usuário atenda às necessidades e expectativas. | [https://www.inf.ufsc.br/\~edla.ramos/ine5624/\_Walter/Normas/Parte%2011/iso9241-11F2.pdf](https://www.inf.ufsc.br/~edla.ramos/ine5624/_Walter/Normas/Parte%2011/iso9241-11F2.pdf) |
| **Lei de Fitts** | Princípio da Interação que afirma que o tempo necessário para mover um apontador (mouse) para um alvo é uma função da distância até o alvo e do tamanho do alvo. É vital para o projeto porque garante que botões e filtros críticos no dashboard sejam grandes e fáceis de alcançar, maximizando a eficiência e velocidade do analista. | [https://www.interaction-design.org/literature/article/fitts-s-law-the-science-behind-cursor-targeting](https://www.interaction-design.org/literature/article/fitts-s-law-the-science-behind-cursor-targeting) |

## 3. Metas de Usabilidade

### 1. Qualitativo

| Meta de Usabilidade | Descrição |
| :--- | :--- |
| **Eficiência e Produtividade** | O sistema deve permitir que os analistas (como Matheus) completem a análise tática de uma partida em **50% menos tempo** do que o gasto com a utilização de scripts e planilhas manuais. A interface deve reduzir a sobrecarga cognitiva para a tomada de decisão. |
| **Confiabilidade da Informação** | Os usuários (como o Técnico Carlos) devem considerar o resultado das análises do dashboard como **altamente confiável** e preciso para a tomada de decisões táticas, de forma que o uso da ferramenta se torne o método padrão de planejamento. |
| **Facilidade de Customização** | Usuários avançados devem ser capazes de **configurar e ajustar o peso das métricas** de desempenho de forma intuitiva, sem a necessidade de recorrer ao código-fonte ou a documentação extensa. |

### 2. Quantitativo

| Metas | Porcentagem | Justificativa |
| ----- | :---- | :---- |
| **Facilidade de Aprendizado (Learnability)** | **50%** | Um novo analista deve ser capaz de realizar as 3 tarefas principais (Inserir Log, Filtrar Dados, Visualizar Classificação Tática) em até 15 minutos de uso autônomo. |
| **Eficiência de Tarefa (Time on Task)** | **30%** | O tempo médio gasto para filtrar os logs e comparar duas equipes adversárias não deve ultrapassar 60 segundos, após a familiaridade inicial. |
| **Taxa de Erros Críticos** | **15%** | A taxa de erros graves (erros que causam perda ou corrupção de dados, como inserir um log no formato errado) não deve exceder 15% das tentativas. |
| **Taxa de Sucesso na Tarefa** | **5%** | Garantir que pelo menos 95% dos usuários consigam completar as tarefas-chave de análise sem recorrer à ajuda externa ou documentação. |
| **Total** | **100%** | A soma das porcentagens é distribuída entre as métricas de usabilidade essenciais para o projeto (aprendizado e eficiência são prioritários em um ambiente técnico). |
