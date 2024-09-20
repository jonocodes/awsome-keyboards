
# A talk about computer keyboards

by Jono

made using Marp

see rendered slides here:
http://jonocodes.github.io/awesome-keyboards

Note: Most of the text is in the speaker notes (press 'p') so the slide visuals dont stand on thier own. Press 'p' or visit http://localhost:8080/marp-slides.md?view=presenter


## Development Setup

### If using Nix

> devenv shell

### Else

install nodejs


## Running

Note: Embeded videos and iframes dont appear to show in the vscode preview, or local file html. So run in "server" mode.

Live watch with html iframe support:

> npx @marp-team/marp-cli@latest --html -w -s .
 
Visit http://localhost:8080/marp-slides.md


## To use a custom theme

> npx @marp-team/marp-cli@latest --theme ./dracula.css --html -w -s .

Visit http://localhost:8080/marp-slides.md


## Building

to compile for hosting (on github pages)

> npx @marp-team/marp-cli@latest marp-slides.md -o index.html