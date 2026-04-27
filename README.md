 # The Invisible Skeleton: How a 2,000-Year-Old Network Still Decides Who Gets Rich

  Does living near a Roman road built in 43 AD make you richer in 2025?

  This project maps the Roman road network of England against modern household income data across 6,856 neighbourhoods, asking whether ancient infrastructure still shapes economic outcomes today.

  ## Method

  - **Roman centrality** quantified using the Itiner-e dataset and a distance decay model — treating road junctions as radiators, with influence decaying by distance
  - **OLS regression** with controls (education, health, population density, modern road centrality, distance to London) to isolate the Roman signal
  - **Geographically Weighted Regression (GWR)** to uncover local variation hidden by national averages

  ## Key Finding

  Roman roads are not a uniform wealth predictor. Along the A1 "Ermine Street" spine and in commuter towns like Brighton, ancient centrality is a strong predictor of modern income (β up to 1.96). In post-industrial areas like Bristol and
  Leicester, the effect reverses — early connectivity became a lock-in trap rather than a wealth accelerator.

  ## Data Sources

  - Itiner-e digital atlas of Roman roads
  - 2021 UK Census household income data (LSOA level)
