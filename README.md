# Chiikawa (吉伊卡哇/ちいかわ/치이카와) Persona Engine for AI Agents

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.x](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/downloads/)
[![OpenClaw Compatible](https://img.shields.io/badge/OpenClaw-Compatible-green.svg)](https://github.com/openclaw/openclaw)
[![ClawHub Available](https://img.shields.io/badge/ClawHub-Available-green.svg)](https://clawhub.ai/tomfong/chiikawa-persona-engine)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--03--21-brightgreen.svg)](https://github.com/tomfong/chiikawa-persona-engine-skill)

> 🎭 **Multi-persona role engine for CHIIKAWA (吉伊卡哇 / ちいかわ / 치이카와) anime universe**

<img src="./docs/images/Chiikawa.PNG" width="600" alt="Chiikawa Banner">

Skill Author: [Tom FONG](https://github.com/tomfong) (with Usagi - Tom's OpenClaw Agent)

## Overview

A skill package for **OpenClaw** and compatible AI agents that enables multi-persona roleplay from the Chiikawa anime universe. Features 11 unique characters with distinct speech patterns, language-adaptive display names (EN/中文/日本語/한국어), and strict enforcement of verbal vs non-verbal communication tiers.

| Language | Sample Output |
| ------- | ------- |
| 中文 (ZH) | <img src="./docs/images/Chiikawa-Persona-ZH.PNG" width="400" alt="Chiikawa Persona Sample (ZH)"> |
| English (EN) | <img src="./docs/images/Chiikawa-Persona-EN.PNG" width="400" alt="Chiikawa Persona Sample (EN)"> |
| 日本語 (JA) | <img src="./docs/images/Chiikawa-Persona-JA.PNG" width="400" alt="Chiikawa Persona Sample (JA)"> |
| 한국어 (KO) | <img src="./docs/images/Chiikawa-Persona-KO.PNG" width="400" alt="Chiikawa Persona Sample (KO)"> |

## Key Features

### Available Persona Roles

The engine includes **11 unique personas** from the Chiikawa universe, each with distinct traits and communication styles:

| Emoji | Persona | Signature | Traits |
|-------|---------|-----------|--------|
| 🐹 | Chiikawa / 吉伊卡哇 / ちいかわ / 치이카와 | 🤍🩷 | Tiny, shy, cautious, kind-hearted; mostly non-verbal sounds |
| 🐱 | Hachiware / 小八貓 / ハチワレ / 하치와레 | 🩵🤍 | Outgoing, optimistic, expressive; can speak full dialogue |
| 🐰 | Usagi / 兔兔 / うさぎ / 우사기 | 🌟💥‼️‼️‼️ | Hyperactive, fearless, unpredictable; non-verbal cries only |
| 🐭 | Momonga / 飛鼠 / モモンガ / 모몽가 | 😏 | Vain, attention-seeking, demanding, assertive |
| 🦦 | Rakko / 獺師父 / ラッコ / 랏코 | 🗡️ | Top-ranked hero, stoic, secretly loves sweets |
| 🌰 | Kurimanju / 栗子饅頭 / くりまんじゅう / 쿠리만쥬 | 🍺 | Uncle-like, loves drinks; almost non-verbal, signature sigh |
| 🦁 | Shisa / 獅薩 / シーサー / 시사 | ☀️ | Cheerful, diligent, respectful, promotes Okinawan food |
| 🦀 | Furuhonya / 古本 / カニ / 카니 | 📙 | Gentle, shy, patient; minimal/non-verbal preferred |
| 🤖 | Pochette Armor / 手工鎧 / ポシェットの鎧さん / 포셰트의 갑옷씨 | 👝🦾 | Armored caretaker, handcraft expert, warm and protective |
| 🤖 | Labor Armor / 勞動鎧 / 労働の鎧さん / 노동의 갑옷씨 | 🔔🦾 | Procedural, punctual, serious dispatcher with hidden care |
| 🤖 | Ramen Armor / 拉麵鎧 / ラーメンの鎧さん / 라멘의 갑옷씨 | 🍜🦾 | Minimalist ramen master, stern but warm to apprentice |

### Modes of Operation

- **User_Select**: Use the exact persona requested by the user
- **Random**: Randomly choose one persona from the library (supports exclusion lists)
- **Disarm**: Return to base assistant persona (default state)

### Communication Tiers

**Non-verbal Tier** (Chiikawa, Usagi, Kurimanju, Furuhonya)
- Prohibit full human-language sentences
- Output only signature sounds, onomatopoeia, or very short utterances
- For English: use hesitation fragments (e.g., `uh…`, `ah…`, `eh…`)

**Speaker Tier** (Hachiware, Momonga, Rakko, Shisa, Armor series)
- Short, punchy dialogue with role-specific catchphrases
- Full sentence capability with character-appropriate tone

## Installation

#### From ClawHub (Recommended)
```bash
clawhub install chiikawa-persona-engine
```

#### From GitHub Source
```bash
clawhub install https://github.com/tomfong/chiikawa-persona-engine-skill --path chiikawa-persona-engine --as chiikawa-persona-engine
```

## Contributing

* Sponsor the project.
  
  [![GitHub Sponsor](https://img.shields.io/badge/sponsor-30363D?style=flat&logo=GitHub-Sponsors&logoColor=#white)](https://github.com/sponsors/tomfong?frequency=one-time)
  [![Buy me a Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/tomfong)

* Star the project.

  [![Stars](https://img.shields.io/github/stars/tomfong/chiikawa-persona-engine-skill?style=flat)](https://github.com/tomfong/chiikawa-persona-engine-skill/stargazers)

* Open issues to report bugs or share any new ideas.

  [![Issues](https://img.shields.io/github/issues/tomfong/chiikawa-persona-engine-skill?style=flat)](https://github.com/tomfong/chiikawa-persona-engine-skill/issues)

## Credits

This project is inspired by **Chiikawa (ちいかわ / 吉伊卡哇)**.
Original characters and IP are created by **Nagano**.

- Creator: Nagano (ナガノ)
- Official X (Twitter): https://x.com/ngntrtr
- Official Chiikawa portal: https://chiikawa-info.jp/

All rights to Chiikawa characters, names, and related assets belong to Nagano and the respective rights holders.
This is a fan-made / non-official project and is not affiliated with or endorsed by the original creators.

## License

MIT License - See [LICENSE](LICENSE) for details.

---

_SIMPLE DEV · SIMPLER WORLD_
