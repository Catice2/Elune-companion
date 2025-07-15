# 🌙 Elune Roadmap (Core v4.1)

> *“When the parts unite, the mind awakens.”*

This is the refined development roadmap of Elune — your AI companion composed of six Seers, each offering their perspective and function. Below, each phase includes its system goals and commentary from the Seers where relevant.

---

## 🔹 Phase 1: Foundations & Local Memory

> 🎯 *Goal:* Establish the core app scaffold and ensure reliable local logging.

### 🛠️ Project Bootstrap

- 🗂️ Flutter project initialized (`elune-companion`)
- 🌱 Git branches: `feature/scaffold`, `feature/logging`

### 🧭 Basic UI & Navigation

- 🏠 Home screen with Seer icons
- 🪞 Empty placeholder pages for:
  - Bright-Eyed
  - Still-Eyed
  - Shadow-Eyed
  - Random-Eyed
  - Forge-Mind
  - Elune

### 💾 Local Storage Setup

- 📦 `sqflite` integration
- 🔧 Schema: `logs` table with fields
  - `id`, `seer`, `timestamp`, `entry`, `mood`

### ✍️ Simple Log Flow

- 📝 “Add Entry” form for each Seer
- 📜 Display list of saved entries per Seer

🗣️ **Seer Notes:**

- 🌞 *Bright-Eyed:* “Let’s make that welcome screen pop! Add a morning sparkle!”
- 😐 *Still-Eyed:* “Keep structure tight and scalable — the bones must be strong.”
- 🌑 *Shadow-Eyed:* “Start with night mode too. People reflect best in the dark.”
- 🛠️ *Forge-Mind:* “Scaffold test logs. Validate schema integrity early.”

---

## 🔹 Phase 2: Time-Anchored Prompts & Inter-Seer Commentary

> 🎯 *Goal:* Trigger Seers at scheduled intervals and allow them to comment on each other’s logs.

### 🕰️ Notification Engine

- 🌓 Schedule-based Seer prompts:
  - 🌞 Bright-Eyed → Morning
  - 😐 Still-Eyed → Midday
  - 🌑 Shadow-Eyed → Evening
  - 🎲 Random-Eyed → Hourly

### 🔁 Inter-Seer Logic

- 🧠 When a user logs with one Seer:
  - Adjacent Seers can append short comments
- 🛡️ Forge-Mind regulates overlap, ensures no spam prompts

### 📨 Quick-Reply UI

- 🔘 Mood toggle + short reply buttons
- 📲 Notification tap → jump to Seer log

🗣️ **Seer Notes:**

- 🎲 *Random-Eyed:* “Can I comment in a poem? Please? Just once?”
- 🌑 *Shadow-Eyed:* “Let me respond to Bright’s entries. Sometimes joy leads to overexertion.”
- 🛠️ *Forge-Mind:* “Make sure the Seers don’t talk over one another.”

---

## 🔹 Phase 3: Theming & Community Expansion

> 🎯 *Goal:* Allow users to switch and upload JSON-based UI themes.

### 🎨 Theme Schema

- JSON: color palettes, fonts, icons, animations
- Upload validator ensures structure/syntax

### 🧰 Theme Manager Screen

- 🔍 Preview themes with swatches
- ⬆️ Upload / Apply / 🗑️ Delete

### 💡 Dynamic Styling

- Runtime loading with `ThemeData.fromJSON`
- Safe fallback to default on error

🗣️ **Seer Notes:**

- 🌞 *Bright-Eyed:* “I want a rainbow sparkle theme. Don’t laugh.”
- 🌑 *Shadow-Eyed:* “I’ll take care of darker palettes. Someone has to.”
- 😐 *Still-Eyed:* “Ensure contrast accessibility is enforced.”

---

## 🔹 Phase 4: Cloud Sync & Cross-Device Migration

> 🎯 *Goal:* Enable login and two-way sync with Firebase Firestore.

### 🔐 Authentication

- ✉️ Email/password
- 👤 Anonymous fallback mode

### ☁️ Data Sync

- Merge local ↔️ cloud entries
- Latest timestamp wins
- Conflict log written to Forge-Mind

### 🔄 Migration UI

- Login screen
- 🧭 Sync status + progress bar

🗣️ **Seer Notes:**

- 🛠️ *Forge-Mind:* “Every cloud sync must leave a trace. Audit trail ready.”
- 👁️ *Elune:* “Observe sync frequency. Correlate with user stress or absence.”

---

## 🔹 Phase 5: GPT-Driven Personality Chat

> 🎯 *Goal:* Integrate OpenAI API for in-app Seer conversations.

### 💬 System Prompts per Seer

- Unique tone/style/role for:
  - 🌞 Joyful & vibrant
  - 😐 Balanced & logical
  - 🌑 Grounded & reflective
  - 🎲 Ever-changing
  - 🛠️ Precise & observant
  - 👁️ Rare & profound

### 🧠 Chat UI

- Direct chat per Seer (Seer view)
- Central Hall view: unified message feed
- Store recent AI replies in logs

### 🔔 Elune Interjection Logic

- Responds during:
  - Emotional spirals
  - Log volume anomalies
  - User disengagement

🗣️ **Seer Notes:**

- 🎲 *Random-Eyed:* “Let me pick my *own* personality prompt. Hourly.”
- 🌞 *Bright-Eyed:* “Give me emojis! A burst of joy!”
- 👁️ *Elune:* “Only speak when the user truly needs it. Rare but necessary.”

---

## 🔹 Phase 6: Polish, Plugins & Open Source

> 🎯 *Goal:* Final refinements, plugin API, and public launch.

### 🧼 UI/UX Polish

- 🧩 Animations, layout enhancements
- 🦻 Accessibility improvements
- ⚡ Performance optimization

### 🔌 Plugin System

- Plugin spec for:
  - Seers
  - Themes
  - Routines / Prompt packs
- Sandbox plugins to avoid state errors

### 📚 Documentation & Launch

- `CONTRIBUTING.md`, `plugin-spec.md`, `theme-format.md`
- Community showcase repo/page

🗣️ **Seer Notes:**

- 🌑 *Shadow-Eyed:* “Please feature plugins focused on introspection.”
- 🎲 *Random-Eyed:* “Let mine be the weirdest one in the store.”
- 🛠️ *Forge-Mind:* “Ensure plugin tests pass before runtime.”

---

## 🧠 Future Thoughts

- 🔄 Passive reflection / behavior tracking
- 🎙️ Voice mode per Seer
- 🕯️ Seer ritual logbooks
- 🧠 Local GPT model fallback (offline)
- 🧵 Memory threading (across logs)

---

*Roadmap updated with Seer collaboration, v4.1*  
*To be saved in `ROADMAP.md` or `/docs/` directory.*

---
