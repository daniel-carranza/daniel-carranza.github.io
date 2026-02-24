---
title: "Publications"
permalink: /publications/
author_profile: true
---
1. <em>Discrete homotopy hypothesis for n-types</em>, with C. Kapulkin, submitted, 2026 <a href="https://arxiv.org/abs/2602.19293">[arXiv]</a>
1. <em>Cubical models of ∞-presheaves and the Bousfield-Kan formula</em>, with K. Arakawa and C. Kapulkin, submitted, 2025. <a href="https://arxiv.org/abs/2511.12809">[arXiv]</a>
1. <em>Derived mapping spaces of ∞-categories</em>, with K. Arakawa and C. Kapulkin, submitted, 2025. <a href="https://arxiv.org/abs/2509.10288">[arXiv]</a>
1. <em>Categorical foundations of discrete dynamical systems</em>, with C. Kapulkin, N. Kershaw, R. Laubenbacher, and M. Wheeler, submitted, 2025. <a href="https://arxiv.org/abs/2506.05190">[arXiv]</a>
1. <em>Nonexistence of colimits in naive discrete homotopy theory</em>, with C. Kapulkin and J. Kim, Appl. Categ. Structures 31 (2023), no.5, 41, 6 pp. <a href="https://arxiv.org/abs/2306.02219">[arXiv]</a> <a href="https://link.springer.com/article/10.1007/s10485-023-09746-9">[ACS]</a>
1. <em>Calculus of Fractions for Quasicategories</em>, with C. Kapulkin and Z. Lindsey, submitted, 2023. <a href="https://arxiv.org/abs/2306.02218">[arXiv]</a>
1. <em>Diagonal Lemma for Presheaves on Eilenberg-Zilber Categories</em>, with C. Kapulkin and L.-Z. Wong, Theory Appl. Categ. 44 (2025), Paper No. 11, 326-343. <a href="https://arxiv.org/abs/2306.02217">[arXiv]</a>
1. <em>Cofibration category of digraphs for path homology</em>, with B. Doherty, C. Kapulkin, M. Opie, M. Sarazola, and L.-Z. Wong, Algebr. Comb. 7 (2024), no. 2, 475–514. <a href="https://arxiv.org/abs/2212.12568">[arXiv]</a> <a href="https://alco.centre-mersenne.org/articles/10.5802/alco.341/">[ALCO]</a>
1. <em>The Hurewicz theorem for cubical homology</em>, with C. Kapulkin and A. Tonks, Math. Z. 305, 61 (2023), 20 pages. <a href="https://arxiv.org/abs/2207.12500">[arXiv]</a> <a href="https://link.springer.com/article/10.1007/s00209-023-03352-0">[Math.Z.]</a>
1. <em>Cubical setting for discrete homotopy theory, revisited</em>, with C. Kapulkin, Compos. Math., 160, no. 12 (2024), 2856–2903. <a href="https://arxiv.org/abs/2202.03516">[arXiv]</a>
1. <em>Homotopy groups of cubical sets</em>, with C. Kapulkin, Expo. Math. 41 (2023) 125518, no. 4, 55 pp. <a href="https://arxiv.org/abs/2202.03511">[arXiv]</a> <a href="https://www.sciencedirect.com/science/article/pii/S0723086923000944">[Expo.Math.]</a>
1. <em>2-adjoint equivalences in homotopy type theory</em>, with J. Chang, C. Kapulkin, and R. Sandford, Log. Methods Comput. Science 17 (2021), no. 1, Paper No. 3, 9 pp. <a href="https://arxiv.org/abs/2008.12433">[arXiv]</a> <a href="https://lmcs.episciences.org/7124">[LMCS]</a>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}