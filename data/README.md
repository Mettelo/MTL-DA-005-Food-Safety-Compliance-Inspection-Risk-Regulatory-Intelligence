# Data Workspace — MTL-DA-005

## Dataset

**Food Standards Agency — Food Hygiene Rating Scheme / Food Hygiene Information Scheme Open Data**

The data provides establishment-level food hygiene ratings and related metadata for food businesses across the UK.

## Official Open Data Source

https://ratings.food.gov.uk/open-data

## API Documentation

https://api.ratings.food.gov.uk/

## Recommended Acquisition Method

For full recurring ingestion, use the official open-data files published by the Food Standards Agency.

The API can be used for targeted or live queries, but teams should document whichever approach they use and ensure it is reproducible.

## Useful Fields

Depending on source format, useful fields include:

- FHRSID;
- BusinessName;
- BusinessType;
- Address;
- PostCode;
- RatingValue;
- RatingDate;
- LocalAuthorityName;
- LocalAuthorityCode;
- Hygiene;
- Structural;
- ConfidenceInManagement;
- NewRatingPending;
- Latitude;
- Longitude;
- SchemeType.

## Folder Structure

```text
data/
├── README.md
├── raw/
├── reference/
└── metadata/
```

## raw/

Use for:
- downloaded FSA open-data files;
- reproducible source extracts;
- small source samples.

Do not manually edit raw source files.

## reference/

Store:
- API documentation;
- field definitions;
- scheme notes;
- rating interpretation guidance;
- licence/reuse notes.

## metadata/

Store:
- source provenance;
- file inventory;
- schema;
- data dictionary;
- extraction date;
- known limitations.

## Team Repository Data Structure

Each team should use:

```text
data/
├── README.md
├── raw/
└── processed/
```

The team's `data/README.md` must explain exactly how a reviewer obtains and prepares the source data.
