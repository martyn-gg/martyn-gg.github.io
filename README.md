# martyn-gg.github.io

The front page at <https://martyn-gg.github.io/>. One HTML file, no build step.

It links to each project, and each project is its own repository with its own Pages
deployment. A project repo named `name` publishes at `https://martyn-gg.github.io/name/`
unless it has a custom domain, as the figure skating guide does.

To add a project, copy one `<a class="card">` block in `index.html` and change the link,
picture, title, description and address line. The grid makes room for it.

GitHub publishes a repository named `<username>.github.io` from the root of `main`.
`.nojekyll` stops it running the page through Jekyll.
