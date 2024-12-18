# LaTeX Homework Template
## Masters of Software Engineering

This repository provides a template for homework assignments at the University of Applied Sciences Technikum Wien. The template is designed to enable professional-quality digital submissions in an educational context.

## Makefile

The Makefile automates the LaTeX build process. Building the template with the
Makefile requires `latexmk` and a reasonably recent version of `TeX Live`.

### Targets

- **all**: Builds the document.  
  ```bash
  make
  ```

- **clean-build**: Cleans and rebuilds the document.  
  ```bash
  make clean-build
  ```

- **build**: Compiles the LaTeX document to PDF.  
  ```bash
  make build
  ```

- **watch**: Watches for changes and recompiles automatically.  
  ```bash
  make watch
  ```

- **clean**: Removes auxiliary files, keeps the PDF.  
  ```bash
  make clean
  ```

- **clean-all**: Removes all generated files, including the PDF.  
  ```bash
  make clean-all
  ```

## Requirements

- `latexmk` installed
- Recent version of TeX Live
