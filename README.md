markdown
# Price Analytics MCP Server

Welcome to the Price Analytics MCP Server! This server provides a unified and efficient way to access price and product data from multiple online marketplaces. By using this platform, you can effortlessly gather detailed product information including titles, manufacturers, reviews, retail prices, and more from various sources like Amazon, Google Shopping, eBay, Idealo, and billiger.

## Features

- **Unified API Access**: Retrieve price and product data from multiple marketplaces through a single API.
- **Comprehensive Product Information**: Access detailed information such as product titles, manufacturers, reviews, and size selections.
- **Marketplaces Supported**: Data available from Amazon, Google Shopping, eBay, Idealo, and billiger.
- **Country-Specific Data**: Retrieve data specific to various countries, ensuring localized results.
- **Flexible Search Options**: Search using a variety of identifiers like GTIN, ASIN, id, term, or PZN.

## How It Works

### Workflow

1. **Create a Job**: Initiate a product data search by creating a job with specific parameters such as the source marketplace, country, and search identifier.
2. **Poll for Results**: Once a job is created, periodically poll the job to check the status and retrieve results once they are available.

### Tools

The Price Analytics MCP Server offers a set of tools to facilitate your data retrieval process:

- **Start Search by Term**: Initiate a product search using a general search term like "iPhone 13".
- **Start Search by ID**: Search using marketplace-specific product IDs, such as Amazon's ASIN.
- **Start Search by GTIN**: Utilize the Global Trade Item Number for product searches.
- **Start Search by PZN**: Search using Pharmazentralnummer, ideal for specific marketplaces.
- **Poll Session Results**: Retrieve the products and offers data from a created session using the job ID.

## Error Handling

The server provides clear error messages for various scenarios, such as missing parameters, unsupported sources or countries, unauthorized access, and more, ensuring you have a seamless experience.

## Contact and Customization

For any special requirements, including higher request volumes, custom integrations, or additional features, feel free to reach out for customized pricing and plans tailored to your needs.

---

Thank you for choosing the Price Analytics MCP Server for your product and price data needs. We are committed to providing reliable and comprehensive data solutions for your business.