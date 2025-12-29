# Semantic Evaluation of Ukrainian Student Answers

Система автоматизованого оцінювання текстових відповідей студентів українською мовою на основі семантичної схожості.

## Огляд проєкту
Даний проєкт розробляється в рамках курсової роботи. Метою є створення інструменту, що порівнює відповідь студента з еталоном викладача, використовуючи векторні представлення тексту (embeddings) замість простого пошуку ключових слів.

## Cтек 
* **Language:** Python 3.10+
* **ML Framework:** PyTorch, Sentence-Transformers
* **NLP Models:** Multilingual BERT / RoBERTa (Hugging Face)
* **API:** FastAPI
* **Infrastructure:** Docker

## Структура проєкту
* `data/` — JSON-файли з питаннями та еталонними відповідями.
* `src/` — Вихідний код (логіка моделі, препроцесинг, API).
* `notebooks/` — Дослідження та експерименти з моделями.
* `docs/` — Документація та пояснювальна записка до курсової.

## Встановлення та запуск
1. Клонувати репозиторій:
   ```bash
   git clone [https://github.com/ВАШ_ЛОГІН/NLP-Student-Grading.git](https://github.com/ВАШ_ЛОГІН/NLP-Student-Grading.git)