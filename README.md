# Reconhecimento de Imagem

Projeto desenvolvido como acompanhamento do vídeo "Dois projetos práticos em 30 minutos usando Pythodo Canal DIO. *Título do vídeo* (link: https://www.youtube.com/watch?v=het1o0JEmT4)

## Descrição

Este projeto consiste em um sistema de reconhecimento de imagem que consegue identificar objetos/elementos em imagens. Ele utiliza técnicas de aprendizado de máquina / redes neurais para classificar/rotular imagens com base em um conjunto de dados.

## Funcionalidades

- Treinamento de modelo de reconhecimento de imagem a partir de dataset.
- Pré-processamento de imagens (redimensionamento, normalização, etc).
- Avaliação do modelo (métricas como acurácia, precisão, recall, etc).
- Carregamento de modelo treinado para fazer predições sobre novas imagens.

## Tecnologias / Ferramentas

- Linguagem: Python 3.x  
- Bibliotecas: `numpy`, `pandas`, `tensorflow` / `keras` ou `pytorch` (especifique qual usa)  
- Ferramentas auxiliares: OpenCV, PIL, etc  
- Ambiente de execução: local / GPU / Colab  

## Estrutura do Projeto

```text
.
├── data/                   # Conjunto de dados (imagens)
│   ├── train/              # Imagens de treino
│   ├── test/               # Imagens de teste
├── models/                 # Modelos treinados salvos
├── notebooks/              # Notebooks Jupyter com experimentos
├── src/                    # Código fonte
│   ├── preprocess.py       # Pré-processamento de imagens
│   ├── train.py            # Treinamento do modelo
│   ├── predict.py          # Script de predição
├── README.md               # Este arquivo
└── requirements.txt        # Lista de dependências



 • Desenvolver raciocínio lógico;

 • Praticar a resolução de problemas;

 • Consolidar os fundamentos de Python;

 • Registrar minha evolução na linguagem.

-> Site onde estão localizados os exercicios: https://exercicios.dunossauro.com/
