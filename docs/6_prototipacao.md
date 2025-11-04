# Prototipação em Papel

## Jornada do Usuário 01 – Desenvolvedor/Analista "Matheus Oliveira" [Conhecimentos Avançados - Análise de Dados]

Persona: Matheus Oliveira, 21 anos, desenvolvedor do time de Futebol de Robôs da FEI.

Contexto: Está no laboratório se preparando para o Campeonato Nacional de Futebol de Robôs  e precisa analisar o desempenho recente da própria equipe e de um adversário.

1. Acesso → O usuário (Matheus) abre o software de análise (Dashboard) em seu notebook.

2. Visualização Geral (Home) → A tela inicial (protótipo ) exibe o dashboard "Desempenho Time", mostrando gráficos como "Time X Meses" e "Desempenho geral X Times" (FEI, MAUÁ, USP, SJ).

3. Seleção de Tarefa (Análise) → O usuário decide "Verificar classificação de times".

4. Interação (Filtros) → O usuário interage com os filtros do dashboard  (similares aos do Power BI) para "Solicitar dados dos times". Ele seleciona "Time: FEI" e "Período: Últimos 3 meses".

5. Execução (Sistema) → O sistema consulta a máquina para "Classificar times" com base nos logs e métricas configurados.

6. Feedback Visual → O gráfico "Time X Meses"  é atualizado, mostrando a classificação da FEI (Neutro, Defensivo, Ofensivo) no período. Matheus percebe que o time está classificado majoritariamente como "Defensivo".

7. Ações pós-feedback → O usuário (Matheus) salva a visualização atual ("Gerar relatório" ) e a envia para o técnico (Carlos), sugerindo uma mudança tática para uma postura mais ofensiva.

8. Registro → Os filtros aplicados são mantidos para uma próxima consulta rápida.

   <img width="893" height="577" alt="image" src="https://github.com/user-attachments/assets/58524d68-b793-4a10-982c-1b6520ac68ad" />



## Jornada do Usuário 02 – Técnico "Carlos" [Conhecimentos Avançados - Estratégia e IA]

Persona: Carlos, 46 anos, técnico do time Robocup FEI.

Contexto: Após receber a análise de Matheus (Jornada 01), Carlos decide que precisa ajustar o modelo de análise para valorizar mais as ações ofensivas.

1. Acesso → O usuário (Carlos) abre o software no PC do laboratório.

2. Login → Acessa com seu perfil de "Técnico/Admin", que possui permissões para "Configurações de métricas".

3. Navegação (Menu) → Na barra lateral (conforme protótipo ), o usuário ignora os dashboards de visualização e clica no ícone "Configurações".

4. Seleção de Tarefa → O usuário seleciona a opção "Acessar menu de métricas".

5. Execução (Edição) → Na lista de métricas, ele seleciona "Ajustar peso da métrica no desempenho geral".

6. Ajuste de Parâmetros → O usuário localiza a métrica "Posse de Bola X Partida" e "Chutes ao gol"  e aumenta o peso delas na classificação "Ofensivo".

7. Feedback (Validação) → Carlos observa que, no relatório de teste, a classificação da FEI nos últimos 3 meses agora aparece mais equilibrada entre "Ofensivo" e "Neutro". Ele considera o teste um sucesso.

8. Ações pós-feedback → O usuário clica em "Salvar configurações".

10. Registro → O sistema armazena as novas configurações. Todas as análises futuras (incluindo as de Matheus) utilizarão esses novos pesos para classificar os times.

<img width="874" height="571" alt="image" src="https://github.com/user-attachments/assets/c5ada444-6bfa-4281-83cc-6d4c62026330" />


