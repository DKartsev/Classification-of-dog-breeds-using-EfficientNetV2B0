# Classification-of-dog-breeds-using-EfficientNetV2B0
---

## 📘 Описание проекта
В этом проекте реализована **нейросеть для классификации пород собак** на основе предобученной модели **EfficientNetV2B0**.  
Используется датасет [**Stanford Dogs Dataset**](http://vision.stanford.edu/aditya86/ImageNetDogs/), включающий изображения собак **120 пород**.

Модель обучается в два этапа:
1. Обучение верхних слоёв с замороженной базовой частью;
2. Разморозка и дообучение верхних слоёв для повышения точности.

Проект реализован в **Google Colab** с использованием **Keras 3.10**.

---

## 🧭 Навигация

- [Импорт библиотек](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=W_c83WiEYMXl&line=1&uniqifier=1)
- [Набор данных](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=kAMOZDndYTvk)
- [Фильтрация поврежденных изображений](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=sfagDvsRYvWE)
- [Генерация датасета](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=HuSN3_JQZB9v)
- [Аугментация данных](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=Rs2Y9sZkZafM)
- [Предварительная обработка данных](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=HZfKRs9ZZhiC)
- [Вспомогательные функции](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=uSZxEN9zZq-p)
- [Перенос обучения](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=7He7eaMya-94&line=1&uniqifier=1)
- [Обучение с заморозкой базовой модели](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=XAvPV0-k4BhZ&line=1&uniqifier=1)
- [Разморозка весов](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=_PZyRx5Cz3S0&line=1&uniqifier=1)
- [Проверка модели](https://colab.research.google.com/drive/1WmjPLnJ_NZwO-6AEO0Uhyzi2YTw1veKJ#scrollTo=w2DYrcAxz7z3&line=1&uniqifier=1)


[Автор](https://github.com/DKartsev)
---