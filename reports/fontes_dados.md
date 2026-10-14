# Levantamento das fontes de dados públicas e não confidenciais

## 1. Fonte de dados utilizada

### 1.1. Fórum Brasileiro de Segurança Pública (FBSP)

**Descrição da fonte**

A principal fonte de dados deste projeto é o Fórum Brasileiro de Segurança Pública (FBSP), organização que publica estudos, pesquisas e estatísticas relacionadas à segurança pública no Brasil.

Para este projeto, foi utilizado o **19º Anuário Brasileiro de Segurança Pública 2025**, que reúne informações sobre diferentes indicadores de violência e criminalidade, incluindo dados referentes aos anos de 2023 e 2024.

**Link da fonte oficial:**
https://publicacoes.forumseguranca.org.br/items/c3605778-37b3-4ad6-8239-94e4cb236444

**Tipo de dados disponíveis**

Os dados utilizados são predominantemente **estruturados**, pois estão organizados em planilhas, linhas e colunas, permitindo sua leitura e manipulação por ferramentas de análise de dados.

A planilha contém informações numéricas e categóricas, como:

* Unidades da Federação;
* anos de referência;
* quantidades de ocorrências e vítimas;
* taxas por 100 mil habitantes;
* indicadores relacionados à violência e à criminalidade.

**Indicadores selecionados**

Foram selecionadas quatro tabelas do Anuário:

* **T01 — Mortes Violentas Intencionais (MVI):** informações sobre as ocorrências e taxas de MVI em 2023 e 2024.
* **T04 — Latrocínio:** dados sobre o número de vítimas e o número de ocorrências, incluindo suas respectivas taxas.
* **T13 — Roubo e furto de celulares:** informações sobre roubos, furtos e o total combinado desses registros.
* **T24 — Feminicídios:** dados sobre feminicídios, taxas e proporção.

**Método de acesso e coleta**

O acesso aos dados foi realizado por meio do download direto da planilha disponibilizada pelo FBSP em sua publicação oficial.

Após o download, o arquivo foi armazenado localmente na pasta `data/raw/` do projeto. A leitura e a extração das tabelas selecionadas foram realizadas com Python, utilizando a biblioteca Pandas e recursos de leitura de arquivos Excel.

Em seguida, os dados passaram por etapas de tratamento e padronização, incluindo seleção de colunas, organização dos indicadores por ano, conversão dos tipos de dados e remoção de referências numéricas de notas presentes em alguns nomes de Unidades da Federação.

Os dados tratados foram organizados em arquivos CSV, armazenados na pasta `data/processed/`, para utilização nas análises exploratórias e nas etapas posteriores do projeto.

**Necessidade de API ou web scraping**

Não foi necessário utilizar API nem realizar web scraping, pois os dados estavam disponíveis para download direto em formato de planilha. Esse método também evita a necessidade de automatizar a extração de informações de páginas da web.

## 2. Publicidade e confidencialidade dos dados

A fonte selecionada disponibiliza estatísticas agregadas sobre segurança pública, organizadas principalmente por Unidade da Federação e ano de referência.

A análise utiliza indicadores estatísticos e quantitativos, e não depende de nomes, documentos, endereços ou outros identificadores pessoais de vítimas ou envolvidos.

Dessa forma, o conjunto de dados utilizado no projeto não contém informações pessoais identificáveis nos campos selecionados para a análise.

## 3. Justificativa da escolha da fonte

O Anuário Brasileiro de Segurança Pública foi escolhido por reunir indicadores relevantes para o estudo da violência e da criminalidade no Brasil em uma publicação especializada.

A disponibilidade de dados de diferentes indicadores e de mais de um ano permite realizar comparações entre as Unidades da Federação e analisar variações entre 2023 e 2024.

Além disso, o formato estruturado da planilha facilita a leitura por Python, o tratamento dos dados, a criação de gráficos e a construção de um painel de visualização.

## 4. Limitações da fonte

Os dados refletem os indicadores, períodos e critérios metodológicos apresentados na publicação consultada. Portanto, as conclusões devem considerar as definições utilizadas pelo FBSP e as limitações inerentes às estatísticas de segurança pública.

A comparação entre indicadores distintos exige cuidado, pois cada medida representa um fenômeno específico. Por exemplo, o número de vítimas de latrocínio não equivale necessariamente ao número de ocorrências desse crime.

Além disso, a comparação entre os anos de 2023 e 2024 permite observar diferenças no período analisado, mas, isoladamente, não explica as causas dessas variações nem permite estabelecer relações de causalidade.
