[README.md](https://github.com/user-attachments/files/28076709/README.md)
# Rhode Island Sun Safety & Shade Access Resource

A free, single-page public health tool that helps Rhode Islanders understand
local UV risk, tree-canopy shade access, and skin cancer prevention. Built as a
community resource with a focus on shade-access equity across RI communities.

## Features

- Live daily UV index by city/town (Open-Meteo API, no key required)
- Tree-canopy shade-access comparison across RI municipalities
- County-level qualitative sun-exposure context
- ABCDE melanoma warning signs and skin-of-color guidance
- Curated screening and care resources (AAD, RIDOH, RI Free Clinic, NCI)
- Printable one-page sun safety handout

## Running it

It is a static site with no build step and no dependencies. Open `index.html`
in any browser, or host it on GitHub Pages (Settings → Pages → deploy from the
`main` branch, root). The UV checker requires an internet connection to reach
the Open-Meteo API.

## Data sources

- UV index: [Open-Meteo](https://open-meteo.com) (free, open source)
- Tree canopy: [RI DEM Urban Forestry](https://dem.ri.gov/urban-forestry) and
  [American Forests Tree Equity Score](https://www.treeequityscore.org)
- Cancer surveillance: [NCI State Cancer Profiles](https://statecancerprofiles.cancer.gov)

Tree-canopy values are approximate shade-access indicators compiled from public
sources and may vary by source, year, and geographic boundary. They are intended
as relative indicators, not precise measurements.

## Disclaimer

This resource is for educational purposes only and does not constitute medical
advice. Consult a licensed clinician for personal medical guidance.

## License

MIT License.
