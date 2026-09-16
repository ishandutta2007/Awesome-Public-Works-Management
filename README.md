# Awesome-Public-Works-Management

## Top Public Works Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Municipal Asset Management, Work Orders, GIS Integration, Infrastructure Maintenance & Capital Planning*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Public Works Management**. These systems help cities, counties, and public agencies manage infrastructure assets (roads, signs, parks, utilities, facilities), work orders, service requests, inspections, and capital planning—often with strong GIS integration.



**Examples** include Cityworks, Cartegraph, OpenGov Public Works, Asset Essentials, Brightly Confirm, Lucity, Infor Public Sector, MaintainX, UpKeep, and IBM Maximo (the category leaders).



**Open-source emphasis**: Specialized public-works and municipal asset platforms are largely commercial. Strong open options exist in general CMMS/EAM tools (**openMAINT**, Odoo Maintenance, emerging open CMMS projects) that can support asset and work-order needs. This section lists the best available open resources and is realistic about the GIS and municipal-specific gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



| Product | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Cityworks (Trimble)](https://www.cityworks.com/)** | Leading GIS-centric public works and asset management platform tightly integrated with Esri ArcGIS for infrastructure lifecycle management. | Annual subscription quotes (base deployments typically start around $1,995/yr - $50,000+/yr based on scale) | No free trial; custom interactive demos available upon request |
| **[Cartegraph (OpenGov)](https://www.cartegraph.com/)** | Municipal asset and operations management platform (now part of OpenGov) covering roads, parks, facilities, and related public works assets. | Custom annual subscription quotes (base subscriptions estimated from $1,499/user/yr) | No free trial; live customized demo sessions provided |
| **[OpenGov Public Works / EAM](https://opengov.com/)** | Government cloud platform that includes public works, asset management, work orders, and capital planning capabilities. | Custom enterprise quotes based on agency size and module selection | No free trial; personalized demos available for government agencies |
| **[Asset Essentials (Brightly)](https://www.brightlysoftware.com/)** | Cloud CMMS/asset management solution frequently used by public sector organizations for facilities and infrastructure maintenance. | Custom annual quotes (small deployments typically range from $100–$300/mo) | No free trial; guided product demos provided |
| **[Brightly Confirm](https://www.brightlysoftware.com/)** | Infrastructure asset management and investment planning tools within the Brightly portfolio. | Custom enterprise quotes based on asset volume and infrastructure scope | No free trial; scheduled product demonstrations available |
| **[Lucity (CentralSquare EAM)](https://www.lucity.com/)** | Public works management software for work orders, assets, and municipal operations. | Custom enterprise quote-based pricing via CentralSquare Technologies | No free trial; customized software demonstrations offered |
| **[Infor Public Sector](https://www.infor.com/)** | Enterprise solutions for public sector operations, including asset and work management capabilities. | Custom annual enterprise subscription quotes based on modules and user count | No free trial; tailored enterprise demos available |
| **[MaintainX](https://www.getmaintainx.com/)** | Modern mobile-first CMMS and work order platform used by both private and public organizations. | $20 per user/month (Essential plan, billed annually) or $25/mo (monthly) | Free for life Basic plan (max 2 active repeating work orders, 1 month analytics) |
| **[UpKeep](https://www.upkeep.com/)** | Asset and maintenance management platform with work order, preventive maintenance, and inventory features. | $20 per user/month (Essential plan, billed annually) or $24/mo (monthly) | 7-day free trial (no credit card required; free unlimited view-only/requester users) |
| **[IBM Maximo](https://www.ibm.com/products/maximo)** | Enterprise asset management platform widely used for complex infrastructure and public-sector asset programs. | Credit-based AppPoints model (estimates starting around $164 per user/month) | 14-day free trial (includes access to Maximo Manage and Maximo Health with sample data) |



## Open-Source GitHub Projects

- **[openMAINT](https://www.openmaint.org/)**  

  Open-source enterprise asset management and CMMS solution based on the CMDBuild platform, suitable for facilities and infrastructure maintenance.



- **[Odoo Maintenance](https://github.com/odoo/odoo)**  

  Open-source maintenance and equipment management module within Odoo ERP, supporting work orders, preventive maintenance, and asset tracking.



- **[Emerging open CMMS platforms (Atlas CMMS, SuperCMMS, etc.)](https://github.com/)**  

  Community and commercial-open CMMS projects that provide work orders, asset registers, preventive maintenance, and mobile access.



- **[Infrastructure asset registry open experiments](https://github.com/)**  

  Initiative projects aiming to provide GIS-linked inventories of roads, bridges, pipes, and other public infrastructure without proprietary lock-in.



- **[GIS and PostGIS open asset tools](https://github.com/)**  

  Open geospatial components and PostGIS-based systems that can support spatial asset inventories and mapping.



- **[Work order and request open trackers](https://github.com/)**  

  Lightweight open systems for logging service requests and maintenance work orders.



- **[Preventive maintenance scheduling open helpers](https://github.com/)**  

  Tools and templates for defining and tracking recurring maintenance tasks.



- **[Inventory and parts open managers](https://github.com/)**  

  Open inventory modules that can be paired with maintenance systems for public works stockrooms.



- **[Mobile inspection open forms](https://github.com/)**  

  Open form and mobile data collection tools useful for field inspections of public assets.



- **[Reporting and dashboard open components](https://github.com/)**  

  Open BI tools for visualizing work order backlogs, asset condition, and maintenance performance.



### Additional Strong Open-Source Options

- Starting with **openMAINT** or **Odoo Maintenance** for facilities-oriented public works needs.

- Combining open CMMS tools with open GIS (QGIS, PostGIS) for basic spatial asset management.

- Using emerging open asset registry projects for inventory and condition tracking.

- Accepting that deep Esri ArcGIS integration, advanced capital planning, multi-department public works workflows, and proven municipal scale still favor commercial platforms (Cityworks, Cartegraph/OpenGov, Brightly, Lucity, IBM Maximo, etc.).

- Hybrid approaches that use open tools for smaller agencies or specific asset classes alongside commercial systems for core operations.



**Frameworks for building custom systems**: Deploy an open CMMS (openMAINT or Odoo) → build an asset hierarchy → configure work order and preventive maintenance workflows → add spatial data via PostGIS/QGIS → expose mobile forms for field crews → report on performance. Suitable for smaller municipalities or specialized use cases. Most mid-to-large public works departments continue to rely on commercial platforms designed specifically for municipal infrastructure and GIS-centric operations.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Public works systems manage critical infrastructure data and field operations. Ensure proper security, access control, data backup, and compliance with local government requirements. Self-hosted open-source solutions require ongoing technical capacity. This list is not operational or engineering advice.



---

**Made for public works directors, asset managers, and municipal technology teams who need reliable infrastructure management.**

Let's keep public assets well-maintained, data-driven, and as open as practical.
