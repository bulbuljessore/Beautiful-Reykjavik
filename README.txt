Beautiful Reykjavik website

Open index.html to start. All pages are plain .html files in this folder and link to each other.
Upload the whole folder as-is. Keep the folder structure, because pages load support.js, apartments-data.json, SiteHeader.html, SiteFooter.html, RatingBadge.html and ReykjavikSky.html from the same folder.
Pages need to be served over http(s). Opening them by double-clicking may block the data file.

Pages
index.html          Home
apartments.html     All apartments with filters
apartment.html      Single apartment (apartment.html#250, #251 ... #454)
reviews.html        Guest reviews
host.html           Your host
neighbourhood.html  Neighbourhood and guidebook
seasons.html        Winter and summer
about.html          The building, questions and house rules
login.html          Log in and sign up
account.html        My account: trips, saved, payments, personal info, security
checkout.html       Booking and payment (opened from an apartment page)

Rebuilding in WordPress with Elementor
These pages are a working design reference, not an Elementor import file. Rebuild each section with Elementor widgets and use the files below.
Fonts: fonts/Karla-Variable.ttf (body). Headings use Figtree from Google Fonts (weights 500, 600, 700).
Colours: navy #0E1B2C, deep navy #08111D, panel #1A2B42, border #2A3D57, gold #C29A4C, gold hover #D4AE62, cream #F3EEE4, text muted #C4CCD8, body text on light #4A5566.
Icons: assets/icons/*.svg (stroke icons, use currentColor so they take the widget colour). star.svg is a filled icon.
Badges: assets/badges/*.png (laurels, trophy, map pin, kitchen, star bubble).
Logos: assets/logo-dark-bg.svg, assets/logo-light-bg.svg. Host photo: assets/host-arni.jpg.
Photos: assets/photos (covers and building) and uploads/<apartment>/photos (full galleries).

Still to fill in: footer Instagram, Facebook and Tripadvisor links (currently #), email and phone on the home page footer, and real nightly rates in checkout.html (sample rates).
