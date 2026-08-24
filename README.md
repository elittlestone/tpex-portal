# tpex-portal (redirect only)

This repository used to host the Quarto build of the Tpex Data Portal on GitHub Pages.

**It was retired on 2026-08-24 and now contains only a redirect.** The portal is a Django
application, live at <https://tpex-portal.onrender.com/>, built from `webapp/` in the private
`Tpex_Data_Portal` repository and deployed by Render.

`index.html` and `404.html` are identical redirects. The 404 copy matters: GitHub Pages serves it
for any unknown path, so old deep links land on the redirect instead of a Pages error page.

The previous site is in this repository's git history if it is ever needed.
