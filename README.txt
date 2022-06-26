There are two zip files for the experimental code for article - A Dynamic Fusion Method Using Fast Guided Sampling and Dynamic Constraints

Static map planning
1.You can select the "Static Complex Map" file in the FGSDC Code folder and click to run "DWA_rong.m".
2.After the global path planning is complete, you can right-click and left-click to set two static obstacles to start local planning.
3.If you want to change the environment map, you can set up your own obstacles.
4.If unknown static obstacles cannot be avoided during local planning, it means that the radius of obstacles set for conflict determination is too small, and you can increase it appropriately.

Dynamic map programming
1.You can select the "Dynamic Complex Map" file in the FGSDC code folder and click to run "Ant_DWA.m".
2.After the global path planning is completed, click the mouse to select the running track of dynamic obstacles, and then set static obstacles to start local planning.
3.If the path of the dynamic obstacle conflicts with the static obstacle, you can set the map in "Astar. m".
