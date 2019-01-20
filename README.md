# Subreddit Explorer

This project uses collaborative filtering (CF) to find similar subreddits. The CF is done using the alternating least squares (ALS) algorithm in PySpark which outputs an item-feature matrix and a user-feature matrix. Item-item similarity is calculated using the item-feature matrix.

## Getting Started

If you have Jupyter Notebook and PySpark installed on your machine, you can simply clone this repository and open the notebook. The only data needed is provided in the CSV file.

### Prerequisites

Jupyter Notebook - See https://jupyter.org/ for instructions. <br>
PySpark - Please refer to instructions for your operating system.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
