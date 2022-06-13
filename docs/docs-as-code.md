# Docs-as-code<!-- omit in toc -->

Documentation as code (docs-as-code) is an approach to developing and
maintaining technical documentation using the same tools and processes used to
write code.

## Contents<!-- omit in toc -->

- [General information](#general-information)
  - [Books](#books)
- [Git](#git)
  - [Tutorials](#tutorials)
  - [Reference](#reference)
- [Docs-as-code tool chain](#docs-as-code-tool-chain)
  - [Documentation generators](#documentation-generators)
  - [Static site generators (SSGs)](#static-site-generators-ssgs)
  - [Version control](#version-control)

## General information

- [Docs as Code](https://www.writethedocs.org/guide/docs-as-code) &ndash; a
  high-level overview of docs-as-code from Write the Docs.
- [Docs as Code: An introduction for beginners](https://www.knowledgeowl.com/home/docs-as-code)
  &ndash; an introduction to docs-as-code that includes pros and cons of the
  approach.
- [Docs-As-Code Demo](https://papercut-docs-as-code.gitlab.io/docs-as-code/index.html)
  &ndash; a tutorial demo and several presentations on the subject from
  PaperCut Software.

### Books

- [Docs Like Code](https://www.docslikecode.com/) by Anne Gentle
- [Modern Technical Writing](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
  by Andrew Etter

## Git

Git is the most commonly used version control system for docs-as-code. It is
often used in connection with a service such as [GitHub](https://github.com/)
or [GitLab](https://gitlab.com/).

### Tutorials

- [GitHowTo](https://githowto.com/) &ndash; a guided tour that walks through
  the fundamentals of Git.

### Reference

- [git Reference Manual](https://git-scm.com/docs) &ndash; the official manual
  that is included with the git command line tool.
- [Pro Git](https://git-scm.com/book/) by Scott Chacon and Ben Straub &ndash; a
  free eBook about using git.

## Docs-as-code tool chain

Each tool listed below is tagged with one or more of the following tags to
provide additional context.

| Tag            | Description                                    |
| -------------- | ---------------------------------------------- |
| `#linux`       | Runs on Linux*                                 |
| `#macos`       | Runs on macOS                                  |
| `#open-source` | Open source software offered at no charge      |
| `#windows`     | Runs on Windows                                |

\* *Command line software written for Linux may also run on Windows using the
[Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/about)*

### Documentation generators

- [Asciidoctor](https://asciidoctor.org/) &ndash; a command line tool that
  publishes AsciiDoc files to HTML, DocBook, PDF, EPUB, and other formats.
  `#open-source` `#windows` `#linux` `#macos`
- [DITA Open Toolkit](https://www.dita-ot.org/) &ndash; a suite of command line
  tools that provide processing for content authored in the Darwin Information
  Typing Architecture. `#open-source` `#windows` `#linux` `#macos`
- [docToolChain](https://doctoolchain.org/) &ndash; a collection of scripts
  that makes it easy to create and maintain technical documentation.
- [pandoc](https://pandoc.org/) &ndash; a command line tool that can convert
  documents to or from dozens of file formats. `#open-source` `#windows`
  `#linux` `#macos`
- [Sphinx](https://www.sphinx-doc.org/) &ndash; a tool to create documentation
  from reStructuredText files. Sphinx can out HTML, LaTeX, EPUB, and more.
  `#open-source` `#windows` `#linux` `#macos`

### Static site generators (SSGs)

- [Antora](https://antora.org/) &ndash; a tool for generating documentation
  sites from collections of AsciiDoc files stored in git repositories.
  `#open-source` `#windows` `#linux` `#macos`
- [Docusaurus](https://docusaurus.io) &ndash; built by Facebook, this tool
  builds documentation websites, blogs, and more from Markdown or MDX files.
  `#open-source` `#linux` `#macos`
- [Jekyll](https://jekyllrb.com/) &ndash; an established and robust tool for
  generating static websites and blogs from Markdown files. This is the tool
  that powers GitHub Pages. `#open-source` `#linux` `#macos`
- [MkDocs](https://www.mkdocs.org/) &ndash; a fast and simple tool for building
  static sites from Markdown files. `#open-source` `#linux` `#macos`

### Version control

- [git](https://git-scm.com/) &ndash; the official git command line client.
  `#open-source` `#windows` `#linux` `#macos`
- [GitHub CLI](https://cli.github.com/) &ndash; a command line client for the
  GitHub service. `#open-source` `#windows` `#linux` `#macos`
- [GitHub Desktop](https://desktop.github.com/) &ndash; GitHub's graphical user
  interface for managing git repositories (even those not on GitHub).
  `#open-source` `#windows` `#macos`
- [GitHub Mobile](https://github.com/mobile) &ndash; a mobile client for
  managing GitHub repositories. `#free` `#ios` `#ipados` `#android`
