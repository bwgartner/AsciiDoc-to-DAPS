
# Simple, elegant way to create SUSE formatted documentation

Walking the path ...
- using simple text markup
  - AsciiDoc ( https://github.com/asciidoc/asciidoc )
    - with many choices of editors
      - Linux : vi/vim/gvim, emacs, gedit, ...
      - Multi-platform : Atom ( https://atom.io/ ), Visual Studio Code ( https://code.visualstudio.com ), ...
- convert to XML/DocBook, leveraging DocBook Authorting and Publishing Suite DAPS ( https://github.com/openSUSE/daps )
  - to render with your choice of multiple output formats ... epub, html (single or multipage), pdf

Quickstart ...

- Browse the following files
  - [DC-sample](./DC-sample) DAPS configuration file
  - [sample.adoc](./adoc/sample.adoc) 
    - [sample-include.adoc](./adoc/sample-include.adoc)
    - [sample_vars.adoc](./adoc/sample_vars.adoc)
  - [images](./images) directory where images are stored/referenced from
  - review [examples](./examples) to create and view some sample outputs

- DIY
  - either follow [tips.md](./tips.md) to create local structure or feel free to browse/pull this repository's template content
    - git clone "ThisGitHubRepoURL" (to make a local copy)
    - or download either master (zip), then unpack it
    - cd to your local directory where it landed (or was uncompressed)
  - test that you have all the tooling in place to generate an output
    - e.g. daps --force -d DC-sample html
    - test with a web browser, open the file:///localDirectoryName/build/sample/html/sample_draft/index.htm

