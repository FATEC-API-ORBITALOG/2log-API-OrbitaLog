#  MVP - OrbitaLog

## Objetivo do Projeto

Desenvolver uma plataforma interativa de análise de segurança viária no Brasil, utilizando dados de acidentes envolvendo veículos pesados, como caminhões e ônibus, para identificar pontos críticos, comparar indicadores entre as regiões do país e apoiar o planejamento de ações de fiscalização, infraestrutura e políticas públicas. A solução permitirá visualizar concentrações de sinistros, analisar a distribuição de áreas de descanso, identificar boas práticas entre estados e gerar recomendações estratégicas por meio de dashboards, mapas e relatórios técnicos.

- **Qual problema resolve?**

Resolve a dificuldade de identificar e analisar os fatores relacionados aos acidentes envolvendo veículos pesados, permitindo compreender as diferenças regionais, localizar trechos com maior concentração de sinistros e identificar necessidades de melhorias na infraestrutura viária, fiscalização e segurança no transporte de cargas.

- **Qual hipótese será validada?**

A utilização de uma plataforma interativa, integrada a indicadores, mapas e análises comparativas, permitirá que gestores públicos, autoridades de trânsito e responsáveis pela logística identifiquem regiões de maior risco, compreendam os problemas relacionados ao transporte de veículos pesados e utilizem essas informações para propor medidas mais eficientes de prevenção de acidentes e redução de mortes no trânsito.

- **Qual valor será entregue ao usuário final?**

Entrega uma visão consolidada e estratégica dos acidentes envolvendo veículos pesados no Brasil, possibilitando comparar as cinco regiões, identificar pontos críticos para fiscalização, avaliar a necessidade de novas áreas de descanso, conhecer casos de sucesso de outros estados e obter recomendações para o desenvolvimento de leis e políticas públicas. Além disso, disponibiliza relatórios técnicos, documentação do sistema e uma interface intuitiva, facilitando a interpretação dos dados e a tomada de decisões.

---

## Descrição da Solução

Desenvolver uma plataforma interativa de análise de segurança viária, com foco em acidentes envolvendo veículos pesados, como caminhões e ônibus. A solução permitirá analisar indicadores, identificar regiões e trechos críticos, comparar as cinco regiões do Brasil e apoiar decisões relacionadas à fiscalização, infraestrutura e criação de políticas públicas.

- **Funcionalidades principais incluídas:**
  - Análise da relação entre veículos pesados e acidentes de trânsito.
  - Comparação dos indicadores de segurança viária entre as cinco regiões do Brasil.
  - Mapas interativos com concentração de sinistros envolvendo veículos pesados.
  - Análise da distância entre pontos de descanso e locais de acidentes.
  - Identificação de casos de sucesso e boas práticas adotadas por outros estados.
  - Geração de recomendações para políticas públicas e propostas de leis.
  - Elaboração de relatórios técnicos consolidados.
  - Interface intuitiva e acessível para facilitar a navegação.
  - Documentação dos scripts e modelos utilizados.
  - Testes de qualidade, navegação e cálculos.
  - Material visual para apresentação dos resultados.

- **Limitações conhecidas:**
  - As análises dependem da disponibilidade e qualidade dos dados utilizados.
  - O projeto possui foco em acidentes envolvendo veículos pesados.
  - A identificação de pontos críticos está condicionada à precisão das informações geográficas disponíveis.
  - As recomendações geradas servem como apoio à tomada de decisão, não substituindo análises técnicas especializadas.
  - A abrangência das análises depende dos indicadores e informações disponíveis na base de dados.

- **Escopo reduzido (somente o essencial para validar a ideia):**
  - Desenvolver um painel com os principais indicadores de acidentes envolvendo veículos pesados.
  - Permitir a comparação dos dados entre as cinco regiões brasileiras.
  - Disponibilizar mapas para identificação dos pontos com maior concentração de sinistros.
  - Analisar a relação entre acidentes e localização de pontos de descanso.
  - Apresentar recomendações e informações estratégicas para apoiar decisões.
  - Garantir uma interface funcional, intuitiva e confiável.

---

## Personas / Usuários-Alvo

- **Persona 1: Planejador de Logística**
  - Responsável por analisar o transporte de cargas e a circulação de veículos pesados.
  - Necessidades: identificar relações entre caminhões, ônibus e acidentes, além de avaliar regiões com maior risco.
  - Dores: dificuldade em encontrar informações consolidadas para propor melhorias nas normas de transporte de cargas.

- **Persona 2: Gestor Público ou Regional**
  - Responsável por acompanhar indicadores de segurança viária e planejar melhorias na infraestrutura.
  - Necessidades: comparar indicadores entre regiões, identificar problemas estruturais e conhecer boas práticas de outros estados.
  - Dores: dificuldade em comparar dados regionais e identificar soluções eficientes para reduzir acidentes.

- **Persona 3: Comandante da Polícia Rodoviária**
  - Responsável pelo planejamento de operações e fiscalização nas rodovias.
  - Necessidades: visualizar mapas de concentração de sinistros e identificar os trechos mais perigosos.
  - Dores: dificuldade em direcionar equipes de fiscalização para os locais com maior necessidade de intervenção.

- **Persona 4: Tomador de Decisão Governamental**
  - Responsável por propor e fundamentar políticas públicas relacionadas à segurança no trânsito.
  - Necessidades: acessar informações consolidadas, relatórios e recomendações estratégicas.
  - Dores: falta de informações organizadas que auxiliem na elaboração de leis e políticas de prevenção de acidentes.

---

