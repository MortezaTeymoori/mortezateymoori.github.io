---
layout: page
title: Light Coils
permalink: /lightcoils/
description: MRI with fully optical data and power transmission
nav: true
---

<div class="lc-page">

<p class="lc-lead">
<strong>Light Coils</strong> are MRI receive coils that are powered, read out and detuned entirely over optical fibre, with no galvanic cables between the coil array and the scanner. We show <em>in vivo</em> human brain imaging at 3&nbsp;T with SNR comparable to a conventional coaxial readout, and a 4-channel array multiplexed over a single fibre.
</p>

<p>
Zining Liu<sup>†</sup>, <strong>Morteza Teymoori</strong><sup>†</sup>, Jakob Gerlach, Reza Aghabagheri, Henning Helmers, Michael Bock, Çağlar Ataman, Ali Caglar Özen<br>
<small><sup>†</sup>Equal contribution. University of Freiburg (Radiology · IMTEK) and Fraunhofer ISE.</small>
</p>

<div class="lc-buttons">
  <a class="primary" href="https://arxiv.org/abs/2607.04211">Read the preprint (arXiv)</a>
  <a href="https://arxiv.org/pdf/2607.04211">PDF</a>
  <a href="#contact">Get in touch</a>
</div>

<h2>Why it matters</h2>

<div class="lc-placeholder">
  [PLACEHOLDER: 2–4 sentences on the problem. E.g. what conductive cables cost you in dense MRI coil arrays (RF heating and safety, cable traps, cross-talk below 20 dB between neighbouring coax lines, bulk, the practical ~64-channel ceiling) and what replacing them with light enables.]
</div>

<figure class="lc-figure">
  <img src="{{ '/assets/img/lightcoils/fig1-concept.jpg' | relative_url }}" alt="Light Coils concept: optically connected receive-array modules, modular head arrays, and the optical power, data and detuning architecture" data-zoomable>
  <figcaption><strong>Fig. 1</strong> The Light Coils concept. (a) Lightweight, optically connected receive-array modules close to the patient. (b) Modular "array-of-arrays" head configurations. (c) One laser powers the on-coil LNAs through a photonic power converter (PPC); MR signals are put onto light by electro-optic modulators and wavelength-multiplexed out of the MR room, while detuning is also controlled optically.</figcaption>
</figure>

<h2>Key results</h2>

<div class="lc-results">
  <div class="lc-result">
    <span class="lc-number">5–10 mW</span>
    <span class="lc-label">Optical power at the modulator input needed to match the SNR of a galvanic coax link (with 80–100 mW into the PPC)</span>
  </div>
  <div class="lc-result">
    <span class="lc-number"><em>in vivo</em> 3 T</span>
    <span class="lc-label">Human brain imaging with a single-channel Light Coil: image quality and SNR comparable to the same coil read out over coax</span>
  </div>
  <div class="lc-result">
    <span class="lc-number">&gt;28 dB</span>
    <span class="lc-label">Inter-channel optical isolation for a 4-channel array, dense-WDM multiplexed over a single fibre</span>
  </div>
  <div class="lc-result">
    <span class="lc-number">≤ −21 dB</span>
    <span class="lc-label">Noise correlation between channels, vs. down to −13.6 dB for a matched coax array; lower g-factors in parallel imaging</span>
  </div>
</div>

<figure class="lc-figure">
  <img src="{{ '/assets/img/lightcoils/fig4-single-channel.jpg' | relative_url }}" alt="Image SNR versus PPC power, and in vivo brain images and SNR maps for the reference coil and the Light Coil" data-zoomable>
  <figcaption><strong>Fig. 4</strong> Single-channel Light Coil. (a) Phantom image SNR vs. optical power into the PPC for four optical link powers; the dashed line is the galvanic reference. (b, c) <em>In vivo</em> brain images and SNR maps, reference coil (top) vs. Light Coil (bottom).</figcaption>
</figure>

<figure class="lc-figure">
  <img src="{{ '/assets/img/lightcoils/fig5-4channel.jpg' | relative_url }}" alt="4-channel Light Coil array schematic, WDM isolation matrix, noise correlation matrices and g-factor maps" data-zoomable>
  <figcaption><strong>Fig. 5</strong> 4-channel Light Coil array. (a) Schematic. (b) WDM channel isolation/loss matrix. (c, d) Noise correlation for the Light Coil array vs. a matched coax reference array. (e) Phantom images and g-factor maps at R = 2 and R = 3 (g = 1.44 vs. 1.54 and 1.82 vs. 2.02).</figcaption>
