# Инструментальные средства разработки ПО

<div align="center">

<img src="https://play-lh.googleusercontent.com/mArlt7B_0PsBnRIIECGXcWn3xdql8eoFM7ObWsQmcKplMLVJjWr0lxh4Y2PF1IRloJC1xBsu2_Ol-F_nbqDx=w240-h480-rw" alt="НКЭиВТ" width="120"/>

**Репозиторий практических работ по дисциплине «Инструментальные средства разработки программного обеспечения»**

[НКЭиВТ](http://www.nke.ru/) — Новосибирский колледж электроники и вычислительной техники

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-68217A?style=flat&logo=windows&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Wiki](https://img.shields.io/badge/Wiki-Documentation-blue)
[![Status](https://img.shields.io/badge/status-in%20progress-yellow)](#)
[![Works](https://img.shields.io/badge/works-4%20of%2015-brightgreen)](#)
</div>

---
<details>
<summary><b>Оглавление</b> (нажмите, чтобы развернуть)</summary>

- [О репозитории](#о-репозитории)
- [Список практических работ](#список-практических-работ)
- [Статус выполнения](#статус-выполнения)
- [Работа с репозиторием](#работа-с-репозиторием)
  - [Клонирование без субмодулей](#клонирование-репозитория-без-субмодулей)
  - [Клонирование с субмодулями](#клонирование-репозитория-вместе-со-всеми-субмодулями)
  - [Обновление субмодулей](#обновление-субмодулей)
  - [Клонирование Wiki](#клонирование-wiki)
  - [Полезные команды](#полезные-команды)
- [Структура репозитория](#️структура-репозитория)
- [Требования](#️требования)
- [Авторы](#авторы)

</details>

---

## О репозитории

Данный репозиторий — это хранилище всех практических работ по предмету «Инструментальные средства разработки программного обеспечения». Каждая практическая работа вынесена в отдельный git-субмодуль со своим репозиторием, что позволяет вести независимую разработку и версионирование каждой задачи.

Репозиторий покрывает полный курс из 15 практических работ: от классических паттернов проектирования (GoF) на C# до разработки полноценных WPF-приложений с базой данных SQLite.

> Все отчёты, схемы и примеры выполнения доступны в [Wiki](https://github.com/Nu-K2/InstrumentalTools/wiki) репозитория.

## Список практических работ

### Паттерны проектирования (C#)

| № | Тема | Ссылка | Отчёт |
|---|---|---|---|
| 1 | Реализация основных шаблонов на примере паттерна «Одиночка» в C# | ./practical-01-singleton | [Wiki]() |
| 2 | Реализация порождающего паттерна «Абстрактная фабрика» в C# | ./practical-02-abstract-factory | [Wiki]() |
| 3 | Реализация структурного паттерна «Адаптер» в C# | ./practical-03-adapter | [Wiki]() |
| 4 | Реализация поведенческого паттерна «Шаблонный метод» в C# | ./practical-04-template-method | [Wiki]() |

### WPF и C#

| № | Тема | Ссылка | Отчёт |
|---|---|---|---|
| 5 | Разработка приложения с использованием текстовых компонентов в WPF и C# | ./practical-05-wpf-text-components | [Wiki]() |
| 6 | Разработка приложения с несколькими формами в WPF и C# | ./practical-06-wpf-multiple-forms | [Wiki]() |
| 7 | Разработка приложения с невизуальными компонентами в WPF и C# | ./practical-07-wpf-nonvisual-components | [Wiki]() |
| 8 | Разработка игрового приложения в WPF и C# | ./practical-08-wpf-game-app | [Wiki]() |

### Оптимизация, рефакторинг и UI

| № | Тема | Ссылка | Отчёт |
|---|---|---|---|
| 9 | Оптимизация и рефакторинг кода в WPF и C# (базовый уровень) | ./practical-09-refactoring-basic | [Wiki]() |
| 10 | Оптимизация и рефакторинг кода в WPF и C# (повышенный уровень) | ./practical-10-refactoring-advanced | [Wiki]() |
| 11 | Разработка интерфейса пользователя в WPF и C# (базовый уровень) | ./practical-11-ui-basic | [Wiki]() |
| 12 | Разработка интерфейса пользователя в WPF и C# (повышенный уровень) | ./practical-12-ui-advanced | [Wiki]() |

### Работа с базой данных

| № | Тема | Ссылка | Отчёт |
|---|---|---|---|
| 13–15 | Работа с локальной базой данных SQLite в WPF и C# | ./practical-13-15-sqlite | [Wiki]() |

---
## Статус выполнения

| № | Работа | Статус |
|---|---|---|
| 1 | Одиночка | ✅ |
| 2 | Абстрактная фабрика | ✅ |
| 3 | Адаптер | ✅|
| 4 | Шаблонный метод | ✅  |
| 5 | WPF: текстовые компоненты | 🚧  |
| 6 | WPF: несколько форм | 🚧 |
| 7 | WPF: невизуальные компоненты | 🚧  |
| 8 | WPF: игровое приложение | 🚧  |
| 9 | Рефакторинг (базовый) | 🚧  |
| 10 | Рефакторинг (продвинутый) | 🚧 |
| 11 | UI (базовый) | 🚧  |
| 12 | UI (продвинутый) | 🚧|
| 13–15 | SQLite + WPF | 🚧  |

> Легенда: ✅ выполнено · 🚧 в работе · ❌ не сдано

---
## Работа с репозиторием

### Клонирование репозитория (без субмодулей)

```bash
git clone https://github.com/Nu-K2/InstrumentalTools.git
```

В этом случае папки практических работ будут пустыми, пока вы не инициализируете субмодули.

### Клонирование репозитория вместе со всеми субмодулями

```bash
git clone --recurse-submodules https://github.com/Nu-K2/InstrumentalTools.git
```

Если репозиторий уже склонирован без субмодулей:

```bash
git submodule update --init --recursive
```

### Обновление субмодулей

Подтянуть последние изменения во всех субмодулях:

```bash
git submodule update --remote --merge
```

Или для конкретного субмодуля:

```bash
git submodule update --remote practical-01
```

### Клонирование Wiki

Wiki репозитория хранится как отдельный git-репозиторий:

```bash
git clone https://github.com/Nu-K2/InstrumentalTools.wiki.git
```


> Домашняя страница Wiki: https://github.com/Nu-K2/InstrumentalTools/wiki

### Полезные команды

| Команда | Назначение |
|---|---|
| `git submodule status` | Показать состояние субмодулей |
| `git submodule foreach git pull origin main` | Обновить все субмодули до последних изменений |
| `git pull --recurse-submodules` | Обновить основной репозиторий и субмодули |
| `git clone --recurse-submodules --depth 1 <url>` | Быстрый клон без истории |

---

## Структура репозитория

```
InstrumentalTools/
├── README.md                          # ← вы здесь
├── .gitmodules                        # конфигурация субмодулей
├── practical-01-singleton/            # ПР №1  — паттерн «Одиночка»
├── practical-02-abstract-factory/     # ПР №2  — «Абстрактная фабрика»
├── practical-03-adapter/              # ПР №3  — «Адаптер»
├── practical-04-template-method/      # ПР №4  — «Шаблонный метод»
├── practical-05-wpf-text-components/  # ПР №5  — текстовые компоненты
├── practical-06-wpf-multiple-forms/   # ПР №6  — несколько форм
├── practical-07-wpf-nonvisual-comp/   # ПР №7  — невизуальные компоненты
├── practical-08-wpf-game-app/         # ПР №8  — игровое приложение
├── practical-09-refactoring-basic/    # ПР №9  — рефакторинг (базовый)
├── practical-10-refactoring-advanced/ # ПР №10 — рефакторинг (продвинутый)
├── practical-11-ui-basic/             # ПР №11 — UI (базовый)
├── practical-12-ui-advanced/          # ПР №12 — UI (продвинутый)
└── practical-13-15-sqlite/            # ПР №13–15 — SQLite + WPF
```


---

## 🛠️ Требования

- [.NET SDK](https://dotnet.microsoft.com/download) 6.0+
- Visual Studio 2022 / Rider / VS Code с расширением C#
- Windows 10/11 (для WPF-проектов)
- Git 2.13+

---
# Авторы
<table> <tr> <td align="center"> <a href="https://github.com/krill810"> <img src="https://github.com/krill810.png" width="100" alt="Бедарева Софья"/><br/> <sub><b>Бедарева Софья</b></sub> </a><br/> <a href="https://github.com/krill810">@krill810</a> </td> <td align="center"> <a href="https://github.com/Nu-K2"> <img src="https://github.com/Nu-K2.png" width="100" alt="Сторожева Анна"/><br/> <sub><b>Сторожева Анна</b></sub> </a><br/> <a href="https://github.com/Nu-K2">@Nu-K2</a> </td> </tr> </table>

---
