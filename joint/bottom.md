-9   1.0   0 #shape fitting changes, in meters and Cartesian coord
1   0.01     20   1.0   1.0   #1cm,    40 divs, even spaced- 1st length of base x
2   0.005    10   1.0   1.0   #0.42cm, 10 divs, even spaced- 2nd length of base x
3   0.005    10   1.0   1.0   #0.5cm,  10 divs, even spaced, 1st height of si 
4   0.0025    5   1.0   1.0   #0.25cm,  5 divs, even spaced, length in z
-9 #marks
0   0.0   0.0   0.0   #mark 0 x=0,y=0,z=0
1   1     3     4     #x-span 1, y-span 3, z-span 4
2   2     0     0     #x-span 2,
-9 #zones are next
0  1    0  1    0  1    1   #between zone 0 and 2 in x,0 and 1 in y, 0 and 1 in z- #silicon zone
1  2    0  1    0  1    2
-9 #surface patches definition
 -4  1    1   #patch 1 is top y
-9 #material
1   1   #Zone 1 is material 1
2   1   #Zone 2 is material 1
-9
