---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

<style>
.pub-tabs {
  display: flex;
  flex-wrap: wrap;
  gap: 4px;
  border-bottom: 2px solid #ddd;
  margin: 20px 0 25px 0;
}
.pub-tab-btn {
  background: none;
  border: none;
  padding: 10px 16px;
  cursor: pointer;
  font-size: 1em;
  font-weight: 500;
  color: inherit;
  opacity: 0.6;
  border-bottom: 3px solid transparent;
}
.pub-tab-btn:hover {
  opacity: 0.9;
}
.pub-tab-btn.active {
  opacity: 1;
  border-bottom: 3px solid #4a90d9;
}
.pub-tab-content {
  display: none;
}
.pub-tab-content.active {
  display: block;
}
.pub-year {
  margin-top: 25px;
  margin-bottom: 10px;
  font-size: 1.1em;
  opacity: 0.6;
  border-bottom: 1px solid #ddd;
  padding-bottom: 4px;
}
.pub-entry {
  margin-bottom: 18px;
}
.pub-title {
  font-size: 1.05em;
  font-weight: 600;
  margin-bottom: 3px;
}
.pub-authors {
  opacity: 0.65;
  font-size: 0.95em;
  margin-bottom: 3px;
}
.pub-journal {
  font-size: 0.95em;
}
</style>

<div class="pub-tabs">
  <button class="pub-tab-btn active" onclick="showPubTab('key', this)">Key Publications</button>
  <button class="pub-tab-btn" onclick="showPubTab('all', this)">All Publications</button>
  <button class="pub-tab-btn" onclick="showPubTab('journal', this)">Journal Articles</button>
  <button class="pub-tab-btn" onclick="showPubTab('book', this)">Book Chapters</button>
  <button class="pub-tab-btn" onclick="showPubTab('conf', this)">Conference Papers</button>
</div>

<div id="pub-key" class="pub-tab-content active">
<h3 class="pub-year">2024</h3>
<div class="pub-entry">
  <div class="pub-title">Entropy production rate and correlations in a cavity magnomechanical system</div>
  <div class="pub-authors"><strong>Collins O. Edet</strong>, Muhammad Asjad, Denys Dutykh, Norshamsuri Ali, Obinna Abah</div>
  <div class="pub-journal"><i>Physical Review Research</i> <strong>6</strong>(3) (2024) &ndash; <a href="https://doi.org/10.1103/PhysRevResearch.6.033037">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Irreversibility in an Optical Parametric Driven Optomechanical System</div>
  <div class="pub-authors">Obinna Abah, <strong>Collins O. Edet</strong>, Norshamsuri Ali, Berihu Teklu, Muhammad Asjad</div>
  <div class="pub-journal"><i>Annalen der Physik</i> <strong>536</strong>(3) (2024) &ndash; <a href="https://doi.org/10.1002/andp.202300400">DOI</a></div>
</div>
<h3 class="pub-year">2021</h3>
<div class="pub-entry">
  <div class="pub-title">The Nikiforov–Uvarov-Functional Analysis (NUFA) Method: A New Approach for Solving Exponential-Type Potentials</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, P.O. Amadi, <strong>C.O. Edet</strong>, G.J. Rampho, R. Sever</div>
  <div class="pub-journal"><i>Few-Body Systems</i> <strong>62</strong>(1) (2021) &ndash; <a href="https://doi.org/10.1007/s00601-021-01593-5">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Bound state solutions of the generalized shifted Hulthén potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Okoi, A.S. Yusuf, P.O. Ushie, P.O. Amadi</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>95</strong>(3), 471-480 (2021) &ndash; <a href="https://doi.org/10.1007/s12648-019-01650-0">DOI</a></div>
</div>
<h3 class="pub-year">2020</h3>
<div class="pub-entry">
  <div class="pub-title">Bound state solutions of the Schrodinger equation for the modified Kratzer potential plus screened Coulomb potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, U.S. Okorie, A.T. Ngiangia, A.N. Ikot</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>94</strong>(4), 425-433 (2020) &ndash; <a href="https://doi.org/10.1007/s12648-019-01477-9">DOI</a></div>
</div>
</div>

<div id="pub-all" class="pub-tab-content">
<h3 class="pub-year">2026</h3>
<div class="pub-entry">
  <div class="pub-title">Controllable diatomic molecular quantum thermodynamic machines</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, E.P. Inyang, O. Abah, N. Ali</div>
  <div class="pub-journal"><i>European Physical Journal Plus</i> <strong>141</strong>(3) (2026) &ndash; <a href="https://doi.org/10.1140/epjp/s13360-026-07434-w">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Quantum Otto Machine With q-Deformed Pöschl–Teller Oscillator</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, Norshamsuri Ali, Rosdisham Endut, O. Abah</div>
  <div class="pub-journal"><i>Annalen der Physik</i> <strong>538</strong>(7) (2026) &ndash; <a href="https://doi.org/10.1002/andp.70241">DOI</a></div>
</div>
<h3 class="pub-year">2025</h3>
<div class="pub-entry">
  <div class="pub-title">Thermo-Magnetic properties of non-relativistic particles under the effect of energy-dependent Hellmann potential</div>
  <div class="pub-authors">C. Ertugay, <strong>C.O. Edet</strong>, A.N. Ikot, B.C. Lütfüoğlu</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>123</strong>(11) (2025) &ndash; <a href="https://doi.org/10.1080/00268976.2024.2411327">DOI</a></div>
</div>
<h3 class="pub-year">2024</h3>
<div class="pub-entry">
  <div class="pub-title">Investigating the magneto-transport and thermal properties of 2D electron systems under the influence of the Aharonov–Bohm field and Eckart potential interaction</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, K. Lakaal, J. El Hamdaoui, K. Feddi, L.M. Pérez, E. Feddi, A.N. Ikot, N. Ali, Shamsul Amir Abdul Rais, M. Asjad</div>
  <div class="pub-journal"><i>Physica B: Condensed Matter</i> <strong>673</strong> (2024) &ndash; <a href="https://doi.org/10.1016/j.physb.2023.415438">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effects of electron–phonon coupling and Rashba spin–orbit interaction on thermodynamic and magnetic properties of quantum dots</div>
  <div class="pub-authors">K. Lakaal, L.M. Pérez, M. Kria, J. El Hamdaoui, <strong>C.O. Edet</strong>, V. Prasad, D. Laroze, E. Feddi</div>
  <div class="pub-journal"><i>Chinese Journal of Physics</i> <strong>89</strong>, 390-403 (2024) &ndash; <a href="https://doi.org/10.1016/j.cjph.2023.10.045">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Entropy production rate and correlations in a cavity magnomechanical system</div>
  <div class="pub-authors"><strong>Collins O. Edet</strong>, Muhammad Asjad, Denys Dutykh, Norshamsuri Ali, Obinna Abah</div>
  <div class="pub-journal"><i>Physical Review Research</i> <strong>6</strong>(3) (2024) &ndash; <a href="https://doi.org/10.1103/PhysRevResearch.6.033037">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Irreversibility in an Optical Parametric Driven Optomechanical System</div>
  <div class="pub-authors">Obinna Abah, <strong>Collins O. Edet</strong>, Norshamsuri Ali, Berihu Teklu, Muhammad Asjad</div>
  <div class="pub-journal"><i>Annalen der Physik</i> <strong>536</strong>(3) (2024) &ndash; <a href="https://doi.org/10.1002/andp.202300400">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Recent progress in graphene quantum dots for energy applications and storage devices: A review</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, E.P. Agbo, H.O. Edet, Nnanake-Abasi O. Offiong, John B. Edet, E.B. Ettah</div>
  <div class="pub-journal"><i>Graphene Quantum Dots (GQDs): Advances in Research and Applications</i> , 141-163 (2024)</div>
</div>
<div class="pub-entry">
  <div class="pub-title">Stationary entanglement in hybrid optomechanical systems</div>
  <div class="pub-authors">Fatin Yusoff, Muhammad Zulkifli, Norshamsuri Ali, <strong>Collins Edet</strong>, Muhammad Asjad, Rosdisham Endut, Syed Aljunid, Mat Ismail</div>
  <div class="pub-journal"><i>AIP Conference Proceedings</i> <strong>2898</strong>(1) (2024) &ndash; <a href="https://doi.org/10.1063/5.0195712">DOI</a></div>
