# Het Fulfilment Bedrijf WooCommerce Sync

Connects your WooCommerce store to the Het Fulfilment Bedrijf platform: orders and products sync
out automatically, and stock/tracking updates flow back in.

## Requirements

- WordPress 6.0+
- WooCommerce (latest recommended)
- PHP 7.4+
- A Het Fulfilment Bedrijf account with your webhook token

## Installation

1. Click to download the latest version: [Download hetfulfilmentbedrijf-woocommerce.zip](https://github.com/youwinn/woocommerce_hetfulfilmentbedrijf_public/releases/latest/download/hetfulfilmentbedrijf-woocommerce.zip)
2. In your WordPress admin, go to **Plugins → Add New → Upload Plugin**.
3. Choose the downloaded ZIP file and click **Install Now**.
4. Click **Activate**.

## Setup

1. Go to **WooCommerce → Het Fulfilment Bedrijf**.
2. Paste in the token provided by Het Fulfilment Bedrijf.
3. Enable **Order Sync** and select which order statuses should trigger a sync.
4. Enable **Product Sync** and select which product statuses should trigger a sync.
5. Save changes.

That's it — new orders and product changes matching your selected statuses are sent automatically.
Use **Sync all orders now** / **Sync all products now** to push your existing catalog and order
history on first setup.

## Staying up to date

The plugin checks this repository for new releases and shows an **Update available** notice on
the Plugins page in wp-admin, the same way WordPress.org-hosted plugins do. Click **Update Now**
to install the latest version — no manual download required after the first install.

## Support

Contact Het Fulfilment Bedrijf support for help with your token, webhook configuration, or sync
questions.
