# Advance Auto Parts (advance-auto-parts)
Advance Auto Parts is a leading automotive aftermarket parts retailer offering a comprehensive catalog of automotive parts, accessories, batteries, and maintenance items. The company serves both professional automotive technicians and do-it-yourself customers across North America through retail stores, online, and commercial delivery programs.

**URL:** [Visit Advance Auto Parts](https://www.advanceautoparts.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automotive, E-Commerce, Parts Catalog, Retail, Supply Chain

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Advance Auto Parts Catalog API
The Advance Auto Parts Catalog API provides programmatic access to the full product catalog including parts, accessories, batteries, and fluids. Supports vehicle fitment lookups by year/make/model/engine, part number searches, availability checks, pricing, and store inventory queries for professional and DIY customers.

**Human URL:** [https://www.advanceautoparts.com](https://www.advanceautoparts.com)

#### Tags:

 - Automotive, Parts Catalog, Inventory, Vehicle Fitment

#### Properties

- [Documentation](https://www.advanceautoparts.com/i/policies/terms-and-conditions)
- [OpenAPI](openapi/advance-auto-parts-catalog-api-openapi.yml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSONLD](json-ld/advance-auto-parts-catalog-api-context.jsonld)
- [SpectralRules](rules/advance-auto-parts-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/catalog-api.yaml)
- [Vocabulary](vocabulary/advance-auto-parts-vocabulary.yaml)

### Advance Auto Parts Commerce API
The Advance Auto Parts Commerce API enables ordering, cart management, loyalty program integration, and order fulfillment for commercial accounts. Supports creating orders, managing Speed Perks loyalty points, tracking shipments, and accessing purchase history for fleet and professional installer accounts.

**Human URL:** [https://www.advanceautoparts.com/i/help/commercial-accounts](https://www.advanceautoparts.com/i/help/commercial-accounts)

#### Tags:

 - Automotive, E-Commerce, Loyalty, Order Management

#### Properties

- [Documentation](https://www.advanceautoparts.com/i/help/commercial-accounts)
- [OpenAPI](openapi/advance-auto-parts-commerce-api-openapi.yml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSONLD](json-ld/advance-auto-parts-commerce-api-context.jsonld)
- [SpectralRules](rules/advance-auto-parts-spectral-rules.yml)
- [NaftikoCapability](capabilities/auto-parts-shopping.yaml)
- [Vocabulary](vocabulary/advance-auto-parts-vocabulary.yaml)

## Common Properties

- [Website](https://www.advanceautoparts.com)
- [Portal](https://www.advanceautoparts.com/i/help)
- [Support](https://www.advanceautoparts.com/i/help/customer-service)
- [Blog](https://www.advanceautoparts.com/gearhead)
- [TermsOfService](https://www.advanceautoparts.com/i/policies/terms-and-conditions)
- [PrivacyPolicy](https://www.advanceautoparts.com/i/policies/privacy)
- [Login](https://www.advanceautoparts.com/myaccount/login)
- [SignUp](https://www.advanceautoparts.com/myaccount/register)

## Features

| Name | Description |
|------|-------------|
| Vehicle Fitment Search | Look up compatible parts by year, make, model, engine, and trim for accurate fitment verification. |
| Real-Time Inventory | Check part availability and quantity at nearby stores and distribution centers in real time. |
| Parts Catalog Access | Access a comprehensive catalog of millions of SKUs including OEM and aftermarket parts, accessories, and fluids. |
| Commercial Account Management | Manage commercial accounts, purchase orders, net terms, and invoice history for professional installers. |
| Speed Perks Loyalty Integration | Query and apply Speed Perks loyalty points for purchases and track reward status. |
| Same-Day Delivery and Store Pickup | Order parts for same-day delivery or in-store pickup with real-time availability confirmation. |
| Price and Promo Queries | Retrieve current pricing, promotional discounts, and sale prices for catalog items. |
| Order Tracking | Track shipment status and estimated delivery for online and commercial orders. |

## Use Cases

| Name | Description |
|------|-------------|
| Shop Management Software Integration | Integrate parts ordering directly into auto repair shop management software for seamless procurement. |
| Fleet Maintenance Automation | Automate parts procurement for fleet vehicles based on maintenance schedules and repair orders. |
| Mobile Parts Lookup App | Build mobile applications that allow technicians to look up and order parts from their smartphones. |
| Vehicle Repair Platforms | Embed parts catalog and ordering in vehicle repair estimation and diagnostic platforms. |
| Loyalty Program Portals | Build custom loyalty dashboards showing Speed Perks points, rewards, and purchase history. |
| Inventory Management Systems | Sync Advance Auto Parts catalog data with shop or warehouse inventory management systems. |

## Integrations

| Name | Description |
|------|-------------|
| Mitchell 1 ProDemand | Integration with Mitchell 1 shop management and repair information software for parts ordering. |
| ALLDATA | Integration with ALLDATA repair information and shop management platform for professional technicians. |
| Amazon | Parts available through Amazon marketplace for broader consumer reach. |
| AutoZone MOTOR Data | ACES/PIES automotive data standard compatibility for parts catalog interchange. |
| DealerSocket | Dealer management system integration for automotive dealership parts departments. |
| Shopify | Storefront integration for resellers using Shopify to list Advance Auto Parts products. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Advance Auto Parts Catalog API](openapi/advance-auto-parts-catalog-api-openapi.yml)
- [Advance Auto Parts Commerce API](openapi/advance-auto-parts-commerce-api-openapi.yml)

### JSON Schema

- 21 schema files in [json-schema/](json-schema/)

### JSON Structure

- 21 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Catalog API Context](json-ld/advance-auto-parts-catalog-api-context.jsonld)
- [Commerce API Context](json-ld/advance-auto-parts-commerce-api-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Catalog API](capabilities/shared/catalog-api.yaml) — 7 operations for vehicle fitment lookup, parts search, inventory, and store location

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Auto Parts Shopping](capabilities/auto-parts-shopping.yaml) | Catalog API, Commerce API | 7 | Automotive Technicians, Fleet Managers, DIY Customers |

## Vocabulary

- [Advance Auto Parts Vocabulary](vocabulary/advance-auto-parts-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 6 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Advance Auto Parts Spectral Rules](rules/advance-auto-parts-spectral-rules.yml) — 31 rules across 12 categories enforcing Advance Auto Parts API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
