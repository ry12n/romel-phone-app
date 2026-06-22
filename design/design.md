# ROMEL Phone App — Design

## Version
V1

## Direction
Mobile command-center interface for ROMEL. Pre-authentication tension: the agents are present but the system is locked. The user is being verified. One access CTA.

## Screens
1. **Command Center** — single mobile viewport. Status bar, agent roster, operations feed, access CTA.

## Palette
| Token | Hex | Usage |
|-------|-----|-------|
| bg | `#080C12` | background |
| surface | `#0D1117` | raised panels |
| panel | `#131922` | elevated cards |
| accent | `#3D8EF0` | borders, focus, active indicators only |
| accent-dim | `#1E4A8A` | subdued accent |
| accent-faint | `#0D2040` | tinted button bg |
| text | `#F0EEE9` | primary text |
| text-secondary | `#9BA3AF` | secondary text |
| text-muted | `#4B5563` | disabled/ghost |
| border | `#161D28` | subtle separator |
| border-mid | `#1F2937` | visible border |
| border-bright | `#2D3B4E` | active/focused border |

## Typography
- Headlines / UI: Inter, 300–400 weight.
- Labels / metadata / IDs / status: JetBrains Mono, 400–500 weight, uppercase, wide tracking.

## Shape language
- Zero border radius.
- 1px borders; steel blue for active/focus states.
- No shadows. Depth via tonal layering.
- 8px grid.

## Components
- Status bar: system read-out, verification badge, time.
- Agent row: initials badge, name, role, status dot + label.
- Operation feed item: timestamp (mono), agent label, action text.
- Primary CTA: bordered/faint treatment, full-width.

## Guardrails observed
- Accent is border/focus only.
- One primary CTA per view.
- Agent roles exact from brand; Dr. Bayle shown as "—".
- No SaaS tropes: no pricing, testimonials, logo walls, gradients, rounded pills, warm colors.
