# Macula Artwork

Official logos, icons, and brand assets for the Macula platform.

## Assets

### Full Logo (Symbol + Wordmark)

| Variant | SVG | PNG |
|---------|-----|-----|
| Dark theme | [macula-full-dark.svg](svg/macula-full-dark.svg) | [128](png/macula-full-dark-128.png) · [256](png/macula-full-dark-256.png) · [512](png/macula-full-dark-512.png) · [1024](png/macula-full-dark-1024.png) |
| Light theme | [macula-full-light.svg](svg/macula-full-light.svg) | [128](png/macula-full-light-128.png) · [256](png/macula-full-light-256.png) · [512](png/macula-full-light-512.png) · [1024](png/macula-full-light-1024.png) |

### Symbol Only

| Variant | SVG | PNG |
|---------|-----|-----|
| Dark theme | [macula-symbol-dark.svg](svg/macula-symbol-dark.svg) | [128](png/macula-symbol-dark-128.png) · [256](png/macula-symbol-dark-256.png) · [512](png/macula-symbol-dark-512.png) · [1024](png/macula-symbol-dark-1024.png) |
| Light theme | [macula-symbol-light.svg](svg/macula-symbol-light.svg) | [128](png/macula-symbol-light-128.png) · [256](png/macula-symbol-light-256.png) · [512](png/macula-symbol-light-512.png) · [1024](png/macula-symbol-light-1024.png) |

### Favicon

- [favicon.ico](favicon.ico)

### SDK Availability Announcement Banner

The long-form Macula logo plus the four shipped SDK badges (Go, Rust,
PHP, .NET), each linking to its repo. Built for social announcements
(LinkedIn, etc.) — 1200×630, the widely-safe single-image social post
size.

| Asset | Link |
|-------|------|
| SVG (clickable badges) | [macula-sdk-announcement.svg](svg/macula-sdk-announcement.svg) |
| PNG, 1200×630 | [macula-sdk-announcement.png](png/macula-sdk-announcement.png) |
| PNG, 2400×1260 (2x/retina) | [macula-sdk-announcement@2x.png](png/macula-sdk-announcement@2x.png) |

Badge artwork is reused verbatim from each SDK repo's own `assets/`
(already licensed and reviewed there — see each SDK repo's own README
License section for that badge's specific attribution). Note that a
raster export, and any platform that re-encodes an uploaded image (like
LinkedIn), loses the per-badge repo links baked into the SVG — those
only work when the SVG itself is viewed or embedded directly.

### Deployables Announcement Banner

Same layout as the SDK banner above, with the three badge icons already
used as each repo's own README badge — macula-cli (terminal), macula-mcp
(plug), macula-station (radio tower) — reused verbatim from
`macula-{cli,mcp,station}/assets/macula-*-full-*.svg`. Also 1200×630.

| Asset | Link |
|-------|------|
| SVG (clickable badges) | [macula-deployables-announcement.svg](svg/macula-deployables-announcement.svg) |
| PNG, 1200×630 | [macula-deployables-announcement.png](png/macula-deployables-announcement.png) |
| PNG, 2400×1260 (2x/retina) | [macula-deployables-announcement@2x.png](png/macula-deployables-announcement@2x.png) |

### Macrel — the mesh mascot (speculative)

A fish built from the same node-and-line vocabulary as the plain mesh
symbol above, arranged into a mackerel instead of an abstract mesh — the
central hub doubles as its eye, two orange chords across the back stand in
for tiger stripes. Sketched alongside a joke about renaming the Erlang/OTP
core (`macula-io/macula`, currently un-suffixed while its ports are
`macula-go`/`macula-rust`/`macula-php`/`macula-dotnet`) to `macula-erl` for
naming consistency. **Not an executed rename** — the core package, its hex
name, and every consumer's dependency stay exactly as they are today; this
is art, not a migration.

| Variant | SVG | PNG |
|---------|-----|-----|
| Dark theme | [macrel-mascot-dark.svg](svg/macrel-mascot-dark.svg) | [128](png/macrel-mascot-dark-128.png) · [256](png/macrel-mascot-dark-256.png) · [512](png/macrel-mascot-dark-512.png) · [1024](png/macrel-mascot-dark-1024.png) |
| Light theme | [macrel-mascot-light.svg](svg/macrel-mascot-light.svg) | [128](png/macrel-mascot-light-128.png) · [256](png/macrel-mascot-light-256.png) · [512](png/macrel-mascot-light-512.png) · [1024](png/macrel-mascot-light-1024.png) |

A badge-scale version of the same fish, simplified the way the CLI/MCP/
Station badges are, sits in a `macula-erl` full-logo mockup for if the
rename ever actually happens:

| Variant | SVG |
|---------|-----|
| Dark theme | [macula-erl-full-dark.svg](svg/macula-erl-full-dark.svg) |
| Light theme | [macula-erl-full-light.svg](svg/macula-erl-full-light.svg) |

## Colors

| Element | Dark Theme | Light Theme |
|---------|-----------|-------------|
| Primary (mesh lines, nodes) | `#38BDF8` | `#0EA5E9` |
| Accent (active connections) | `#FB923C` | `#F97316` |
| Node fill | `#1E293B` | `#0C1929` |
| Hub nodes | `#F8FAFC` | `#FFFFFF` |

## Typography

Wordmark uses monospace: JetBrains Mono, Fira Code, SF Mono, Consolas.

## Usage

- **Dark backgrounds**: use `-dark` variants
- **Light backgrounds**: use `-light` variants
- **All PNGs are transparent** — no background baked in
- **SVG is preferred** for web and print — scales to any size

## License

Apache-2.0
