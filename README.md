# Quarto template for the *Journal of Quantitative Analysis in Sports*

  <!-- badges: start -->
  [![R-CMD-check](https://github.com/beanumber/jqas/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/beanumber/jqas/actions/workflows/R-CMD-check.yaml)
  <!-- badges: end -->

## Creating a New Article

To create a new article using this format:

```bash
quarto use template beanumber/jqas
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add beanumber/jqas
```

Then, add the format to your document options:

```yaml
format:
  jqas-pdf: default
```    

## Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

<!-- pdftools::pdf_convert('template.pdf',pages = 1) 
![[template.qmd](template.qmd)](template_1.png) -->
