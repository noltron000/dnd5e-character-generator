# Character Generator for D&D 5e
> *View the project live at [https://projects.nebuloid.dev/dnd5e-character-generator/](https://projects.nebuloid.dev/dnd5e-character-generator/).*

A "vanilla" character generator using backgrounds &amp; races from the player's handbook.
Generates everything but the character class, you can pick that yourself!
This defaults to a "level zero" character with a +1 proficiency bonus, increase it to +2 when you pick a class.

This project was set up to be compatible with a printer, in an 8&frac12;"&times;11" paper format.

![Some dice for generating your character](https://repository-images.githubusercontent.com/236939432/9ba64abd-450f-4b4a-951f-3a6f50f69fe2)

## Running Locally
You can get this website running locally with a few commands in your terminal:
1. Download the code using `git clone`.
1. Enter the project directory via `cd`.
1. Run a web-server locally using `python -m http.server 8000`.
	- Ensure Python is installed locally on your machine.
1. Open [http://localhost:8000](http://localhost:8000) in your browser to view the site.
	Stop the server with `Ctrl+C`.

## Deploy using GitHub Pages
The site is hosted with GitHub Pages from the `main` branch at the repository root.
Whenever `main` receives new commits, the pages should update automatically.
