# Análise de Tarefas

Descrição das Funcionalidades Principais
Conforme solicitado, esta seção descreve as funcionalidades mais importantes da interface do produto de análise de dados para futebol de robôs, que são modeladas a seguir:


- Input de Logs: Refere-se à capacidade central do sistema de ingerir, processar e classificar os dados brutos (logs) gerados pelos robôs durante as partidas, preparando-os para a análise.
- Validação de Relatórios: Permite ao usuário (técnico ou analista) verificar a precisão e a integridade dos relatórios gerados pela plataforma, comparando-os com os dados originais.
- Configuração de Métricas: Oferece ao usuário a flexibilidade de personalizar a análise, permitindo ajustar, editar ou definir parâmetros e pesos das métricas de desempenho.
- Gerenciamento de Logs de Partidas: Descreve a interação do usuário com o sistema para inserir novos logs de partidas, bem como visualizar e filtrar logs de jogos anteriores.
- Classificação de Times: Modela a capacidade do sistema de, a partir da solicitação do usuário e de parâmetros predefinidos, classificar os times e informar suas categorias (ex: ofensivo, defensivo).

# Análise Hierárquica de Tarefas (HTA)
A seguir, apresentamos a Análise Hierárquica de Tarefas para três funcionalidades centrais do sistema.

## 1. Funcionalidade: Input de Logs

Esta funcionalidade descreve o processo completo de entrada de dados no sistema. A tarefa principal (0. Input de Logs) é decomposta em três sub-tarefas principais:

- Coletar os dados brutos dos sensores dos robôs.
- Classificar os tipos de logs recebidos (ex: movimentação, interação com a bola).
- Integrar os logs classificados na plataforma de análise para visualização.

## Diagrama HTA - Input de Logs:

<img width="940" height="333" alt="image" src="https://github.com/user-attachments/assets/412ce39e-97b4-4584-9270-716d34ae333b" />


| Objetivos/Operações | Problemas e Recomendações |
| :--- | :--- |
| **0. Input de Logs**<br>1>2>3 | **Plano:** Coletar logs dos robôs, depois classificar os logs e depois integrar os logs na plataforma de análise |
| **1. Coletar logs dos sensores dos robôs**<br>1>2>3 | **Input:** Dados brutos dos sensores dos robôs. <br>**Feedback:** Indicação do status de coleta (completa, em progresso, falhou). <br>**Plano:** Sincronizar os sensores, depois realizar a verificação dos dados recebidos e depois transferir os dados para o sistema de análise. |
| 1.1 Sincronizar os sensores com o sistema de coleta | **Plano:** Passo para garantir que todos os sensores estejam sincronizados com o sistema de coleta. |
| 1.2 Garantir a integridade dos dados durante a coleta | **Input:** Dados dos sensores.<br>**Problema:** Ocorrer um erro durante a coleta dos dados.<br>**Plano:** Procedimento para verificar a integridade dos dados e corrigir erros. |
| 1.3 Transferir dados para o sistema de análise | **Input:** Dados coletados prontos para transferência. <br>**Problema:** Ocorrer um erro durante a transferência de dados. <br>**Feedback:** Status da transferência (completa, falhou, em progresso). <br>**Plano:** Procedimento para iniciar, monitorar e confirmar a transferência de dados. |
| **2. Classificar tipos de logs**<br>1+2+3 | **Input:** Logs brutos para classificação. <br>**Feedback:** Resultado da classificação. <br>**Plano:** Informar os dados de movimentação, interação com a bola e interação com outros robôs |
| 2.1 Dados de movimentação | |
| 2.2 Dados de interação com a bola<br>1>2 | **Input:** Dados brutos da interação com a bola. <br>**Plano:** Método para detectar, registrar e depois classificar interações com a bola. |
| 2.2.1 Detectar e registrar toques na bola | |
| 2.2.2 Classificar tipos de toque | **Plano:** Classificar tipos de toque em passe, drible e chute. |
| 2.3 Dados de interação com outros robôs | **Input:** Dados brutos da interação com robôs. <br>**Feedback:** Resultados da classificação de interações entre robôs. <br>**Plano:** Método para detectar, registrar e classificar interações entre robôs. |
| **3. Integrar logs em plataforma de análise** | **Input:** Logs classificados prontos para integração. <br>**Problema:** Formato dos logs não condizem com o formato aceito pela plataforma. |
| 3.1 Converter dados para formato aceitável pela plataforma | **Problema:** Falha na conversão de dados. |
| 3.2 Upload dos dados | |

