---
layout: default
title: Style-guide
permalink: /styleguide/
---

<style>
.color-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  margin: 2rem 0;
}

.color-tile {
  flex: 1 1 150px;
  max-width: 180px;
  border: 1px solid #ccc;
  border-radius: 6px;
  padding: 1rem;
  text-align: center;
  background: #fff;
  box-shadow: 0 1px 2px rgba(0,0,0,0.04);
}

.color-tile .swatch {
  width: 100%;
  height: 40px;
  border-radius: 4px;
  margin-bottom: 0.5rem;
  border: 1px solid #999;
}

.color-tile code {
  display: block;
  font-size: 0.85rem;
  background: #f5f5f5;
  color: #333;
  border: 1px solid #ddd;
  border-radius: 4px;
  padding: 0.2rem 0.4rem;
  margin: 0.25rem 0;
}

table.typography {
  width: 100%;
  border-collapse: collapse;
  margin-top: 2rem;
}
table.typography th,
table.typography td {
  text-align: left;
  padding: 0.5rem;
  border: 1px solid #ddd;
}
table.typography th {
  background: #f5f5f5;
}
</style>

<section id="styleguideAll" class="section">
  <div class="section-text">

  Basic style guide to surface styles / colours and test components work.
  <br>
  <h2>🎨 Colours</h2>

  <h3>Primary</h3>
  <div class="color-grid">
    <div class="color-tile">
      <div class="swatch" style="background-color: #010100;"></div>
      <code>$color-dark</code>
      <code>#010100</code>
      <div>Text, footer background</div>
    </div>

    <div class="color-tile">
      <div class="swatch" style="background-color: #fdfbf9;"></div>
      <code>$color-light</code>
      <code>#fdfbf9</code>
      <div>Background, section base</div>
    </div>

    <div class="color-tile">
      <div class="swatch" style="background-color: #fe9400;"></div>
      <code>$color-orange</code>
      <code>#fe9400</code>
      <div>Accent, buttons, highlights</div>
    </div>
  </div>

  <h3>Accent</h3>
  <div class="color-grid">
    <div class="color-tile">
      <div class="swatch" style="background-color: #5e8a57;"></div>
      <code>$color-green</code>
      <code>#5e8a57</code>
      <div>Accent green</div>
    </div>

    <div class="color-tile">
      <div class="swatch" style="background-color: #436e82;"></div>
      <code>$color-blue</code>
      <code>#436e82</code>
      <div>Accent blue</div>
    </div>
  </div>

  <h3>Alternatives (not in use)</h3>
  <div class="color-grid">
    <div class="color-tile">
      <div class="swatch" style="background-color: #c46a2d;"></div>
      <code>$color-orange</code>
      <code>#c46a2d</code>
      <div>Burnt orange — calmer, still recognisable</div>
    </div>

    <div class="color-tile">
      <div class="swatch" style="background-color: #4f6f52;"></div>
      <code>$color-green</code>
      <code>#4f6f52</code>
      <div>Deeper, grounded green</div>
    </div>

    <div class="color-tile">
      <div class="swatch" style="background-color: #6b8ca7;"></div>
      <code>$color-blue</code>
      <code>#6b8ca7</code>
      <div>Muted blue — balance for calm sections</div>
    </div>

    <div class="color-tile">
      <div class="swatch" style="background-color: #4f4f4f;"></div>
      <code>$color-secondary-text</code>
      <code>#4f4f4f</code>
      <div>Friendly but firm secondary text</div>
    </div>
  </div>

  <h3>Typography</h3>
  <table class="typography">
    <thead>
      <tr>
        <th>Element</th>
        <th>Font Stack</th>
        <th>Weight</th>
        <th>Notes</th>
      </tr>
    </thead>

    <tbody>
      <tr>
        <td>Headers</td>
        <td><code>'area-extended', sans-serif</code></td>
        <td><code>500</code></td>
        <td>Used for all h1–h3</td>
      </tr>
      <tr>
        <td>Body Text</td>
        <td><code>'area', sans-serif</code></td>
        <td><code>normal</code></td>
        <td>Used for paragraphs and lists</td>
      </tr>
      <tr>
        <td>Line Height</td>
        <td><code>1.6</code> (body), <code>1.1</code> (lists)</td>
        <td>—</td>
        <td>Improves readability</td>
      </tr>
    </tbody>
  </table>

  </div>

  <br>
  <br>
</section>