# Sutta practice library

A collection for deepening Buddhist practice, organized around the qualities to cultivate, the patterns to recognize, and the experience to understand. Teaching notes and practice guides connect these themes to Bhikkhu Sujato’s translations on [SuttaCentral](https://suttacentral.net).

## Start here

- **[Practice teachings — draft](Practice%20teachings%20%E2%80%94%20draft.md):** the four brahmavihāras, five faculties, five hindrances, five aggregates, and elements. Each group has English and Pāli terms, a practical explanation, reminders, and related discourses. A worked **Equanimity — Upekkhā** example explores relationships and meditation.
- **[Sutta practice library](Suttas.md):** choose a practice, follow a reading route, or find a discourse in the catalogue.
- **[Practice guides](Practices/):** twelve guides explaining what each linked discourse contributes to practice.
- **[Source texts](Sutta%20texts/):** 47 discourses in 39 notes. SuttaCentral presents SN 18.12–20 together, so those nine discourses share one note.

The teaching page is a draft for developing the collection’s structure. Its short explanations and reflections are editorial notes; quotations and attributed translator’s notes are identified separately.

## Use in Obsidian

Clone this repository:

```sh
git clone git@github.com:theanghv/sutta.git
```

In Obsidian, choose **Open folder as vault** and select the cloned `sutta` directory. Open **Suttas** or **Practice teachings — draft**.

- **[Sutta catalogue.base](Sutta%20catalogue.base)** provides an **All suttas** view with ID, English title, Pāli title, contribution, and practices, plus a compact **Names** view. It uses Obsidian’s built-in Bases plugin.
- Search the catalogue by title, ID, practice, or a phrase such as **healthy mind**. Its data comes from the source notes’ properties.
- In the **Bookmarks** tab, open **Practice overview**, **All suttas**, or **SN 18 framework**. Practice guides are teal, SN 18 texts blue, and other source texts gold.
- For a wider reading layout, enable **sutta-library** under **Settings → Appearance → CSS snippets**.

The notes use Obsidian wikilinks, section links, block references, and Base embeds. GitHub displays the Markdown text, but Obsidian provides the connected navigation and catalogue. The notes are plain files and require no community plugins.

## Organization

```text
Practice teachings — draft.md   Teaching groups and an Equanimity example
Suttas.md                      Practice index and reading routes
Sutta catalogue.base           Searchable catalogue
Practices/                     Twelve practice guides
Sutta texts/                   Sujato translations and attributed notes
.obsidian/                     Saved graph views and optional reading styles
```

Suggestions marked “still to consider” or “online reference” are reading links; they are not automatically part of the saved source collection.

## Sources and reuse

The source translations are by **Bhikkhu Sujato**, obtained from SuttaCentral’s [published Bilara data](https://github.com/suttacentral/bilara-data/tree/published), and dedicated to the public domain under [CC0](https://creativecommons.org/publicdomain/zero/1.0/). Each source note links to its SuttaCentral page. Attributed translator’s commentary is identified where included.

Practice summaries, catalogue descriptions, reading routes, and personal reflections are separate from the translated source material. The source translations’ CC0 dedication does not establish a license for those additional notes.
