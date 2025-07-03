# AuxVault API Documentation

This repository contains the official API documentation for AuxVault, a comprehensive financial transaction platform. The documentation is built using [Mintlify](https://mintlify.com/).

## Documentation Structure

### API Reference

- **Introduction**: Overview of the API, authentication, and general information
- **Transaction Endpoints**:
  - Transaction API (card and ACH payments)
  - Void Transaction API
  - Refund API
  - Recurring Transaction API
  - Token Transaction API
  - Transaction Retrieval API
- **Customer Management**:
  - Customer API

## Local Development

To preview the documentation locally, install the Mintlify CLI:

```bash
npm i -g mintlify
```

Then run the development server:

```bash
mintlify dev
```

## Customization

The documentation uses the following customization files:

- `docs.json`: Configuration for navigation, colors, and branding
- `/images/`: Directory containing logo files and other images

## Deployment

Changes pushed to the main branch will automatically deploy to the documentation site through Mintlify's GitHub integration.

## Contributing

When contributing to the documentation, please follow these guidelines:

1. Ensure all API examples are accurate and tested
2. Maintain consistent formatting across all documentation pages
3. Include detailed request/response examples for all endpoints
4. Document all possible error codes and their meanings
