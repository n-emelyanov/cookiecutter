# {{cookiecutter.project_name}}

{{cookiecutter.description}}

## Структура проекта
```bash
.
├── config/                        # Конфигурационные файлы
│
├── data/                          # Данные проекта
│   ├── external/                  # Внешние данные от партнеров
│   ├── processed/                 # Обработанные данные для модели
│   └── raw/                       # Сырые данные из источников
│
├── docs/                          # Документация и справочники
│
├── models/                        # Модели машинного обучения
│   ├── params/                    # Параметры и конфиги моделей
│   └── final_model.cbm            # Финальная CatBoost модель
│
├── notebooks/                     # Основные исследовательские ноутбуки
│   ├── 1.Data_preparation.ipynb   # Подготовка и обработка данных
│   ├── 2.Eda.ipynb                # Разведочный анализ данных              
│   └── 3.Model.ipynb              # Разработка модели
│
├── reports/                       # Готовые отчеты и результаты
├── sql/                           # SQL запросы для выгрузки данных
├── utils/                         # Вспомогательные утилиты
│
├── Makefile                       # Автоматизация задач
├── poetry.lock                    # Зависимости Poetry (lock file)
├── pyproject.toml                 # Конфигурация проекта и зависимости
└── README.md                      # Описание проекта
```

## Быстрый старт (Poetry)

```bash
# 1. Установить зависимости
poetry install

# 2. Активировать окружение
source $(poetry env info --path)/bin/activate
```

