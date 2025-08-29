# Argentina - Accounting


Functional
----------

This module add accounting features for the Argentinean localization, which represent the minimal configuration needed for a company  to operate in Argentina and under the AFIP (Administración Federal de Ingresos Públicos) regulations and guidelines.

Follow the next configuration steps for Production:

1. Go to your company and configure your VAT number and AFIP Responsibility Type
2. Go to Accounting / Settings and set the Chart of Account that you will like to use.
3. Create your Sale journals taking into account AFIP POS info.

Demo data for testing:

* 3 companies were created, one for each AFIP responsibility type with the respective Chart of Account installed. Choose the company that fix you in order to make tests:

  * (AR) Responsable Inscripto
  * (AR) Exento
  * (AR) Monotributo

* Journal sales configured to Pre printed and Expo invoices in all companies
* Invoices and other documents examples already validated in “(AR) Responsable Inscripto” company
* Partners example for the different responsibility types:

  * ADHOC (IVA Responsable Inscripto)
  * Servicios Globales (IVA Sujeto Exento)
  * Gritti (Monotributo)
  * Montana Sur. IVA Liberado in Zona Franca
  * Barcelona food (Cliente del Exterior)
  * Odoo (Proveedor del Exterior)

Highlights:

* Chart of account will not be automatically installed, each CoA Template depends on the AFIP Responsibility of the company, you will need to install the CoA for your needs.
* No sales journals will be generated when installing a CoA, you will need to configure your journals manually.
* The Document type will be properly pre selected when creating an invoice depending on the fiscal responsibility of the issuer and receiver of the document and the related journal.
* A CBU account type has been added and also CBU Validation


Technical
---------

This module adds both models and fields that will be eventually used for the electronic invoice module. Here is a summary of the main features:

Master Data:

* Chart of Account: one for each AFIP responsibility that is related to a legal entity:

  * Responsable Inscripto (RI)
  * Exento (EX)
  * Monotributo (Mono)

* Argentinean Taxes and Account Tax Groups (VAT taxes with the existing aliquots and other types)
* AFIP Responsibility Types
* Fiscal Positions (in order to map taxes)
* Legal Documents Types in Argentina
* Identification Types valid in Argentina.
* Country AFIP codes and Country VAT codes for legal entities, natural persons and others
* Currency AFIP codes
* Unit of measures AFIP codes
* Partners: Consumidor Final and AFIP


## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_ar
```

## Dependencies

This addon depends on:
- l10n_latam_invoice_document
- l10n_latam_base

## Manifest Information

- **Name**: Argentina - Accounting
- **Version**: 3.7
- **Category**: Accounting/Localizations/Account Charts
- **License**: LGPL-3
- **Installable**: True

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_ar`.

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
