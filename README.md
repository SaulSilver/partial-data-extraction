## How to run

1. clone the repo
2. open the `index.html` file locally
3. Run `extractData()`
4. Observe the magic happens :confetti_ball:

## Solution

1.  Using `document.getElementById('boxes')` or the `boxes` element directly is not allowed
2.  I query for a `title` element then fetch its parents till I reach the boxes nodes
3.  Afterwards, traverse through all the `boxes` children nodes to get the `title` and `subtitle`
