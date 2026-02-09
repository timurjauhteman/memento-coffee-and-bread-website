# Design System: Memento Coffee and Bread
**Project ID:** Memento-Vintage-Archive

## 1. Visual Theme & Atmosphere
**Atmosphere:** Vintage, archival, tactile, warmth, specific.
The design evokes a sense of history and physical documentation. It uses paper textures, typewriter fonts, and stamp-like elements to create an interface that feels like a collection of physical artifacts rather than a digital screen. The mood is quiet, intellectual, and community-focused.

## 2. Color Palette & Roles
*   **Primary Orange (#cf6317):** Used for primary actions, highlights, stamps, and key text elements. evokves warmth and baked goods.
*   **Deep Teal (#2d5a5e):** Used for backgrounds in specific sections (Reading Room), accents, and secondary stamps. Adds a sense of depth and calmness.
*   **Paper Cream (#f4f0e8):** The main background color, simulating aged paper.
*   **Ink Black (#2d2a26):** The primary text color, softer than pure black to mimic printed ink.
*   **Light Background (#fcfaf8):** A slightly lighter shade for visual hierarchy and subtle gradients.
*   **Vintage Teal (#1a3a3a):** Darker teal for footer elements or specific high-contrast badges.

## 3. Typography Rules
*   **Headings (Display):** `Space Grotesk`. Used for large titles, section headers, and modern contrasts. Weights: 700 (Bold), 900 (Black).
*   **Body & Meta (Mono):** `Courier Prime`. Used for all body text, metadata, navigational elements, and "typewritten" notes. This is the defining font of the archival aesthetic. Weights: 400 (Regular), 700 (Bold).
*   **Utility:** `Noto Sans`. Used sparingly for specific UI elements if needed, but largely replaced by the other two.

## 4. Component Stylings
*   **Buttons:**
    *   *Primary:* Sharp corners or slightly rounded. Background color `#cf6317` (Orange) or `#2d5a5e` (Teal). Text is white, uppercase, `Courier Prime` font, with wide letter spacing (`tracking-widest`).
    *   *Floating Action Button:* Circular, large icon, with a slide-out text label on hover.
*   **Cards (Catalog/Library):**
    *   *Style:* "Polaroid" style with white borders and shadow. Often rotated slightly (`rotate-1`, `rotate-[-2deg]`) to mimic physical stacking.
    *   *Shadows:* Soft, diffused shadows (`shadow-2xl`) to lift elements off the "paper" background.
*   **Stamps & Badges:**
    *   *Style:* Bordered boxes with uppercase text. Often rotated (`-3deg`).
    *   *Colors:* Matches Primary Orange or Deep Teal.
*   **Navigation:**
    *   *Links:* Uppercase, `Courier Prime`, bold. Hover effects include changing color to Primary Orange. Active state often underlined.

## 5. Layout Principles
*   **Whitespace:** Generous usage. Layouts are often centered with wide margins (`max-w-[1200px]`).
*   **Grid:** Uses CSS Grid and Flexbox. Listings are often in 1, 2, or 3 column grids depending on screen size.
*   **Responsiveness:** Mobile-first approach. Complex layouts (like the catalog drawer) use horizontal scrolling or stacking on smaller screens.
*   **Structure:** Sections are clearly divided by horizontal lines (`border-b`) or distinct background color changes.
