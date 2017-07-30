# Pac-man-Ray-Tracer

A computer graphics project that uses a basic ray tracer to render a scene using ray casting and the Phong shading model. The intersections of cylinders, spheres and squares/rectangles were calculated and programmed, along with shadows and reflections. Anti-aliasing and area light sources were also implemented. 

An initial framework was given where missing code fragments were filled to meet project requirements. The final scene was individually created and rendered using the framework as a base. 

The program can be run using the command line in a linux enviroment. When in the file directory, the following commands will produce the final_scene.ppm render in rendered_scenes folder:

./compile.sh

./RayTracer 1024 7 0 final_scene.ppm
