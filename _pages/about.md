---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a junior undergraduate student at **Zhejiang University**, majoring in **Optoelectronic Information Science and Engineering**. I am a member of the *Chu Kochen Honors College (Mixed Class)*, an elite program for the top 5% of students.

My research interests lie at the intersection of **Quantum Nanophotonics** and **Computational Physics**. I am particularly interested in developing novel quantum light sources and exploring electron transport properties in low-dimensional materials using methods like NEGF and DFT.

I am currently looking for PhD opportunities starting in **Fall 2027**.

## Education
* **Zhejiang University** (2023 - Present)
  * B.Eng. in Optoelectronic Information Science and Engineering
  * **GPA:** 4.60/5.00 | **Rank:** 4/162 (CKC Honors College)
  * **Awards:** National Scholarship (Top 0.2%), First-Class Scholarship of ZJU, OPPO "benfen" Scholarship(8 students per year)

## Research

My work sits on the boundary between photonics and electron transport: integrated quantum photonics and on-chip quantum light sources, first-principles modelling of optoelectronic devices with NEGF, DFT/DFPT and Wannier functions, and the hybrid integration of low-dimensional materials on silicon photonic platforms. What draws me to this boundary is that the performance of a photonic device is so often decided by the electrons driving it — by transport across an interface, by the phonons that scatter them, by the statistics of the current feeding an emitter. I would like my modelling to stay answerable to measurement.

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

<article class="research-entry">
  <div class="research-entry__meta">
    <div class="research-entry__logos"></div>
    <div class="research-entry__period">Apr 2025 - Present</div>
  </div>
  <div class="research-entry__content">
    <h3><a href="/portfolio/2025-01-gold-nanowire/">Student Researcher &middot; Electrically Driven Non-Classical Light from Gold Atomic Chains</a></h3>
    <p class="research-entry__institution">State Key Laboratory of Extreme Photonics and Instrumentation, Zhejiang University</p>
    <p class="research-entry__advisor">Advisor: Prof. Haoliang Qian</p>
    <p>Built an end-to-end quantum-transport model of a gold atomic-chain junction: the transport Hamiltonian from fully relativistic DFT in Quantum ESPRESSO projected onto Wannier functions, vibrational modes from DFPT, and leads coupled through bulk self-energies. Solved the non-equilibrium Green's function problem beyond the wide-band limit with electron&ndash;phonon coupling in the self-consistent Born approximation, implementing the pipeline in Python on HPC clusters. Computing the current noise as well as the current showed the emitted electroluminescence to be sub-Poissonian, with a Fano factor well below unity, and quantified how electron&ndash;phonon scattering and substitutional doping reshape the photon statistics. Coupling the transport model to full-wave simulations of a plasmonic nanocube dimer then linked the emitter statistics to its local electromagnetic environment.</p>
  </div>
</article>

<article class="research-entry">
  <div class="research-entry__meta">
    <div class="research-entry__logos"></div>
    <div class="research-entry__period">Sep 2024 - Sep 2025</div>
  </div>
  <div class="research-entry__content">
    <h3><a href="/portfolio/2024-09-microscope/">Student Researcher &middot; Modular Fluorescence Microscope Design</a></h3>
    <p class="research-entry__institution">Zhejiang University</p>
    <p class="research-entry__advisor">Advisor: Prof. Yubing Han</p>
    <p>Worked on making biological imaging hardware cheaper and easier to reconfigure. Designed and hand-assembled a fluorescence microscope on a modular Lego framework for low-cost customisation, and ran optical-path simulation and optimisation in Zemax OpticStudio to hold imaging quality and fluorescence collection efficiency.</p>
  </div>
</article>

<article class="research-entry">
  <div class="research-entry__meta">
    <div class="research-entry__logos"></div>
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

<p style="margin-bottom: 1.2rem; color: #7b858d; font-size: 0.72rem;">&dagger; equal contribution &nbsp;&middot;&nbsp; * corresponding author</p>

<article class="publication-card publication-card--no-teaser" itemscope itemtype="http://schema.org/ScholarlyArticle">
  <div class="publication-card__body">
    <h3 class="publication-card__title" itemprop="headline">Sub-Poissonian Electroluminescence from Resonant Inelastic Tunnelling in One-Dimensional Gold Atomic Chains</h3>
    <p class="publication-card__authors"><strong>Hongyi Yang</strong>&dagger;, Haipeng Zhu&dagger;, Shiyu Feng, Zexi Lu, Xiyao Peng, Hongsheng Chen*, Sihan Zhao*, Dexin Ye*, and Haoliang Qian*</p>
    <p class="publication-card__venue">Under revision at <i>ACS Photonics</i>, 2026 &mdash; both referees recommend publication</p>
    <p class="publication-card__excerpt">Shows that a two-terminal atomic-scale junction can act as an electrically driven source of antibunched light. The transport Hamiltonian is built from fully relativistic DFT projected onto Wannier functions and the non-equilibrium Green's function problem is solved beyond the wide-band limit, with electron&ndash;phonon coupling treated in the self-consistent Born approximation. Computing the current noise rather than the current alone reveals that electroluminescence from resonant inelastic tunnelling is sub-Poissonian, with a Fano factor far below the classical value of one.</p>
  </div>
</article>

<article class="publication-card publication-card--no-teaser" itemscope itemtype="http://schema.org/ScholarlyArticle">
  <div class="publication-card__body">
    <h3 class="publication-card__title" itemprop="headline">Physically Grounded Neural Networks: From Physical Substrates to Physics-Integrated Learning</h3>
    <p class="publication-card__authors"><strong>Hongyi Yang</strong>, Wendi Xia, Jun Li, Dexin Ye*, and Haoliang Qian*</p>
    <p class="publication-card__venue">Under review at <i>Applied Physics Reviews</i>, 2026</p>
    <p class="publication-card__excerpt">Asks what it means to constrain a learning model by the physics of the medium that carries out the computation, rather than treating that hardware as a black box. The review argues the question at the level of architecture rather than of any single device, mapping the design space from physical computing substrates through to physics-integrated learning.</p>
  </div>
</article>

<!-- To add a thumbnail to a paper: drop the image in /images/, remove the
     publication-card--no-teaser class from the <article>, and add

       <div class="publication-card__teaser" aria-hidden="true">
         <img src="/images/YOUR_IMAGE.png" alt="" />
       </div>

     as the first child of the <article>. Links go after the excerpt as
     <a class="publication-card__link" href="...">[Paper]</a>. -->

## News
* **Nov 2025:** I was honored as one of the **Top Ten College Students** at the School of Optoelectrics.
* **Dec 2024:** I received the **National Scholarship** from the Ministry of Education of China!
* **Oct 2024:** My team won the **First Prize** in the Zhejiang Provincial College Physics Competition.