</div>
<h3 class="pub-year">2023</h3>
<div class="pub-entry">
  <div class="pub-title">Quantum information entropy of a particle trapped by the Aharonov-Bohm-type effect</div>
  <div class="pub-authors">F.C.E. Lima, A.R.P. Moreira, C.A.S. Almeida, <strong>C.O. Edet</strong>, N. Ali</div>
  <div class="pub-journal"><i>Physica Scripta</i> <strong>98</strong>(6) (2023) &ndash; <a href="https://doi.org/10.1088/1402-4896/acd309">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Quantum information entropy of heavy mesons in the presence of a point-like defect</div>
  <div class="pub-authors">C.A.S. Almeida, <strong>C.O. Edet</strong>, F.C.E. Lima, N. Ali, M. Asjad</div>
  <div class="pub-journal"><i>Results in Physics</i> <strong>47</strong> (2023) &ndash; <a href="https://doi.org/10.1016/j.rinp.2023.106343">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Relativistic and non-relativistic thermal properties with bound and scattering states of the Klein-Gordon equation for Mobius square plus generalized Yukawa potentials</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, I.B. Okon, A.I. Ahmadov, <strong>C.O. Edet</strong>, Enock Oladimeji, C.A. Duque, G.J. Rampho</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>97</strong>(10), 2871-2888 (2023) &ndash; <a href="https://doi.org/10.1007/s12648-023-02654-7">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Determination of thermodynamic properties of CrH,NiC and CuLi diatomic molecules with the linear combination of Hulthen-type potential plus Yukawa potential</div>
  <div class="pub-authors">M. Ramantswana, G.J. Rampho, <strong>C.O. Edet</strong>, A.N. Ikot, U.S. Okorie, Karwan Wasman Qadir, Hewa Y. Abdullah</div>
  <div class="pub-journal"><i>Physics Open</i> <strong>14</strong> (2023) &ndash; <a href="https://doi.org/10.1016/j.physo.2022.100135">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effect of nanoshell geometries, sizes, and quantum emitter parameters on the sensitivity of plasmon-exciton hybrid nanoshells for sensing application</div>
  <div class="pub-authors">A. Firoozi, Angela Amphawan, R. Khordad, A. Mohammadi, T. Jalali, <strong>C.O. Edet</strong>, N. Ali</div>
  <div class="pub-journal"><i>Scientific Reports</i> <strong>13</strong>(1) (2023) &ndash; <a href="https://doi.org/10.1038/s41598-023-38475-1">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Comparison of Mann–Kendall and Şen’s innovative trend method for climatic parameters over Nigeria’s climatic zones</div>
  <div class="pub-authors">Emmanuel P. Agbo, Ugochukwu Nkajoe, <strong>Collins O. Edet</strong></div>
  <div class="pub-journal"><i>Climate Dynamics</i> <strong>60</strong>(11-12), 3385-3401 (2023) &ndash; <a href="https://doi.org/10.1007/s00382-022-06521-9">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Tunable Transparency and Group Delay in Cavity Optomechanical Systems with Degenerate Fermi Gas</div>
  <div class="pub-authors">Fatin Nadiah Yusoff, Muhammad Afiq Zulkifli, Norshamsuri Ali, Shailendra Kumar Singh, Nooraihan Abdullah, Nor Azura Malini Ahmad Hambali, <strong>Collins Okon Edet</strong></div>
  <div class="pub-journal"><i>Photonics</i> <strong>10</strong>(3) (2023) &ndash; <a href="https://doi.org/10.3390/photonics10030279">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Identification of trends of key parameters affecting vegetation over Nigeria’s vegetation zones using innovative trend analysis</div>
  <div class="pub-authors">Emmanuel P. Agbo, Ugochukwu Nkajoe, <strong>Collins O. Edet</strong>, Norshamsuri Ali</div>
  <div class="pub-journal"><i>Environmental Earth Sciences</i> <strong>82</strong>(20) (2023) &ndash; <a href="https://doi.org/10.1007/s12665-023-11141-5">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Development of New Spectral Amplitude Coding OCDMA Code by Using Polarization Encoding Technique</div>
  <div class="pub-authors">Syed Mohammad Ammar, Norshamsuri Ali, Mohamad Naufal Saad, Syed Alwee Aljunid, Rosdisham Endut, Ahmed M. Alhassan, <strong>Collins Okon Edet</strong></div>
  <div class="pub-journal"><i>Applied Sciences (Switzerland)</i> <strong>13</strong>(5) (2023) &ndash; <a href="https://doi.org/10.3390/app13052829">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Characteristics of various radiative fluxes: global, tilted, direct, and diffused radiation—a case study of Nigeria</div>
  <div class="pub-authors">E.P. Agbo, E.B. Ettah, <strong>C.O. Edet</strong>, E.G. Ndoma</div>
  <div class="pub-journal"><i>Meteorology and Atmospheric Physics</i> <strong>135</strong>(2) (2023) &ndash; <a href="https://doi.org/10.1007/s00703-023-00951-8">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effects of the confinement potential parameters and optical intensity on the linear and nonlinear optical properties of spherical quantum dots</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, E.B. Al, F. Ungan, N. Ali, M.M. Ramli, M. Asjad</div>
  <div class="pub-journal"><i>Results in Physics</i> <strong>44</strong> (2023) &ndash; <a href="https://doi.org/10.1016/j.rinp.2022.106182">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Information-theoretic measures and thermodynamic properties under magnetic and Aharonov–Bohm flux fields</div>
  <div class="pub-authors">E. Omugbe, O.E. Osafile, I.J. Njoku, A. Jahanshir, <strong>C.O. Edet</strong>, I.B. Okon, E.S. Eyube, C.A. Onate, R. Horchani, E.S. William, A.N. Ikot</div>
  <div class="pub-journal"><i>European Physical Journal D</i> <strong>77</strong>(7) (2023) &ndash; <a href="https://doi.org/10.1140/epjd/s10053-023-00718-1">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Recent advances in density functional theory approach for optoelectronics properties of graphene</div>
  <div class="pub-authors">A.L. Olatomiwa, Tijjani Adam, <strong>C.O. Edet</strong>, A.A. Adewale, Abdullah Chik, Mohammed Mohammed, Subash C.B. Gopinath, U. Hashim</div>
  <div class="pub-journal"><i>Heliyon</i> <strong>9</strong>(3) (2023) &ndash; <a href="https://doi.org/10.1016/j.heliyon.2023.e14279">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Temperature and solar radiation interactions in all six zones of Nigeria</div>
  <div class="pub-authors">E.P. Agbo, U. Nkajoe, M.A. Okono, E.P. Inyang, <strong>C.O. Edet</strong></div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>97</strong>(3), 655-669 (2023) &ndash; <a href="https://doi.org/10.1007/s12648-022-02429-6">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Approximate solutions of the Dirac equation with deformed Woods-Saxon potential including a Hellmann-like tensor interation</div>
  <div class="pub-authors">Uduakobong S. Okorie, Akpan N. Ikot, Monday E. Udoh, Sylvester A. Ekong, <strong>Collins O. Edet</strong>, Ridha Horchani, Gaotsiwe J. Rampho</div>
  <div class="pub-journal"><i>Journal of Theoretical and Applied Physics</i> <strong>17</strong>(4) (2023) &ndash; <a href="https://doi.org/10.57647/J.JTAP.2023.1704.41">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Influence of perturbations on linear and nonlinear optical properties of quantum dot</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, E.B. Al, F. Ungan, Etido P. Inyang, N. Ali, M.M. Ramli, R. Endut, S.A. Aljunid</div>
  <div class="pub-journal"><i>European Physical Journal Plus</i> <strong>138</strong>(10) (2023) &ndash; <a href="https://doi.org/10.1140/epjp/s13360-023-04519-8">DOI</a></div>
