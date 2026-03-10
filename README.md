# CRM Implementation Scope Builder

Interactive, browser-based scope estimation tool for CRM implementation projects (HubSpot, Salesforce, Dynamics, etc.).

## Features

- **Compositional estimation**: Build scope from hubs + integrations + migrations + website + add-ons
- **Overage risk scoring**: 0-15 risk scale based on analysis of 3,000+ real CRM projects  
- **Dynamic scoping checklist**: Pre-quote checks that adapt to your scope configuration
- **Multi-currency support**: GBP, EUR, USD, SGD, AUD, ZAR, CAD
- **Comparable project matching**: Find similar past projects by hub combination and currency
- **Revenue impact analysis**: Current vs recommended rate comparison

## How It Works

Total Scope = Base Implementation + Σ Integrations + Σ Migrations + Website + Custom Dev + Change Mgmt + Training + Marketplace Apps

All multiplied by complexity and region factors.

The overage risk assessment scores your configuration against patterns found in overrun projects — flagging website builds, integration stacking, small project paradox, and other risk factors with data-backed recommendations.

## Usage

Just open `index.html` in a browser. No build step, no dependencies, no server needed.

**Live version**: [GitHub Pages](https://raphaelfenaux.github.io/crm-scope-builder/)

## Data

Built from anonymized analysis of 3,000+ real CRM implementation projects across 7 currencies and 13 regions. Project names and client identifiers have been anonymized. Rate cards are rounded sample values — customize for your organization.

## License

MIT
