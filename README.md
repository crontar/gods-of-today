# Gods of Today

This project holds the static web resources that are used by Github Jekyll site generator to generate a 
static web site for this game.  If you are interested in contributing, create a branch and make a pull request
or submit contect directly to me or some that can update stuff it GitHub.

https://crontar.github.io/gods-of-today/

## Updating site

`/assets/images`

JPEG picture files for embedding in MD files that get converted to HTML

`/docs`

Markdown files that get converted to HTML and are linked to from the `index.md` or other Markdown files in the
same directory.

**NOTE:** Specify links to other Markdown files as if they were HTML files so links will work after Jekyll 
converts them.

e.g. `[Gerrard Malleus](docs/gerrard.html "Gerrard Malleus")` links to `docs/gerrard.md` file