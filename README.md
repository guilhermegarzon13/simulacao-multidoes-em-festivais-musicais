# Simulação de Multidões: Modelo Continuum Crowds

Este repositório contém o código e a documentação da primeira metade do meu projeto de iniciação científica focado na simulação de movimento de pedestres utilizando o modelo matemático nomeado **Continuum Crowds**. 

O projeto traduz equações diferenciais e dinâmicas de fluidos em algoritmos computacionais para prever rotas, gargalos e o comportamento de multidões em diferentes cenários espaciais.

## Tecnologias e Implementação
A base deste projeto é a aplicação de métodos numéricos avançados. O desenvolvimento foi inteiramente realizado em **Python**, com forte dependência em cálculo matricial e resolução de equações diferenciais por métodos de diferenças finitas, utilizando:
* **NumPy:** Para manipulação eficiente de matrizes, cálculo de gradientes e operações numéricas de baixo nível.
* **scikit-fmm:** Implementação eficiente do *Fast Marching Method* para resolver a equação eikonal e calcular os campos de potencial e distâncias ótimas na malha da simulação.

## Código e Visualização
A implementação do modelo, a resolução numérica e as visualizações gráficas geradas pelas simulações estão estruturadas em um Jupyter Notebook. 

Você pode visualizar a execução do código e os resultados gerados clicando abaixo:
**[`Simulacao-Multidoes.ipynb`](./IC-Github/simulacao-multidoes.ipynb)**

## Fundamentação Teórica
Para entender a teoria por trás da implementação, incluindo a modelagem do custo de locomoção, o campo de densidade e a dedução final do modelo Continuum Crowds, consulte o **[Relatório de Iniciação Científica](./IC-Github/relatorio-iniciacao.pdf)**.
