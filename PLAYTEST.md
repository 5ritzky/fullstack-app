# STATUS BETA — Playtest Guide

**Build:** `v0.4.0-beta`  
**Game:** [Launch STATUS BETA](https://5ritzky.github.io/fullstack-app/status-beta/)  
**Issue tracker:** [Open a new issue](https://github.com/5ritzky/fullstack-app/issues/new)

---

# Русский

## Цель тестирования

Нам нужны не оценки «понравилось / не понравилось», а воспроизводимые наблюдения о том, как игра связывает действия игрока с отношениями, обязательствами, доступами и социальным статусом.

Текущая сборка — экспериментальная демонстрация механики. Правила переходов статусов пока являются проверяемой гипотезой и не заменяют утверждённую модель v0.3.

## Что сделать

### Минимальный тест

1. Откройте игру и выберите язык.
2. Пройдите текущую сюжетную арку до финала.
3. Выберите стратегию поведения и придерживайтесь её настолько последовательно, насколько это возможно:
   - сотрудничество;
   - независимость;
   - конфронтация;
   - союз.
4. Отслеживайте, что меняется после значимых решений:
   - отношения с NPC;
   - обязательства и их состояние;
   - сюжетные факты и события;
   - доступные сцены и сведения;
   - социальное положение персонажа.
5. Обратите внимание на финал: разрешает ли он центральный конфликт и понятна ли цена выбранного пути.
6. Заполните встроенную форму обратной связи и скачайте или скопируйте отчёт.
7. Передайте отчёт через соответствующий шаблон GitHub Issue.

Не нужно проходить все стратегии за один сеанс. Для сравнения стратегий полезны отдельные прохождения с разными последовательными подходами.

## Пять вопросов после прохождения

1. Какую стратегию вы выбрали?
2. Какое решение имело наиболее заметные последствия?
3. Какие отношения или обязательства повлияли на последующие сцены?
4. Почему, по вашему мнению, персонаж получил именно этот статус? Какие события это подтверждают?
5. Что показалось нелогичным, недостижимым или незавершённым?

## Что особенно важно проверять

- Не меняется ли статус только из-за дружелюбной реплики или значения R/S/P.
- Есть ли конкретные социальные факты, подтверждающие переход.
- Отличаются ли последствия сотрудничества, независимости, конфронтации и союзов.
- Влияют ли отношения и обязательства на последующие сцены.
- Может ли NPC знать то, чего он не видел, не слышал и не мог узнать.
- Не повторяются ли одноразовые эффекты после отмены хода, повторного входа в сцену или загрузки сохранения.
- Можно ли завершить арку без обязательного продолжения.

## Как оформить полезный отчёт

Укажите по возможности:

- язык игры;
- браузер и устройство;
- стратегию прохождения;
- сцену или ID выбора, если он виден;
- что произошло до спорного решения;
- ожидаемое поведение;
- фактический результат;
- шаги для повторения.

Если сообщаете об ошибке, отделяйте наблюдение от предположения о причине. Не нужно самостоятельно предлагать исправление, если причина неясна.

## Когда тест считается активным

Активный тестировщик:
- завершил хотя бы одно прохождение до финала;
- передал конкретный отчёт;
- описал хотя бы одно наблюдение о последствиях или логике игры.

Повторное прохождение с другой стратегией особенно полезно, но не обязательно для минимального теста.

## Конфиденциальность

Игра формирует отчёт на устройстве; автоматическая отправка событий на сервер не заявлена. Отчёт передаётся только после самостоятельного действия тестировщика. Не указывайте личные данные, пароли или конфиденциальную информацию.

---

# English

## Purpose

We are not looking for simple “like / dislike” ratings. We need reproducible observations about how player actions affect relationships, obligations, access and social status.

This build is an experimental mechanics demo. Its status-transition rules are a testable hypothesis and do not replace the approved v0.3 model.

## What to do

### Minimum test

1. Open the game and choose a language.
2. Play the current story arc through to its ending.
3. Choose an approach and follow it consistently where possible:
   - cooperation;
   - independence;
   - confrontation;
   - alliance.
4. Watch what changes after meaningful decisions:
   - relationships with NPCs;
   - obligations and their state;
   - story facts and events;
   - available scenes and information;
   - the character's social position.
5. Evaluate the ending: does it resolve the central conflict, and is the cost of your chosen approach understandable?
6. Complete the in-game feedback form and copy or download the report.
7. Submit it using the appropriate GitHub issue template.

You do not need to test every approach in one session. Separate playthroughs with different consistent approaches are more useful for comparison.

## Five questions after playing

1. Which approach did you choose?
2. Which decision had the most noticeable consequences?
3. Which relationships or obligations affected later scenes?
4. Why do you think the character received this status? Which events support it?
5. What felt illogical, unreachable or incomplete?

## What to check carefully

- Does status change only because of a friendly line or an R/S/P value?
- Are there concrete social facts supporting a transition?
- Do cooperation, independence, confrontation and alliances produce distinct consequences?
- Do relationships and obligations affect later scenes?
- Can an NPC know something they could not have seen, heard or learned?
- Are one-time effects repeated after undo, re-entering a scene or loading a save?
- Can the story arc be completed without a required sequel?

## What makes a useful report

Include where possible:

- game language;
- browser and device;
- chosen approach;
- scene or choice ID, if visible;
- what happened before the disputed decision;
- expected behaviour;
- actual result;
- reproduction steps.

Separate what you observed from your guess about its cause. You do not need to propose a fix.

## Active tester definition

An active tester:
- completes at least one playthrough through to the ending;
- submits a concrete report;
- describes at least one observation about the game's consequences or logic.

A second playthrough with a different approach is especially useful, but is not required for the minimum test.

## Privacy

The game generates the report locally; automatic server-side event submission is not stated. The report is shared only when the tester manually submits it. Do not include personal data, passwords or confidential information.
