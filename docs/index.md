---
layout: default
title: DocuMenTor Project Website
---

<section class="container hero">
  <div class="left">
    <h1></h1>
    <p>DocuMenTor combines a DSL for defining the DMS metamodel with an automated generation layer that transforms the DSL specifications into complete, executable Python/Flask web applications.</p>
    <p>
      <a class="cta" href="#get-started">Get started</a>
    </p>
    <div class="card-grid">
      <article class="card">
        <h3>The DocuMenTor Environment</h3>
        <p>The provided DSL implemented with EMF/Xtext allows users to create textual instances describing the DMSs to generate, and declaring their sections, like slots, document types, and other metadata that may vary between each instance. Additionally, the DocuMenTor engine includes a code generator that transforms such models into the pure Flask/Python, HTML, CSS, and JavaScript files that constitute the generated DMS web applications which are automatically deployed.</p>
      </article>
      <article class="card">
        <h3>Video Demo</h3>
        <div style="display:flex;flex-direction:column;gap:16px;margin-top:12px;">
          <div>
            <p style="margin-bottom: 8px; font-weight: 600; color: #0b1220;">Video demo for the DocuMenTor website</p>
            <video controls style="width:100%;max-width:720px;background:#000;">
              <source src="{{ site.baseurl }}/assets/website.mov" type="video/quicktime">
              Your browser does not support the video tag. <a href="{{ site.baseurl }}/assets/website.mov">Download</a>
            </video>
          </div>
          <div>
            <p style="margin-bottom: 8px; font-weight: 600; color: #0b1220;">Video demo for the DocuMenTor Eclipse plug-in</p>
            <video controls style="width:100%;max-width:720px;background:#000;">
              <source src="{{ site.baseurl }}/assets/plugin.mov" type="video/quicktime">
              Your browser does not support the video tag. <a href="{{ site.baseurl }}/assets/plugin.mov">Download</a>
            </video>
          </div>
        </div>
      </article>
      <article class="card">
        <h3>Authors and Contributors</h3>
        <p>DocuMenTor has been developed by <a href="https://github.com/sara-abouelwafa" target="_blank" style="color: #5b4f9e; text-decoration: none; font-weight: 600;">Sara Abouelwafa</a> and <a href="https://github.com/gomezabajo" target="_blank" style="color: #5b4f9e; text-decoration: none; font-weight: 600;">Pablo Gómez-Abajo</a>.</p>
      </article>
      <article class="card">
        <h3>Related Publications</h3>
        <p>Abouelwafa, S., Gómez-Abajo, P., Arévalo Sarrate, C. (en preparación). <em>Towards a Model-based Framework for the Generation of Document Management Systems</em>.</p>
      </article>
    </div>
  </div>
</section>
