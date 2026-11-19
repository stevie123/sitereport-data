# LPIS 2025 field parcels — compact

Derived from the Department of Agriculture, Food and the Marine's **anonymised LPIS 2025** parcels
(https://data.gov.ie/dataset/anonymous-lpis-data-for-2025), licence **CC BY 4.0**.

Built with `tools/lpis_compact.py` from the sitereport-backend repo: every parcel polygon simplified to 2.5 m
(topology-preserving), coordinates packed as zigzag-varint ITM decimetres, SQLite with an R-tree.
4,922,074 parcels; 754 MB. Published as 95 MB chunks (GitHub's file limit); `parcels.manifest.json` lists them
with the SHA-256 of the stitched file. The field outline, not the Land Registry boundary.
