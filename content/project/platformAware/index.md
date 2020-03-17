+++
# Project title.
title = "Platform-Aware Synthesis of Embedded Control Software"

# Date this page was created.
date = 2018-11-10T00:00:00

# Project summary to display on homepage.
summary = "There is a large semantic gap between control algorithms - making idealistic assumptions on the implementation platform (e.g., fault-tolarence architecture, memory requirement, data-rate requirement, etc.) - and their actual implementation on concrete platforms. "

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
# tags = ["platformAware"]

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

There is a large semantic gap between control algorithms - making idealistic assumptions on the implementation platform (e.g., fault-tolerance architecture, memory requirement, data-rate requirement, etc.) and their actual implementation on concrete platforms. In this research area, we focus on providing controller code enforcing rich specifications while taking into account the features of the computational platforms.

## Highlights of the proposed results include:
* We proposed a novel approach to design controller that provides safety guarantee on the physical component in the presence of application-level and system-level faults through the full system restart.
* We provide a tool _dtControl_ which provides the memory-efficient, compact, understandable representation and the efficient determinization for the formal symbolic controllers obtained from the state-of-the-art toolboxes SCOTS and UPPAL. It also provides a scheme to design non-uniform quantizers (i.e., state encoders with non-uniform partitioning of state-set) for symbolic controllers. The results are also useful for constructing efficient static coders minimizing bit rate over the sensor-controller channel.
