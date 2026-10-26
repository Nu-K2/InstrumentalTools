# Инструментальные средства

[![Status](https://img.shields.io/badge/status-in%20progress-yellow)](#)
[![Works](https://img.shields.io/badge/works-4%20of%2015-brightgreen)](#)

Репозиторий для хранения практических работ по предмету **«Инструментальные средства»** (Инструментальные средства разработки программного обеспечения).

Работы выполняются студентами **НКЭиВТ** — Новосибирского колледжа электроники и вычислительной техники:

- **Бедарева Софья** — GitHub: [@krill810](https://github.com/krill810)
- **Сторожева Анна** — GitHub: [@Nu-K2](https://github.com/Nu-K2)

> 🚧 **Статус:** репозиторий находится в стадии активного выполнения.
> На данный момент готовы практические работы **№1–4 из 15**.

## 📖 Документация

Полные описания заданий, требования к приложениям и критерии оценки находятся в
**[wiki репозитория](https://github.com/Nu-K2/InstrumentalTools/wiki)**.
Навигация по работам — в [`_Sidebar.md`](https://github.com/Nu-K2/InstrumentalTools/wiki/_Sidebar).

## 📚 Практические работы

Каждая работа вынесена в отдельный репозиторий и подключена к этому репозиторию как
**git-подмодуль**. В README каждого подмодуля приведены пояснения к выполненному коду
и описание реализации задания.

| № | Статус | Задание (wiki) | Реализация (подмодуль) |
|:-:|:------:|----------------|------------------------|
| 1 | ✅ Выполнено | [Практическая работа №1](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№1) | [`practical-01`](./practical-01) |
| 2 | ✅ Выполнено | [Практическая работа №2](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№2) | [`practical-02`](./practical-02) |
| 3 | ✅ Выполнено | [Практическая работа №3](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№3) | [`practical-03`](./practical-03) |
| 4 | ✅ Выполнено | [Практическая работа №4](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№4) | [`practical-04`](./practical-04) |
| 5 | 🚧 В работе | [Практическая работа №5](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№-5) | [`practical-05`](./practical-05) |
| 6 | 🚧 В работе | [Практическая работа №6](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№-6) | [`practical-06`](./practical-06) |
| 7 | 🚧 В работе | [Практическая работа №7](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№-7) | [`practical-07`](./practical-07) |
| 8 | 🚧 В работе | [Практическая работа №8](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№-8) | [`practical-08`](./practical-08) |
| 9 | 🚧 В работе | [Практическая работа №9](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№-9) | [`practical-09`](./practical-09) |
| 10 | 🚧 В работе | [Практическая работа №10](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№-10) | [`practical-10`](./practical-10) |
| 11 | 🚧 В работе | [Практическая работа №11](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№-11) | [`practical-11`](./practical-11) |
| 12 | 🚧 В работе | [Практическая работа №12](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№-12) | [`practical-12`](./practical-12) |
| 13–15 | 🚧 В работе | [Практическая работа №13–15](https://github.com/Nu-K2/InstrumentalTools/wiki/Практическая-работа-№-13-15) | [`practical-13-15`](./practical-13-15) |

**Легенда:** ✅ — работа выполнена и оформлена; 🚧 — находится в процессе выполнения.

## 🧩 Структура репозитория

```
InstrumentalTools/
├── practical-01/       # подмодуль → репозиторий ПР №1 (README с пояснением к коду)
├── practical-02/       # подмодуль → репозиторий ПР №2
├── …
├── practical-13-15/    # подмодуль → репозиторий ПР №13–15
└── README.md
```

## 🚀 Клонирование

Так как работы подключены как подмодули, репозиторий следует клонировать с флагом
`--recurse-submodules`:

```bash
git clone --recurse-submodules https://github.com/Nu-K2/InstrumentalTools.git
```

Если репозиторий уже склонирован:

```bash
git submodule update --init --recursive
```

Обновление подмодулей до последних версий:

```bash
git submodule update --remote --merge
```

## ➕ Добавление новой работы (для авторов)

```bash
git submodule add <URL-репозитория-с-работой> practical-XX
git commit -m "Добавлена практическая работа №XX"
git push
```
---

Работы выполняются в учебных целях в НКЭиВТ.
