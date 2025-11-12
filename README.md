# touchSMS V2 API

Official OpenAPI 3.0 specification for TouchSMS API integration with Rewst.

## Documentation
[Rewst Custom Integration Guide](https://docs.rewst.help/documentation/configuration/integrations/custom-integrations/custom-integrations-v2)

## Specification Details
- **Version**: 2.0.0-draft
- **Base URL**: `https://api.touchsms.com.au`
- **Authentication**: N/A

## Description
OpenAPI spec derived from touchSMS V2 Postman collection.
Replace fields marked TODO with exact values from your environment.


## Usage

### Import into Rewst
1. Navigate to: Rewst Dashboard > Configuration > Integrations
2. Create Custom Integration
3. Upload `openapi.json` from this repository
4. Configure authentication parameters
5. Test connection

### Import into API Testing Tools
- **Postman**: Import > Link > Paste raw GitHub URL
- **Insomnia**: Import > URL > Paste raw GitHub URL
- **OpenAPI Generator**: `openapi-generator-cli generate -i openapi.json`

## Repository Structure
```
.
├── openapi.json              # Primary OpenAPI 3.0 specification
├── assets/                   # Integration assets (logos, guides)
├── README.md                 # This file
└── .github/
    └── workflows/
        └── validate-openapi.yml  # CI validation
```

## Validation
This specification is automatically validated on every commit using GitHub Actions.

## Contributing
Maintained by Rewst APAC Automation Team.

## Support
- **Technical Support**: roc@rewst.io
- **Documentation**: [Rewst Docs](https://docs.rewst.help)

## License
Private repository - Rewst LLC internal use only.
