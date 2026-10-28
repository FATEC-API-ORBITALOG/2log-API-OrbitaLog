#  MVP - OrbitaLog

##  Objetivo do MVP

Desenvolver um dashboard no Power BI para analisar os indicadores de segurança viária no Brasil, permitindo visualizar acidentes, comparar índices de mortalidade e identificar regiões críticas por meio de gráficos, mapas e filtros interativos.

- **Qual problema resolve?**

Resolve a dificuldade de centralizar e visualizar os indicadores de segurança viária, reduzindo o tempo necessário para identificar estados e regiões com maior número de acidentes e facilitando a comparação dos indicadores entre estados e períodos.

- **Qual hipótese será validada?**

A utilização de um dashboard interativo permitirá que gestores públicos, fiscais de trânsito e cidadãos consultem os indicadores de segurança viária de forma mais rápida, facilitando a identificação de regiões críticas e apoiando a tomada de decisões.

- **Qual valor será entregue ao usuário final?**

Entrega uma visão consolidada dos indicadores nacionais, permitindo identificar regiões críticas, comparar estados e regiões e consultar informações por localização e período, apoiando a tomada de decisões estratégicas.

---

##  Descrição da Solução
Desenvolvimento de um dashboard no Power BI para visualização e análise dos indicadores de segurança viária, utilizando tabelas relacionadas, medidas e visualizações interativas.

- **Funcionalidades principais incluídas**
- 
  - Visão geral dos indicadores nacionais de segurança viária.
  - Mapa interativo de acidentes por estado.
  - Filtros por estado, região e ano.
  - Gráficos, tabelas e cartões de indicadores.
 
- **Limitações conhecidas**
  
  - Dependência da qualidade e disponibilidade dos dados.
  - Indicadores limitados às informações existentes na base.
  - Atualização condicionada ao processo de carga dos dados.

- **Escopo reduzido**

  O MVP contemplará somente as funcionalidades essenciais para validar a solução:

  - Modelo de dados e relacionamentos.
  - Indicadores nacionais e estaduais.
  - Mapa interativo.
  - Soma de mortalidade.
  - Filtros geográficos e temporais.
  - Comparação entre estados.

---

##  Personas / Usuários-Alvo

- **Persona 1 (Projetista de BI):** profissional responsável por desenvolver a estrutura de dados no Power BI. Precisa organizar os relacionamentos entre as tabelas para garantir que os relatórios carreguem de forma rápida e fluida. Sua dor é a dificuldade de integrar os dados de maneira eficiente e manter o bom desempenho das visualizações.

- **Persona 2 (Gestor público):** responsável por acompanhar os indicadores de segurança viária. Precisa de uma visão geral dos indicadores nacionais para compreender rapidamente a situação do país e apoiar a tomada de decisões estratégicas. Sua dor é a dificuldade de obter uma visão consolidada e confiável dos dados.

- **Persona 3 (Fiscal de trânsito):** profissional que acompanha a ocorrência de acidentes nas diferentes regiões. Precisa visualizar os dados em um mapa interativo por estado para identificar geograficamente as regiões com maior número de acidentes. Sua dor é a dificuldade de localizar áreas críticas e priorizar ações de fiscalização.

- **Persona 4 (Secretário de Mobilidade):** responsável por planejar e acompanhar políticas de segurança viária. Precisa consultar o ranking dos estados com maiores índices de mortalidade para comparar as regiões e identificar onde as ações devem receber maior atenção. Sua dor é a dificuldade de avaliar diferenças regionais e definir prioridades.

- **Persona 5 (Cidadão):** pessoa interessada em conhecer a situação da segurança viária em sua região. Precisa aplicar filtros por estado, região e ano para consultar os indicadores de sua localidade. Sua dor é a dificuldade de encontrar informações específicas e compreender a realidade local.

- **Persona 6 (Gestor estadual):** responsável por acompanhar os indicadores de segurança viária de seu estado. Precisa comparar os resultados com os de outros estados para compreender o desempenho regional. Sua dor é a dificuldade de identificar diferenças entre localidades e avaliar oportunidades de melhoria.

---

