# Tidy Data Rulebook
This is a list of best practices and a compilation of the most common mistakes when we collect, store, and deliver data for further analysis and visualization. It’s inspired and broadly based on the excellent paper Tidy Data (http://www.jstatsoft.org/v59/i10) by Hadley Wickham as well as our own experience at Interactive Things while working with clients on data-driven design projects.

## Data Structure Best Practices
- Each variable forms a column.
- Each observation forms a row.
- Each type of observational unit forms a table.

## Common Data Structure Defects
- Column headers are values, not variable names.
- Multiple variables are stored in one column.
- Variables are stored in both rows and columns.
- Multiple types of observational units are stored in the same table.
- A single observational unit is stored in multiple tables.

## Spreadsheet Best Practices
- Format data standardized and consistent (like dates and currencies).
- Keep table headers standardized and consistent (lowercase, underscored).
- Keep file names standardized and consistent.
- Deliver your spreadsheets as CSV files instead of XLS files.
- Deliver your spreadsheets as UTF-8 formatted.

## Common Spreadsheet Defects
- Introductory and other unnecessary text.
- Missing column header.
- Multiple column header lines.
- Comments in columns where values should be.
- Formatting on text and background of cells.
- Empty columns and rows for layout purposes.
- Connected cells between spreadsheets.
- Formulas to transform values in cells.
- Auto-formatting of values in cells (like dates and currencies).
- Hidden columns (either show them when necessary or delete them).
- Multiple tables on one spreadsheet.


## Additional Resources
- http://vita.had.co.nz/papers/tidy-data.pdf
- http://kb.tableau.com/articles/knowledgebase/preparing-excel-files-analysis
