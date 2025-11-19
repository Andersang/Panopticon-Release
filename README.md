# Panopticon

Panopticon is a desktop application for managing and searching through PDF documents with advanced text extraction and bookmarking capabilities.

## Features

- Intelligent search across thousands of PDF pages
- Text extraction using OCR on your device
- Bookmarking capabilities for quick access to important pages
- Real-time file system monitoring
- Local storage: all data stored in ```documents/Panopticon``` (settings, Python environment, saved searches) and within your library directories (processed indexes)

## Prerequisites

### Platform Support

- Windows only (I don't have a Mac to test this on)

### Document OCR

PDFs are processed locally with the help of [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF). To process these PDFs yourself you must first install these packages:

- [Python 3.11+](https://www.python.org/downloads/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
- [Ghostscript](https://www.ghostscript.com/releases/gsdnld.html)


## Support Development

If you find Panopticon useful, please consider [supporting me on Ko-fi](https://ko-fi.com/andersang).

## Licence Overview

### Free for Everyone

Panopticon is free for all purposes, including personal, commercial, and non-profit use.

### No Account Required

Downloading and using Panopticon requires no account, and we do not collect your personal information.

### Your Data Remains Local

Your processed search indices and application data are saved locally on your device. Your search activity remains entirely private on your machine, as we don't run any servers for Panopticon itself.

#### Document OCR

All processing occurs entirely on your device.

### You Own Your Content

You retain full ownership of all content you process in Panopticon. We claim no rights to it.

We own and reserve rights to our own content, including the application's text, images, and code, which are protected by copyright and other laws.

### Terms of Use

By using Panopticon, you agree to our [Terms of Service](#terms-of-service). Please read these terms carefully, as they outline our relationship, including provisions for licensing, security, privacy, liability, and dispute resolution.

## Why Not Open Source?

Panopticon isn't open-sourced because we wish to preserve the option of building a sustainable, commercial future for it. Keeping the code private helps prevent low-effort clones or repackaged versions that could dilute its quality or confuse users.

Every version released will continue to work indefinitely, provided your operating system supports it. The goal is to keep Panopticon accessible, reliable, and entirely under your control, whilst allowing us to explore ways to sustain its development over time.

## Terms of Service

**Last updated: 19/11/2025**

## Agreement

By using Panopticon, you agree to these Terms of Service. If you do not agree, please do not use the software.

## License

We grant you a free, non-transferable, non-exclusive licence to use Panopticon for any purpose, including personal, commercial, and non-profit use.

You may not:

- Sell, rent, lease, or distribute/re-distribute Panopticon
- Reverse engineer or decompile the software
- Remove copyright notices or branding
- Use Panopticon for unlawful purposes

## Ownership

**Your Content**: You retain full ownership of all content you process through Panopticon. We claim no rights to your files, notes, or data.

**Our Software**: We own all rights to Panopticon's code, design, and branding. The software is licensed to you, not sold.

## Third Party Services

### OCR Tools

To perform OCR on PDFs, you must install Python, Tesseract, and Ghostscript separately. Panopticon will then create a Python virtual environment for other
 tools such as OCRmyPDF. These tools are governed by their respective licences and terms.

## Privacy and Data

We do not collect, store, or transmit your personal information. Your search indices and application data remain on your device. We operate no servers for Panopticon.

## Disclaimer

Panopticon is provided "as is" without warranties of any kind. We do not guarantee that the software will be error-free, uninterrupted, or suitable for your specific needs.

We are not responsible for:

- Loss of data or content
- Accuracy or completeness of search results
- Issues arising from third party services
- Compatibility with your system or other software

## Limitation of Liability

To the maximum extent permitted by law, we shall not be liable for any indirect, incidental, special, or consequential damages arising from your use of Panopticon. Our total liability shall not exceed the amount you paid for Panopticon (which is zero, as the software is free).

This limitation does not exclude liability for death or personal injury caused by our negligence, or for fraud.

## User Responsibilities

You agree to:

- Use Panopticon only for lawful purposes
- Comply with all applicable laws
- Not use the software to harm others or their property
- Not upload or process content that infringes third party rights

You are solely responsible for ensuring your use of Panopticon complies with relevant regulations, including those of the Board of Architects Singapore.

## Termination

You may stop using Panopticon at any time by uninstalling the software. We reserve the right to discontinue development or support of Panopticon without notice.

## Changes to Terms

We may update these Terms of Service from time to time. Continued use of Panopticon after changes constitutes acceptance of the revised terms.

## Governing Law

These Terms are governed by the laws of Singapore. Any disputes shall be resolved in the courts of Singapore.

## Contact

For questions about these Terms of Service, please contact: [andersang.wl@gmail.com](mailto:andersang.wl@gmail.com)

---
