# Bambu Studio Settings (X1 Carbon, PETG – Black)

Recommended starting profile settings for the split mask holder and masks, organized by the common Bambu Studio categories.

## Quality
- Layer height: 0.20 mm (use 0.16 mm if you want crisper slot edges).
- Perimeters (walls): 4.
- Top/Bottom: 5–6 layers (≈1.0–1.2 mm).

## Strength
- Infill: 20–30% gyroid or grid (20% is usually enough; 30% for extra rigidity).
- Material: PETG.

## Support
- Supports: Off by default. If the slot needs help, enable “Touching buildplate” only.
- Support density: 10–15% if used.
- Support interface: Off (not needed if minimal supports).

## Adhesion
- Brim: 5 mm brim on the holder; no brim needed for masks.
- Bed prep: Clean bed; a light glue stick layer helps PETG release from the plate.

## Cooling
- Part fan: 20–40%. For bridging the slot, allow a temporary bump to 40–60%.
- Aux fan: Off.

## Speed
- Use the PETG preset speeds (avoid “Ludicrous” mode).
- If you see stringing/blobs: lower outer wall to ~60 mm/s and travel to ~180 mm/s.

## Temperature
- Nozzle: 245 °C (can drop to 240 °C if stringing persists).
- Bed: 80–85 °C.
- Dry filament if exposed (e.g., 60 °C for ~4 h).

## Notes for This Part
- Holder: Print flange-down so the slot bridges; with good bridging, supports aren’t needed.
- Masks: Lay flat (plate on bed); no supports.
- Fit tuning: If the slot is tight, increase `slot_gap` or reduce `stem_width` slightly. If the bayonet fit is tight, increase clearance/tolerance in the SCAD and re-export.
