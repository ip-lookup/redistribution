# IP-Lookup Redistribution

This repository contains redistributions of IP geolocation databases from third-party providers. These databases are automatically updated on a regular schedule to ensure accuracy and compliance with privacy regulations.

## Available Databases

### MaxMind GeoLite2

- GeoLite2-City-CSV: City-level IP geolocation data
- GeoLite2-Country-CSV: Country-level IP geolocation data
- GeoLite2-ASN-CSV: Autonomous System Number (ASN) data

Updates occur daily at 1:34 UTC.

## Usage

Each database is available in the corresponding folder with its own README containing specific usage instructions and licensing details.

## Legal Notice

- Usage of these databases is governed by the respective license agreements of the original providers
- Due to privacy regulations (e.g., GDPR) that implement the right to be forgotten, we:
  - Update databases regularly to ensure accuracy
  - Remove old versions and git history to prevent unauthorized user tracking
  - Only distribute the latest versions of each database

## Automated Updates

Updates are handled via GitHub Actions workflows. The process includes:

1. Checking for new database versions
2. Verifying file integrity via checksums
3. Cleaning git history of old versions
4. Committing new database files

For technical details, see the workflow files in `.github/workflows/`.
