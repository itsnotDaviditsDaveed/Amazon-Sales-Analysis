# Amazon Product Ratings & Discounts

**Tools:** Tableau · Kaggle dataset (1,465 products)

I used a dataset of 1,465 Amazon product listings with prices, discounts, ratings, and review counts to see whether bigger discounts go with better ratings, and how categories compare.

![Dashboard](Dashboard%201.png)

## Key Findings

- **The catalog is mostly electronics, computer accessories, and home & kitchen** (1,427 of 1,465 products).
- **Discounts are steep.** The average discount is about 48%, and Computers & Accessories averages about 54% off.
- **Ratings are consistently high.** The average is about 4.1 out of 5 across all major categories.
- **Bigger discounts don't mean better ratings.** The relationship is slightly negative (r ≈ −0.16), so heavily discounted items actually rate a little lower.

| Category | Products | Avg Rating | Avg Discount |
|---|---|---|---|
| Electronics | 526 | 4.08 | 51% |
| Computers & Accessories | 453 | 4.15 | 54% |
| Home & Kitchen | 448 | 4.04 | 40% |
| Office Products | 31 | 4.31 | 12% |

## Dashboard

- **Rating vs Discount:** discount level for the top sub-categories, with bubble size showing review count
- **Discount % by Category:** average discount for each sub-category
- **Average Rating by Category:** average rating for each sub-category

## Files

- `Dashboard 1.png`: Tableau dashboard
- `amazon.csv.zip`: dataset (unzip to use)
