# CrowdPalette-100K
A user-contributed dataset of 100K color palettes

This dataset contains 100,000 color palettes with 5 colors each collected from online community sources.
Each palette includes names, HEX codes, and RGB values.

##  Data format
Each line in `dataset.jsonl` is a JSON object:
```json
{
  "name": "Pink Coral",
  "hexes": ["#F6DAE8", "#F1C5DB", "#EAABAB", "#E59797", "#EB9270"],
  "rgbs": [[246, 218, 232], [241, 197, 219], [234, 171, 171], [229, 151, 151], [235, 146, 112]]
}
