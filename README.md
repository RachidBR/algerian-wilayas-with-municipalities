# Algeria Wilayas and Municipalities JSON
Salam 3likom

Here is a JSON dataset containing the full list of Algeria's 58 **wilayas** (provinces) and their corresponding **municipalities** (communes), as an array.

## Structure

Each wilaya includes:
- `wilayaCode`: The official numeric code
- `nameFr`: Name in French
- `nameAr`: Name in Arabic
- `communes`: An array of municipalities with:
  - `id`
  - `nameFr`
  - `nameAr`

## Example of a wilaya object containing a commune object

```json
{
  "wilayaCode": 1,
  "nameFr": "Adrar",
  "nameAr": "أدرار",
  "communes": [
    {
      "id": 1,
      "nameFr": "Adrar",
      "nameAr": "أدرار"
    }
  ]
}
```
