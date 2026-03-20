<div align="center">

# 📻 DavMar FM - Discord Radio Bot

![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Discord.py](https://img.shields.io/badge/discord.py-2.7.1-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)
![Status](https://img.shields.io/badge/Status-Online-brightgreen?style=for-the-badge)
[![License](https://img.shields.io/badge/License-Closed%20Source-red?style=for-the-badge)](#-licencja)

<br>

### 🎵 Bot radiowy Discord z obsługą wielu polskich stacji radiowych - Vox FM, Radio Party, Energy 2000, Radio ZET, RMF FM, RMF MAX

<br>

[✨ Funkcje](#-funkcje) •
[📸 Screenshots](#-screenshots) •
[🛠️ Technologie](#️-technologie) •
[📞 Kontakt](#-kontakt)

<br>

---

</div>

<br>

## ✨ Funkcje

<table>
<tr>
<td>

### 📻 Stacje Radiowe
- ✅ **Vox FM** - Muzyka pop
- ✅ **Radio Party** - Imprezy i zabawa
- ✅ **Energy 2000** - Dance i elektronika
- ✅ **Radio ZET** - Hity i nowości
- ✅ **RMF FM** - Największe hity
- ✅ **RMF MAX** - Dance i R&B

</td>
<td>

### 🎛️ Sterowanie
- ✅ **Ręczne sterowanie** - Bot dołącza po komendzie /join
- ✅ **Interaktywne menu** - Przyciski do wyboru stacji
- ✅ **Szybka zmiana** - Zmień stację w czasie rzeczywistym
- ✅ **Regulacja głośności** - Ustaw głośność 1-100%
- ✅ **Status ze stacją** - Wyświetla aktualną stację jako status

</td>
</tr>
<tr>
<td>

### 📊 Statystyki i Analityka
- ✅ **Licznik odtworzeń** - Automatyczne zliczanie statystyk
- ✅ **Historia odtwarzania** - Ostatnio grane stacje
- ✅ **Ranking stacji** - Top najczęściej słuchanych
- ✅ **Monitorowanie** - Starty, restarty, błędy
- ✅ **Watchdog system** - Automatyczny restart streamu

</td>
<td>

### 🎨 Design i UX
- ✅ **Kolorowe logi** - Czytelne logi z timestampami
- ✅ **Slash commands** - Nowoczesne komendy Discord
- ✅ **Interaktywne embedy** - Piękne panele informacyjne
- ✅ **Status bota** - Dynamiczny status ze stacją
- ✅ **Błędy i logi** - Szczegółowe logowanie systemowe

</td>
</tr>
</table>

<br>

## 📸 Screenshots

### 🎵 Bot Discord w Akcji

<img src="screenshots/bot-radio.png" alt="DavMar FM Bot" width="600">

*Interaktywne menu radiowe z przyciskami*

<br><br>

### 📊 Statystyki i Ranking

<img src="screenshots/statistics.png" alt="Statystyki radiowe" width="700">

*Raporty odtwarzania i ranking stacji*

<br><br>

### 🎨 Kolorowe Logi Systemowe

<img src="screenshots/console-logs.png" alt="Logi konsoli" width="800">

*Kolorowe logi z timestampami i kategoriami*

<br>

---

## 🎨 Przykładowe Logi

```
2026-03-09 10:15:43 [SYSTEM] ⚙️ ==================================================
2026-03-09 10:15:43 [OK] Zalogowano jako DavMar FM#7471
2026-03-09 10:15:43 [INFO] discord.py 2.7.1
2026-03-09 10:15:43 [SYSTEM] ⚙️ ==================================================
2026-03-09 10:15:43 [INFO] Serwer: DavMar Discord
2026-03-09 10:15:43 [MUSIC] 🎵 Gra stacja: RMF FM
2026-03-09 10:15:43 [OK] DavMar FM Bot gotowy do pracy!

2026-03-09 10:16:04 [VOICE] 🔊 Łączę z: 📻 Radio
2026-03-09 10:16:06 [PLAYER] Odtwarzanie RMF FM rozpoczęte
2026-03-09 10:16:10 [MUSIC] 🎵 Zmieniono stację na: Radio ZET
2026-03-09 10:16:15 [STATS] 📊 Odtwarzanie #45: RMF FM
```

<br>

## 🛠️ Technologie

<div align="center">

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Discord.py](https://img.shields.io/badge/discord.py-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discordpy.readthedocs.io/)
[![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)](https://ffmpeg.org/)
[![aiohttp](https://img.shields.io/badge/aiohttp-2C5AA0?style=for-the-badge&logo=python&logoColor=white)](https://aiohttp.readthedocs.io/)

</div>

### Stack Techniczny:

- **Runtime:** Python 3.12+ z discord.py[voice] 2.7.1
- **Audio:** FFmpeg do obsługi streamów radiowych
- **HTTP:** aiohttp do zapytań o stacje radiowe
- **Environment:** python-dotenv do zarządzania konfiguracją
- **Security:** pynacl do szyfrowania voice connections

<br>

## 📁 Struktura Projektu

```
davmar-fm-bot/
├── 📄 bot.py              # Główny plik bota (762 linii)
├── 📄 .env                # Konfiguracja (DISCORD_TOKEN, GUILD_ID)
├── 📄 .env.example        # Przykładowa konfiguracja
├── 📄 requirements.txt    # Zależności Python
├── 📄 README.md           # Ta dokumentacja
├── 📄 LICENSE             # Licencja MIT
├── 📁 .venv/              # Wirtualne środowisko Python
└── 📁 screenshots/        # Zrzuty ekranu bota
```

<br>

## 💼 Dostępne na zamówienie

<div align="center">

### 🎯 Chcesz takiego bota radiowego dla swojego serwera?

<br>

| Pakiet | Opis |
|--------|------|
| 🎵 **Basic** | Bot radiowy z 3 stacjami |
| 📻 **Professional** | Pełny bot z 6+ stacjami + statystyki |
| 🎚️ **Custom** | Dowolne stacje + custom funkcje |
| 🏢 **Enterprise** | Wsparcie 24/7 + hosting + utrzymanie |

<br>

---

## 📞 Kontakt

<div align="center">

### Zainteresowany? Napisz do mnie!

<br>

| Developer | Discord | GitHub |
|-----------|---------|--------|
| **DrWilkor** | [DrWilkor#446740090757316608](https://discord.com/users/446740090757316608) | [@WilkorPLYT](https://github.com/WilkorPLYT) |

</div>

<br>

## 📄 Licencja

<div align="center">

� **Closed Source - Wszelkie prawa zastrzeżone**

Ten projekt jest własnością autora. Kod źródłowy nie jest publicznie dostępny.

Nieautoryzowane kopiowanie, modyfikowanie lub dystrybucja jest zabroniona.

Autor: DrWilkor (WilkorPLYT)
Copyright © 2026 DrWilkor

</div>

<br>

---

<br>

## 👨‍💻 Autor

<div align="center">

[![Stworzony przez](https://img.shields.io/badge/Stworzony%20przez-DrWilkor-blueviolet?style=for-the-badge)](https://github.com/WilkorPLYT)

<br>

Stworzony z ❤️ przez **DrWilkor** dla **DavMar**

<br>

| Developer | Discord | GitHub |
|-----------|---------|--------|
| DrWilkor | [![Discord](https://img.shields.io/badge/Discord-DrWilkor%23446740090757316608-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/446740090757316608) | [![GitHub](https://img.shields.io/badge/GitHub-WilkorPLYT-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/WilkorPLYT) |

<br>

---

<br>

**⭐ Jeśli podoba Ci się ten projekt, zostaw gwiazdkę! ⭐**

</div>

<br>

---

<div align="center">

Made with ❤️ | DavMar FM © 2026

</div>
