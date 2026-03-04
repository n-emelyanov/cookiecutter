.DEFAULT_GOAL := help

help:  ## Показать доступные команды
	@echo "Доступные команды:"
	@echo "  make init    - Инициализация git, poetry, активация окружения"

init:  ## Инициализация git, poetry, активация окружения
	git init
	poetry install
	/bin/bash -c "source $$(poetry env info --path)/bin/activate && exec bash"
	@echo "✅ Проект инициализирован!"