---
title: 高エネルギー宇宙物理研究室
type: landing

sections:
  # ===== ヒーロー =====
  - block: hero-rotator
    id: hero
    content:
      title: 高エネルギー宇宙物理研究室
      text: |
        ブラックホール近傍の極限環境から月面の放射線環境まで——
        理論とマルチメッセンジャー観測(X線・MeVガンマ線・電波・ニュートリノ・重力波)を駆使して、
        高エネルギー宇宙の謎に挑みます。
      primary_action:
        text: 参加希望の方へ
        url: join/
      secondary_action:
        text: 研究内容を見る
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

  # ===== 研究(2カテゴリ)=====
  - block: research-areas
    id: research
    content:
      title: 研究
      text: 基礎から応用まで——高エネルギー宇宙物理を軸に研究を展開しています。
      groups:
        - title: 基礎宇宙物理
          kicker: 01 — FUNDAMENTAL
          accent: navy
          description: ブラックホールとMeVガンマ線を軸に、高エネルギー宇宙の物理を理論とマルチメッセンジャー観測で解明します。
          cta:
            text: 基礎宇宙物理の研究へ
            url: research/#fundamental
          items:
            - name: ブラックホール天文学
              icon: star
              gradient: from-gray-700 to-slate-900
              description: AGNコロナの磁場測定(ALMA・IXPE・XRISM)、降着流の物理、事象の地平線近傍の極限物理。
              topics: [AGNコロナ, X線偏光, ALMA, XRISM]
              cta:
                text: 詳しく
                url: research/#blackhole
            - name: 高エネルギー天文学(MeV)
              icon: bolt
              gradient: from-purple-500 to-fuchsia-600
              description: COSI・GRAMSによるMeVガンマ線天文学の開拓、IceCubeニュートリノとのマルチメッセンジャー研究。
              topics: [COSI, GRAMS, ニュートリノ, ブレーザー]
              cta:
                text: 詳しく
                url: research/#mev
        - title: 応用高エネルギー・放射線研究
          kicker: 02 — APPLIED
          accent: gold
          description: 高エネルギー宇宙物理の知見を、宇宙時代の実課題である放射線環境の理解と予測に応用します。
          cta:
            text: 応用研究へ
            url: research/#applied
          items:
            - name: 月面放射線環境
              icon: moon
              gradient: from-amber-400 to-yellow-600
              description: 有人月面活動時代に向けた、月面の宇宙線・放射線環境の理解と予測。
              topics: [宇宙線, 太陽高エネルギー粒子, アルテミス]
              cta:
                text: 詳しく
                url: research/#lunar
    design:
      spacing:
        padding: ['1rem', '0']

  # ===== ニュース =====
  - block: collection
    id: news
    content:
      title: ニュース
      count: 5
      filters:
        folders: [news]
    design:
      view: date-title-summary
      spacing:
        padding: ['1rem', '0']

  # ===== 最近の論文 =====
  - block: markdown
    id: latest-pubs
    content:
      title: 最近の論文
      text: |
        <!-- RECENT_PUBS:START -->
        - Ly, M. N., **Inoue, Y.**, Sentoku, Y., Sano, T. (2026). Proton Acceleration by Collisionless Shocks in Supermassive Black Hole Coronae: Implications for High-energy Neutrinos. *The Astrophysical Journal* 1004, 27. [ADS](https://ui.adsabs.harvard.edu/abs/2026ApJ..1004...27L) / [arXiv](https://arxiv.org/abs/2601.01999) / [DOI](https://doi.org/10.3847/1538-4357/ae61ab)
        - Xue, R., **Inoue, Y.**, Wang, Z., Liao, N., Xiong, D. (2026). Locating the Production Sites of High-Energy Neutrinos in Blazar Jets. *arXiv e-prints*, arXiv:2606.02024. [ADS](https://ui.adsabs.harvard.edu/abs/2026arXiv260602024X) / [arXiv](https://arxiv.org/abs/2606.02024) / [DOI](https://doi.org/10.48550/arXiv.2606.02024)
        - Komugi, S., Saito, T., Michiyama, T., **Inoue, Y.**, Nakanishi, K., et al. (2026). An AGN in the Antennae galaxies ?. *arXiv e-prints*, arXiv:2605.21879. [ADS](https://ui.adsabs.harvard.edu/abs/2026arXiv260521879K) / [arXiv](https://arxiv.org/abs/2605.21879) / [DOI](https://doi.org/10.48550/arXiv.2605.21879)
        - Kusakabe, K., **Inoue, Y.**, Toyouchi, D. (2026). Coherence of Supermassive Black Hole Binary Demographics with the nHz Stochastic Gravitational-wave Background. *The Astrophysical Journal* 999, 117. [ADS](https://ui.adsabs.harvard.edu/abs/2026ApJ...999..117K) / [arXiv](https://arxiv.org/abs/2510.10548) / [DOI](https://doi.org/10.3847/1538-4357/ae3962)
        - Owen, E. R., Wu, K., **Inoue, Y.**, Fujiwara, T., Han, Q., et al. (2026). The 'Forgotten' Neutrons: Implications for the Propagation of High-Energy Cosmic Rays in Magnetized Astrophysical and Cosmological Structures. *Universe* 12, 94. [ADS](https://ui.adsabs.harvard.edu/abs/2026Univ...12...94O) / [arXiv](https://arxiv.org/abs/2603.25060) / [DOI](https://doi.org/10.3390/universe12040094)
        <!-- RECENT_PUBS:END -->
        [論文一覧へ →](publication/)
    design:
      spacing:
        padding: ['2rem', '0']

  # ===== メンバー募集 =====
  - block: cta-card
    id: join-cta
    content:
      title: メンバー募集
      text: 大学院生(修士・博士)・博士研究員・卒研生を募集しています。ブラックホール、ガンマ線、ニュートリノ、月——どれか一つでもピンと来たら、まずは気軽に連絡してください。
      button:
        text: 参加希望の方へ
        url: join/
    design:
      spacing:
        padding: ['1rem', '0']
---
