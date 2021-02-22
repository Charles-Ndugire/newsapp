# The Daily News.
#### An application that allows users to list and preview news articles from various sources all around the world , 19/02/2021.

## Author

[Charles-Ndugire](https://github.com/Charles-Ndugire)
## Description
The application consumes the [NewsAPI](https://newsapi.org/) hence the application provides the following functionalities to users:
- View top stories. These are displayed on the landing page in carousel form. Each carousel item has a clickable link that allows the user to read the top story's article.
- Have access to news sources. The user has access to over 50 news sources of various categories. These are displayed on the landing page in card format for each news source.
- Search for articles from all around the world. The user can search for an article by keyword.


## Live link

 Click the [link](https://the-daily-telegram.herokuapp.com/)  to see the site


## User Story

1. A user would see various news sources on the homepage of the application.
2. A user would also be able to select a news source and see all news articles from the selected news source in the application.
3. A user will be able to see the image, description and the time a news article was created from the News-Articles tab.
4. A click on an article and read the full article on the source website.


## Development Installation
To get the code..

1. Cloning the repository:
  ```bash
  git clone https://github.com/Charles-Ndugire/newsapp.git
  ```
2. Move to the folder and install requirements
  ```bash
  cd newsapp
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export API_KEY='{Enter your News Api Key}'
  ```
4. Running the application
  ```bash
  python3.6 manage.py server
  ```
5. Testing the application
  ```bash
  python3.6 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.


## Technology used

* [Python3.6](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)
* HTML 
* CSS


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

If you have any question or contributions, please email me at [ndugirecharles@gmail.com]

## License
* *MIT License:*
* Copyright (c) 2019 **Charles Ndugire**
