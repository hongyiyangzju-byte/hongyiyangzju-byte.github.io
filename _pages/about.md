---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- NOTE: the raw HTML blocks below are indented one space per level on
     purpose. Four or more leading spaces would make kramdown read them as a
     code block and print the tags verbatim. -->

I am a final-year undergraduate student at **Zhejiang University**, majoring in **Optoelectronic Information Science and Engineering** as a member of the *Chu Kochen Honors College (Mixed Class)*.

My work is on **integrated quantum photonics and on-chip quantum light sources**, approached through **first-principles modelling of optoelectronic devices** — NEGF, DFT/DFPT and Wannier functions — and on the **hybrid integration of low-dimensional materials on silicon photonic platforms**. What keeps me at this boundary is that the performance of a photonic device is so often decided by the electrons driving it: transport across an interface, the phonons that scatter them, the statistics of the current feeding an emitter.

I have two first-author manuscripts under review, and in 2026 I spent a term as a visiting researcher at **Stanford University**. I am currently looking for PhD opportunities starting in **Fall 2027**.

## Education
* **Zhejiang University** (Sep 2023 - Jun 2027, expected)
  * B.Eng. in Optoelectronic Information Science and Engineering
  * *Chu Kochen Honors College* (Mixed Class, Honors Program)
  * **GPA:** 4.11/4.30 | **Rank:** 4/162 (Chu Kochen Honors College), 4/102 (School of Optoelectronic Science and Engineering)
  * **Scholarships:** National Scholarship (highest national honour for undergraduates in China, top 0.2%), Huawei Elite Scholarship, OPPO "Benfen" Scholarship (8 recipients nationwide per year), First-Class Scholarship of Zhejiang University

## Research

My work sits on the boundary between photonics and electron transport: integrated quantum photonics and on-chip quantum light sources, first-principles modelling of optoelectronic devices with NEGF, DFT/DFPT and Wannier functions, and the hybrid integration of low-dimensional materials on silicon photonic platforms. I would like my modelling to stay answerable to measurement.

<div class="research-timeline">

<article class="research-entry">
 <div class="research-entry__meta">
  <div class="research-entry__logos"></div>
  <div class="research-entry__period">Jul 2026 - Oct 2026<br /><span>(on-site)</span></div>
 </div>
 <div class="research-entry__content">
  <h3>Visiting Undergraduate Research Intern &middot; Strain Engineering of Halide Perovskite Heterostructures</h3>
  <p class="research-entry__institution">Xu Research Group, Stanford University, USA</p>
  <p class="research-entry__advisor">Advisor: Prof. Sheng Xu</p>
  <p>Built DFT models of epitaxially strained halide-perovskite heterostructures in Quantum ESPRESSO, and quantified how epitaxial compressive strain reshapes the lattice and the band structure of the epilayer — giving design guidance for perovskite optoelectronic devices.</p>
 </div>
</article>

<article class="research-entry research-entry--zju">
 <div class="research-entry__meta">
  <div class="research-entry__logos"><img src="/images/zju-logo.png" alt="Zhejiang University" /></div>
  <div class="research-entry__period">Apr 2025 - Present</div>
 </div>
 <div class="research-entry__content">
  <h3><a href="/portfolio/2025-01-gold-nanowire/">Student Researcher &middot; Electrically Driven Non-Classical Light from Gold Atomic Chains</a></h3>
  <p class="research-entry__institution">State Key Laboratory of Extreme Photonics and Instrumentation, Zhejiang University</p>
  <p class="research-entry__advisor">Advisor: Prof. Haoliang Qian</p>
  <p>Built an end-to-end quantum-transport model of a gold atomic-chain junction: the transport Hamiltonian from fully relativistic DFT in Quantum ESPRESSO projected onto Wannier functions, vibrational modes from DFPT, and leads coupled through bulk self-energies. Solved the non-equilibrium Green's function problem beyond the wide-band limit with electron&ndash;phonon coupling in the self-consistent Born approximation, implementing the pipeline in Python on HPC clusters. Computing the current noise as well as the current showed the emitted electroluminescence to be sub-Poissonian, with a Fano factor well below unity, and quantified how electron&ndash;phonon scattering and substitutional doping reshape the photon statistics. Coupling the transport model to full-wave simulations of a plasmonic nanocube dimer then linked the emitter statistics to its local electromagnetic environment.</p>
 </div>
</article>


