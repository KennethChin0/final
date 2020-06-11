# Final
### Kenneth Chin (Period 10) and Michael Lin (Period 4)

#### Features to be implemented
- light
    - Add a light to the symbol table
    - MDL Commands:
        - light lightname x y z r g b
        - creates a light at the point x y z using the given r g b
- mesh
    - use an external .obj file for polygons
    - MDL Commands: 
        - mesh :filename
        - utilizes coordinates from .obj file to create an image
- set
    - assigns a value to a knob
    - MDL Commands:
        - set knobname value
        - assigns a knob value to knobname in the symbol table
- save knobs
    - saves current knob values to a list
    - MDL Commands:
        - save_knobs knoblist
        - saves the current value of knobs under list, knoblist
- tween
    - produce an animation by going between two knob lists
    - MDL Commands:
        - tween start_frame end_frame knoblist0 knoblist1
        - generates a number of frames using basename
			  as the base filename. It will start from
			  start_frame and end at end_frame and
			  interpolate the image using knoblist0 as
			  the starting configuration and knoblist 2
			  as the ending configuration.
- save_coordinate_system
    - save a copy of the top of the stack to the symbol table
    - MDL Commands:
        - save_coord_system name
        - Makes a copy of the top of the stack and
			  saves it in the symbol table under "name."
#### If we have time
- Add new primitive shapes
    - Pyramid
    - Tetrahedron
    - Cone
    - Cylinder
