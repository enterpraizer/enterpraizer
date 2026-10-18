## Никита Радченко

Начинающий ML-инженер, студент БГУИР (направление «Искусственный интеллект»).
Довожу модели до работающего сервиса: данные → обучение → экспорт в ONNX → API → Docker.

### Проекты

| Проект | Что внутри |
| --- | --- |
| [**Wardrobe AI**](https://github.com/enterpraizer/Wardrobe-AI) | AI-стилист по фото одежды. ViT-классификатор атрибутов, сиамский трансформер сочетаемости вещей (ROC-AUC 0.84 на валидации), инференс в ONNX. 9 микросервисов: FastAPI, Go, Kafka, Qdrant; MLflow, DVC, Airflow |
| [**MovieMatch**](https://github.com/enterpraizer/MovieMatch) | Рекомендации фильмов тремя способами: Two-Tower по оценкам (MovieLens), гибридный семантический поиск (sentence-transformers + pgvector + полнотекстовый поиск, слияние через RRF), подбор по эмоции с селфи (ViT, ONNX) |
| [**CloudIaaS**](https://github.com/enterpraizer/cloudiaas-backend) | Мультитенантная IaaS-платформа: VM, сети, квоты. LLM (Gemini) рекомендует конфигурацию VM по текстовому описанию и предлагает оптимизации по метрикам: few-shot, ответ в JSON, проверка квот в коде, фолбэк. FastAPI, Celery, PostgreSQL, Redis · [фронтенд](https://github.com/enterpraizer/cloudiaas-frontend) |
| [**Football Match Prediction**](https://github.com/enterpraizer/football-match-prediction) | Прогноз футбольных матчей: модели CatBoost, мультиагентный пайплайн и текстовый отчёт от LLM в Telegram-боте |
| [**YOLO на Raspberry Pi 5**](https://github.com/enterpraizer/Practice) | YOLOv11n на CPU и на ускорителе Hailo-8L: модель скомпилирована и квантована в int8 самостоятельно, ускорение ~11× (3.6 → 38.8 FPS) |
| [**CookFlow**](https://github.com/enterpraizer/cookflow) | Веб-приложение интерактивных рецептов на Flask + SQLAlchemy: REST API, миграции, тесты |

### Стек

- **ML:** Python, PyTorch / Lightning, scikit-learn, CatBoost, LightGBM, sentence-transformers, ONNX, YOLO
- **Сервисы:** FastAPI, Flask, PostgreSQL + pgvector, Redis, Celery, Kafka, Qdrant
- **MLOps и инфраструктура:** Docker, MLflow, DVC, Airflow, GitHub Actions, Git, Linux
- **LLM:** OpenAI-совместимые API (OpenRouter), Google Gemini

### Контакты

Telegram: [@nik_nigh](https://t.me/nik_nigh)
