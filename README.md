# Home Refurbishment Inspiration Planner

A simple, browser-based inspiration board for planning your family home refurbishment. Organise ideas by room and category — colours, materials, furniture, fittings, and more — and collect image links, notes, and votes all in one place. No sign-up, no server, no installation required.

Each family member keeps their own independent wishlist in their browser. Everyone can collect their favourites, vote on items, and then use the Export feature to share a printable summary with the rest of the family. It's a lightweight, privacy-friendly way to gather everyone's input before making decisions.

---

## Using it locally

1. Download or clone this repository.
2. Open `index.html` directly in any modern browser (Chrome, Firefox, Safari, Edge).
3. Start adding rooms and inspiration items straight away — all data is saved automatically in your browser's localStorage.

No internet connection is required after the page loads (except to load images you link to from external URLs).

---

## Deploying to GitHub Pages

1. Push this repository to GitHub (or fork it).
2. Go to your repository on GitHub and click **Settings**.
3. In the left sidebar, click **Pages**.
4. Under *Branch*, select `main` (or `master`) and leave the folder as `/ (root)`, then click **Save**.
5. After a minute or two, GitHub Pages will publish the site. The URL will appear at the top of the Pages settings page — it looks like `https://yourusername.github.io/your-repo-name/`.
6. Share that URL with your family.

---

## How family members use it

Each person opens the shared GitHub Pages URL in their own browser. Because data is stored in **localStorage**, every browser maintains a completely separate, independent collection of rooms and inspiration items. Nothing is shared automatically between devices or family members — this is intentional and keeps things simple.

**Typical workflow:**

1. Each family member opens the URL and starts adding inspiration items for the rooms they care about.
2. When ready to share, click the **Export** button (top-right of the page).
3. A printable HTML summary opens in a new tab, listing every room, category, and item sorted by vote count. Print it or save it as a PDF.
4. Share the exported PDF (or screenshot) in a family group chat, email, or shared folder.
5. The family can then discuss and agree on the best ideas together.

---

## Tips

- **Use the colour tag** on each card to visually group items — for example, tag all "shortlisted" items in terracotta and "maybe" items in sage green.
- **Vote on your own favourites** using the heart button. The vote count persists in your browser so you can come back later and see what you liked most.
- **Image URLs**: paste any direct image URL (ending in `.jpg`, `.png`, `.webp`, etc.) from Pinterest, Houzz, Google Images, or anywhere else. The app shows a live preview before you save.
- **Export before a family meeting** so everyone can compare their picks side by side.
- **Add custom rooms** with the "+ Add Room" button — useful for spaces like Office, Garden, Utility Room, or Garage.

