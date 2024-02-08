# About

This is the repository for the DS4MH interest group website @ ATI.

## Ackowledgements
This repository is based on the Architect theme.

## How-to
### Previewing the theme locally

If you'd like to preview the theme locally (for example, in the process of proposing a change):

1. Clone down the theme's repository (`git clone https://github.com/pages-themes/architect`)
2. `cd` into the theme's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit [`localhost:4000`](http://localhost:4000) in your browser to preview the theme

### Running tests
The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run `script/cibuild`. You'll need to run `script/bootstrap` once before the test script will work.

### Updating the website
* To add speakers, modify the yaml files under `_data/`.
* To add pages to the header, modify `_data/navigation.yml`.
* To change the pages, modify the markdown files and/or the respective html files under `_layouts/`. This will need to be done whenever there's a new table to generate, etc.