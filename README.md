# Quarto template for ICCR 2024

This template can be used to write an abstract for ICCR 2024 using [Quarto].

> [!NOTE]
> This is **NOT** an official template from the organizers of ICCR 2024. I have merely forked [their official repository](https://github.com/tbaudier/iccr2024_templates) and tried to make a quarto template from it that resembles theirs as close as possible.


[Quarto]: https://quarto.org


## Using the Template

To start writing an abstract with this template, use the following command

```
quarto use template rmnldwg/quaro-iccr
```

which will create a new project based off of this template.

You still need to get rid of all the placeholder stuff in the `*.qmd` file that you can now find in the directory created by [Quarto]. Also, don't forget to replace/update the `references.bib` file and the `fig1.pdf`.


## Render LaTeX and PDF

To render a LaTeX and PDF for submission from the template, run this command:

```
quarto render <name-of-your .qmd file> --to iccr-pdf
```
