# 🚲🚚 YOLO Object Detection — Bicycle & Truck

## 📌 Descrição do Desafio

- Criar uma base de dados rotulada (ou usar COCO já rotulado).  
- Treinar a rede YOLO com pelo menos **duas classes** customizadas.  
- Testar e apresentar exemplos de detecção.  
- O objetivo final é reproduzir resultados como na imagem abaixo:

<p align="center">
  <img src="docs/example_target.jpg" alt="exemplo esperado" width="600">
</p>

---

## ⚙️ Tecnologias Utilizadas

- Ultralytics YOLOv8
- Google Colab (CPU)
- Dataset COCO 2017 (subset: bicycle, truck)
- Python 3.12, PyTorch

---

## 📊 Resultados
- Épocas: 20 (CPU)
- Modelo: yolov8n.pt (nano, pré-treinado no COCO)
- Métricas finais:
    Classe	Precisão (P)	Recall (R)	mAP50	mAP50-95
    bicycle	0.611	0.321	0.359	0.184
    truck	0.412	0.336	0.303	0.148
    média	0.511	0.328	0.331	0.166
<p align="center"> <img src="runs/detect/train/confusion_matrix.png" alt="Matriz de Confusão" width="500"><br> <em>Matriz de confusão (validação)</em> </p>
