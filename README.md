# Introdução a Redes Neurais com Keras

Este repositório contém um **notebook educacional** voltado para a introdução prática a **Redes Neurais Artificiais** e **Deep Learning**, utilizando a biblioteca **Keras (TensorFlow)**. O material apresenta exemplos guiados de construção, compilação e treinamento de modelos neurais para **tarefas de classificação**, tanto com dados tabulares quanto com imagens.

O notebook foi desenvolvido com foco didático, desmistificando conceitos fundamentais de redes neurais por meio de exercícios práticos e incrementais.

---

## 🎯 Objetivos

- Introduzir os conceitos básicos de **Redes Neurais Artificiais**
- Apresentar o uso do modelo **Sequential** do Keras
- Construir e treinar:
  - Redes neurais totalmente conectadas (MLP)
  - Redes neurais convolucionais (CNN)
- Aplicar redes neurais em problemas reais de **classificação**

---

## 🧠 Conteúdos Abordados

### 🔹 1. Primeira Rede Neural (MLP)

Construção de uma rede neural simples para classificação de dados de sensores.

**Problema:**
- Classificação de movimentos humanos a partir de dados de smartwatch

**Características do conjunto de dados:**
- 16 atributos de entrada (features)
- 4 classes de saída:
  - Walking
  - Running
  - Sitting
  - Lying

**Arquitetura:**
- Modelo: `Sequential`
- Camada oculta: `Dense` com 8 neurônios
- Camada de saída: `Dense` com número de neurônios igual ao número de classes
- Função de ativação apropriada para classificação multiclasse

---

### 🔹 2. Deep Learning com CNN (Classificação de Imagens)

Construção de uma **Rede Neural Convolucional (CNN)** para reconhecimento de dígitos.

**Problema:**
- Leitura automática de placas / reconhecimento de dígitos

**Dados de entrada:**
- Imagens em tons de cinza
- Dimensão: 28 × 28 pixels
- 10 classes (dígitos de 0 a 9)

**Arquitetura:**
- `Conv2D` com 64 filtros (3×3)
- `MaxPooling2D`
- `Flatten`
- `Dense` com ativação *softmax*

---

## ⚙️ Tecnologias Utilizadas

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Jupyter Notebook**

---

## 📂 Estrutura do Repositório

```text
.
├── notebook.ipynb   # Notebook principal com os exercícios e explicações
└── README.md        # Documentação do projeto
