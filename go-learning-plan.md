
# 🐹 Golang Learning Plan

## 🎯 Цілі

- Вивчити синтаксис Go
- Розробляти CLI-інструменти
- Побудувати прості мікросервіси
- Практикуватися через задачі
- Працювати з паралелізмом та мережею

---

## 📆 Тижневий розклад (10 год/тиждень)

| День | Тематика                           | Час | Формат         |
|------|------------------------------------|------|----------------|
| Пн   | Синтаксис Go: змінні, типи, if     | 1.5h | Книга + приклади |
| Вт   | Функції, масиви, слайси, мапи      | 1.5h | Задачі         |
| Ср   | Структури, методи, інтерфейси      | 2h   | Відео + практика |
| Чт   | Goroutines, канали                 | 2h   | Стаття + приклади |
| Пт   | Створення CLI-інструменту          | 1.5h | Mini-проєкт    |
| Сб   | Рефакторинг і тести                | 1h   | Практика       |
| Нд   | Відпочинок / Рев’ю + нотатки       | 0.5h | Повторення     |

---

## 🏁 Тижневі спринти

### Тиждень 1 — Основи Go
- [ ] Встановити Go + редактор
- [ ] Tour of Go
- [ ] Вивчити типи, функції, слайси, мапи
- [ ] 10 вправ (наприклад: сортування, фільтрація, обробка рядків)

### Тиждень 2 — Структури та конкурентність
- [ ] Структури, методи, інтерфейси
- [ ] Goroutines, канали
- [ ] Скрипт, що паралельно обробляє файли або запити

### Тиждень 3 — CLI-інструменти
- [ ] Вивчити [cobra](https://github.com/spf13/cobra) або [urfave/cli](https://github.com/urfave/cli)
- [ ] Зробити CLI-проєкт (`jsonlint`, `kube-analyzer`, `aws-cost-viewer`)
- [ ] Додати флаги, логування, unit-тести

### Тиждень 4 — Мікросервіси
- [ ] net/http, encoding/json
- [ ] Побудувати REST API (`GET /health`, `POST /item`)
- [ ] Використати `gin`, `echo`, або `fiber`
- [ ] Dockerfile + запуск у контейнері

### Тиждень 5 — Обробка файлів, логування, фреймворки
- [ ] Обробка файлів (`os`, `io/ioutil`, `filepath`)
- [ ] Робота з флагами (`flag`, `cobra`)
- [ ] Стандарти логування (`log`, `zap`, `logrus`)
- [ ] Інструмент для агрегації JSON/YAML + логування
- [ ] CLI-параметри: `--verbose`, `--output`

### Тиждень 6 — Бази даних та API
- [ ] `database/sql`, `sqlx` (SQLite/PostgreSQL)
- [ ] Підключення до зовнішніх API (`http.Client`)
- [ ] Клієнт до GitHub API або ін.
- [ ] Кешування відповідей (map або BoltDB)
- [ ] Паралельне звернення через goroutines

### Тиждень 7 — CI/CD, Docker, Тестування
- [ ] `testing`, `testify` для unit-тестів
- [ ] CI (GitHub Actions / GitLab CI): тест + lint + vet
- [ ] Dockerfile + Makefile
- [ ] Контейнеризація CLI-утиліти

### Тиждень 8 — Pet-проєкт і K8s
- [ ] Обрати тему pet-проєкту
- [ ] Структура `cmd/`, `internal/`, `pkg/`
- [ ] Написати Helm-чарт або YAML
- [ ] Запуск у kind/EKS
- [ ] Інтеграційні тести

---

## 📚 Рекомендовані ресурси

### Курси та інтерактивні ресурси:
- [Tour of Go](https://go.dev/tour/welcome/1)
- [Exercism Go Track](https://exercism.org/tracks/go)
- [Go by Example](https://gobyexample.com/)
- [Gophercises](https://gophercises.com/)
- [Learn Go with Tests](https://quii.gitbook.io/learn-go-with-tests/)
- [Go Patterns](https://github.com/tmrts/go-patterns)

### Відео:
- [JustForFunc](https://www.youtube.com/playlist?list=PL64wiCrrxh4Jisi7OcCJIUpguV_f5jGnZ)
- [Golang Dojo](https://golangdojo.com/)

---

## 💡 Pet-проєкти

| Назва                | Опис                                                      |
|----------------------|-----------------------------------------------------------|
| `json-inspector`     | CLI утиліта для перевірки та форматування JSON            |
| `aws-bill-summary`   | API сервер + CLI, що читає з AWS Cost Explorer            |
| `kube-secret-audit` | Інструмент для перевірки Kubernetes Secret-об'єктів       |
| `git-reminder-bot`   | Сервіс, який надсилає Slack/Telegram нотифікації про PR   |
| `s3-backup-cli`      | Клієнт для архівації та відправки файлів у S3             |

---

## ✅ To-Do стартовий

- [ ] Встановити Go → https://go.dev/doc/install
- [ ] Tour of Go → https://go.dev/tour/welcome/1
- [ ] Створити Git-репозиторій `go-learn`
- [ ] Написати перший `main.go` з аргументами з CLI
- [ ] Виконати 10 задач з Exercism
- [ ] Вивчити приклади з Gophercises

---

_Успіхів!_