## 2. Funcionalidade: Validação de Relatórios

Esta funcionalidade permite ao usuário confirmar a precisão dos relatórios gerados pelo sistema. O processo envolve selecionar um relatório (1), revisar seus dados (2) — o que inclui comparar com os logs originais (2.1) e verificar a precisão (2.2) — e, por fim, confirmar a validação ou listar os erros (3) e salvar esse status (4).

## Diagrama HTA - Validação de Relatórios:

<img width="940" height="373" alt="image" src="https://github.com/user-attachments/assets/07bb7c2a-8b58-4ed3-a5e7-470808e0c84d" />


| Objetivos/Operações | Problemas e Recomendações |
| :--- | :--- |
| **0. Validação de Relatórios**<br>1>2>3>4 | **Plano:** Realizar a verificação dos Relatórios que foram gerados após a tratativa dos logs depois revisar os dados, depois informar resultados da verificação e depois confirmar o status da validação |
| **1. Escolher relatório a validar** | **Input:** Lista de relatórios gerados. <br>**Feedback:** Relatório selecionado e pronto para revisão. <br>**Plano:** Navegar pela lista de relatórios disponíveis, selecionar o relatório desejado para validação. |
| **2. Revisar dados do relatório**<br>1+2 | **Input:** Conteúdo do relatório escolhido. <br>**Feedback:** Relatório revisado, com pontos destacados para validação. <br>**Plano:** Abertura e leitura do relatório, seguido de comparação com os logs originais e verificação da precisão dos dados. |
| 2.1 Comparar com logs originais | **Input:** Dados apresentados no relatório e logs originais.<br>**Problema:** Discrepâncias entre o relatório e os logs.<br>**Plano:** Procedimento detalhado para alinhar e comparar os dados do relatório com os logs originais. |
| 2.2 Verificar precisão dos dados | **Input:** Resultados da comparação. <br>**Problema:** A precisão dos dados não pode ser confirmada. <br>**Feedback:** Indicação das discrepâncias ou confirmação da precisão. <br>**Plano:** Procedimento para verificar e validar a precisão dos dados apresentados. |
| **3. Confirmar validação ou listar erros** | **Input:** Resultado da revisão. <br>**Feedback:** Lista de erros, se houver, ou confirmação de validação. <br>**Plano:** Após a revisão completa, confirmar a validação do relatório ou listar todas as discrepâncias identificadas. |
| **4. Salvar status de validação** | **Input:** Status de validação (validado, contém erros). <br>**Feedback:** Indicação de que o status de validação foi salvo. <br>**Problema:** Falha ao salvar o status. <br>**Plano:** Procedimento para registrar o status da validação e salvar no sistema. |


## 3. Funcionalidade: Configurações de Métricas

Esta funcionalidade descreve como um usuário pode personalizar a análise de desempenho. O usuário acessa o menu de métricas (1), seleciona a métrica que deseja configurar ou editar (2) — definindo seus parâmetros (2.1) ou ajustando seu peso no desempenho geral (2.2) — testa o impacto dessa mudança no relatório (3) e, finalmente, salva as novas configurações (4).


## Diagrama HTA - Configurações de Métricas:

<img width="940" height="377" alt="image" src="https://github.com/user-attachments/assets/65818c49-6922-461b-b890-1528bdaface8" />

