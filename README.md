# Análise da Segurança Pública no Brasil (2023–2024)

## Sobre o projeto

Este projeto tem como objetivo analisar indicadores de segurança pública nos estados brasileiros, comparando os dados de 2023 e 2024.

A análise busca identificar diferenças regionais, variações nos indicadores de violência e possíveis padrões que contribuam para uma melhor compreensão do cenário da segurança pública no Brasil.

O projeto foi desenvolvido como parte do meu aprendizado em Análise de Dados, aplicando técnicas de tratamento, exploração, análise e visualização de dados no Data Studio (Looker Studio).

## Problema e justificativa

A segurança pública é um tema de grande relevância social e política,  principalmente em ano eleitoral, como as eleições presidenciais brasileiras de 2026. A violência nesse período se torna ainda mais evidente, apresentando diferenças entre os estados e podendo sofrer variações significativas ao longo do tempo.

Por meio da análise de dados públicos, é possível identificar estados com indicadores elevados, observar mudanças entre períodos e produzir informações que auxiliem na compreensão do problema e na discussão de possíveis ações de prevenção.

## Fonte de dados

Os dados utilizados foram obtidos no **19º Anuário Brasileiro de Segurança Pública 2025**, publicado pelo Fórum Brasileiro de Segurança Pública (FBSP).

- **Instituição:** Fórum Brasileiro de Segurança Pública (FBSP).
- **Publicação:** 19º Anuário Brasileiro de Segurança Pública 2025.
- **Formato original:** planilha Excel.
- **Método de coleta:** download direto pelo portal oficial.

**Fonte oficial:**  
https://publicacoes.forumseguranca.org.br/items/c3605778-37b3-4ad6-8239-94e4cb236444

## Indicadores analisados

A base consolidada reúne oito indicadores:

- Mortes Violentas Intencionais (MVI);
- Latrocínio — vítimas;
- Latrocínio — ocorrências;
- Roubo de celulares;
- Furto de celulares;
- Roubo e furto de celulares;
- Homicídios de mulheres;
- Feminicídios.

A análise exploratória e o dashboard priorizaram quatro indicadores: MVI, latrocínio, roubo de celulares e feminicídios.

## Ferramentas e tecnologias

- **Python:** tratamento e análise dos dados.
- **Pandas:** manipulação e organização dos dados.
- **Matplotlib e Seaborn:** visualização e exploração dos dados.
- **Jupyter Notebook:** desenvolvimento das análises exploratórias.
- **Looker Studio:** criação do dashboard interativo.
- **Excel:** armazenamento e consulta dos dados originais.
- **Git e GitHub:** versionamento e documentação do projeto.

## Principais resultados

A comparação entre 2023 e 2024 revelou diferenças importantes entre os estados brasileiros.

**Mortes Violentas Intencionais (MVI):**
- O Amapá apresentou a maior taxa em 2024, com aproximadamente 45,09 mortes por 100 mil habitantes.
- O Amapá também registrou a maior redução percentual entre os estados analisados, com queda de 30,57%.

**Latrocínio:**
- 15 dos 27 estados apresentaram redução nas taxas.
- O Mato Grosso do Sul registrou aumento de 237,20%, passando de 0,17 para 0,59 por 100 mil habitantes.

**Roubo de celulares:**
- A Paraíba apresentou a maior redução, de 55,23%.
- O Rio de Janeiro registrou o maior aumento, de 38,16%.

**Feminicídios:**
- O Amapá apresentou a maior redução, de 50,26%.
- O Piauí registrou o maior aumento, de 42,40%.

As variações percentuais devem ser interpretadas em conjunto com as taxas absolutas, especialmente nos indicadores com valores iniciais baixos.

## Dashboard interativo

O projeto conta com um dashboard desenvolvido no Looker Studio (Data Studio), organizado em três páginas:

1. Panorama da violência letal (MVI).
2. Crimes patrimoniais e violência contra a mulher.
3. Análise dos resultados e recomendações.

**Acesse o dashboard:** [https://datastudio.google.com/s/mrGdf47RdVM]

## Limitações da análise

- A comparação contempla apenas os anos de 2023 e 2024.
- As variações percentuais devem ser analisadas considerando os valores absolutos e as taxas de cada período.
- Os indicadores possuem definições e denominadores próprios, portanto devem ser interpretados separadamente.

## Considerações finais

O projeto demonstra como dados públicos podem ser utilizados para investigar problemas sociais, identificar diferenças regionais e transformar informações em visualizações acessíveis.

Além de desenvolver habilidades técnicas em análise de dados, o trabalho reforça a importância da interpretação crítica dos resultados e da comunicação de informações por meio de dashboards.

---

**Desenvolvido por:** Rafael Machado da Cruz  
**Área de estudo:** Análise de Dados