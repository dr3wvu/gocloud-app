---
title: "Dynamics 365 Cloud"
category: "Business Application"
featuredImage: ../../../images/Power-BI.png
iconImage: ../../../images/Data-Analytics.png
downloads: [{location: "../../static/Power BI Brochure.pdf", name: "Power BI Brochure"},
            {location: "../../static/Power BI How-To Guide.pdf", name: "Power BI How-To Guide"},
        ]
description: "PowerBI takes common spreadsheets and various data sources and transforms them into intuitive visualizations using an array of built-in tools."
billing: "A SKU – On-demand via Azure Portal charged to IFIS String. P SKU – Annual commit paid to ITS procurement"
networkConnectivity: "Use-cases have been put into production that integrate with Azure IaaS, Azure PaaS, Microsoft SaaS (SharePoint and Dynamics), GDC/KDC hosted databases"
sensitivityTable: [
            {sensitivity: 'High Sensitivity', status: false},
            {sensitivity: 'Medium Sensitivity', status: true},
            {sensitivity: 'Low Sensitivity', status: false},
        ]
FAQInfo: [
           {header: "Premium Node", qa: [{question: 'Why should I get a Premium node', answer: 'Avoids having to assign individual pro licenses for people to access reports which becomes cumbersome to manage at scale. Only feasible method to share reports externally (with BPS and trusted vendors) that do not already have Pro licenses. Your reports are hosted in your own reserved capacity as opposed to the multi-tenancy capacity included with Pro licenses. Data storage limits are higher.'}, {question: 'Can I share a Premium node?', answer: 'Please contact ITSM Data Analytics Practice for more information'}, {question: 'Can I turn off the Premium Node to save costs?', answer: 'A SKU yes, P SKU no'}]},
           {header: "Other", qa: [{question: 'When can I use the A SKU', answer: 'Only when your report is being embedded into a custom webpage. Consider there may be other costs associated with this to secure the webpage and make it available.'}, {question: 'Can Power BI work with Azure AD B2C', answer: 'Currently natively unavailable. You can embed a report into a webpage that can be integrated with Azure AD B2C but consider the expertise needed for this before deciding to move ahead with this option (developer required).'}, {question: 'Can we modify certain tenant settings?', answer: '	These are reviewed on a per-use case basis. The modifications here affect the supportability of Power BI for the entire OPS.'}, {question: 'Can I connect Power BI to my data source in GDC/KDC?', answer: 'Yes, but there are multiple considerations'}, {question: 'Yes, but there are multiple considerations', answer: 'As of Aug 2020, this cannot be done. The type of ExpressRoute connectivity the OPS has procured only allows connectivity to Azure IaaS. All connectivity to PowerBi.com directly from GDC/KDC would be over the internet.'}, {question: 'What authentication method does Power BI natively support', answer: 'PowerBi.com supports Azure AD authentication. OPS Ontario.ca identities work out of the box. Onboarding broader public sector or trusted vendor identities can be done via Azure AD B2B.'}, {question: 'How do I obtain a Power BI Pro license', answer: 'Look for Microsoft Common Services in SODO. The Free license allows access to PowerBi.com as an individual. The Pro license allows you to share your live reports/dashboard with others.'}
           ]},
        ]
 
---
<!-- Use Cases -->
- **Hosting**
- Hosting reports accessed by Broader Public Sector
- Hosting reports accessed by a large number of OPS users to avoid individual licensing
- **Database Support**
- Supporting larger datasets
