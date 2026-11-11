# Claude Brand Guidelines Skill

A styling skill for applying Anthropic's visual identity to presentations and other artifacts. It provides a consistent palette, typography choices, and formatting guidance for work that benefits from Anthropic's brand look and feel.

## What It Covers

- **Brand colors:** Core dark, light, and gray tones with orange, blue, and green accents.
- **Typography:** Poppins for headings and Lora for body text, with Arial and Georgia fallbacks.
- **Text styling:** Apply readable hierarchy and select colors based on background contrast.
- **Shape styling:** Use accent colors for non-text visual elements.
- **Font handling:** Use installed fonts when available and fall back gracefully when they are not.

## Installation

Clone the repository into your Claude skills directory:

```bash
git clone https://github.com/Brajesh31/claude-brand-guidelines-skill.git ~/.claude/skills/brand-guidelines
```

## Using the Skill

Example request:

```text
Use the brand-guidelines skill to apply Anthropic's visual styling
to this presentation, including colors, typography, and shape accents.
```

The skill is intended for visual formatting and post-processing. It describes the brand palette and font behavior in [SKILL.md](SKILL.md).

## Brand Palette

| Role | Color |
|---|---|
| Dark | `#141413` |
| Light | `#faf9f5` |
| Mid gray | `#b0aea5` |
| Light gray | `#e8e6dc` |
| Orange accent | `#d97757` |
| Blue accent | `#6a9bcc` |
| Green accent | `#788c5d` |

## Typography

Use Poppins for headings and Lora for body text when available. The skill specifies Arial and Georgia as fallback fonts. Font availability depends on the execution environment.

## License

See [LICENSE](LICENSE) for the repository license.
