There are two versions to this project: alpha and beta.
The alpha version uses a slower algorithm to check for wins that calculates which winning paths contain the clicked square and checks if they are a winning path.
The beta version uses a quicker algorithm that generates a list of every path and connects each square to its respective paths. Thus, when clicked, the checker only needs to check the connected paths.

While the algorithm works in any dimension, the graphics only support up to dimension 5.
To change the dimension or size, simply edit the line:

var game = new game(DIMENSION, SIZE)
