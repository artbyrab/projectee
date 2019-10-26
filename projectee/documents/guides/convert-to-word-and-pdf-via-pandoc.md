# Convert to word and PDF via Pandoc

Pandoc is a great way to generate Word and PDF files from Markdown. I will provide a basic tutorial and examples here.

## Installing Pandoc

Before you can perform any generation via Pandoc you need to install it. For full information on how to install visit the official site

* https://pandoc.org/

## Information

* Pandoc converts Markdown files into other formats
* Pandoc works from the command line
* You need to have Pandoc installed on your system

## Examples

To see the example files please navigate to the files/pandoc-examples folder in this repo.

### Generate PDF from a single markdown file

* Navigate to the projectee/files/pandoc-examples/single-file-to-pdf folder

```
$ pandoc -o exports/example.pdf -f markdown -t latex example.md
```

### Generate PDF from multiple markdown files

* Navigate to the projectee/files/pandoc-examples/multiple-files-to-pdf folder

```
$ pandoc -o exports/example.pdf -f markdown -t latex example-a.md example-b.md example-c.md
```


### Generate a word processor document from a single markdown file

* Navigate to the projectee/files/pandoc-examples/single-file-to-word-doc folder

```
$ pandoc -o exports/example.docx -f markdown -t docx example.md
```
