# Borozdov Ribbon

A theme from the Borozdov collection. Two faces — light **Cambric**, ink on white
ledger paper, and dark **Bullion**, the same ledger after the vault door closes. One
sans at one weight carries every size from a caption to an inline title; the only
colour in either face is a ribbon lying flush across the top of every tab strip —
cream on Cambric, bullion gold on Bullion.

![Borozdov Ribbon in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/ribbon/main/screenshots/light.png)

![Borozdov Ribbon in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/ribbon/main/screenshots/dark.png)

## Principles

- **One weight, every size.** Headings never turn bold — the jump from a subheading
  to a heading is carried by size alone, the way a ledger's totals stand out by being
  larger, not heavier.
- **A single ribbon.** One warm accent, and only one: a strip across the top of every
  tab header and the highlighter's own ink. Nowhere else does either face reach for
  colour.
- **A hairline builds every card.** Callouts, code panes, tables and popovers round
  to the same 20px corner with a 1px rim, never a shadow — elevation here is a line,
  not a cast shade.
- **Cambric by day, Bullion by night.** The same ink-on-paper structure runs both
  ways: paper and ink swap ends, and the ribbon itself turns from cream to gold.
- **Developer-native type.** The platform's own sans for text and headings alike; no
  embedded font, no load, no flash of unstyled text.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts, code blocks, embeds, tables and popovers drawn as the same hairline-rimmed
  card at a single 20px radius
- A table draws its own rounded frame; cells only carry the inner grid, so no edge is
  ever doubled
- Tags and pills go fully round and invert to solid ink under the pointer
- The highlighter stays an opaque cream or gold with ink on top, so a note never grows
  an olive smear by night
- Quiet editing: no focus ring around the note, its title or form fields while you
  type; property names read as labels, not boxed fields
- A toggle thumb tuned per face so it never disappears against its own track
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts, so the theme stays well under the directory's size limit
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Ember**. Install Borozdov Ember under Settings → Appearance → Themes → Manage, then the
[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and choose
**Ribbon** under Style Settings → Borozdov Ember → Variant. The variant brings this
theme's palette, type and corners; its own layout, and its embedded font if it has one,
come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/ribbon/releases/latest)
into `<vault>/.obsidian/themes/Borozdov Ribbon/`, then choose Borozdov Ribbon under
Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Cambric» — чернила на
белой бумаге гроссбуха, и тёмный «Bullion» — та же страница после того, как закрылась
дверь хранилища. Один гротеск одного начертания несёт любой размер, от подписи до
заголовка страницы; единственный цвет в обоих ликах — лента поперёк верха каждой
полосы вкладок: кремовая на Cambric, цвета червонного золота на Bullion. Шрифты не
встроены. В каталоге тема живёт вариантом Borozdov Ember: установите Borozdov Ember и плагин Style Settings, затем выберите Ribbon в Style Settings → Borozdov Ember → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
