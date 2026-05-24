# ui-ux-pro-max-skill-main

> **Enterprise UI/UX at Claude-speed** — advanced Claude Code skill for pixel-perfect, accessible, production-grade interface design workflows

<div align="center">

[![Stars](https://img.shields.io/github/stars/hmzainjamil/ui-ux-pro-max-skill-main?style=for-the-badge&color=FFD700&labelColor=555)](https://github.com/hmzainjamil/ui-ux-pro-max-skill-main/stargazers)
[![Forks](https://img.shields.io/github/forks/hmzainjamil/ui-ux-pro-max-skill-main?style=for-the-badge&color=00BFFF&labelColor=555)](https://github.com/hmzainjamil/ui-ux-pro-max-skill-main/network)
[![Issues](https://img.shields.io/github/issues/hmzainjamil/ui-ux-pro-max-skill-main?style=for-the-badge&color=FF6347&labelColor=555)](https://github.com/hmzainjamil/ui-ux-pro-max-skill-main/issues)
[![PRs](https://img.shields.io/github/issues-pr/hmzainjamil/ui-ux-pro-max-skill-main?style=for-the-badge&color=32CD32&labelColor=555)](https://github.com/hmzainjamil/ui-ux-pro-max-skill-main/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/hmzainjamil/ui-ux-pro-max-skill-main?style=for-the-badge&color=9370DB&labelColor=555)](https://github.com/hmzainjamil/ui-ux-pro-max-skill-main/commits)

</div>

<div align="center">

![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-FF6B35?labelColor=555&style=flat)
![UI/UX](https://img.shields.io/badge/UI%2FUX-Pro_Max-E91E63?labelColor=555&style=flat)
![Figma](https://img.shields.io/badge/Figma-Compatible-F24E1E?labelColor=555&style=flat)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-Expert-06B6D4?labelColor=555&style=flat)
![React](https://img.shields.io/badge/React-Components-61DAFB?labelColor=555&style=flat)
![WCAG](https://img.shields.io/badge/WCAG-2.1_AA-4CAF50?labelColor=555&style=flat)
![Design Systems](https://img.shields.io/badge/Design_Systems-Architect-9C27B0?labelColor=555&style=flat)

</div>

---

## Why This Exists

Most AI-generated UIs are mediocre. Flat components, no hierarchy, zero accessibility, copy-paste Tailwind without thought. This skill changes that.

`ui-ux-pro-max` is a Claude Code skill that injects enterprise-grade UI/UX knowledge directly into every design task. When loaded, Claude thinks like a senior product designer with 10+ years of design system experience — understanding visual hierarchy, Gestalt principles, WCAG compliance, component architecture, micro-interactions, and brand consistency simultaneously.

Built for agencies and product teams who can't afford "good enough" design.

---

## At a Glance

| Property | Detail |
|---|---|
| **Skill type** | Claude Code skill (SKILL.md) |
| **Activation** | `claude ui-ux-pro-max` or inline skill load |
| **Primary use case** | Enterprise UI/UX design generation |
| **Design systems** | Tailwind, shadcn/ui, Radix UI, MUI, Ant Design |
| **Output formats** | JSX/TSX, HTML/CSS, Figma tokens, design specs |
| **Accessibility** | WCAG 2.1 AA enforced on all output |
| **Responsive** | Mobile-first by default |
| **Component types** | Forms, dashboards, landing pages, modals, nav, tables |
| **Color science** | Contrast ratios, palette generation, dark mode |
| **Typography** | Type scale, line height, reading rhythm, font pairing |
| **Animation** | Micro-interactions, Framer Motion patterns |
| **Testing** | Storybook stories, visual regression hints |

---

## 🧠 CONCEPTS

| Concept | What it means in this skill |
|---|---|
| **Visual Hierarchy** | Size, weight, color, spacing used to guide eye flow |
| **Design Token** | Named variable (color, spacing, font) for system consistency |
| **Component Anatomy** | Slot-based structure: trigger, content, overlay, footer |
| **Gestalt Principles** | Proximity, similarity, continuity applied to layout |
| **WCAG 2.1 AA** | Minimum 4.5:1 contrast, keyboard nav, ARIA labels |
| **Type Scale** | Modular ratio (1.25/1.333) for heading/body sizing |
| **Spacing System** | 4px or 8px base grid, consistent padding/margin tokens |
| **Dark Mode** | CSS custom properties, semantic color tokens, no hardcodes |
| **Micro-interaction** | Sub-200ms feedback: hover states, loading, transitions |
| **Atomic Design** | Atoms → Molecules → Organisms → Templates → Pages |
| **Design Critique** | Structured review: hierarchy, color, motion, a11y, copy |
| **Responsive Breakpoints** | sm/md/lg/xl/2xl with content-aware reflows |

### 🔥 Hot

- **Auto-generates Storybook stories** alongside every component
- **WCAG audit inline** — flags contrast failures before code is written
- **Figma token export** — design tokens as JSON for Figma Tokens plugin
- **Dark mode by default** — every component ships with `dark:` variants

---

## ⚙️ HOW IT WORKS

```
User prompt → Skill loads SKILL.md context → Claude activates UI/UX expert persona
       ↓
Design brief parsing → Component identification → System selection
       ↓
Hierarchy planning → Color/type/spacing decisions → WCAG check
       ↓
Component code generation (JSX/TSX) → Storybook story → Design spec
       ↓
Output: production-ready component + tokens + accessibility notes
```

The skill injects a 2000+ token design knowledge base into Claude's context. This includes:
- **Design principles**: 8 Gestalt laws, visual hierarchy rules, reading patterns (F/Z/E)
- **Component patterns**: 50+ UI patterns with do/don't examples
- **WCAG checklists**: Per-component accessibility requirements
- **Code standards**: Tailwind utility patterns, class organization, responsive naming
- **Review framework**: Structured critique template for every output

---

## 🚀 INSTALL

### Option 1 — Clone into Claude skills directory

```bash
git clone https://github.com/hmzainjamil/ui-ux-pro-max-skill-main.git \
  ~/.claude/skills/ui-ux-pro-max
```

### Option 2 — Manual install

```bash
mkdir -p ~/.claude/skills/ui-ux-pro-max
curl -sL https://raw.githubusercontent.com/hmzainjamil/ui-ux-pro-max-skill-main/main/SKILL.md \
  -o ~/.claude/skills/ui-ux-pro-max/SKILL.md
```

### Option 3 — Claude Code skill installer

```bash
claude skill install hmzainjamil/ui-ux-pro-max-skill-main
```

**Dependencies:**
```bash
# For JSX output
npm install -D tailwindcss @radix-ui/react-* framer-motion

# For design tokens
npm install -D style-dictionary

# For Storybook
npm install -D @storybook/react @storybook/addon-a11y
```

---

## 📟 USAGE

### Basic component generation

```
/ui-ux-pro-max design a dashboard header with user avatar, search, notifications
```

### Full page design

```
/ui-ux-pro-max create a SaaS pricing page: 3 tiers, monthly/annual toggle, feature comparison table
```

### Design system setup

```
/ui-ux-pro-max bootstrap a design system for a fintech app: primary blue #1A56DB, dark mode required
```

### Component audit

```
/ui-ux-pro-max audit this component for WCAG 2.1 AA compliance: [paste component]
```

### Dark mode conversion

```
/ui-ux-pro-max convert this light-only component to support dark mode with CSS tokens
```

### Figma token generation

```
/ui-ux-pro-max generate Figma design tokens JSON for this Tailwind config
```

---

## ⚙️ CONFIGURATION

| Config key | Default | Options | Description |
|---|---|---|---|
| `design_system` | `tailwind` | `tailwind`, `mui`, `antd`, `chakra`, `shadcn` | Base component framework |
| `accessibility` | `wcag-aa` | `wcag-a`, `wcag-aa`, `wcag-aaa` | Minimum accessibility standard |
| `responsive` | `mobile-first` | `mobile-first`, `desktop-first` | Breakpoint strategy |
| `dark_mode` | `true` | `true`, `false` | Include dark mode variants |
| `animation` | `subtle` | `none`, `subtle`, `expressive` | Motion design level |
| `type_scale` | `1.25` | `1.125`, `1.25`, `1.333`, `1.5` | Modular type scale ratio |
| `spacing_base` | `4` | `4`, `8` | Spacing grid base (px) |
| `output_format` | `tsx` | `tsx`, `jsx`, `html`, `vue`, `svelte` | Component file format |
| `storybook` | `true` | `true`, `false` | Auto-generate Storybook stories |
| `design_tokens` | `true` | `true`, `false` | Export design tokens JSON |
| `color_mode` | `semantic` | `semantic`, `literal` | Token naming strategy |
| `critique` | `true` | `true`, `false` | Include design critique with output |

---

## 💡 TIPS AND TRICKS

### Visual Hierarchy

> **Use 3 font sizes max per section** — body, label, heading. More creates chaos.

> **Golden ratio spacing** — if container padding is 24px, inner element gap should be ~15px (24 / 1.618).

> **Weight before color** — establish hierarchy with font-weight first, use color as secondary signal only.

### Accessibility

> **Never rely on color alone** — pair every color signal with an icon, label, or pattern.

> **Test with 400% zoom** — WCAG 1.4.4 requires text still readable at 400% browser zoom.

> **Skip links** — every keyboard-navigable page needs `<a href="#main">Skip to content</a>` as first focusable element.

### Component Architecture

> **Compound components over prop drilling** — `<Dialog>`, `<Dialog.Trigger>`, `<Dialog.Content>` beats a 20-prop monolith.

> **Controlled vs uncontrolled** — always support both. `value + onChange` for controlled, `defaultValue` for uncontrolled.

> **Polymorphic `as` prop** — let consumers change the underlying HTML element without losing styles.

### Performance

> **CSS variables over JS tokens** — switching themes with `document.documentElement.style.setProperty` is faster than re-rendering.

> **Lazy load modals** — `React.lazy` + `Suspense` for heavy dialog content, especially rich text editors.

> **`will-change: transform`** — only on elements that actually animate. Overuse tanks GPU memory.

---

## 🔧 TROUBLESHOOTING

| Issue | Cause | Fix |
|---|---|---|
| Skill not activating | Wrong path in `~/.claude/skills/` | Verify `ls ~/.claude/skills/ui-ux-pro-max/SKILL.md` |
| Generic output, no design system knowledge | Skill not loading | Run `/skill load ui-ux-pro-max` explicitly |
| Tailwind classes not applying | Missing Tailwind config | Run `npx tailwindcss init` and add content paths |
| Dark mode flicker on load | Missing `class` strategy | Add `darkMode: 'class'` to `tailwind.config.js` |
| WCAG contrast warnings | Hardcoded colors | Replace with semantic tokens from design system |
| Storybook stories broken | Missing addon | `npm install -D @storybook/addon-a11y` |
| Framer Motion not animating | SSR conflict | Wrap in `<AnimatePresence>` and check `initial={false}` |
| TypeScript prop errors | Missing type exports | Export component prop types explicitly |
| Figma tokens not importing | Wrong token format | Use `@tokens-studio/sd-transforms` for Figma Tokens plugin |
| Component breaks on mobile | Desktop-first assumption | Set `min-w-0` on flex children, check truncation |

---

## 📊 ARCHITECTURE

```
ui-ux-pro-max-skill-main/
├── SKILL.md                    # Core skill definition loaded by Claude Code
├── knowledge/
│   ├── design-principles.md    # Gestalt, hierarchy, color theory
│   ├── component-patterns.md   # 50+ UI patterns with examples
│   ├── wcag-checklist.md       # Per-component a11y requirements
│   ├── design-systems.md       # Tailwind/shadcn/MUI/Radix patterns
│   └── critique-framework.md   # Structured review template
├── templates/
│   ├── component.tsx.tpl       # Base component template
│   ├── story.tsx.tpl           # Storybook story template
│   └── tokens.json.tpl         # Design token template
├── examples/
│   ├── dashboard/              # Full dashboard example
│   ├── landing-page/           # SaaS landing page example
│   └── design-system/          # Bootstrap design system example
└── README.md
```

**Skill activation flow:**
```
Claude Code → /skill load → reads SKILL.md → injects knowledge context
→ activates UI/UX expert mode → applies to all subsequent design prompts
```

---

## 🗺️ ROADMAP

| Feature | Status | ETA |
|---|---|---|
| Core SKILL.md with design principles | ✅ Done | — |
| WCAG 2.1 AA enforcement | ✅ Done | — |
| Tailwind + shadcn/ui patterns | ✅ Done | — |
| Dark mode by default | ✅ Done | — |
| Storybook story generation | ✅ Done | — |
| Figma design token export | 🔄 In progress | Q3 2025 |
| Vue 3 component support | 🔄 In progress | Q3 2025 |
| Svelte 5 component support | 📋 Planned | Q4 2025 |
| WCAG 2.2 AAA mode | 📋 Planned | Q4 2025 |
| Animation design system | 📋 Planned | Q4 2025 |
| AI design critique agent | 📋 Planned | Q1 2026 |
| Figma MCP integration | 📋 Planned | Q1 2026 |

---

## ☠️ STARTUPS / BUSINESSES

**Real leverage this skill gives your team:**

| Scenario | Without skill | With skill |
|---|---|---|
| SaaS dashboard build | 3 days, mediocre output | 4 hours, production-ready |
| Design system bootstrap | Hire $5k designer | Bootstrap in 2 hours |
| WCAG audit | External audit $2k+ | Inline with code generation |
| Component library | Weeks of iteration | Ship v1 in a day |
| Landing page redesign | Agency quote: $8k | Done in an afternoon |
| Dark mode retrofit | Sprint of work | One `/ui-ux-pro-max` command |

**Who uses this:**
- Indie hackers shipping fast without a designer
- Agencies needing consistent output across projects
- Product teams that have engineers but no design lead
- Founders who know what good looks like but can't execute it manually

**ROI calculation:**
- Senior product designer rate: $120-180/hr
- This skill replaces ~70% of routine design work
- Payback on setup time: first project

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/ui-ux-pro-max-skill-main&type=Date)](https://star-history.com/#hmzainjamil/ui-ux-pro-max-skill-main&Date)

---

<div align="center">

Built by [HMZ](https://github.com/hmzainjamil) · Claude Code skill for enterprise UI/UX · PRs welcome

</div>
