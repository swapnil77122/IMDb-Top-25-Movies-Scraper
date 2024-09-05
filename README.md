

# IMDb Top 25 Movies Scraper

This project scrapes the top 25 movies from IMDb using Python and the BeautifulSoup library. The scraper retrieves essential details such as movie title, rank, release year, and IMDb rating.

## Features

- Extracts the top 25 movies from the IMDb website.
- Collects movie details, including:
  - Movie Title
  - Rank
  - Release Year
  - IMDb Rating
- Exports the collected data into a structured format (e.g., CSV, JSON).

## Requirements

To run this project, you need the following installed on your system:

1. **Python 3.x** - [Download Python](https://www.python.org/downloads/)
2. **BeautifulSoup** and **Requests** Libraries for web scraping. You can install them using pip:

   ```bash
   pip install beautifulsoup4
   pip install requests
   ```

3. (Optional) **Pandas** for exporting data to CSV:

   ```bash
   pip install pandas
   ```

## Installation and Setup

1. **Clone the repository or download the project files**:

   ```bash
   git clone https://github.com/your-username/imdb-top-25-scraper.git
   ```

2. **Install the required Python libraries** by running the following command:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Python script**:

   ```bash
   python imdb_top_25_scraper.py
   ```

4. The script will scrape the top 25 movies from IMDb and display the details or export them to a file (depending on the script functionality).

## How It Works

1. **Request the IMDb page**: The script sends a request to IMDb's Top 250 movies page.
2. **Parse the HTML**: Using BeautifulSoup, it parses the HTML and extracts the required movie details such as title, rank, release year, and rating.
3. **Store the Data**: The extracted data is either displayed in the terminal or stored in a CSV or JSON file for further use.

## Example Output

After running the script, you will get the following information for the top 25 movies:

| Rank | Title           | Year | Rating |
|------|-----------------|------|--------|
| 1    | The Shawshank Redemption | 1994 | 9.3 |
| 2    | The Godfather   | 1972 | 9.2   |
| ...  | ...             | ...  | ...    |

## Customization

You can modify the code to:

- Scrape more movies (e.g., Top 50, Top 100).
- Extract additional details like genre, director, cast, etc.
- Change the output format (e.g., JSON, XML).

## Potential Issues

- **Rate Limiting**: IMDb may block excessive scraping requests. Consider adding time delays between requests to avoid getting blocked.
- **Website Changes**: IMDb may update its website structure, which could break the scraper. In such cases, you'll need to update the scraping logic accordingly.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) - Library for parsing HTML and XML documents.
- [IMDb](https://www.imdb.com/) - Source of the data.
  
Feel free to contribute to this project by submitting issues or pull requests.

---

