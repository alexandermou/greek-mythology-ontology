# Greek Mythology Interactive Ontology

Interactive bilingual (English/Chinese) visualization of Greek mythology characters, stories, sources, and relationships.

## v1.2.1

- Adds Nike, Styx, Pallas, Zelos, Kratos, Bia, and Eurybia with 20 passage-anchored relationships from Hesiod’s *Theogony*.
- Adds Styx and her four children to the Titanomachy event.
- Updates canonical JSON, JSON-LD, Turtle, manifest, and both interactive views.

## v1.2

- Adds richer character details for type, story cycle, and generation.
- Distinguishes sibling relationships from variant traditions.
- Improves network clustering, spacing, and portrait presentation.
- Includes the complete v1.0 ontology data exports and release metadata.

## GitHub Pages

This repository is a static site. Publish the repository root from the `main` branch with GitHub Pages. The root page redirects to `ontology/`.

## Local preview

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.
