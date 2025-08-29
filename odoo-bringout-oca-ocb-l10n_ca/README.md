# Canada - Accounting


This is the module to manage the Canadian accounting chart in Odoo.
===========================================================================================

Canadian accounting charts and localizations.

Fiscal positions
----------------

When considering taxes to be applied, it is the province where the delivery occurs that matters.
Therefore we decided to implement the most common case in the fiscal positions: delivery is the
responsibility of the vendor and done at the customer location.

Some examples:

1) You have a customer from another province and you deliver to his location.
On the customer, set the fiscal position to his province.

2) You have a customer from another province. However this customer comes to your location
with their truck to pick up products. On the customer, do not set any fiscal position.

3) An international vendor doesn't charge you any tax. Taxes are charged at customs
by the customs broker. On the vendor, set the fiscal position to International.

4) An international vendor charge you your provincial tax. They are registered with your
position.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_ca
```

## Dependencies

This addon depends on:
- account
- base_iban
- l10n_multilang

## Manifest Information

- **Name**: Canada - Accounting
- **Version**: 1.1
- **Category**: Accounting/Localizations/Account Charts
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_ca`.

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
