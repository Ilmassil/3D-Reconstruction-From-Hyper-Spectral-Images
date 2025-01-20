# 3D-Reconstruction-From-Hyper-Spectral-Images 
__Final Year Project Master 2 Advanced Electronic System Engineering U-Burgundy__
## Inroduction
__3D model__ is a digital representation of a physical object or scene in three-dimensional space created using specialized technics and software, and consists of a collection of vertices, edges, and faces that define the shape and structure of the object. 3D models can be used in various fields, such as animation, gaming, architecture, engineering, and product design. They allow for visualization, simulation, and manipulation of objects in a virtual environment.
__Photogrammetry__ is the science and technique of making measurements from photographs, especially to create maps, models, or 3D representations of physical objects or environments. It involves the use of photographs taken from different angles to extract accurate geometric data about the shape, size, and position of objects, and defined on __Merriam-Webster dictionary__ as
> “the science of making reliable measurements by the use of photographs and especially aerial photographs (as in surveying)”
[Webster-Definition](https://www.merriam-webster.com/dictionary/photogrammetry)
>
According to __YellowScan__ a leader company in photogrammetry and LIDAR technologies 
>“LiDAR and photogrammetry are two popular technologies for creating 3D maps and models. Because both can produce similar outputs”, “Both are remote sensing technologies. Remote sensing involves capturing information about an object or phenomenon without making physical contact with it”, “Photogrammetry includes several techniques to capture, measure, and interpret photographic images to produce 3D models, maps, and other spatial data”
[YellowScan Definition](https://www.yellowscan.com/knowledge/lidar-vs-photogrammetry-key-differences-and-applications/#:~:text=LiDAR%20stands%20for%20Light%20Detection,maps%2C%20and%20other%20spatial%20data.)
>
In 3D modeling, vertices, edges, and faces (or surfaces) work together to define the shape and structure of a 3D object:
__Vertices__ are individual points in 3D space, each defined by (x, y, z) coordinates. 
__Edges__ are straight line segments that connect two vertices, forming the skeleton of the object. 
__Faces__ (or surfaces) are flat, polygonal areas enclosed by edges, typically formed by triangles or quadrilaterals.

__Point cloud__ is an intermediate step in creating a 3D model. It’s a sparse collection of data points (vertices) in space that represents the surface of the object. However the point cloud does not define the specific structure of the object since these points can be connected in different ways and hence implementing different structures. Therefore, this point cloud is later converted into a mesh during the 3D reconstruction process to implement the object’s geometric structure.

__Mesh__ After processing a point cloud in photogrammetry, the software typically creates a mesh, which connects the vertices of the point cloud to form a continuous surface (typically triangles), on which different textures could be projected giving the visible aspect to the object’s 3D model.

![Project Image](Images/3D-Reconstruction-From-Hyper-Spectral-Images/Electromagnetic-Spectrum_accurate1.png)
