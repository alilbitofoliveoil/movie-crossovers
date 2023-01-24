# IMDb Movie-Crossover 

As a small troll, I made a quick one-liner script that generates movie crossover ideas from IMDb. A small sampling of the absolute goldmine of ideas I uncovered:
```
Blue's Clues + Kill Bill: Vol. 2
Curious George + Hot Fuzz
Dora the Explorer + Bad Boys II
Alvin & the Chipmunks + Terminator 3: Rise of the Machines
Teenage Mutant Ninja Turtles + 300
Doctor Who + Attack on Titan
The Mandalorian + The Last of Us
```

## Usage
- Navigate to the [IMDB Genres Page](https://www.imdb.com/feature/genre/) or any other list the piques your interest in the latest Chrome or Edge web browser.
- Pick 2 movie genres that would make for interesting crossovers, note them.
- Navigate to the first of your two movie genre pages in the browser.
- Open your browser's development tools by pressing the `F12` key.
- Go to the `Console` tab in the developer tools.
- Paste the contents of `./crossovers.js` into the Console window.
- Hit the return key to run the code.
- Your browser will prompt you to enter a url for a different IMDb page. Find the url of the *second* of your two movie genre pages, and paste it into the prompt. Click OK.
- Wait for the program to complete, and then click the blob uri it generates to view the results. It should start with `blob:https://...`.

## Limitations
- Does not support pagination and doesn't make use of the API.
- Some characters will not output correctly right now. ¯\\_(ツ)_/¯
