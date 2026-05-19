# Educação Infantil: Projeção e Alocação de Vagas com Data Science e IA
Este projeto visa a estruturação de um Artigo para TCC focado no estudo da problematica social e aplicação de Ciência de Dados e Inteligência Artificial para atuar no problema de alocação e previsão de vagas na educação infantil pública, com estudo de caso voltado, inicialmente, ao município de Praia Grande/SP.

Projeto de TCC: Projeção e Alocação de Vagas com Data Science e IA na Educação Infantil em Praia Grande/SP

# 1. Introdução e Contextualização

A administração pública brasileira enfrenta atualmente o desafio de converter a "revolução dos dados" em melhorias tangíveis na entrega de serviços ao cidadão. Conforme discutido na literatura técnica da Enap, a gestão de políticas públicas ainda sofre com uma persistente "lacuna informacional" — onde o excesso de dados brutos não se traduz em inteligência — e um "gap de competências" analíticas, com estimativas de que 20% da força de trabalho federal atua em funções passíveis de automação, mas carece de habilidades para lidar com grandes volumes de dados.

No âmbito da Educação Infantil, essa deficiência analítica impacta a garantia de direitos fundamentais, especificamente na gestão de filas de espera e na expansão da rede escolar. O uso de Inteligência Artificial (IA) e Ciência de Dados surge como ferramenta indispensável para descobrir necessidades reprimidas e mapear a demanda regional de forma dinâmica. Em municípios com crescimento populacional acelerado, como Praia Grande/SP, a transição de decisões baseadas em intuição política para modelos orientados por evidências é o único caminho para a eficiência alocativa.

A tomada de decisão em políticas públicas, orientada pelo respeito aos direitos fundamentais e valores democráticos, exige o uso de evidências técnicas sólidas para garantir que a alocação de recursos seja eficiente, justa e transparente.

# 2. Objetivos do Projeto

##### Objetivo Geral: 
* Otimizar a alocação e a projeção de vagas na rede de Educação Infantil do município de Praia Grande/SP por meio do desenvolvimento de modelos preditivos e algoritmos de inteligência de dados, utilizando benchmarks federais como referência de eficiência.

##### Objetivos Específicos:
* Mapear a demanda por região (distrito/setor educacional), identificando gargalos geográficos e áreas de alta vulnerabilidade social.
* Aplicar algoritmos de matching (Gale-Shapley e Top Trading Cycles) integrados à Reatribuição Dinâmica (PLDA) para garantir um emparelhamento estável e eficiente entre aluno e unidade escolar, mesmo após desistências iniciais.
* Desenvolver modelos de séries temporais (Como Prophet, ARIMA, Variações de Arvores de decisoes simples e/ou sequenciais/boosting ) via Python para prever o tamanho das filas de espera e antecipar a necessidade de novas turmas.
* Analisar e implementar critérios de governança e ética em IA, assegurando a conformidade com a LGPD e a mitigação de vieses algorítmicos através de métricas de Fairness.

# 3. Materiais Utilizados (Referencial Teórico e Prático)

### 3.1. Vídeos e Tutoriais
##### Material de	foco mais técnico/prático abordando:
ARIMA, Árvore de Decisão, Dashboards, GeoSpatial + Machine Learning, K-Means, LIghtGBM, LSTM, LSTM/ GRU (Redes Recorrentes), Mineração de Dados, PROPHET, Random Forest, Redes Neurais, SARIMAX (ARIMA com variáveis exógenas), Séries Temporais, Streamlit, Python, SQL, Postgree, SVM, Temporal Fusion Transformer (TFT), VAR / VARMAX (Vector AutoRegression), Explainable Artificial Intelligence (XAI)/ SHAP, XGBoost, LightGBM, CatBoost

### 3.2. Leituras e Bases de Dados

