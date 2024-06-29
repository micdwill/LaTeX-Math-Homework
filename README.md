# LaTeX Math Homework Template

This repository provides a versatile and customizable LaTeX template for formatting and typesetting math homework assignments. Originally created for Math 451 (Intro to Analysis) at the University of Michigan, this template includes several features to streamline the creation of structured and professional-quality documents.

## Features

### Custom Commands and Environments

- **Colored Boxes:** The `\begin{mybox} ... \end{mybox}` command creates a colored box around the enclosed content. The color can be easily adjusted by modifying the settings in `preamble.tex`.
  
- **Difficulty Rating:** Use the `\begin{rating} \rating{number} \end{rating}` command to assign and display a difficulty rating to proof problems, providing an intuitive way to indicate the complexity of each problem.

### Flexible Document Structure

- **Sectioned Layout:** Organized sections for title, author information, and individual problems make it easy to navigate and edit the document.
  
- **Problem Formatting:** Customizable problem formats to suit different types of math problems and solutions.

### High-Quality Typesetting

- Designed to produce clean and professional-looking PDFs.
  
- Integrated with LaTeX’s powerful typesetting capabilities, particularly well-suited for mathematical notation and complex formulas.

## Getting Started

To use this template, ensure you have LaTeX installed on your system. You can download LaTeX from [LaTeX Project](https://www.latex-project.org).

### Installation

**Clone the Repository:**

```bash
git clone https://github.com/micdwill/LaTeX-Math-Homework.git
```
### Compile the LaTeX file:

Use a LaTeX editor or the command line to compile homework.tex into a PDF:

```bash
latexmk -pdf homework.tex
```

## Usage

**Editing `homework.tex`:**

- Open `homework.tex` in your preferred LaTeX editor.
  
- Replace placeholder text with your specific homework details, including the title, author, and problems.
  
- Utilize the provided commands to insert equations, figures, and tables seamlessly.

**Customizing with `preamble.tex`:**

- The `preamble.tex` file contains custom LaTeX commands and settings. Modify these to adjust the document's appearance and functionality.
  
- Change the color settings for the `mybox` environment or adjust the difficulty rating display as needed.

### Example Content

The example provided in this template is based on concepts from Riemann integration, step functions, and limits of functions. It serves as a practical demonstration of how to use the template’s features to present complex mathematical topics clearly and effectively.

## Academic Context

This template was initially developed for an assignment in Math 451, Intro to Analysis, at the University of Michigan. The course covers foundational topics in real analysis, such as the theory of integration and the behavior of functions, providing a rigorous introduction to the principles of mathematical analysis.

