# Ecuadorian Accounting


Functional
----------

This module adds accounting features for Ecuadorian localization, which
represent the minimum requirements to operate a business in Ecuador in compliance
with local regulation bodies such as the ecuadorian tax authority -SRI- and the 
Superintendency of Companies -Super Intendencia de Compañías-

Follow the next configuration steps:
1. Go to your company and configure your country as Ecuador
2. Install the invoicing or accounting module, everything will be handled automatically

Highlights:
* Ecuadorian chart of accounts will be automatically installed, based on example provided by Super Intendencia de Compañías
* List of taxes (including withholds) will also be installed, you can switch off the ones your company doesn't use
* Fiscal position, document types, list of local banks, list of local states, etc, will also be installed

Technical
---------
Master Data:
* Chart of Accounts, based on recomendation by Super Cías
* Ecuadorian Taxes, Tax Tags, and Tax Groups
* Ecuadorian Fiscal Positions
* Document types (there are about 41 purchase documents types in Ecuador)
* Identification types
* Ecuador banks
* Partners: Consumidor Final, SRI, IESS, and also basic VAT validation
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_ec
```

## Dependencies

This addon depends on:
- base
- base_iban
- account
- account_debit_note
- l10n_latam_invoice_document
- l10n_latam_base

## Manifest Information

- **Name**: Ecuadorian Accounting
- **Version**: 3.9
- **Category**: Accounting/Localizations/Account Charts
- **License**: LGPL-3
- **Installable**: True

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_ec`.

## License

This package maintains the original LGPL-3 license from the upstream Odoo project.

## Documentation

- Overview: doc/OVERVIEW.md
- Architecture: doc/ARCHITECTURE.md
- Models: doc/MODELS.md
- Controllers: doc/CONTROLLERS.md
- Wizards: doc/WIZARDS.md
- Install: doc/INSTALL.md
- Usage: doc/USAGE.md
- Configuration: doc/CONFIGURATION.md
- Dependencies: doc/DEPENDENCIES.md
- Troubleshooting: doc/TROUBLESHOOTING.md
- FAQ: doc/FAQ.md