| Objetivos/Operações | Problemas e Recomendações |
| :--- | :--- |
| **0. Configurações de métricas**<br>1>2>3>4 | **Plano:** Navegar até o menu de métricas da ferramenta, depois selecionar quais tipos de métricas/visualizações deseja utilizar, depois testar as escolhas e verificar sua eficácia e depois salvar as modificações. |
| **1. Acessar menu de métricas** | **Input:** Interface principal do software de análise. <br>**Plano:** Navegar através da interface do software até a seção ou menu dedicado às métricas. |
| **2. Selecionar métrica a configurar/editar**<br>1>2 | **Input:** Lista de métricas disponíveis no menu. <br>**Plano:** Navegar pela lista de métricas e selecionar a métrica desejada para configuração ou edição. |
| 2.1 Definir parâmetros | |
| 2.2 Ajustar peso da métrica no desempenho geral | |
| **3. Testar métricas no relatório de desempenho** | **Input:** Relatório de desempenho gerado com as métricas atualizadas. <br>**Feedback:** Indicação de como as métricas atualizadas afetam o relatório de desempenho. <br>**Problema:** Discrepâncias ou erros no relatório após aplicar as novas métricas. <br>**Plano:** Procedimento para gerar um relatório de teste usando as métricas atualizadas e avaliar os resultados. |
| **4. Salvar configurações** | **Input:** Todas as alterações e reajustes feitos nas métricas. <br>**Feedback:** Indicação de como as métricas atualizadas afetam o relatório de desempenho <br>**Problema:** Erros no relatório após as modificações. <br>**Plano:** Procedimento para gerar um relatório de teste usando as métricas atualizadas e avaliar os resultados. |


# GOMS (Goals, Operators, Methods, e Selection Rules)
A seguir, apresentamos o modelo GOMS para as mesmas três funcionalidades, detalhando os objetivos, operadores, métodos e regras de seleção.

## 1. Funcionalidade: Input de Logs

Este modelo GOMS detalha a funcionalidade de "Input de Logs" , decompondo os objetivos do usuário e do sistema em métodos e operadores específicos necessários para coletar (GOAL 1) , classificar (GOAL 2) e integrar os dados (GOAL 3).

- GOAL 0: Inserir e classificar os logs dos robôs para análise posterior.
- GOAL 1: Coletar logs dos sensores dos robôs.

METHOD 1.A: Sincronizar sensores com o sistema de coleta.

- OP. 1.A.1: Enviar comando de sincronização para os sensores.
- OP. 1.A.2: Aguardar confirmação de sincronização dos sensores.
- OP. 1.A.3: Verificar status de sincronização no sistema de coleta.
  
- GOAL 2: Classificar tipos de logs.

METHOD 2.A: Identificar o tipo de log.

- OP. 2.A.1: Aplicar algoritmos de identificação para a movimentação.
- OP. 2.A.2: Associar logs identificados ao tipo "Dados de movimentação".
- OP. 2.A.3: Armazenar logs classificados no banco de dados correspondente.

METHOD 2.B: (Identificar interação com a bola)

- OP. 2.B.1: Aplicar algoritmos de identificação para interação com a bola.
- OP. 2.B.2: Associar logs identificados ao tipo "Dados de interação com a bola".
- OP. 2.B.3: Armazenar logs classificados no banco de dados correspondente.

GOAL 3: Integrar logs na plataforma de análise.
- SEL. RULE: SE (Logs não estão no formato aceito pela plataforma) ENTÃO (Usar METHOD 3.A), SENÃO (Usar METHOD 3.B).
METHOD 3.A: Converter logs para o formato da plataforma.

- OP. 3.A.1: Selecionar os logs para conversão.
- OP. 3.A.2: Iniciar ferramentas de conversão.
- OP. 3.A.3: Confirmar a conversão bem-sucedida.
- OP. 3.A.4: Confirmar o upload bem-sucedido e a integração dos logs.

METHOD 3.B: Carregar logs puros na plataforma.

- OP. 3.B.1: Acessar a seção de upload da plataforma.
- OP. 3.B.2: Selecionar e carregar os logs puros.
- OP. 3.B.3: Confirmar o upload bem-sucedido e a integração dos logs.

## 2. Funcionalidade: Validação de Relatórios

Este modelo GOMS descreve a tarefa de "Validação de Relatórios". Ele detalha os objetivos e operadores para um usuário acessar um relatório (GOAL 1) , compará-lo com os dados de origem (GOAL 2) e confirmar sua precisão (GOAL 3).

- GOAL 0: Validar um relatório de desempenho de futebol de robôs.
- GOAL 1: Acessar o relatório gerado.
- SEL. RULE: SE (Usuário está logado E tem permissões para acessar relatórios) ENTÃO (Usar METHOD 1.A).

METHOD 1.A: Utilizar a interface do software de análise.

- OP. 1.A.1: Navegar até a seção de relatórios.
- OP. 1.A.2: Clicar no relatório desejado.
- OP. 1.A.3: Visualizar detalhes do relatório.

