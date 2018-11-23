# Shopify Digital Checkout
Fixes the Shopify Checkout for digital products
This handy little script will hide the Address 1, City and Zip fields for a quicker checkout, aimed for digital products.

## Installation Guide:

1. Go to **"Online Store**" -> **"Preferences**" and scroll down the **Google Analytics** area.
* You must have previously added your Google Analytics code, if not, follow this guide:
> https://help.shopify.com/en/manual/reports-and-analytics/google-analytics/google-analytics-setup

2. Paste the installation code in the **"Additional Google Analytics JavaScript"** text box.

```
if (window.location.href.indexOf('checkout') > -1) {
  var script = document.createElement('script');
  script.src = 'https://public.store-genius.com/digital-checkout.js';
  document.head.appendChild(script);
}
```

3.- Go to **"Settings**" -> **"Checkout**" and scroll down the **"Form options area**".
There, you should leave the options like this image: 
![Form options](https://public.store-genius.com/digital-form-options.png "Form options")

4.- On the **"same page**", scroll down to the **"Order processing**" area.
There, you should leave the options like this image:
![Order processing](https://public.store-genius.com/digital-order-processing.png "Order processing")

That's it.
If you liked it, you can buy Bruno a coffee.
https://buymeacoff.ee/brunocalderon

**Happy Shopifying!**

- Springs Digital
https://springsdigital.com
*Code is poetry*
