# Criando um Modelo de Previsão no Azure Machine Learning

Este documento descreve o processo de criação de um modelo de previsão utilizando o **Azure Machine Learning (AML)**.

## Passo a Passo

### 1. Criar um Workspace no Azure Machine Learning
1. Acesse o portal do **Azure Machine Learning**.
2. Navegue até **Workspaces** e clique em **Criar um novo workspace**.
3. Preencha os detalhes como nome, região e grupo de recursos.
4. Clique em **Criar** e aguarde a implantação.

### 2. Criar e Treinar um Modelo
1. No AML Studio, acesse **Designer** ou **Notebooks**.
2. Selecione ou carregue um conjunto de dados.
3. Utilize bibliotecas como **scikit-learn**, **TensorFlow** ou **PyTorch** para construir seu modelo.
4. Treine o modelo e avalie seu desempenho.
5. Salve o modelo treinado em um formato adequado (ex: `.pkl`, `.onnx`).

### 3. Registrar o Modelo
1. Acesse a guia **Modelos** no AML Studio.
2. Clique em **Registrar modelo**.
3. Envie o arquivo do modelo treinado.
4. Preencha as informações necessárias e clique em **Registrar**.



