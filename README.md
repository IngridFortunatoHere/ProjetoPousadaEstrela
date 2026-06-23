# 🌟 Análise de Dados da Pousada Estrela — Maragogi/AL

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de aplicar conceitos de **Análise de Dados** em um cenário inspirado na realidade do turismo de **Maragogi, Alagoas**, um dos principais destinos turísticos do litoral nordestino.

A análise foi construída a partir de uma base de dados fictícia contendo **1.000 reservas**, distribuídas entre **janeiro de 2024 e fevereiro de 2025**, simulando a operação de uma pousada de médio porte com aproximadamente **30 quartos**.

A modelagem dos dados considerou fatores como:

* Sazonalidade turística;
* Perfil dos hóspedes;
* Origem dos visitantes;
* Canais de reserva;
* Categorias de acomodação;
* Comportamento da demanda ao longo do ano.

O objetivo não é reproduzir dados reais de uma empresa específica, mas sim demonstrar como dados podem ser utilizados para compreender uma operação hoteleira, identificar padrões e gerar insights que apoiem a tomada de decisão.

---

## 💡 Por que escolhi este projeto?

Escolhi este projeto por unir **experiência profissional, conhecimento de negócio e interesse pela área de Dados**.

Durante minha atuação na área de hotelaria e atendimento ao público, tive contato com processos relacionados à gestão de reservas, sazonalidade, ocupação, canais de venda e perfil dos hóspedes.

Além disso, por residir na região de Maragogi há vários anos, acompanho de perto a importância do turismo para a economia local e o comportamento da demanda ao longo do ano.

Como estou em processo de transição para a área de **Análise de Dados**, busquei desenvolver um projeto que me permitisse aplicar conceitos de análise, visualização e interpretação de dados em um contexto que já conheço na prática.

Dessa forma, o projeto une **aprendizado técnico** e **conhecimento de negócio**, aproximando a análise de dados de um cenário real de operação.

---

## ❓ Perguntas de Negócio

A análise foi desenvolvida para responder questões relevantes para a gestão de uma pousada de médio porte, como:

* Quais períodos do ano concentram o maior volume de reservas?
* Como a sazonalidade impacta a receita da pousada?
* Qual é o perfil predominante dos hóspedes?
* Quais estados e cidades mais enviam visitantes para a região?
* Quais canais de reserva apresentam melhor desempenho?
* Quais canais geram mais receita?
* Qual categoria de quarto possui maior demanda?
* Quais tipos de quarto mais contribuem para o faturamento?
* Qual é a taxa de cancelamento observada no período analisado?

Responder a essas perguntas permite compreender melhor o comportamento dos hóspedes e identificar oportunidades para apoiar decisões estratégicas.

---

## 🧱 Metodologia de Construção da Base

A base de dados foi criada para simular a operação de uma pousada fictícia localizada em Maragogi/AL.

Embora os dados sejam fictícios, a modelagem foi construída com base em características observadas no turismo da região, buscando representar um cenário plausível para fins de estudo e análise.

---

### 🏨 Porte da Operação

A pousada foi modelada como um empreendimento de médio porte, com aproximadamente **30 quartos**.

Esse porte foi escolhido por representar uma realidade comum entre pousadas da região e por permitir um volume de reservas compatível com a demanda turística local.

| Característica        | Descrição                     |
| --------------------- | ----------------------------- |
| Tipo de negócio       | Pousada fictícia              |
| Localização           | Maragogi/AL                   |
| Porte                 | Médio                         |
| Quantidade de quartos | Aproximadamente 30            |
| Total de reservas     | 1.000                         |
| Período analisado     | Janeiro/2024 a Fevereiro/2025 |

---

### 🌊 Sazonalidade

A distribuição das reservas foi construída para refletir o comportamento sazonal característico do turismo em Maragogi.

| Temporada       | Período                       | Participação aproximada |
| --------------- | ----------------------------- | ----------------------- |
| Alta temporada  | Dez/2024, Jan/2025 e Fev/2025 | 60%                     |
| Média temporada | Julho/2024                    | 25%                     |
| Baixa temporada | Demais meses de 2024          | 15%                     |

