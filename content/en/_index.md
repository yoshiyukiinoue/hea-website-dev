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

  # ===== Research Pillars (cards) =====
  - block: research-areas
    id: research
    content:
      title: Research Pillars
      text: The three pillars of our research program
      items:
        - name: Black Hole Astrophysics
          icon: star
          gradient: from-gray-700 to-slate-900
          description: Magnetic field measurements of AGN coronae (ALMA, IXPE, XRISM), accretion physics, and extreme physics near the event horizon.
          topics: [AGN coronae, X-ray polarimetry, ALMA, XRISM]
          cta:
            text: Read more
            url: research/blackhole/
        - name: High-Energy Astrophysics (MeV)
          icon: bolt
          gradient: from-purple-500 to-fuchsia-600
          description: Pioneering MeV gamma-ray astronomy with COSI and GRAMS, and multi-messenger studies with IceCube neutrinos.
          topics: [COSI, GRAMS, neutrinos, blazars]
          cta:
            text: Read more
            url: research/mev/
        - name: Lunar Radiation Environment
          icon: moon
          gradient: from-amber-400 to-yellow-600
          description: Understanding and forecasting the cosmic-ray and radiation environment on the lunar surface for the era of human lunar activity.
          topics: [cosmic rays, solar energetic particles, Artemis]
          cta:
            text: Read more
            url: research/lunar/
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
  - block: collection
    id: latest-pubs
    content:
      title: Recent Publications
      count: 5
      filters:
        folders: [publication]
    design:
      view: citation
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
