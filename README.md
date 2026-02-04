# Face Detector

Проект для детекции лиц в реальном времени с веб-камеры с использованием OpenCV и Haar Cascade.

## Требования

- Python 3.7+
- Веб-камера

## Установка

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/sneeppy/face-detector.git
   cd face-detector
   ```

2. Создайте виртуальное окружение (рекомендуется):
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # Linux/macOS
   source venv/bin/activate
   ```

3. Установите зависимости:
   ```bash
   pip install -r requirements.txt
   ```

## Запуск

```bash
python main.py
```

Программа откроет окно с видео с камеры и будет рисовать зелёные прямоугольники вокруг обнаруженных лиц. Для выхода нажмите клавишу **Q**.

## Технологии

- **OpenCV** — компьютерное зрение и работа с видео
- **Haar Cascade** — классификатор для детекции лиц (встроен в OpenCV)

