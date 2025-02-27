# EcomDemand
Demand Forecast in E-commerce

## Descrição do Projeto
O **EcomDemand** é um projeto voltado para a previsão de demanda de múltiplos produtos em uma plataforma de e-commerce. Utilizando técnicas de séries temporais, regressão linear e, quando aplicável, clusterização, o objetivo é desenvolver um pipeline robusto que passe pela coleta e integração de dados brutos até a criação de modelos preditivos. Essa abordagem permite identificar padrões de vendas, sazonalidade e o impacto de promoções, contribuindo para uma melhor gestão de estoque e estratégias de marketing.

## Objetivos
- **Prever a Demanda:** Desenvolver modelos que estimem o volume de vendas dos produtos com base em dados históricos e variáveis externas (como promoções, sazonalidade e eventos).
- **Segmentar Produtos:** Aplicar técnicas de clusterização para agrupar produtos com comportamentos de vendas semelhantes e construir modelos específicos para cada grupo.
- **Criar um Pipeline de Dados Completo:** Implementar um processo de coleta, limpeza, transformação e integração dos dados, desde fontes brutas (ex.: web scraping, APIs ou datasets públicos) até a modelagem.

## Importância do Projeto
- **Otimização de Estoque:** Previsões precisas permitem reduzir os custos com excesso ou falta de produtos, contribuindo para uma operação mais eficiente.
- **Melhoria na Estratégia de Marketing:** Com insights sobre a demanda, é possível ajustar campanhas promocionais e estratégias de vendas para maximizar resultados.
- **Tomada de Decisão Baseada em Dados:** Oferece uma base analítica sólida para a gestão operacional, ajudando empresas de e-commerce a se manterem competitivas no mercado.

## Modelos e Técnicas Utilizadas
- **Regressão Linear:** Para modelar a relação entre as variáveis preditoras (como histórico de vendas, promoções, datas especiais) e a demanda dos produtos.
- **Análise de Séries Temporais:** Criação de variáveis temporais (lags, médias móveis, variáveis dummy para feriados e eventos) para capturar a dinâmica de vendas.
- **Clusterização:** Aplicação de algoritmos como K-Means para segmentar produtos com comportamentos de venda similares, permitindo ajustes específicos nos modelos.
- **Engenharia de Dados:** Coleta de dados brutos por meio de web scraping, APIs públicas (por exemplo, de marketplaces ou portais de dados abertos) e datasets como o "Online Retail" do UCI, seguido de limpeza, transformação e integração dos dados.
- **Validação e Métricas:** Uso de técnicas de validação cruzada temporal e métricas como RMSE, MAE e R² para avaliar a performance dos modelos.

## Estrutura do Repositório
- **data/**: Scripts e arquivos para coleta, armazenamento e pré-processamento dos dados.
- **notebooks/**: Notebooks Jupyter para análise exploratória, visualização de dados e experimentos com os modelos.
- **src/**: Código fonte para a implementação do pipeline de dados e dos modelos preditivos.
- **README.md**: Este arquivo, com a descrição e orientação do projeto.
- **requirements.txt**: Lista das dependências e bibliotecas utilizadas.
