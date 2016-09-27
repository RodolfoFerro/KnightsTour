# Knights Tour Problem

Knights Tour solved using Python.

(And graphically with PyGame.)

### Requirements:
- [Python 2.7 or greater](https://www.python.org/)
- [PyGame 1.9.2](http://pygame.org/hifi.html)
- [Numpy](http://www.numpy.org/)

## About

This program was made as part of the very first homework of a course taken back in 2015.
The way the problem was solved is using backtracking and recursion, applying the Wansdorff's rule.

## Running the script

The program won't need any arg variables, but it'll ask you for the dimensions of the board and the initial positions in x and y, in order to begin to compute a solution. The positions are integer values in `[0,N-1]x[0,N-1]`.

To run the script, just open a terminal in the directory where the script and run it by doing:
```bash
python Knights.py
```

(You just have to be sure to have the `knight.png` and `chess.png` files.)

### Constraints:

Of course, some constraints apply to have a solution. If you want a solution, the `N` from the input must be greater than 5. Also, for a graphical tour, `N` must be less than 32.

![Knights Tour](https://github.com/RodolfoFerro/KnightsTour/blob/master/Knights.gif "Knights Tour")
