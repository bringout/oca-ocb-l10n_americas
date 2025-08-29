# Brazilian - Accounting


Base module for the Brazilian localization
==========================================

This module consists of:

 - Generic Brazilian chart of accounts
 - Brazilian taxes such as:

        - IPI
        - ICMS
        - PIS
        - COFINS
        - ISS
        - IR
        - IRPJ
        - CSLL

The field tax_discount has also been added in the account.tax.template and
account.tax objects to allow the proper computation of some Brazilian VATs
such as ICMS. The chart of account creation wizard has been extended to
propagate those new data properly.

It's important to note however that this module lack many implementations to
use Odoo properly in Brazil. Those implementations (such as the electronic
fiscal Invoicing which is already operational) are brought by more than 15
additional modules of the Brazilian Launchpad localization project
https://launchpad.net/openerp.pt-br-localiz and their dependencies in the
extra addons branch. Those modules aim at not breaking with the remarkable
Odoo modularity, this is why they are numerous but small. One of the
reasons for maintaining those modules apart is that Brazilian Localization
leaders need commit rights agility to complete the localization as companies
fund the remaining legal requirements (such as soon fiscal ledgers,
accounting SPED, fiscal SPED and PAF ECF that are still missing as September
2011). Those modules are also strictly licensed under AGPL V3 and today don't
come with any additional paid permission for online use of 'private modules'.


## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_br
```

## Dependencies

This addon depends on:
- account
- base_vat

## Manifest Information

- **Name**: Brazilian - Accounting
- **Version**: N/A
- **Category**: Accounting/Localizations/Account Charts
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_br`.

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
