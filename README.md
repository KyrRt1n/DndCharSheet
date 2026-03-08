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

# 🎨 Темы для D&D Hero Sheet

Копируй нужный CSS в поле 🎨 CSS → Применить

---

## 🌑 Шадар Кай — Сумеречный Жрец
Пепельно-серый с тёмно-фиолетовыми оттенками.

```css
:root {
  --gold: #b8a9d4;
  --bg: #0d0b12;
  --card: #13111a;
  --text: #ccc6d8;
  --blue: #7a6e9a;
  --purple: #9b8cbf;
  --green: #6b7a8a;
  --red: #8a4a5a;
  --tab-inactive: #1a1720;
  --dark-input: #0e0c14;
}
body {
  background: #0d0b12;
  background-image:
    radial-gradient(ellipse at 60% 0%, rgba(80,60,120,0.12) 0%, transparent 55%),
    radial-gradient(ellipse at 20% 100%, rgba(50,40,80,0.10) 0%, transparent 50%);
}
.container { border-color: #2a2535; background: rgba(19,17,26,0.97) !important; box-shadow: 0 0 60px rgba(40,25,70,0.4), inset 0 0 80px rgba(0,0,0,0.2); }
h1, h2, h3 { color: #b8a9d4; border-color: #2a2535; text-shadow: 0 0 18px rgba(140,110,200,0.2); }
h3 { border-color: #221e2e; }
.stat-card { background: #1a1724; border-bottom: 3px solid #5a4e7a; }
.stat-mod { background: #110f18; color: #b8a9d4; }
.stat-card input.stat-val { color: #ddd6ee; }
.vitals-grid { background: #100e18; border-color: #2a2535; }
.vital-box input { background: #1a1724; border-color: #3a3348; color: #ccc6d8; }
.hp-box input { color: #c4788a; border-color: #8a4a5a; }
.ac-box input { color: #8a9ec4; border-color: #4a5a8a; }
.dc-box input[type="number"] { color: #a48acc; border-color: #6a5a9a; }
.tabs-nav { border-color: #2a2535; }
.tab-btn.active { color: #b8a9d4; border-color: #2a2535; }
.tab-btn:hover { color: #b8a9d4; background: #1e1b28; }
.level-badge { border-color: #5a4e7a; background: #110f18; }
.lvl-val { color: #b8a9d4; }
.skill-item { border-left-color: #5a4e7a; background: #17151f; }
.skill-name { background: #110f18; }
.bonus-item { border-left-color: #4a4468; background: #17151f; }
.trait-card { background: #17151f; border-color: #2a2535; }
.trait-card input { background: #110f18; color: #b8a9d4; }
.trait-card textarea { background: #110f18; }
.spells-wrapper { background: #100e18; border-color: #2a2535; }
.spell-slot-card { background: #17151f; border-color: #2a2535; }
.slot-inputs input { border-color: #3a3348; color: #b8a9d4; }
.inventory-wrapper { background: #100e18; border-color: #2a2535; }
.inv-slot { background: #17151f; border-left-color: #5a4e7a; }
.npc-card { background: #17151f; border-color: #2a2535; border-left-color: #7a6a9a; }
.npc-name { background: #110f18; }
.npc-desc { background: #110f18; }
.notes-area { background: #110f18; border-color: #2a2535; color: #ccc6d8; }
.languages-box { background: #100e18; border-color: #2a2535; }
.languages-box textarea { background: #1a1724; border-color: #3a3348; }
.add-zone { border-color: #2a2535; color: #5a5070; }
.add-zone:hover { border-color: #7a6a9a; color: #b8a9d4; }
input[type="text"], input[type="number"] { border-color: #2a2535; background: #0e0c14; color: #ccc6d8; }
label { color: #7a6e9a; }
.stat-skill { color: #7a7490; }
.stat-skill.proficient { color: #b8a9d4; }
.stat-skill.proficient::before { color: #9a8abf; }
.xp-control button { background: #5a4e7a; }
.btn-save { background: #5a4e7a; color: #f0ecff; }
.btn-cloud { background: #3d3558; color: #c4bade; }
.btn-io { background: #2e2a42; color: #a89ec4; }
.btn-clear { background: #5a2e3a; color: #f0c4cc; }
.rest-btn { background: #1a1724; border-color: #3a3348; color: #8a7eaa; }
```

---

## 🩸 Кровавый Варвар
Красно-чёрный. Для берсерков и воинов хаоса.

```css
:root {
  --gold: #ff4444;
  --bg: #0a0000;
  --card: #1a0505;
  --text: #ffcccc;
  --blue: #cc2222;
  --purple: #881111;
  --green: #884444;
  --tab-inactive: #2a0808;
  --dark-input: #0f0202;
}
body {
  background: radial-gradient(ellipse at top, #1a0000 0%, #050000 100%);
}
.container { border-color: #5a0000; box-shadow: 0 0 40px rgba(180,0,0,0.3), inset 0 0 60px rgba(100,0,0,0.1); }
h1, h2, h3 { color: var(--gold); border-color: #5a0000; text-shadow: 0 0 10px rgba(255,50,50,0.4); }
.stat-card { border-bottom-color: #cc0000; background: #200808; }
.stat-mod { background: #2a0505; color: #ff4444; }
.tabs-nav { border-color: #5a0000; }
.tab-btn.active { color: #ff4444; border-color: #5a0000; }
.vitals-grid { background: #160404; border-color: #5a0000; }
.level-badge { border-color: #cc0000; }
.lvl-val { color: #ff4444; text-shadow: 0 0 15px rgba(255,0,0,0.5); }
.skill-item { border-left-color: #cc0000; }
.stat-skill { color: #774444; }
.stat-skill.proficient { color: #ff4444; }
.stat-skill.proficient::before { color: #ff4444; }
```

