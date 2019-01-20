# Subreddit Explorer

This project uses collaborative filtering (CF) to find similar subreddits. The CF is done using the alternating least squares (ALS) algorithm in PySpark which outputs an item-feature matrix and a user-feature matrix. Item-item similarity is calculated using the item-feature matrix.

## Getting Started

If you have Jupyter Notebook and PySpark installed on your machine, you can simply clone this repository and open the notebook. The only data needed is provided in the CSV file.

### Prerequisites

Jupyter Notebook - See https://jupyter.org/ for instructions. <br>
PySpark - Please refer to instructions for your operating system.

## What is a Subreddit?

A Subreddit is a forum dedicated to a specific topic on the social media website https://www.reddit.com. According to Amazon Alexa, Reddit.com is the 5th most visited website in the US (as of January 2019). Its users post approximately three million comments per day.

## Web Application

This project is available online at: http://www.apexquery.com <br>
The web application gives results generated using 97 million comments from September 2018.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