##  User Stories (Backlog do MVP)
| Rank | Prioridade | User Story | Estimativa | Sprint |
|---:|---|---|---:|---:|
| 13 | Alta | Como planejador de logística, quero analisar a relação entre a frota pesada (caminhões/ônibus) e os acidentes, para que possamos propor normas específicas para o transporte de cargas. | 8 | 3 |
| 14 | Média | Como gestor regional, quero comparar os indicadores das 5 regiões do Brasil, para que possamos entender as desigualdades regionais em infraestrutura viária. | 5 | 3 |
| 15 | Alta | Como Comandante da Polícia Rodoviária, quero visualizar um mapa de concentração de sinistros com veículos pesados, para que eu posicione equipes de fiscalização nos pontos mais perigosos. | 8 | 3 |
| 16 | Média | Como gestor de infraestrutura, quero analisar a distância entre pontos de descanso e a localização dos sinistros, para que possamos criar novas áreas de descanso onde os motoristas mais precisam. | 8 | 3 |
| 17 | Média | Como gestor público, quero acessar um painel com casos de sucesso de outros estados, para que eu possa replicar boas práticas que reduziram mortes no trânsito. | 8 | 3 |
| 18 | Alta | Como tomador de decisão governamental, quero transformar os problemas encontrados em recomendações diretas, para que possamos fundamentar novas propostas de leis e políticas públicas. | 5 | 3 |
| 19 | Alta | Como diretor de órgão público, quero um relatório técnico consolidado, para que possamos apresentar resultados oficiais à sociedade e órgãos reguladores. | 8 | 3 |
| 20 | Média | Como responsável pelo sistema, quero ter uma documentação final completa dos scripts e modelos, para que qualquer novo profissional consiga dar manutenção no sistema no futuro. | 5 | 3 |
| 21 | Alta | Como analista de qualidade, quero realizar testes completos de navegação e cálculos, para que o público receba uma plataforma confiável e livre de erros. | 5 | 3 |
| 22 | Média | Como usuário da plataforma, quero navegar em uma interface limpa, moderna e acessível, para que a leitura dos gráficos e a navegação sejam simples e intuitivas. | 5 | 3 |
| 23 | Alta | Como porta-voz do projeto, quero ter um material visual de apresentação pronto, para que eu possa expor os resultados para a imprensa, investidores ou lideranças. | 5 | 3 |
---

| Sprint | Entregas Principais | Status |
|---|---|---|
| 01 | Limpeza, validação e padronização dos dados de segurança viária. | Concluído |
| 02 | Estruturação dos relacionamentos entre tabelas e criação do modelo de dados no Power BI. | Em andamento |
| 03 | Desenvolvimento dos indicadores nacionais de segurança viária e construção da visão geral dos dados. | Planejado |
| 04 | Criação do mapa interativo para visualização dos indicadores por estado. | Planejado |
| 05 | Implementação do ranking de mortalidade e dos filtros por estado, região e ano. | Planejado |
| 06 | Comparação entre estados e regiões, validação dos indicadores e testes de usabilidade. | Planejado |
| 07 | Validação, limpeza e padronização dos dados de segurança viária. | Concluído |
| 08 | Estruturação dos relacionamentos entre tabelas e criação do modelo de dados no Power BI. | Concluído |
| 09 | Desenvolvimento dos indicadores nacionais e criação do mapa interativo por estado. | Concluído |
| 10 | Implementação do ranking de mortalidade e dos filtros por estado, região e ano. | Concluído |
| 11 | Comparação entre estados e regiões, validação dos indicadores e testes de usabilidade. | Concluído |
| 12 | Comparação entre estados, validação dos indicadores e testes de usabilidade. | Concluído |
---
## Critérios de Aceitação

- O dashboard deve permitir analisar a relação entre veículos pesados e acidentes.
- O sistema deve apresentar comparações entre as cinco regiões do Brasil.
- O mapa deve permitir identificar pontos de concentração de sinistros envolvendo veículos pesados.
- A análise deve possibilitar relacionar a localização dos sinistros com os pontos de descanso.
- O projeto deve apresentar exemplos de boas práticas adotadas por outros estados.
- Os resultados devem permitir elaborar recomendações para políticas públicas e melhorias na segurança viária.
- O projeto deve possuir um relatório técnico consolidado e documentação dos scripts e modelos.
- A plataforma deve funcionar corretamente, sem erros nos cálculos e na navegação.
- A interface deve ser organizada, acessível e intuitiva.
- O material de apresentação deve reunir os principais resultados do projeto.

---

## Métricas de Validação

- **Número de usuários que testaram o MVP:** 6 pessoas.
- **Feedback qualitativo:** Positivo.
- **Indicadores de negócio:**
  - **Usabilidade:** avaliação positiva dos usuários durante os testes.
  - **Facilidade de navegação:** capacidade de acessar e consultar os indicadores no dashboard.
  - **Identificação de regiões críticas:** possibilidade de visualizar áreas com maiores índices de acidentes e mortalidade.
  - **Eficiência na análise:** facilidade de comparar indicadores entre estados e regiões.
  - **Confiabilidade:** funcionamento dos gráficos, filtros e cálculos apresentados na plataforma.

---

## Próximos Passos

- **Finalização do projeto:** consolidar as funcionalidades desenvolvidas e garantir que os requisitos definidos tenham sido atendidos.
- **Documentação final:** organizar a documentação dos scripts, modelos de dados, indicadores e funcionalidades do dashboard.
- **Apresentação dos resultados:** utilizar o relatório técnico e o material visual para apresentar os resultados alcançados pelo OrbitaLog.
- **Disponibilização do dashboard:** disponibilizar a ferramenta para consulta dos indicadores de segurança viária.
- **Manutenção e atualização:** realizar atualizações periódicas dos dados e corrigir possíveis erros identificados durante o uso.
- **Evolução futura:** avaliar novas funcionalidades e melhorias que possam ser implementadas futuramente, conforme as necessidades dos usuários.
---

##  Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
