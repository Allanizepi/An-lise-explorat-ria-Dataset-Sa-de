Análise Preditiva de Dados de Saúde

Este projeto realiza uma análise descritiva e preditiva de dados relacionados à saúde, com foco na influência do sono e dos estilos de vida no peso corporal dos indivíduos. Através de técnicas de aprendizado de máquina, foi desenvolvido um modelo capaz de prever a categoria de peso (IMC) de uma pessoa com base em atributos como duração e qualidade do sono, nível de estresse, frequência cardíaca e passos diários.

📊 Objetivo

O principal objetivo deste estudo é:

Análise descritiva: Explorar e entender a distribuição dos dados, identificando padrões e relações entre as variáveis.

Análise preditiva: Construir um modelo de aprendizado de máquina que classifique os indivíduos em categorias de peso (Normal, Overweight, Obese) com base em seus hábitos de sono e estilo de vida.

🧪 Metodologia

Aquisição e Pré-processamento de Dados:

Leitura e limpeza dos dados.

Conversão de variáveis categóricas em numéricas.

Identificação e tratamento de valores ausentes.

Análise Exploratória:

Geração de estatísticas descritivas.

Visualização das distribuições das variáveis.

Identificação de correlações entre os atributos.

Divisão dos Dados:

Separação dos dados em conjuntos de treino (70%) e teste (30%) utilizando a função train_test_split do Scikit-learn.

Padronização dos Dados:

Aplicação do StandardScaler para normalizar as variáveis numéricas, garantindo que todas tenham a mesma escala.

Construção do Modelo Preditivo:

Implementação de um modelo de Regressão Logística.

Avaliação do desempenho utilizando métricas como acurácia, F1-score e matriz de confusão.

Ajustes e Melhorias:

Modificação do algoritmo para Random Forest com o parâmetro class_weight='balanced' para lidar com o desbalanceamento das classes.

Reavaliação do modelo e comparação de resultados.

📈 Resultados

Após os ajustes, o modelo apresentou:

Acurácia: 97%

Desempenho equilibrado: Capacidade de prever corretamente todas as classes, incluindo as minoritárias.

Robustez: Melhor desempenho em valores próximos aos limites das classes de peso.

🛠️ Tecnologias Utilizadas

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

📂 Estrutura do Repositório
/Analise_Preditiva_Dataset_Saude
│
├── Analise_Descritiva_Preditiva_Saude.ipynb
├── README.md
└── dataset.csv

🚀 Como Executar

Clone este repositório:

git clone https://github.com/Allanizepi/Analise_Preditiva_Dataset_Saude.git
cd Analise_Preditiva_Dataset_Saude


Instale as dependências:

pip install -r requirements.txt


Execute o notebook:

jupyter notebook Analise_Descritiva_Preditiva_Saude.ipynb
