# Ray Tracing in One Week 
# 1.Author github page
`https://github.com/RayTracing/raytracing.github.io/`
---
# 2.Image Output 
![Output](/RayTracingKnowledge/RayTracingInOneWeek/BasicRayTracer/images/ppmExample.png?raw=true)


`inOneWeekend.exe > image.ppm`

Note: `Irfan view` or something that can open this file format is needed !

---
# 3.The vec3 Class

2 Classes added
- vec3 (operations)
- color

---
# 4.Rays, a Simple Camera, and Background

Ray moves based on variable `t => Vec(t)` changes position

Ray class implementation

Important steps:
1. Calculating the path of the ray from the eye(camera) to the pixel
2. Object collision (with our vectors)
3. Update colors of the pixels

![Visualization](https://github.com/eska5/RayTracingKnowledge/blob/main/RayTracingInOneWeek/BasicRayTracer/images/focalPoint.png?raw=true)

Dictionary:
- `linear interpolation, linear blend`: method of curve fitting using linear polynomials to construct new data points within the range of a discrete set of known data points.
- `Focal length`:
The distance between the optical center of a lens or mirror to its focal point

or

The distance from the optical center of a lens or curved mirror to the point where light rays from a very distant object converge.

---
# 5.Adding a Sphere

`Let’s add a single object to our ray tracer. People often use spheres in ray tracers because calculating whether a ray hits a sphere is pretty straightforward.`

![Visualization](/RayTracingKnowledge/RayTracingInOneWeek/BasicRayTracer/images/redSphere.png?raw=true)

---
# 6.Surface Normals and Multiple Objects

Adding Hittable Class !

Dictionary:
- `Normal vector`: In geometry, a normal is an object such as a line, ray, or vector that is perpendicular to a given object.

![Directions](/RayTracingKnowledge/RayTracingInOneWeek/BasicRayTracer/images/possibleDirections.png?raw=true)

Determining from where the ray comes from is crucial (for objects that render differently on each side)

Added Hittable list and rtweekend !

Hard chapter, so output for comparison:
![chapter 6 Summary](/RayTracingKnowledge/RayTracingInOneWeek/BasicRayTracer/images/chapterSixSummary.png?raw=true) 

---
# 7.Antialiasing

---
# 8
# 9
# 10
# 11
# 12
# 13