</figure>

<figure class="lc-figure">
  <img src="{{ '/assets/img/lightcoils/fig6-invivo-4ch.jpg' | relative_url }}" alt="In vivo axial brain images with the 4-channel Light Coil array: GRE at R = 1 to 4 and MPRAGE" data-zoomable>
  <figcaption><strong>Fig. 6</strong> <em>In vivo</em> brain imaging with the 4-channel Light Coil array: 2D GRE without acceleration and with GRAPPA R = 2, 3, 4, and a T1-weighted 3D MPRAGE.</figcaption>
</figure>

<h2>How it works</h2>

<div class="lc-placeholder">
  [PLACEHOLDER: short explanation of the chain, aimed at an MR physicist who is not a photonics person: the MR signal is amplified on the coil and converted to light by a Mach–Zehnder modulator on a C-band carrier; a high-efficiency photovoltaic cell powers the LNA over fibre; a sequence-triggered optical path switches the coil between detuned and active states.]
</div>

<figure class="lc-figure">
  <img src="{{ '/assets/img/lightcoils/fig3-power.jpg' | relative_url }}" alt="Optical power transmission setup, noise figure and gain versus optical power, sequence timing, and detuning comparison" data-zoomable>
  <figcaption><strong>Fig. 3</strong> Optical power delivery and detuning. (a) Setup combining power-over-fibre, optical detuning and the analog optical data link. (b, c) Noise figure and gain of the PPC-powered LNA chain vs. optical power, with bench supply and battery references. (d) Sequence timing of the coil state. (e) Galvanic vs. 10 mW optical detuning vs. no detuning.</figcaption>
</figure>

<h2>Read more</h2>

<ul class="lc-links">
  <li><strong>Preprint:</strong> Z. Liu<sup>†</sup>, M. Teymoori<sup>†</sup>, J. Gerlach, R. Aghabagheri, H. Helmers, M. Bock, Ç. Ataman, A. C. Özen. <a href="https://arxiv.org/abs/2607.04211"><em>Light Coils: MRI with Fully Optical Data and Power Transmission</em></a>. arXiv:2607.04211 (2026). <a href="https://arxiv.org/bibtex/2607.04211">BibTeX</a></li>
  <li><strong>ISMRM 2026:</strong> Z. Liu, M. Teymoori, J. Gerlach, R. Aghabagheri, Ç. Ataman, M. Bock, A. Özen. <em>Multi-channel coil array with optical data transmission using wavelength division multiplexing.</em> Abstract 631-01-007.</li>
  <li><strong>ISMRM 2026:</strong> R. Aghabagheri, J. Gerlach, Z. Liu, M. Teymoori, Ç. Ataman, M. Bock, A. Özen. <em>Light-powered low noise amplifiers for MRI.</em> Abstract 631-01-008.</li>
  <li><strong>ISMRM 2025:</strong> J. Gerlach, Z. Liu, R. Aghabagheri, S. Liu, Ç. Ataman, M. Teymoori, M. Bock et al. <em>Optical detuning strategies for light coil elements.</em></li>
</ul>

<p><small>Figures reproduced from the arXiv preprint.</small></p>

<h2 id="contact">Contact</h2>

<div class="lc-qr">
  <img src="{{ '/assets/img/lightcoils/qr-lightcoils.svg' | relative_url }}" alt="QR code linking to this page">
  <div>
    <p><strong>Dr. Morteza Teymoori</strong><br>
    Microsystems for Biomedical Imaging Laboratory<br>
    IMTEK, University of Freiburg, Germany</p>
    <p>Interested in collaborating, or want to talk about optical coils? Email me at
    <a href="mailto:Morteza.Teymoori@imtek.uni-freiburg.de">Morteza.Teymoori@imtek.uni-freiburg.de</a>
    or connect on <a href="https://www.linkedin.com/in/morteza-teymoori-8061ab141">LinkedIn</a>.</p>
  </div>
</div>

</div>
