# WHT Web Calculator

Calculate withholding tax (WHT) from invoice amounts instantly.

## Overview

**wht-web** is a simple, browser-based calculator for determining withholding tax obligations and the net amount due to suppliers. Enter your invoice amount and applicable WHT rate, and get instant results.

## Quick Start

1. Clone this repo:
   ```bash
   git clone https://github.com/Wyzdmulc/wht-web.git
   ```

2. Open `index.html` in your browser or serve locally:
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`

3. Enter your invoice amount and WHT percentage, then calculate.

## What is Withholding Tax?

Withholding Tax (WHT) is a portion of payment withheld and remitted to tax authorities before paying a supplier. This tool calculates:

- **Withholding Tax Amount** = Invoice Amount × (WHT Rate ÷ 100)
- **Amount to Pay Supplier** = Invoice Amount − Withholding Tax Amount

## Example

| Item | Amount |
|------|--------|
| Invoice Amount | $1,000 |
| WHT Rate | 5% |
| **Withholding Tax** | **$50** |
| **Amount to Pay** | **$950** |

## Purpose
The purpose of the website is to help institutions easily calculate Withholding tax. it also help uncover the calculation of VAT, PPDA, and in some cases Retention, NCIC, and Tourism levy. this will ensure accurate tax calculation hence paying the supplier the required amount and submit to MRA the required tax returns. it is made to be simple to use that even those who doesn't know or understand the tax calculations may be able to use, and make proper transactions.

## Features

✓ Real-time calculation  
✓ Client-side only (no server required)  
✓ Simple, clean interface  
✓ Works on desktop and mobile  

## Technology Stack

- **HTML** (60.8%) — structure
- **JavaScript** (28.8%) — calculations and interactivity
- **CSS** (10.4%) — styling

## Contributing

Found a bug or have a feature idea? Open an issue or submit a pull request.

## License

See LICENSE file for details.

---

**Need help?** Open an issue on GitHub: https://github.com/Wyzdmulc/wht-web/issues
