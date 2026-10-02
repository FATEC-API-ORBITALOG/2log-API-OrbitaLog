#  MVP - OrbitaLog

##  Objetivo do MVP

O propósito deste MVP é consolidar, limpar e disponibilizar dados históricos (2015–2025) de sinistros, fatalidades, frota e população em um ambiente analítico unificado, permitindo a visualização rápida da situação da segurança viária no país.

- **Qual problema resolve?**  
  Resolve a dispersão, inconsistência e divergência de padrões entre bases de dados de diferentes órgãos oficiais, eliminando o esforço manual e o risco de análises enviesadas por dados nulos ou despadronizados.

- **Qual hipótese será validada?**  
  A centralização e padronização dos dados de frota, acidentes e mortalidade em um pipeline limpo permitem identificar correlações diretas entre o crescimento da frota e os índices de fatalidade, acelerando o diagnóstico situacional do país.

- **Qual valor será entregue ao usuário final?**  
  Entrega aos gestores de trânsito, pesquisadores e analistas de políticas públicas uma visão integrada, confiável e imediata dos principais indicadores viários por estado e ano, fundamentando decisões estratégicas e formulação de políticas públicas mais eficazes.
  

---

## Descrição da Solução

- **Funcionalidades principais incluídas**
  - Ingestão e limpeza dos dados oficiais em Python (tratamento de valores nulos e inconsistências).
  - Padronização de nomes de estados e categorias para permitir o cruzamento entre órgãos.
  - Organização dos dados de 2015 a 2025 por estado e por ano.
  - Ambiente único que integra frota, população, acidentes e mortes.
  - Painel de indicadores básicos de mortes, sinistros e frota.

- **Limitações conhecidas**
  - Qualidade e formato heterogêneo das bases de origem limitam a automação total da limpeza.
  - Dados podem ter defasagem de publicação e incompletude em anos recentes.
  - Não há, nesta etapa, integração automática com as APIs dos órgãos.
  - Indicadores dependem da padronização prévia; divergências remanescentes geram ressalvas.

- **Escopo reduzido (somente o essencial para validar a ideia)**
  - Uma base consolidada e limpa, um conjunto de indicadores básicos e uma visualização simples.
  - Sem modelagem preditiva, sem alertas em tempo real e sem controle de acesso por perfil.

---

## Personas / Usuários-Alvo

- **Persona 1 (Auditor de dados / Analista de negócios):** profissional responsável por garantir a consistência das bases. Precisa de rotinas de limpeza reprodutíveis e de uma padronização de nomes de estados e categorias. Suas dores são inconsistências e dados nulos que distorcem os indicadores e falhas de divergência no cruzamento entre órgãos.

- **Persona 2 (Gestor de trânsito):** tomador de decisão em segurança viária. Precisa visualizar indicadores básicos de mortes, sinistros e frota e selecionar dados oficiais de frota, população, mortes e sinistros. Sua dor é a falta de uma medição imediata e confiável da situação geral do país para decisões estratégicas.

- **Persona 3 (Analista de políticas públicas):** formulador de políticas. Precisa dos dados organizados de 2015 a 2025 por estado e ano. Sua dor é não conseguir comparar séries históricas para definir políticas mais eficientes.

- **Persona 4 (Pesquisador de mobilidade):** estudioso do impacto do trânsito. Precisa cruzar frota, população, acidentes e mortes em um único ambiente. Sua dor é não conseguir avaliar o impacto real do tamanho da frota sobre as fatalidades.

---

##  User Stories (Backlog do MVP)
| Rank | Prioridade | User Story | Estimativa | Sprint |
|---:|---|---|---:|---:|
| 1 | Alta | Como auditor de dados, quero aplicar procedimentos de limpeza em Python, para que inconsistências e dados nulos não distorçam os indicadores finais de mortalidade. | 8 | 1 |
| 2 | Alta |Como gestor de trânsito, quero identificar e selecionar dados oficiais de frota, população, mortes e sinistros, para apoiar decisões estratégicas de segurança viária. | 5 | 1 |
| 3 | Alta | Como analista de políticas públicas, quero organizar os dados de 2015 a 2025 por estado e ano, para apoiar a definição de políticas públicas mais eficientes para a segurança viária. | 8 | 1 |
| 4 | Alta | Como analista de negócios, quero padronizar nomes de estados e categorias, para que possamos cruzar informações de diferentes órgãos sem falhas de divergência. | 5 | 1 |
| 5 | Alta | Como pesquisador de mobilidade, quero integrar dados de frota, população, acidentes e mortes em um único ambiente, para que eu possa avaliar o impacto real do tamanho da frota nas fatalidades. | 20 | 1 |
| 6 | Alta | Como gestor de trânsito, quero visualizar indicadores básicos de mortes, sinistros e frota, para que eu tenha uma medição imediata da situação geral do país. | 5 | 1 |
---

##  Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | [Funcionalidade X, Y]                        | Concluído|
| 02     | [Funcionalidade Z]                           | Em andamento |

---

## Critérios de Aceitação

## Critérios de Aceitação

- A base de dados deve estar **limpa**: sem inconsistências, sem dados nulos e sem divergências de nomenclatura de estados e categorias.
- As próximas sprints devem funcionar **a partir dessa base limpa**, consumindo-a como fonte única de dados já tratados.
- 
---

##  Métricas de Validação
| Número de usuários que testaram o MVP| Feedback qualitativo |                                                            Indicadores de negócio                                                                       | 
|--------------------------------------|-------------- -------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
                                                              |**Taxa de aproveitamento dos dados:** percentual de registros válidos após a limpeza, sobre o total ingerido das bases oficiais.                         |
                                                              |**Redução de inconsistências:** quantidade de inconsistências, nulos e divergências de nomenclatura eliminadas em cada base de origem.                  |
                                                              |**Cobertura temporal e geográfica:** percentual de estados e de anos (2015–2025) com dados completos e padronizados na base final.                       |
                                                              |**Reuso da base pelas sprints seguintes:** quantidade de sprints e de análises que consomem a base limpa como fonte única, sem retrabalho de tratamento. |

---

##  Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
