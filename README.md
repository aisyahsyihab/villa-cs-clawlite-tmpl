# Villa Customer Service - ClawLite Template

ClawLite template for creating a Villa Customer Service agent.

## Features

- 🏡 Room and facility information
- 💰 Pricing inquiry assistance  
- 📅 Booking process guidance
- 🌐 Bilingual support (Indonesian/English)

## Usage

```bash
clawlite instances new aisyahsyihab/villa-cs my-villa-agent
```

The wizard will prompt you for:
- Villa name
- Villa address
- Contact phone
- Check-in/check-out times

## Configuration

After instance creation, edit:

1. **`.env`** - Add your API keys (copy from `.env.example`)
2. **`workspace/TOOLS.md`** - Update room rates, facilities, payment info
3. **`workspace/SOUL.md`** - Customize persona if needed

## Start the Agent

```bash
clawlite instances start my-villa-agent
```

## Template Structure

```
workspace/
├── SOUL.md     # Agent persona and communication style
├── AGENTS.md   # Rules and response formats
└── TOOLS.md    # Villa info (rooms, rates, facilities)
```

## License

MIT
