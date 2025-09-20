# Nervous System Study Map

---

## 🧠 Interactive Brain (Primary View)

<div class="embed-hero">
  <iframe
    title="Motor and Sensory Areas of the Cerebral Cortex"
    src="https://sketchfab.com/models/300c488c013f4d41ad5acab9ef08e50a/embed"
    allow="autoplay; fullscreen; xr-spatial-tracking"
    mozallowfullscreen="true"
    webkitallowfullscreen="true">
  </iframe>
</div>

<style>
  .embed-hero { position:relative; width:100%; height:72vh; min-height:520px; border:0; border-radius:10px; box-shadow:0 8px 28px rgba(0,0,0,.08); overflow:hidden; margin-bottom:30px; }
  .embed-hero iframe { position:absolute; inset:0; width:100%; height:100%; border:0; }
  .two-col { display:grid; grid-template-columns:1fr 1fr; gap:30px; }
  @media(max-width:960px){.two-col{grid-template-columns:1fr}}
  .tree { font-family: ui-monospace, monospace; white-space: pre-wrap; line-height:1.35; background:#fafafa; border:1px solid #eee; border-radius:8px; padding:14px 12px; }
  .syn { color:#1d4ed8; font-weight:700; }
  .dec { color:#dc2626; font-weight:700; }
</style>

---

## 📚 Concept Maps

<div class="two-col">

### 🧩 Central Nervous System (CNS)
<pre class="tree">CNS
│
├── Motor (Descending Tracts)
│   ├── Lateral corticospinal
│   │     └─ 1st → cortex
│   │         → <span class="dec">decussates</span> medulla (pyramids)
│   │         → <span class="syn">synapse</span> anterior horn
│   │         → fine voluntary limb movement
│   │
│   ├── Anterior corticospinal
│   │     └─ 1st → cortex
│   │         → <span class="dec">decussates</span> at spinal cord level
│   │         → axial / postural muscles
│   │
│   ├── Medial corticospinal — bilateral → trunk, neck, shoulders
│   ├── Rubrospinal → origin red nucleus → <span class="dec">decussates</span> midbrain → <span class="syn">synapse</span> anterior horn → UE flexors
│   ├── Reticulospinal → posture, locomotion, reflex modulation
│   ├── Vestibulospinal → balance, head position, extensors
│   └── Tectospinal → origin superior colliculus → <span class="dec">decussates</span> midbrain → reflex head/eye orientation
│
└── Sensory (Ascending Tracts)
    ├── DCML (Dorsal Column–Medial Lemniscus)
    │     └─ 1st DRG → <span class="syn">synapse</span> nucleus gracilis / cuneatus (medulla)
    │         → 2nd <span class="dec">decussates</span> internal arcuate fibers
    │         → ascend medial lemniscus
    │         → <span class="syn">synapse</span> thalamus (VPL)
    │         → 3rd cortex
    │         → modalities: vibration, proprioception, fine touch
    │
    ├── Spinothalamic (Anterolateral System)
    │     ├─ Fast pain (A-delta; glutamate)
    │     │     └─ 1st DRG → <span class="syn">synapse</span> dorsal horn
    │     │         → 2nd <span class="dec">decussates</span> anterior white commissure
    │     │         → ascend → VPL → 3rd cortex
    │     │
    │     └─ Slow pain (C fibers; Substance P)
    │           └─ 1st DRG → <span class="syn">synapse</span> dorsal horn
    │               → 2nd <span class="dec">decussates</span> in cord
    │               → divergent ascent → thalamus / limbic targets
    │
    ├── Divergent pathways → spinomesencephalic (PAG), spinoreticular (arousal), spino-emotional (limbic)
    ├── Spinocerebellar → posterior, cuneocerebellar, anterior (double <span class="dec">decussation</span> → ipsilateral), rostrospinocerebellar → nonconscious proprioception
    └── Trigeminal → trigeminothalamic (<span class="dec">decussates</span> pons → <span class="syn">synapse</span> VPM → cortex), trigeminoreticulolimbic (slow pain → reticular/limbic)
</pre>

### 🌐 Peripheral Nervous System (PNS)
<pre class="tree">PNS
│
├── Development
│   ├─ Ectoderm → CNS, PNS, epidermis, sensory organs
│   ├─ Neural tube → CNS
│   └─ Neural crest → DRG, Schwann cells, autonomic ganglia
│
├── Distal spinal anatomy
│   ├─ Conus medullaris → end of cord (≈L1–L2)
│   ├─ Cauda equina → lumbosacral roots
│   └─ Filum terminale → pia tether
│
├── Sensory (Afferent)
│   ├─ Receptors → mechanoreceptors (deformation), thermoreceptors (temp), nociceptors (pain), chemoreceptors (chemical), proprioceptors (position)
│   ├─ Fibers
│   │   ├─ Alpha-alpha → fastest; proprioception & motor
│   │   ├─ Alpha-beta → touch, vibration
│   │   ├─ Alpha-delta → sharp pain, cold
│   │   └─ C fibers → dull pain, warmth; slowest
│   ├─ Coding → tonic (constant) vs phasic (adapt)
│   └─ Pathway → 1st DRG → <span class="syn">synapse</span> dorsal horn/brainstem → CNS
│
├── Motor (Efferent)
│   ├─ LMN → anterior horn → axon → NMJ (ACh → nicotinic receptor)
│   ├─ Reflex arc → receptor → afferent → <span class="syn">synapse</span> cord → efferent → effector
│   ├─ LMN lesion → flaccid paralysis, fasciculations, atrophy, ↓ reflexes
│   └─ UMN lesion → spasticity, hyperreflexia, Babinski
│
├── Autonomic
│   ├─ Sympathetic → pre ACh → <span class="syn">synapse</span> ganglion → post NE (fight/flight)
│   └─ Parasympathetic → pre ACh → <span class="syn">synapse</span> ganglion → post ACh (rest/digest)
│
├── Neurotransmitters → ACh (NMJ, parasymp), NE (symp), glutamate (fast pain), Substance P (slow pain), GABA/glycine (inhibitory), endorphins (pain inhibition)
├── Synaptic physiology → EPSP (Na⁺/Ca²⁺ open), IPSP (Cl⁻/K⁺ open), Gate control theory (Aβ touch inhibits pain)
├── Support cells → Schwann (PNS myelin), Satellite (ganglia), Oligodendrocytes (CNS myelin), Microglia (immune), Astrocytes (BBB/support)
└── Clinical relevance → Cauda equina syndrome, Guillain–Barré (PNS demyelination), Myasthenia gravis, Lambert–Eaton, Peripheral neuropathy, ALS (UMN+LMN)
</pre>

</div>
