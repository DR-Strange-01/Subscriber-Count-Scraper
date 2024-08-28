# Subscriber Count Scraper

This project allows you to scrape the subscriber or follower counts of different social media platforms (Instagram, Twitter, YouTube, TikTok, Facebook, etc.) using RapidAPI or web scraping techniques. The scraper is built with Python and utilizes libraries like `http.client`, `requests`, and `selenium` for different approaches to retrieve subscriber counts.

## Features

- **Instagram, Twitter, TikTok, Facebook API Integration:** Fetches follower counts using RapidAPI.
- **YouTube API Integration:** Retrieves live subscriber counts from Socialcounts.org.
- **Web Scraping Support:** Uses `BeautifulSoup` (`bs4`) or `Selenium` to scrape follower counts directly from websites.
- **Flexible and Modular Code:** Easily extendable to include more platforms or switch APIs.

## Table of Contents

1. [Supported Platforms](#supported-platforms)
2. [Installation](#installation)
3. [Usage](#usage)
4. [APIs and Pricing](#apis-and-pricing)
5. [Contributing](#contributing)

## Supported Platforms

- **Instagram:** Uses RapidAPI to get the follower count.
- **Twitter:** Supports two different RapidAPI packages to retrieve follower counts.
- **YouTube:** Retrieves live subscriber counts from Socialcounts.org (Free).
- **TikTok:** Provides options to get follower counts via RapidAPI or web scraping.
- **Facebook:** Scrapes follower counts using RapidAPI or direct scraping methods.

## Installation

1. **Clone the repository:**
    ```bash
   git clone https://github.com/yourusername/Subscriber-Count-Scraper.git
    
   cd Subscriber-Count-Scraper

2. **Install required libraries:**
    ```bash
    pip install -r requirements.txt

4. **Set up Selenium:**
   
- Download ChromeDriver or another WebDriver compatible with your browser.
- Set the path to the driver in the script as required.


## Usage

### API-based Approach:

1. Obtain API keys from RapidAPI and replace them in the script.
2. Run the script for the specific platform you want to fetch data from.

### Web Scraping Approach:

1. Ensure you have `Selenium` and `BeautifulSoup` installed.
2. Set up the WebDriver for your preferred browser (e.g., `ChromeDriver`).
3. Run the web scraping script for the platform you are targeting.

## APIs and Pricing

- **RapidAPI:** Provides access to several APIs for Instagram, Twitter, TikTok, and Facebook follower counts. Prices may vary depending on the API package.
- **Socialcounts.org API:** Free API for retrieving YouTube subscriber counts.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the Branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License

Distributed under the MIT License. See `LICENSE` for more information.
