A Python package for three-dimensional geometry.

Software tools for CMS

Installation

Run

python -m pip install -e ".[dev]"

to install pygeo and all dependencies required for local development.

Testing

Run

pytest tests

to run all the tests for pygeo.

Tasks

Implement the missing Ray class. A ray may be represented as its origin and a direction.

Implement an __init__ method that takes the origin and direction as argument and stores them as attributes on the instance.

Implement a __repr__ method.

Implement an __eq__ method that works by comparing both the origin and direction of the other ray. Provide tests for this method.

Implement the missing Sphere class. A sphere may be represented by its center and a radius.

Implement an __init__ method that takes the center and radius as argument and stores them as attributes on the instance.

Implement a __repr__ method.

Implement an __eq__ method that works by comparing both the center and radius of the other sphere. Provide tests for this method.

Implement the missing _intersect_ray_and_sphere function. You may follow this article, but keep in mind that for a ray the parameter d mentioned in the article must be larger or equal to zero. Provide tests for this method.

As an optional extra exercise, implement

the missing Triangle class,

the missing _intersect_ray_and_triangle function and accompanying tests, and

the missing intersect that calls either _intersect_ray_and_sphere or _intersect_ray_and_triangle depending on the arguments.