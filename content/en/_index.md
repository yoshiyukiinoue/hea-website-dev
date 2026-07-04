---
title: Inoue High-Energy Astrophysics Lab
type: landing

sections:
  # ===== Hero =====
  - block: hero-rotator
    id: hero
    content:
      title: Inoue High-Energy Astrophysics Lab
      text: |
        From the extreme environments around black holes to the radiation environment on the lunar surface —
        we tackle the mysteries of the high-energy universe through theory and multi-messenger observations
        (X-rays, MeV gamma rays, radio, neutrinos, and gravitational waves).
      primary_action:
        text: Join Us
        url: join/
      secondary_action:
        text: Explore Our Research
        url: research/
      images:
        - file: hero/corona.jpg
          credit: "Credit: RIKEN"
        - file: hero/fermi.jpg
          credit: "Credit: NASA/DOE/Fermi LAT Collaboration"
        - file: hero/m51.jpg
          credit: "Credit: NASA/ESA/STScI"
        - file: hero/moon.jpg
          credit: "Credit: NASA"
    design:
      spacing:
        padding: ['0', '0']

  # ===== Research (two categories) =====
  - block: research-areas
    id: research
    content:
      title: Research
      text: From fundamental astrophysics to applied radiation science.
      groups:
        - title: Fundamental Astrophysics
          kicker: 01 — FUNDAMENTAL
          accent: navy
          description: Uncovering the physics of the high-energy universe — black holes and MeV gamma rays — through theory and multi-messenger observations.
          cta:
            text: Explore fundamental research
            url: research/#fundamental
          items:
            - name: Black Hole Astrophysics
              icon: star
              gradient: from-gray-700 to-slate-900
              description: Magnetic field measurements of AGN coronae (ALMA, IXPE, XRISM), accretion physics, and extreme physics near the event horizon.
              topics: [AGN coronae, X-ray polarimetry, ALMA, XRISM]
              cta:
                text: Read more
                url: research/#blackhole
            - name: High-Energy Astrophysics (MeV)
              icon: bolt
              gradient: from-purple-500 to-fuchsia-600
              description: Pioneering MeV gamma-ray astronomy with COSI and GRAMS, and multi-messenger studies with IceCube neutrinos.
              topics: [COSI, GRAMS, neutrinos, blazars]
              cta:
                text: Read more
                url: research/#mev
        - title: Applied High-Energy and Radiation Studies
          kicker: 02 — APPLIED
          accent: gold
          description: Applying our expertise in high-energy astrophysics to real-world radiation challenges of the space age.
          cta:
            text: Explore applied research
            url: research/#applied
          items:
            - name: Lunar Radiation Environment
              icon: moon
              gradient: from-amber-400 to-yellow-600
              description: Understanding and forecasting the cosmic-ray and radiation environment on the lunar surface for the era of human lunar activity.
              topics: [cosmic rays, solar energetic particles, Artemis]
              cta:
                text: Read more
                url: research/#lunar
    design:
      spacing:
        padding: ['2.5rem', '0']

  # ===== News =====
  - block: collection
    id: news
    content:
      title: News
      count: 5
      filters:
        folders: [news]
    design:
      view: date-title-summary
      spacing:
        padding: ['2.5rem', '0']

  # ===== Recent Publications =====
  - block: markdown
    id: latest-pubs
    content:
      title: Recent Publications
      text: |
        <!-- RECENT_PUBS:START -->
        - Ly, M. N., **Inoue, Y.**, Sentoku, Y., Sano, T. (2026). Proton Acceleration by Collisionless Shocks in Supermassive Black Hole Coronae: Implications for High-energy Neutrinos. *The Astrophysical Journal* 1004, 27. [ADS](https://ui.adsabs.harvard.edu/abs/2026ApJ..1004...27L) / [arXiv](https://arxiv.org/abs/2601.01999) / [DOI](https://doi.org/10.3847/1538-4357/ae61ab)
        - Xue, R., **Inoue, Y.**, Wang, Z., Liao, N., Xiong, D. (2026). Locating the Production Sites of High-Energy Neutrinos in Blazar Jets. *arXiv e-prints*, arXiv:2606.02024. [ADS](https://ui.adsabs.harvard.edu/abs/2026arXiv260602024X) / [arXiv](https://arxiv.org/abs/2606.02024) / [DOI](https://doi.org/10.48550/arXiv.2606.02024)
        - Komugi, S., Saito, T., Michiyama, T., **Inoue, Y.**, Nakanishi, K., et al. (2026). An AGN in the Antennae galaxies ?. *arXiv e-prints*, arXiv:2605.21879. [ADS](https://ui.adsabs.harvard.edu/abs/2026arXiv260521879K) / [arXiv](https://arxiv.org/abs/2605.21879) / [DOI](https://doi.org/10.48550/arXiv.2605.21879)
        - Kusakabe, K., **Inoue, Y.**, Toyouchi, D. (2026). Coherence of Supermassive Black Hole Binary Demographics with the nHz Stochastic Gravitational-wave Background. *The Astrophysical Journal* 999, 117. [ADS](https://ui.adsabs.harvard.edu/abs/2026ApJ...999..117K) / [arXiv](https://arxiv.org/abs/2510.10548) / [DOI](https://doi.org/10.3847/1538-4357/ae3962)
        - Owen, E. R., Wu, K., **Inoue, Y.**, Fujiwara, T., Han, Q., et al. (2026). The 'Forgotten' Neutrons: Implications for the Propagation of High-Energy Cosmic Rays in Magnetized Astrophysical and Cosmological Structures. *Universe* 12, 94. [ADS](https://ui.adsabs.harvard.edu/abs/2026Univ...12...94O) / [arXiv](https://arxiv.org/abs/2603.25060) / [DOI](https://doi.org/10.3390/universe12040094)
        <!-- RECENT_PUBS:END -->
        [All publications →](publication/)
    design:
      spacing:
        padding: ['2.5rem', '0']

  # ===== Join CTA =====
  - block: cta-card
    id: join-cta
    content:
      title: Join Us
      text: We are recruiting graduate students (MSc/PhD), postdocs, and undergraduates. Black holes, gamma rays, neutrinos, or the Moon — if any of these excites you, get in touch.
      button:
        text: How to Join
        url: join/
    design:
      spacing:
        padding: ['2.5rem', '0']
---
