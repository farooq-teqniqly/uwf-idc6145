# Code for STA6232 (Spring 2025)

## Prerequisites (if using Visual Studio Code)

Follow the steps [here](https://code.visualstudio.com/docs/languages/r) to configure Visual Studio Code for R.

## Run the Code

1. After cloning the repository, open the repository root in Visual Studio Code.
2. In Visual Sutdio Code, open a new R terminal.
3. Run the following command to install the `renv` package:

```R
install.packages("renv")
```

4. Run `renv::restore()` to install required packages as specified in the `renv.lock` file.
5. Open an R file in the editor, i.e. `week-01\office-ratings.r`.
6. Run the file.

## Formatting Files

The following code formats R files according to the configuration specified in the `.lintr` file:

```R
styler::style_dir("./")
```

## Render Quarto Markdown Files

To render Quarto markdown files (.QMD) do the following:

1. [Install the Quarto CLI](https://quarto.org/docs/get-started/)
2. [Install the Quarto extension for VS Code](https://marketplace.visualstudio.com/items?itemName=quarto.quarto)
3. Open a QMD file in Visual Studio Code.
4. Press `CTRL+Shift+K` to render the document to HTML.
