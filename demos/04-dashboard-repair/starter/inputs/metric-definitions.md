# Fieldwork Services metric definitions
Fixed fictional reporting date: June 30, 2026. Currency: fictional CAD amounts.
Approved order value = sum(quantity * unit_price) for rows whose status is exactly approved, within the selected region.
Approved order count = number of approved rows within the selected region. Cancelled and draft rows never count as approved value or count.
A visible table must make status clear. An export contains exactly the visible table rows after filtering. Include All, North, South, East and a no-data region West so the empty state can be tested.
No forecasting or live data claim. Inputs must remain unchanged.
