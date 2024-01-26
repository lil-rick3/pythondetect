Hello, this is the readme file for my implementation of yolov5, at line 187, there is  
```print(lightArr)```  
This is the light arr and has the format of  
```[((543.5, 9.5), 3), ((249.0, 319.5), 0)]```  
This is an array of tuples. In each tuple, there is a number and another tuple. The tuple is the xy coordinate starting in top left corner.  
The other int value is from 0 to 4, and corresponds to the color, which is goes as 0:r, 1:b, 2:g, y:3  

To run the program, type this into the command line: 
```python detect.py --source 0 --weights 300epoch.pt --agnostic --hide-conf --delay 1``` 
The delay feature allows for the framerate to be slowed down, and the source will be either 0 or 1 depending on if there is a webcam or other camera as a potential source.