##### 1. Fontes de Dados e Referências Metodológicas: 
* Dados Gerenciais SME (SIGPEC/EOL), plataforma Vaga na Creche e Pátio Digital. O projeto utilizará o modelo do GeoSampa e InfoCidade (São Paulo) como blueprint metodológico para o mapeamento espacial em Praia Grande/SP.
* Bases Nacionais: Censo Escolar/INEP, Crescimento Demográfico — IBGE, Ministério do Desenvolvimento e Assistência Social, Família e Combate à Fome (MDS), Vulnerabilidade Social — IPVS (SEADE), Dados Institucionais — Prefeitura de Praia Grande e indicadores do Observa Primeira Infância.
##### 2. Textos Base/ Trabalhos de referência:
* Análise Experimental de Modelos Preditivos para a Previsão da Demanda por Vagas na Rede Pública de Ensino
* Acesso à creche nos municípios brasileiros
* Análise Espacial de Instituições Públicas de Ensino Fundamental em Relação às Suas Demandas Potenciais
* Aplicações de Aprendizagem de Máquina com dados do INEP:  Uma Revisão da Literatura
* Big Data Fortaleza: Plataforma Inteligente para Políticas Públicas
* Grow and multiply social development, birth rates and demographic transition in the Municipality of São Paulo
* Livro Digital Ciência de Dados em Políticas Públicas
* Optimizing education resource allocation using grey model forecasting of school age populations
* Retrato da Educação Infantil no Brasi - 2025
* The Distributional Effects of School Choice - Evidence from New York City Public Elementary Schools
* Uma periferia_dois centros - O município de Praia Grande no contexto da formação da macrometrópole paulista

# 4. Estrutura Proposta para o Artigo do TCC

1. Resumo e Abstract: Síntese do problema das filas e a proposta de solução baseada em algoritmos de emparelhamento e predição.
2. Revisão Bibliográfica: Análise da IA ética, consideração de experiências internacionais (NYC/Chile/China). Foco em sistemas de matching e nos princípios de transparência e explicabilidade.
3. Metodologia: Descrição do pipeline ETL em Python, utilizando bibliotecas como Scikit-learn, Prophet e GeoPandas. Detalhamento do uso de classificadores para identificar objetos de gasto e prever conversão de demanda em matrícula motivadoras para criação de vagas futuras.
4. Resultados e Discussão: Projeção de filas vs. capacidade física, associação de multiplas variáveis para predição de vagas como natalidade, adensamento populacional, variações de renda, mobilidade urbana e etc.
5. Conclusão: Reflexão sobre os desafios de implementação, incluindo a infraestrutura tecnológica local e verbas, predição acertiva para orientar a criação de vagas e encaminhamento de alunos de maneira menos reativa

# 5. Principais Conceitos a Serem Estudados

* Gale-Shapley (Deferred Acceptance) & PLDA: Algoritmo de emparelhamento estável que otimiza a satisfação das preferências das famílias. A inclusão da Reatribuição Dinâmica (PLDA) é fundamental para tratar vagas remanescentes e desistências de forma justa.
* Séries Temporais (Prophet/ARIMA): Modelos estatísticos para previsão do crescimento da fila de espera, permitindo que a secretaria antecipe a abertura de turmas antes do colapso da capacidade física.
* Clustering (K-Means): Técnica de aprendizado não supervisionado para criar perfis de demanda. O projeto empregará a Inércia e o Método do Cotovelo para identificar "Regiões Prioritárias" com base em vulnerabilidade socioeconômica e carência de cobertura escolar.
* Modelos Logit/Probit: Modelos de escolha discreta superiores à regressão linear para eventos binários (participar ou não da rede), pois garantem que as probabilidades previstas permaneçam no intervalo matemático de 0 a 1.
* XAI com SHAP
* Featuring Engineering
* Conformal Prediction
* Princípios da IA Ética e Fairness: A aplicação de Justiça (Fairness) será tratada como um constrangimento matemático dentro do algoritmo (conforme as 21 definições de Narayanan), buscando evitar que vieses geográficos ou socioeconômicos prejudiquem grupos específicos.

# 6. Datasets e Fontes de Dados (Ground Truth)

Para a viabilidade do projeto em Praia Grande/SP, as seguintes bases e referências são necessárias:

* [ ] Dados Gerenciais SME (Sistemas SIGPEC e EOL).
* [ ] Plataforma Vaga na Creche (Dados de fila em tempo real).
* [ ] Censo Escolar/INEP.
* [ ] Pátio Digital e InfoCidade (Referenciais de evolução de demanda).
* [ ] Shapefiles municipais (Inspirados no modelo GeoSampa para mapeamento de distritos e setores).

# 7. Link para este projeto no NotebookLM

https://notebooklm.google.com/notebook/7d98006b-9608-47a6-ac6e-62914b5f17ba

