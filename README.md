# PJTL-VL Internal Dashboard
Internal Dashboard

## Dashboard design mock-ups

Standalone HTML pages in `mockups/`. Open them in any browser; no server or data needed.
All brain images and numbers are synthetic placeholders for reviewing the design.

- `pet_dashboard_mockup_v1.html` - first draft: SSIM, overlap (Dice/Jaccard/MAE/SWD), hotspot and cluster measures, plus a methods section.
- `pet_dashboard_mockup_v2.html` - current draft: metric-family filter (SSIM, MS-SSIM & MHD, EMD & PSNR, Hotspot, Cluster), overlap group and methods section removed.

Layout: subject/slice filters, headline tiles (one per visible metric family), four image panels
(GT, ERP prediction, median baseline, difference) with hotspot/cluster/region overlays,
per-slice hotspot and cluster tables, a cross-subject chart and a full metric table.
