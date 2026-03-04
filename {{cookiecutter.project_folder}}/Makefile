.DEFAULT_GOAL := help

help:  ## Показать доступные команды
	@echo "Доступные команды:"
	@echo "  make init    - Инициализация git, poetry, активация окружения"

init:  ## Инициализация git, poetry, активация окружения
	git init
	poetry install
	source $(poetry env info --path)/bin/activate