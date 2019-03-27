# CSS-for-PDF
CSS to be used when converting Markdown files to PDF

Direct Link to CSS

[https://raw.githubusercontent.com/sandeeprenjith/CSS-for-PDF/master/pdf.css](https://raw.githubusercontent.com/sandeeprenjith/CSS-for-PDF/master/pdf.css)


#### Sample PDF 

[Download Sample PDF](https://github.com/sandeeprenjith/CSS-for-PDF/raw/master/Sample.pdf)

#### Additional info

Command to generate PDF from markdown using pandoc (on Windows)

```
pandoc -f markdown -t html5 -o "Sample.pdf" --css pdf.css .\sample-pdf.md
```

```
PS C:\Users\srenjith\Dropbox\SaaS\WBR\CSS-for-PDF> pandoc -f markdown -t html5 -o "Sample.pdf" --css pdf.css .\sample-pdf.md
[WARNING] This document format requires a nonempty <title> element.
  Please specify either 'title' or 'pagetitle' in the metadata,
  e.g. by using --metadata pagetitle="..." on the command line.
  Falling back to 'sample-pdf'
Loading pages (1/6)
Counting pages (2/6)
Resolving links (4/6)
Loading headers and footers (5/6)
Printing pages (6/6)
Done
```
