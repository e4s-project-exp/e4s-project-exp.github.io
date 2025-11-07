---
layout: home
title: "E4S: HPC-AI Software Ecosystem for Science"
excerpt: "Performance-portable libraries & tools for advanced computing"
layout: splash # Default: home, but that includes a list of posts
classes: wide
header:
#   overlay_color: "#000"
#  overlay_filter: "0.60"
  overlay_filter: rgba(0, 146, 202, 0.75) # Same color as "air" skin footer
  overlay_image: /assets/images/e4s-logo.jpg
permalink: "/"
---


Welcome to **E4S**, the *Ecosystem for Scientific Software* — an open-source, community-driven collection of high-quality HPC and AI libraries and tools. E4S enables scientists, developers, and institutions to develop, deploy, and run performance-portable applications across CPUs and GPUs from NVIDIA, AMD, Intel, and Arm. Ready to adapt to new architectures as they emerge.

Supported by the **U.S. Department of Energy (DOE)** and its partners, E4S accelerates scientific innovation on systems ranging from laptops to exascale supercomputers.

<style>
.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}
.feature-item {
  background: #f8f9fa;
  border-radius: 12px;
  text-align: center;
  padding: 1.5rem;
  box-shadow: 0 1px 3px rgba(0,0,0,0.1);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.feature-item:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 10px rgba(0,0,0,0.12);
}
.feature-item svg {
  width: 64px;
  height: 64px;
  margin-bottom: 10px;
  stroke: #0092CA;
  stroke-width: 1.8;
  fill: none;
}
.feature-item h3 {
  color: #0092CA;
  font-size: 1.25rem;
  margin-bottom: 0.5rem;
}
.feature-item p {
  font-size: 0.95rem;
  color: #444;
}
</style>

<div class="feature-grid">

<div class="feature-item">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M9 9h6v6H9z"/></svg>
<h3>Performance Portability</h3>
<p>Run anywhere—from laptops to exascale supercomputers using modern GPU and CPU architectures.</p>
</div>

<div class="feature-item">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect x="3" y="3" width="18" height="6" rx="1"/><rect x="3" y="9" width="18" height="6" rx="1"/><rect x="3" y="15" width="18" height="6" rx="1"/></svg>
<h3>Curated Software Ecosystem</h3>
<p>Over 120 interoperable libraries for HPC and AI workflows, validated for research and production use.</p>
</div>

<div class="feature-item">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 5V3m0 18v-2m9-7h2M3 12H1m16.95 5.95l1.414 1.414M5.636 5.636 4.222 4.222M18.364 5.636l1.414-1.414M5.636 18.364 4.222 19.778"/><circle cx="12" cy="12" r="5"/></svg>
<h3>Reproducible Environments</h3>
<p>Deploy via Spack or pre-built containers for Docker, Singularity, and cloud environments.</p>
</div>

<div class="feature-item">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M4 7h16M4 12h8M4 17h4M15 16l2 2 3-3"/></svg>
<h3>Continuous Validation</h3>
<p>E4S packages are tested across DOE leadership and cloud platforms for quality and reproducibility.</p>
</div>

</div>

---
<p style="text-align:center;">
    <strong style="font-size: 1.5em;">Trusted by the HPC-AI Community</strong>
</p>
E4S is developed and supported by contributors from U.S. national laboratories, universities, and industry partners. It is available as both open-source and commercial distributions such as [ParaTools Pro for E4S™](https://paratoolspro.com).

---

<p style="text-align:center;">
    <strong>Ask me anything:</strong>
</p>
{% include e4s-bot-button.html %}


{% include e4s-footer.html %}