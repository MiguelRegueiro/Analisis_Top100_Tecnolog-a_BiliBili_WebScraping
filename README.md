# Analysis of the Top 100 Most Popular Technology Videos on BiliBili 🖥️📊

This project analyzes the top 100 most popular videos in the technology category on BiliBili, one of the leading video platforms in China. **Web scraping** is used to collect the data, and **Python** is used for processing and analysis.

## Description 📄

The goal of this project is to analyze the behavior of the most-viewed technology videos on BiliBili, extracting information such as:

- Video titles.
- Number of views, likes, and comments.
- Publication date.
- Common categories and tags.

The data was obtained using **web scraping** techniques with **BeautifulSoup** and **Requests**. Subsequently, the data was analyzed in a **Jupyter Notebook**, where visualizations and descriptive statistics were performed.

## Project Structure 📂

- **BiliBili_Project.ipynb**: Jupyter Notebook with the complete analysis.
- **requirements.txt**: File containing the dependencies required to run the project.
- **README.md**: This file, with the project description and instructions.

## Tools Used 🚧

- **Python**: Main language for scraping and analysis.
- **Jupyter Notebook**: For developing the analysis interactively.
- **BeautifulSoup**: For extracting data from BiliBili pages.
- **Requests**: For making HTTP requests and obtaining the HTML.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For visualizations.

## Installation Instructions ⚙️

To run this project in your own environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook BiliBili_Project.ipynb
   ```

## Results 🏆

The analysis provides insights on:

- The most popular topics in technology videos.
- The relationship between video duration and the number of views.
- User behavior in terms of likes, comments, and shares.

## Next Steps 🚀

- Expand the analysis to include other popular categories on BiliBili.
- Implement more scraping techniques to collect additional data such as video descriptions or highlighted comments.
- Automate the scraping process to update the data regularly.

## Contributions 🤝

Contributions are welcome. If you have suggestions, improvements, or find any issues, feel free to open an issue or submit a pull request.

## License 📜

This project is licensed under the MIT License. See the `LICENSE` file for details.
