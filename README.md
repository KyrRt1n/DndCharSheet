# 🐉 D&D Hero Sheet (Mobile & Desktop)

![Status](https://img.shields.io/badge/Status-Active-success)
![Platform](https://img.shields.io/badge/Platform-Web%20|%20Mobile-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

**Легкий, быстрый и полностью автономный лист персонажа для D&D 5e.** Работает как на компьютере, так и на телефоне (адаптивный дизайн). Не требует регистрации, серверов или установки — просто откройте HTML-файл.

🔗 **[Открыть Онлайн Демо](https://kyrrt1n.github.io/DndCharSheet/)**

---

## ✨ Возможности

### 🎨 Темы
<details>
<summary>+- прикольные заготовки</summary>

### 🌿 Лесной Следопыт
Тёмно-зелёный, природный. Для друидов и рейнджеров.

```css
:root {
  --gold: #7ec850;
  --bg: #070f07;
  --card: #0e1a0e;
  --text: #c8e8c0;
  --blue: #3a9e5f;
  --purple: #2e7a3e;
  --green: #5ab840;
  --tab-inactive: #152015;
  --dark-input: #080e08;
}
body {
  background: #070f07;
  background-image: radial-gradient(ellipse at 30% 20%, rgba(30,70,20,0.4) 0%, transparent 50%),
    radial-gradient(ellipse at 70% 80%, rgba(10,50,15,0.3) 0%, transparent 50%);
}
.container { border-color: #2a4a2a; box-shadow: 0 0 40px rgba(0,80,20,0.2); }
h1, h2, h3 { color: #7ec850; border-color: #2a4a2a; }
.stat-card { background: #112011; border-bottom-color: #4a8a30; }
.stat-mod { background: #0e1a0e; color: #7ec850; }
.vitals-grid { background: #0a150a; border-color: #2a4a2a; }
.level-badge { border-color: #4a8a30; }
.lvl-val { color: #7ec850; }
.skill-item { border-left-color: #4a8a30; background: #101e10; }
.tabs-nav { border-color: #2a4a2a; }
.tab-btn.active { color: #7ec850; border-color: #2a4a2a; }
.add-zone { border-color: #2a4a2a; color: #4a6a3a; }
.stat-skill.proficient { color: #7ec850; }
.stat-skill.proficient::before { color: #7ec850; }
input[type="text"], input[type="number"] { border-color: #2a4a2a; }
```

### ✨ Звёздный Маг
Тёмно-синий с мерцающим фиолетовым. Для волшебников и колдунов.

```css
:root {
  --gold: #a78bfa;
  --bg: #04051a;
  --card: #0a0c2e;
  --text: #ddd6fe;
  --blue: #7c3aed;
  --purple: #6d28d9;
  --green: #4c1d95;
  --tab-inactive: #0f1035;
  --dark-input: #050718;
}
body {
  background: #04051a;
  background-image:
    radial-gradient(ellipse at 20% 30%, rgba(109,40,217,0.2) 0%, transparent 45%),
    radial-gradient(ellipse at 80% 70%, rgba(79,70,229,0.15) 0%, transparent 45%),
    url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='400' height='400'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='1'/%3E%3CfeColorMatrix type='saturate' values='0'/%3E%3C/filter%3E%3Crect width='400' height='400' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
}
.container { border-color: #312e81; box-shadow: 0 0 60px rgba(109,40,217,0.25), inset 0 0 80px rgba(79,70,229,0.05); }
h1, h2, h3 { color: #a78bfa; border-color: #312e81; text-shadow: 0 0 12px rgba(167,139,250,0.4); }
.stat-card { background: #0d0f38; border-bottom-color: #7c3aed; }
.stat-mod { background: #080a28; color: #a78bfa; }
.vitals-grid { background: #07091f; border-color: #312e81; }
.level-badge { border-color: #7c3aed; box-shadow: 0 0 15px rgba(124,58,237,0.3); }
.lvl-val { color: #a78bfa; text-shadow: 0 0 20px rgba(167,139,250,0.6); }
.skill-item { border-left-color: #7c3aed; background: #0c0e30; }
.tabs-nav { border-color: #312e81; }
.tab-btn.active { color: #a78bfa; border-color: #312e81; }
.stat-skill.proficient { color: #a78bfa; }
.stat-skill.proficient::before { color: #a78bfa; }
.spell-slot-card { border-color: #312e81; background: #0d0f38; }
.spells-wrapper { border-color: #312e81; background: #07091f; }
```

### 🔥 Пламя Феникса
Огненный оранжево-алый. Для паладинов, жрецов огня, сорсеров.

```css
:root {
  --gold: #ff9500;
  --bg: #0f0500;
  --card: #1c0a00;
  --text: #ffe8cc;
  --blue: #e05a00;
  --purple: #c03000;
  --green: #ff7700;
  --tab-inactive: #240d00;
  --dark-input: #100400;
}
body {
  background: #0f0500;
  background-image:
    radial-gradient(ellipse at 50% 100%, rgba(220,60,0,0.25) 0%, transparent 55%),
    radial-gradient(ellipse at 20% 50%, rgba(255,100,0,0.1) 0%, transparent 40%);
}
.container { border-color: #5a2000; box-shadow: 0 0 50px rgba(200,60,0,0.2), inset 0 0 60px rgba(150,30,0,0.08); }
h1, h2, h3 { color: #ff9500; border-color: #5a2000; text-shadow: 0 0 10px rgba(255,120,0,0.4); }
.stat-card { background: #220c00; border-bottom-color: #cc5500; }
.stat-mod { background: #180800; color: #ff9500; }
.vitals-grid { background: #160600; border-color: #5a2000; }
.level-badge { border-color: #cc5500; box-shadow: 0 0 15px rgba(200,80,0,0.3); }
.lvl-val { color: #ff9500; text-shadow: 0 0 20px rgba(255,140,0,0.6); }
.skill-item { border-left-color: #cc5500; background: #1e0900; }
.tabs-nav { border-color: #5a2000; }
.tab-btn.active { color: #ff9500; border-color: #5a2000; }
.stat-skill.proficient { color: #ff9500; }
.stat-skill.proficient::before { color: #ff9500; }
.hp-box input { color: #ff4400; border-color: #cc2200; }
.spell-slot-card { background: #220c00; border-color: #5a2000; }
label { color: #cc6600; }
```

</details>

### 🧮 Автоматика
- Расчёт модификаторов характеристик (с поддержкой временных модификаторов)
- Калькулятор уровня по XP с кнопкой **+LVL** — мгновенно добавляет целый уровень одним нажатием
- Отслеживание ячеек заклинаний с анимацией траты
- **Авторасчёт Сложности Заклинаний (СЛ):** кнопка ⚡ Авто считает `8 + Бон. Мастерства + мод выбранной характеристики`

### 📋 Главная страница
- Аватар персонажа (загрузка из файла)
- Имя, раса и класс
- Уровень и XP с двумя режимами добавления опыта: точное количество или сразу +1 уровень
- Витальные показатели: Макс. ХП, Тек. ХП, Броня (КД), Скорость, Бонус Мастерства, **СЛ заклинаний**
- Шесть характеристик (СИЛ, ЛОВ, ТЕЛ, ИНТ, МУД, ХАР) с временными модификаторами

### ⚔️ Способности
- Произвольный список способностей и заклинаний
- Для каждой способности: название, описание, уровень ячейки и кнопка **Cast** (автоматически тратит ячейку)
- **Ссылка на заклинание (Spell Link):** кнопка 📖 открывает страницу заклинания в новой вкладке, карандашик ✏️ позволяет задать или изменить URL

### 🔮 Магия
- Бонусы проверок (например: Восприятие +5)
- Черты и особенности персонажа
- Ячейки заклинаний 1–9 уровней + ячейки Пакта
- Кнопки **Короткий отдых** (восстанавливает Пакт) и **Долгий отдых** (восстанавливает всё)

### 🎒 Инвентарь
- Валюта: PP, GP, SP, CP + кастомная строка (монеты душ и прочее)
- Список предметов с названием и описанием
- Сортировка предметов стрелками ▲▼

### 📝 Заметки
- Свободное текстовое поле для записей
- **Известные персонажи:** карточки с именем и заметками о NPC, союзниках и врагах

### 💾 Сохранение и синхронизация
- **Автосохранение** в LocalStorage браузера
- **☁️ Cloud Sync** через GitHub Gist — переносите персонажа между устройствами без проводов
- **Импорт / Экспорт** в `.json` файл для бэкапов

### 📱 Мобильная версия
- Фиксированная нижняя навигация (как в нативных приложениях)
- Крупные инпуты, удобные для пальцев
- Панель управления (Save/Sync/Export) прилипает над нижней навигацией

---

## 📸 Скриншоты

| Рабочий стол (PC) | Мобильная версия (Mobile) |
|:---:|:---:|
| *[Вставь сюда скриншот ПК версии]* | *[Вставь сюда скриншот с телефона]* |

---

## 🚀 Как начать

### Вариант 1: Просто играть
1. Перейдите по ссылке на GitHub Pages (см. выше) или скачайте `index.html` и откройте в любом браузере (Chrome, Safari, Edge).
2. Заполните данные персонажа — всё сохраняется автоматически.
3. Для переноса между устройствами настройте Cloud Sync (см. ниже).

### Вариант 2: Свой репозиторий
1. Сделайте **Fork** этого репозитория.
2. Перейдите в `Settings` → `Pages`.
3. Включите Deployment from branch `main` / `root`.
4. Ваш лист будет доступен по адресу `https://ваш-ник.github.io/repo-name/`.

---

## ☁️ Настройка Cloud Sync (GitHub Gist)

Синхронизация между телефоном и компьютером без скачивания файлов — бесплатно, через GitHub.

### 1. Подготовка (один раз)
1. Зайдите в [Developer Settings → Tokens (Classic)](https://github.com/settings/tokens).
2. Нажмите **Generate new token (classic)**, выберите scope **`gist`**.
3. Скопируйте токен (начинается на `ghp_...`).
4. Создайте новый [секретный Gist](https://gist.github.com/):
   - Имя файла: `hero.json`
   - Содержимое: `{}`
   - Сохраните и скопируйте **ID** из адресной строки (набор букв и цифр после вашего ника).

### 2. Подключение в листе
1. Нажмите кнопку **☁️ Sync** внизу листа персонажа.
2. Введите **Token** и **Gist ID**.
3. **Upload To Cloud** — отправить текущего персонажа в облако.
4. **Load From Cloud** — загрузить персонажа с другого устройства.

> Настройки сохраняются в браузере — вводить каждый раз не нужно. Главное не чистить куки.

---

## 🛠 Технологии

- **HTML5 / CSS3** (Flexbox & Grid)
- **Vanilla JavaScript** (ES6+)
- **No dependencies** — никаких фреймворков. Один файл, чистый код.

---

## 📝 Лицензия

MIT — используйте, изменяйте и распространяйте свободно.