# README Flair — Cyberpunk Neon Design

## Goal

Add Option A (Cyberpunk Neon) visual flair to the existing recruiter-optimized README without changing any guide-specified content.

## Approach

Additive only — insert new visual elements around existing content blocks. No text, badges, or structure from the previous rework gets removed or modified.

## Elements to Add

### 1. Header — capsule-render animated wave
```
https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=header&text=&animation=fadeIn
```
- `type=waving`, animated, purple→cyan gradient
- `height=120`, no text (name follows as static markdown below)
- Placed at very top of file, before `<div align="center">`

### 2. readme-jokes card
```
https://readme-jokes.vercel.app/api?theme=dark&hideBorder=true&bgColor=%230D0D1A&textColor=%23C4B5FD&questionColor=%23A78BFA&answerColor=%2306B6D4
```
- Dark theme matching palette
- Placed directly below the contact links row inside the header div

### 3. Section dividers — capsule-render slim rect
```
https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=0,2,2,5,30&height=2&section=header
```
- `type=rect`, `height=2`, same purple→cyan gradient
- Inserted as `<img>` between each major section: after header div, before About, before Projects, before Tech Stack, before Stats

### 4. github-profile-trophy
```
https://github-profile-trophy.vercel.app/?username=pappdavid&theme=darkhub&no-frame=true&no-bg=true&column=6&margin-w=4
```
- `theme=darkhub`, frameless, transparent bg
- Placed in `<div align="center">` above the Stats section

### 5. Carbon.now.sh code snippet image
- A styled TypeScript snippet representing MCP Sentinel's proxy intercept logic
- Hosted as a GitHub-linked image or direct carbon.now.sh export URL
- Use this representative snippet:
```typescript
// mcp-sentinel: intercept every tool call
proxy.on('tool_call', async (call) => {
  await logger.record({ tool: call.name, args: call.args });
  if (await guard.isBlocked(call)) throw new GuardError(call);
  return upstream.forward(call);
});
```
- Carbon config: `theme=one-dark`, `bg=#0D0D1A`, `font=Fira Code`, `fontSize=14`
- Embed via: `[![MCP Sentinel](https://carbon.now.sh/...)](https://davidpapp.dev/mcp)`
- **Note:** Generate the actual image at carbon.now.sh and replace the URL, or use a carbon embed link directly
- Placed after the Projects table, before the Tech Stack section

### 6. Snake animation
- Already exists in workflow (`.github/workflows/snake.yml`)
- Re-add the `<picture>` block at bottom, before footer wave:
```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/pappdavid/pappdavid/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/pappdavid/pappdavid/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/pappdavid/pappdavid/output/github-contribution-grid-snake.svg" />
</picture>
```

### 7. Footer — capsule-render wave (flipped)
```
https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=footer
```
- `section=footer` flips the wave
- Placed at very end of file

## Color Palette
| Role | Hex |
|------|-----|
| Background | `#0D0D1A` |
| Primary purple | `#7C3AED` |
| Accent cyan | `#06B6D4` |
| Text light | `#C4B5FD` |
| Title | `#A78BFA` |

## Content Unchanged
- Header text: name, subtitle, value prop, contact links
- About section: all 5 bullets
- Projects table: all 3 rows with davidpapp.dev links
- Tech Stack: all 4 groups with FastAPI and Hetzner kept
- GitHub Stats: two cards at height=150
