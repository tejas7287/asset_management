# Asset Management

**Version:** 1.0  
**Category:** Operations  
**License:** LGPL-3  
**Author:** WebbyCrown Solutions

## Description

Manage company assets, transfers, maintenance, and depreciation.

Streamline your asset lifecycle management with our comprehensive Odoo module. Track assets, automate depreciation, manage maintenance, and handle transfers effortlessly.

## Features

- Odoo 19.0 compatible
- Standalone application
- Manage company assets, transfers, maintenance, and depreciation.

## Dependencies

- `base`
- `product`
- `hr`
- `account`

## Installation

1. Clone this repository into your Odoo addons directory:
   ```bash
   git clone https://github.com/tejas7287/asset_management.git
   ```

2. Add the module path to your Odoo configuration file (`odoo.conf`):
   ```
   addons_path = /path/to/odoo/addons,/path/to/asset_management
   ```

3. Restart the Odoo server:
   ```bash
   sudo systemctl restart odoo
   ```

4. Go to **Apps** → **Update Apps List** → Search for **"Asset Management"** → Click **Install**

## Module Structure

```
asset_management/
├── __init__.py
├── __manifest__.py
├── data/
├── doc/
├── i18n/
├── models/
├── report/
├── security/
├── static/
├── views/
├── wizard/
```

## License

This project is licensed under the LGPL-3 License.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m "Add amazing feature"`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