<article class="research-entry research-entry--zju">
 <div class="research-entry__meta">
  <div class="research-entry__logos"><img src="/images/zju-logo.png" alt="Zhejiang University" /></div>
  <div class="research-entry__period">Sep 2023 - Jun 2024</div>
 </div>
 <div class="research-entry__content">
  <h3><a href="/portfolio/2023-09-perovskite/">Research Assistant &middot; Perovskite Optoelectronic Devices</a></h3>
  <p class="research-entry__institution">Zhejiang University</p>
  <p class="research-entry__advisor">Advisor: Prof. Dawei Di</p>
  <p>Joined the experimental fabrication of next-generation optoelectronic materials. Learned the full cleanroom process for perovskite devices, including spin-coating and encapsulation, then designed and built an optical measurement setup to characterise the external quantum efficiency of the devices we made.</p>
 </div>
</article>

</div>

## Publications

<p class="publication-legend">&dagger; equal contribution &nbsp;&middot;&nbsp; &ast; corresponding author</p>

<article class="publication-card" itemscope itemtype="http://schema.org/ScholarlyArticle">
 <div class="publication-card__teaser" aria-hidden="true">
  <img src="/images/pub-gold-atomic-chains.png" alt="" />
 </div>
 <div class="publication-card__body">
  <h3 class="publication-card__title" itemprop="headline">Sub-Poissonian electroluminescence from resonant inelastic tunnelling in one-dimensional gold atomic chains</h3>
  <p class="publication-card__authors"><strong>Hongyi Yang</strong>&dagger;, Haipeng Zhu&dagger;, Shiyu Feng, Zexi Lu, Xiyao Peng, Hongsheng Chen&ast;, Sihan Zhao&ast;, Dexin Ye&ast;, and Haoliang Qian&ast;</p>
  <p class="publication-card__venue">Under revision at <i>ACS Photonics</i>, 2026 &mdash; both referees recommend publication</p>
  <p class="publication-card__excerpt">Electrically driven single-photon sources usually inherit the electrical shot noise of Poissonian carrier injection. This work suppresses that bottleneck at its origin, using a one-dimensional gold atomic chain as an atomic-scale quantum conductor: DFT-parameterised non-equilibrium Green's-function calculations show that resonant tunnelling through a d<sub>z&sup2;</sub>-dominated ballistic channel removes the electronic partition noise and yields a sub-Poissonian current, while the same 1D spectrum opens a resonant inelastic channel with an intrinsic plasmon-excitation efficiency near 80%. Coupled to a nanometre-scale plasmonic antenna, it predicts antibunched electroluminescence with a projected photon-generation efficiency of about 60% and g<sup>(2)</sup>(0) &asymp; 0.</p>
 </div>
</article>

<article class="publication-card" itemscope itemtype="http://schema.org/ScholarlyArticle">
 <div class="publication-card__teaser" aria-hidden="true">
  <img src="/images/pub-physically-grounded-nn.png" alt="" />
 </div>
 <div class="publication-card__body">
  <h3 class="publication-card__title" itemprop="headline">Physically Grounded Neural Networks: From Physical Substrates to Physics-Integrated Learning</h3>
  <p class="publication-card__authors"><strong>Hongyi Yang</strong>, Wendi Xia, Jun Li, Dexin Ye&ast;, and Haoliang Qian&ast;</p>
  <p class="publication-card__venue">Under review at <i>Applied Physics Reviews</i>, 2026</p>
  <p class="publication-card__excerpt">A review of two complementary routes beyond purely digital scaling: physical neural networks, in which optical, quantum, memristive or biomolecular substrates carry out the neural transformation, and physics-integrated learning, in which scientific laws restrict the hypothesis space of the model. It surveys trainable physical neural networks, neural operators, hard-constrained scientific machine learning and Kolmogorov&ndash;Arnold architectures, and argues that a network is only physically grounded when it satisfies both conditions inside one training loop &mdash; a pairing the review frames as emerging rather than established.</p>
 </div>
</article>

## News
* **Jul 2026:** I began a visiting research internship in **Prof. Sheng Xu's group at Stanford University**, working on strain engineering of halide perovskite heterostructures.
* **Nov 2025:** I was honored as one of the **Top Ten College Students** at the School of Optoelectrics.
* **Dec 2024:** I received the **National Scholarship** from the Ministry of Education of China!
* **Oct 2024:** My team won the **First Prize** in the Zhejiang Provincial College Physics Competition.
