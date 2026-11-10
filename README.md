# EGA, FGA and SGA: editions and translations

An index of the editions and translations of Alexander Grothendieck's *Éléments de géométrie algébrique* (EGA),
*Fondements de la géométrie algébrique* (FGA) and *Séminaire de géométrie algébrique du Bois Marie* (SGA) made in this
project: French transcriptions, and translations into English, Spanish, Brazilian Portuguese, Vietnamese, Korean and
Simplified Chinese, each with PDF readers and LaTeX sources.

Each edition has its own repository. The tables below say what each one contains, how complete it is, and where its
PDF is.

## Website

The website <https://kokunoyumeto.github.io/ega-fga-sga/> presents the text of the SGA volumes held here, in French,
English and Spanish: in French SGA 5, SGA 6 and SGA 7 (tomes I and II); in English SGA 1, SGA 2, SGA 4½, SGA 5,
SGA 6 and SGA 7; in Spanish SGA 1 and SGA 7. Each exposé has its own page with the printed page numbers, links
between the numbered statements and a search; machine-readable indexes of the statements and references (CSV and
JSON) are linked from the home page. Volumes and languages not yet on the website have pages that say so and link to
the editions that exist. The website is built from the editions' sources and published from this repository with
GitHub Pages (`.github/workflows/pages.yml`).

## How the editions were made

The French texts are AI-transcribed from the original printings. The translations are AI-translated, mostly by
OpenAI Codex models (GPT-5.6 Sol, GPT-6.1 Sol), whose work GPT-6 Astra (OpenAI Codex) checked, corrected and
assembled; parts of the English EGA and the November 2026 revision of the English SGA 3 are by Claude Opus 5.5
(Anthropic). Some translations used earlier human translations and typesetting
as references; each repository names the models, the source texts and the human contributions it used.

Errors may remain in every edition. The French EGA is being checked page by page against the printed volumes, and
its corrections are being carried into the English translation.

## EGA: *Éléments de géométrie algébrique*

By Alexander Grothendieck, with the collaboration of Jean Dieudonné; *Publications mathématiques de l'IHÉS* 4, 8,
11, 17, 20, 24, 28 and 32 (1960–1967).

