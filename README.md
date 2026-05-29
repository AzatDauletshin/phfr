# Photos

A categorized library of stock photos (sourced from Unsplash), organized by subject and renamed in kebab-case to reflect their visual content.

## Structure

```
photos/
├── Travel/
│   ├── Avia/        # airplanes, airports, boarding passes, in-flight views
│   ├── Hotels/      # hotel rooms, lobbies, exteriors
│   └── Railways/    # trains, tracks, stations, platforms
├── Groceries/       # produce, shopping bags, supermarket items
├── Restaurants/     # restaurant interiors, table settings, plated spreads
├── Food/            # individual dishes, bowls, prepared food
├── Health/          # medical, pharma, DNA/biotech illustrations
├── Events/          # concerts, theaters, cinemas, tickets
└── Backgrounds/     # abstract gradient and aurora backgrounds
```

## Counts

| Category         | Files |
| ---------------- | ----- |
| Travel/Avia      | 20    |
| Groceries        | 15    |
| Travel/Hotels    | 14    |
| Health           | 12    |
| Events           | 8     |
| Travel/Railways  | 7     |
| Restaurants      | 5     |
| Food             | 5     |
| Backgrounds      | 14    |
| **Total**        | **100** |

## Naming convention

- All filenames are **kebab-case**: lowercase words separated by hyphens.
- Names describe the **content** of the photo, not the photographer or source ID.
- Format: `subject-modifier-detail.jpg` (e.g. `airplane-window-snowy-mountains.jpg`, `hotel-bedroom-pink.jpg`).
- The category is implied by the parent folder, so names don't repeat it (e.g. inside `Travel/Hotels/`, files are `hotel-bedroom-*.jpg` rather than `travel-hotel-bedroom-*.jpg`).

## Adding new photos

1. Drop the file into the matching category folder.
2. Rename to kebab-case based on what's in the photo.
3. Keep names short but specific enough to disambiguate similar shots (`airplane-belly-blue-sky.jpg` vs `airplane-belly-clear-sky.jpg`).

## Attribution

All photos were originally sourced from [Unsplash](https://unsplash.com). The original Unsplash filenames (e.g. `alexander-mils-7EpPehZxP6E-unsplash.jpg`) preserved the photographer and image ID — if you need to credit a specific photo, the original IDs are recoverable from git history before the renaming commit.
