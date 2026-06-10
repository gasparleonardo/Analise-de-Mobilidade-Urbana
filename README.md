# Análise de Mobilidade Urbana e Impacto do Clima: Zuber

## Descrição do Projeto
Este projeto foi desenvolvido com foco em Análise Exploratória de Dados (EDA) e Testes Estatísticos de Hipóteses para o setor de transporte por aplicativo. O desafio consistiu em analisar o comportamento de usuários e empresas de transporte na cidade de Chicago, buscando identificar padrões de demanda e correlacionar variáveis ambientais com a performance operacional. A análise incluiu o tratamento de bases de dados de viagens, a identificação de bairros com maior tráfego e a validação estatística de que o clima possui um impacto significativo na duração das corridas entre o *Loop* e o aeroporto, fornecendo subsídios para ajustes na precificação dinâmica.

---

## Tecnologias e Ferramentas Utilizadas
* **Linguagem:** Python
* **Análise e Manipulação de Dados:** Pandas
* **Análise Estatística:** SciPy (Teste t de Student)
* **Visualização de Dados:** Matplotlib e Seaborn
* **Ambiente de Desenvolvimento:** Jupyter Notebook

---

## Pipeline de Dados e Metodologia

### 1. Auditoria e Limpeza de Dados
* Carga e integração de múltiplas bases de dados (empresas de táxi, bairros e previsões meteorológicas).
* Processamento de dados para identificar as empresas líderes de mercado e os principais destinos, garantindo a integridade dos tipos de variáveis para análise.

### 2. Análise Exploratória e Visualização de Tendências
* Identificação dos Top 10 bairros de destino, cruzando a frequência de corridas com os nomes das localidades.
* Construção de gráficos de barras e visualizações de distribuição para identificar quais empresas detêm o maior volume de viagens.
* Mapeamento de padrões de demanda, filtrando dados para evidenciar os pontos de maior atração na cidade.

### 3. Testes Estatísticos de Hipóteses (Teste t de Student)
* Formulação de hipóteses para verificar se a duração das corridas entre o *Loop* e o aeroporto é afetada pelas condições meteorológicas (dias chuvosos vs. dias de bom tempo).
* Aplicação do teste de Student para amostras independentes, com nível de significância de 5%, garantindo rigor estatístico na conclusão.

---

## Principais Insights & Impacto de Negócio
* **Concentração de Mercado:** O mercado de transporte em Chicago é dominado por um grupo seleto de empresas, com os líderes capturando a maior fatia do volume de viagens, o que sugere um ambiente altamente competitivo para novas entradas.
* **Geografia da Demanda:** Os dados indicam uma concentração clara de destinos no *Loop*, que funciona como o hub central da cidade, validando a necessidade de estratégias de posicionamento de frota focadas nessa área.
* **O Fator Meteorológico:** Comprovou-se estatisticamente que o clima "Bad" (chuva/tempo ruim) aumenta o tempo de ocupação do motorista. Isso é crucial para a Zuber: o sistema de precificação dinâmica deve ser sensível à meteorologia em tempo real para compensar a redução da oferta de veículos causada pelo trânsito mais lento.
* **Decisões Data-Driven:** A análise provou que a eficiência operacional está diretamente ligada à capacidade de prever o impacto ambiental no tempo de percurso, transformando variáveis meteorológicas em dados estratégicos para o algoritmo de preços.

---

