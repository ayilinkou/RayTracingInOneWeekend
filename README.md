# RayTracingInOneWeekend

An offline software ray tracer built upon the foundations of the [Ray Tracing in One Weekend](https://raytracing.github.io/) book series.

The project was extended beyond the book series through the introduction of multithreading using std::async. This alone decreased the render time by 88%.

Features of this ray tracer include:
- materials with properties which determine how rays should be reflected/refracted
- antialiasing with MSAA
- depth of field

![RenderImage](Renders/render4k.png)
