# MerakiUI Plugin for Claude Code

Browse, search, and generate beautiful UI components from [MerakiUI](https://merakiui.com/) directly in Claude Code.

**228 free Tailwind CSS components** with dark mode, RTL support, and responsive design.

## Installation

```bash
/plugin install khatabwedaa/claude-plugin-merakiui
```

## Usage

### Browse Components

```
/merakiui
```

Shows all available categories. Pick a category, then pick a variant to get the HTML code.

### Search Components

```
/merakiui pricing table
/mui hero section
```

Searches for components matching your query.

### Generate with Customization

```
/merakiui generate a contact form with a map and social links
/mui generate a dark-themed navbar with a search bar
```

Finds the best matching component and adapts it to your needs.

### Compose Full Pages

```
/merakiui page SaaS landing page with navbar, hero, features, pricing, and footer
/mui page portfolio site with hero, project grid, testimonials, and contact form
```

Combines multiple MerakiUI components into a complete HTML page.

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

- **Tailwind CSS** — Utility-first CSS framework
- **AlpineJS** — Lightweight interactivity (dropdowns, modals, navbars)
- **Dark Mode** — Built-in `dark:` variants
- **RTL Support** — Right-to-left language ready
- **Responsive** — Mobile-first, fully responsive

## Short Alias

Use `/mui` as a shorthand for `/merakiui`:

```
/mui hero
/mui generate a pricing table with 3 tiers
/mui page landing page for a SaaS product
```

## License

MIT - [MerakiUI](https://merakiui.com/) by Khatab Wedaa
