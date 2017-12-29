+++
title = "Leakage Resilient Strong Key-Insulated Signatures in Public Channel."
date = "2010-12-13"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Le Trieu Phong", "Shin'ichiro Matsuo","Moti Yung"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = " INTRUST 2010: Lecture Notes in Computer Science 6802, pp. 160-172. Springer Verlag, 2010."
publication_short = ""

# Abstract and optional shortened version.
abstract = "Key-insulation aims at minimizing (i.e., compartmentalizing) the damage of users from key exposures, and traditionally requires a private channel of communication between a user and a semi-trusted party called a helper to refresh the private keys. The configuration is highly suitable to architectures where the signer is a user application and the helper resides in the safer trusted module, yet the user wants to remain in control of the sensitive crypto operation. The private channel employed in the model, while acceptable in some settings, certainly limits the usage of key insulation schemes (in case the user sits across the network from the trusted environment). In 2009, Bellare, Duan, and Palacio (CT-RSA 2009) refined the model of key-insulation by consid- ering public channels (namely, ones controlled by the adversary), and showed how to convert a key-insulated signature scheme from the private channel into the public one, using extra primitives such as key exchange protocols and symmetric encryption. In this paper, we show that the primitives may be redundant in specific cases. In particular, we revisit the original key-insulated signature scheme in the private channel given by Dodis, Katz, Xu, and Yung (PKC 2003), and show that, with a tweak, the scheme can be naturally proved secure in the public channel without any additional primitives. Next we consider the area of leakage resilient cryptographic schemes which has gained much interest recently. In particular, we consider the continual key leakage scenario of our design (which is more general than the model of key exposure), and argue that our proposal, while requiring an added helper component, nevertheless enjoys several advantages over the recent signature scheme of Faust et al. (TCC 2010) with the same purpose of allowing continual leakage. Our design demonstrates how when given a more complex architecture with some parts that are safer than others, a trade-off can be applied, exploiting the safer modules but keeping users in control; further we show how to do it while mitigating the effect of exposures and leakages."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["deep-learning"]

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++