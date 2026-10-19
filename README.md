### Xiang Li — music AI, systems and tooling

I build systems that turn music into data you can check, and the tools around them: a transcription
pipeline, the validator that says which grid a song can be trusted on, and the annotation app I listen with.

**Now: AI4Music / Workbench.** The aim is one representation of a song — chords, bass, melody, rhythm,
part activity and playing technique all mapped onto a single discrete time axis — and then to find
structure in it (sections, boundaries, transitions) without supervision.

- **Workbench** — audio → beat/downbeat grid (Beat This!, madmom, Mapperatorinator, human taps) →
  note layers (bass, guitar, piano, drums, vocals, each from whichever open model survives listening
  tests) → chords, keys, structure.
- **MGMCS validator** — per-song timing admission: which grid readings still stand, and which ranges
  have to be treated with caution. Downstream reads this verdict; it does not re-decide it.
- **listening-ai** — Android annotation app: on-device musicnn chord recognition plus a local Qwen
  sidecar, for listening passes and label fixes.
- **Research** — masked reconstruction on a self-built 300–400 song corpus, audio-derived layers
  measured against a MIDI ceiling, and how much of the gap is label noise rather than model capacity.

Two rules I keep: the ears decide and metrics only size the effect; and a rule is either applied to
the whole library or dropped — no per-song hand-tuning.

Before this: game design — the rules, the numbers, the editors other people author content with, and
the checks that tell me whether any of it works.

Currently finishing an MSc in Business Administration (International Business) at the University of Amsterdam.
Before that: equipment and gem systems at SAGI Games, production coordination and build testing at TAIKO Studios,
localization QA at MPMF.

**Looking for:** a six-month internship from February 2027 in Amsterdam — game design, systems design,
technical design, or music-AI tooling and research engineering. 32 hours per week alongside my studies.

---

#### Selected work

| Project | What it is | Status |
| --- | --- | --- |
| **[FallenAngel](https://github.com/lixiang021011-sketch/FallenAngel)** | Roguelike rhythm game: songs are encounters inside a run rather than trophies you retire, and you perform one instrument's part of each song | Playable; content and the build layer next |
| **[StylesVN](https://github.com/lixiang021011-sketch/StylesVN)** | Visual-novel pipeline where the script is data — 9 chapters, 495 staged instructions, validated and self-tested by one command | In progress |
| **Game Forge** | Zero-dependency local dashboard that runs my projects and turns each one's README and Git state into the next three steps | 11 automated tests |
| **Bell Garden** | Metroidvania vertical slice: abilities that open the map, enemies that read the player, a three-phase boss | In progress |

#### How I work

- **Design claims get tested, not asserted.** If a design says "playing better should pay better", there is a simulation behind that sentence — and its boundary conditions are written down too.
- **Production problems become tool problems.** When content costs too much to produce, the answer is a tool, not more hours. When the tool is not good enough, that answer gets abandoned rather than defended.
- **Automation verifies state; people verify feel.** Automated checks confirm that systems behave. Whether something feels right is decided by playing it.

On AI, since my CV says so directly: AI writes most of the implementation. The design decisions, the scope rules and
the on-device testing are mine. Code implements decisions that have already been made; design is deciding what to make.

#### More

- **Portfolio page** — the guided tour, with figures: <https://lixiang021011-sketch.github.io/>
- **Project manual (PDF, 30 pages)** — <https://lixiang021011-sketch.github.io/assets/xiang-li-project-manual.pdf>
- **Contact** — lixiang021011@gmail.com · Amsterdam, the Netherlands
