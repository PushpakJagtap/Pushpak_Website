+++
# Project title.
title = "Compositional Abstraction-based Synthesis"

# Date this page was created.
date = 2017-01-10T00:00:00

# Project summary to display on homepage.
summary = "As the complexity of constructing symbolic models grows exponentially in the number of state variables in the concrete system, the existing monolithic approaches on the construction of discrete abstractions are unfortunately limited to only lower dimensional control systems."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
# tags = ["Truck Platooning", "Connected & Automated Vehicles"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"

+++

As the complexity of constructing symbolic models grows exponentially in the number of state variables in the concrete system, the existing monolithic approaches on the construction of discrete abstractions are unfortunately limited to only lower dimensional control systems. Motivated by the above limitation, we currently aim at proposing a compositional framework for constructing symbolic models for interconnected control systems. Our methodology is based on a divide-and-conquer scheme. In particular, we first (1) partition the overall concrete system into a number of concrete subsystems and construct discrete abstractions of them individually; (2) then establish a compositional scheme that allows us to construct a discrete abstraction of the overall network using those of individual ones. We also aim at improving the computation time required for the synthesis of controllers by leveraging compositional abstractions.

## Highlights of the proposed results include:
* We propose the notion of approximate composition which allows us to use different types of abstractions for each subsystem.
* We provide compositional construction of abstractions by utilizing the notion of approximate composition.
* We develop an incremental procedure for controller synthesis which helps to reduce the computational complexity while ensuring completeness with respect to the monolithic synthesis.
