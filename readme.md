EPUB 3 Boilerplate
==================
An EPUB 3.0 template (including iBooks display options) to help you get started with your ebook.

Forked from https://github.com/reitermarkus/epub3-boilerplate

---


# Structure of an EPUB file

    ▾ /
      ▾ META-INF/
        ▪ container.xml
      ▪ mimetype
      ▾ OPS/ (Open Publishing Structure)
        ▾ book/
          ▪ cover.xhtml
          ▪ title-and-copyright.xhtml
          ▪ table-of-contents.ncx (only needed for EPUB 2.0 backward-compatibility)
          ▪ table-of-contents.xhtml
          ▪ chapter1.xhtml
          ▪ chapter2.xhtml
          ▪ chapter3.xhtml
          // more chapters as needed
        ▾ css/
          ▪ style.css
        ▾ images/
          ▪ cover.png
        ▪ package.opf

# How To Use

This template is designed to be a starting point for an EPUB v3 file. Currently using v3.0, but eventually will be updated to v3.2.
