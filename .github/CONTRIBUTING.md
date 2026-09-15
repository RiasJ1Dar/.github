# Як надіслати внесок

Ці правила діють для всіх репозиторіїв `RiasJ1Dar`, де немає власного файлу
`CONTRIBUTING`.

## Спершу — угода

Проєкти відкриті, але внески приймаються лише з прийнятою
**[угодою контриб'ютора](https://github.com/RiasJ1Dar/.github/blob/main/CLA.md)**.
Вона не забирає у вас авторство: ви лишаєтесь власником свого коду, а проєкт
отримує право випускати його під різними умовами. Без цього змінити ліцензію
чи випустити комерційну версію було б неможливо без дозволу кожного, хто
колись надіслав патч.

Прийняти — один рядок в описі pull request:

```
Я прочитав і приймаю CLA v1.0: https://github.com/RiasJ1Dar/.github/blob/main/CLA.md
```

Виправлення однієї одруківки угоди не потребує.

## Перед тим як писати код

**Спитайте, чи це потрібно** — issue або обговорення. Велика правка, яка не
вписується в задум проєкту, відхиляється незалежно від якості коду, і шкода
буде вашого часу, а не мого.

Ліцензія проєкту — у файлі `LICENSE` того репозиторію. Вона в різних
проєктах різна (GPL-3.0, MIT), тож перевірте саме той, куди пишете.

## Яким має бути pull request

- **одна причина на один PR.** Виправлення помилки й переформатування тисячі
  рядків разом неможливо ні перевірити, ні відкотити;
- **збірка й тести зелені** — команди в `README` проєкту. PR із червоним CI
  не читається;
- **новий код без тесту не приймається**, якщо він виправляє помилку:
  спершу тест, який падає через цю помилку, потім виправлення. Інакше через
  півроку ніщо не заважає зламати те саме знову;
- **стиль сусіднього коду**, а не улюблений. Мова коментарів і повідомлень
  про помилки — така сама, як у решті того репозиторію;
- **без нових залежностей** без попередньої згоди. Залежність — це чужий
  код, чужа ліцензія й чужа підтримка назавжди.

## Про що писати в описі

Що зламано або чого бракує, як це побачити, і що саме зміна робить. Якщо
зміна виправляє помилку — **як виглядав симптом**: помилку впізнають за
симптомом, а не за назвою.

## Помилки й діри в безпеці

Звичайна помилка — issue. Вразливість — **не** issue: напишіть приватно через
[Security advisory](https://docs.github.com/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)
відповідного репозиторію.

---

# Contributing (English)

These rules apply to every `RiasJ1Dar` repository without its own
`CONTRIBUTING` file.

**Agreement first.** Contributions are accepted only with the
[Contributor Agreement](https://github.com/RiasJ1Dar/.github/blob/main/CLA.md)
accepted. You keep the copyright to your work; the project gains the right to
release it under different terms. Add one line to your pull request:

```
I have read and accept the CLA v1.0: https://github.com/RiasJ1Dar/.github/blob/main/CLA.md
```

Fixing a single typo needs no agreement.

**Ask before you code.** Open an issue first. A large change that does not fit
the project's intent is rejected regardless of code quality — and the wasted
time is yours, not mine.

**Check the licence** in the `LICENSE` file of that specific repository: they
differ (GPL-3.0, MIT).

**A good pull request:** one reason per PR; build and tests green (commands in
the project's `README`); a bug fix comes with a test that fails because of the
bug; the style of the surrounding code, including the language of comments and
error messages; no new dependencies without prior agreement.

**In the description:** what is broken or missing, how to see it, and what the
change does. For a bug fix — **what the symptom looked like**: a bug is
recognised by its symptom, not by its name.

**Security holes are not issues.** Report them privately through the
repository's Security advisory.
