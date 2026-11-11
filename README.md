<div align="center">

# UNIVERSAL FURRY LOREBOOK
**Strict anthropomorphic world-building & prose enforcement for SillyTavern.**

![Target](https://img.shields.io/badge/SillyTavern-World_Info-000000?style=for-the-badge)
![Scope](https://img.shields.io/badge/Scope-Global-blue?style=for-the-badge)
![Species](https://img.shields.io/badge/Species-Canines_%26_Felines-success?style=for-the-badge)
![Rating](https://img.shields.io/badge/NSFW-Supported-red?style=for-the-badge)

</div>

> [!IMPORTANT]
> **Strict Species Scope:** Currently supports **Canines** and **Felines** (with **Equines** next on the list). I have zero plans to include reptiles, rodents, bears, avians, insects, etc. If you want them -  feel free to fork the lorebook and add them yourself.

---

## // Why?
Because I'm tired of seeing kemonomimi and ferals when I want pure anthro. I'm tired of furry lorebooks on Chub.ai being locked to specific character cards instead of working globally. 

**The goal:** A universal, plug-and-play furry world that works with *any* scenario and forces the LLM to respect anthro anatomy.

## // What This Lorebook Changes

* **100% Anthro World:** Brands, TV, celebrities, background characters — everyone is furry.
* **No Humans / No Kemonomimi:** Humans as a species are completely wiped from the context.
* **Strict Anatomy:** Bipedal, plantigrade legs and paw-hands with pawpads and claws.
* **Dynamic Body Language:** Ears and tails move independently and remain active *throughout* a single reply (no more static poses).
* **Prose & Metaphor Fix:** Eliminates jarring human-centric comparisons (e.g., *"like a human who can't wait..."*).

### Prose Comparison:
```diff
- BEFORE: "Her face flushed. His skin was warm as she pressed her lips to his."
+ AFTER:  "Her ears pinned back. Fur lay taut over muscle as she pressed her muzzle to his."
```

---

## // Tested Models

* **DeepSeek v4.1 flash 1017** — Primary testing ground. *(Why not Claude/Argon/GLM? Because I don't have millions of dollars to burn on API tests, lol).*
* **Gemini 3.7** — Works really well!

---

## // Installation & Setup

### 1. The Lorebook
It's dead simple:
`World Info (Lorebook Menu)` ➔ `Import` ➔ `Set as Global` ➔ **Enjoy.**

### 2. Megumin Suite V11
Included in this repo is a modified V11 engine preset that strips human bias at the system prompt level.
1. Go to `Dev Mode` ➔ `Engines` ➔ `Import`.
2. Select `V11_Тайна_DeepSeek_(Copy).json` (or whatever you renamed it to).
3. Activate it in your presets.

> [!NOTE]
> **What does this engine do?** It's a modified *"V11 Тайна DeepSeek"* where instances of `person` and `people` in the Main prompt are replaced with `character` and `characters`. You can easily apply this same tweak to your own favorite presets!

---

## // Prompting Tips
To prevent the LLM from hallucinating human traits or kemonomimi, adjust the vocabulary in your character cards and local lorebooks:

| ❌ Avoid Using | ✅ Use Instead |
| :--- | :--- |
| `wolf-girl`, `cat-boy` | `she-wolf`, `tomcat`, `feline` |
| `people`, `person(s)` | `anthro(s)`, `character(s)`, `NPC(s)` |
| `face`, `skin`, `hands`, `feet` | `muzzle`, `fur/hide`, `paws`, `hindpaws` |

---

## // Roadmap (TODO)
- [x] Canines
- [x] Felines
- [ ] Equines
- [ ] Earn more money and test on Gemini 4 Argon *(mission impossible)*

---

## // Links, Contacts & Credits

Need help, want to contribute, or just chat? Hit me up on Discord: **`jolinckelpe`** (main) or **`pb001b`** (alt).

[![Chub V2](https://img.shields.io/badge/Chub.ai-Lorebook_V2_(Latest)-orange?style=for-the-badge)](https://chub.ai/lorebooks/glum_celebration_90021/universal-furry-lorebook-canines-and-felines-837d1f915f4e)
[![Chub V1](https://img.shields.io/badge/Chub.ai-Lorebook_V1_(Legacy)-grey?style=for-the-badge)](https://chub.ai/lorebooks/glum_celebration_90021/furry-4c42eb92b1e5)

*(Note: Chub.ai updates may be delayed by a few years).*

**Credits:**
* Base Preset: [Megumin Suite Beta (V11)](https://github.com/Arif-salah/Megumin-Suite-Beta)
