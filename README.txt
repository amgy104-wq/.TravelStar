TRAVEL STAR - HANOI TOUR WEBSITE

FILES
- index.html: Home
- about.html: About Us
- tours.html: all tours
- hanoi-tour.html: detailed Hanoi 2D1N tour (main assignment content)
- ninh-binh.html: additional tour
- sapa.html: additional tour
- danang-hoian.html: additional tour
- services.html: services
- contact.html: contact form
- style.css: shared design

RUN LOCALLY
1. Put all files in one folder.
2. Double-click index.html.
3. Use the menu and click "View tour" on the tour cards.

PUBLISH WITH GITHUB PAGES
1. Go to github.com and sign in.
2. Create a NEW PUBLIC repository, e.g. travel-star.
3. Upload every file in this folder to the repository root.
4. Open Settings -> Pages.
5. Under Build and deployment choose "Deploy from a branch".
6. Branch = main; Folder = / (root).
7. Click Save.
8. Wait a short time. GitHub gives a URL like:
   https://YOUR-USERNAME.github.io/travel-star/
9. Open that URL in Chrome. For presentation, press F11.

IMPORTANT
The main Hanoi tour page uses exactly the supplied assignment content:
- 2 days 1 night
- Hanoi, Vietnam
- 3-star hotel in the Old Quarter
- Tourist bus and walking
- Individual tourists / young travelers
- About 1,550,000 VND/person
- Day 1 and Day 2 itinerary
- Includes and excludes
Other tours are supporting sample content so the Tours section has multiple clickable tour cards.
Images are loaded from Unsplash URLs, so internet is required for the photos and Google Fonts.

HANOI IMAGE NOTE
The main Hanoi visual is the exact Hoan Kiem Lake / Turtle Tower image supplied for the assignment.
The Hanoi tour page also uses location-specific images for Ba Dinh Square/Ho Chi Minh Mausoleum,
One Pillar Pagoda, Temple of Literature, Ta Hien Street and Hoa Lo Prison. These are not generic
Da Nang/Hoi An images.


HANOI IMAGE FIX (SELF-CONTAINED)
- The main Hanoi image is embedded directly inside the HTML/CSS, so it does NOT depend on the images folder or an external image host.
- The Hanoi hero, Hanoi tour card, About page Hanoi image, and Day 2 image are all self-contained.
- The Hanoi highlights gallery uses Hanoi-specific Wikimedia Commons images.
- When uploading to GitHub Pages, upload the HTML/CSS files from this folder; the main Hanoi image will still work even if the images folder is omitted.
