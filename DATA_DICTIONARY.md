# Plant Data Dictionary

The digital archive uses a structured record for each plant.

| Field | Meaning |
|---|---|
| `id` | Unique plant record identifier |
| `common` | Common/local name of the plant |
| `sci` | Scientific name |
| `family` | Botanical family |
| `conf` | Identification-confidence level |
| `type` | General plant type |
| `desc` | Morphological or observational description |
| `habitat` | Habitat/environment where the plant was observed |
| `uses` | Recorded/common uses |
| `loc` | Collection/observation location |
| `lat` | Latitude when available |
| `lng` | Longitude when available |
| `date` | Collection/observation date |
| photograph | Associated plant photograph |

## Confidence Values

The current interface supports confidence labels including:

- High
- High (genus)
- Medium-High
- Medium

A scientific name containing a probable identification is additionally marked as **PROVISIONAL IDENTIFICATION** by the interface.

## Missing Data

Not every original record contains every field. Missing information should remain explicitly unavailable instead of being guessed.

## Example

```json
{
  "id": "P-002",
  "common": "Purple/Ruby Alternanthera",
  "sci": "Alternanthera brasiliana (probable)",
  "family": "Amaranthaceae",
  "conf": "Medium",
  "type": "Herb/subshrub",
  "loc": "Indore, Madhya Pradesh",
  "lat": "22.759458",
  "lng": "75.898665",
  "date": "02 Oct 2026"
}
```

