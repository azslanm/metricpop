# MetricPop

**Multi-Platform Advertising Data Connector for Looker Studio**

MetricPop is a multi-platform advertising data connector designed to help marketers and businesses consolidate their advertising performance data directly into Looker Studio.

Connect multiple advertising platforms, access campaign performance metrics, and build unified reporting dashboards from one place.

## Supported Platforms

| Platform | Development Status |
|---|---|
| Meta Ads | Phase 1 — In Development |
| TikTok Ads | Planned |
| Google Ads | Planned |
| Shopee Ads | Planned |
| LinkedIn Ads | Planned |
| Other Advertising Platforms | Future Expansion |

## Product Vision

To simplify advertising analytics by bringing data from multiple advertising platforms into one unified reporting environment.

## Planned Capabilities

- Multi-platform account connections
- Campaign, ad group/ad set, and ad-level reporting
- Performance and conversion metrics
- Cost and revenue reporting
- Custom date range configuration
- Platform-specific dimensions and metrics
- Breakdown and attribution reporting
- Unified cross-platform reporting capabilities

## Technology Stack

- Google Apps Script
- Looker Studio Community Connector
- Advertising Platform APIs
- JavaScript

## Architecture

MetricPop is designed with a modular architecture. Each advertising platform will have its own connector module, while shared components handle common data processing, schema management, and reporting functionality.

This approach allows new advertising platforms to be integrated without rebuilding the entire system.

## Development Roadmap

**Phase 1 — Meta Ads Connector**
- Meta Marketing API integration
- Account authentication
- Campaign, ad set, and ad reporting
- Performance metrics and conversion reporting
- Looker Studio integration

**Future Phases — Multi-Platform Expansion**
- TikTok Ads integration
- Google Ads integration
- Shopee Ads integration
- LinkedIn Ads integration
- Additional advertising platforms

## Project Status

Under Development.

## License

All rights reserved.
