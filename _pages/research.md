---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research broadly focuses on equilibrium and non-equilibrium quantum systems with applications to Quantum Technologies.

<style>
.accordion-item {
  border-bottom: 1px solid #ccc;
}
.accordion-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 18px 0;
  cursor: pointer;
  user-select: none;
}
.accordion-header h2 {
  margin: 0;
  font-size: 1.3em;
  text-decoration: underline;
}
.accordion-icon {
  flex-shrink: 0;
  width: 34px;
  height: 34px;
  border-radius: 50%;
  background: #3a3a3a;
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1em;
  transition: transform 0.2s ease;
}
.accordion-item.open .accordion-icon {
  transform: rotate(180deg);
}
.accordion-content {
  display: none;
  padding: 0 0 25px 0;
}
.accordion-item.open .accordion-content {
  display: block;
}
</style>

<div class="accordion-item open" id="acc-thermo">
  <div class="accordion-header" onclick="toggleAccordion('acc-thermo')">
    <h2>Thermodynamic Processes in Hybrid Quantum Systems</h2>
    <div class="accordion-icon">&#9660;</div>
  </div>
  <div class="accordion-content">
    <p>Generally, a quantum system is not isolated or closed. Typically, realistic quantum systems are open, which causes energy dissipation due to the system-environment interaction, leading to an irreversible increase in entropy production rate. An adequate account of the causes of entropy production in these systems plays a role in designing energy-efficient quantum thermal machines. In this direction, I study the thermodynamic processes (such as irreversible entropy production) in hybrid quantum systems. One of the primary goals of my research is to manipulate and assess the entropy production rate in hybrid quantum systems.</p>

    <div style="display:flex; gap:20px; flex-wrap:wrap; margin: 15px 0;">
      <img src="/images/research-thermo-diagram-1.png" alt="Hybrid quantum system diagram 1" style="max-width:320px; width:100%;">
      <img src="/images/research-thermo-diagram-2.png" alt="Hybrid quantum system diagram 2" style="max-width:320px; width:100%;">
    </div>

    <p><strong>Selected publications</strong>:</p>
    <ul>
      <li>Abah, O., Edet, C. O., Ali, N., Teklu, B., &amp; Asjad, M. (2024). Irreversibility in an optical parametric driven optomechanical system. <a href="https://doi.org/10.1002/andp.202300400"><i>Annalen der Physik</i>, 536(3), 2300400</a>.</li>
      <li>Edet, C. O., Asjad, M., Dutykh, D., Ali, N., &amp; Abah, O. (2024). Entropy production rate and correlations in a cavity magnomechanical system. <a href="https://doi.org/10.1103/PhysRevResearch.6.033037"><i>Physical Review Research</i>, 6(3), 033037</a>.</li>
    </ul>
  </div>
</div>

<div class="accordion-item" id="acc-eigen">
  <div class="accordion-header" onclick="toggleAccordion('acc-eigen')">
    <h2>Eigensolutions of the Schrödinger Equation</h2>
    <div class="accordion-icon">&#9660;</div>
  </div>
  <div class="accordion-content">
    <p>The Schrödinger equation is a fundamental equation in quantum mechanics that describes how the quantum state of a physical system changes over time. Here, I have focused on deriving the eigenvalues and eigenfunctions for a broad array of exponential-type potential energy functions. I contributed to the development of the Nikiforov–Uvarov-Functional Analysis (NUFA) Method, a technique for deriving eigenvalues and eigenfunctions.</p>

    <img src="/images/research-schrodinger-equation.png" alt="Schrodinger equation Hpsi=Epsi" style="max-width:300px; display:block; margin: 15px 0;">

    <p><strong>Selected publications</strong>:</p>
    <ul>
      <li>Ikot, A. N., Okorie, U. S., Amadi, P. O., Edet, C. O., Rampho, G. J., &amp; Sever, R. (2021). The Nikiforov–Uvarov-Functional Analysis (NUFA) Method: A new approach for solving exponential-type potentials. <a href="https://doi.org/10.1007/s00601-021-01593-5"><i>Few-Body Systems</i>, 62, 1-16</a>.</li>
      <li>Edet, C. O., Okoi, P. O., Yusuf, A. S., Ushie, P. O., &amp; Amadi, P. O. (2021). Bound state solutions of the generalized shifted Hulthen potential. <a href="https://doi.org/10.1007/s12648-019-01650-0"><i>Indian Journal of Physics</i>, 95, 471-480</a>.</li>
      <li>Edet, C. O., Okorie, U. S., Ngiangia, A. T., &amp; Ikot, A. N. (2020). Bound state solutions of the Schrodinger equation for the modified Kratzer potential plus screened Coulomb potential. <a href="https://doi.org/10.1007/s12648-019-01477-9"><i>Indian Journal of Physics</i>, 94, 425-433</a>.</li>
    </ul>
  </div>
</div>

<div class="accordion-item" id="acc-funding">
  <div class="accordion-header" onclick="toggleAccordion('acc-funding')">
    <h2>Funding and Support</h2>
    <div class="accordion-icon">&#9660;</div>
  </div>
  <div class="accordion-content">
    <div style="display:flex; gap:30px; align-items:center; flex-wrap:wrap; margin-top: 15px;">
      <img src="/images/funding-tetfund.png" alt="TETFund logo" style="max-width:180px; width:100%;">
      <img src="/images/funding-malaysia-mohe.jpg" alt="Malaysia Ministry of Higher Education logo" style="max-width:180px; width:100%;">
      <img src="/images/funding-ieee-photonics.png" alt="IEEE Photonics Society logo" style="max-width:200px; width:100%;">
      <img src="/images/funding-nicolaus-copernicus.png" alt="Nicolaus Copernicus University logo" style="max-width:220px; width:100%;">
      <img src="/images/funding-oist.png" alt="OIST logo" style="max-width:180px; width:100%;">
      <img src="/images/funding-chalmers.png" alt="Chalmers University of Technology logo" style="max-width:150px; width:100%;">
      <img src="/images/funding-sigma-xi.png" alt="Sigma Xi logo" style="max-width:200px; width:100%;">
    </div>
  </div>
</div>

<script>
function toggleAccordion(id) {
  document.getElementById(id).classList.toggle('open');
}
</script>