</div>
<h3 class="pub-year">2022</h3>
<div class="pub-entry">
  <div class="pub-title">Thermodynamic functions of Manning-Rosen plus a class of Yukawa potential using Euler-Maclaurin formula</div>
  <div class="pub-authors">M. Ramantswana, A.N. Ikot, G.J. Rampho, <strong>C.O. Edet</strong>, U.S. Okorie</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica E</i> <strong>19</strong>(2), 1-11 (2022) &ndash; <a href="https://doi.org/10.31349/RevMexFisE.19.020204">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">The magnetocaloric effect, thermo-magnetic and transport properties of LiH diatomic molecule</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Amadi, E.B. Ettah, Norshamsuri Ali, Muhammad Asjad, A.N. Ikot</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>120</strong>(10) (2022) &ndash; <a href="https://doi.org/10.1080/00268976.2022.2059025">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Non-Relativistic Energy Spectra of the Modified Hylleraas Potential and Its Thermodynamic Properties in Arbitrary Dimensions</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Jonathan E. Osang, Norshamsuri Ali, Emmanuel Paul Agbo, Syed Alwee Aljunid, Rosdisham Endut, Emmanuel B. Ettah, Reza Khordad, Akpan Ndem Ikot, Muhammad Asjad</div>
  <div class="pub-journal"><i>Quantum Reports</i> <strong>4</strong>(3), 238-250 (2022) &ndash; <a href="https://doi.org/10.3390/quantum4030016">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Eigensolution and Expectation Values of the Hulthen and Generalized Inverse Quadratic Yukawa Potential</div>
  <div class="pub-authors">Peter O. Okoi, <strong>Collins O. Edet</strong>, Thomas O. Magu, Etido P. Inyang</div>
  <div class="pub-journal"><i>Jordan Journal of Physics</i> <strong>15</strong>(2), 137-148 (2022) &ndash; <a href="https://doi.org/10.47011/15.2.4">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Non-Relativistic Treatment of the 2D Electron System Interacting via Varshni–Shukla Potential Using the Asymptotic Iteration Method</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Salman Mahmoud, Etido P. Inyang, Norshamsuri Ali, Syed Alwee Aljunid, Rosdisham Endut, Akpan Ndem Ikot, Muhammad Asjad</div>
  <div class="pub-journal"><i>Mathematics</i> <strong>10</strong>(15) (2022) &ndash; <a href="https://doi.org/10.3390/math10152824">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effects of Applied Magnetic Field on the Optical Properties and Binding Energies Spherical GaAs Quantum Dot with Donor Impurity</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Emre Bahadir Al, Fatih Ungan, Norshamsuri Ali, Nursalasawati Rusli, Syed Alwee Aljunid, Rosdisham Endut, Muhammad Asjad</div>
  <div class="pub-journal"><i>Nanomaterials</i> <strong>12</strong>(16) (2022) &ndash; <a href="https://doi.org/10.3390/nano12162741">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Impurity effect on thermal properties of tuned quantum dot/ring systems</div>
  <div class="pub-authors">A. Ghanbari, R. Khordad, F. Taghizadeh, I. Nasirizadeh, <strong>C.O. Edet</strong>, N. Ali</div>
  <div class="pub-journal"><i>Chemical Physics Letters</i> <strong>806</strong> (2022) &ndash; <a href="https://doi.org/10.1016/j.cplett.2022.140000">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Quantum Information of the Aharanov–Bohm Ring with Yukawa Interaction in the Presence of Disclination</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Francisco Cleiton E. Lima, Carlos Alberto S. Almeida, Norshamsuri Ali, Muhammad Asjad</div>
  <div class="pub-journal"><i>Entropy</i> <strong>24</strong>(8) (2022) &ndash; <a href="https://doi.org/10.3390/e24081059">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Magneto-transport and Thermal properties of TiH diatomic molecule under the influence of magnetic and Aharonov-Bohm (AB) fields</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, R. Khordad, E.B. Ettah, S.A. Aljunid, R. Endut, N. Ali, M. Asjad, P.O. Ushie, A.N. Ikot</div>
  <div class="pub-journal"><i>Scientific Reports</i> <strong>12</strong>(1) (2022) &ndash; <a href="https://doi.org/10.1038/s41598-022-19396-x">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Magneto-transport and thermal properties of the Yukawa potential in cosmic string space-time</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Nwbabuzor, E.B. Ettah, C.A. Duque, N. Ali, A.N. Ikot, S. Mahmoud, M. Asjad</div>
  <div class="pub-journal"><i>Results in Physics</i> <strong>39</strong> (2022) &ndash; <a href="https://doi.org/10.1016/j.rinp.2022.105749">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Superstatistics of diatomic molecules with the shifted deng-fan potential model</div>
  <div class="pub-authors"><strong>Collins Edet</strong>, Akpan Ikot</div>
  <div class="pub-journal"><i>Biointerface Research in Applied Chemistry</i> <strong>12</strong>(3), 4126-4139 (2022) &ndash; <a href="https://doi.org/10.33263/BRIAC123.41264139">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Eigenfunctions, uncertainties and thermal properties of diatomic molecules under screened modified Kratzer potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot, U.S. Okorie, M. Ramantswana, G.J. Rampho, R. Horchani, H.Y. Abdullah, H.Y. Zahran, L.F. Obagboye, A.-H. Abdel-Aty, S. Kaya</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>96</strong>(12), 3429-3448 (2022) &ndash; <a href="https://doi.org/10.1007/s12648-022-02292-5">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Confinement effects of external fields and topological defect on hydrogen atom in a quantum-plasma environment</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica</i> <strong>68</strong>(5) (2022) &ndash; <a href="https://doi.org/10.31349/RevMexFis.68.051501">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Meteorological analysis of the relationship between climatic parameters: understanding the dynamics of the troposphere</div>
  <div class="pub-authors">Emmanuel P. Agbo, <strong>Collins O. Edet</strong></div>
  <div class="pub-journal"><i>Theoretical and Applied Climatology</i> <strong>150</strong>(3-4), 1677-1698 (2022) &ndash; <a href="https://doi.org/10.1007/s00704-022-04226-x">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Aharonov–Bohm (AB) flux and thermomagnetic properties of Hellmann plus screened Kratzer potential as applied to diatomic molecules using Nikiforov–Uvarov-Functional-Analysis (NUFA) method</div>
  <div class="pub-authors">I.B. Okon, C.A. Onate, E. Omugbe, U.S. Okorie, <strong>C.O. Edet</strong>, A.D. Antia, J.P. Araujo, C.N. Isonguyo, M.C. Onyeaju, E.S. William, R. Horchani, A.N. Ikot</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>120</strong>(9) (2022) &ndash; <a href="https://doi.org/10.1080/00268976.2022.2046295">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Global Quantum Information-Theoretic Measures in the Presence of Magnetic and Aharanov-Bohm (AB) Fields</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Emmanuel Benjamin Ettah, Syed Alwee Aljunid, Rosdisham Endut, Norshamsuri Ali, Akpan Ndem Ikot, Muhammad Asjad</div>
  <div class="pub-journal"><i>Symmetry</i> <strong>14</strong>(5) (2022) &ndash; <a href="https://doi.org/10.3390/sym14050976">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Statistical Analysis and Distribution of Global Solar Radiation and Temperature over Southern Nigeria</div>
  <div class="pub-authors">M.A. Okono, E.P. Agbo, B.J. Ekah, U.J. Ekah, E.B. Ettah, <strong>C.O. Edet</strong></div>
  <div class="pub-journal"><i>Journal of the Nigerian Society of Physical Sciences</i> <strong>4</strong>(3) (2022) &ndash; <a href="https://doi.org/10.46481/jnsps.2022.588">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Application of Morse potential and improved deformed exponential-type potential (IDEP) model to predict thermodynamics properties of diatomic molecules</div>
  <div class="pub-authors">R. Khordad, <strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>International Journal of Modern Physics C</i> <strong>33</strong>(8) (2022) &ndash; <a href="https://doi.org/10.1142/S0129183122501066">DOI</a></div>