A alta temporada concentra maior volume de reservas devido a fatores como:

* Férias escolares;
* Festividades de fim de ano;
* Verão;
* Carnaval.

Julho foi considerado média temporada por coincidir com as férias escolares de meio de ano, mesmo sendo um período em que chuvas podem influenciar a decisão de viagem.

Os demais meses foram classificados como baixa temporada, com menor fluxo de visitantes e maior dependência de feriados prolongados, viagens planejadas e turismo regional.

---

### 🗺️ Origem dos Hóspedes

A distribuição geográfica foi baseada em estados com forte presença no turismo da região.

Os estados com maior participação na base foram:

* Pernambuco;
* São Paulo;
* Bahia.

Também foram incluídos hóspedes provenientes de:

* Alagoas;
* Paraíba;
* Ceará;
* Sergipe;
* Distrito Federal;
* Minas Gerais.

Essa escolha busca representar tanto visitantes regionais quanto turistas de outros mercados emissores relevantes para destinos do litoral nordestino.

---

### 👥 Perfil dos Hóspedes

A modelagem considerou que Maragogi é um destino amplamente associado ao turismo de lazer, especialmente para casais.

Por esse motivo:

* Reservas para **2 hóspedes** representam a maior parte da base;
* Reservas individuais possuem participação reduzida;
* Reservas para grupos familiares aparecem em menor proporção.

Essa distribuição busca reproduzir um cenário compatível com o perfil turístico frequentemente observado na região.

---

### 🛏️ Tipos de Quarto

Foram definidas quatro categorias de acomodação:

| Tipo de Quarto |     Capacidade | Características                          |
| -------------- | -------------: | ---------------------------------------- |
| Standard       | Até 2 hóspedes | Acomodação padrão                        |
| Deluxe         | Até 2 hóspedes | Varanda com vista para o mar             |
| Master         | Até 4 hóspedes | Banheira e comodidades adicionais        |
| Família        | Até 5 hóspedes | Voltado para famílias ou pequenos grupos |

Todas as reservas respeitam a capacidade máxima de cada acomodação, garantindo consistência operacional na base de dados.

Para fins da simulação, foi considerado que crianças de colo não são contabilizadas como hóspedes adicionais e não geram cobrança extra de hospedagem.

A categoria **Deluxe** foi configurada como a mais reservada, simulando um cenário em que os hóspedes buscam maior conforto sem atingir os valores das categorias superiores.

---

### 📲 Canais de Reserva

A distribuição dos canais de reserva foi baseada em tendências atuais observadas no setor hoteleiro, considerando a relevância dos canais digitais na captação de hóspedes.

| Canal        | Participação esperada      |
| ------------ | -------------------------- |
| Booking      | Maior participação         |
| WhatsApp     | Participação intermediária |
| Instagram    | Participação intermediária |
| Site próprio | Menor participação         |
| Telefone     | Menor participação         |

O objetivo é representar a crescente importância das plataformas online e dos canais digitais no processo de aquisição de reservas.

---

### 💰 Política de Preços

Os valores das reservas foram definidos considerando:

* Categoria da acomodação;
* Quantidade de noites reservadas;
* Período da hospedagem;
* Diferença entre dias úteis e finais de semana.

Essa lógica busca simular práticas comuns do setor de hospedagem, em que a precificação varia conforme demanda, tipo de acomodação e período da estadia.

---

### 📌 Premissas Utilizadas

Por se tratar de uma base fictícia, algumas premissas foram adotadas para garantir consistência e realismo na simulação:

* A pousada possui aproximadamente 30 quartos;
* A demanda turística segue padrões sazonais observados na região;
* Casais representam o principal perfil de hóspedes;
* As reservas respeitam a capacidade máxima de cada acomodação;
* Os preços variam de acordo com o tipo de quarto e o período da hospedagem;
* Nenhum dado pessoal real foi utilizado na construção da base.

---

## 🗂️ Estrutura dos Dados

Cada linha da base representa uma reserva individual e contém informações relacionadas ao período da hospedagem, origem dos hóspedes, canal de aquisição, categoria do quarto e valor financeiro da reserva.

