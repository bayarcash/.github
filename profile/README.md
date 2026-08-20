# Bayarcash

**Payment gateway & commerce platform for Malaysian businesses.**

Bayarcash helps Malaysian businesses accept payments through FPX, DuitNow Online
Banking/Wallets, DuitNow QR, e-wallets, cards, Buy Now Pay Later, and cross-border
QR — with recurring billing, e-Invoicing (MyInvois), and merchant tools built in.

Operated by Bayarcash Sdn. Bhd. (202201040365).

## Merchant platforms

| Platform | Description |
|---|---|
| [BCL](https://bcl.my) | Create QR terminals, payment forms, and payment links in minutes |
| [Beri Salam](https://berisalam.com) | Donation management — fundraising, reporting, and donor relationship tools |
| [Korban Plus](https://korbanplus.com) | Digital platform for managing korban and aqiqah programs |
| [Submit eInvoice](https://submiteinvoice.com) | LHDN-compliant e-Invoicing for Malaysian businesses |

## API

**v3 is the current API version.** v2 is deprecated and receives no new features.
Build new integrations on v3.

| Environment | API base URL | Console |
|---|---|---|
| Production | `https://api.console.bayar.cash/v3` | [console.bayar.cash](https://console.bayar.cash) |
| Sandbox | `https://api.console.bayarcash-sandbox.com/v3` | [console.bayarcash-sandbox.com](https://console.bayarcash-sandbox.com) |

Authenticate with a Personal Access Token sent as a bearer token. Payment intents
and callbacks can be signed with HMAC-SHA256 using your API Secret Key.

## Official SDKs

Feature-parity SDKs for the Bayarcash Payment Gateway API. All support API v2 and v3.

| Language | Package | Install |
|---|---|---|
| [PHP](https://github.com/bayarcash/php-sdk) | [`bayarcash/php-sdk`](https://packagist.org/packages/bayarcash/php-sdk) | `composer require bayarcash/php-sdk` |
| [Node.js / TypeScript](https://github.com/bayarcash/node-sdk) | [`bayarcash`](https://www.npmjs.com/package/bayarcash) | `npm install bayarcash` |
| [Python](https://github.com/bayarcash/python-sdk) | [`bayarcash`](https://pypi.org/project/bayarcash/) | `pip install bayarcash` |
| [Go](https://github.com/bayarcash/go-sdk) | [`go-sdk`](https://pkg.go.dev/github.com/bayarcash/go-sdk) | `go get github.com/bayarcash/go-sdk` |
| [Ruby](https://github.com/bayarcash/ruby-sdk) | [`bayarcash`](https://rubygems.org/gems/bayarcash) | `gem install bayarcash` |
| [Rust](https://github.com/bayarcash/rust-sdk) | [`bayarcash`](https://crates.io/crates/bayarcash) | `cargo add bayarcash` |
| [Dart / Flutter](https://github.com/bayarcash/dart-sdk) | [`bayarcash`](https://pub.dev/packages/bayarcash) | `dart pub add bayarcash` |
| [C# / .NET](https://github.com/bayarcash/dotnet-sdk) | [`Bayarcash`](https://www.nuget.org/packages/Bayarcash) | `dotnet add package Bayarcash` |

## Framework integrations

| Framework | Package | Install |
|---|---|---|
| [Laravel](https://github.com/bayarcash/laravel) | [`bayarcash/laravel`](https://packagist.org/packages/bayarcash/laravel) | `composer require bayarcash/laravel` |
| [Django](https://github.com/bayarcash/django) | [`django-bayarcash`](https://pypi.org/project/django-bayarcash/) | `pip install django-bayarcash` |

## Plugins & integrations

No-code integrations for popular platforms. Browse and download every plugin at
[plugin.bayarcash.com](https://plugin.bayarcash.com).

| Category | Platforms |
|---|---|
| WordPress | WooCommerce · GiveWP · Gravity Forms · Fluent Forms · FluentCart · Easy Digital Downloads · Paymattic |
| E-commerce | OpenCart · PrestaShop |
| Billing & hosting | WHMCS · HostBill |
| e-Invoicing | E-Invoice for MyInvois LHDN |
| Payment links | BCL Payment Link for WooCommerce |
| Workflow automation | [n8n — Bayarcash](https://github.com/bayarcash/n8n-nodes-bayarcash) · [n8n — BCL](https://github.com/bayarcash/n8n-nodes-bcl) |

WordPress plugins are published on WordPress.org under
[@bayarcash](https://profiles.wordpress.org/bayarcash/).

## Developer resources

| Resource | Description |
|---|---|
| [API reference](https://api.webimpian.support/bayarcash) | REST API endpoint reference |
| [Platform docs](https://docs.bayarcash.com) | Platform documentation and integration guides |
| [Plugins](https://plugin.bayarcash.com) | Official plugins for WordPress, WooCommerce, and more |
| [Live demos](https://bayarcash-demo.com) | Working demo stores across supported platforms |
| [php-demo](https://github.com/bayarcash/php-demo) | Reference integration in vanilla PHP |

## Official channels

| Channel | Address |
|---|---|
| Website | [bayarcash.com](https://bayarcash.com) |
| Telegram — latest updates | [telegram.bayarcash.com](https://telegram.bayarcash.com) |
| WhatsApp — support | [whatsapp.bayarcash.com](https://whatsapp.bayarcash.com) |
| Support email | [support@bayarcash.com](mailto:support@bayarcash.com) |
| Facebook | [facebook.com/mybayarcash](https://facebook.com/mybayarcash) |

> For your security, contact Bayarcash only through the official channels listed
> above. Bayarcash staff will never ask for your password or OTP.
