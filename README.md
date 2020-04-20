# DigitalStartup_PortoCrumbs
Module attempts to fix Porto Breadcrumbs on Magento 2.2.x with Porto 3.2.3

1. Upload via FTP to `app/code/`
2. Enable Module: `bin/magento enable:module DigitalStartup_PortoCrumbs`
3. Compile if in Production: `bin/magento setup:di:compile`
4. Clear Static Content: `bin/magento setup:static-content:deploy en_US en_GB -f` (replace locale if necessary)
5. Clear Cache: `bin/magento cache:clean`
