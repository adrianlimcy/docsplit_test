# README

This is used to familiarise gem docsplit.

Source:
https://github.com/documentcloud/docsplit
http://documentcloud.github.io/docsplit/

ruby version 2.6.0-dev

Installation & Dependencies
Grab the gem:
gem install docsplit
Install GraphicsMagick. Its ‘gm’ command is used to generate images.
Either compile it from source, or use a package manager:
[aptitude | port | brew] install graphicsmagick
Install Poppler. On Linux, use aptitude, apt-get or yum:
aptitude install poppler-utils poppler-data
On the Mac, you can install from source or use MacPorts:
sudo port install poppler | brew install poppler
(Optional) Install Ghostscript:
[aptitude | port | brew] install ghostscript
Ghostscript is required to convert PDF and Postscript files.
(Optional) Install Tesseract:
[aptitude | port | brew] install [tesseract | tesseract-ocr]
Without Tesseract installed, you'll still be able to extract text from documents, but you won't be able to automatically OCR them.
(Optional) Install pdftk. On Linux, use aptitude, apt-get or yum:
aptitude install pdftk
On the Mac, you can download a recent installer for the binary. Without pdftk installed, you can use Docsplit, but won't be able to split apart a multi-page PDF into single-page PDFs.
(Optional) Install LibreOffice. On Linux, use aptitude, apt-get or yum:
aptitude install libreoffice
On the Mac, download and install the latest release.
