[ ![Image](https://aplazame.com/static/img/banners/banner-728-white-magento.png "Aplazame") ](https://aplazame.com "Aplazame")

[![Package version](https://img.shields.io/packagist/v/aplazame/magento.svg)](https://packagist.org/packages/aplazame/magento) [![Build Status](http://drone.aplazame.com/api/badges/aplazame/magento/status.svg)](http://drone.aplazame.com/aplazame/magento) [![Dependencies](https://www.versioneye.com/php/aplazame:magento/badge.svg)](https://www.versioneye.com/php/aplazame:magento)

**Compatible with**

Magento CE 1.4.0.1+

### Configure

![config](docs/config.png)

* **Sandbox**: Determines if the module is on Sandbox mode.
* **Host**: Aplazame host `https://aplazame.com`
* **API Version**: The latest version is `v1.2`
* **Button**: The CSS Selector for Aplazame payment method. The default selector is `dt:has(input#p_method_aplazame)`. [See bellow](#one-step-checkout-button) to configure button with One Step Checkout modules.
* **Button Image**: [Select the image](http://docs.aplazame.com/#buttons) that appear as payment method on you cart. The default image is `white-148x46`.
* **Position**: The position in the payment method list, by default is `1`, on the top.
* **Secret API Key**: The Secret Key provided by Aplazame. You cannot share this key with anyone!!
* **Public API Key**: The Public Key provided by Aplazame.

> Be sure that on all fields you don't keep any whitespace. Otherwise the module can generate unexpected results.

#### One Step Checkout button

* [GoMage LightCheckout](http://www.magentocommerce.com/magento-connect/gomage-lightcheckout-v-5-9.html): `#pm-aplazame`

> It's important to use simple quotation marks for button CSS Selector.


#### Developers

**To install using [modgit](https://github.com/jreinke/modgit)**

```
modgit init
modgit -i extension/:. add Magento_Aplazame https://github.com/aplazame/magento
```

> to update:

```
modgit update Magento_Aplazame
```

**To install using [modman](https://github.com/colinmollenhour/modman)**

```
modman clone https://github.com/aplazame/magento
```

> to update:

```
modman update Magento_Aplazame
```


#### Live demo

This is the online demo for uses to test Aplazame and its features.

[http://magento.aplazame.com](http://magento.aplazame.com)


#### Install Magento

It is easy to deploy Magento with [Ansible](http://www.ansible.com/home)!

[https://github.com/aplazame/ansible-magento](https://github.com/aplazame/ansible-magento)


#### Release history

For new features check [this](HISTORY.md).


#### Help

**Have a question about Aplazame?**

For any support request please drop us an email at [soporte.magento@aplazame.com](mailto:soporte.magento@aplazame.com?subject=Help me with the module).
