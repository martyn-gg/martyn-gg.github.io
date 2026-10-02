# martyn-gg.github.io

The front page at <https://greville-giddings.me/>; <https://martyn-gg.github.io/> redirects
there. One HTML file, no build step. `CNAME` holds the custom
domain; GitHub wrote it when the domain was set under Settings → Pages.

The header shows tonight's sky: the Moon's phase, where the five naked-eye planets are,
and a plan of all eight around the Sun. It uses the orrery's JPL elements, Kepler solver
and abridged lunar theory, copied into the page, so it fetches nothing. If the orrery's
elements or lunar theory change, change them here too.

It links to each project, and each project is its own repository with its own Pages
deployment. A project repo named `name` publishes at
`https://greville-giddings.me/name/` unless it has a custom domain of its own, as the figure skating guide does.

To add a project, copy one `<a class="card">` block in `index.html` and change the link,
picture, title, description and address line. The grid makes room for it.

GitHub publishes a repository named `<username>.github.io` from the root of `main`.
`.nojekyll` stops it running the page through Jekyll.
