-8   1.0   0 #shape fitting changes, in meters and Cartesian coord
1   0.01     20   1.0   1.0   #1cm,    40 divs, even spaced- 1st length of base x
2   0.005    10   1.0   1.0   #0.42cm, 10 divs, even spaced- 2nd length of base x
3   0.00375   7   1.0   1.0   #0.375cm, 7 divs, even spaced, 2nd length of al y
4   0.0025    5   1.0   1.0   #0.25cm,  5 divs, even spaced, length in z
-8 #marks
0   0.0   0.005   0.0   #mark 0 x=0,y=0,z=0
1   1     3     4     #x-span 1, y-span 3, z-span 4
2   2     0     0     #x-span 2, 
-8 #zones are next
0  1    0   1    0  1    1   #between zone 0 and 1 in x,1 and 2 in y, 0 and 1 in z- aluminium
1  2    0   1    0  1    2
-8 #surface patches definition
 -3  1    1   #patch 1 is low y; all other will become patch 2 automatically
-8 #material
1   2   #Zone 1 is material 2
2   2
-8 #deformations p patches
2  1  1    20    0.  0.0005  0.    2  3  7 #plane 2 in x, plane 1 in y, plane 1 in z, indiv point, point patch 2 in x (default), point patch 3 in y (default), point patch 7 in z
2  1  0    20    0.  0.0005  0.    2  4  7 #plane 2 in x, plane 1 in y, plane 0 in z, indiv point, point patch 2 in x (default), point patch 3 in y (default), point patch 7 in z
2  0  1    20    0.  0.0005  0.    2  3  7 #plane 2 in x, plane 1 in y, plane 1 in z, indiv point, point patch 2 in x (default), point patch 3 in y (default), point patch 7 in z
2  0  0    20    0.  0.0005  0.    2  4  7 #plane 2 in x, plane 1 in y, plane 0 in z, indiv point, point patch 2 in x (default), point patch 3 in y (default), point patch 7 in z
-8
