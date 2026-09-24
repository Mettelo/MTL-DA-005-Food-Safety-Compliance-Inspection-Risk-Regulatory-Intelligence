# Required Deliverables

Every team repository must contain evidence for all deliverables below.

## D1 — Discovery & Data Quality Assessment
**Due:** End of Week 1  
**Location:** `docs/01-discovery/`

Required:
- source inventory;
- record counts;
- establishment ID checks;
- scheme coverage;
- rating distribution;
- missing-data assessment;
- geographic completeness;
- date coverage;
- component-score availability;
- key data-quality limitations.

## D2 — Ingestion & Transformation Layer
**Due:** Initial version by end of Week 2  
**Location:** `src/`, `sql/`, `docs/02-data-model/`

Required:
- reproducible source ingestion;
- standardised establishment model;
- rating/status normalisation;
- local-authority mapping;
- inspection/rating recency fields;
- derived analytical fields;
- documented execution steps.

## D3 — KPI & Metric Catalogue
**Due:** End of Week 3  
**Location:** `docs/03-kpi-catalogue/`

Expected metrics:
- establishments by rating;
- low-rating rate;
- unrated/awaiting rating;
- new-rating-pending rate;
- median/average rating age;
- establishments with stale ratings;
- business-type compliance profile;
- local-authority portfolio size;
- component-score indicators.

Each metric must include definition, calculation, grain, source fields, exclusions and limitations.

## D4 — Compliance & Rating Analysis
**Due:** End of Week 4  
**Location:** `analysis/` and `docs/04-compliance-analysis/`

Required:
- rating distribution;
- business-type comparison;
- component-score analysis;
- local-authority comparison;
- inspection-recency analysis;
- clear interpretation of limitations.

## D5 — Geographic & Regulatory Workload Analysis
**Due:** End of Week 4  
**Location:** `analysis/` and `docs/05-geographic-workload/`

Required:
- geographic distribution;
- low-rating concentrations;
- establishment density context;
- local-authority workload indicators;
- pending-rating patterns;
- appropriate caveats.

## D6 — Transparent Prioritisation Framework
**Due:** End of Week 5  
**Location:** `docs/06-prioritisation-framework/`

Develop an interpretable analytical framework using factors such as:
- low rating;
- rating age;
- component-score concerns;
- pending rating status;
- business type;
- data completeness.

The framework must:
- remain explainable;
- avoid pretending to be a statutory risk score;
- document assumptions;
- show how false positives/negatives could arise;
- identify where professional judgement remains required.

## D7 — Management Dashboard / Decision-Support Product
**Due:** Draft Week 5; final Week 6  
**Location:** `dashboard/`

Should support:
- compliance overview;
- rating distribution;
- inspection recency;
- local-authority comparison;
- geographic exploration;
- prioritisation review.

## D8 — Technical Handover
**Due:** Week 6  
**Location:** `docs/07-technical-handover/`

Must explain:
- repository structure;
- source acquisition;
- ingestion process;
- transformation logic;
- metric definitions;
- dashboard refresh;
- reproduction steps;
- limitations;
- maintenance recommendations.

## D9 — Executive Briefing
**Due:** Week 6  
**Location:** `deliverables/executive-briefing/`

Maximum two pages or equivalent.

## D10 — Final Presentation
**Due:** Mettelo Demo Day  
**Location:** `deliverables/presentation/`

15–20 minute presentation plus Q&A.

## D11 — Contribution Record
**Due:** Final submission  
**Location:** `CONTRIBUTIONS.md`

For each member:
- role;
- responsibilities;
- main deliverables;
- linked evidence;
- presentation contribution.
