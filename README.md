## Projeto de Previsão de Aluguel de Bicicleta - README

Bem-vindo ao projeto de Previsão de Aluguel de Bicicleta! Este projeto tem como objetivo criar um modelo de previsão sofisticado utilizando aprendizado de máquina para prever o número de aluguéis de bicicletas com base em diversas características sazonais e meteorológicas.

## Processo de Discovery

Este projeto foi conduzido em várias etapas, incluindo exploração de dados, seleção e treinamento de modelos, e implantação do modelo final como um serviço web. Aqui está um resumo detalhado do processo de discovery:

### Exploração dos Dados

Exploramos um conjunto de dados históricos de aluguel de bicicletas fornecido pela Capital Bikeshare. Analisamos cuidadosamente as características sazonais, como o mês, dia da semana e ano, juntamente com as condições meteorológicas, como temperatura, umidade e velocidade do vento.
![image](https://github.com/RochaDenis/rentalbike_lab_AI900_Azure/assets/49164278/e5d95ab4-6c8c-4dc1-a73e-219bd5a3388e)

### Seleção e Treinamento do Modelo

Optamos por utilizar o aprendizado de máquina automatizado fornecido pelo Azure Machine Learning. Configuramos um trabalho de ML automatizado com várias configurações, incluindo tipo de tarefa de regressão e métrica primária de raiz do erro quadrático médio normalizado.

Selecionamos cuidadosamente os modelos permitidos, incluindo RandomForest e LightGBM, e configuramos limites para controlar o tempo e os recursos utilizados durante o treinamento.

### Avaliação do Modelo

Após o treinamento, avaliamos os modelos gerados pelo trabalho de ML automatizado. Analisamos métricas de desempenho, como o erro quadrático médio normalizado, e revisamos gráficos residuais e preditos para entender melhor o desempenho do modelo.

### Implantação do Modelo

Implantamos o melhor modelo treinado como um serviço web usando uma instância de contêiner do Azure. Testamos o serviço implantado com dados de entrada simulados para garantir que ele estivesse funcionando corretamente.

