# Privacy Policy — Simply Schema

**Last updated:** February 11, 2026

## Overview

Simply Schema ("we," "our," or "the app") is a Shopify app developed by Licitra Design LLC that manages structured data (schema.org markup) for Shopify stores. This privacy policy describes what information the app accesses, how it's used, and how it's protected.

## Information We Access

Simply Schema requests the following Shopify API permissions:

- **read_content** — To scan your store's pages and blog articles for existing structured data
- **read_products** — To audit product data for Product Schema Readiness (checking whether products have the fields Google requires for rich results)
- **read_themes** — To detect theme-generated schema markup on your storefront

These are all **read-only** permissions. Simply Schema cannot modify your products, content, theme files, orders, or any other store data through the Shopify API.

## Information We Store

Simply Schema stores the following data in its own database:

- **Store URL and name** — To identify your store within the app
- **Scan results** — Page URLs scanned, schema types found, source classifications, and conflict reports
- **Organization settings you enter** — Business type, logo URL, social media links, phone number, and contact type. This information is also saved to your store's metafields for use in schema output.
- **Onboarding state** — Whether you've completed setup steps like enabling the app embed and running your first scan

## Information We Do NOT Collect

- Customer names, emails, or personal information
- Order data or financial information
- Payment details or billing information
- Analytics or tracking data about your store's visitors
- Browsing behavior or usage analytics beyond basic app functionality

## How Your Data Is Used

Your data is used exclusively to provide the app's functionality:

- Scan results are used to detect schema conflicts and display findings in your dashboard
- Organization settings are used to generate structured data markup on your storefront
- Product data (titles, descriptions, prices, SKUs, barcodes) is read during the Product Readiness check to determine if your products meet Google's requirements — this data is not stored beyond the readiness report

## Data Sharing

We do not sell, rent, or share your data with third parties. Your store data stays between you, the app, and Shopify's platform.

The only external network requests the app makes are:

- **To your own storefront** — to fetch page HTML during scans (the same pages your customers see)
- **To Shopify's API** — to read product, content, and theme data using your authorized permissions

## Data Retention

- Scan results are retained as long as the app is installed. Previous scan data is overwritten when you run a new scan.
- Organization settings persist as Shopify metafields on your store and within the app's database.
- When you uninstall Simply Schema, the app's database records for your store are deleted. Metafields written to your store remain unless you manually remove them.

## Data Security

- All communication between the app and Shopify uses HTTPS encryption
- The app authenticates through Shopify's OAuth flow — we never see or store your Shopify password
- Access tokens are managed by Shopify's session infrastructure

## Your Rights

You can:

- **View your data** — All data the app stores is visible within the app's dashboard
- **Delete your data** — Uninstalling the app removes your data from our systems
- **Control what's scanned** — You choose when to run scans and which page types to include
- **Control what's emitted** — You enable or disable schema output through the theme editor

## Children's Privacy

Simply Schema does not knowingly collect information from children under 13. The app is designed for use by Shopify store owners and administrators.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be posted at this URL with an updated "Last updated" date.

## Contact

If you have questions about this privacy policy or how Simply Schema handles your data:

- **Email:** brian@licitradesign.com
- **Business:** Licitra Design LLC

## GDPR and Data Protection

For users in the European Economic Area:

- **Legal basis for processing:** Legitimate interest (providing the app's functionality as requested by the merchant)
- **Data controller:** Licitra Design LLC
- **Data processor:** The app processes data on behalf of the merchant as part of Shopify's platform
- **Data access requests:** Contact us at the email above to request access to or deletion of your data
