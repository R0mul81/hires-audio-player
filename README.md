# RE:PLAY — Hi-Res Desktop Audio Player (v1.1.0)

> **Crafted by the `RE:` Ecosystem** | Official YouTube Channel: [@2REGENERATE](https://www.youtube.com/@2REGENERATE)

**RE:PLAY** is a lightweight, high-precision desktop audio player built for music lovers and audiophiles. Designed with a pure audio path in mind, it combines bit-perfect playback, studio-grade headphone equalization, real-time spectral visualization, and a customizable modern interface.

---

## 🌐 Languages / Языки
- [English](#english)
- [Русский](#русский)

---

<a name="english"></a>
## 🇬🇧 English

### ✨ Key Features

- **Lossless & Hi-Res Playback:** Native support for `FLAC`, `WAV`, `ALAC`, `OGG`, `MP3`, and `CUE` sheet album splitting via a low-latency audio engine (`miniaudio` / PortAudio).
- **Bit-Perfect Audio Path (WASAPI):**
  - **WASAPI Exclusive Mode:** Direct hardware DAC bypass with native sample rate output (`44.1 / 48 / 96 / 192 kHz`) and live `BIT-PERFECT` status indicator.
  - **WASAPI Shared Mode:** Seamless desktop playback with automatic high-precision polyphase resampling.
- **Real-Time FFT Spectrum Analyzer:** Smooth 48-band logarithmic spectrum visualizer (`20 Hz – 20 kHz`) with peak hold indicators and adaptive skin colors.
- **AutoEq & Equalizer APO Integration:** Direct import of `.txt` headphone correction profiles (`PK`, `LSC`, `HSC` filters + `Preamp` anti-clipping protection) powered by 64-bit float IIR biquad filtering (`SciPy DSP`).
- **10-Band Graphic Equalizer:** Independent real-time EQ (`31 Hz – 16 kHz`, `±12 dB`) with genre-tuned presets (*Ambient, Rap/Hip-Hop, Dubstep, Rock, Jazz, Classical, Strings, Minimal Techno*) and custom user presets.
- **High-Speed SQLite Media Library:** Instant multi-threaded indexing, search, and filtering by artist, album, genre, and year.
- **Built-in Tag & Cover Art Editor:** Single and batch metadata editing (`ID3`, `FLAC`, `OGG`, `M4A`, `WAV`) with embedded cover art management.
- **Synced Karaoke Lyrics:** Optional Spotify-style lyrics panel with real-time `.lrc` timecode highlighting, automatic lyrics fetching via **LRCLIB**, and a built-in `Ctrl+T` timestamping tool.
- **20 Custom Skins & 14 Languages:** Instant theme switching (including Windows 11 Acrylic/Mica *iOS Glassmorphism* themes) and full on-the-fly localization with RTL support.
- **Desktop Integration:** Drag-and-Drop playlists (`M3U` / `JSON`), system tray minimization, and global media hotkeys.

### 💻 System Requirements
- **OS:** Windows 10 or Windows 11 (64-bit)
- **Audio Output:** Any Windows-compatible sound card, USB DAC, or Bluetooth audio device

### 🚀 How to Install
1. Download the latest release archive (`RE_PLAY_v1.1.0_Win64.zip`) from the **Releases** section.
2. Extract the archive and run **`RE_PLAY_Setup.exe`**.
3. **Note on Windows SmartScreen:** Because **RE:PLAY** is an independent release without a commercial EV code-signing certificate, Windows Defender SmartScreen may display a blue warning dialog (*"Windows protected your PC"*). Click **"More info"** → **"Run anyway"** to proceed safely.
4. Follow the installation wizard and launch **RE:PLAY** from your Desktop or Start Menu.

### ❤️ Support the Project & Ecosystem
**RE:PLAY** is shared as a free gift for the music community. If you enjoy the player and our music channels, you can support future updates and releases:
- **YouTube Channel:** [youtube.com/@2REGENERATE](https://www.youtube.com/@2REGENERATE)
- **Crypto Donations (0% Fees — USDT / USDC / ETH / BNB):**
  - **EVM Address (ERC-20, BEP-20, Polygon, Arbitrum, Base):**
    ```text
    0x037FcC3a6aBf2E4E6fcdC0Ab2D0222d9F9AF50B4
    ```

---

<a name="русский"></a>
## 🇷🇺 Русский

### ✨ Основные возможности

- **Воспроизведение Lossless и Hi-Res:** Поддержка форматов `FLAC`, `WAV`, `ALAC`, `OGG`, `MP3` и разметки альбомов `CUE` на базе звукового движка с низкой задержкой (`miniaudio` / PortAudio).
- **Чистый аудиотракт (WASAPI Bit-Perfect):**
  - **WASAPI Exclusive:** Монопольный захват звуковой карты и прямой вывод на ЦАП с нативной частотой трека (`44.1 / 48 / 96 / 192 кГц`) в обход системного микшера Windows + индикатор `BIT-PERFECT`.
  - **WASAPI Shared:** Совместный режим работы с автоматическим качественным ресемплингом на системную частоту устройства.
- **Живой FFT-спектроанализатор:** Плавный 48-полосный логарифмический анализатор спектра (`20 Гц – 20 кГц`) с пиковыми индикаторами и адаптацией под цвета выбранного скина.
- **Поддержка профилей наушников AutoEq / Equalizer APO:** Прямой импорт `.txt`-файлов коррекции АЧХ наушников (фильтры `PK`, `LSC`, `HSC` и `Preamp` с защитой от клиппинга) на базе 64-битной биквадратной IIR-фильтрации (`SciPy DSP`).
- **10-полосный графический эквалайзер:** Независимый эквалайзер (`31 Гц – 16 кГц`, `±12 дБ`) с готовыми жанровыми пресетами (*Ambient, Rap/Hip-Hop, Dubstep, Rock, Jazz, Classical, Strings, Minimal Techno*) и пользовательскими настройками.
- **Быстрая медиабиблиотека на SQLite:** Мгновенное фоновое сканирование коллекций, поиск и фильтрация по исполнителю, альбому, жанру и году.
- **Встроенный редактор тегов и обложек:** Одиночное и пакетное редактирование метаданных (`ID3`, `FLAC`, `OGG`, `M4A`, `WAV`) и вшивание обложек альбомов.
- **Караоке-лирика:** Отключаемая панель текста песен в стиле Spotify с построчной подсветкой таймкодов `.lrc`, автопоиском текстов через **LRCLIB** и инструментом быстрой разметки времени (`Ctrl+T`).
- **20 тем оформления и 14 языков:** Мгновенная смена скинов без перезапуска (включая полупрозрачные темы *iOS Glassmorphism* с размытием Windows 11) и перевод интерфейса на лету с поддержкой RTL.
- **Интеграция с Windows:** Плейлисты с Drag-and-Drop (`M3U` / `JSON`), сворачивание в системный трей и глобальные горячие клавиши.

### 💻 Системные требования
- **ОС:** Windows 10 или Windows 11 (64-bit)
- **Звук:** Любая встроенная или внешняя звуковая карта, USB-ЦАП или Bluetooth-гарнитура

### 🚀 Установка
1. Скачайте актуальный архив релиза (`RE_PLAY_v1.1.0_Win64.zip`) из раздела **Releases**.
2. Распакуйте архив и запустите **`RE_PLAY_Setup.exe`**.
3. **Примечание про Windows SmartScreen:** Так как **RE:PLAY** — новое независимое приложение без платного коммерческого сертификата подписи, при первом запуске Windows может показать синее окно защиты (*«Система Windows защитила ваш компьютер»*). Нажмите **«Подробнее»** → **«Выполнить в любом случае»**, чтобы продолжить установку.
4. Следуйте инструкциям мастера установки и запустите плеер с Рабочего стола или из меню «Пуск».

### ❤️ Поддержка проекта и экосистемы RE:
**RE:PLAY** распространяется бесплатно как подарок для всех ценителей качественного звука. Поддержать развитие плеера и новые музыкальные релизы можно подпиской или донатом:
- **YouTube-канал:** [youtube.com/@2REGENERATE](https://www.youtube.com/@2REGENERATE)
- **Крипто-донаты (без комиссий — USDT / USDC / ETH / BNB):**
  - **EVM-адрес (сети ERC-20, BEP-20, Polygon, Arbitrum, Base):**
    ```text
    0x037FcC3a6aBf2E4E6fcdC0Ab2D0222d9F9AF50B4
    ```

---

*© RE: Ecosystem — All rights reserved.*
