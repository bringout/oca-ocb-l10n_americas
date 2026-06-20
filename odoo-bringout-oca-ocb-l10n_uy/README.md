# Uruguay - Accounting


General Chart of Accounts.
==========================

This module adds accounting functionalities for the Uruguayan localization, representing the minimum required configuration for a company to operate in Uruguay under the regulations and guidelines provided by the DGI (Dirección General Impositiva).

Among the functionalities are:

* Uruguayan Generic Chart of Account
* Pre-configured VAT Taxes and Tax Groups.
* Legal document types in Uruguay.
* Valid contact identification types in Uruguay.
* Configuration and activation of Uruguayan Currencies  (UYU, UYI - Unidad Indexada Uruguaya).
* Frequently used default contacts already configured: DGI, Consumidor Final Uruguayo.

Configuration
-------------

Demo data for testing:

* Uruguayan company named "UY Company" with the Uruguayan chart of accounts already installed, pre configured taxes, document types and identification types.
* Uruguayan contacts for testing:

   * IEB Internacional
   * Consumidor Final Anónimo Uruguayo.



## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_uy
```

## Dependencies

- account
- l10n_latam_invoice_document
- l10n_latam_base

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 17.0
- Path: addons/l10n_uy

## License

This package preserves the original LGPL-3 license.
