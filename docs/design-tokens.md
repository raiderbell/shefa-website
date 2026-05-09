# Design Tokens

Source file: `src/styles/tokens.css`

## Usage rules

- **Navy holds structure.** Use `--navy` / `--surface-2` for backgrounds that carry weight.
- **Gold signals importance.** Use `--gold` once per composition. The header wordmark counts.
- **Never hardcode hex.** All values must reference CSS variables.
- **Never swap navy and gold.** If something should be gold, it has to earn it.

## Color reference

| Token | Dark value | Light value | Use |
|-------|-----------|-------------|-----|
| `--bg` | `#0B0F1C` | `#FFFFFF` | Page background |
| `--bg-2` | `#0E1424` | `#FAFAF7` | Alternate section bg |
| `--surface` | `#131A2E` | `#F8F8F8` | Cards, form fields |
| `--surface-2` | `#1C2B4A` | `#F5F5F5` | Header, elevated surfaces |
| `--border` | `#2A3854` | `#CCCCCC` | Borders, dividers |
| `--text` | `#E8ECF2` | `#1A1A1A` | Primary text |
| `--text-2` | `#C2CBD8` | `#2A2A2A` | Secondary text, body |
| `--text-mute` | `#8A97AA` | `#777777` | Labels, nav, captions |
| `--gold` | `#C4963A` | `#C4963A` | Accent — use once |
| `--navy` | `#1C2B4A` | `#1C2B4A` | Structure, callout borders |
| `--green` | `#3A7D44` | `#3A7D44` | Success callouts only |

## Font stacks

| Token | Value | Use |
|-------|-------|-----|
| `--font-sans` | Helvetica Neue stack | All body and UI text |
| `--font-mono` | System monospace | Labels, metadata, tags |
| `--font-hebrew` | Frank Ruhl Libre | שפע wordmark only |

## Layout

| Token | Value | Use |
|-------|-------|-----|
| `--page-max` | `1200px` | Max content width |
| `--gutter` | `clamp(20px, 4vw, 56px)` | Side padding |
| `--rule` | `1.5px` | Gold rule thickness |