| Coluna                | Descrição                                    |
| --------------------- | -------------------------------------------- |
| `id_reserva`          | Identificador único da reserva               |
| `data_reserva`        | Data em que a reserva foi realizada          |
| `checkin`             | Data prevista para entrada do hóspede        |
| `periodo_estadia`     | Quantidade de noites reservadas              |
| `cidade_origem`       | Cidade de origem do hóspede                  |
| `estado_origem`       | Estado de origem do hóspede                  |
| `canal_reserva`       | Canal utilizado para realizar a reserva      |
| `status_reserva`      | Situação da reserva: Confirmada ou Cancelada |
| `tipo_quarto`         | Categoria da acomodação reservada            |
| `quantidade_hospedes` | Número de hóspedes da reserva                |
| `valor_reserva`       | Valor total da reserva em reais              |

---

### 📋 Resumo da Base

| Informação             | Valor                                         |
| ---------------------- | --------------------------------------------- |
| Total de registros     | 1.000 reservas                                |
| Período analisado      | Janeiro/2024 a Fevereiro/2025                 |
| Tipos de quarto        | Standard, Deluxe, Master e Família            |
| Principais canais      | Booking, WhatsApp, Instagram, Site e Telefone |
| Abrangência geográfica | Hóspedes de diferentes estados brasileiros    |

---

## 🛠️ Ferramentas Utilizadas

| Ferramenta | Finalidade                                                       |
| ---------- | ---------------------------------------------------------------- |
| Excel      | Manipulação inicial dos dados e validação da base                |
| Power BI   | Construção do dashboard e visualização dos indicadores           |
| SQL        | Consultas à base de dados e exploração de tabelas complementares |
| GitHub     | Versionamento e documentação do projeto                          |

---

## 📚 Competências Praticadas

Durante o desenvolvimento deste projeto, foram aplicados conceitos relacionados a:

* Estruturação de bases de dados;
* Análise exploratória de dados;
* Definição de indicadores;
* Criação de KPIs;
* Visualização de dados;
* Storytelling com dados;
* Interpretação de métricas de negócio;
* Geração de insights e recomendações.

Embora a base utilizada seja fictícia, o projeto foi desenvolvido seguindo uma lógica próxima à encontrada em cenários reais de negócio, buscando transformar dados em informações úteis para a tomada de decisão.

---

## 📊 Dashboard

Com o objetivo de transformar os dados em informações de fácil interpretação, foi desenvolvido um dashboard interativo no Power BI reunindo os principais indicadores da operação da pousada.

O painel foi estruturado para permitir uma visão geral do negócio, possibilitando a análise de receita, sazonalidade, perfil dos hóspedes, canais de venda e desempenho das categorias de acomodação.

<p align="center">
  <img src="images/imagem_2026-06-20_152637044.png" width="1000" alt="Dashboard da Pousada Estrela">
</p>

### Indicadores apresentados

* Receita Total;
* Total de Reservas;
* Ticket Médio;
* Taxa de Cancelamento;
* Receita por Mês;
* Reservas por Mês;
* Origem dos Hóspedes por Estado;
* Reservas por Canal;
* Receita por Canal;
* Tipos de Quarto mais Reservados;
* Receita por Tipo de Quarto;
* Perfil dos Hóspedes.

---

## 📈 Resultados Obtidos

Ao longo do período analisado, a pousada registrou:

| Indicador            |     Resultado |
| -------------------- | ------------: |
| Receita Total        | R$ 653.230,00 |
| Total de Reservas    |         1.000 |
| Ticket Médio         |     R$ 653,23 |
| Taxa de Cancelamento |         13,7% |

Também foi observado que:

* A categoria **Deluxe** foi a mais reservada;
* Reservas para **2 hóspedes** representaram mais de 60% da demanda;
* O **Booking** foi o principal canal de aquisição;
* Pernambuco, São Paulo e Bahia concentraram grande parte dos visitantes;
* A alta temporada concentrou a maior parcela das reservas e da receita.

---

## 🔎 Principais Insights

