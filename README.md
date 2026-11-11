# VitaLoom — GitHub Organization Configuration

This repository maintains the public [VitaLoom GitHub Organization](https://github.com/vitaloom) profile and may also host shared GitHub community templates in the future.

## Repository structure

```text
.github/
├── README.md                    # Guide to this repository
└── profile/
    ├── README.md                # Public organization profile
    └── assets/
        └── vitaloom-banner.svg  # Profile banner
```

## Updating the organization profile

Edit [`profile/README.md`](./profile/README.md) to update the content shown at **[github.com/vitaloom](https://github.com/vitaloom)**. Keep profile images and other presentation assets in [`profile/assets/`](./profile/assets/).

This root README describes the **`.github` repository itself** and does not appear as the organization profile.

## Documentation ownership

Avoid duplicating product specifications, API contracts, or repository-specific setup instructions here. Link to the canonical source instead:

- **Product direction and business rules:** `vitaloom-business-docs-and-tools` (private organization repository).
- **Backend implementation and API contracts:** [vitaloom-backend](https://github.com/vitaloom/vitaloom-backend).
- **Mobile implementation:** [vitaloom-frontend](https://github.com/vitaloom/vitaloom-frontend).
- **Design specifications and visual assets:** [vitaloom-design](https://github.com/vitaloom/vitaloom-design).
- **Synthetic event producer:** [vitaloom-data-producer](https://github.com/vitaloom/vitaloom-data-producer).

Profile content should distinguish the current implementation from the product roadmap. A documented or designed capability is not necessarily implemented.

## Optional shared GitHub templates

GitHub supports organization-wide community health defaults in a public `.github` repository (for repositories that do not define their own versions). Add shared issue or pull request templates only when there is a concrete need; individual repositories can own their own workflows.
