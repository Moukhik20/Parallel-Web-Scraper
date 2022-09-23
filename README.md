# Parallel-Web-Scraper
Parallel Web Scraper implemented in python that can scrape images of various keywords from Google Images. Uses parallel processing techniques to ensure efficient web scraping and downloading of images (Both directly from Google Images as well as high quality from source website)
Instructions for use:
1. Download latest version of Chromedriver or use the one provided with the code.
2. Install required python modules.
3. Put required keywords in keywords.txt
4. Usage: python main.py [--threads 10] [--full false] [--limit 0]
threads: Defines the number of threads to be used
full: Download full resolution image from source
limit: Limit number of downloads
