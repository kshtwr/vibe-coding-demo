# Design doc: Boba Picker

## Mood
Retro terminal, playful, late-night hackathon. Think pixel arcade, not corporate dashboard.

## Colors
| Role | Hex |
|---|---|
| Background | `#001a33` (deep Berkeley blue) |
| Panel / card | `#003262` (Berkeley blue) |
| Accent (buttons, borders, highlights) | `#fdb515` (California gold) |
| Accent shadow | `#8a6200` |
| Main text | `#f5f0e6` (cream) |
| Muted text | `#8fa4b8` |

## Fonts
- **Headings and labels:** Silkscreen (pixel font), uppercase
- **Body text:** IBM Plex Sans
- **Small terminal-style text:** IBM Plex Mono

## Layout
- One centered column, at most 520px wide, so it works on phones
- A faint gold grid in the background
- Order, top to bottom: terminal prompt line, big title, order card, history list, footer
- Generous spacing (24px between blocks)

## Components
- **Card:** blue panel, 3px gold border, hard 6px offset shadow, no rounded corners
- **Button:** gold fill, dark text, pixel font, hard shadow that disappears when pressed
- **History list:** monospace text, thin divider lines, newest pick on top
- **Cursor:** blinking gold block after the terminal prompt line

## References
- Our group site: ucberkeley-ai.vercel.app (colors, fonts and card style come from here)
