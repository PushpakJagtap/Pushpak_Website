+++
title = "Formal synthesis of stochastic systems via control barrier certificates"
date = 2020-03-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["P. Jagtap", "S. Soudjani", "M. Zamani"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "_IEEE Transactions on Automatic Control(TAC),_( Conditionally accepted)"
# publication_short = "In *ACC*"

# Abstract and optional shortened version.
# abstract = "We study formal synthesis of control policies for discrete-time stochastic control systems against complex temporal properties. Our goal is to synthesize a control policy for the system together with a lower bound on the probability that the system satisfies a complex temporal property. The desired properties of the system are expressed as a fragment of linear temporal logic (LTL), called safe-LTL over finite traces. We propose leveraging \emph{control barrier certificates} which alleviate the issue of the curse of dimensionality associated with discretization-based approaches existing in the literature. We show how control barrier certificates can be used for synthesizing policies while guaranteeing lower bounds on the probability of satisfaction for the given property. Our approach decomposes negation of the specification into sequential reachabilities and then finds control barrier certificates for computing upper-bounds on the reachability probabilities. Control policies associated with these barrier certificates are then combined as a hybrid control policy for the concrete system that guarantees a lower bound on the probability of satisfaction of the property. We distinguish uncountable and finite input sets in the computation of barrier certificates. For the former, control barrier certificates can be computed using sum-of-square optimization. For the latter, we develop a computational method based on counter-example guided inductive synthesis. We demonstrate the effectiveness of the proposed approach on a room temperature control and lane keeping of a vehicle modeled as a four-dimensional single-track kinematic model. We compare our results with the discretization-based methods in the literature."
# Is this a selected publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
# tags = ["Switched Systems","Predictive Control","Time delayed Systems"]

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1905.04585"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Taken from paper: [**Figure**]()"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
