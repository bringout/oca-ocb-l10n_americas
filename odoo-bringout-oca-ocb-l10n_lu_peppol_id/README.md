# Luxembourg - Peppol Identifier


    Some Luxembourg public institutions do not have a VAT number but have been assigned an arbitrary number 
    (see: https://pch.gouvernement.lu/fr/peppol.html). Thus, this module adds the Peppol Identifier field on 
    the account.move form view. If this field is set, it is then read when exporting electronic invoicing formats.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_lu_peppol_id
```

## Dependencies

This addon depends on:
- l10n_lu
- account_edi_ubl_cii

## Manifest Information

- **Name**: Luxembourg - Peppol Identifier
- **Version**: 1.0
- **Category**: N/A
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_lu_peppol_id`.

## License

This package maintains the original LGPL-3 license from the upstream Odoo project.

## Documentation

- Overview: doc/OVERVIEW.md
- Architecture: doc/ARCHITECTURE.md
- Models: doc/MODELS.md
- Controllers: doc/CONTROLLERS.md
- Wizards: doc/WIZARDS.md
- Reports: doc/REPORTS.md
- Security: doc/SECURITY.md
- Install: doc/INSTALL.md
- Usage: doc/USAGE.md
- Configuration: doc/CONFIGURATION.md
- Dependencies: doc/DEPENDENCIES.md
- Troubleshooting: doc/TROUBLESHOOTING.md
- FAQ: doc/FAQ.md
