# Research: альтернативы Babushka (оболочки/лаунчеры для пожилых)

**Запросов:** 25 | **Раундов поиска:** 3 | **Дата:** 2025-03-08

**Цель:** Список альтернатив с кратким перечислением функций; понимание, по какому пути идти/не идти при описании концепции. Рынок глобальный, 2–3 года + старые проекты. Только софт (без железа). Big Launcher — главный ориентир; фокус на полном ограничении (не «почти вся ОС»).

---

## Ключевые выводы

### По какому пути идти (для концепции)

- **Чётко противопоставлять модель «действия, а не приложения».** Большинство решений — это **упрощённый список приложений** (крупные иконки, пин избранного, SOS). Явно action-only и полное скрытие всего остального делают единицы: Senior Home, Uncomplicated Launcher, Senior Launcher (F-Droid), Incoming Call Only Launcher, отчасти ONYPhone (AIR mode) и BIG Launcher (hide apps + PIN).
- **Делать акцент на «мастер-доступ» (PIN/пароль опекуна).** Это уже ожидаемая функция: BIG Launcher, Senior Launcher - Simple Phone, BigPad, Lina, Naviya — все так или иначе дают блокировку настроек/домашнего экрана для опекуна. В концепции стоит подчёркивать: один раз настроил — пользователь не видит и не меняет.
- **Полное ограничение как УТП.** «Ни браузера, ни Spotify, если не добавлено» — в явном виде редко. BIG Launcher даёт hide apps + lock; Senior Launcher - Simple Phone — lock home screen и только избранное; ONYPhone — AIR mode. Остальные чаще оставляют доступ к списку приложений или настройкам. В позиционировании Babushka логично выделять: **по умолчанию ничего лишнего**, добавлено только то, что явно включил опекун.
- **iOS:** Сторонней замены домашнего экрана нет. Релевантно встроенное: **Assistive Access** (iOS 17+) и **Guided Access**. Концепция «guided access + полноэкранное приложение» для iOS согласуется с ограничениями платформы и с тем, что делают пользователи сейчас.

### По какому пути не идти

- **Не позиционировать как «ещё один простой лаунчер с крупными иконками».** Эту нишу заполняют BIG Launcher, Bleta, Elder Launcher, Simple Senior Launcher и др. (Simple Launcher TCT снят с публикации в Play в 2024.) Конкуренция там по размеру шрифта и количеству тем — не по модели взаимодействия.
- **Не смешивать с «киоск-режимом» в одном предложении.** Kiosk-лаунчеры (SecureME, Fully, open-source Kiosk Launcher) — про предприятия, одно приложение, удалённое управление. Целевая аудитория и сценарий другие; технически пересечение есть (жёсткое ограничение), но позиционирование и маркетинг лучше разделять.
- **Не опираться на общие «сравнения лучших лаунчеров» 2023–2024.** В них доминируют Nova, Niagara, Smart Launcher — не senior-лаунчеры. Релевантны обзоры именно «для пожилых» / «for elderly» (Airdroid, TechLog360, Make Tech Easier, Android Authority, Joy of Android).

---

## Список альтернатив (кратко)

### Крупные / часто упоминаемые

