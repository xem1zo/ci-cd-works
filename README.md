# CI/CD Works — GitHub Actions

Портфолио учебных работ по настройке CI/CD в GitHub Actions.

## 📊 Сводная таблица работ

| № | Работа | Язык | Репозиторий | CI Status | Actions |
|---|--------|------|-------------|-----------|---------|
| 1 | Первый Pipeline | YAML | [xem1zo-my-first-cicd](https://github.com/xem1zo/xem1zo-my-first-cicd) | ![CI](https://github.com/xem1zo/xem1zo-my-first-cicd/actions/workflows/hello.yml/badge.svg) | [Actions](https://github.com/xem1zo/xem1zo-my-first-cicd/actions) |
| 2 | Python CI | Python | [my-python-app](https://github.com/xem1zo/my-python-app) | ![CI](https://github.com/xem1zo/my-python-app/actions/workflows/ci.yml/badge.svg) | [Actions](https://github.com/xem1zo/my-python-app/actions) |
| 3 | Node.js CI | Node.js | [my-node-app](https://github.com/xem1zo/my-node-app) | ![CI](https://github.com/xem1zo/my-node-app/actions/workflows/ci.yml/badge.svg) | [Actions](https://github.com/xem1zo/my-node-app/actions) |
| 4 | Go CI | Go | [my-go-app](https://github.com/xem1zo/my-go-app) | ![CI](https://github.com/xem1zo/my-go-app/actions/workflows/ci.yml/badge.svg) | [Actions](https://github.com/xem1zo/my-go-app/actions) |
| 5 | Rust CI | Rust | [my-rust-app](https://github.com/xem1zo/my-rust-app) | ![CI](https://github.com/xem1zo/my-rust-app/actions/workflows/rust-ci.yml/badge.svg) | [Actions](https://github.com/xem1zo/my-rust-app/actions) |
| 6 | PHP CI | PHP | [my-php-app](https://github.com/xem1zo/my-php-app) | ![CI](https://github.com/xem1zo/my-php-app/actions/workflows/ci.yml/badge.svg) | [Actions](https://github.com/xem1zo/my-php-app/actions) |
| 7 | C++ CI | C++ | [my-cpp-app](https://github.com/xem1zo/my-cpp-app) | ![CI](https://github.com/xem1zo/my-cpp-app/actions/workflows/ci.yml/badge.svg) | [Actions](https://github.com/xem1zo/my-cpp-app/actions) |
| 8 | Java CI | Java | [hello-java](https://github.com/xem1zo/hello-java) | ![CI](https://github.com/xem1zo/hello-java/actions/workflows/ci.yml/badge.svg) | [Actions](https://github.com/xem1zo/hello-java/actions) |

## 🎯 Что в каждой работе

- **CI на GitHub Actions** — проверка кода при каждом push
- **Docker** — контейнеризация приложения
- **Артефакты** — сохранение Docker-образа для локального запуска
- **Тесты** — unit-тесты в каждом проекте

## 📝 Структура каждой работы

- `.github/workflows/ci.yml` — workflow GitHub Actions
- `src/` — исходный код
- `tests/` — unit-тесты
- `Dockerfile` — сборка контейнера
- `README.md` — описание работы

## ✅ Что реализовано

- ✅ Линтинг (flake8, ESLint, golangci-lint, clippy, PHP syntax check, clang-format)
- ✅ Тесты (pytest, Jest, go test, cargo test, PHPUnit, Google Test, JUnit 5)
- ✅ Сборка Docker-образа
- ✅ Сохранение артефактов (`actions/upload-artifact`)
- ✅ Matrix strategy (тестирование на нескольких версиях языка)
- ✅ Кэширование зависимостей
- ✅ Multi-stage Docker сборка

## 🔗 Полезные ссылки

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Docker Documentation](https://docs.docker.com/)

## 📝 Автор

**xem1zo** — учебные работы по CI/CD