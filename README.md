This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Magento file to i18N for thailand

In the project directory, you can run:

### download file and move file to  root magento/app/design/frontend/Vendor/module/i18n/

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `run php bin/magento setup:static-content:deploy -f` -f for default mode or developer mode
### `php bin/magento c:c`
### `php bin/magento c:f`

And refresh Page But not work follow this line.

### `php bin/magento setup:upgrade`
### `php bin/magento setup:di:compile`
### `php bin/magento setup:static-content:deploy -f` -f for default mode or developer mode
### `php bin/magento c:c`
### `php bin/magento c:f`

hope this way help everyone.
