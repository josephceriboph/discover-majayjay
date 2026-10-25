# Discover Majayjay

A responsive static tourism website concept for Majayjay, Laguna, built with plain HTML, CSS, and JavaScript. It can be hosted for free using GitHub Pages.

## Included features

- Responsive layout for phones and desktop
- Searchable attraction cards and category filters
- Google Maps direction links
- Embedded Google Map centered on Majayjay
- Nearby destinations: Hulugan Falls and Kamay ni Hesus
- No build tools or API key required for the basic version

## Publish using GitHub Pages

1. Sign in to https://github.com.
2. Click **New repository**.
3. Name it `discover-majayjay`.
4. Set it to **Public** (or confirm Pages availability for your plan if private).
5. Create the repository.
6. Click **Add file → Upload files**.
7. Upload `index.html` from this folder and this `README.md`.
8. Click **Commit changes**.
9. Open the repository's **Settings → Pages**.
10. Under **Build and deployment**, select **Deploy from a branch**.
11. Select branch `main` and folder `/(root)`, then click **Save**.
12. Wait for GitHub Pages to publish. The site URL will appear in Settings → Pages, usually:
    `https://YOUR-USERNAME.github.io/discover-majayjay/`

If you name the repository `YOUR-USERNAME.github.io`, the site can instead publish at the root URL.

## Before publishing publicly

- Check each destination's exact map pin and route, especially Malinao, Bukal Falls, and Sprite Falls. The supplied search/direction links are starting points and may need to be updated to an exact entrance or registration point.
- Confirm local names, barangays, entrance fees, opening hours, and access conditions.
- The current photographs are illustrative images hosted by Unsplash and are not guaranteed to show the exact attraction. Replace them with photos you own or have permission to use.
- The basic Google Maps embed does not require a Google Maps API key. Advanced Maps Platform features may require an API key and billing.
- Add a contact email, privacy notice if collecting user data, and any required attribution before launch.

## Editing the attraction cards

Open `index.html` and search for the attraction name. Each attraction is an `<article class="card">`. Change its title, location, description, image URL, and Google Maps links. Keep the `data-category` values consistent with the filter buttons:
- `Waterfall`
- `Spring & resort`
- `Culture & pilgrimage`
