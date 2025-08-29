# Indonesia E-faktur (Coretax)


        E-invoicing feature provided by DJP (Indonesian Tax Office). As of January 1st 2025,
        Indonesia is using CoreTax system, which changes the file format and content of E-Faktur.
        We're changing from CSV files into XML.
        At the same time, due to tax regulation changes back and forth, for general E-Faktur now,
        TaxBase (DPP) has to be mulitplied by factor of 11/12 while multiplied to tax of 12% which
        is resulting to 11%.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_id_efaktur_coretax
```

## Dependencies

This addon depends on:
- l10n_id
- l10n_id_efaktur

## Manifest Information

- **Name**: Indonesia E-faktur (Coretax)
- **Version**: 1.0
- **Category**: Accounting/Localizations/EDI
- **License**: LGPL-3
- **Installable**: True

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_id_efaktur_coretax`.

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