##  User Stories (Backlog do MVP)
| Rank | Prioridade | User Story | Estimativa | Sprint |
|---:|---|---|---:|---:|
7	|Alta|	Como projetista de BI, quero criar a estrutura de relacionamento entre as tabelas no Power BI, para que os relatórios carreguem de forma rápida e fluida para os usuários.	|8|	2|
8|	Alta|	Como gestor público, quero ter uma visão geral nacional dos indicadores, para obter uma compreensão rápida e consolidada da situação da segurança viária, apoiando a tomada de decisões estratégicas	|8	|2|
9|	Alta|	Como fiscal de trânsito, quero visualizar os dados através de um mapa interativo por estado, para que eu consiga identificar geograficamente as regiões com maior número de acidentes.	|8	|2|
10|	Alta|	Como Secretário de Mobilidade, quero acessar o ranking dos estados com maiores índices de mortalidade, para comparar o cenário entre as diferentes regiões e identificar onde as ações de segurança viária precisam ser acompanhadas com maior atenção.	|5|	2|
11|	Alta|	Como cidadão, quero aplicar filtros por estado, região e ano, para que eu consiga consultar a situação da segurança viária na minha própria região.	|5	|2|
12|	Média|	Como gestor estadual, quero comparar os indicadores do meu estado com os de outros estados vizinhos, para que eu entenda o nosso desempenho relativo de segurança.|	5	|2|
---

##  Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 07     |Validação, limpeza e padronização dos dados de segurança viária.| Concluído|
| 08     |Estruturação dos relacionamentos entre tabelas e criação do modelo de dados no Power BI.  | Concluído|
| 09     |Desenvolvimento dos indicadores nacionais e criação do mapa interativo por estado.           | Concluído|
| 10     | Implementação do ranking de mortalidade e dos filtros por estado, região e ano.             | Concluído|
| 11    | Comparação entre estados e regiões, validação dos indicadores e testes de usabilidade.                  | Concluído|
| 12    | Comparação entre estados, validação dos indicadores e testes de usabilidade. | Concluído|

---

## Critérios de Aceitação

- O dashboard deve apresentar os principais indicadores nacionais de segurança viária.
- As tabelas devem possuir relacionamentos consistentes no Power BI.
- O usuário deve conseguir visualizar os dados em um mapa interativo por estado.
- Os filtros por estado, região e ano devem funcionar corretamente.
- Os gráficos e indicadores devem responder aos filtros selecionados.
- O usuário deve conseguir comparar os indicadores entre estados e regiões.
- Os valores apresentados devem corresponder aos dados da fonte utilizada.
- As páginas e visualizações devem funcionar sem erros.
- O carregamento e a aplicação dos filtros devem ocorrer de forma fluida.
 

---

##  Métricas de Validação
- **Número de usuários que testaram o MVP:** 6 pessoas.
- **Feedback qualitativo:** Positivo.
- **Indicadores de negócio:**
  - **Usabilidade:** avaliação positiva dos usuários durante os testes.
  - **Facilidade de navegação:** capacidade de consultar os indicadores no dashboard.
  - **Identificação de regiões críticas:** possibilidade de visualizar áreas com maiores índices de acidentes e mortalidade.
  - **Eficiência na análise:** facilidade de comparar os indicadores de segurança viária.

---

##  Próximos Passos
- Desenvolver análises da relação entre frota de veículos pesados e acidentes.
- Comparar os indicadores de segurança viária entre as cinco regiões do Brasil.
- Criar mapas de concentração de sinistros envolvendo veículos pesados.
- Analisar a localização dos acidentes em relação aos pontos de descanso.
- Identificar boas práticas de outros estados para reduzir mortes no trânsito.
- Gerar recomendações para políticas públicas com base nos indicadores.
- Elaborar relatórios técnicos com os principais resultados.
- Documentar os scripts, modelos e processos utilizados no projeto.
- Realizar testes de navegação, cálculos e confiabilidade do dashboard.
- Melhorar a acessibilidade, a navegação e a apresentação dos gráficos.
- Preparar material visual para apresentar os resultados do projeto.

---

##  Anexos / Evidências


https://github.com/user-attachments/assets/039c4c77-806e-489e-b6d5-086bffcb5559

<img width="871" height="489" alt="image" src="https://github.com/user-attachments/assets/5332527a-9a8d-4d0c-9586-347503a766e1" />


Para âmbitos de estudos, comparações com o Power BI e análise da ferramenta, utilizamos a plataforma Base44 para a criação de um Dashboard baseado no backlog da segunda sprint, contendo as informações de sinistros do ano de 2020.


https://github.com/user-attachments/assets/51d5f01b-d230-47c4-a3ab-fc9fa0fbc9dc

<img width="1133" height="296" alt="WhatsApp Image 2026-10-28 at 19 38 06" src="https://github.com/user-attachments/assets/0c18f0c6-c580-4450-b280-3140e95af05d" />

<img width="631" height="212" alt="WhatsApp Image 2026-10-28 at 19 34 55" src="https://github.com/user-attachments/assets/e8c70995-84b2-499e-87a8-001dc1b3117f" />

<img width="1145" height="328" alt="WhatsApp Image 2026-10-28 at 19 38 06 (1)" src="https://github.com/user-attachments/assets/716ac635-0c89-4a57-84f4-d124200d75a1" />




