+++
title = "Solving a 676-Bit Discrete Logarithm Problem in $GF(3^{6n})$"
date = "2012-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Takuya Hayashi","Naoyuki Shinohara","Lihua Wang","Shin'ichiro Matsuo"," Masaaki Shirase","Tsuyoshi Takagi"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "IEICE Transactions of Fundamentals, 95A-1 (January 01, 2012): 204-212"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Pairings on elliptic curves over finite fields are crucial for constructing various cryptographic schemes. The ηT pairing on supersingular curves over $GF(3^n)$ is particularly popular since it is efficiently implementable. Taking into account the Menezes-Okamoto-Vanstone attack, the discrete logarithm problem (DLP) in $GF(3^{6n})$ becomes a concern for the  security of cryptosystems using ηT pairings in this case. In 2006, Joux and Lercier proposed a new variant of the function field sieve in the medium prime case, named JL06-FFS. We have, however, not yet found any practical implementations on JL06-FFS over $GF(3^{6n})$. Therefore, we first fulfill such an implementation and we successfully set a new record for solving the DLP in $GF(3^{6n})$, the DLP in GF(3^{6·71}) of 676-bit size. In addition, we also compare JL06-FFS and an earlier version, named JL02-FFS, with practical experiments. Our results confirm that the former is several times faster than the latter under certain conditions."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

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