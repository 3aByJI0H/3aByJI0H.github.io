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
  <li>Eigenvalue optimization via a first-variation formula. <a href="https://arxiv.org/abs/2606.31869">arXiv</a> (2026).</li>
  <li>Geometric bounds for Steklov and weighted Neumann eigenvalues on Euclidean domains. <a href="https://arxiv.org/abs/2604.03418">arXiv</a> (2026).</li>
  <li>Maximizing higher eigenvalues in dimensions three and above. <a href="https://arxiv.org/abs/2506.09328">arXiv</a> (2025).</li>
</ol>

## Published and accepted papers

<ol reversed class="publication-list">
<li>Eigenvalue optimization in higher dimensions and \(p\)-harmonic maps. <a href="https://doi.org/10.1007/s00039-026-00751-3">Geom. Funct. Anal.</a> 36.4 (2026), pp. 1244–1293. <a href="https://rdcu.be/6DM9sGh2TbYa">sharedIt</a> | <a href="https://arxiv.org/abs/2601.17896">arXiv</a>.</li>

<li>Conformal optimization of eigenvalues on surfaces with symmetries. <a href="https://doi.org/10.1112/jlms.70386">J. Lond. Math. Soc.</a> 112.6 (2025), e70386. <a href="https://arxiv.org/abs/2502.03756">arXiv</a>.</li>

<li>(with M. Karpukhin) The first eigenvalue of the Laplacian on orientable surfaces. <a href="https://doi.org/10.1007/s00209-022-03009-4">Math. Z.</a> 301.3 (2022), pp. 2733–2746. <a href="https://rdcu.be/KycWC68WQfca">sharedIt</a> | <a href="https://arxiv.org/abs/2106.00627">arXiv</a>.</li>
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
