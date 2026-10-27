# Portfolio Grid — Bootstrap Exercise

An educational single-page portfolio layout with expandable resume, work and contact panels.

## Included UI

- Profile/header layout and collapsible content sections.
- A work-image grid and contact form presentation.

## Repository map

| Path | Purpose |
|---|---|
| [index.html](index.html) | Portfolio layout |
| [css](css) | Styles |
| [img](img) | Local images |

## Preview locally

Use a modern browser and Python 3 for a simple loopback-only static server. From a terminal:

```powershell
git clone https://github.com/s-hesam-s/Portfoilogrid.git
cd Portfoilogrid
```

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000/index.html`. Keep the terminal open while previewing and press Ctrl+C to stop it. No database or application backend is needed.

There is no package manifest or build step in this repository; the checked-in HTML and CSS are the preview inputs.

## External resources

The pages reference resources from `cdn.jsdelivr.net`, `code.jquery.com`, `unsplash.it`, `use.fontawesome.com`. Internet access is needed for the referenced CDN scripts, fonts or remote images; the repository is not a fully offline asset bundle. Third-party resource availability can affect the preview.

## Verification and limitations

Open each section, resize the grid and inspect the contact layout. The sample John Doe content is demonstration copy, not a description of the repository owner. Social links, work images and form submission need real application data before reuse.

No automated behavior-test suite is included. Preview instructions are not a claim that every third-party widget is compatible with current CDN responses. Application services, persistent storage and deployment are outside this UI exercise.

## Project scope and reuse

This is an educational repository. The implementation notes describe the code in this repository; they do not claim a deployed commercial service or measured production results. Third-party libraries and assets retain their own terms. No project-wide license is currently declared.
