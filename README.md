# Análise de Sobrevivência de Pacientes com Carcinoma Hepatocelular (HCC)

Este projeto utiliza técnicas de aprendizado de máquina para prever a sobrevivência de pacientes com carcinoma hepatocelular (HCC) com base em dados clínicos. O modelo final utiliza a técnica de oversampling ADASYN e um classificador Random Forest.

## Estrutura do Projeto

- `default.ipynb`: Jupyter Notebook contendo todo o código e análises.
- `hcc_dataset.csv`: Conjunto de dados utilizado no projeto.
- `random_forest_adasyn_model.pkl`: Modelo treinado salvo para previsões futuras.

## Pré-requisitos

Certifique-se de ter as seguintes bibliotecas instaladas:

- `numpy`
- `pandas`
- `scikit-learn`
- `imbalanced-learn`
- `joblib`
- `matplotlib`

Você pode instalar todas as dependências usando o seguinte comando:

pip install numpy pandas scikit-learn imbalanced-learn joblib matplotlib


## Uso

### 1. Carregar e Pré-processar os Dados

O conjunto de dados `hcc_dataset.csv` é carregado e pré-processado para tratar valores ausentes, normalizar os dados e codificar a variável alvo.

### 2. Aplicar ADASYN

Utilizamos a técnica de oversampling ADASYN para lidar com o desbalanceamento de classes, gerando novas amostras sintéticas para a classe minoritária.

### 3. Treinar o Modelo

Treinamos um modelo Random Forest com os dados balanceados.

### 4. Avaliar o Modelo

Avaliamos o modelo utilizando métricas como exatidão, relatório de classificação e matriz de confusão.

### 5. Salvar o Modelo

Salvamos o modelo treinado para uso futuro.

### 6. Fazer Previsões

Utilizamos uma função para fazer previsões em novos dados utilizando o modelo salvo.


## Contribuição

Sinta-se à vontade para contribuir com este projeto. Você pode abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


