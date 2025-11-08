# Scribd Downloader

A little Python script I made to grab documents from Scribd when I needed them.
Just a personal solution that I cleaned up a bit and put here for reference.

## Features
- Download documents as images or text.
- Automatically turns downloaded images into a PDF.

## Usage

```bash
python scribdl.py [-i] DOC
```

## Arguments

`DOC`: Scribd document URL.
`-i` : Download document as images. PDF conversion is automatic if images are downloaded.

Example:
```bash
python scribdl.py -i https://www.scribd.com/document/xxxxxx
```
