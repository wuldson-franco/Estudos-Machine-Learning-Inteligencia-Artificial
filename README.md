# Estudos de Machine Learning e Inteligência Artificial

Repositório com os notebooks que escrevo durante meus estudos de **Machine Learning**, **Deep Learning** e **Inteligência Artificial**. Os notebooks são abertos para quem quiser estudar junto, acompanhar o passo a passo ou reaproveitar os exemplos.

> Este repositório está em construção. Novos temas (como NLP, LLMs, IA Generativa e Agentes) serão adicionados ao longo dos estudos.

## Sobre o projeto

Como Engenheiro de Dados/ML e Professor, estou aprofundando meus estudos em ML e IA como parte do meu plano de desenvolvimento. Cada notebook segue o mesmo princípio: explicar o conceito, mostrar o código funcionando e interpretar o resultado.

## Estrutura do repositório

```
Estudos-Machine-Learning-Inteligencia-Artificial/
├── MachineLearning/            # Fundamentos e algoritmos clássicos
├── MachineLearningAvancado/    # Engenharia de atributos, AutoML, clusters e mais
├── DeepLearning/               # Redes neurais, CNN, LSTM e detecção de objetos
└── README.md
```

## Conteúdo

### [MachineLearning](./MachineLearning)

| # | Notebook | Tema |
|---|---|---|
| 1 | `1_AulaML_RegressaoLinear` | Regressão linear |
| 2 | `2_AulaML_RegressaoLinear_StatsModels` | Regressão linear com StatsModels |
| 3 | `3_AulaML_NaiveBayes` | Naive Bayes |
| 4 | `4_AulaML_DecisionTree` | Árvores de decisão |
| 5 | `5_AulaML_RandonForest` | Random Forest |
| 6 | `6_AulaML_KNN` | K-Nearest Neighbors (KNN) |
| 7 | `7_AulaML_ClutersDiversos` | Algoritmos de clusterização |
| 8 | `8_AulaML_RegrasApriori` | Regras de associação (Apriori) |

### [MachineLearningAvancado](./MachineLearningAvancado)

| # | Notebook | Tema |
|---|---|---|
| 9 | `9_AulaML_EngAtributos` | Engenharia de atributos |
| 10 | `10_AulaML_PCA` | Redução de dimensionalidade (PCA) |
| 11 | `11_AulaML_SelecaoAtributos` | Seleção de atributos |
| 12 | `12_AulaML_Cluster` | Clusterização |
| 13 | `13_AulaML_BestCluster` | Escolha do melhor número de clusters |
| 14 | `14_AulaML_Multilabel` | Classificação multilabel |
| 15 | `15_AulaML_AutoML` | AutoML |

### [DeepLearning](./DeepLearning)

| # | Notebook | Tema |
|---|---|---|
| 16 | `16_AulaDPL_MLP` | Perceptron de múltiplas camadas (MLP) |
| 17 | `17_AulaDPL_RNAKeras` | Redes neurais com Keras |
| 18 | `18_AulaDpl_CNN` | Redes neurais convolucionais (CNN) |
| 19 | `19_AulaDPL_LSTM` | Redes neurais recorrentes (LSTM) |
| 20 | `20_AulaDPL_DeteccaoObjetos` | Detecção de objetos |

## Como usar

Os notebooks foram escritos no Google Colab e podem ser abertos de duas formas:

1. **No Google Colab:** abra o notebook pelo GitHub (`Arquivo > Abrir notebook > GitHub`) e cole o link do repositório.
2. **Localmente:** clone o repositório e abra os notebooks no Jupyter ou no VS Code.

```bash
git clone https://github.com/wuldson-franco/Estudos-Machine-Learning-Inteligencia-Artificial.git
cd Estudos-Machine-Learning-Inteligencia-Artificial
pip install jupyter pandas numpy scikit-learn statsmodels matplotlib tensorflow
jupyter notebook
```

Cada notebook instala ou importa as bibliotecas de que precisa. Se algo falhar, verifique a primeira célula do notebook.

## Ordem de estudo sugerida

1. **MachineLearning**, na ordem numérica (1 a 8)
2. **MachineLearningAvancado** (9 a 15)
3. **DeepLearning** (16 a 20)

A numeração dos arquivos já segue essa ordem.

## Próximos passos

- [ ] NLP (processamento de linguagem natural)
- [ ] LLMs e IA Generativa
- [ ] RAG com LangChain e LangGraph
- [ ] Agentes de IA e MCP

## Observações

- Os notebooks são material de estudo e podem conter simplificações. Sugestões e correções são bem-vindas.
- O conteúdo acompanha cursos e livros que estou estudando atualmente;

## Contribuindo

Encontrou um erro ou tem uma sugestão? Abra uma *issue* ou envie um *pull request*.

## Autor

**Wuldson Franco**
GitHub: [@wuldson-franco](https://github.com/wuldson-franco)