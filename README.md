# Система «Численные методы линейной алгебры»

## Описание системы
Система предоставляет веб-интерфейс для выполнения численных вычислений линейной алгебры:
- Решение систем линейных уравнений.
- Вычисление определителей, обратных матриц.
- Нахождение собственных значений и векторов.
- Визуализация результатов и генерация отчетов.

## Диаграммы архитектуры (C4-модель)

### Системный контекст (C4 Level 1)
![System Context Diagram](docs/c4-diagrams/system-context.png)

### Контейнеры (C4 Level 2)
![Container Diagram](docs/c4-diagrams/container-diagram.png)

### Компоненты Backend API (C4 Level 3)
![Component Diagram](docs/c4-diagrams/component-diagram.png)

## OpenAPI-спецификация
Спецификация API доступна по ссылке: [openapi.yaml](docs/api-specification/openapi.yaml)

## Инструкция по запуску скрипта генерации документации

### 1. Убедитесь, что установлены:
- Java 11+
- Docker
- Git

### 2. Клонируйте репозиторий:
```bash
git clone <URL-репозитория>
cd numerical-linear-algebra-system

