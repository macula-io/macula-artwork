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

### Ecosystem Announcement Card

Combines the two banners above into one card, under the same long-form
logo: a **BUILD** row splits into the three dedicated-port SDK badges
(Go/Rust/.NET — PHP dropped from this card only, for a clean 3×3 grid;
its own SDK repo and the original SDK banner are untouched) and a second
sub-row for the three languages that need no port because they already
run on the BEAM (Erlang, Elixir, Gleam), then a **RUN** row with the three
deployable badges. SDK, Erlang, and deployable badges are verbatim brand
marks; Elixir/Gleam are original simplified renditions (no local asset to
reuse verbatim, unlike the others). Taller than the single-row banners
(1200×1240, not 1200×630) since nine badges don't fit one LinkedIn-safe
row — sized for a README hero or a taller post, not the strict 1.91:1
safe zone.

| Asset | Link |
|-------|------|
| SVG (clickable badges) | [macula-ecosystem-announcement.svg](svg/macula-ecosystem-announcement.svg) |
| PNG, 1200×1240 | [macula-ecosystem-announcement.png](png/macula-ecosystem-announcement.png) |
| PNG, 2400×2480 (2x/retina) | [macula-ecosystem-announcement@2x.png](png/macula-ecosystem-announcement@2x.png) |

### Agent-Mesh Architecture Diagram

Not a product announcement like the banners/card above — an honest picture
of one real workflow: a coding agent (Claude Code) reaches the mesh
through macula-mcp and calls real, deployed edge services (hecate-graph,
hecate-llm, hecate-rag, hecate-sentinel, hecate-mail, hecate-stations),
not a roadmap. macula-mcp's plug badge and the mesh-node motif are reused
verbatim from the deployables banner above. 1200×630, LinkedIn-safe.

| Asset | Link |
|-------|------|
| SVG | [macula-agent-mesh-architecture.svg](svg/macula-agent-mesh-architecture.svg) |
| PNG, 1200×630 | [macula-agent-mesh-architecture.png](png/macula-agent-mesh-architecture.png) |
| PNG, 2400×1260 (2x/retina) | [macula-agent-mesh-architecture@2x.png](png/macula-agent-mesh-architecture@2x.png) |

### Macrel — the Erlang mascot (speculative)

A small mackerel mascot, filled-illustration style like the Go/Rust/PHP
badges rather than macula's own CLI/MCP/Station line-icon convention — a
proper little character (body, back stripes, forked tail, a grin), not an
abstract construction. Represents the Erlang/OTP core (`macula-io/macula`,
currently un-suffixed while its ports are
`macula-go`/`macula-rust`/`macula-php`/`macula-dotnet`) the way Go's gopher
or Rust's crab represent theirs. Lives at badge scale only — sits in a
`macula-erl` full-logo mockup for if a `macula → macula-erl` rename ever
actually happens (**not an executed rename** — the core package, its hex
name, and every consumer's dependency stay exactly as they are today).
The ecosystem card above uses the real Erlang/OTP mark for its "Erlang"
badge instead, so Macrel doesn't appear there.

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
