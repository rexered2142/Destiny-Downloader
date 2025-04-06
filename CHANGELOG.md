# 📦 Changelog – Destiny Downloader 1.4 beta

---

## 🇷🇺 Русский

### 🆕 Новое
- Добавлена кнопка **"Отменить загрузку"**
- Программа **автоматически предлагает установить FFmpeg**, если он не найден
- Поддержка конвертации в **MP3, WAV, M4A**
- Добавлено предупреждение при попытке **закрыть приложение во время загрузки**

### ⚙️ Улучшения
- Полностью переработана логика загрузки — **исправлены ошибки** при скачивании видео
- Обновлены и улучшены **подсказки** по использованию интерфейса
- Повышена стабильность при загрузке через **cookies**
- **Блокировка изменения настроек** (папки, cookies, качество, формат) во время загрузки

### ⚠️ Важно
- Если выбран чекбокс "Конвертация в аудио", выбор качества видео будет **заблокирован**, и наоборот
- При выборе качества "best" может скачаться видео в нестандартном формате — **рекомендуется использовать 1080p или 720p**
- Если получаете ошибку `403 Forbidden` при использовании cookies:
  - Cookies скорее всего **устарели**
  - Зайдите в `%appdata%/DestinyDownloader` и обнулите путь `cookies_path`
  - Рекомендуется **обновлять cookies каждые 30 минут** или отключать при ошибках

---

## 🇬🇧 English

### 🆕 New
- Added **"Cancel Download"** button
- App now **automatically prompts to install FFmpeg** if it's missing
- Added support for **MP3, WAV, M4A** conversion
- App now **asks for confirmation** if you try to exit during a download

### ⚙️ Improvements
- Download logic has been improved — **major bug fixes**
- Interface **tooltips and usage hints** improved
- Better handling of **cookies-based downloads**
- **Settings are locked** (folder, cookies, quality, format) during downloads

### ⚠️ Notes
- If **"Convert to audio"** is selected, **video quality selection is disabled** and vice versa
- When using **"best" quality**, some videos may download in non-standard formats — use **1080p or 720p** instead
- Got a `403 Forbidden` error while using cookies?
  - Cookies are likely **expired**
  - Open `%appdata%/DestinyDownloader`, and clear the path from `cookies_path`
  - It is recommended to **update cookies every 30 minutes**, or disable them temporarily

---

## 🇺🇦 Українська

### 🆕 Нове
- Додано кнопку **"Скасувати завантаження"**
- Якщо FFmpeg не встановлений, програма **автоматично запропонує його встановити**
- Додано конвертацію в **MP3, WAV, M4A**
- При спробі закрити програму під час завантаження — з’явиться **підтвердження**

### ⚙️ Покращення
- Повністю оновлено механіку завантаження — **виправлено помилки**
- Оновлені **підказки** для кращого розуміння інтерфейсу
- Покращено стабільність при використанні **cookies**
- **Заблоковано зміну налаштувань** під час завантаження (теку, cookies, якість, формат)

### ⚠️ Увага
- Якщо увімкнено "Конвертацію в аудіо", вибір якості відео буде **заблоковано**, і навпаки
- При виборі "best" може завантажитись нестандартний формат — рекомендується **1080p або 720p**
- Якщо бачите помилку `403 Forbidden` з cookies:
  - Cookies, ймовірно, **протерміновані**
  - Зайдіть у `%appdata%/DestinyDownloader`, та очистіть шлях `cookies_path`
  - Рекомендується **оновлювати cookies кожні 30 хвилин** або тимчасово їх відключати

---
