# Extract Results from AlternativeTo.net

This project provides a script for extracting alternative software suggestions from the website [AlternativeTo.net](https://alternativeto.net).

## Files

- `extract-alternative-to-results.js`: This is the main script for extracting software alternatives.
- `LICENSE`: The license file associated with this project.

## Usage

1. Navigate to [AlternativeTo.net](https://alternativeto.net) and use the search bar to look for a software product, such as "SurveyJS".
2. On the results page, click the "Show more [Software] alternatives" button repeatedly until all results are visible.
3. Open the browser DevTools by pressing `F12`.
4. In the console tab, paste the contents of `extract-alternative-to-results.js` and press `Enter`.
5. Once the script finishes running, right-click on the output list in the console and select "Copy string contents" to save the list of alternatives.