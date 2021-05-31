# Tech Academy - Crappy Google

This is a small backend that returns two results for searches on ```tenet``` and ```react```.

## Installation

- Clone the repository
- Go into the Crappy Google folder
- Install all the dependencies ```npm install```
- Run the server ```npm start```

## Usage

If you go to http://localhost:3000/results/tenet, you'll get
```
{
  "id": "tenet",
  "performance": "0.82 seconds",
  "resultCount": 3,
  "commonQuestions": [
    {
      "body": "What Tenet means??"
    },
    ...
  ],
  "results": [
    {
      "url": "https://www.imdb.com/title/tt6723592/",
      "type": "Main",
      "title": "Tenet (2020) - IMDb",
      "body": "Tenet: Directed by Christopher Nolan. With Juhan Ulfsak, Jefferson Hall, Ivo Uukkivi, Andrew Howard. Armed with only one word, Tenet, and fighting for the ...",
      "visitCount": "You've visited this page many times. Last visit: 5/31/21"
    },
    ...
  ]
}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate???

## License
[MIT](https://choosealicense.com/licenses/mit/)