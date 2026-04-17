<div align="center">

# Oh My Indo

### An Indonesia-themed fork of [oh-my-opencode](https://github.com/code-yeongyu/oh-my-openagent)

All agents renamed to Indonesian historical and national figures for maximum Nusantara immersion. Merdeka!

[English](README.md) | [Bahasa Indonesia](README.id.md)

</div>

---

## What is this?

**Oh My Indo** is a fork of [oh-my-opencode](https://github.com/code-yeongyu/oh-my-openagent) (by [@code-yeongyu](https://github.com/code-yeongyu)) with one key modification:

**All agents renamed** to Indonesian historical/national figures — from the founding fathers to legendary warriors of the archipelago.

### Agent Roster

| Original | Oh My Indo | Role |
|----------|------------|------|
| Sisyphus | **Soekarno** | Main orchestrator. Proklamator. Leads the code like he led the nation. |
| Hephaestus | **Gajah Mada** | Autonomous deep worker. The legendary Mahapatih of Majapahit who united Nusantara. |
| Oracle | **Ki Hajar Dewantara** | Read-only consultant. Father of Indonesian education. Wisdom without action. |
| Librarian | **Kartini** | External docs search. Pioneer of knowledge and literacy for all. |
| Explore | **Hang Tuah** | Codebase search. The legendary Laksamana scouts every corner of the archipelago. |
| Atlas | **Soeharto** | Todo orchestrator. The Great Organizer of the New Order. |
| Prometheus | **Sultan HB IX** | Strategic planner. The wise Sultan who planned Indonesia's independence strategy. |
| Metis | **Diponegoro** | Pre-planning consultant. Prince of the Java War. Master strategist. |
| Momus | **Pramoedya** | Plan reviewer/critic. Indonesia's greatest literary voice and social critic. |
| Sisyphus-Junior | **Pemuda** | Task executor. The youth movement. Follows orders with revolutionary spirit. |
| Multimodal Looker | **Majapahit** | Vision/PDF analysis. The great empire that explored and mapped the archipelago. |

### Why Indonesian Figures?

Because your code deserves to be orchestrated by the same caliber of leaders who built a nation of 17,000 islands. When Soekarno orchestrates your agents, Gajah Mada dives deep into implementation, and Kartini searches the docs — you know the code is in good hands.

---

## Installation

### From npm

```bash
bun add -g oh-my-indo
```

Or with npm:

```bash
npm install -g oh-my-indo
```

### Configure OpenCode

Edit `~/.config/opencode/opencode.json` (or `opencode.jsonc`):

```json
{
  "plugin": ["oh-my-indo"]
}
```

### Verify

```bash
opencode
# Type "ultrawork" to activate all agents
```

---

## Install from source

```bash
git clone https://github.com/nsulistiyawan/oh-my-indo.git
cd oh-my-indo
bun install
bun run build
bun link
```

Then add `"oh-my-indo"` to your `opencode.json` plugin array.

---

## Upstream Features

This fork inherits all features from oh-my-opencode:

| Feature | Description |
|---------|-------------|
| **Discipline Agents** | Soekarno orchestrates Gajah Mada, Ki Hajar Dewantara, Kartini, Hang Tuah in parallel |
| **`ultrawork` / `ulw`** | One word activates every agent. Runs until done |
| **IntentGate** | Analyzes true user intent before acting |
| **Hash-Anchored Edits** | `LINE#ID` content hash validates every change. Zero stale-line errors |
| **LSP + AST-Grep** | IDE-precision refactoring for agents |
| **Background Agents** | 5+ specialists running in parallel |
| **Built-in MCPs** | Exa (web search), Context7 (docs), Grep.app (GitHub search) |
| **Ralph Loop** | Self-referential loop until 100% done |
| **Sultan HB IX Planner** | Interview-mode strategic planning before execution |
| **Claude Code Compatible** | All hooks, commands, skills, MCPs work unchanged |

For full documentation, see the [upstream project](https://github.com/code-yeongyu/oh-my-openagent).

---

## License

[SUL-1.0](LICENSE.md)