</div>
<h3 class="pub-year">2021</h3>
<div class="pub-entry">
  <div class="pub-title">Thermo-magnetic properties of the screened Kratzer potential with spatially varying mass under the influence of Aharanov-Bohm(AB) and position-dependent magnetic fields</div>
  <div class="pub-authors"><strong>Collins O. Edet</strong>, Akpan N. Ikot, Michael C. Onyeaju, Uduakobong S. Okorie, Gaotsiwe J. Rampho, Mantile L. Lekala, Savas Kaya</div>
  <div class="pub-journal"><i>Physica E: Low-Dimensional Systems and Nanostructures</i> <strong>131</strong> (2021) &ndash; <a href="https://doi.org/10.1016/j.physe.2021.114710">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">The Nikiforov–Uvarov-Functional Analysis (NUFA) Method: A New Approach for Solving Exponential-Type Potentials</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, P.O. Amadi, <strong>C.O. Edet</strong>, G.J. Rampho, R. Sever</div>
  <div class="pub-journal"><i>Few-Body Systems</i> <strong>62</strong>(1) (2021) &ndash; <a href="https://doi.org/10.1007/s00601-021-01593-5">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Energy spectra and thermal properties of diatomic molecules in the presence of magnetic and AB fields with improved Kratzer potential</div>
  <div class="pub-authors">G.J. Rampho, A.N. Ikot, <strong>C.O. Edet</strong>, U.S. Okorie</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>119</strong>(5) (2021) &ndash; <a href="https://doi.org/10.1080/00268976.2020.1821922">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Shannon information entropy in the presence of magnetic and Aharanov–Bohm (AB) fields</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>European Physical Journal Plus</i> <strong>136</strong>(4) (2021) &ndash; <a href="https://doi.org/10.1140/epjp/s13360-021-01438-4">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Klein–Gordon Equation and Nonrelativistic Thermodynamic Properties with Improved Screened Kratzer Potential</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, G.J. Rampho, P.O. Amadi, <strong>C.O. Edet</strong>, I.O. Akpan, H.Y. Abdullah, R. Horchani</div>
  <div class="pub-journal"><i>Journal of Low Temperature Physics</i> <strong>202</strong>(3-4), 269-289 (2021) &ndash; <a href="https://doi.org/10.1007/s10909-020-02544-w">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Solutions of the 2D Schrodinger equation and its thermal properties for improved ultra-generalized exponential hyperbolic potential (IUGE-HP)</div>
  <div class="pub-authors">Akpan Ndem Ikot, <strong>Collins Okon Edet</strong>, Uduakobong Sunday Okorie, Abdel-Haleem Abdel-Aty, M. Ramantswana, Gaotsiwe Joel Rampho, Nawal A. Alshehri, S.K. Elagan, Savas Kaya</div>
  <div class="pub-journal"><i>European Physical Journal Plus</i> <strong>136</strong>(4) (2021) &ndash; <a href="https://doi.org/10.1140/epjp/s13360-021-01408-w">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Bound state solutions of the generalized shifted Hulthén potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Okoi, A.S. Yusuf, P.O. Ushie, P.O. Amadi</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>95</strong>(3), 471-480 (2021) &ndash; <a href="https://doi.org/10.1007/s12648-019-01650-0">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Non-relativistic quark model under external magnetic and aharanov–bohm (Ab) fields in the presence of temperature-dependent confined cornell potential</div>
  <div class="pub-authors">M. Abu-Shady, <strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>Canadian Journal of Physics</i> <strong>99</strong>(11), 1024-1031 (2021) &ndash; <a href="https://doi.org/10.1139/cjp-2020-0101">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Analyzing the effects of topological defect (Td) on the energy spectra and thermal properties of lih, tic and i2 diatomic molecules</div>
  <div class="pub-authors">Peter Nwabuzor, <strong>Collins Edet</strong>, Akpan Ndemikot, Uduakobong Okorie, Morris Ramantswana, Ridha Horchani, Abdel-Haleem Abdel-Aty, Gaotsiwe Rampho</div>
  <div class="pub-journal"><i>Entropy</i> <strong>23</strong>(8) (2021) &ndash; <a href="https://doi.org/10.3390/e23081060">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Analysis of the effects of meteorological parameters on radio refractivity, equivalent potential temperature and field strength via Mann-Kendall test</div>
  <div class="pub-authors">Emmanuel P. Agbo, Chris M. Ekpo, <strong>Collins O. Edet</strong></div>
  <div class="pub-journal"><i>Theoretical and Applied Climatology</i> <strong>143</strong>(3-4), 1437-1456 (2021) &ndash; <a href="https://doi.org/10.1007/s00704-020-03464-1">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Thermal Properties and Magnetic Susceptibility of Hellmann Potential in Aharonov–Bohm (AB) Flux and Magnetic Fields at Zero and Finite Temperatures</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Amadi, M.C. Onyeaju, U.S. Okorie, R. Sever, G.J. Rampho, Hewa Y. Abdullah, Idris H. Salih, A.N. Ikot</div>
  <div class="pub-journal"><i>Journal of Low Temperature Physics</i> <strong>202</strong>(1-2), 83-105 (2021) &ndash; <a href="https://doi.org/10.1007/s10909-020-02533-z">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Bound and Scattering State Solutions of the Klein–Gordon Equation with Deng–Fan Potential in Higher Dimensions</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, G.J. Rampho, <strong>C.O. Edet</strong>, R. Horchani, A. Abdel-aty, N.A. Alshehri, S.K. Elagan</div>
  <div class="pub-journal"><i>Few-Body Systems</i> <strong>62</strong>(4) (2021) &ndash; <a href="https://doi.org/10.1007/s00601-021-01693-2">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Analysis of the impact of external fields on the energy spectra and thermo-magnetic properties of N  2,I  2,CO,NO and HCl diatomic molecules</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>119</strong>(23) (2021) &ndash; <a href="https://doi.org/10.1080/00268976.2021.1957170">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Solar energy: A panacea for the electricity generation crisis in Nigeria</div>
  <div class="pub-authors">Emmanuel.P. Agbo, <strong>Collins.O. Edet</strong>, Thomas.O. Magu, Armstrong.O. Njok, Chris.M. Ekpo, Hitler Louis</div>
  <div class="pub-journal"><i>Heliyon</i> <strong>7</strong>(5) (2021) &ndash; <a href="https://doi.org/10.1016/j.heliyon.2021.e07016">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effects of Topological Defect on the Energy Spectra and Thermo-magnetic Properties of CO Diatomic Molecule</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>Journal of Low Temperature Physics</i> <strong>203</strong>(1-2), 84-111 (2021) &ndash; <a href="https://doi.org/10.1007/s10909-021-02577-9">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Persistent Current, Magnetic Susceptibility, and Thermal Properties for a Class of Yukawa Potential in the Presence of External Magnetic and Aharanov–Bohm Fields</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot, U.S. Okorie, G.J. Rampho, M. Ramantswana, R. Horchani, H. Abdullah, J.A. Vinasco, C.A. Duque, Abdel-Haleem Abdel-Aty</div>
  <div class="pub-journal"><i>International Journal of Thermophysics</i> <strong>42</strong>(10) (2021) &ndash; <a href="https://doi.org/10.1007/s10765-021-02891-0">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Thermodynamic functions for diatomic molecules with modified Kratzer plus screened Coulomb potential</div>
  <div class="pub-authors">U.S. Okorie, <strong>C.O. Edet</strong>, A.N. Ikot, G.J. Rampho, R. Sever</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>95</strong>(3), 411-421 (2021) &ndash; <a href="https://doi.org/10.1007/s12648-019-01670-w">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effect of the deformation parameter on the nonrelativistic energy spectra of the q-deformed Hulthen-quadratic exponential-type potential</div>
  <div class="pub-authors">Ushie Patrick Obogo, Ofem Egbe Ubi, <strong>Collins Okon Edet</strong>, Akpan Ndem Ikot</div>
  <div class="pub-journal"><i>Ecletica Quimica</i> <strong>46</strong>(4), 60-73 (2021) &ndash; <a href="https://doi.org/10.26850/1678-4618eqj.v46.4.2021.p60-73">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Bound and scattering states solutions of the Klein–Gordon equation with generalized Mobius square potential in D-dimensions</div>
  <div class="pub-authors">Uduakobong S. Okorie, Akpan N. Ikot, <strong>Collins O. Edet</strong>, Gaotsiwe J. Rampho, Ridha Horchani, Haikel Jelassi</div>
  <div class="pub-journal"><i>European Physical Journal D</i> <strong>75</strong>(2) (2021) &ndash; <a href="https://doi.org/10.1140/epjd/s10053-021-00059-x">DOI</a></div>
</div>
<h3 class="pub-year">2020</h3>
<div class="pub-entry">
  <div class="pub-title">Bound state solutions of the Schrödinger equation with energy-dependent molecular Kratzer potential via asymptotic iteration method</div>
  <div class="pub-authors">Akpan Ndem Ikot, Uduakobong Okorie, Alalibo Thompson Ngiangia, Clement Atachegbe Onate, <strong>Collins Okon Edet</strong>, Ita Okon Akpan, Precious Ogbonda Amadi</div>
  <div class="pub-journal"><i>Ecletica Quimica</i> <strong>45</strong>(1), 65-76 (2020) &ndash; <a href="https://doi.org/10.26850/1678-4618eqj.v45.1.p65-76">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Bound state solutions of the Schrodinger equation for the modified Kratzer potential plus screened Coulomb potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, U.S. Okorie, A.T. Ngiangia, A.N. Ikot</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>94</strong>(4), 425-433 (2020) &ndash; <a href="https://doi.org/10.1007/s12648-019-01477-9">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Superstatistics of Schrödinger equation with pseudo-harmonic potential in external magnetic and Aharanov-Bohm fields</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, G. Osobonye, P.O. Amadi, <strong>C.O. Edet</strong>, M.J. Sithole, G.J. Rampho, R. Sever</div>
  <div class="pub-journal"><i>Heliyon</i> <strong>6</strong>(4) (2020) &ndash; <a href="https://doi.org/10.1016/j.heliyon.2020.e03738">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Thermal properties of Deng–Fan–Eckart potential model using Poisson summation approach</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, U.S. Okorie, G. Osobonye, A.N. Ikot, G.J. Rampho, R. Sever</div>
  <div class="pub-journal"><i>Journal of Mathematical Chemistry</i> <strong>58</strong>(5), 989-1013 (2020) &ndash; <a href="https://doi.org/10.1007/s10910-020-01107-4">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Relativistic treatment of the hellmann-generalized morse potential</div>
  <div class="pub-authors">P.O. Okoi, <strong>C.O. Edet</strong>, T.O. Magu</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica</i> <strong>66</strong>(1), 1-13 (2020) &ndash; <a href="https://doi.org/10.31349/RevMexFis.66.1">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Analytic solutions of the Schrödinger equation with non-central generalized inverse quadratic Yukawa potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Okoi, S.O. Chima</div>
  <div class="pub-journal"><i>Revista Brasileira de Ensino de Fisica</i> <strong>42</strong> (2020) &ndash; <a href="https://doi.org/10.1590/1806-9126-RBEF-2019-0083">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Solutions of Schrödinger equation and thermal properties of generalized trigonometric Pöschl-Teller potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Amadi, U.S. Okorie, A. Taş, A.N. Ikot, G. Rampho</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica</i> <strong>66</strong>(6), 824-839 (2020) &ndash; <a href="https://doi.org/10.31349/RevMexFis.66.824">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Any l-state solutions of the Schrodinger equation interacting with Hellmann–Kratzer potential model</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, Kalu Okam Okorie, Hitler Louis, Nelson A. Nzeata-Ibe</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>94</strong>(2), 243-251 (2020) &ndash; <a href="https://doi.org/10.1007/s12648-019-01467-x">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Thermodynamic properties of Aharanov–Bohm (AB) and magnetic fields with screened Kratzer potential</div>
  <div class="pub-authors">Akpan N. Ikot, <strong>Collins O. Edet</strong>, Precious O. Amadi, Uduakobong S. Okorie, Gaotsiwe J. Rampho, Hewa Y. Abdullah</div>
  <div class="pub-journal"><i>European Physical Journal D</i> <strong>74</strong>(7) (2020) &ndash; <a href="https://doi.org/10.1140/epjd/e2020-10084-9">DOI</a></div>