---

## 🌿 Лесной Следопыт
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
  background-image:
    radial-gradient(ellipse at 30% 20%, rgba(30,70,20,0.4) 0%, transparent 50%),
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
.stat-skill { color: #4a6a3a; }
.stat-skill.proficient { color: #7ec850; }
.stat-skill.proficient::before { color: #7ec850; }
input[type="text"], input[type="number"] { border-color: #2a4a2a; }
```

---

## ✨ Звёздный Маг
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
    radial-gradient(ellipse at 80% 70%, rgba(79,70,229,0.15) 0%, transparent 45%);
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
.stat-skill { color: #4a4870; }
.stat-skill.proficient { color: #a78bfa; }
.stat-skill.proficient::before { color: #a78bfa; }
.spell-slot-card { border-color: #312e81; background: #0d0f38; }
.spells-wrapper { border-color: #312e81; background: #07091f; }
```

---

## ☠️ Некромант
Мертвенно-серый с зелёным свечением. Для нежити и тёмных магов.

```css
:root {
  --gold: #39ff8a;
  --bg: #050508;
  --card: #0c0c10;
  --text: #b0b8c0;
  --blue: #1a9e6a;
  --purple: #156e4a;
  --green: #39ff8a;
  --tab-inactive: #101015;
  --dark-input: #080808;
}
body {
  background: #050508;
  background-image: radial-gradient(ellipse at 50% 0%, rgba(30,200,80,0.08) 0%, transparent 60%);
}
.container { border-color: #1a2e1a; box-shadow: 0 0 50px rgba(30,200,80,0.1), inset 0 0 100px rgba(0,0,0,0.3); }
h1, h2, h3 { color: #39ff8a; border-color: #1a3a1a; text-shadow: 0 0 10px rgba(57,255,138,0.35); font-family: 'Courier New', monospace; }
.stat-card { background: #0e0e14; border-bottom: 3px solid #39ff8a; }
.stat-mod { background: #080810; color: #39ff8a; text-shadow: 0 0 8px rgba(57,255,138,0.5); }
.vitals-grid { background: #090910; border-color: #1a3a1a; }
.level-badge { border-color: #39ff8a; box-shadow: 0 0 15px rgba(57,255,138,0.2); }
.lvl-val { color: #39ff8a; text-shadow: 0 0 20px rgba(57,255,138,0.7); font-family: 'Courier New', monospace; }
.skill-item { border-left-color: #39ff8a; background: #0d0d12; }
.tabs-nav { border-color: #1a3a1a; }
.tab-btn.active { color: #39ff8a; border-color: #1a3a1a; }
.stat-skill { color: #2a5a3a; }
.stat-skill.proficient { color: #39ff8a; text-shadow: 0 0 5px rgba(57,255,138,0.4); }
.stat-skill.proficient::before { color: #39ff8a; }
.spell-slot-card { background: #0e0e14; border-color: #1a3a1a; }
input[type="text"], input[type="number"] { border-color: #1a3a1a; color: #b0b8c0; }
label { color: #39ff8a; }
```

---

## 🔥 Пламя Феникса
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
.stat-skill { color: #6a3a10; }
.stat-skill.proficient { color: #ff9500; }
.stat-skill.proficient::before { color: #ff9500; }
.hp-box input { color: #ff4400; border-color: #cc2200; }
.spell-slot-card { background: #220c00; border-color: #5a2000; }
label { color: #cc6600; }
```

---

## 🧊 Ледяной Маг / Зима
Холодный синий. Для чародеев льда, эльфов, северных варваров.

```css
:root {
  --gold: #88ccff;
  --bg: #010a14;
  --card: #041525;
  --text: #cce8ff;
  --blue: #1a7ab8;
  --purple: #0e5a8a;
  --green: #2299cc;
  --tab-inactive: #071e30;
  --dark-input: #020c18;
}
body {
  background: #010a14;
  background-image:
    radial-gradient(ellipse at 40% 0%, rgba(30,100,180,0.2) 0%, transparent 50%),
    radial-gradient(ellipse at 60% 100%, rgba(10,60,120,0.15) 0%, transparent 50%);
}
.container { border-color: #0e3a5a; box-shadow: 0 0 50px rgba(20,100,180,0.15), inset 0 0 80px rgba(10,60,120,0.08); }
h1, h2, h3 { color: #88ccff; border-color: #0e3a5a; text-shadow: 0 0 10px rgba(100,180,255,0.3); }
.stat-card { background: #051a2e; border-bottom-color: #1a7ab8; }
.stat-mod { background: #031020; color: #88ccff; }
.vitals-grid { background: #031020; border-color: #0e3a5a; }
.level-badge { border-color: #1a7ab8; box-shadow: 0 0 15px rgba(30,120,200,0.25); }
.lvl-val { color: #88ccff; text-shadow: 0 0 15px rgba(136,204,255,0.5); }
.skill-item { border-left-color: #1a7ab8; background: #051825; }
.tabs-nav { border-color: #0e3a5a; }
.tab-btn.active { color: #88ccff; border-color: #0e3a5a; }
.stat-skill { color: #2a5070; }
.stat-skill.proficient { color: #88ccff; }
.stat-skill.proficient::before { color: #88ccff; }
.ac-box input { color: #55aaff; border-color: #1a7ab8; }
label { color: #4a90cc; }
input[type="text"], input[type="number"] { border-color: #0e3a5a; color: #cce8ff; }
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