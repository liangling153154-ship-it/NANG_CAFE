# Nâng Café

Website for Nâng Café, a coffee house in an earthen-wall home in Cao Bằng. In the Tày and Nùng languages, “Nâng” means the number 1.

075 tổ 10, P. Sông Hiến, Thục Phán, Cao Bằng, Việt Nam ·
[Instagram](https://www.instagram.com/naang.cafe/) ·
[Facebook](https://www.facebook.com/p/N%C3%A2ng-Cafe-100085033421351/) ·
[Google Maps](https://maps.app.goo.gl/TmgUhDWyS7gdo8w19)

## Structure
- `index.html`: a single static page with all CSS and JS inline and no build step
- `assets/fonts/`: self-hosted Be Vietnam Pro and Big Shoulders Display (SIL OFL)
- `media/nang/`: logo, favicon and photos of the café
- `data/nang-feed.json`: photos shown in the "Khoảnh khắc" carousel

## Run locally
Serve the folder, for example with `npx serve .`. Opening the file directly via `file://` won't load the photo carousel, because the page fetches `data/nang-feed.json`.
The site also works on GitHub Pages: Settings → Pages → Deploy from branch `main` / root.