</div>
<h3 class="pub-year">2019</h3>
<div class="pub-entry">
  <div class="pub-title">Solutions of the klein gordon equation with generalized hyperbolic potential in d-dimensions</div>
  <div class="pub-authors">Uduakobong S. Okorie, Akpan N. Ikot, <strong>C.O. Edet</strong>, I.O. Akpan, R. Sever, G.J. Rampho</div>
  <div class="pub-journal"><i>Journal of Physics Communications</i> <strong>3</strong>(9) (2019) &ndash; <a href="https://doi.org/10.1088/2399-6528/ab42c6">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Any l-state solutions of the Schrödinger equation for q-deformed Hulthen plus generalized inverse quadratic Yukawa potential in arbitrary dimensions</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Okoi</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica</i> <strong>65</strong>(4), 333-344 (2019) &ndash; <a href="https://doi.org/10.31349/REVMEXFIS.65.333">DOI</a></div>
</div>
</div>

<div id="pub-journal" class="pub-tab-content">
<h3 class="pub-year">2026</h3>
<div class="pub-entry">
  <div class="pub-title">Controllable diatomic molecular quantum thermodynamic machines</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, E.P. Inyang, O. Abah, N. Ali</div>
  <div class="pub-journal"><i>European Physical Journal Plus</i> <strong>141</strong>(3) (2026) &ndash; <a href="https://doi.org/10.1140/epjp/s13360-026-07434-w">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Quantum Otto Machine With q-Deformed Pöschl–Teller Oscillator</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, Norshamsuri Ali, Rosdisham Endut, O. Abah</div>
  <div class="pub-journal"><i>Annalen der Physik</i> <strong>538</strong>(7) (2026) &ndash; <a href="https://doi.org/10.1002/andp.70241">DOI</a></div>
</div>
<h3 class="pub-year">2025</h3>
<div class="pub-entry">
  <div class="pub-title">Thermo-Magnetic properties of non-relativistic particles under the effect of energy-dependent Hellmann potential</div>
  <div class="pub-authors">C. Ertugay, <strong>C.O. Edet</strong>, A.N. Ikot, B.C. Lütfüoğlu</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>123</strong>(11) (2025) &ndash; <a href="https://doi.org/10.1080/00268976.2024.2411327">DOI</a></div>
</div>
<h3 class="pub-year">2024</h3>
<div class="pub-entry">
  <div class="pub-title">Investigating the magneto-transport and thermal properties of 2D electron systems under the influence of the Aharonov–Bohm field and Eckart potential interaction</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, K. Lakaal, J. El Hamdaoui, K. Feddi, L.M. Pérez, E. Feddi, A.N. Ikot, N. Ali, Shamsul Amir Abdul Rais, M. Asjad</div>
  <div class="pub-journal"><i>Physica B: Condensed Matter</i> <strong>673</strong> (2024) &ndash; <a href="https://doi.org/10.1016/j.physb.2023.415438">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effects of electron–phonon coupling and Rashba spin–orbit interaction on thermodynamic and magnetic properties of quantum dots</div>
  <div class="pub-authors">K. Lakaal, L.M. Pérez, M. Kria, J. El Hamdaoui, <strong>C.O. Edet</strong>, V. Prasad, D. Laroze, E. Feddi</div>
  <div class="pub-journal"><i>Chinese Journal of Physics</i> <strong>89</strong>, 390-403 (2024) &ndash; <a href="https://doi.org/10.1016/j.cjph.2023.10.045">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Entropy production rate and correlations in a cavity magnomechanical system</div>
  <div class="pub-authors"><strong>Collins O. Edet</strong>, Muhammad Asjad, Denys Dutykh, Norshamsuri Ali, Obinna Abah</div>
  <div class="pub-journal"><i>Physical Review Research</i> <strong>6</strong>(3) (2024) &ndash; <a href="https://doi.org/10.1103/PhysRevResearch.6.033037">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Irreversibility in an Optical Parametric Driven Optomechanical System</div>
  <div class="pub-authors">Obinna Abah, <strong>Collins O. Edet</strong>, Norshamsuri Ali, Berihu Teklu, Muhammad Asjad</div>
  <div class="pub-journal"><i>Annalen der Physik</i> <strong>536</strong>(3) (2024) &ndash; <a href="https://doi.org/10.1002/andp.202300400">DOI</a></div>
</div>
<h3 class="pub-year">2023</h3>
<div class="pub-entry">
  <div class="pub-title">Quantum information entropy of a particle trapped by the Aharonov-Bohm-type effect</div>
  <div class="pub-authors">F.C.E. Lima, A.R.P. Moreira, C.A.S. Almeida, <strong>C.O. Edet</strong>, N. Ali</div>
  <div class="pub-journal"><i>Physica Scripta</i> <strong>98</strong>(6) (2023) &ndash; <a href="https://doi.org/10.1088/1402-4896/acd309">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Quantum information entropy of heavy mesons in the presence of a point-like defect</div>
  <div class="pub-authors">C.A.S. Almeida, <strong>C.O. Edet</strong>, F.C.E. Lima, N. Ali, M. Asjad</div>
  <div class="pub-journal"><i>Results in Physics</i> <strong>47</strong> (2023) &ndash; <a href="https://doi.org/10.1016/j.rinp.2023.106343">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Relativistic and non-relativistic thermal properties with bound and scattering states of the Klein-Gordon equation for Mobius square plus generalized Yukawa potentials</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, I.B. Okon, A.I. Ahmadov, <strong>C.O. Edet</strong>, Enock Oladimeji, C.A. Duque, G.J. Rampho</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>97</strong>(10), 2871-2888 (2023) &ndash; <a href="https://doi.org/10.1007/s12648-023-02654-7">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Determination of thermodynamic properties of CrH,NiC and CuLi diatomic molecules with the linear combination of Hulthen-type potential plus Yukawa potential</div>
  <div class="pub-authors">M. Ramantswana, G.J. Rampho, <strong>C.O. Edet</strong>, A.N. Ikot, U.S. Okorie, Karwan Wasman Qadir, Hewa Y. Abdullah</div>
  <div class="pub-journal"><i>Physics Open</i> <strong>14</strong> (2023) &ndash; <a href="https://doi.org/10.1016/j.physo.2022.100135">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effect of nanoshell geometries, sizes, and quantum emitter parameters on the sensitivity of plasmon-exciton hybrid nanoshells for sensing application</div>
  <div class="pub-authors">A. Firoozi, Angela Amphawan, R. Khordad, A. Mohammadi, T. Jalali, <strong>C.O. Edet</strong>, N. Ali</div>
  <div class="pub-journal"><i>Scientific Reports</i> <strong>13</strong>(1) (2023) &ndash; <a href="https://doi.org/10.1038/s41598-023-38475-1">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Comparison of Mann–Kendall and Şen’s innovative trend method for climatic parameters over Nigeria’s climatic zones</div>
  <div class="pub-authors">Emmanuel P. Agbo, Ugochukwu Nkajoe, <strong>Collins O. Edet</strong></div>
  <div class="pub-journal"><i>Climate Dynamics</i> <strong>60</strong>(11-12), 3385-3401 (2023) &ndash; <a href="https://doi.org/10.1007/s00382-022-06521-9">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Tunable Transparency and Group Delay in Cavity Optomechanical Systems with Degenerate Fermi Gas</div>
  <div class="pub-authors">Fatin Nadiah Yusoff, Muhammad Afiq Zulkifli, Norshamsuri Ali, Shailendra Kumar Singh, Nooraihan Abdullah, Nor Azura Malini Ahmad Hambali, <strong>Collins Okon Edet</strong></div>
  <div class="pub-journal"><i>Photonics</i> <strong>10</strong>(3) (2023) &ndash; <a href="https://doi.org/10.3390/photonics10030279">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Identification of trends of key parameters affecting vegetation over Nigeria’s vegetation zones using innovative trend analysis</div>
  <div class="pub-authors">Emmanuel P. Agbo, Ugochukwu Nkajoe, <strong>Collins O. Edet</strong>, Norshamsuri Ali</div>
  <div class="pub-journal"><i>Environmental Earth Sciences</i> <strong>82</strong>(20) (2023) &ndash; <a href="https://doi.org/10.1007/s12665-023-11141-5">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Development of New Spectral Amplitude Coding OCDMA Code by Using Polarization Encoding Technique</div>
  <div class="pub-authors">Syed Mohammad Ammar, Norshamsuri Ali, Mohamad Naufal Saad, Syed Alwee Aljunid, Rosdisham Endut, Ahmed M. Alhassan, <strong>Collins Okon Edet</strong></div>
  <div class="pub-journal"><i>Applied Sciences (Switzerland)</i> <strong>13</strong>(5) (2023) &ndash; <a href="https://doi.org/10.3390/app13052829">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Characteristics of various radiative fluxes: global, tilted, direct, and diffused radiation—a case study of Nigeria</div>
  <div class="pub-authors">E.P. Agbo, E.B. Ettah, <strong>C.O. Edet</strong>, E.G. Ndoma</div>
  <div class="pub-journal"><i>Meteorology and Atmospheric Physics</i> <strong>135</strong>(2) (2023) &ndash; <a href="https://doi.org/10.1007/s00703-023-00951-8">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effects of the confinement potential parameters and optical intensity on the linear and nonlinear optical properties of spherical quantum dots</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, E.B. Al, F. Ungan, N. Ali, M.M. Ramli, M. Asjad</div>
  <div class="pub-journal"><i>Results in Physics</i> <strong>44</strong> (2023) &ndash; <a href="https://doi.org/10.1016/j.rinp.2022.106182">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Information-theoretic measures and thermodynamic properties under magnetic and Aharonov–Bohm flux fields</div>
  <div class="pub-authors">E. Omugbe, O.E. Osafile, I.J. Njoku, A. Jahanshir, <strong>C.O. Edet</strong>, I.B. Okon, E.S. Eyube, C.A. Onate, R. Horchani, E.S. William, A.N. Ikot</div>
  <div class="pub-journal"><i>European Physical Journal D</i> <strong>77</strong>(7) (2023) &ndash; <a href="https://doi.org/10.1140/epjd/s10053-023-00718-1">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Recent advances in density functional theory approach for optoelectronics properties of graphene</div>
  <div class="pub-authors">A.L. Olatomiwa, Tijjani Adam, <strong>C.O. Edet</strong>, A.A. Adewale, Abdullah Chik, Mohammed Mohammed, Subash C.B. Gopinath, U. Hashim</div>
  <div class="pub-journal"><i>Heliyon</i> <strong>9</strong>(3) (2023) &ndash; <a href="https://doi.org/10.1016/j.heliyon.2023.e14279">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Temperature and solar radiation interactions in all six zones of Nigeria</div>
  <div class="pub-authors">E.P. Agbo, U. Nkajoe, M.A. Okono, E.P. Inyang, <strong>C.O. Edet</strong></div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>97</strong>(3), 655-669 (2023) &ndash; <a href="https://doi.org/10.1007/s12648-022-02429-6">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Approximate solutions of the Dirac equation with deformed Woods-Saxon potential including a Hellmann-like tensor interation</div>
  <div class="pub-authors">Uduakobong S. Okorie, Akpan N. Ikot, Monday E. Udoh, Sylvester A. Ekong, <strong>Collins O. Edet</strong>, Ridha Horchani, Gaotsiwe J. Rampho</div>
  <div class="pub-journal"><i>Journal of Theoretical and Applied Physics</i> <strong>17</strong>(4) (2023) &ndash; <a href="https://doi.org/10.57647/J.JTAP.2023.1704.41">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Influence of perturbations on linear and nonlinear optical properties of quantum dot</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, E.B. Al, F. Ungan, Etido P. Inyang, N. Ali, M.M. Ramli, R. Endut, S.A. Aljunid</div>
  <div class="pub-journal"><i>European Physical Journal Plus</i> <strong>138</strong>(10) (2023) &ndash; <a href="https://doi.org/10.1140/epjp/s13360-023-04519-8">DOI</a></div>
