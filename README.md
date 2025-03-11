
# Git for Confluence reference repository

This repository contains a set of files in different formats that you can use
to try out the Git for Confluence app. This repository comes preconfigured when
you install Git for Confluence! You can start immediately by using the
view-git-file macro on any Confluence page.

## Marketplace

You can install Git for Confluence by using the Universal Plugin Manager inside
Confluence, or by visiting the
[Git for Confluence marketplace entry](https://marketplace.atlassian.com/apps/1211675/git-for-confluence).

## Documentation

If you want to learn how to configure Git for Confluence or use the Git for
Confluence macro's, please refer tot the
[Git for Confluence documentation](https://avisi-apps.gitbook.io/git-for-confluence/).

# Formats

The are three main classes of formats that the Git for Confluence add-on natively
supports. These consist of Markdown, Image and PlantUML files. Showcase examples
that demonstrate how these can be used and rendered in Confluence are available
in the formats directory:
```bash
.
├── README.md
└── formats
    ├── code
    │   └── index.html
    ├── image
    │   ├── graph.png
    │   ├── logo.svg
    │   ├── success.jpg
    │   ├── tv.webp
    │   └── world.ico
    ├── markdown
    │   ├── image-reference.md
    │   └── images
    │       └── success.jpg
    └── plantuml
        ├── multi-block.puml
        ├── multi-page.puml
        └── simple-sequence-diagram.puml
```
These files can be directly added to the ``view-git-file`` Macro in Confluence
and will be rendered on a page.

## Image

Several images in several formats are available in the formats/markdown folder.
An image will simply be show as an image when included on a Confluence page by
using the ``view-git-file`` macro. Currently we support the following extensions:
* .png
* .jpg
* .webp
* .ico

## Markdown

You can simply use the ``view-git-file`` macro to include this file. There are
more markdown examples in the formats/markdown folder.

## PlantUML

There are a few basic and a few more advanced PlantUML examples available in
the formats/plantuml folder. Try out a basic sequence diagram, or the more
advanced examples, that result in multiple images on your Confluence page when
rendered with the ``view-git-file`` macro.
