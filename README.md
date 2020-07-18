# Path-Finding-Visualiser
FORMULA USED
t(x) = s(x) + e(x)

The Goal is to Minimize t(x)

x => current spot
t(x) => total distance of the path including x from start to end
s(x) => distance from start to current
e(x) => shortest distance from current to end

s(x) is calculated by counting the number of squares from start to current
e(x) is the shortest distance between current and end calculated using ((x1+x2)^2 + (y1+y2)^2)^1/2
