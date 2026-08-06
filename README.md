# 💻 The Interactive Software & Memory Journey

A single-file, zero-dependency interactive web app that teaches **Chapter 1: Computer Software** and **Chapter 2: Computer Memory** to young students (around 4th grade). Switch between chapters with the **① Software / ② Memory** buttons under the title.

👉 **Live app:** open `index.html` in any browser, or visit the GitHub Pages link (see the repo's About section).

## Chapter 1 — Computer Software

- **🏁 Start** — Hardware vs. Software, machine language, and the two software families.
- **🧰 Hardware** — every computer part (input, output, processing, storage) as tappable cards, plus an Input-vs-Output sorting game.
- **⚡ Signal Odyssey** — press a key or click the mouse and watch a signal race through all 5 system-software checkpoints (Firmware → Device Driver → OS → Language Translator → Utility). Flip any switch **OFF** to see the computer "crash" at that exact step. Full working keyboard.
- **🧩 The 5 System Software** — deep-dive cards with real examples from the chapter.
- **📱 Application Software** — working demos: a rich-text Word Processor, a Presentation slideshow, and a mock Web Browser.
- **🧠 Quiz** — a live-scored quiz built from the chapter's Checkpoint and Exercises (match, multiple-choice, fill-in-the-blanks, true/false).
- **🔤 Word Hunt** — the Activity Hub word search.
- **🖥️ Full PC** — a working desktop: **drag the mouse** to move the pointer, **click** to open apps (Files, Browser, Notepad, Antivirus…), type into Notepad, and watch a **Serial Monitor** narrate every interaction, tagged by the responsible system software.

## Chapter 2 — Computer Memory

- **🎨 Simon Says** — a fully playable memory game. The colour sequence you're holding in your head *is* RAM; hit "Simulate Power Cut" and watch it vanish.
- **🔄 IPO Cycle** — type a word and watch Input → Processing → Output animate, with all three kinds of data appearing in memory.
- **🗺️ Memory Map** — the primary/secondary classification tree, every box tappable.
- **⚡ RAM vs ROM** — write data into RAM, try (and fail) to write into ROM, then flip the power switch: **RAM is wiped, ROM survives.** Plus DRAM/SRAM and PROM/EPROM/EEPROM.
- **🎮 Memory Arcade** — the centrepiece. A **Flappy Bird game wired to live memory chips**: RAM cells (`bird_y`, `bird_speed`, `score`…) update every frame as you fly, while ROM (`gravity`, `flap_power`…) never changes. A **Signal Bus** narrates each read and write, and **Cut Power** erases RAM while ROM stays perfectly intact.
- **💾 Secondary Memory** — Hard Disk, SSD, CD, DVD, Blu-ray and Pen Drive, with capacity bars drawn to scale.
- **🧠 Quiz** and **📋 Recap** for the chapter.

## Tech

- One HTML file. All CSS and vanilla JavaScript inline.
- No images, no external fonts, no libraries — graphics are emoji + CSS/SVG.
- Fully responsive, works on desktop and mobile.

## Usage

Just open `index.html` — no build step, no server required.
