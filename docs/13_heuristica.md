# 1) Avaliação de IHC através de inspeção HEURÍSTICA
NOTE:: SOMENTE VIOLAÇÕES

## Avaliação Heurística  

| 3. Controle e liberdade para o usuário |
| :--- |
| **Verificação:** Os usuários possuem a possibilidade de inserção de novos visuais nas páginas do relatório? |
| **Problema:** Os usuários têm a flexibilidade de criar novas páginas de visualização de acordo com suas necessidades, bem como de personalizar os relatórios para análises específicas. No entanto, é importante notar que há limites para a quantidade de itens que podem ser inseridos em cada página, o que pode impactar a distribuição de insights valiosos em diferentes seções. |
| **Grau de severidade** |
| ( ) Sem importância - 0 <br> ( X ) Cosmético - 1 <br> ( ) Simples - 2 <br> ( ) Grave - 3 <br> ( ) Catastrófico - 4 |
| <img width="639" height="413" alt="image" src="https://github.com/user-attachments/assets/34a64a32-45d0-41cd-9644-52fe2ce1cec7" /> |

| 7. Flexibilidade e eficiência de uso |
| :--- |
| **Verificação:** A flexibilidade na criação de páginas de visualização impacta diretamente na eficiência de uso do sistema, especialmente em termos de análise e personalização de relatórios? |
| **Problema:** Considerando a flexibilidade na criação de páginas de visualização, seria interessante explorar uma abordagem que atenda tanto a pessoas novatas quanto experientes. Poderíamos incorporar sugestões ou modelos predefinidos para auxiliar usuários novatos na construção inicial de suas páginas, proporcionando uma experiência mais orientada. Ao mesmo tempo, usuários experientes podem desfrutar da liberdade total de personalização. Essa estratégia visa oferecer um equilíbrio, permitindo que usuários de diferentes níveis de experiência aproveitem ao máximo a plataforma de relatórios. |
| **Grau de severidade** |
| ( ) Sem importância - 0 <br> ( ) Cosmético - 1 <br> ( X ) Simples - 2 <br> ( ) Grave - 3 <br> ( ) Catastrófico - 4 |
| <img width="639" height="417" alt="image" src="https://github.com/user-attachments/assets/36ab3153-26ba-4422-a70e-e9c272d73a1d" /> |

| 5. Prevenção de erros |
| :--- |
| **Verificação:** O sistema previne que o usuário insira dados inválidos na barra de busca? |
| **Problema:** A interface exibe uma barra de "Search" (Busca) no topo, mas não mostra nenhum mecanismo de prevenção de erros. Por exemplo, o que acontece se o usuário buscar por um time que não existe ("Time X")? O sistema não oferece *autocomplete* ou sugestões (como "FEI", "MAUÁ") para prevenir a digitação errada. Isso pode levar o usuário a um estado de erro (nenhum resultado) que poderia ser facilmente evitado. |
| **Grau de severidade** |
| ( ) Sem importância - 0 <br> ( ) Cosmético - 1 <br> ( X ) Simples - 2 <br> ( ) Grave - 3 <br> ( ) Catastrófico - 4 |
| <img width="639" height="413" alt="image" src="https://github.com/user-attachments/assets/34a64a32-45d0-41cd-9644-52fe2ce1cec7" /> |

| 9. Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros |
| :--- |
| **Verificação:** O sistema exibe mensagens de erro claras caso uma consulta não retorne dados? |
| **Problema:** Os protótipos não mostram o "estado vazio" (empty state) ou estados de erro. Se o usuário aplicar um filtro ou uma busca e não houver dados, o que é exibido? Os gráficos ficam em branco? Uma mensagem de erro aparece? A *ausência* de uma mensagem clara (ex: "Nenhum dado encontrado para 'Time X'. Tente 'FEI' ou 'USP'.") viola esta heurística, pois não ajuda o usuário a diagnosticar o problema e se recuperar. |
| **Grau de severidade** |
| ( ) Sem importância - 0 <br> ( ) Cosmético - 1 <br> ( ) Simples - 2 <br> ( X ) Grave - 3 <br> ( ) Catastrófico - 4 |
| <img width="639" height="413" alt="image" src="https://github.com/user-attachments/assets/34a64a32-45d0-41cd-9644-52fe2ce1cec7" /> |

| 10. Ajuda e documentação |
| :--- |
| **Verificação:** A interface oferece algum link de ajuda ou documentação para o usuário? |
| **Problema:** Em nenhuma das telas do protótipo existe um ícone de ajuda (como "?") ou um link de "Ajuda" ou "Documentação". Um usuário (especialmente um novo) pode ter dúvidas sobre o que a métrica "Posse de Bola X Partida - Restless / Awake" significa ou como os times são classificados (Neutro, Defensivo, Ofensivo), e não há como encontrar essa informação no sistema. |
| **Grau de severidade** |
| ( ) Sem importância - 0 <br> ( ) Cosmético - 1 <br> ( X ) Simples - 2 <br> ( ) Grave - 3 <br> ( ) Catastrófico - 4 |
| <img width="639" height="413" alt="image" src="https://github.com/user-attachments/assets/34a64a32-45d0-41cd-9644-52fe2ce1cec7" /> |

## 2) INDICAÇÃO DE BOAS PRÁTICAS DE HEURÍSTICA - HEURÍSTICAS NÃO VIOLADAS
Uso das Heurísticas  

| 8. Projeto minimalista e estético |
| :--- |
| **Verificação:** Os diálogos contém informações irrelevantes ou raramente necessárias? |
| **Exemplo de Aplicação:** Não, os diálogos e os gráficos são projetados para conter informações relevantes e necessárias. Evita-se a inclusão de detalhes desnecessários que possam sobrecarregar ou confundir os usuários. Os títulos dos gráficos são claros (ex: "Time X Meses", "Posse de Bola X Partida") e vão direto ao ponto, otimizando a comunicação e facilitando a compreensão. |

| 4. Consistência e padrões |
| :--- |
| **Verificação:** O projeto de elementos como objetos e ações têm o mesmo significado ou efeito em diferentes situações? |
| **Exemplo de Aplicação:** Sim, no contexto deste projeto, os elementos são projetados para terem o mesmo significado. As legendas de cores (FEI = Azul, MAUÁ = Vermelho, USP = Verde, SJ = Laranja/Amarelo) são mantidas de forma consistente entre os diferentes gráficos e telas do protótipo (ex: "Time X Meses" e "Desempenho geral X Times"), o que contribui para uma experiência de usuário mais intuitiva e previsível. | 

| 1. Visibilidade do status do sistema |
| :--- |
| **Verificação:** O sistema informa ao usuário o que está sendo exibido? |
| **Exemplo de Aplicação:** Sim. As legendas (ex: "Neutro", "Defensivo", "Ofensivo" e os nomes dos times "FEI", "MAUÁ", etc.) estão sempre visíveis ao lado dos gráficos. Isso informa constantemente ao usuário o *status* do que cada cor e linha significa, sem que ele precise adivinhar ou lembrar, mantendo-o informado. |

