# Treinamento de Redes Neurais com o Dataset MNIST 

Este repositório contém o código do trabalho da disciplina de Aprendizado de Máquina do DCC-UFMG. O objetivo é treinar uma rede neural no dataset MNIST, explorando diferentes configurações de hiperparâmetros para otimizar o desempenho.

## Estrutura do Projeto 📁

- **`MNISTDataset`**: Classe para carregar e preparar o dataset MNIST.
- **`NeuralNetwork`**: Rede neural simples com uma camada oculta.
- **Funções de Treinamento e Avaliação**: Funções para treinar, avaliar e visualizar os resultados.

## Hiperparâmetros Testados 🔍

- **Unidades na Camada Oculta**: 25, 50, 100
- **Taxa de Aprendizado**: 0.5, 1, 10
- **Tamanho do Batch**: 1, 10, 50, 5000

## Melhores Resultados 🏅

- **Unidades na Camada Oculta**: 50
- **Taxa de Aprendizado**: 1
- **Tamanho do Batch**: 10
- **Perda de Validação**: 0.3917
- **Acurácia de Validação**: 0.8933
