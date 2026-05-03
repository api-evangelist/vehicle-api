# Vehicle API (vehicle-api)
The Vehicle API by Edmunds provides comprehensive access to automotive datasets covering vehicle makes, models, trims, specs, media, pricing (TMV), incentives, dealer information, and reviews. Enables developers to build automotive shopping tools, vehicle configurators, and consumer research applications.

**URL:** [https://developer.edmunds.com/api-documentation/vehicle/](https://developer.edmunds.com/api-documentation/vehicle/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automotive, Cars, Edmunds, Pricing, Vehicles

## Timestamps

- **Created:** 2025-01-07
- **Modified:** 2026-05-03

## APIs

### Vehicle API (Edmunds)
The Edmunds Vehicle API provides access to a comprehensive automotive data platform including vehicle makes, models, trims, configurations, specifications, media (photos and videos), True Market Value (TMV) pricing, dealer inventories, incentives, reviews, and consumer ratings. Ideal for building automotive shopping tools, vehicle comparison engines, and dealer management systems.

**Human URL:** [https://developer.edmunds.com/api-documentation/vehicle/](https://developer.edmunds.com/api-documentation/vehicle/)

#### Tags:

 - Automotive, Cars, Edmunds, Pricing, Vehicles

#### Properties

- [Documentation](https://developer.edmunds.com/api-documentation/vehicle/)
- [Portal](https://developer.edmunds.com/)
- [Reference](https://developer.edmunds.com/api-documentation/vehicle/)
- [Authentication](https://developer.edmunds.com/api-documentation/overview/)
- [OpenAPI](openapi/vehicle-api-openapi.yml)
- [JSONSchema - Vehicle Make Schema](json-schema/vehicle-api-make-schema.json)
- [JSONSchema - Vehicle Model Schema](json-schema/vehicle-api-model-schema.json)
- [JSONSchema - Vehicle Style Schema](json-schema/vehicle-api-style-schema.json)
- [JSONSchema - Vehicle Price Schema](json-schema/vehicle-api-style-price-schema.json)
- [JSONStructure - Vehicle Make Structure](json-structure/vehicle-api-make-structure.json)
- [JSONStructure - Vehicle Model Structure](json-structure/vehicle-api-model-structure.json)
- [Example - Vehicle Make Example](examples/vehicle-api-make-example.json)
- [Example - Vehicle Style Example](examples/vehicle-api-style-example.json)

## Common Properties

- [Website](https://developer.edmunds.com/)
- [Portal](https://developer.edmunds.com/)
- [Documentation](https://developer.edmunds.com/api-documentation/vehicle/)
- [Authentication](https://developer.edmunds.com/api-documentation/overview/)
- [GettingStarted](https://developer.edmunds.com/api-documentation/overview/)
- [Support](https://developer.edmunds.com/support/)
- [SpectralRules - Vehicle API Spectral Rules](rules/vehicle-api-spectral-rules.yml)
- [Vocabulary - Vehicle API Vocabulary](vocabulary/vehicle-api-vocabulary.yml)
- [NaftikoCapability - Vehicle Data](capabilities/vehicle-data.yaml)

## Features

| Name | Description |
|------|-------------|
| Vehicle Make and Model Data | Comprehensive database of vehicle makes, models, and trim levels with OEM specifications, features, and configuration options. |
| True Market Value Pricing | Edmunds TMV pricing data including new vehicle suggested retail, invoice prices, and used vehicle values by condition and mileage. |
| Vehicle Media | Photo and video assets for vehicle makes, models, and trims including exterior, interior, color swatch, and 360-degree images. |
| Dealer Inventory | Real-time dealer inventory search with make, model, year, zip code, radius, and price range filtering. |
| Incentives and Rebates | Manufacturer incentives, rebates, financing offers, and lease programs by vehicle, region, and customer type. |
| Vehicle Reviews and Ratings | Edmunds editorial reviews and consumer ratings for vehicle models including performance, comfort, value, and reliability scores. |

## Use Cases

| Name | Description |
|------|-------------|
| Automotive Shopping Tools | Build vehicle search and comparison tools that let consumers filter by make, model, year, price, and features with TMV pricing guidance. |
| Dealer Management Systems | Power dealer websites and CRM systems with accurate vehicle specs, pricing, and inventory data synced from Edmunds. |
| Vehicle Configurator | Enable consumers to build and price vehicles with available trims, packages, options, and colors with live pricing calculations. |
| Used Car Valuation | Integrate used vehicle pricing into trade-in calculators, appraisal tools, and consumer value estimators using TMV data. |

## Integrations

| Name | Description |
|------|-------------|
| AutoTrader | Cross-reference vehicle listings with AutoTrader inventory using Edmunds vehicle identifiers and specs for consistent data. |
| Cars.com | Combine Edmunds vehicle data with Cars.com listings for enriched consumer shopping experiences. |
| Dealer CRM Systems | Integrate vehicle specs and pricing into Salesforce, CDK, and Reynolds and Reynolds dealer management systems. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Vehicle API (Edmunds)](openapi/vehicle-api-openapi.yml)

### JSON Schema

- [vehicle-api-inventory-item-schema.json](json-schema/vehicle-api-inventory-item-schema.json)
- [vehicle-api-make-schema.json](json-schema/vehicle-api-make-schema.json)
- [vehicle-api-model-schema.json](json-schema/vehicle-api-model-schema.json)
- [vehicle-api-model-year-schema.json](json-schema/vehicle-api-model-year-schema.json)
- [vehicle-api-photo-schema.json](json-schema/vehicle-api-photo-schema.json)
- [vehicle-api-price-response-schema.json](json-schema/vehicle-api-price-response-schema.json)
- [vehicle-api-style-price-schema.json](json-schema/vehicle-api-style-price-schema.json)
- [vehicle-api-style-schema.json](json-schema/vehicle-api-style-schema.json)

### JSON Structure

- [vehicle-api-inventory-item-structure.json](json-structure/vehicle-api-inventory-item-structure.json)
- [vehicle-api-make-structure.json](json-structure/vehicle-api-make-structure.json)
- [vehicle-api-model-structure.json](json-structure/vehicle-api-model-structure.json)
- [vehicle-api-model-year-structure.json](json-structure/vehicle-api-model-year-structure.json)
- [vehicle-api-photo-structure.json](json-structure/vehicle-api-photo-structure.json)
- [vehicle-api-price-response-structure.json](json-structure/vehicle-api-price-response-structure.json)
- [vehicle-api-style-price-structure.json](json-structure/vehicle-api-style-price-structure.json)
- [vehicle-api-style-structure.json](json-structure/vehicle-api-style-structure.json)

### Examples

- [vehicle-api-inventory-item-example.json](examples/vehicle-api-inventory-item-example.json)
- [vehicle-api-make-example.json](examples/vehicle-api-make-example.json)
- [vehicle-api-model-example.json](examples/vehicle-api-model-example.json)
- [vehicle-api-model-year-example.json](examples/vehicle-api-model-year-example.json)
- [vehicle-api-photo-example.json](examples/vehicle-api-photo-example.json)
- [vehicle-api-price-response-example.json](examples/vehicle-api-price-response-example.json)
- [vehicle-api-style-price-example.json](examples/vehicle-api-style-price-example.json)
- [vehicle-api-style-example.json](examples/vehicle-api-style-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Vehicle API (Edmunds)](capabilities/shared/vehicle-api.yaml) — 7 operations for makes, models, styles, pricing, photos, and inventory

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Vehicle Data](capabilities/vehicle-data.yaml) | vehicle-api | 7 | Car Shopper, Dealer Platform Developer, Automotive App Developer |

## Vocabulary

- [Vehicle API Vocabulary](vocabulary/vehicle-api-vocabulary.yml) — Unified taxonomy mapping 7 resources, 3 actions, 1 workflow, and 3 personas across automotive catalog, pricing, media, and inventory dimensions

## Rules

- [Vehicle API Spectral Rules](rules/vehicle-api-spectral-rules.yml) — 24 rules across 10 categories enforcing Vehicle API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