</div>
<h3 class="pub-year">2022</h3>
<div class="pub-entry">
  <div class="pub-title">Thermodynamic functions of Manning-Rosen plus a class of Yukawa potential using Euler-Maclaurin formula</div>
  <div class="pub-authors">M. Ramantswana, A.N. Ikot, G.J. Rampho, <strong>C.O. Edet</strong>, U.S. Okorie</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica E</i> <strong>19</strong>(2), 1-11 (2022) &ndash; <a href="https://doi.org/10.31349/RevMexFisE.19.020204">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">The magnetocaloric effect, thermo-magnetic and transport properties of LiH diatomic molecule</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Amadi, E.B. Ettah, Norshamsuri Ali, Muhammad Asjad, A.N. Ikot</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>120</strong>(10) (2022) &ndash; <a href="https://doi.org/10.1080/00268976.2022.2059025">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Non-Relativistic Energy Spectra of the Modified Hylleraas Potential and Its Thermodynamic Properties in Arbitrary Dimensions</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Jonathan E. Osang, Norshamsuri Ali, Emmanuel Paul Agbo, Syed Alwee Aljunid, Rosdisham Endut, Emmanuel B. Ettah, Reza Khordad, Akpan Ndem Ikot, Muhammad Asjad</div>
  <div class="pub-journal"><i>Quantum Reports</i> <strong>4</strong>(3), 238-250 (2022) &ndash; <a href="https://doi.org/10.3390/quantum4030016">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Eigensolution and Expectation Values of the Hulthen and Generalized Inverse Quadratic Yukawa Potential</div>
  <div class="pub-authors">Peter O. Okoi, <strong>Collins O. Edet</strong>, Thomas O. Magu, Etido P. Inyang</div>
  <div class="pub-journal"><i>Jordan Journal of Physics</i> <strong>15</strong>(2), 137-148 (2022) &ndash; <a href="https://doi.org/10.47011/15.2.4">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Non-Relativistic Treatment of the 2D Electron System Interacting via Varshni–Shukla Potential Using the Asymptotic Iteration Method</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Salman Mahmoud, Etido P. Inyang, Norshamsuri Ali, Syed Alwee Aljunid, Rosdisham Endut, Akpan Ndem Ikot, Muhammad Asjad</div>
  <div class="pub-journal"><i>Mathematics</i> <strong>10</strong>(15) (2022) &ndash; <a href="https://doi.org/10.3390/math10152824">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effects of Applied Magnetic Field on the Optical Properties and Binding Energies Spherical GaAs Quantum Dot with Donor Impurity</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Emre Bahadir Al, Fatih Ungan, Norshamsuri Ali, Nursalasawati Rusli, Syed Alwee Aljunid, Rosdisham Endut, Muhammad Asjad</div>
  <div class="pub-journal"><i>Nanomaterials</i> <strong>12</strong>(16) (2022) &ndash; <a href="https://doi.org/10.3390/nano12162741">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Impurity effect on thermal properties of tuned quantum dot/ring systems</div>
  <div class="pub-authors">A. Ghanbari, R. Khordad, F. Taghizadeh, I. Nasirizadeh, <strong>C.O. Edet</strong>, N. Ali</div>
  <div class="pub-journal"><i>Chemical Physics Letters</i> <strong>806</strong> (2022) &ndash; <a href="https://doi.org/10.1016/j.cplett.2022.140000">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Quantum Information of the Aharanov–Bohm Ring with Yukawa Interaction in the Presence of Disclination</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Francisco Cleiton E. Lima, Carlos Alberto S. Almeida, Norshamsuri Ali, Muhammad Asjad</div>
  <div class="pub-journal"><i>Entropy</i> <strong>24</strong>(8) (2022) &ndash; <a href="https://doi.org/10.3390/e24081059">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Magneto-transport and Thermal properties of TiH diatomic molecule under the influence of magnetic and Aharonov-Bohm (AB) fields</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, R. Khordad, E.B. Ettah, S.A. Aljunid, R. Endut, N. Ali, M. Asjad, P.O. Ushie, A.N. Ikot</div>
  <div class="pub-journal"><i>Scientific Reports</i> <strong>12</strong>(1) (2022) &ndash; <a href="https://doi.org/10.1038/s41598-022-19396-x">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Magneto-transport and thermal properties of the Yukawa potential in cosmic string space-time</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Nwbabuzor, E.B. Ettah, C.A. Duque, N. Ali, A.N. Ikot, S. Mahmoud, M. Asjad</div>
  <div class="pub-journal"><i>Results in Physics</i> <strong>39</strong> (2022) &ndash; <a href="https://doi.org/10.1016/j.rinp.2022.105749">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Superstatistics of diatomic molecules with the shifted deng-fan potential model</div>
  <div class="pub-authors"><strong>Collins Edet</strong>, Akpan Ikot</div>
  <div class="pub-journal"><i>Biointerface Research in Applied Chemistry</i> <strong>12</strong>(3), 4126-4139 (2022) &ndash; <a href="https://doi.org/10.33263/BRIAC123.41264139">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Eigenfunctions, uncertainties and thermal properties of diatomic molecules under screened modified Kratzer potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot, U.S. Okorie, M. Ramantswana, G.J. Rampho, R. Horchani, H.Y. Abdullah, H.Y. Zahran, L.F. Obagboye, A.-H. Abdel-Aty, S. Kaya</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>96</strong>(12), 3429-3448 (2022) &ndash; <a href="https://doi.org/10.1007/s12648-022-02292-5">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Confinement effects of external fields and topological defect on hydrogen atom in a quantum-plasma environment</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica</i> <strong>68</strong>(5) (2022) &ndash; <a href="https://doi.org/10.31349/RevMexFis.68.051501">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Meteorological analysis of the relationship between climatic parameters: understanding the dynamics of the troposphere</div>
  <div class="pub-authors">Emmanuel P. Agbo, <strong>Collins O. Edet</strong></div>
  <div class="pub-journal"><i>Theoretical and Applied Climatology</i> <strong>150</strong>(3-4), 1677-1698 (2022) &ndash; <a href="https://doi.org/10.1007/s00704-022-04226-x">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Aharonov–Bohm (AB) flux and thermomagnetic properties of Hellmann plus screened Kratzer potential as applied to diatomic molecules using Nikiforov–Uvarov-Functional-Analysis (NUFA) method</div>
  <div class="pub-authors">I.B. Okon, C.A. Onate, E. Omugbe, U.S. Okorie, <strong>C.O. Edet</strong>, A.D. Antia, J.P. Araujo, C.N. Isonguyo, M.C. Onyeaju, E.S. William, R. Horchani, A.N. Ikot</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>120</strong>(9) (2022) &ndash; <a href="https://doi.org/10.1080/00268976.2022.2046295">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Global Quantum Information-Theoretic Measures in the Presence of Magnetic and Aharanov-Bohm (AB) Fields</div>
  <div class="pub-authors"><strong>Collins Okon Edet</strong>, Emmanuel Benjamin Ettah, Syed Alwee Aljunid, Rosdisham Endut, Norshamsuri Ali, Akpan Ndem Ikot, Muhammad Asjad</div>
  <div class="pub-journal"><i>Symmetry</i> <strong>14</strong>(5) (2022) &ndash; <a href="https://doi.org/10.3390/sym14050976">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Statistical Analysis and Distribution of Global Solar Radiation and Temperature over Southern Nigeria</div>
  <div class="pub-authors">M.A. Okono, E.P. Agbo, B.J. Ekah, U.J. Ekah, E.B. Ettah, <strong>C.O. Edet</strong></div>
  <div class="pub-journal"><i>Journal of the Nigerian Society of Physical Sciences</i> <strong>4</strong>(3) (2022) &ndash; <a href="https://doi.org/10.46481/jnsps.2022.588">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Application of Morse potential and improved deformed exponential-type potential (IDEP) model to predict thermodynamics properties of diatomic molecules</div>
  <div class="pub-authors">R. Khordad, <strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>International Journal of Modern Physics C</i> <strong>33</strong>(8) (2022) &ndash; <a href="https://doi.org/10.1142/S0129183122501066">DOI</a></div>
