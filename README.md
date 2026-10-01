# Returning Racer

## Overview

Returning Racer is a static website project originally created as part of the **eCollege WebAuthoring (Adobe Dreamweaver) course** in 2016.

It is an online catalogue of bicycles covering **Mountain, Urban and Road Racing** bikes.

**Live site:** [Returning Racer](https://returningracer.github.io/)

**Course:** [eCollege WebAuthoring (Adobe Dreamweaver)](https://www.ecollege.ie/)<span style="color: grey;"> Since retired</span>
## Features

* Homepage with visual navigation to the main bicycle categories
* Separate Mountain, Urban and Road Racing sections
* Image-based navigation
* Bicycle catalogue pages
* Custom CSS styling
* Structured website directories for each bicycle category
* Static hosting through GitHub Pages

## Website Structure

| Section         | Description                                    |
| --------------- | ---------------------------------------------- |
| **Urban**       | Catalogue of urban bicycles                    |
| **Mountain**    | Catalogue of mountain bicycles                 |
| **Road Racing** | Catalogue of road racing bicycles              |
| **Dashboard**   | Shared website images and supporting resources |
| **CSS**         | Website stylesheets                            |
| **Images**      | Image resources used throughout the project    |

## Project Structure

```text
returningracer.github.io/

│
├── index.html
├── bootstrap.css
├── menu.css
├── mountain-home.jpg
├── LICENSE.md
│
├── css/
│   └── ...
│
├── Images/
│   └── ...
│
├── Mountain/
│   └── ...
│
├── Roadracing/
│   └── ...
│
├── Urban/
│   └── ...
│
├── dashboard/
│   └── ...
│
└── htdocs/
    └── ...
```

## Homepage

The homepage provides visual entry points into the three principal areas of the website:

* Urban
* Mountain
* Road Racing

The navigation uses HTML image maps to make defined areas of the homepage graphics clickable.

## Design

The website uses custom CSS for the overall presentation and navigation.

The repository also contains Bootstrap CSS and separate directories for the site's images, styles and individual bicycle categories.

## Development

The project is a static website and does not require a server-side application or database to display the catalogue.

The repository can be run locally by opening the website through a local web server or deployed as a static GitHub Pages website.

## Author

**Pio O'Connell**

## Repository

[Returning Racer on GitHub](https://github.com/ReturningRacer/returningracer.github.io)

## License

See `LICENSE.md` for licensing information.
