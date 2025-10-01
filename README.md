🧠 Projeto de Classificação de Imagens com Redes Neurais
📋 Sobre o Projeto
Este repositório contém implementações completas de redes neurais para classificação de imagens, desde modelos básicos até sistemas avançados com transfer learning. Desenvolvido como parte de estudos em pós-graduação.

🏗️ Estrutura do Projeto
1. 🔢 Classificador MNIST
Função: Reconhece dígitos manuscritos de 0 a 9

Arquitetura: Rede neural simples com 3 camadas (512 → 256 → 10 neurônios)

Dataset: MNIST - 70,000 imagens de dígitos

Performance: ~98% de acurácia

2. 🖼️ CNN para CIFAR-10
Função: Classifica objetos coloridos em 10 categorias

Arquitetura: Rede convolucional com 3 camadas

Dataset: CIFAR-10 - aviões, carros, pássaros, etc.

Complexidade: Mais desafiadora por ser com imagens coloridas

3. 🌐 Sistema de Transfer Learning com VGG16
Função: Classifica imagens da web em 1.000 categorias

Modelo: VGG16 pré-treinado no ImageNet

Funcionalidades:

Download automático de imagens

Pré-processamento inteligente

Top 5 previsões com probabilidades

Análise estatística completa

4. 🔬 Comparação de Arquiteturas CNN
Objetivo: Analisar impacto de diferentes designs

Modelos Comparados:

Kernel 3x3 + Pooling 2x2 (padrão)

Kernel 4x4 + Pooling 3x3 (modificado)

Saída: Gráficos comparativos e métricas

5. 🎭 Sistema Avançado de Reconhecimento Facial
Função: CNN profunda para características faciais

Arquitetura: 4 camadas convolucionais (64→128→256→512)

Técnicas: Batch Normalization, Dropout, Early Stopping

Funcionalidades:

Matriz de confusão

Curvas de aprendizado

Visualização de filtros

Relatório de classificação

🛠️ Tecnologias Utilizadas
TensorFlow/Keras - Framework de deep learning

Matplotlib/Seaborn - Visualizações e gráficos

NumPy - Processamento numérico

PIL/OpenCV - Manipulação de imagens

Requests - Download de imagens web

📊 Resultados e Métricas
O projeto inclui análise completa de:

Acurácia em conjuntos de teste

Curvas de aprendizado (loss e accuracy)

Matrizes de confusão

Comparação estatística entre modelos

Visualização de características aprendidas

🎯 Aplicações Práticas
Reconhecimento de objetos em imagens

Classificação de características visuais

Sistemas de recomendação baseados em imagem

Prototipagem rápida de modelos de visão computacional