</div>
<h3 class="pub-year">2021</h3>
<div class="pub-entry">
  <div class="pub-title">Thermo-magnetic properties of the screened Kratzer potential with spatially varying mass under the influence of Aharanov-Bohm(AB) and position-dependent magnetic fields</div>
  <div class="pub-authors"><strong>Collins O. Edet</strong>, Akpan N. Ikot, Michael C. Onyeaju, Uduakobong S. Okorie, Gaotsiwe J. Rampho, Mantile L. Lekala, Savas Kaya</div>
  <div class="pub-journal"><i>Physica E: Low-Dimensional Systems and Nanostructures</i> <strong>131</strong> (2021) &ndash; <a href="https://doi.org/10.1016/j.physe.2021.114710">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">The Nikiforov–Uvarov-Functional Analysis (NUFA) Method: A New Approach for Solving Exponential-Type Potentials</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, P.O. Amadi, <strong>C.O. Edet</strong>, G.J. Rampho, R. Sever</div>
  <div class="pub-journal"><i>Few-Body Systems</i> <strong>62</strong>(1) (2021) &ndash; <a href="https://doi.org/10.1007/s00601-021-01593-5">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Energy spectra and thermal properties of diatomic molecules in the presence of magnetic and AB fields with improved Kratzer potential</div>
  <div class="pub-authors">G.J. Rampho, A.N. Ikot, <strong>C.O. Edet</strong>, U.S. Okorie</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>119</strong>(5) (2021) &ndash; <a href="https://doi.org/10.1080/00268976.2020.1821922">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Shannon information entropy in the presence of magnetic and Aharanov–Bohm (AB) fields</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>European Physical Journal Plus</i> <strong>136</strong>(4) (2021) &ndash; <a href="https://doi.org/10.1140/epjp/s13360-021-01438-4">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Klein–Gordon Equation and Nonrelativistic Thermodynamic Properties with Improved Screened Kratzer Potential</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, G.J. Rampho, P.O. Amadi, <strong>C.O. Edet</strong>, I.O. Akpan, H.Y. Abdullah, R. Horchani</div>
  <div class="pub-journal"><i>Journal of Low Temperature Physics</i> <strong>202</strong>(3-4), 269-289 (2021) &ndash; <a href="https://doi.org/10.1007/s10909-020-02544-w">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Solutions of the 2D Schrodinger equation and its thermal properties for improved ultra-generalized exponential hyperbolic potential (IUGE-HP)</div>
  <div class="pub-authors">Akpan Ndem Ikot, <strong>Collins Okon Edet</strong>, Uduakobong Sunday Okorie, Abdel-Haleem Abdel-Aty, M. Ramantswana, Gaotsiwe Joel Rampho, Nawal A. Alshehri, S.K. Elagan, Savas Kaya</div>
  <div class="pub-journal"><i>European Physical Journal Plus</i> <strong>136</strong>(4) (2021) &ndash; <a href="https://doi.org/10.1140/epjp/s13360-021-01408-w">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Bound state solutions of the generalized shifted Hulthén potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Okoi, A.S. Yusuf, P.O. Ushie, P.O. Amadi</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>95</strong>(3), 471-480 (2021) &ndash; <a href="https://doi.org/10.1007/s12648-019-01650-0">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Non-relativistic quark model under external magnetic and aharanov–bohm (Ab) fields in the presence of temperature-dependent confined cornell potential</div>
  <div class="pub-authors">M. Abu-Shady, <strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>Canadian Journal of Physics</i> <strong>99</strong>(11), 1024-1031 (2021) &ndash; <a href="https://doi.org/10.1139/cjp-2020-0101">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Analyzing the effects of topological defect (Td) on the energy spectra and thermal properties of lih, tic and i2 diatomic molecules</div>
  <div class="pub-authors">Peter Nwabuzor, <strong>Collins Edet</strong>, Akpan Ndemikot, Uduakobong Okorie, Morris Ramantswana, Ridha Horchani, Abdel-Haleem Abdel-Aty, Gaotsiwe Rampho</div>
  <div class="pub-journal"><i>Entropy</i> <strong>23</strong>(8) (2021) &ndash; <a href="https://doi.org/10.3390/e23081060">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Analysis of the effects of meteorological parameters on radio refractivity, equivalent potential temperature and field strength via Mann-Kendall test</div>
  <div class="pub-authors">Emmanuel P. Agbo, Chris M. Ekpo, <strong>Collins O. Edet</strong></div>
  <div class="pub-journal"><i>Theoretical and Applied Climatology</i> <strong>143</strong>(3-4), 1437-1456 (2021) &ndash; <a href="https://doi.org/10.1007/s00704-020-03464-1">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Thermal Properties and Magnetic Susceptibility of Hellmann Potential in Aharonov–Bohm (AB) Flux and Magnetic Fields at Zero and Finite Temperatures</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Amadi, M.C. Onyeaju, U.S. Okorie, R. Sever, G.J. Rampho, Hewa Y. Abdullah, Idris H. Salih, A.N. Ikot</div>
  <div class="pub-journal"><i>Journal of Low Temperature Physics</i> <strong>202</strong>(1-2), 83-105 (2021) &ndash; <a href="https://doi.org/10.1007/s10909-020-02533-z">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Bound and Scattering State Solutions of the Klein–Gordon Equation with Deng–Fan Potential in Higher Dimensions</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, G.J. Rampho, <strong>C.O. Edet</strong>, R. Horchani, A. Abdel-aty, N.A. Alshehri, S.K. Elagan</div>
  <div class="pub-journal"><i>Few-Body Systems</i> <strong>62</strong>(4) (2021) &ndash; <a href="https://doi.org/10.1007/s00601-021-01693-2">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Analysis of the impact of external fields on the energy spectra and thermo-magnetic properties of N  2,I  2,CO,NO and HCl diatomic molecules</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>Molecular Physics</i> <strong>119</strong>(23) (2021) &ndash; <a href="https://doi.org/10.1080/00268976.2021.1957170">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Solar energy: A panacea for the electricity generation crisis in Nigeria</div>
  <div class="pub-authors">Emmanuel.P. Agbo, <strong>Collins.O. Edet</strong>, Thomas.O. Magu, Armstrong.O. Njok, Chris.M. Ekpo, Hitler Louis</div>
  <div class="pub-journal"><i>Heliyon</i> <strong>7</strong>(5) (2021) &ndash; <a href="https://doi.org/10.1016/j.heliyon.2021.e07016">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effects of Topological Defect on the Energy Spectra and Thermo-magnetic Properties of CO Diatomic Molecule</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot</div>
  <div class="pub-journal"><i>Journal of Low Temperature Physics</i> <strong>203</strong>(1-2), 84-111 (2021) &ndash; <a href="https://doi.org/10.1007/s10909-021-02577-9">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Persistent Current, Magnetic Susceptibility, and Thermal Properties for a Class of Yukawa Potential in the Presence of External Magnetic and Aharanov–Bohm Fields</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, A.N. Ikot, U.S. Okorie, G.J. Rampho, M. Ramantswana, R. Horchani, H. Abdullah, J.A. Vinasco, C.A. Duque, Abdel-Haleem Abdel-Aty</div>
  <div class="pub-journal"><i>International Journal of Thermophysics</i> <strong>42</strong>(10) (2021) &ndash; <a href="https://doi.org/10.1007/s10765-021-02891-0">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Thermodynamic functions for diatomic molecules with modified Kratzer plus screened Coulomb potential</div>
  <div class="pub-authors">U.S. Okorie, <strong>C.O. Edet</strong>, A.N. Ikot, G.J. Rampho, R. Sever</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>95</strong>(3), 411-421 (2021) &ndash; <a href="https://doi.org/10.1007/s12648-019-01670-w">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Effect of the deformation parameter on the nonrelativistic energy spectra of the q-deformed Hulthen-quadratic exponential-type potential</div>
  <div class="pub-authors">Ushie Patrick Obogo, Ofem Egbe Ubi, <strong>Collins Okon Edet</strong>, Akpan Ndem Ikot</div>
  <div class="pub-journal"><i>Ecletica Quimica</i> <strong>46</strong>(4), 60-73 (2021) &ndash; <a href="https://doi.org/10.26850/1678-4618eqj.v46.4.2021.p60-73">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Bound and scattering states solutions of the Klein–Gordon equation with generalized Mobius square potential in D-dimensions</div>
  <div class="pub-authors">Uduakobong S. Okorie, Akpan N. Ikot, <strong>Collins O. Edet</strong>, Gaotsiwe J. Rampho, Ridha Horchani, Haikel Jelassi</div>
  <div class="pub-journal"><i>European Physical Journal D</i> <strong>75</strong>(2) (2021) &ndash; <a href="https://doi.org/10.1140/epjd/s10053-021-00059-x">DOI</a></div>
