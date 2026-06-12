# Advanced Calculator – 7 Languages

Мощный многофункциональный калькулятор с графическим/консольным интерфейсом, историей вычислений, поддержкой тригонометрии, логарифмов, степеней, сменой темы, горячими клавишами и копированием результата. Реализован на 7 языках программирования:

- **Python** (Tkinter GUI + история в JSON)
- **Go** (CLI с цветным выводом и продвинутым парсером)
- **Rust** (CLI с обработкой ошибок и история)
- **C#** (Windows Forms с темой)
- **JavaScript** (Node.js CLI с mathjs)
- **TypeScript** (Web с локальным хранилищем)
- **Java** (Swing с историей)

## Возможности

- Арифметические операции: `+ - * /`
- Тригонометрия: `sin`, `cos`, `tan` (в радианах)
- Логарифмы: `log` (base 10), `ln` (natural)
- Корень квадратный: `sqrt`
- Возведение в степень: `^` или `**`
- История последних 20 вычислений (сохраняется в файл/локальное хранилище)
- Тёмная / светлая тема (в GUI версиях)
- Горячие клавиши: `Enter` = равно, `Esc` = очистка, `Backspace` = удалить
- Копирование результата в буфер обмена
- Обработка ошибок (деление на ноль, неверный ввод)

## Запуск

| Язык | Команда | Требования |
|------|---------|-------------|
| Python | `cd python && python calculator.py` | `tkinter` (встроен) |
| Go | `cd go && go run calculator.go` | Go 1.21+ |
| Rust | `cd rust && cargo run` | Rust 1.70+ |
| C# | `cd csharp && dotnet run` | .NET 8.0+ |
| JavaScript | `cd js && node calculator.js` | Node.js 18+, `npm install mathjs` |
| TypeScript | `cd ts && npx ts-node calculator.ts` | TypeScript, `mathjs` |
| Java | `cd java && javac Calculator.java && java Calculator` | JDK 11+ |

## Пример интерфейса (Python)
