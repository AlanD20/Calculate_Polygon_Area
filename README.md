# Calculate Polygon Area

## Downloading the project
here is the commands to work with.
```
$ git clone https://github.com/AlanD20/Calculate_Polygon_Area.git
$ cd Calculate_Polygon_Area
```
For Windows open `Calculate_Polygon_Area.sln` in Visual Studio. 

For Linux use this command line.
```
$ ./Calculate_Polygon_Area.sln
```
## How the program works?

The program asks for the file that contains polygon area with the following format
```
(direction, length), (direction, length), (direction, length),
```
##### directions are 
`E - East`, `N - North`, `W - West`, `S - South`
##### Lengths can be anything
`33`, `2.8`, `8.2`

#### Here is an example.
```
(S, 25), (E, 7.6), (N, 17.5), (E, 28), (S, 10), (W, 56), (N, 17.5), (E, 20.4), 
```
after the file opened on the program it calculates the total area of the polygon.

## Contribution
Feel free to add new features to the program as much as you wish. I would love to see a better looking of the program and how you will do it.

## License
[GPL-2.0 License](LICENSE)