</div>
<h3 class="pub-year">2020</h3>
<div class="pub-entry">
  <div class="pub-title">Bound state solutions of the Schrödinger equation with energy-dependent molecular Kratzer potential via asymptotic iteration method</div>
  <div class="pub-authors">Akpan Ndem Ikot, Uduakobong Okorie, Alalibo Thompson Ngiangia, Clement Atachegbe Onate, <strong>Collins Okon Edet</strong>, Ita Okon Akpan, Precious Ogbonda Amadi</div>
  <div class="pub-journal"><i>Ecletica Quimica</i> <strong>45</strong>(1), 65-76 (2020) &ndash; <a href="https://doi.org/10.26850/1678-4618eqj.v45.1.p65-76">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Bound state solutions of the Schrodinger equation for the modified Kratzer potential plus screened Coulomb potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, U.S. Okorie, A.T. Ngiangia, A.N. Ikot</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>94</strong>(4), 425-433 (2020) &ndash; <a href="https://doi.org/10.1007/s12648-019-01477-9">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Superstatistics of Schrödinger equation with pseudo-harmonic potential in external magnetic and Aharanov-Bohm fields</div>
  <div class="pub-authors">A.N. Ikot, U.S. Okorie, G. Osobonye, P.O. Amadi, <strong>C.O. Edet</strong>, M.J. Sithole, G.J. Rampho, R. Sever</div>
  <div class="pub-journal"><i>Heliyon</i> <strong>6</strong>(4) (2020) &ndash; <a href="https://doi.org/10.1016/j.heliyon.2020.e03738">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Thermal properties of Deng–Fan–Eckart potential model using Poisson summation approach</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, U.S. Okorie, G. Osobonye, A.N. Ikot, G.J. Rampho, R. Sever</div>
  <div class="pub-journal"><i>Journal of Mathematical Chemistry</i> <strong>58</strong>(5), 989-1013 (2020) &ndash; <a href="https://doi.org/10.1007/s10910-020-01107-4">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Relativistic treatment of the hellmann-generalized morse potential</div>
  <div class="pub-authors">P.O. Okoi, <strong>C.O. Edet</strong>, T.O. Magu</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica</i> <strong>66</strong>(1), 1-13 (2020) &ndash; <a href="https://doi.org/10.31349/RevMexFis.66.1">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Analytic solutions of the Schrödinger equation with non-central generalized inverse quadratic Yukawa potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Okoi, S.O. Chima</div>
  <div class="pub-journal"><i>Revista Brasileira de Ensino de Fisica</i> <strong>42</strong> (2020) &ndash; <a href="https://doi.org/10.1590/1806-9126-RBEF-2019-0083">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Solutions of Schrödinger equation and thermal properties of generalized trigonometric Pöschl-Teller potential</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Amadi, U.S. Okorie, A. Taş, A.N. Ikot, G. Rampho</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica</i> <strong>66</strong>(6), 824-839 (2020) &ndash; <a href="https://doi.org/10.31349/RevMexFis.66.824">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Any l-state solutions of the Schrodinger equation interacting with Hellmann–Kratzer potential model</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, Kalu Okam Okorie, Hitler Louis, Nelson A. Nzeata-Ibe</div>
  <div class="pub-journal"><i>Indian Journal of Physics</i> <strong>94</strong>(2), 243-251 (2020) &ndash; <a href="https://doi.org/10.1007/s12648-019-01467-x">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Thermodynamic properties of Aharanov–Bohm (AB) and magnetic fields with screened Kratzer potential</div>
  <div class="pub-authors">Akpan N. Ikot, <strong>Collins O. Edet</strong>, Precious O. Amadi, Uduakobong S. Okorie, Gaotsiwe J. Rampho, Hewa Y. Abdullah</div>
  <div class="pub-journal"><i>European Physical Journal D</i> <strong>74</strong>(7) (2020) &ndash; <a href="https://doi.org/10.1140/epjd/e2020-10084-9">DOI</a></div>
</div>
<h3 class="pub-year">2019</h3>
<div class="pub-entry">
  <div class="pub-title">Solutions of the klein gordon equation with generalized hyperbolic potential in d-dimensions</div>
  <div class="pub-authors">Uduakobong S. Okorie, Akpan N. Ikot, <strong>C.O. Edet</strong>, I.O. Akpan, R. Sever, G.J. Rampho</div>
  <div class="pub-journal"><i>Journal of Physics Communications</i> <strong>3</strong>(9) (2019) &ndash; <a href="https://doi.org/10.1088/2399-6528/ab42c6">DOI</a></div>
</div>
<div class="pub-entry">
  <div class="pub-title">Any l-state solutions of the Schrödinger equation for q-deformed Hulthen plus generalized inverse quadratic Yukawa potential in arbitrary dimensions</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, P.O. Okoi</div>
  <div class="pub-journal"><i>Revista Mexicana de Fisica</i> <strong>65</strong>(4), 333-344 (2019) &ndash; <a href="https://doi.org/10.31349/REVMEXFIS.65.333">DOI</a></div>
</div>
</div>

<div id="pub-book" class="pub-tab-content">
<div class="pub-entry">
  <div class="pub-title">Recent progress in graphene quantum dots for energy applications and storage devices: A review</div>
  <div class="pub-authors"><strong>C.O. Edet</strong>, E.P. Agbo, H.O. Edet, Nnanake-Abasi O. Offiong, John B. Edet, E.B. Ettah</div>
  <div class="pub-journal"><i>Graphene Quantum Dots (GQDs): Advances in Research and Applications</i> , 141-163 (2024)</div>
</div>
</div>

<div id="pub-conf" class="pub-tab-content">
<div class="pub-entry">
  <div class="pub-title">Stationary entanglement in hybrid optomechanical systems</div>
  <div class="pub-authors">Fatin Yusoff, Muhammad Zulkifli, Norshamsuri Ali, <strong>Collins Edet</strong>, Muhammad Asjad, Rosdisham Endut, Syed Aljunid, Mat Ismail</div>
  <div class="pub-journal"><i>AIP Conference Proceedings</i> <strong>2898</strong>(1) (2024) &ndash; <a href="https://doi.org/10.1063/5.0195712">DOI</a></div>
</div>
</div>

<script>
function showPubTab(tabId, btn) {
  document.querySelectorAll('.pub-tab-content').forEach(function(el) { el.classList.remove('active'); });
  document.querySelectorAll('.pub-tab-btn').forEach(function(el) { el.classList.remove('active'); });
  document.getElementById('pub-' + tabId).classList.add('active');
  btn.classList.add('active');
}
</script>
