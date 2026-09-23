# ORBITALOG  

# Índice
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Equipe](#Equipe)
* [Backlog do produto](#Product-Backlog)
* [Competências desenvolvidas](#competências-desenvolvidas)
* [Registro das Sprints](#Registro-das-Sprints)


Projeto (API) Projeto de análise da segurança viária alicerçado em dados oficiais de frota, população, sinistros e mortes, organizados entre 2015 e 2025. Uso de Python para tratamento e padronização dos dados e Power BI para integração, análise e visualização dos indicadores, permitindo avaliar a relação entre frota e fatalidades no trânsito.

# Equipe
|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner |   Nicolly de Araújo Silva         |     [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)              |
| Scrum Master  | João Felipe Góes de Oliveira |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)     |
| Team Member   | Inaê Taís da Rosa Silva             |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)        |
|  Team Member  | Fernanda Fernandes Caldi Palma               |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)        |
|  Team Member  | Manuela Maria Magalhães Mendes             |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)   |
|  Team Member  | Isabella Carvalho Leite      |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/)    


# Objetivo do Projeto
Este projeto tem como objetivo ajudar e facilitar na utilização da plataforma GitHub, visando:
* Centralizar os trabalhos e projetos;
* Organizar e estruturar as informações;
* Versionar e controlar as alterações;
* Facilitar o compartilhamento e feedback;
* Desenvolver habilidades técnicas.


## Tecnologias Utilizadas

* Jira Software
* Power BI
* Microsoft Excel
* Python (Colab)


# Product Backlog

| Rank | Prioridade | User Story | Estimativa | Sprint |
|---:|---|---|---:|---:|
| 1 | Alta | Como auditor de dados, quero aplicar procedimentos de limpeza em Python, para que inconsistências e dados nulos não distorçam os indicadores finais de mortalidade. | 8 | 1 |
| 2 | Alta |Como gestor de trânsito, quero identificar e selecionar dados oficiais de frota, população, mortes e sinistros, para apoiar decisões estratégicas de segurança viária. | 5 | 1 |
| 3 | Alta | Como analista de políticas públicas, quero organizar os dados de 2015 a 2025 por estado e ano, para apoiar a definição de políticas públicas mais eficientes para a segurança viária. | 8 | 1 |
| 4 | Alta | Como analista de negócios, quero padronizar nomes de estados e categorias, para que possamos cruzar informações de diferentes órgãos sem falhas de divergência. | 5 | 1 |
| 5 | Alta | Como pesquisador de mobilidade, quero integrar dados de frota, população, acidentes e mortes em um único ambiente, para que eu possa avaliar o impacto real do tamanho da frota nas fatalidades. | 20 | 1 |
| 6 | Alta | Como projetista de BI, quero criar a estrutura de relacionamento entre as tabelas no Power BI, para que os relatórios carreguem de forma rápida e fluida para os usuários. | 8 | 2 |
| 7 | Alta | Como gestor de trânsito, quero visualizar indicadores básicos de mortes, sinistros e frota, para que eu tenha uma medição imediata da situação geral do país. | 5 | 1 |
| 9 | Alta |Como gestor público, quero ter uma visão geral nacional dos indicadores, para obter uma compreensão rápida e consolidada da situação da segurança viária, apoiando a tomada de decisões estratégicas| 8 | 2 |
| 10 | Alta | Como fiscal de trânsito, quero visualizar os dados através de um mapa interativo por estado, para que eu consiga identificar geograficamente as regiões com maior número de acidentes. | 8 | 2 |
| 11 | Alta |Como Secretário de Mobilidade, quero acessar o ranking dos estados com maiores índices de mortalidade, para comparar o cenário entre as diferentes regiões e identificar onde as ações de segurança viária precisam ser acompanhadas com maior atenção. | 5 | 2 |
| 13 | Alta | Como cidadão, quero aplicar filtros por estado, região e ano, para que eu consiga consultar a situação da segurança viária na minha própria região. | 5 | 2 |
| 14 | Média | Como gestor estadual, quero comparar os indicadores do meu estado com os de outros estados vizinhos, para que eu entenda o nosso desempenho relativo de segurança. | 5 | 2 |
| 16 | Alta | Como planejador de logística, quero analisar a relação entre a frota pesada (caminhões/ônibus) e os acidentes, para que possamos propor normas específicas para o transporte de cargas. | 8 | 3 |
| 17 | Média | Como gestor regional, quero comparar os indicadores das 5 regiões do Brasil, para que possamos entender as desigualdades regionais em infraestrutura viária. | 5 | 3 |
| 18 | Alta | Como Comandante da Polícia Rodoviária, quero visualizar um mapa de concentração de sinistros com veículos pesados, para que eu posicione equipes de fiscalização nos pontos mais perigosos. | 8 | 3 |
| 19 | Média | Como gestor de infraestrutura, quero analisar a distância entre pontos de descanso e a localização dos sinistros, para que possamos criar novas áreas de descanso onde os motoristas mais precisam. | 8 | 3 |
| 20 | Média | Como gestor público, quero acessar um painel com casos de sucesso de outros estados, para que eu possa replicar boas práticas que reduziram mortes no trânsito. | 8 | 3 |
| 21 | Alta | Como tomador de decisão governamental, quero transformar os problemas encontrados em recomendações diretas, para que possamos fundamentar novas propostas de leis e políticas públicas. | 5 | 3 |
| 22 | Alta | Como diretor de órgão público, quero um relatório técnico consolidado, para que possamos apresentar resultados oficiais à sociedade e órgãos reguladores. | 8 | 3 |
| 23 | Média | Como responsável pelo sistema, quero ter uma documentação final completa dos scripts e modelos, para que qualquer novo profissional consiga dar manutenção no sistema no futuro. | 5 | 3 |
| 24 | Alta | Como analista de qualidade, quero realizar testes completos de navegação e cálculos, para que o público receba uma plataforma confiável e livre de erros. | 5 | 3 |
| 25 | Média | Como usuário da plataforma, quero navegar em uma interface limpa, moderna e acessível, para que a leitura dos gráficos e a navegação sejam simples e intuitivas. | 5 | 3 |
| 26 | Alta | Como porta-voz do projeto, quero ter um material visual de apresentação pronto, para que eu possa expor os resultados para a imprensa, investidores ou lideranças. | 5 | 3 |






  
# Registro das Sprints

| Sprint            | Previsão   |  Status   | Histórico |
|-------------------|------------|-----------|-----------|
| 01                | 30/09/2026 | concluída | [MVP](MVP/sp1.md)  |
| 02                | dd/mm/aaaa | a fazer   | [MVP](MVP/sp2.md)  |
| 03                | dd/mm/aaaa | a fazer   | [MVP](MVP/sp3.md)  |
| Feira de Soluções | 03/12/2026 | a fazer   | [MVP](#)  |

