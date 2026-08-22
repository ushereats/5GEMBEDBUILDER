# Embed Forge

A browser-based Discord embed & component builder with a live, pixel-accurate preview. No install, no backend — open the page and start building.

**🔨 Made entirely with AI.**

---

## ✨ Features

- **Live Discord-accurate preview** — see exactly what your message will look like before you send it
- **Two-way JSON sync** — edit in the builder or paste raw JSON directly; both stay in sync automatically
- **Imports raw Discord client dumps** — paste a message straight from Discord and it normalizes into the builder
- **Templates** — save and reload your designs (stored locally in your browser)
- **Built-in limit warnings** — flags anything that would get rejected by Discord's API (character counts, component counts, invalid colors, missing URLs) before you export

## 🧱 Supports every Discord message component

### Classic Embeds
- Title, description, URL, color
- Author (name, URL, icon)
- Thumbnail & image
- Footer (text, icon) + timestamp
- Up to 25 fields, inline or full-width
- Up to 10 embeds per message
- Legacy button rows (link, primary, secondary, success, danger)

### Components V2
- **Container** — with accent color and spoiler toggle
- **Section** — text + thumbnail accessory (with alt text and spoiler)
- **Text Display** — full Discord markdown (headings, lists, quotes, code blocks, spoilers, mentions, timestamps, custom emoji)
- **Media Gallery** — up to 10 images, each with optional alt text and spoiler
- **File** — attachment references
- **Separator** — with spacing control
- **Action Row / Buttons** — all functional button styles
- **Select Menus** — String, User, Role, Mentionable, and Channel selects, including channel type filters and default pre-selected values

Everything is checked against Discord's official component reference, including the fields most builders skip: spoilers, alt text, channel type filters, and default values.

*(Premium buttons and modal-only components like Text Input/Label are intentionally out of scope — this tool builds messages, not modals or monetized buttons.)*

## 🚀 Usage

1. Open `index.html` in any browser
2. Build your message using the panel on the left
3. Copy or download the generated JSON from the middle panel
4. Paste it into your bot, webhook, or Discord developer tool of choice

## 📄 License

The Discord preview renderer is adapted from [Discohook](https://github.com/discohook/discohook) (AGPL-3.0). Builder/editor code is original.
