# 🚲🚚 YOLO Object Detection — Bicycle & Truck

## 📌 Descrição do Desafio

- Criar uma base de dados rotulada (ou usar COCO já rotulado).  
- Treinar a rede YOLO com pelo menos **duas classes** customizadas.  
- Testar e apresentar exemplos de detecção.  


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
