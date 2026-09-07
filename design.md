# Portfolio Design Specification

## Stack
- `index.html` + `index.css`
- Google Fonts: Space Grotesk (representing Module Grotesk) & Plus Jakarta Sans (representing Core Grotesk)
- Vanilla CSS, no frameworks

## Colors & Theme
- **Paper (Background):** `#F3EFE6` (warm editorial off-white)
- **Ink (Primary Text & Navigation):** `#1F2E27` (crisp dark green-black)
- **Ink Soft (Muted/Secondary):** `#63705F`
- **Line (Dividers/Borders):** `#DFD9CE`
- **Accent (Burnt Terracotta):** `#C85A32` (used for company names, lab names, project names, hover highlights)
- **Signature Blue (Job Titles, Links & Project Kickers):** `#16337F` (used for job titles, project summary titles / kickers, and direct contact links)

## Typography
- **Headings & Structural Titles:** `Space Grotesk` (Module Grotesk aesthetic)
  - Page Title / H1: Space Grotesk 700, 48px, -0.03em letter-spacing
  - Section Titles / H2: Space Grotesk 700, 28px, -0.02em letter-spacing
  - Company & Lab Names: Space Grotesk 700, 21px (bold, balanced alongside 20px role title), `#C85A32` (Accent Terracotta)
  - Project Titles / H3: Space Grotesk 700, 21px (bold), `#C85A32` (Accent Terracotta)
  - Job Titles / H3: Space Grotesk 600, 20px, `#16337F` (Signature Blue)
  - Project Summary Kickers: Space Grotesk 700, 11.5px uppercase, 0.07em letter-spacing, `#16337F` (Signature Blue)
  - Navigation: Space Grotesk 600, 14.5px, `#1F2E27` (Black)
- **Body & Editorial Content:** `Plus Jakarta Sans` (Core Grotesk aesthetic)
  - Bio: Plus Jakarta Sans 400, 19px, 1.62 line-height (fills the hero height nicely next to 260px portrait)
  - Locations: Plus Jakarta Sans 600, 13.5px, `#1F2E27` (aligned to the right of position titles)
  - Timings / Dates: Plus Jakarta Sans 500, 12.5px, `#63705F` (subtle, right-aligned directly under location)
  - Body & Bullets: Plus Jakarta Sans 400, 15px, 1.55 line-height, 0.88 opacity
  - Tags / Pills: Plus Jakarta Sans 600, 12px, pill-radius (999px)
  - Contact labels: Space Grotesk 700, 13px uppercase, 0.08em letter-spacing

## Layout & Components
- **Container:** Max-width 1040px, centered with 40px horizontal padding
- **Topnav:** All links in crisp Black (`#1F2E27`) using Space Grotesk (`var(--font-heading)`) with clean 24px flex spacing (no separator dots)
  - Left side: Resume
  - Right side: Experience · Research · Projects · Contact
- **Hero:** 2-column layout (260px left, 1fr right)
  - Left: Circular profile photo (`profile.jpg`, 260px × 260px, `border-radius: 50%`) with subtle elevation shadow
  - Right: Name (`h1` 48px), expanded bio (`19px`, `1.62` line-height). (Location line removed)
- **Content Sections:**
  - **Experience:** Sequential list items with `grid-template-columns: 260px 1fr`
    - Left column (`.period`):
      - Company name (21px bold, `#C85A32`) linked to official site:
        - Rox (`https://www.rox.com/`)
        - Ernst & Young (EY) (`https://www.ey.com/en_us`)
        - Purdue SoCET (`https://engineering.purdue.edu/SoC-Team`)
    - Right column:
      - Header row (`.role-header`): Position title in Signature Blue (`#16337F`, 20px) on the left; Location (`San Francisco, CA`, `Bangalore, India`, `West Lafayette, IN`) and subtle Dates (`May 2026 to Aug 2026`, `Jun 2025 to Aug 2025`, `Aug 2026 to Present`) stacked and right-aligned
      - 3 detailed bulleted achievements (no tag pills under roles)
  - **Research:** Structured identically to Experience
    - Left column (`.period`):
      - Lab name with professor in parenthesis (21px bold, `#C85A32`) linked to official lab site:
        - HCSS Lab (Prof. Tianyi Zhang) (`https://tianyi-zhang.github.io/`)
        - Duality Lab (Prof. James C. Davis) (`https://davisjam.github.io/`)
    - Right column:
      - Header row (`.role-header`): Role in Signature Blue (`#16337F`, 20px) on the left; Location (`West Lafayette, IN`) and subtle Dates (`Aug 2026 to Present`, `Jan 2026 to May 2026`) stacked and right-aligned
      - Detailed bulleted achievements
  - **Selected Projects:**
    - Left column: Project name in Terracotta (21px bold, `#C85A32`) linked directly to its GitHub repository:
      1. MCPAegis (`https://github.com/sanjayriram44/MCPAegis`)
      2. PebbleGPT (`https://github.com/sanjayriram44/PebbleGPT`)
      3. Sift (`https://github.com/akkshay0107/sift`)
      4. KernelFusion (`https://github.com/sanjayriram44/KernelFusion`)
      5. Glimpse (`https://github.com/sanjayriram44/glimpse`)
    - Right column:
      - Category kicker in Signature Blue (`#16337F`, 11.5px bold uppercase)
      - Paragraph description and tech pills
  - **Contact:** Clean row-based layout for:
    - Email: `sanjaysriram44@gmail.com`
    - LinkedIn: `https://www.linkedin.com/in/sanjaysriram44/`
    - GitHub: `https://github.com/sanjayriram44`
  - **Footer:** Simple centered footer note
