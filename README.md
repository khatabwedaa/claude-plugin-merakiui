<p align="center">
    <a href="https://merakiui.com"><img src="https://merakiui.com/images/full-logo.svg" alt="MerakiUI" width="200"></a>
    <h1 align="center">claude-plugin-merakiui</h1>
    <p align="center">Browse, search, and generate beautiful UI components from MerakiUI directly in Claude Code — 228 free Tailwind CSS components with dark mode, RTL support, and responsive design.</p>
</p>

<p align="center">
    <a href="https://github.com/khatabwedaa/claude-plugin-merakiui"><img src="https://img.shields.io/github/v/release/khatabwedaa/claude-plugin-merakiui?style=flat-square" alt="release"></a>
    <a href="https://github.com/khatabwedaa/claude-plugin-merakiui"><img src="https://img.shields.io/github/stars/khatabwedaa/claude-plugin-merakiui?style=flat-square" alt="stars"></a>
    <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square" alt="license"></a>
    <a href="https://merakiui.com"><img src="https://img.shields.io/badge/components-228-blue.svg?style=flat-square" alt="components"></a>
</p>

<hr>

This plugin brings [MerakiUI](https://merakiui.com)'s full component library into [Claude Code](https://claude.ai/code). When you ask for a component, it opens **up to 4 design variants** in your browser with a visual switcher — pick your favorite, and Claude injects it into your code.

Once installed, using it is as simple as:

```
/mui:mui hero
```

The browser opens with 4 hero designs and a bottom switcher bar. Navigate with arrow keys, pick your favorite, and Claude drops it into your project.

## Table of Contents

- [Installation](#installation)
- [Visual Preview & Choose](#visual-preview--choose)
- [Usage](#usage)
  - [Browse Components](#browse-components)
  - [Search Components](#search-components)
  - [Generate with Customization](#generate-with-customization)
  - [Compose Full Pages](#compose-full-pages)
- [Available Components](#available-components)
  - [Application UI](#application-ui-129-components)
  - [Marketing](#marketing-99-components)
- [Tech Stack](#tech-stack)
- [Credits](#credits)
- [License](#license)

## Installation

**Step 1:** Add the marketplace (one time):

```
/plugin marketplace add khatabwedaa/claude-plugins-marketplace
```

**Step 2:** Install the plugin:

```
/plugin install mui@khatabwedaa-plugins
```

**Step 3:** Reload:

```
/reload-plugins
```

That's it. No dependencies, no build step. The plugin bundles all 228 component templates.

## Visual Preview & Choose

When you ask for a component, the plugin doesn't just give you one option — it opens **up to 4 design variants** in your browser with a sleek switcher bar at the bottom center.

```
You: /mui:mui hero
Browser: Opens with 4 hero designs + bottom switcher (← 1/4 "Center Content" →)
You: I like design 3
Claude: Injects "Background Image" hero into your code
```

The switcher supports:
- **Arrow keys** (left/right) to navigate between designs
- **Dot indicators** to jump to any design
- **Variant name display** so you know what you're looking at
- **Counter** (e.g. "2 / 4") to track your position

## Usage

### Browse Components

```
/mui:mui
```

Shows all categories. Pick one, and 4 best variants open in your browser for visual comparison.

### Search Components

```
/mui:mui pricing table
/mui:mui hero section
```

Finds matching components, opens up to 4 in the browser preview for you to choose from.

### Generate with Customization

```
/mui:mui generate a contact form with a map and social links
/mui:mui generate a dark-themed navbar with a search bar
```

Shows you 4 matching designs to preview, then customizes your chosen one with your content.

### Compose Full Pages

```
/mui:mui page SaaS landing page with navbar, hero, features, pricing, and footer
/mui:mui page portfolio site with hero, project grid, testimonials, and contact form
```

For each page section, shows design options to preview and choose from, then composes everything into a complete responsive page.

## Available Components

### Application UI (129 components)

| Category | Components |
|----------|-----------|
| Alerts | 9 variants (error, info, success, warning) |
| Avatars | 10 variants (profiles, groups, statuses) |
| Breadcrumbs | 5 variants (simple, icons, full-width) |
| Buttons | 10 variants (primary, groups, social, icons) |
| Cards | 9 variants (article, product, user, testimonial) |
| Cookies | 6 variants (banner, card, full-width) |
| Dropdowns | 6 variants (simple, multi-level, notification) |
| Forms | 4 variants (newsletter, search, simple) |
| Inputs | 13 variants (text, email, password, file, date) |
| Modals | 5 variants (confirm, archive, invite, steps) |
| Navbars | 6 variants (simple, avatar, search, e-commerce) |
| Pagination | 4 variants (simple, arrows, icons, table) |
| Sidebar | 8 variants (avatar, search, sub-menu, collapse) |
| Sign-in & Registration | 9 variants (card, page, social, side-image) |
| Skeleton | 8 variants (card, grid, header, navbar, footer) |
| Tables | 6 variants (simple, avatar, files, filters) |
| Tabs | 4 variants (line, closed, with icons) |
| Tooltip | 7 variants (top, bottom, left, right, centered) |

### Marketing (99 components)

| Category | Components |
|----------|-----------|
| 404 Pages | 7 variants (centered, illustration, image) |
| Blog | 6 variants (cards, grid, single post) |
| Contact | 13 variants (form, map, grid, card, image) |
| CTA | 6 variants (centered, card, form, grid, image) |
| Email Templates | 7 variants (welcome, invite, notification) |
| FAQ | 5 variants (cards, centered, collapse, grid) |
| Features | 7 variants (cards, grid, media, trusted-by) |
| Footers | 10 variants (simple, CTA, links, subscribe) |
| Heros | 11 variants (center, side-image, background, slides) |
| Portfolio | 5 variants (cards, filter, hover effect) |
| Pricing | 7 variants (simple, popular, checkbox, navigation) |
| Teams | 7 variants (cards, grid, filter, background) |
| Testimonials | 8 variants (card, centered, full-page, slider) |

## Tech Stack

- **[Tailwind CSS](https://tailwindcss.com)** — Utility-first CSS framework
- **[AlpineJS](https://alpinejs.dev)** — Lightweight interactivity (dropdowns, modals, navbars)
- **Dark Mode** — Built-in `dark:` variants on all components
- **RTL Support** — Right-to-left language ready
- **Responsive** — Mobile-first, fully responsive design

## Credits

- Components by [MerakiUI](https://merakiui.com)
- Built for [Claude Code](https://claude.ai/code) by [Anthropic](https://anthropic.com)

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