### 1. A alta temporada concentrou a maior parte da demanda

A maior parte das reservas ocorreu entre **dezembro de 2024 e fevereiro de 2025**, período que concentrou aproximadamente 60% do volume total de hospedagens.

Esse comportamento evidencia a forte influência da sazonalidade sobre a operação da pousada e reforça a importância do planejamento para os períodos de maior demanda.

---

### 2. Casais representaram o perfil predominante dos hóspedes

Reservas para duas pessoas foram amplamente predominantes ao longo do período analisado.

Esse resultado está alinhado com o perfil turístico frequentemente associado a destinos de praia e lazer, indicando que ações de marketing voltadas para casais podem apresentar maior potencial de conversão.

---

### 3. O quarto Deluxe foi a categoria mais procurada

Entre as acomodações disponíveis, a categoria **Deluxe** apresentou o maior volume de reservas.

Esse comportamento sugere que os hóspedes valorizam diferenciais de conforto e experiência, desde que os valores permaneçam acessíveis quando comparados às categorias superiores.

---

### 4. O Booking foi o principal canal de aquisição

A maior parte das reservas foi originada através do **Booking**, superando os demais canais de venda.

O resultado evidencia a relevância das plataformas online para a captação de hóspedes, mas também indica a necessidade de monitorar a dependência de um único canal.

---

### 5. Pernambuco, São Paulo e Bahia concentraram a maior parte dos visitantes

A análise geográfica revelou maior participação de hóspedes provenientes desses estados.

Esse comportamento sugere oportunidades para campanhas segmentadas e ações de marketing direcionadas aos mercados que já demonstram maior interesse pelo destino.

---

### 6. A receita acompanhou o comportamento da sazonalidade

Os meses de maior demanda também apresentaram os maiores níveis de faturamento.

Esse resultado demonstra a relação direta entre ocupação e receita, reforçando a importância de estratégias comerciais específicas para os períodos de baixa temporada.

---

### 7. A diversificação de categorias permitiu atender diferentes perfis de hóspedes

Embora o quarto Deluxe tenha liderado em quantidade de reservas, as demais categorias contribuíram para atender públicos com necessidades distintas, ampliando as possibilidades de venda da pousada.

---

## 💡 Recomendações

Com base nos resultados encontrados, algumas ações poderiam ser consideradas:

* Desenvolver campanhas específicas para períodos de baixa temporada;
* Incentivar avaliações no Booking para fortalecer a reputação da pousada;
* Investir em canais próprios, como WhatsApp e Site, para reduzir a dependência de plataformas terceirizadas;
* Criar pacotes voltados para casais, principal público identificado na análise;
* Explorar estratégias de upsell para aumentar a ocupação dos quartos Master e Família.

---

## ⚠️ Limitações

Este projeto utiliza uma base de dados fictícia criada exclusivamente para fins educacionais e de portfólio.

Embora a modelagem tenha sido inspirada em características reais do turismo de Maragogi, os resultados não representam dados operacionais de nenhuma empresa específica.

Consequentemente, os insights apresentados devem ser interpretados como exercício de análise e não como diagnóstico real de mercado.

---

## 🚀 Próximos Passos

Possíveis evoluções futuras para este projeto incluem:

* Melhoria do banco de dados relacional;
* Criação de dashboards avançados com segmentações adicionais;
* Implementação de automações para envio de relatórios;
* Desenvolvimento de um site fictício para a pousada;
* Integração com APIs de reservas e sistemas de gestão hoteleira;
* Aplicação futura de Python para automação, tratamento e análise dos dados.

---

## ✅ Conclusão

Este projeto permitiu aplicar conceitos fundamentais de Análise de Dados em um contexto próximo da realidade do setor hoteleiro.

A partir de uma base fictícia, foi possível estruturar perguntas de negócio, construir indicadores, desenvolver visualizações e gerar insights que poderiam auxiliar uma pousada na compreensão de sua operação.

Além do desenvolvimento técnico, o projeto também reforça a importância do conhecimento de negócio na análise de dados, especialmente quando os dados são utilizados para apoiar decisões estratégicas.


