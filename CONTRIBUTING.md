# Contributing to Pegasus PS4 Collection Catalog

Thank you for contributing to the catalog! Please follow these guidelines to keep entries structured, clean, and fully compatible with Pegasus DL.

---

## How to Contribute

1. **Fork the Repository:** Create your own fork of this repo.
2. **Create a Feature Branch:** `git checkout -b update-links`
3. **Edit `catalog.json`:** Add new titles or update existing links following the format below.
4. **Validate JSON:** Ensure `catalog.json` passes strict JSON validation.
5. **Open a Pull Request:** Submit your PR with a clear summary of changes.

---

## Entry Guidelines

Every package inside `"packages"` must adhere to this structure:

```json
{
  "titleId": "CUSAXXXXX",
  "title": "Clean Game Title",
  "downloadLinks": [
    {
      "name": "Region Base (vVersion) - Provider",
      "url": "https://..."
    }
  ],
  "category": "game",
  "posterUrl": "https://...",
  "version": "01.00",
  "description": "Region: USA\nVersion: 01.00\nMin FW: 9.00\nSize: X.XX GB",
  "downloadSource": "https://..."
}
```

### Hoster & Provider Tags:
- Always format the link name as: `<Region> Base (v<Version>) - <Provider>`
- Example: `USA Base (v01.04) - Direct`
- Valid Title IDs for PS4 must start with `CUSA`.
