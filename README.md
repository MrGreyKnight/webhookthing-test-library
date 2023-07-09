# Webhookthing Hooks Library

This repo contains structured JSON data for simulating webhooks with Webhookthing by ping.gg

> Please note that these are the examples set out by the Service providers, they can change at any time and there data structures will most likely need modifying for your specific use case.

Any contributions would be greatly appricated.

## Contributing Guide

All Hooks are stored in the `.thing/hooks/` directory to match webhookthing directly.

Please follow the pretter configuration for JSON files.

Folder structure sits in the following format

- Hooks
  - Service Provider/Product
    - Major version
      - Minor Version
        - Folders to match webhook naming scheme

### Example

Square Devices Webhooks `device.code.paired`

- Hooks
  - Square
    - V2
      - 2023-06-08
        - device
          - code
            - paired.json

## Current Library

| Library | Major Version | Minor Version | Last Updated |
| ------- | ------------- | ------------- | ------------ |
| Clerk   |               |               | 09-07-2023   |
| Square  | V2            | 2023-06-28    | 09-07-2023   |

# License

Apache-2.0 license
