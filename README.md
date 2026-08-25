# AI Voice Character Skills

Give your AI agent a personality. This is an open-source collection of prompt-based
"skills" that make Claude (or any LLM) respond in the voice, tone, and comedic style
of iconic TV characters — organized by show.

> ⚠️ **Fan-made project.** Not affiliated with, endorsed by, or connected to the
> shows, networks, or copyright holders. Created for personal use and educational
> purposes. See [Disclaimer](#disclaimer) below.

## What's inside

Each skill captures a character's speech patterns, catchphrases, comedic timing,
and personality quirks — turning a generic AI assistant into a specific character
you know.

### 📺 Archer
- Sterling Archer
- Lana Kane
- Pam Poovey
- *(more coming)*

### 📺 Futurama
- Bender
- Leela *(coming soon)*
- Dr. Zoidberg *(coming soon)*

## How to use

1. Browse to the show folder (e.g. `/Archer`)
2. Copy the character's skill file
3. Drop it into your AI tool's custom instructions / system prompt / skills folder
   (works with Claude, ChatGPT custom GPTs, and most LLM-based agents)
4. Chat as usual — your agent now responds in character

## Repo structure

```
AI-Voice-Character-Skills/
├── Archer/
│   ├── README.md
│   ├── archer-character-voice.md
│   └── pam-character-voice.md
└── Futurama/
    ├── README.md
    └── bender-character-voice.md
```

Each show folder has its own `README.md` listing the characters available in it,
along with the activation/deactivation phrases for each skill.

## Contributing

New characters and shows welcome! To add one:

1. Fork the repo
2. Add your character file under the matching show folder (create a new folder
   for a new show)
3. Follow the existing file format for voice/tone/catchphrases
4. Open a pull request

## Disclaimer

All characters, names, and associated likenesses are the property of their
respective copyright holders. This project contains original prompt engineering
work only — no copyrighted scripts, dialogue, or other protected content is
reproduced here. Provided for personal, non-commercial, fan and educational use.

## License

MIT — see [LICENSE](LICENSE)
