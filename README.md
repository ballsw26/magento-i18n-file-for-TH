## Magento file to i18N for thailand

*** Important *** <br />
1.Go to Stores Config > GENERAL > General And go Locale Options Tab<br />
2.Change Locale With your Scope For i18n<br />
Example<br />
-Scope Default Config set Locale = English ( US ) i18n = en_US.csv<br />
-Scope TH Config set Locale or anything your use = Thailand i18n = th_TH.csv<br />
But your don't know code file for i18n run php bin/magento info:language:list and find code for csv<br />
when your choose locale finish run php bin/magento setup:static-content:deploy en_EN th_TH .... anything your want<br />
Hope help for your.<br />

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
