# Análise de concorrência


## 1) Looker (Google Cloud)


- Propósito e Abordagem

O Looker, atualmente parte do Google Cloud, é uma plataforma de business intelligence (BI) que permite criar relatórios e dashboards baseados em consultas SQL. Seu foco está na modelagem centralizada de dados, garantindo consistência nas métricas e reutilização de modelos analíticos.

<img width="802" height="401" alt="image" src="https://github.com/user-attachments/assets/7b24d253-7595-4712-a404-0bb364c10a44" />


- Integração e Fontes de Dados

O Looker oferece conectividade com diversas fontes, como BigQuery, MySQL, PostgreSQL e Redshift. Sua arquitetura favorece empresas com grande volume de dados e múltiplos times de análise.

- Modelagem de Dados

A principal diferença está na abordagem centralizada: os modelos são criados uma única vez e reaproveitados por toda a organização. Isso reduz erros e promove governança, mas exige conhecimento técnico em SQL e LookML (linguagem própria do Looker).

- Facilidade de Uso e Experiência do Usuário (UX)

A interface do Looker é limpa, profissional e funcional, mas menos intuitiva para iniciantes. A experiência do usuário é voltada para analistas técnicos, não para o público geral.
Usuários relatam que a curva de aprendizado é maior, mas valorizam a estabilidade e a padronização das métricas.

- Preços e Modelo de Negócio

O Looker possui planos personalizados, baseados em escala de uso e volume de dados, o que o torna viável para grandes empresas, mas pouco acessível para projetos acadêmicos e equipes menores.

- Padrões e Tendências

O Looker segue o padrão minimalista e corporativo, priorizando consistência e governança de dados. Seu layout é responsivo e se integra bem a soluções Google, refletindo tendências modernas de design clean e foco em eficiência.


## 1.2) Tableau (Salesforce)

- Propósito e Abordagem

O Tableau, pertencente à Salesforce, é uma das ferramentas de BI mais conhecidas mundialmente, destacando-se pela qualidade visual e interatividade de seus dashboards.
O Power BI, por outro lado, oferece um ecossistema mais acessível e integrado à suíte Microsoft, o que o torna mais adequado para o ambiente acadêmico e pequenas equipes.

<img width="656" height="395" alt="image" src="https://github.com/user-attachments/assets/326690ee-6a33-46bb-a700-5d2391a1400a" />

- Integração e Fontes de Dados

O Tableau suporta integração com diversas fontes, incluindo Excel, Google Sheets, SQL Server, MySQL e Salesforce. Também é compatível com APIs externas e bancos de dados em nuvem.

- Modelagem e Visualização de Dados

O Tableau prioriza a visualização e análise exploratória, oferecendo gráficos altamente interativos e animações fluidas. Entretanto, sua modelagem é mais limitada comparada ao DAX do Power BI.

- Experiência do Usuário (UX)

A interface é considerada intuitiva, fluida e agradável, com destaque para a liberdade de criação.
Usuários afirmam que o Tableau entrega visualizações impressionantes, mas pode exigir maior esforço técnico para modelar os dados corretamente.

- Preços e Modelo de Negócio

O Tableau oferece licenças por usuário (a partir de cerca de US$ 15 a US$ 70/mês, dependendo da função e do ambiente: Creator, Explorer, Viewer).
Para fins acadêmicos, há versões educacionais gratuitas com recursos limitados.

- Padrões e Tendências

O Tableau define tendências de design orientado à visualização, com foco em interatividade, uso de cores dinâmicas e elementos gráficos modernos.
Ele reforça o conceito de storytelling com dados, tendência crescente em interfaces de BI.


## 1.3) QlikView (Qlik Technologies)

- Propósito e Abordagem

O QlikView é uma plataforma de BI com foco em análise associativa de dados, permitindo a exploração de grandes volumes de informação de forma dinâmica.
Enquanto o Power BI é mais intuitivo e visual, o QlikView oferece alto desempenho técnico, mas com complexidade maior na configuração inicial.

<img width="615" height="352" alt="image" src="https://github.com/user-attachments/assets/9ddb99f9-f395-4f6c-a121-8bcbea24e092" />

- Integração e Fontes de Dados

