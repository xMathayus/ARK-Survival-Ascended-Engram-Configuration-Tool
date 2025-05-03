# ARK: Survival Ascended Engram Configuration Tool

A modern, browser-based toolset for customizing `Game.ini` overrides in **ARK: Survival Ascended**. Built for server admins and modders who want full control over how engrams and crafting recipes behave — all without touching `.ini` files manually.

> No installs. No backend. 100% client-side.

---

## 🌟 Features

### ✅ Engram Editor
- Supports **all official DLC content**
  - Categorized by Base Game, Scorched Earth, Aberration, Extinction, Genesis 1 & 2, and more.
- **Automatic mod detection**
  - Groups third-party engrams under a collapsible “Third-Party Mod Engrams” section.
- **Toggleable sections**
  - Easily hide/show cosmetics like skins.
- **Live table editing**
  - Change level requirements, engram costs, visibility, and prerequisites directly.
- **Import existing config lines**
  - Paste `OverrideNamedEngramEntries` or raw `EngramEntry_Example_C` lines.
- **One-click Game.ini output**
  - Generates fully formatted `OverrideNamedEngramEntries` ready to paste into your config.

---

### 🧪 Crafting Recipe Editor
- **Crafting override support** via `ConfigOverrideItemCraftingCosts`
- Edit ingredients for individual engrams
- Add/remove items with dropdown search
- Generate ready-to-use `Game.ini` override lines

---

## 📦 File List

- `EngramsEditor.html` — Engram Editor
- `CraftingEditor.html` — Crafting Override Editor
- `EngramsList.js` — Full engram data list
- `DefaultCraftingRecipes.js` — Default recipe definitions
- `CraftingItems.js` — Ingredient lookup for recipe editor
- `Background.jpg` — ASA-themed background

---

## 📄 Use Cases

- Server admins fine-tuning progression
- Modders balancing engram availability and recipes
- Visual editing of `.ini` override entries

---

## ☕ Support

If you find the tool helpful, consider supporting the developer:  
[Buy me a coffee](https://ko-fi.com/mathayus)

---

## 📘 License

MIT — free to use and modify.

