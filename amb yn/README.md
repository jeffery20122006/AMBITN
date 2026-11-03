# AMBI TN - Academic Events Page

This project contains the complete implementation of the **Academic Events** page for **AMBI TN** based directly on the design specifications provided in the screenshots.

---

## 📁 Files Included

1. **[`index.html`](file:///c:/Users/Jeffery/OneDrive/Desktop/amb%20yn/index.html)**:
   - Full standalone webpage including:
     - Header navigation bar with AMBI TN branding, dropdown indicators, active page indicator, and search.
     - Hero banner with university motif, breadcrumb pill (`Home / Academic Events`), gold accent bar, and academic typography.
     - 4 interactive filter category cards (`All Events`, `Conferences`, `Workshops`, `Seminars`).
     - "Upcoming Academic Events" section with card grid (Date badge, image with category pills, title, snippet, location, and Register button).
     - "Next Event" featured sidebar box with university photo, metadata, and gold CTA button.
     - Interactive registration modal dialog.

2. **[`wix-embed-section.html`](file:///c:/Users/Jeffery/OneDrive/Desktop/amb%20yn/wix-embed-section.html)**:
   - Self-contained, scoped embed snippet designed specifically to be pasted directly into **Wix Studio** / **Wix Editor** as an **Embed HTML / iframe** component without conflicting with Wix's site headers or footers.

---

## 🚀 How to Add This to Wix Studio

Whenever you share the link or open the Wix Studio session:

### Method 1: Using "Embed HTML" in Wix Studio (Fastest & 100% Pixel-Perfect)
1. Open your site in **Wix Studio Editor**.
2. Navigate to the **Academic Events** (or target) page.
3. In the left panel, click **+ Add Elements** &rarr; **Embed & Social** &rarr; **Embed HTML** (or **Custom Element / iFrame**).
4. Click **Enter Code** on the embedded box.
5. Copy all the content from **[`wix-embed-section.html`](file:///c:/Users/Jeffery/OneDrive/Desktop/amb%20yn/wix-embed-section.html)** and paste it into the code editor.
6. Set the element width to **100%** (Full Width) and height to approximately **950px** (or auto-adjust).
7. Click **Apply** and **Publish / Preview**.

### Method 2: Wix Studio Native Elements & Velo CMS Integration
- If you prefer the event cards to pull dynamically from a Wix CMS collection (e.g. `AcademicEvents` dataset), we can connect the card fields (`Title`, `Date`, `Category`, `Location`, `Image`, `RegistrationLink`) directly via Wix Velo code.

