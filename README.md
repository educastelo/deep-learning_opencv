# OpenCV e Visão Computacional - Projetos PyImageSearch

Este repositório contém uma coleção de projetos práticos de OpenCV e visão computacional baseados nos tutoriais do blog [PyImageSearch](https://pyimagesearch.com/). Todos os exercícios aqui implementados seguem as técnicas e métodos ensinados neste excelente recurso para aprendizado de computer vision.

## 📋 Índice

- [Sobre](#sobre)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Categorias de Projetos](#categorias-de-projetos)
- [Requisitos](#requisitos)
- [Como Usar](#como-usar)
- [Projetos por Categoria](#projetos-por-categoria)

## 🎯 Sobre

Este repositório documenta minha jornada de aprendizado em visão computacional e processamento de imagens usando OpenCV. Cada diretório representa um tutorial específico do PyImageSearch, implementado e testado com diferentes cenários e imagens.

## 📁 Estrutura do Repositório

O repositório está organizado em 43 projetos numerados sequencialmente, cada um focando em aspectos específicos de visão computacional:

```
deep-learning_opencv/
├── 01_command_line_arguments/     # Argumentos de linha de comando
├── 02_opencv_examples/            # Exemplos básicos do OpenCV
├── 03_rotate_images/              # Rotação de imagens
├── 04_color_detection/            # Detecção de cores
├── 05_montages_opencv/            # Criação de montagens
├── 06_fast_color_transfer/        # Transferência rápida de cores
├── ...
├── 41_multiple_object_tracking_opencv/  # Rastreamento múltiplo com OpenCV
├── 42_multiple_object_tracking_dlib/    # Rastreamento múltiplo com dlib
└── 43_people_counter/             # Contador de pessoas
```

## 🔧 Requisitos

Para executar os projetos deste repositório, você precisará das seguintes dependências:

```bash
# Principais bibliotecas
pip install opencv-python
pip install imutils
pip install numpy
pip install argparse
pip install dlib
pip install scikit-learn

# Para projetos de deep learning
pip install tensorflow  # ou pytorch
```

## 🚀 Como Usar

Cada projeto pode ser executado independentemente. A maioria dos scripts aceita argumentos de linha de comando:

```bash
# Exemplo - Contador de formas
cd 01_command_line_arguments/
python shape_counter.py -i input_01.png -o output_01.png

# Exemplo - Detecção de faces
cd 17_face_detection/
python detect_faces.py --image image.jpg --prototxt deploy.prototxt --model res10_300x300_ssd_iter_140000.caffemodel

# Exemplo - YOLO Object Detection
cd 28_YOLO_object_detection/
python yolo.py -i images/example.jpg -y yolo-coco
```

## 📚 Projetos por Categoria

### 🔰 **Fundamentos de OpenCV**
- **01** - Argumentos de linha de comando
- **02** - Exemplos básicos do OpenCV
- **03** - Rotação de imagens
- **04** - Detecção de cores
- **05** - Montagens com OpenCV

### 🎨 **Processamento de Imagens**
- **06** - Transferência rápida de cores
- **07** - Centro de contornos
- **08** - Encontrando formas
- **09** - Pontos extremos
- **10** - Ordenação de contornos
- **11** - Detecção de formas
- **12** - Determinação de cores de objetos

### 📐 **Transformações Geométricas**
- **13** - Transformação de perspectiva com 4 pontos
- **14** - Scanner de documentos
- **15** - Scanner de folhas de resposta múltipla escolha

### 📹 **Vídeo e Webcam**
- **16** - Streaming de webcam
- **25** - Detecção de objetos em webcam com deep learning
- **31** - Rastreamento de bolas
- **32** - Rastreamento de movimento de objetos

### 👤 **Detecção e Reconhecimento Facial**
- **17** - Detecção de faces
- **18** - Detecção de marcos faciais
- **19** - Detecção de piscadas
- **20** - Reconhecimento facial
- **21** - Dataset customizado de reconhecimento facial
- **22** - Reconhecimento facial com OpenCV
- **23** - Alinhamento facial

### 🧠 **Deep Learning**
- **24** - Blobs com OpenCV
- **26** - Detecção de objetos baseada em deep learning
- **28** - Detecção de objetos YOLO
- **30** - Detecção de vivacidade (liveness detection)

### 🔍 **Detecção de Objetos**
- **29** - Detecção de gatos em imagens
- **33** - Detecção de pedestres
- **34** - Pirâmides de imagens
- **35** - Janelas deslizantes para detecção
- **36** - Supressão não-máxima para detecção
- **37** - Supressão não-máxima otimizada

### 📊 **Rastreamento e Monitoramento**
- **38** - Rastreamento simples de objetos
- **39** - Rastreamento de objetos com OpenCV
- **40** - Rastreamento de objetos com dlib
- **41** - Rastreamento múltiplo com OpenCV
- **42** - Rastreamento múltiplo com dlib
- **43** - Contador de pessoas

### ⚡ **Aplicações Especiais**
- **27** - Detector de sonolência

## 🎯 Principais Técnicas Implementadas

- **Processamento básico de imagens**: redimensionamento, rotação, filtros
- **Detecção de contornos**: identificação e análise de formas
- **Transformações geométricas**: perspectiva, afim, homografia
- **Detecção de características**: SIFT, SURF, ORB
- **Machine Learning**: classificação, clustering
- **Deep Learning**: redes neurais convolucionais, detecção de objetos
- **Rastreamento de objetos**: algoritmos de tracking
- **Processamento de vídeo**: análise temporal, detecção de movimento

## 🏆 Destaques

### Projetos Mais Complexos:
- **Scanner de Documentos (14)**: Implementa detecção automática de bordas e correção de perspectiva
- **Contador de Pessoas (43)**: Sistema completo de detecção, rastreamento e contagem bidirecional
- **YOLO Object Detection (28)**: Implementação do estado da arte em detecção de objetos
- **Sistema de Reconhecimento Facial (20-22)**: Pipeline completo desde captura até reconhecimento

### Técnicas Avançadas:
- Uso de modelos pré-treinados (MobileNet, YOLO, etc.)
- Integração de múltiplas bibliotecas (OpenCV, dlib, deep learning frameworks)
- Processamento em tempo real
- Otimizações de performance

## 📖 Recursos de Aprendizado

Este repositório serve como um guia prático para:
- **Iniciantes**: começando com projetos básicos e progredindo gradualmente
- **Intermediários**: explorando técnicas mais avançadas de visão computacional
- **Avançados**: implementando sistemas completos de computer vision

## 🔗 Referências

- [PyImageSearch Blog](https://pyimagesearch.com/)
- [OpenCV Documentation](https://docs.opencv.org/)
- [dlib Library](http://dlib.net/)

---

*Este repositório representa uma jornada de aprendizado contínuo em visão computacional. Cada projeto foi implementado com foco no entendimento das técnicas fundamentais e sua aplicação prática.*
