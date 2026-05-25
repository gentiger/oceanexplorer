# 🌊 Ocean Explorers

A browser-based educational game for **5-year-olds** in Malaysia and Singapore, designed to build curiosity and empathy for ocean life through play.

🎮 **[Play Now → gentiger.github.io/oceanexplorer](https://gentiger.github.io/oceanexplorer)**

---

## 🐠 About the Game

Ocean Explorers lets young children swim as a **Clownfish** through a vibrant coral reef, learning about the ocean ecosystem through intuitive tap-to-play mechanics — no reading required.

Guided by **Tino the Hawksbill Sea Turtle**, players:
- 🦐 Hunt for glowing zooplankton to eat
- 🌿 Hide in the sea anemone when a Grouper predator arrives
- 🏅 Earn a Junior Ocean Passport stamp on completion
- 📖 Discover the Clownfish's habitat, diet, and endangered status through an interactive Fact Card

---

## 🎯 Design Philosophy

| Principle | Implementation |
|---|---|
| **No reading required** | All instructions delivered via Tino's voice bubbles and visual cues |
| **Fat-finger friendly** | All hitboxes are 2× the visual size; minimum 44px touch targets |
| **Non-violent** | Predator encounters use bubble transitions — no biting animations |
| **Soft realism** | Accurate fish anatomy with warm colours and expressive eyes |
| **Local relevance** | Hawksbill Sea Turtle guide (native to MY/SG waters); passport stamp mechanic familiar from Science Centre SG and Aquaria KLCC |

---

## 📱 Platform Support

| Platform | Support |
|---|---|
| 🖥️ Desktop (Chrome, Firefox, Safari, Edge) | ✅ Full |
| 📱 Phone — landscape | ✅ Full |
| 📱 Phone — portrait | ⚠️ Rotate prompt shown |
| 📟 Tablet — landscape | ✅ Full |
| 📟 Tablet — portrait | ⚠️ Rotate prompt shown (large iPads playable) |

---

## 🕹️ How to Play

1. Tap the **Passport cover** to begin
2. Wait for **Tino** to swim in, then tap the **glowing Clownfish**
3. **Tap anywhere** on the reef to swim your fish
4. Collect all **3 glowing zooplankton** 🦐
5. When the **amber glow** appears — a Grouper is coming! Tap the **green-glowing anemone** 🌿 to hide
6. Collect all 3 to earn your **🏅 Clownfish Expert stamp**
7. Tap each button on the **Fact Card** to learn more!

---

## 🗂️ Project Structure

```
oceanexplorer/
└── index.html      # Complete self-contained game (HTML + CSS + JS)
```

No build tools, no dependencies, no server required. Open `index.html` in any modern browser.

---

## 🌱 Roadmap

Based on the full Product Requirement Document (PRD):

- [ ] **v1.0** — Clownfish prototype *(current)*
- [ ] **v1.1** — Add Parrotfish & Bluefin Tuna levels
- [ ] **v1.2** — Add Anglerfish (Deep Sea biome) & Great White Shark
- [ ] **v2.0** — "My Safe Ocean" virtual aquarium (unlock fish to live together)
- [ ] **v2.1** — Bahasa Malaysia / Mandarin audio narration support
- [ ] **v3.0** — Expand to 20+ ocean species

---

## 📄 Background

This game is the prototype from the **Ocean Explorers PRD** — a full product design session covering:
- Market research (MY/SG EdTech trends, CAGR >14%)
- Target audience: 5-year-olds, pre-readers
- UX: tap-to-move, fat-finger hitboxes, no text in gameplay
- Reward mechanic: Junior Ocean Passport (culturally familiar in SG/MY)
- Empathy-building: first-person animal storytelling, Heart Meter for endangered status
- Success metrics: D3 retention >35%, task completion >80%, fact card engagement >60%

---

## 🐢 Credits

Designed and built with ❤️ for young ocean explorers in Malaysia and Singapore.

*"The ocean is calling — are you ready to explore?"* — Tino the Turtle
