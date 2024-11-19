# MaxMind GeoLite2 Databases

This directory contains the latest versions of MaxMind's GeoLite2 databases in CSV format.

## Available Databases

### GeoLite2-City-CSV

- Provides city-level IP geolocation data
- Updated daily
- Format: ZIP archive containing CSV files

### GeoLite2-Country-CSV

- Provides country-level IP geolocation data
- Updated daily
- Format: ZIP archive containing CSV files

### GeoLite2-ASN-CSV

- Provides Autonomous System Number (ASN) data
- Updated daily
- Format: ZIP archive containing CSV files

## Usage

1. Download the desired `.zip` file
2. Verify the file integrity using the corresponding `.sha256` checksum file
3. Extract and use according to MaxMind's documentation

## License

These databases are distributed under MaxMind's GeoLite2 End User License Agreement.
For full terms, visit: https://www.maxmind.com/en/geolite2/eula

## Updates

- Databases are automatically updated daily at 1:34 UTC
- Only the latest version is kept to comply with privacy regulations
- Updates are verified using SHA-256 checksums before distribution
