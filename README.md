# PayNow OpenAPI Specifications

OpenAPI specifications for PayNow's merchant of record platform.

## Available APIs

### Storefront API
Customer-facing endpoints for building custom storefronts and enabling purchases.
- **YAML**: [`openapi/yaml/storefront-api.yaml`](openapi/yaml/storefront-api.yaml)
- **JSON**: [`openapi/json/storefront-api.json`](openapi/json/storefront-api.json)

### Management API
Administrative endpoints for managing your store, products, subscriptions, and customers.
- **YAML**: [`openapi/yaml/management-api.yaml`](openapi/yaml/management-api.yaml)
- **JSON**: [`openapi/json/management-api.json`](openapi/json/management-api.json)

### Gameserver API
Specialized endpoints for game server integration and in-game purchases.
- **YAML**: [`openapi/yaml/gameserver-api.yaml`](openapi/yaml/gameserver-api.yaml)
- **JSON**: [`openapi/json/gameserver-api.json`](openapi/json/gameserver-api.json)

## Getting Started

### Authentication

**Management API**: Create an API key in your [PayNow Dashboard](https://dashboard.paynow.gg/api-keys)

**Storefront API**: Generate customer tokens via the Management API

**Gameserver API**: Configure server tokens through your game server integration settings

## Resources

- **Official Documentation**: [docs.paynow.gg](https://docs.paynow.gg/)
- **Dashboard**: [dashboard.paynow.gg](https://dashboard.paynow.gg/)
- **Discord Community / Support**: [discord.gg/paynow](https://discord.gg/paynow)

## PayNow Overview

PayNow handles the complexities of global payments so you can focus on your business:

- **75+ Payment Methods**: Credit cards, PayPal, crypto, and regional payment options
- **Global Tax Compliance**: Automated tax calculation and remittance worldwide
- **Chargeback Protection**: Full coverage with no fees
- **Subscription Management**: Automated billing cycles and customer lifecycle management
- **Multi-Currency Support**: Accept payments in USD, EUR, GBP, and more
- **Headless Commerce**: Build custom checkout experiences with our flexible APIs

## Contributing

Found an issue with the specifications? Please open an issue in this repository or reach out on our Discord server. Note that the OpenAPI specs themselves are generated from our internal API definitions, so content changes should be addressed through our support channels.

## License

These OpenAPI specifications are provided for integration purposes. The APIs themselves are subject to PayNow's Terms of Service and API usage policies. OpenAPI specification files are licensed under the MIT license.
