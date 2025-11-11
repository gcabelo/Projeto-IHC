
## 1) **Fluxograma de Avaliação de Usabilidade por Observação do Usuário**
   
![Molics-Página-2](https://github.com/user-attachments/assets/7c9bf194-dee1-49ba-a7be-d3de4ea6b5ba)


## 2) DESCRIÇÃO DO PROCEDIMENTO DE PREPARAÇÃO DO TESTE 

Passo 1: Definição dos Objetivos do Teste: O objetivo principal é avaliar a eficácia do protótipo com um usuário leigo (nível 0 de experiência em análise de dados). Queremos identificar:

- Se a interface é intuitiva e se os gráficos são fáceis de entender à primeira vista.
- Se o usuário consegue realizar tarefas básicas (como usar filtros).
- Se o usuário entende como realizar tarefas complexas (como inserir dados ou criar novas análises).

 Passo 2: Lista de tarefas que o usuário deve cumprir Baseado nos "Objetivos do Usuário" definidos no roteiro , as seguintes tarefas foram apresentadas:

- Tarefa 1 (Entendimento): "Observe os gráficos na tela e descreva o que você entende de cada um."
- Tarefa 2 (Interação Simples): "Tente usar os filtros para iniciar uma análise." (Ex: filtrar por data ou time).
- Tarefa 3 (Interação Complexa): "Tente iniciar o processo de inserção de novos dados ou de criação de uma nova análise."

Passo 3: Formulário de perfil do usuário (Questionário Pré-Teste) O seguinte formulário (baseado na "Estrutura de Informações do Usuário" ) foi aplicado:

- Qual o seu nome?
- Qual sua idade?
- Qual seu trabalho no momento?
- Qual seu nível de formação?
- De 1 a 10, qual seu nível de experiência com Data Analysis?
- De 1 a 10, qual sua frequência em utilizar apps para análise de dados?
- De 1 a 10, quão importante para você é um analisador de dados para futebol de robôs?

Passo 4: Formulário de Feedback (Questionário Pós-Teste) O seguinte roteiro (baseado na "Estrutura de Feedback do Usuário" ) foi aplicado após a interação:

- Passou por alguma dificuldade ao interagir com algum componente de interface específico?
- Qual o nível de dificuldade de interação que você considera que a interface possui?
- Existe alguma informação que você sentiu falta durante a interação?

## 3) RESULTADOS DO TESTE

| Tarefa | Grau de Sucesso | Total de Erros cometidos | Tipos de Erros | Tempo Necessário | Grau de Satisfação |
| ----- | ----- | ----- | ----- | ----- | ----- |
| **1: Entender os gráficos** | **Sucesso com Assistência** | 1 | (1) Necessitou de auxílio/explicação do desenvolvedor para confirmar o entendimento. | (Não cronometrado) | **Alto** ("muito fácil de manusear e entender")  |
| **2: Usar os filtros** | **Sucesso** | 0 | - | (Não cronometrado) | **Alto** ("não tive dificuldades, pois só precisei utilizar os filtros")  |
| **3: Criar novas análises** | **Falha** | 1 | (1) Tarefa não realizada. Usuária expressou que "teria dificuldades" e "precisaria de possível auxílio". | N/A | **Baixo / Confusão** |

Links dos vídeos:

Vídeo Usuário 1 (Luciana): https://youtu.be/GB2YBnmKz7s

Respostas do Formulário do Usuário:<br>
Usuário 1: Luciana Zoia Jacomino 

- Nome: Luciana Zoia Jacomino
- Idade: 48 anos
- Trabalho: Do Lar
- Formação: Superior Incompleto
- Experiência com Data Analysis: 0
- Frequência de uso de apps de dados: 0
- Importância de apps para futebol de robôs: 0


**Conclusão da avaliação por observação do usuário:**

A avaliação com a Usuária 1, que representa um perfil totalmente leigo (nível 0 de experiência), foi extremamente valiosa.<br>
Os resultados mostram que o protótipo tem sucesso em sua função de Relatório de Visualização. A usuária achou a interface "muito fácil de manusear e entender" e conseguiu usar funções básicas de interação (filtros) sem dificuldades.<br>
No entanto, o teste revelou uma falha crítica na função de Ferramenta de Criação. A usuária não conseguiu realizar a Tarefa 3 ("criar novas análises" ou "inserir novos dados"). Ela afirmou que "teria dificuldades" e "precisaria de possível auxílio". Isso indica que a interface não oferece affordance (pistas visuais) ou um ponto de partida claro para que um usuário, especialmente um novato, inicie uma tarefa complexa. <br>
A recomendação principal é focar na Heurística de Reconhecimento em lugar de Lembrança e Flexibilidade e Eficiência de Uso, adicionando botões claros (ex: "Adicionar Análise", "Inserir Log") e guias visuais para o processo de criação de novos relatórios.
