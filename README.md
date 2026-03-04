# 🚀 CI/CD Template

Шаблон для учебного задания по GitHub Actions CI/CD.

## 🏗️ CI/CD Pipeline

| Этап | Описание | Label |
|------|----------|-------|
| 1 | Тестирование | `test-passed` |
| 2 | Проверка безопасности | `sec-passed` |
| 3 | Обновление версии | `vX.X.X` |
| 4 | Генерация changelog | `changelog` |
| 5 | Публикация в Docker Hub | `dockerhub` |
| 6 | Уведомление в Telegram | - |
| 7 | Деплой в PROD | `PROD` |
| 8 | Создание релиза | - |

## 🚀 Быстрый старт

1. Форкните этот репозиторий
2. Настройте секреты (см. INSTRUCTION.md)
3. Создайте PR и наблюдайте за пайплайном!

## 📚 Документация

Смотрите `INSTRUCTION.md` для подробной инструкции.

## 🐳 Docker

```bash
docker pull yourname/yourproject:latest
docker-compose up -d
"# KT2" 
