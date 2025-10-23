# LLM Generated App

        This app was automatically generated based on the following brief:

        You are given two attachments: execute.py and data.xlsx.

- Commit execute.py after fixing the non-trivial error in it.
- Ensure it runs on Python 3.11+ with Pandas 2.3.
- Convert data.xlsx to data.csv and commit it.
- Add a GitHub Actions push workflow at .github/workflows/ci.yml that:
  - Runs ruff and shows its results in the CI log
  - Runs: python execute.py > result.json
  - Publishes result.json via GitHub Pages
- Do not commit result.json; it must be generated in CI.

        ## Summary
        This app fulfills the brief using a minimal web interface. It runs on GitHub Pages with client-side JS.

        ## Files
        - index.html
        - execute.py
- data.xlsx

        ## Usage
        Open the deployed GitHub Pages URL in a browser.
        If the app supports `?url=` parameter, pass your URL like:
        `?url=https://example.com/data.json`

        ## Code Explanation
        All app logic is inside `index.html` (inline JS).

        ## License
        MIT License
        