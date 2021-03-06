+++
# Project title.
title = "QUEST: A Tool for State-Space Quantization-Free Synthesis of Symbolic Controllers (C++ toolbox)"

# Date this page was created.
date = 2017-11-10T00:00:00

# Project summary to display on homepage.
summary = "QUEST is an open source software tool, developed in C++, for automated controller synthesis for incrementally input-to-state stable nonlinear control systems."

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

QUEST is an open source software tool, developed in C++, for automated controller synthesis for incrementally input-to-state stable nonlinear control systems. The tool contains two major parts:
1. **Construction of symbolic abstraction:** the tool uses state-space quantization-free approach for the construction of symbolic abstraction which can be potentially more beneficial for systems with high-dimensional state spaces.
2. **Symbolic controller synthesis:** the synthesis of controller using fixed point computations, namely, maximal and maximal fixed points, thus natively supports safety and reachability specifications . The tool is intended to be used and extended by researches in the area of formal synthesis for complex systems. 

## Download QUEST
Get latest version of QUEST from github repository [here](https://github.com/PushpakJagtap/QUEST)

## Related publications
1. **P. Jagtap**, M. Zamani (2017). [QUEST: A tool for state-space quantization-free synthesis of symbolic controllers](https://link.springer.com/chapter/10.1007%2F978-3-319-66335-7_21). 14th International Conference on Quantitative Evaluation of SysTems (QEST), Lecture Notes in Computer Science 10503.
