# Focal Length Shift
We try to simulate a change in focal length for an image with depth map.
Doesn't work due to occlusion.
[test.ipynb](test.ipynb)

## Future work
What you can try is to project image on an object with height defined by depth map and then simulate focal length changed with a 3D rendering engine.

# Dev
- [helpful guide](http://ondata.blog/articles/getting-started-apache-spark-pyspark-and-jupyter-in-a-docker-container/)
- run the command (jupyter is on 8888):
`docker run -p 8888:8888 -p 4040:4040 -v c:/Projects/shifty-focal:/home/jovyan/work --name tf jupyter/tensorflow-notebook`
`docker run -p 8888:8888 -p 4040:4040 -v ~/Documents/GitHub/shifty-focal:/home/jovyan/work --name tf jupyter/tensorflow-notebook`
