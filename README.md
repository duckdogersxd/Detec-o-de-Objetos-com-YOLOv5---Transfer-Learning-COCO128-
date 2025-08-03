# 🧠 Detecção de Objetos com YOLOv5 - Transfer Learning (COCO128)

## 🎯 Objetivo do Projeto

Este projeto tem como objetivo aplicar **transfer learning com a rede YOLOv5** para realizar **detecção de objetos** em imagens, utilizando como base o conjunto de dados **COCO128**.

A proposta faz parte de um desafio prático de visão computacional, onde o modelo é treinado para detectar múltiplas classes, mas a análise é direcionada à capacidade de identificar com precisão duas categorias específicas.

---

## 🚀 Tecnologias e Ferramentas

- Google Colab
- Python 3.11
- PyTorch
- [YOLOv5 (Ultralytics)](https://github.com/ultralytics/yolov5)
- Dataset: [COCO128](https://github.com/ultralytics/yolov5/releases/download/v1.0/coco128.zip)

---

## 🧪 Descrição do Treinamento

- Dataset: COCO128 (128 imagens com 80 classes)
- Modelo base: `yolov5s.pt`
- Classes de interesse: `person` e `dog`
- Treinamento por 5 épocas com batch size 16
- Arquivo final de pesos salvo em `runs/train/yolov5_fullcoco/weights/best.pt`

---

## 📊 Resultados

O modelo treinado foi capaz de detectar com sucesso as classes em imagens de teste, apresentando bounding boxes e scores de confiança satisfatórios, mesmo com poucas épocas de treinamento.  

A detecção foi validada visualmente.

---

## 📌 Conclusão

Este projeto demonstra o uso prático de YOLOv5 com transfer learning para detecção de objetos, mesmo em ambientes computacionalmente limitados como o Google Colab. O uso do dataset COCO128 permite validação rápida e objetiva, com foco em classes específicas relevantes para o desafio.

---

## 📎 Licença

Este projeto está licenciado sob a Licença MIT.

