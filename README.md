
![magento-hyva-webwinkelkeur](https://github.com/magmodules/magento2-webwinkelkeur-hyva/assets/24823946/f563de84-091c-47d5-b02f-3bc5a00de23a)


# WebwinkelKeur Hyvä Compatibility plugin


The Webwinkelkeur plugin for Magento is a powerful integration that seamlessly connects the widely-used review platform, Webwinkelkeur, with Magento. This plugin provides extensive functionality to enhance your online store's reputation management and streamline the customer feedback process. With its compatibility with the Hyva theme, the plugin ensures a smooth and seamless user experience while incorporating the robust features of the Webwinkelkeur platform.

The WebwinkelKeur Compatibility plugin for the Magento Hyva theme has the following requirements:
- [Magento 2.4.+](https://github.com/magento/magento2)
- [Hyvä](https://github.com/hyva-themes)
- [Magmodules WebwinkelKeur Reviews](https://www.magmodules.eu/magento2-webwinkelkeur-reviews.html)    

<img width="1052" alt="hyva-webwinkelkeur" src="https://github.com/magmodules/magento2-webwinkelkeur-hyva/assets/24823946/7da6e6c3-526b-4061-8be2-39272d484b2b">


## About the WebwinkelKeur Plugin

The Webwinkelkeur plugin for Magento is a robust integration that seamlessly connects your Magento store with the popular review platform, Webwinkelkeur. This plugin offers a wide range of powerful features to enhance your online store's reputation management and streamline the customer feedback process.

With the Webwinkelkeur plugin, you can effortlessly integrate the Webwinkelkeur review platform into your Magento store while ensuring compatibility with the Hyva theme. This allows you to maintain a consistent and visually appealing user experience throughout your website.

The plugin empowers you to effectively manage your online store's reputation by collecting and showcasing customer reviews, ratings, and testimonials. By leveraging the power of social proof, you can build trust with potential customers and enhance your brand's reputation.

The Webwinkelkeur plugin provides essential tools for review management, allowing you to moderate and manage reviews within your Magento admin panel. You have full control over which reviews are displayed on your website, ensuring that only relevant and valuable feedback is visible to your customers.

Additionally, the Webwinkelkeur plugin offers advanced features such as automatic review requests, email notifications, customizable review widgets, and rich snippet integration for improved search engine optimization (SEO). These features enable you to actively engage with your customers, gather valuable feedback, and enhance the overall shopping experience on your Magento store.

In conclusion, the Webwinkelkeur plugin for Magento, with its compatibility with the Hyva theme, provides a powerful solution for seamlessly integrating the Webwinkelkeur review platform into your online store. It empowers you to effectively manage your store's reputation, collect customer feedback, and build trust with your audience.

## Installation

1. Install the module using composer: 

```bash
composer require magmodules/magento2-hyva-webwinkelkeur
```

2. Enable the module:

```bash
bin/magento module:enable Magmodules_HyvaWebwinkelKeurSR
```

3. Upgrade the database:

```bash
bin/magento setup:upgrade
```

4. Let Hyvä know about the new module:

```bash
php bin/magento hyva:config:generate
```

5. Generate the CSS files:

```bash
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run ci
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind/ run build-prod
```

Or from your theme:

```bash
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run ci
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run build-prod
```

## WebwinkelKeur Magento plugin features

- Seamless integration
- Review collection automation
- Customizable review widgets
- Rich snippet integration
- Hyvä Compatibility
- Host it all on your platform

## Magento Support

If you have any questions, please fill out our secure contact form by clicking [here](https://www.magmodules.eu/support-form.html).

## Magmodules & Hyva

Magmodules and Hyva have established a strong partnership, working closely together to provide enhanced e-commerce solutions. As an official Hyva partner, we specializes in developing integrations for various platforms and services. 

We have created integrations for well-known providers such as Mollie, Sooqr, Paazl, and many more. This collaboration ensures seamless compatibility and optimized performance for online stores utilizing the Hyva theme. Through our partnership, Magmodules and Hyva strive to deliver comprehensive and tailored solutions to meet the diverse needs of e-commerce businesses.






## Checkout our other Hyva Plugins!

[- Magento 2 Hyvä Shopreview](#) 
 
[- Magento 2 Hyvä Product Review Reminder](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Checkout](#) 

[- Magento 2 Hyvä Mollie React Checkout](#) 

[- Magento 2 Hyvä Paazl](#) 
