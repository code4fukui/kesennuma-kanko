# Kesennuma Tourist Map

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple web application that displays tourist spots in Kesennuma, Japan on an interactive map. This project visualizes open data from Kesennuma City, showing each location on a map and providing its details in a table view.

## Demo

**Live demo: https://github.com/code4fukui/kesennuma-kanko

## Features

-   **Interactive Map**: Displays tourist locations on a map of Kesennuma.
-   **Detailed Information**: Click on a map pin to view details for each spot, including name, hours, and fees.
-   **Data Table**: Presents the raw data in a sortable table format directly below the map.
-   **Static Site**: Runs entirely in the browser with no backend required.

## How It Works

This application is a single `index.html` file that uses modern Web Components to render the map and data table from a local CSV file.

-   **`<csv-map>`**: A component from [Code for Fukui](https://github.com/code4fukui/csv-map) for displaying CSV data on a map.
-   **`<csv-viewer>`**: A component from [Code for Sabae](https://github.com/code4sabae/js) for displaying CSV data in an HTML table.

## Data Source

This project utilizes the "Tourist Facility Information" dataset provided by the [Kesennuma City Open Data Library](https://www.kesennuma.miyagi.jp/sec/s021/010/020/130/20200218174617.html#sightseeing).

A copy of the data is included in this repository as `20220701_kankou_shisetsu.csv`.

## Getting Started

As this is a static website, you can run it locally without any build steps.

1.  Clone the repository:
    ```bash
    git clone https://github.com/code4fukui/kesennuma-kanko.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd kesennuma-kanko
    ```
3.  Open the `index.html` file in your web browser.

The site is automatically deployed to GitHub Pages on every push to the `main` branch.

## License

This project is available under the [MIT License](LICENSE).