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
├── Backgrounds/     # abstract gradient and aurora backgrounds
├── Office/          # office buildings, interiors, meeting rooms, skyscrapers
├── Finance/         # trading desks, charts, calculators, bookkeeping
└── Technology/      # abstract digital/data/network visualizations
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
| Office           | 18    |
| Finance          | 7     |
| Technology       | 5     |
| **Total**        | **130** |

## Naming convention

- All filenames are **kebab-case**: lowercase words separated by hyphens.
- Names describe the **content** of the photo, not the photographer or source ID.
- Format: `subject-modifier-detail.jpg` (e.g. `airplane-window-snowy-mountains.jpg`, `hotel-bedroom-pink.jpg`).
- The category is implied by the parent folder, so names don't repeat it (e.g. inside `Travel/Hotels/`, files are `hotel-bedroom-*.jpg` rather than `travel-hotel-bedroom-*.jpg`).