| Language | Repository | Contents | PDF |
|---|---|---|---|
| French | [ega-fr](https://github.com/KokunoYumeto/ega-fr) | Complete: transcription of Chapters 0–IV in a diplomatic edition (the printed text) and a corrected edition, with separate mathematical notes | [corrected](https://github.com/KokunoYumeto/ega-fr/releases/download/ega-fr-2026-10-24-r20/EGA_French_Current_Cumulative_Reader.pdf) · [diplomatic](https://github.com/KokunoYumeto/ega-fr/releases/download/ega-fr-2026-10-24-r20/EGA_French_Diplomatic_Cumulative_Reader.pdf) |
| English | [ega-en](https://github.com/KokunoYumeto/ega-en) | Complete: Introduction, Chapters 0–IV | [PDF](https://github.com/KokunoYumeto/ega-en/blob/main/pdf/EGA_EN.pdf) |
| Spanish | [ega-fga-es](https://github.com/KokunoYumeto/ega-fga-es) | EGA II, EGA III, EGA IV parts 3 and 4; of EGA IV part 1, Chapter 0 only. EGA I and EGA IV part 2 are not included | [EGA II](https://github.com/KokunoYumeto/ega-fga-es/blob/main/readers/EGA_II/EGA_II_es_current.pdf) · [all PDFs](https://github.com/KokunoYumeto/ega-fga-es/tree/main/readers) |
| Brazilian Portuguese | [ega-fga-sga-pt-br](https://github.com/KokunoYumeto/ega-fga-sga-pt-br) | EGA III part 1 and EGA IV part 3 (PDF); EGA II and Chapter I of EGA I (LaTeX); single sections of other parts | [EGA III part 1](https://github.com/KokunoYumeto/ega-fga-sga-pt-br/releases/download/v2026-09-23-preview.2/019_EGA_III1_PTBR_CURRENT_READER.pdf) · [EGA IV part 3](https://github.com/KokunoYumeto/ega-fga-sga-pt-br/releases/download/v2026-10-26-ega-iv3/EGA_IV3_PTBR.pdf) |
| Vietnamese | [ega-fga-sga-vi](https://github.com/KokunoYumeto/ega-fga-sga-vi) | EGA III part 1 (PDF); EGA II and Chapter I of EGA I (LaTeX); single sections of other parts | [EGA III part 1](https://github.com/KokunoYumeto/ega-fga-sga-vi/releases/download/v2026-09-23-preview.2/025_EGA_III1_VI_CURRENT_READER.pdf) |
| Korean | [ega-ko](https://github.com/KokunoYumeto/ega-ko) | EGA I–III complete; of EGA IV part 1, Chapter 0, §§14–23 and Chapter IV, §1 (LaTeX) | [EGA I–III](https://github.com/KokunoYumeto/ega-ko/blob/main/reader/00_EGA_ko_CUMULATIVE_READER.pdf) |
| Chinese (Simplified) | [ega-zh-hans-cn](https://github.com/KokunoYumeto/ega-zh-hans-cn) | EGA I–III complete; of EGA IV part 1, Chapter 0, §§14–23 and Chapter IV, §1 (LaTeX) | [EGA I](https://github.com/KokunoYumeto/ega-zh-hans-cn/blob/main/releases/2026-09-23-ega-i-iii/01_ega1-zh-hans-cn.pdf) · [EGA II](https://github.com/KokunoYumeto/ega-zh-hans-cn/blob/main/releases/2026-09-23-ega-i-iii/04_ega2-zh-hans-cn.pdf) · [EGA III-1](https://github.com/KokunoYumeto/ega-zh-hans-cn/blob/main/releases/2026-09-23-ega-i-iii/07_ega3-1-zh-hans-cn.pdf) · [EGA III-2](https://github.com/KokunoYumeto/ega-zh-hans-cn/blob/main/releases/2026-09-23-ega-i-iii/10_ega3-2-zh-hans-cn.pdf) |

## FGA: *Fondements de la géométrie algébrique*

By Alexander Grothendieck: the Bourbaki seminar exposés 149, 182, 190, 195, 212, 221, 232 and 236 (1957–1962), their
errata and the 1962 comments.

| Language | Repository | Contents | PDF |
|---|---|---|---|
| French | [fga-fr](https://github.com/KokunoYumeto/fga-fr) | Complete transcription, corrected edition | [PDF](https://github.com/KokunoYumeto/fga-fr/releases/download/fga-fr-2026-08-30-r1/fga-fr-canon-errata-0001-0017.pdf) |
| English | [fga-en](https://github.com/KokunoYumeto/fga-en) | Complete | [PDF](https://github.com/KokunoYumeto/fga-en/releases/download/fga-en-2026-08-30-r1/fga-en-canon-errata-0001-0017.pdf) |
| Spanish | [ega-fga-es](https://github.com/KokunoYumeto/ega-fga-es) | Complete | [PDF](https://github.com/KokunoYumeto/ega-fga-es/blob/main/readers/FGA_CURRENT/FGA_ES_CURRENT.pdf) |
| Brazilian Portuguese | [ega-fga-sga-pt-br](https://github.com/KokunoYumeto/ega-fga-sga-pt-br) | Complete, corrected and diplomatic editions | [PDF](https://github.com/KokunoYumeto/ega-fga-sga-pt-br/releases/download/v2026-10-24-fga.1/001_FGA_PTBR_CURRENT.pdf) |
| Vietnamese | [ega-fga-sga-vi](https://github.com/KokunoYumeto/ega-fga-sga-vi) | Complete, corrected and diplomatic editions | [PDF](https://github.com/KokunoYumeto/ega-fga-sga-vi/releases/download/v2026-10-24-fga.1/00_FGA_vi_CURRENT_READER.pdf) |
| Korean | [fga-ko](https://github.com/KokunoYumeto/fga-ko) | Complete | [PDF](https://github.com/KokunoYumeto/fga-ko/releases/download/fga-ko-2026-10-24-r2/00_FGA_ko_CUMULATIVE_READER.pdf) |
| Chinese (Simplified) | [fga-zh-hans-cn](https://github.com/KokunoYumeto/fga-zh-hans-cn) | Complete | [PDF](https://github.com/KokunoYumeto/fga-zh-hans-cn/releases/download/fga-zh-hans-cn-2026-10-24-r3/00_FGA_zh_Hans_CUMULATIVE_READER.pdf) |

## SGA: *Séminaire de géométrie algébrique du Bois Marie*

SGA 1–7 (1960–1969) and SGA 4½ (1977), by Alexander Grothendieck and his collaborators, among them Michel Demazure,
Michael Artin, Jean-Louis Verdier, Pierre Deligne, Luc Illusie and Nicholas Katz.

| Language | Repository | Contents | PDF |
|---|---|---|---|
| English | [sga-en](https://github.com/KokunoYumeto/sga-en) | SGA 1–7 and SGA 4½ complete as published (SGA 1 has no Exposé VII; SGA 7 I has Exposés I, II and VI–IX); SGA 6 is complete, but only its last part has been fully compared with the French text | [PDF](https://github.com/KokunoYumeto/sga-en/releases/download/v2026-10-26-english-edition/00_SGA_EN_CUMULATIVE_LINKED_READER.pdf) |
| Spanish | [sga-es](https://github.com/KokunoYumeto/sga-es) | SGA 1–7 and SGA 4½ complete (13 books) | [PDF](https://github.com/KokunoYumeto/sga-es/releases/download/v2026-09-23-r20/00_SGA_ES_CUMULATIVE_LINKED_READER.pdf) |
| Brazilian Portuguese | [ega-fga-sga-pt-br](https://github.com/KokunoYumeto/ega-fga-sga-pt-br) | SGA 4½ complete; SGA 3, Exposés VIII and IX; SGA 5, Exposés III, III B, X and XV | [SGA 4½](https://github.com/KokunoYumeto/ega-fga-sga-pt-br/releases/download/v2026-09-23-preview.3/01_SGA4half_PTBR_Atual.pdf) · [SGA 3](https://github.com/KokunoYumeto/ega-fga-sga-pt-br/releases/download/v2026-10-26-sga3.1/SGA3_TOMO_II_PTBR_ATUAL.pdf) · [SGA 5](https://github.com/KokunoYumeto/ega-fga-sga-pt-br/releases/download/v2026-09-07-preview.1/SGA5_PTBR_R4_20260829.pdf) |
| Vietnamese | [ega-fga-sga-vi](https://github.com/KokunoYumeto/ega-fga-sga-vi) | No SGA volume yet | |

## Original texts

- EGA: [Numdam, *Publications mathématiques de l'IHÉS*](https://www.numdam.org/journals/PMIHES/).
- FGA: [Numdam](https://www.numdam.org/) (Séminaire Bourbaki) and the
  [Grothendieck Circle](https://webusers.imj-prg.fr/~leila.schneps/grothendieckcircle/FGA.pdf).

## Rights

This index is dedicated to the public domain under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
Each edition states its own rights; the rights in the original works are not affected.