- GOAL 2: Comparar e validar os dados do relatório.
- SEL. RULE: SE (Logs originais estão disponíveis para comparação) ENTÃO (Usar METHOD 2.A).
METHOD 2.A: Comparar relatório com logs originais.

- OP. 2.A.1: Abra os logs originais.
- OP. 2.A.2: Comparar dados do log com o relatório.
- OP. 2.A.3: Identificar qualquer discrepância ou inconsistência.

- GOAL 3: Confirmar a precisão dos dados.
- SEL. RULE: SE (Não há discrepâncias identificadas na etapa anterior) ENTÃO (Usar METHOD 3.A), SENÃO (Usar METHOD 3.B).

METHOD 3.A: Verificar a precisão dos dados.

- OP. 3.A.1: Marcar o relatório como validado.
- OP. 3.A.2: Registrar quaisquer observações ou comentários necessários.
- OP. 3.A.3: Salvar o status de validação.

## 3. Funcionalidade: Configurações de Métricas

O modelo GOMS para "Configurações de Métricas" detalha os passos para um usuário acessar as configurações (GOAL 1) , editar ou adicionar uma métrica, testar seu impacto e salvar as alterações no sistema (GOAL 2).

- GOAL 0: Configurar métricas para análise de desempenho de futebol de robôs.
- GOAL 1: Acessar a seção de configurações de métricas.
- SEL. RULE: SE (Usuário está logado E tem permissões para acessar configurações) ENTÃO (Usar METHOD 1.A).

METHOD 1.A: Utilizar a interface do software de análise.

- OP. 1.A.1: Navegar até o menu ou aba de configurações.
- OP. 1.A.2: Seleccionar a opção "Configurações de métricas".
- OP. 1.A.3: Visualizar métricas atuais.

- GOAL 2: Editar ou adicionar métricas conforme necessário.
- SEL. RULE: SE (A métrica necessária não está presente) ENTÃO (Usar METHOD 2.A), SENÃO (Usar METHOD 2.B).

METHOD 2.A: Identificar métricas para edição ou adição. 

- OP. 2.A.1: Clicar no botão "Adicionar" ou "Editar" métrica.
- OP. 2.A.2: Introduzir ou modificar os parâmetros da métrica.
- OP. 2.A.3: Confirmar e salvar as alterações.

METHOD 2.B: Testar métricas recém-configuradas.
SEL. RULE: SE (Uma nova métrica foi adicionada OU uma métrica existente foi ajustada) ENTÃO (Usar METHOD 3.A).

- OP. 2.B.1: Gerar um relatório de teste com a métrica ajustada.
- OP. 2.B.2: Analisar os resultados para garantir a precisão da métrica.
- OP. 2.B.3: Ajustar a métrica conforme necessário ou confirmar as configurações.

# CTT (ConcurTaskTrees)
A seguir, apresentamos os diagramas CTT para as funcionalidades de Classificação de Times e Gerenciamento de Logs.

## 1. Funcionalidade: Classificação de Times

O diagrama CTT a seguir modela a funcionalidade de "Classificação". Ele mostra a interação concorrente entre o usuário e o sistema. O usuário pode "Solicitar os times que vão ser analisados". Concorrentemente, o sistema pode "Parametrizar classificações" e "Informar os times". O usuário então interage com a aplicação para "Escolher os times para análise" com base nos times informados.


## Diagrama CTT - Classificação:

<img width="520" height="504" alt="image" src="https://github.com/user-attachments/assets/894f8cf0-f6c3-4b4b-8607-b5b945f18643" />


## 2. Funcionalidade: Gerenciamento de Logs de Partidas

Este diagrama CTT descreve a funcionalidade de "Gerenciamento de Logs de Partidas". Ele ilustra a tarefa principal que se divide em duas tarefas concorrentes que o usuário pode realizar:

Inserção: "Seleciona qual Log quer inserir na aplicação", levando à interação "Inserir Log" e, subsequentemente, à opção "Excluir Log".

Visualização: "Seleciona qual Log quer visualizar na aplicação", o que permite ao usuário "Selecionar um log específico" ou "Visualizar a lista de logs anteriores", esta última podendo ser filtrada ("Filtrar por time" ou "Filtrar por data de partida").

## Diagrama CTT - Gerenciamento de Logs:

<img width="940" height="542" alt="image" src="https://github.com/user-attachments/assets/7bce381f-b4b7-4e55-a3af-5dd1f587c789" />
