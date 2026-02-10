# Raw Data Folder

Place your original, unmodified dataset files here.

## Guidelines

1. **Never modify raw data files** - Always create processed versions instead
2. **Document your data source** in the README
3. **Large files** (>100MB) should NOT be committed to GitHub
   - Add them to `.gitignore`
   - Document how to obtain them

## Data Source Documentation

| File | Source | Date Obtained | Description |
|------|--------|---------------|-------------|
| day.csv | Kaggle | 2/9/26 | Daily count of rental bikes between 2011 and 2012 in a bike sharing system containing corresponding weather and seasonal details. Important to note this file does not have variable `hr`. |

| File | Source | Date Obtained | Description |
|------|--------|---------------|-------------|
| hour.csv | Kaggle | 2/9/26 | Hourly count of rental bikes between 2011 and 2012 in a bike sharing system containing corresponding weather and seasonal details.  |

## If Data Cannot Be Shared

If your data is proprietary or too large:
1. Add the filename to `.gitignore`
2. Provide download instructions here
3. Include a small sample file if possible
