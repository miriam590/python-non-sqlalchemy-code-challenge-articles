# Welcome to the Phase 3 Code Challenge: Articles!

This project is all about managing articles in a simple and efficient way using Python. Here, you'll find three main characters in our story: `Article`, `Author`, and `Magazine`. Together, they represent the relationships between articles, their authors, and the magazines they grace with their presence.

## Meet the Classes

### Article
- Think of an `Article` as a piece of writing crafted by an author for a magazine.
- **Attributes**:
  - `author`: The talented individual behind the words, represented by an instance of the `Author` class.
  - `magazine`: The publication that showcases the article, represented by an instance of the `Magazine` class.
  - `title`: The name of the article, which must be between 5 and 50 characters long and is immutable (once set, it stays that way!).

### Author
- An `Author` is a creative soul who can write multiple articles for various magazines.
- **Attributes**:
  - `name`: The author's name, which must be longer than 0 characters and cannot be changed once set.
  - `_articles`: A collection of articles penned by the author.
  - `_magazines`: A unique set of magazines the author has contributed to.

### Magazine
- A `Magazine` is a platform that publishes a variety of articles.
- **Attributes**:
  - `name`: The magazine's name, which should be between 2 and 16 characters long.
  - `category`: The genre of the magazine, which must be a non-empty string.
  - `_articles`: A list of articles that have been published in the magazine.
  - `_authors`: A unique set of authors who have written for the magazine.

## How to Use This System
To get started, simply create instances of `Author`, `Magazine`, and `Article` to establish their relationships. The system is designed to enforce rules, ensuring that all attributes are valid.

## Testing the Waters
We've included unit tests for each class to make sure everything works as it should. You can run the tests using `pytest` to verify the implementation.

## Getting Started
To install the necessary dependencies, run:
```
pip install -r requirements.txt
```

## Running the Tests
To check if everything is functioning correctly, use:
```
pytest
```

Feel free to dive in and explore the code! Happy coding!
