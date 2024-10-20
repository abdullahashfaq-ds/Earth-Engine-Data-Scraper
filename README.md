# Earth Engine Data Scraper

This repository contains a Python based web scraper designed to extract dataset metadata from the [Google Earth Engine Datasets Catalog](https://developers.google.com/earth-engine/datasets/catalog). It can be utilized for data gathering in research, analysis, or integration into larger systems related to environmental or geospatial data exploration.

## Features

- Scrapes dataset information from multiple pages of the Google Earth Engine Datasets Catalog.
- Extracts detailed metadata, including:
  - Dataset title
  - Availability information
  - Provider name and URL
  - Associated tags
  - Table values, when available
- Outputs the scraped data in a structured format for easy access and further analysis.

## Installation

To set up and run the scraper, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone git@github.com:abdullahashfaq-ds/Earth-Engine-Data-Scrapper.git
    cd Earth-Engine-Data-Scrapper
    ```

2. **Create and Activate a Virtual Environment**

    ```bash
    python -m venv venv
    
    # For Windows, use:
    venv\Scripts\activate
    
    # For macOS/Linux, use:
    source venv/bin/activate
    ```

3. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Scraper**

   The scraper logic is implemented in a Jupyter notebook located in the `Notebooks` directory. Open it with Jupyter Lab or Jupyter Notebook, and execute the cells to initiate the scraping process.

## Note

If you see an unverified signature in the commits, no worries—I've just misplaced my GPG key!

## License

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.
