# Changelog

## 2026-06-01

### Added

- Added a notebook-level last-updated marker for `cerra-ciaran.ipynb`.
- Added source attribution for the CERRA, ERA5, and E-OBS wind datasets used in the Ciaran case study.

### Changed

- Moved the main notebook title into the first markdown cell so the notebook starts with a clear H1 before the banner image.
- Reformatted Python cells throughout `cerra-ciaran.ipynb` for consistent spacing, imports, function calls, plotting setup, and dictionary/list formatting.
- Replaced the wildcard-style CDO import with an explicit `import cdo` and `cdo.Cdo()` initialization.
- Cleared selected stale execution counts and normalized notebook output metadata as part of the reformat.
- Updated plot coordinate setup to use `cerra_daily_max` latitude and longitude values consistently with the daily-maximum wind-speed panels.

### Fixed

- Updated the CDS API setup instructions to point to the current `https://cds.climate.copernicus.eu/how-to-api` page instead of the failing `api-how-to` URL.
- Removed an unused `bgz` assignment from the point time-series locator helper.