| Продукт | Платформа | Кратко о функциях | Модель (действия vs приложения) |
|--------|-----------|--------------------|-----------------------------------|
| **BIG Launcher** | Android | Крупные кнопки и текст, 6 кнопок на главной: Телефон, Сообщения, Камера, Галерея, SOS, **Список приложений**. Скрытие приложений, блокировка настроек PIN опекуна, кастомные экраны (приложения, контакты, сайты), фото-контакты, SOS с GPS. 1M–2M+ загрузок, 4.2–4.3★. Freemium + платная $4.99–$10. [Play](https://play.google.com/store/apps/details?id=name.kunes.android.launcher.demo), [biglauncher.com](https://biglauncher.com/) | Есть «список приложений»; при этом можно многое скрыть и заблокировать — «почти вся ОС» при желании ограничивается |
| **Senior Launcher - Simple Phone** | Android | Крупные иконки и текст, пин избранных приложений и контактов на главную, скрытие неиспользуемых приложений, блокировка настроек и главного экрана. Без рекламы, trial + разовая покупка. 5K+ загрузок, 4.8★. [Play](https://play.google.com/store/apps/details?id=com.eldo.launcher) | Только выбранное на главной + lock — ближе к «только нужное» |
| **Simple Launcher (Big Launcher)** (TCT/TCL) | Android | Крупные шрифты и иконки, быстрый набор контактов на рабочем столе, SOS, центр управления. Разработчик TCL COMMUNICATION LIMITED. **Снят с публикации в Google Play с 23.09.2024** — ссылка на Store недействительна. Для справки: [AppBrain](https://www.appbrain.com/app/simple-launcher-big-launcher/com.tct.simplelauncher) | Упрощённый лаунчер с быстрыми контактами, доступ к приложениям/настройкам есть |
| **Senior Home – Easy Launcher** | Android | Крупные иконки и текст, большие часы, one-tap звонок и сообщения, SOS, шрифт 80–150%, высокий контраст, офлайн, без рекламы и трекинга, встроенный гайд. [Play](https://play.google.com/store/apps/details?id=com.seniorlauncher.app) | Карточки/кнопки действий, без акцента на списке приложений — близко к «действия» |
| **Uncomplicated Launcher** | Android | Без свайпов/пинчей — только кликабельные кнопки и стрелки. Кубки: SOS, Будильники, Фото, Лекарства, Сообщения, Телефон. Защита от случайных нажатий, карманная защита, напоминания о лекарствах, высокий контраст. [Play](https://play.google.com/store/apps/details?id=com.uncomplicat.launcher), [uncomplicat.com](https://uncomplicat.com/) | Фиксированный набор действий — очень близко к Babushka по модели |
| **Bleta - Easy Smartphone** | Android | Крупные кнопки и текст, кастомный домашний экран, плавающая кнопка Home, упрощённые галерея и контакты, блокировка настроек. 100K+ загрузок, 4.7★. [Play](https://play.google.com/store/apps/details?id=io.bleta.simplelauncher) | Упрощённый интерфейс, доступ к приложениям сохраняется |
| **ONYPhone Elderly Launcher** | Android | Упрощённый главный экран, крупные иконки и текст, настройки и управление приложениями, **«AIR mode»** — минимальный режим (всё остальное скрыто). 7 дней trial. [Play](https://play.google.com/store/apps/details?id=com.silveractivities.onyphone) | AIR mode = почти «только нужное»; по умолчанию есть настройки и приложения |
| **Elder Launcher** | Android | Крупные иконки и текст, пин приложений и контактов на главную, звонок с главного экрана, меню редактирования. Open-source, без сбора данных. 50K+ загрузок, 4.4★. [Play](https://play.google.com/store/apps/details?id=xyz.arjunsinh.elderlauncher) | Пин избранного; полное скрытие всего остального не заявлено |
| **BaldPhone** | Android | Open-source, бесплатно, без рекламы. Замена интерфейса Android упрощённой версией, 30+ языков, настраиваемые шрифты, напоминания о лекарствах. [AlternativeTo](https://alternativeto.net/software/baldphone/), [androidphoria.com](https://androidphoria.com/aplicaciones/baldphone) | «Замена интерфейса» — ближе к полному упрощению; детали ограничения по приложениям из поиска не ясны |

### Ближе к «только действия» / жёсткое ограничение

| Продукт | Платформа | Кратко о функциях | Модель |
|--------|-----------|--------------------|--------|
| **Senior Launcher** (F-Droid) | Android | Контакты как крупные кнопки с фото; нажатие = звонок. Без навигации по списку приложений. [F-Droid](https://f-droid.org/packages/de.nodomain.tobihille.seniorlauncher) | По сути «только контакты как действия» |
| **Incoming Call Only Launcher** | Android | Open-source. Только входящие от доверенных контактов, крупный интерфейс, исходящие отключены. Для когнитивных ограничений/учреждений. [GitHub](https://github.com/lcarne/call-only-launcher) | Экстремальное ограничение — только приём звонков |
| **Simple Phone for Seniors** | Android | Высококонтрастные кнопки, без свайпов, отключение аппаратных кнопок, лаунчер с контролем выхода. [chk-simplephone.andro.io](https://chk-simplephone.andro.io/) | Упрощённый интерфейс с жёстким контролем |

### Дополнительные упоминания

| Продукт | Платформа | Кратко |
|--------|-----------|--------|
| **Simple Senior Launcher** | Android | Крупный шрифт, one-tap контакты семьи, кастомные приложения, без рекламы. [Play](https://play.google.com/store/apps/details?id=com.yyi.elderlyzm) |
| **BigPad - Friendly Launcher** | Android | Крупные иконки, звонки/сообщения/камера, кастомные экраны, PIN для настроек, бесплатно без рекламы. [Play](https://play.google.com/store/apps/details?id=com.solo.simplelauncher) |
| **Lina Launcher for Seniors** | Android | Крупные кнопки звонков и сообщений, настройка опекуном, важные контакты на главной. [Play](https://play.google.com/store/apps/details?id=com.hector6872.lina) |
| **Naviya Launcher** | Android | Для пожилых, доступность, восстановление после сбоев, интеграция с опекуном. Репозиторий на GitHub (posdenous/naviya-launcher) по состоянию на проверку недоступен (404). |
| **Easy Launcher** | Android | Крупные иконки и текст, one-tap звонок/сообщения/приложения. [Play](https://play.google.com/store/apps/details?id=app.home.launcher) |
| **Grand Launcher** | Android | Платный ($7.99), крупный интерфейс, красные уведомления, опция алфавитной клавиатуры, пароль на настройки. Требует связки Grand Phone и Grand SMS. [Play](https://play.google.com/store/apps/details?id=com.cuplesoft.launcher.grandlauncher), [grandlauncher.cuplesoft.com](http://grandlauncher.cuplesoft.com/english) |
| **Help Launcher** | Android | Для пожилых и слабовидящих: крупные кнопки и шрифты, высокий контраст, упрощённые меню, быстрый набор, доступ к WhatsApp/Telegram/Skype. Разработчик Primux Trading SL. В Play по названию не находится; доступен на [Aptoide](https://help-launcher.en.aptoide.com/app), [Orientatech (описание)](https://www.orientatech.es/en/help-launcher/) |
| **Senio Launcher** | Android | Немецкий рынок: крупные иконки, простая навигация, избранное. [senio-launcher.de](https://senio-launcher.de/) |

### Kiosk / lock-down (не для пожилых по позиционированию)

| Продукт | Назначение |
|--------|------------|
| **SecureME**, **Fully Single App Kiosk**, **Kiosk Launcher** (GitHub) | Одно приложение или ограниченный набор, PIN, удалённое управление; предприятия, киоски. |

### iOS (нет сторонних лаунчеров)

| Решение | Тип | Кратко |
|--------|-----|--------|
| **Assistive Access** (iOS 17+) | Встроенное | Упрощённый экран, ограниченный набор приложений (Phone, Messages, Camera, Photos, FaceTime), настройки скрыты, пароль для конфигурации. [Airdroid](https://www.airdroid.com/remote-control/iphone-senior-mode/), [The Senior List](https://www.theseniorlist.com/cell-phones/assistive-access/) |
| **Guided Access** | Встроенное | Блокировка в одном приложении. |

---

## Эффективность поиска

| Метрика | Детали |
|--------|--------|
| **Лучшие срезы** | **Source** (site:play.google.com, alternativeto, reddit) — дали конкретные приложения и ссылки. **Specific term** (one-tap, hide apps, caregiver PIN) — решения, близкие к «действия» и ограничению. **Peristatic** («one button», «replace home screen») — подтвердили Senior Home, BIG, Incoming Call Only. |
| **Слабые результаты** | Reddit по «Big Launcher alternative» — в основном общие лаунчеры (Niagara, Lawnchair). Запросы «senior launcher android comparison 2023 2024» — общие лаунчеры, не senior-ниша. |
| **Пробелы** | Нет единого каталога «только action-based лаунчеры». Разброс цен (BIG: $4.99–$10). BaldPhone в сниппетах без детального описания модели ограничений. |
| **Возможные следующие запросы** | `BaldPhone features hide apps restrict`, `elderly launcher "no app drawer" android`, `Senior Home vs Big Launcher comparison`. |

---

## Источники (выборочно)

- [Android Authority — Big Launcher](https://www.androidauthority.com/big-launcher-109231/)
- [AFB AccessWorld — BIG Launcher review](https://afb.org/aw/14/11/15740)
- [biglauncher.com](https://biglauncher.com/)
- [AlternativeTo — Big Launcher](https://alternativeto.net/software/baldphone/) (контекст BaldPhone/Big Launcher)
- [Play Store — Senior Launcher - Simple Phone](https://play.google.com/store/apps/details?id=com.eldo.launcher)
- [Play Store — Senior Home – Easy Launcher](https://play.google.com/store/apps/details?id=com.seniorlauncher.app)
- [Play Store — Uncomplicated Launcher](https://play.google.com/store/apps/details?id=com.uncomplicat.launcher)
- [Android Headlines — Uncomplicated Launcher](https://androidheadlines.pages.dev/posts/uncomplicated-launcher-aims-to-simplify-smartphone-use-for-the-elderly)
- [F-Droid — Senior Launcher](https://f-droid.org/packages/de.nodomain.tobihille.seniorlauncher)
- [GitHub — Incoming Call Only Launcher](https://github.com/lcarne/call-only-launcher)
- Grand Launcher: [Play](https://play.google.com/store/apps/details?id=com.cuplesoft.launcher.grandlauncher), [grandlauncher.cuplesoft.com](http://grandlauncher.cuplesoft.com/english). Help Launcher: [Aptoide](https://help-launcher.en.aptoide.com/app), [Orientatech](https://www.orientatech.es/en/help-launcher/)
- [Airdroid — 7 Best Android Launchers for Elderly 2025](https://www.airdroid.com/remote-control/launcher-for-elderly/)
- [Make Tech Easier — Best Android Launchers for Senior and Visually Impaired](https://www.maketecheasier.com/best-android-launchers-for-senior-visually-impaired-users/)
- [TechLog360 — 8 Best Android Launcher Apps For Elderly](https://techlog360.com/android-launcher-apps-for-elderly/)
- [Android Stack Exchange — Launcher to limit user actions (for elderly)](https://android.stackexchange.com/questions/258431/launcher-or-whatever-to-limit-user-actions-for-elderly)
- [Airdroid — iPhone Senior Mode / Assistive Access](https://www.airdroid.com/remote-control/iphone-senior-mode/)

Уверенность: 72% — выводы по концепции и список альтернатив согласованы с результатами поиска; детали по отдельным приложениям (BaldPhone, цены) могут требовать уточнения по официальным страницам.
