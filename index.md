---
title: Nervous System Study Map
---

<style>
  .section { margin: 24px 0; }
  .center { text-align: center; }
  .embed-wrap { margin: 24px auto 40px; max-width: 1200px; }
  .embed-16x9 { position: relative; width: 100%; padding-bottom: 56.25%; }
  .embed-16x9 iframe { position: absolute; inset: 0; width: 100%; height: 100%; border: 0; }

  .two-col { 
    display: grid; 
    grid-template-columns: 1fr 1fr; 
    gap: 28px; 
    align-items: start;
  }
  @media (max-width: 900px) {
    .two-col { grid-template-columns: 1fr; }
  }

  details { margin: 8px 0 14px 0; }
  summary { cursor: pointer; font-size: 1.05rem; }
  h2, h3 { margin: 8px 0 12px; }
</style>

# Nervous System Study Map

---

## 🧠 Brain-Only 3D Model (loads brain view)

<div class="embed-wrap center">
  <div class="embed-16x9">
    <iframe 
      src="https://human.biodigital.com/widget/?camera=14.881%2C169.834%2C-8.059%2C-0.382%2C168.21%2C6.604%2C-0.055%2C0.997%2C0.053&dk=b2400ef8a45168336af043e68f426b11e5e6a546&initial.hand-hint=true&m=production%2FmaleAdult%2Fbrain.json&ui-annotations=true&ui-dissect=true&ui-fullscreen=false&ui-isolate=true&ui-share=false&ui-tools-display=primary&ui-xray=true"
      allowfullscreen
      loading="lazy">
    </iframe>
  </div>
</div>

---

## Maps: CNS | PNS

<div class="two-col">

  <!-- CNS Map -->
  <div class="section">
    <h2>🧩 Central Nervous System (CNS)</h2>

    <details open>
      <summary><b>Motor (Descending Tracts)</b></summary>
      <ul>
        <li><b>Lateral corticospinal</b> — decussates medulla → synapse anterior horn → controls voluntary limb movement</li>
        <li><b>Anterior corticospinal</b> — decussates at spinal cord levels → controls axial/postural muscles</li>
        <li><b>Medial corticospinal</b> — bilateral to trunk/neck/shoulders</li>
        <li><b>Rubrospinal</b> — origin in red nucleus → decussates midbrain → influences upper extremity flexors</li>
        <li><b>Reticulospinal</b> — posture, locomotion, reflex modulation</li>
        <li><b>Vestibulospinal</b> — balance and head position control (extensors)</li>
        <li><b>Tectospinal</b> — from superior colliculus → decussates midbrain → head/eye orientation reflexes</li>
      </ul>
    </details>

    <details open>
      <summary><b>Sensory (Ascending Tracts)</b></summary>
      <ul>
        <li><b>DCML</b> — 1st-order DRG → synapse nucleus gracilis/cuneatus in medulla → 2nd-order decussates → thalamus (VPL) → cortex; vibration, proprioception, fine touch</li>
        <li><b>Spinothalamic (Anterolateral)</b>
          <ul>
            <li><b>Fast pain</b> — Aδ, glutamate; 1st-order DRG → synapse dorsal horn → 2nd-order decussates anterior white commissure → ascend → VPL → cortex</li>
            <li><b>Slow pain</b> — C, Substance P; 1st-order DRG → synapse dorsal horn → 2nd-order decussates in cord → divergent ascent to thalamus / limbic</li>
          </ul>
        </li>
        <li><b>Divergent pathways</b> — spinomesencephalic, spinoreticular, spino-emotional</li>
        <li><b>Spinocerebellar</b> — posterior, cuneocerebellar, anterior (double decussation → functional ipsilateral), rostrospinocerebellar</li>
        <li><b>Trigeminal pathways</b> — trigeminothalamic → synapse VPM → cortex; trigeminoreticulolimbic (slow pain) </li>
      </ul>
    </details>

    <details>
      <summary><b>Clinical Signs</b></summary>
      <ul>
        <li>UMN lesion → spasticity, hyperreflexia, Babinski</li>
        <li>LMN lesion → flaccid paralysis, atrophy</li>
        <li>DCML lesion → loss of vibration/proprioception</li>
        <li>Spinothalamic lesion → loss of pain/temp (contralateral below lesion)</li>
        <li>Spinocerebellar lesion → ataxia</li>
      </ul>
    </details>

  </div>

  <!-- PNS Map -->
  <div class="section">
    <h2>🌐 Peripheral Nervous System (PNS)</h2>

    <details open>
      <summary><b>Development</b></summary>
      <ul>
        <li>Ectoderm → CNS, PNS, skin, sensory organs</li>
        <li>Neural tube → CNS</li>
        <li>Neural crest → DRG & Schwann & autonomic ganglia</li>
      </ul>
    </details>

    <details open>
      <summary><b>Spinal roots & distal anatomy</b></summary>
      <ul>
        <li>Conus medullaris (ends at ~L1-L2)</li>
        <li>Cauda equina</li>
        <li>Filum terminale</li>
      </ul>
    </details>

    <details open>
      <summary><b>Sensory fibers</b></summary>
      <ul>
        <li>Aα — proprioception, fastest</li>
        <li>Aβ — touch & vibration</li>
        <li>Aδ — sharp pain, cold</li>
        <li>C — dull pain, warm</li>
      </ul>
    </details>

    <details open>
      <summary><b>Motor (LMN)</b></summary>
      <ul>
        <li>Anterior horn cell → peripheral nerve → neuromuscular junction (NMJ)</li>
      </ul>
    </details>

  </div>

</div>
