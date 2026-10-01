---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
hide_title: true
---
<style>
.publications-page li {
  font-size: 0.85em;
  line-height: 1.35;
}

@media (min-width: 1024px) {
  .publications-page {
    width: calc(100% + 80px);
    max-width: none;
  }
}
</style>

<div class="publications-page" markdown="1">

## Preprints

<ol reversed class="publication-list">
  <li>Eigenvalue optimization via a first-variation formula. 2026. <a href="https://arxiv.org/abs/2606.31869">arXiv</a>.</li>
  <li>Geometric bounds for Steklov and weighted Neumann eigenvalues on Euclidean domains. 2026. <a href="https://arxiv.org/abs/2604.03418">arXiv</a>.</li>
  <li>Maximizing higher eigenvalues in dimensions three and above. 2025. <a href="https://arxiv.org/abs/2506.09328">arXiv</a>.</li>
</ol>

## Published and accepted papers

<ol reversed class="publication-list">
<li>Eigenvalue optimization in higher dimensions and \(p\)-harmonic maps. <strong>Geom. Funct. Anal.</strong> 36.4 (2026), pp. 1244–1293. <a href="https://doi.org/10.1007/s00039-026-00751-3">doi</a> | <a href="https://rdcu.be/6DM9sGh2TbYa">sharedIt</a> | <a href="https://arxiv.org/abs/2601.17896">arXiv</a>.</li>

<li>Conformal optimization of eigenvalues on surfaces with symmetries. <strong>J. Lond. Math. Soc.</strong> 112.6 (2025), e70386. <a href="https://doi.org/10.1112/jlms.70386">doi</a> | <a href="https://arxiv.org/abs/2502.03756">arXiv</a>.</li>

<li>(with M. Karpukhin) The first eigenvalue of the Laplacian on orientable surfaces. <strong>Math. Z.</strong> 301.3 (2022), pp. 2733–2746. <a href="https://doi.org/10.1007/s00209-022-03009-4">doi</a> | <a href="https://rdcu.be/KycWC68WQfca">sharedIt</a> | <a href="https://arxiv.org/abs/2106.00627">arXiv</a>.</li>
</ol>

</div>

<script>
  const lists = [...document.querySelectorAll(".publication-list")];

  let number = lists.reduce(
    (total, list) => total + list.children.length,
    0
  );

  lists.forEach(list => {
    list.start = number;
    number -= list.children.length;
  });
</script>
