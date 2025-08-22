# Usage Guide – Dub and CamRip Labeler

## How it Works
- The script scans all **content cards** on CircleFTP.
- It looks for specific keywords in:
  - Title
  - Heading (`h3`)
  - Description (`p`)
- If it detects:
  - **Dub keywords** → adds a `DUB` label
  - **CamRip keywords** → adds a `CAM` label
- Labels are added **only once per card** for performance.

## Lazy Loading
- Uses `IntersectionObserver` to only process cards when they are visible in the viewport.
- Uses `MutationObserver` to detect dynamically loaded cards (infinite scroll).

## Example Labels
- `DUB` (Blue) → Dual Audio or Dubebd Anime
- `DUB` (Orange) → Any other Dubbed content
- `CAM` (Red) → Cam/low-quality releases

---

## Notes
- Script is lightweight — avoids reprocessing by caching cards.
- Designed specifically for **http://new.circleftp.net/**.
- Works best with **default CircleFTP layout**.
