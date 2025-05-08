# Web Scraping and Feature Engineering

### Tasks: Using the provided URL (http://books.toscrape.com/)
1. Use requests and BeautifulSoup to scrape Title, Price, Rating, Availability status for all books on the homepage
2. Save the extracted data into a pandas DataFrame and export it as a CSV file.
3. Clean the data:
  - Convert prices from strings to numerical values (remove symbols like £).
  - Map the ratings (e.g., "Three" = 3, "Five" = 5) to numerical values.

### Feature Engineering:
1. Create a new column categorizing books as "Affordable" (price < £20) or "Expensive" (price ≥ £20).
2. Calculate the average rating for "Affordable" vs. "Expensive" books.
3. Visualize the data:
    - Create a pie chart showing the proportion of affordable vs expensive books.
    - Plot a bar chart of average ratings by category (Affordable vs Expensive).

### Deliverables:
1. The final CSV file containing the scraped data.
2. A Jupyter Notebook with the Python code and a step-by-step explanation.
3. At least two visualisations (e.g., a pie chart for affordability, bar chart for ratings).
