# Projeto de Análise e Previsão de Satisfação do Cliente em Empresas de Fast Food

## **Proposta do Projeto:**
Este projeto tem como objetivo analisar a satisfação do cliente em empresas de fast food e prever como eventos específicos afetam essa satisfação. A proposta é fornecer insights valiosos para empresas do setor de fast food, permitindo que elas compreendam melhor como suas ações e eventos impactam a experiência do cliente.

![Media por ano Todas](https://github.com/T2-Ciencia-de-dados/Analise-de-sentimento/assets/79452652/bc4b5b78-31ec-4967-b459-050844da4e44)

## **Pipeline da Solução:**

## 1. Coleta de Dados:

Os dados foram coletados de diversas fontes, abrangendo informações sobre eventos relevantes para empresas de fast food. Isso inclui campanhas publicitárias, mudanças de receitas, lançamentos de produtos e outros eventos que poderiam influenciar a satisfação do cliente. As empresas consideradas incluem CocaCola, Pepsi, McDonalds, BurgerKing, KFC, PizzaHut, Subway, Starbucks, Nestle e Dominos.

## 2. Análise Exploratória de Dados (EDA):

Durante a fase de EDA, diversas análises estatísticas e visuais foram realizadas para entender a distribuição e características dos dados. Gráficos de barras, histogramas e boxplots foram utilizados para explorar a distribuição da satisfação do cliente em relação às diferentes empresas e eventos.

## 3. Categorização de Eventos:

Os eventos foram categorizados para proporcionar uma visão mais abrangente e compreensível. A categorização inclui tipos como lançamento de campanha publicitária, mudança de receita, marketing, sustentabilidade, entre outros. Isso facilitou a análise agrupada de eventos similares.

## 4. Visualização de Dados:

A biblioteca Seaborn foi utilizada para criar visualizações informativas, como histogramas de satisfação por empresa e distribuição de eventos ao longo do tempo. Além disso, foram gerados gráficos de média de satisfação por ano, destacando eventos marcantes.

## 5. Pré-processamento de Dados:

Os dados foram pré-processados para serem adequados ao treinamento de modelos de aprendizado de máquina. Isso incluiu a normalização de variáveis numéricas, codificação de variáveis categóricas e a criação de uma coluna de categorias de satisfação com base em uma função de categorização.

## 6. Treinamento do Modelo de Machine Learning:

Foi utilizado um modelo de rede neural construído com a biblioteca TensorFlow e Keras para prever a satisfação do cliente. O modelo foi treinado com dados históricos, incluindo informações sobre empresa, dia da semana, ano, mês e categoria do evento.

## 7. Avaliação do Modelo:

O modelo foi avaliado quanto à sua capacidade de prever a satisfação do cliente em um conjunto de teste. Métricas como acurácia, precisão e recall foram calculadas para avaliar o desempenho do modelo.

## 8. Resultados e Conclusões:

A análise revelou que eventos que resultam em mudanças substanciais, como remoção de produtos ou mudança de receita (ingredientes), têm um impacto mais negativo na satisfação do cliente em empresas de fast food. Essa conclusão é crucial para as empresas do setor, destacando a importância de considerar cuidadosamente as mudanças significativas que podem afetar a experiência do cliente.

## 9. Utilização do Modelo para Previsões:

O modelo treinado foi aplicado a novos dados sintéticos relacionados às empresas McDonalds e Subway. Os resultados foram mapeados para categorias compreensíveis e exibidos, demonstrando a utilidade do modelo na previsão da satisfação do cliente em eventos específicos.

## 10. Aplicação de Encoders e Scalers em Novos Dados:

Foi demonstrado como aplicar encoders e scalers previamente treinados em novos dados antes de fazer previsões com o modelo. Isso é essencial para garantir que os novos dados tenham o mesmo formato que os dados de treinamento.

## **Resultados Alcançados:**

As categorias previstas para as empresas McDonalds e Subway foram exibidas, e imagens associadas às empresas foram mostradas usando a biblioteca IPython.

Este projeto oferece uma visão abrangente do processo de análise e previsão de satisfação do cliente em empresas de fast food. A conclusão crítica destaca a importância de gerenciar cuidadosamente eventos que envolvem mudanças significativas, orientando as estratégias das empresas para melhor atender às expectativas e preferências dos clientes.


A análise revelou que eventos que resultam em mudanças substanciais, como remoção de produtos ou mudança de receita (ingredientes), têm um impacto mais negativo na satisfação do cliente em empresas de fast food. Essa conclusão é crucial para as empresas do setor, destacando a importância de considerar cuidadosamente as mudanças significativas que podem afetar a experiência do cliente.

Como pode ser observado,como exemplo, no ano de 2016 ambas as empresas(PizzaHut e Subway) mudaram de alguma forma o padrao com que receitas antigas eram feitas e da forma com que essas mudanças foram apresentadas ao publico, teve um impacto negativo na visao dos clientess sobre essas empresas.
PizzaHut:
![MudançasPizzaHut](https://github.com/T2-Ciencia-de-dados/Analise-de-sentimento/assets/79452652/204c4bd3-d717-4d4e-9e29-8bc1f2d81b37)
Subway:
![MudançasSubWay](https://github.com/T2-Ciencia-de-dados/Analise-de-sentimento/assets/79452652/f4872855-ec7c-4e50-b473-f0bd592de4e0)


Este projeto oferece uma visão abrangente do processo de análise e previsão de satisfação do cliente em empresas de fast food, fornecendo uma solução valiosa para o setor.

