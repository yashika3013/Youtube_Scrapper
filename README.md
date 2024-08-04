# YouTube Video Data Scraper

A Python script to scrape YouTube video data such as views, upload date, and likes, from a list of video links provided in a CSV file.

## Requirements

- Python 3.x
- pandas
- BeautifulSoup
- selenium
- WebDriver for your browser (e.g., ChromeDriver)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the WebDriver for your browser and ensure it's in your PATH. For Chrome, you can download it from [here](https://sites.google.com/a/chromium.org/chromedriver/).

## Usage

1. Ensure you have a CSV file named `youtube.csv` with the following columns:
    - `title`
    - `duration`
    - `video_link`

2. Run the script to start scraping:
    ```bash
    python scrape_youtube.py
    ```

3. The script will generate an updated CSV file `youtube_updated.csv` with the additional scraped data.

## License

This project is licensed under the MIT License.