O QlikView suporta uma ampla variedade de fontes de dados, mas requer configurações manuais e scripts personalizados para integração. O Power BI se destaca pela facilidade de conexão com o ecossistema Microsoft e APIs externas.

- Experiência do Usuário (UX)

A interface do QlikView é funcional, mas datada, com foco na performance e não na estética.
Usuários técnicos elogiam sua velocidade e capacidade analítica, porém relatam dificuldades de uso e curva de aprendizado íngreme para novos usuários.

- Preços e Modelo de Negócio

<img width="1037" height="471" alt="image" src="https://github.com/user-attachments/assets/7859af14-9fb8-4d35-9df5-3de616321836" />

O QlikView é comercializado em planos corporativos e licenças anuais,de U$200 a U$875 sendo mais caro e menos acessível do que o Power BI.
Para projetos educacionais, sua aplicação é limitada, e o QlikSense (versão moderna) é mais indicado.

- Padrões e Tendências

O QlikView segue um padrão mais técnico e tradicional de interface, com poucos elementos visuais modernos. A tendência é de migração gradual para o QlikSense, que possui uma interface mais alinhada às práticas de UX atuais.


## Conclusão Geral da Análise de Concorrência

- Geral
Padrões e tendências analisados

As ferramentas de Business Intelligence (BI) estão cada vez mais orientadas à análise visual interativa, permitindo que usuários de diferentes níveis técnicos interpretem dados de forma intuitiva.
Há uma tendência crescente na integração com plataformas em nuvem, possibilitando colaboração em tempo real e acesso remoto a dashboards e relatórios.
Outro aspecto relevante é o uso de inteligência artificial e machine learning para gerar insights automáticos, prever tendências e sugerir métricas relevantes aos usuários.
A conectividade com múltiplas fontes de dados e a flexibilidade na modelagem são fatores fundamentais para atender diferentes necessidades organizacionais.

- Elabore relatórios e sumarize os resultados

- QlikView

- Ferramenta de Business Intelligence desenvolvida pela Qlik, com foco em análises associativas.
- Utiliza o motor de indexação QIX, que permite explorar dados de forma não linear, revelando relações ocultas entre conjuntos de dados.
- Oferece criação de dashboards interativos com visualizações dinâmicas e filtros globais.
- Instalação local (on-premise), com suporte a integração via Qlik Sense para nuvem.
- Requer modelagem de dados no script interno para combinar diferentes fontes.
- Possui controle de acesso por usuários e funções, permitindo segurança em múltiplos níveis.
- Interface mais técnica, voltada a analistas e desenvolvedores de BI.

- Tableau

- Plataforma de análise e visualização de dados com foco em simplicidade e visual design.
- Permite conexão com diversas fontes de dados locais e em nuvem, como Excel, SQL, Google Sheets e Salesforce.
- Oferece dashboards interativos com drag-and-drop, facilitando o uso por não técnicos.
- Inclui o Tableau Prep para limpeza e preparação de dados.
- Suporta recursos de análise preditiva e integração com R e Python.
- Funcionalidades de compartilhamento via Tableau Server e Tableau Online.
- Ênfase em design visual e experiência do usuário.

- Looker (Google Looker Studio)
  
- Ferramenta de BI baseada em nuvem desenvolvida pelo Google Cloud.
- Utiliza a linguagem LookML para modelagem de dados e padronização de métricas.
- Foco em governança de dados e colaboração entre equipes em tempo real.
- Totalmente baseada em navegador, com integração nativa ao BigQuery e outras soluções Google.
- Dashboards personalizáveis com visualizações modernas e interativas.
- Permite criação de relatórios dinâmicos e compartilhamento por links seguros.
- Voltado para organizações que priorizam escalabilidade e integração com o ecossistema Google.

## Recomendações

- Adotar uma arquitetura híbrida, combinando análises em nuvem e locais, para maior flexibilidade.
- Explorar o uso de automações e alertas inteligentes para monitorar indicadores em tempo real.
- Incentivar a integração com ferramentas colaborativas como Google Workspace e Microsoft Teams.
- Oferecer treinamento contínuo aos usuários para maximizar o aproveitamento das funcionalidades de BI.


## Referências

https://www.qlik.com

https://www.tableau.com

https://cloud.google.com/looker
