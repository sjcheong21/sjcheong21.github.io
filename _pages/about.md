---
layout: clean
permalink: /
title: "Home"
description: "Sungjin Cheong — Ph.D. student in Computer Sciences at the WISION Lab, University of Wisconsin–Madison, working on computational imaging and computer vision."
redirect_from:
  - /about/
  - /about.html
hero:
  avatar: /images/bio.png
  name: "Sungjin Cheong"
  role: "Ph.D. Student in Computer Sciences"
  affiliation: '<a href="https://wisionlab.com/" target="_blank" rel="noopener">WISION Lab</a> &middot; University of Wisconsin–Madison'
  # A YAML literal block, so the HTML below stays readable and editable.
  # Everything here renders inside <div class="hero-bio"> in the hero.
  bio: |
    <p>
      I'm a second-year Ph.D. student in Computer Sciences at the
      <a class="hl" href="https://wisionlab.com/" target="_blank" rel="noopener">WISION Lab</a> at the
      <span class="hl">University of Wisconsin–Madison</span>, advised by
      <a class="hl" href="https://pages.cs.wisc.edu/~mohitg/" target="_blank" rel="noopener">Prof. Mohit Gupta</a>.
      My research focuses on <span class="hl">computational imaging</span> and
      <span class="hl">computer vision</span>, with an emphasis on:
    </p>
    <ul>
      <li>Physics-grounded intelligent sensing and imaging systemsPhysics-grounded intelligent sensing and imaging systems</li>
      <li> ToF/LiDAR computational imaging</li>
      <li>TStatistical signal processing and inverse problems</li>
      <li>Physics-based and learning-based modeling</li>
    </ul>
    <p>
      Previously, I worked at <span class="hl">LG Innotek</span> developing direct Time-of-Flight (dToF) LiDAR
      signal and image processing algorithms.
    </p>
    <p>
      I received my M.S. in Mechanical Engineering from
      <span class="hl">Korea Advanced Institute of Science and Technology (KAIST)</span>, advised by
      <a class="hl" href="https://human.kaist.ac.kr/" target="_blank" rel="noopener">Prof. Yong-Hwa Park</a>,
      and my B.S. in Mechanical Engineering from <span class="hl">Yonsei University</span>.
    </p>
  cv: /files/sjcheong_cv_2026.pdf
  scroll_to: "#education"
---

<section id="education" class="content-section alt">
  <div class="section-inner">
    <h2 class="section-heading reveal">Education</h2>
    <div class="edu-list reveal">

      <div class="edu-item">
        <img class="edu-logo" src="{{ '/images/uwmadison.png' | relative_url }}" alt="University of Wisconsin–Madison logo">
        <div class="edu-text">
          <span class="edu-school">University of Wisconsin–Madison</span>
          <span class="edu-meta">Ph.D. in Computer Sciences</span>
        </div>
        <span class="edu-date">Aug. 2025 – Present</span>
      </div>

      <div class="edu-item">
        <img class="edu-logo" src="{{ '/images/kaist.png' | relative_url }}" alt="KAIST logo">
        <div class="edu-text">
          <span class="edu-school">KAIST</span>
          <span class="edu-meta">M.S. in Mechanical Engineering</span>
        </div>
        <span class="edu-date">Sep. 2021 – Aug. 2023</span>
      </div>

      <div class="edu-item">
        <img class="edu-logo" src="{{ '/images/yonsei.png' | relative_url }}" alt="Yonsei University logo">
        <div class="edu-text">
          <span class="edu-school">Yonsei University</span>
          <span class="edu-meta">B.S. in Mechanical Engineering</span>
          <span class="edu-meta">Military Service (2015–2017)</span>
        </div>
        <span class="edu-date">Mar. 2014 – Aug. 2021</span>
      </div>

    </div>
  </div>
  <a href="#publications" class="scroll-arrow" aria-label="Scroll to Publications">
    <svg width="30" height="30" viewBox="0 0 30 30"><polyline points="7,12 15,20 23,12" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
  </a>
</section>

<section id="publications" class="content-section">
  <div class="section-inner">
    <h2 class="section-heading reveal">Publications</h2>
    <div class="card-list">

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/cvpr.png' | relative_url }}" alt="Ghosts in the Point Clouds">
        <div class="card-body">
          <div class="card-title">Ghosts in the Point Clouds: De-glaring LiDAR in the Transient Domain</div>
          <div class="card-authors">Avery Gump, Connor Andrew Henley, <span class="me">Sungjin Cheong</span>, Akarsh Prabhakara, Mohit Gupta</div>
          <div class="card-venue">CVPR, 2026</div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/trrs1.png' | relative_url }}" alt="Thermal-Infrared Remote-Target Detection System">
        <div class="card-body">
          <div class="card-title">Thermal-Infrared Remote-Target Detection System for Maritime Rescue Using 3-D Game-Based Data Augmentation With GAN</div>
          <div class="card-authors"><span class="me">Sungjin Cheong</span>, Wonhu Jung, Yoon Seop Lim, Yong-Hwa Park</div>
          <div class="card-venue">IEEE Transactions on Geoscience and Remote Sensing, 2024 <span class="hl-red">(IF: 9.4)</span></div>
          <div class="card-links">
            <a href="https://doi.org/10.1109/TGRS.2024.3454983" target="_blank" rel="noopener">Link</a>
            <a href="https://sites.google.com/view/sungjin-website/publications-conferences/tistd-trgs" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/icce_asia_v2.png' | relative_url }}" alt="LiDAR Blooming Artifacts Estimation">
        <div class="card-body">
          <div class="card-title">LiDAR Blooming Artifacts Estimation Method Induced by Retro-Reflectance With Synthetic Data Modeling and Deep Learning</div>
          <div class="card-authors"><span class="me">Sungjin Cheong</span>, Jusung Ha</div>
          <div class="card-venue">ICCE-Asia, 2024</div>
          <div class="card-links">
            <a href="https://ieeexplore.ieee.org/abstract/document/10774004" target="_blank" rel="noopener">Link</a>
            <a href="https://sites.google.com/view/sungjin-website/publications-conferences/lidar-blooming" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/fwkernel.png' | relative_url }}" alt="Infrared Image-Based Remote Target Detection">
        <div class="card-body">
          <div class="card-title">Infrared Image-Based Remote Target Detection for Maritime Rescue Utilizing a Deep Learning Network and Data Augmentation</div>
          <div class="card-authors"><span class="me">Sungjin Cheong</span>, Yoon Seop Lim, Wonho Jung, Yong-Hwa Park</div>
          <div class="card-venue">Proc. of SPIE, 2023</div>
          <div class="card-links">
            <a href="https://doi.org/10.1117/12.2649806" target="_blank" rel="noopener">Link</a>
            <a href="https://sites.google.com/view/sungjin-website/publications-conferences/tistd-spie" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/mpi_suppression.png' | relative_url }}" alt="MEMS-Based Indirect Time-of-Flight Scanning LiDAR">
        <div class="card-body">
          <div class="card-title">MEMS-Based Indirect Time-of-Flight Scanning LiDAR With Parallel-Phase Demodulation and Multipath Interference Suppression</div>
          <div class="card-authors">Sunghyun Lee, Yoon Seop Lim, <span class="me">Sungjin Cheong</span>, Yong-Hwa Park</div>
          <div class="card-venue">Proc. of SPIE, 2023</div>
          <div class="card-links">
            <a href="https://doi.org/10.1117/12.2649693" target="_blank" rel="noopener">Link</a>
            <a href="https://sites.google.com/view/sungjin-website/publications-conferences/mpi-suppression" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/fr.png' | relative_url }}" alt="Long-Distance 3D Face Recognition">
        <div class="card-body">
          <div class="card-title">A Long-Distance 3D Face Recognition Architecture Utilizing MEMS-Based Region-Scanning LiDAR</div>
          <div class="card-authors">Yoon Seop Lim, Sunghyun Lee, <span class="me">Sungjin Cheong</span>, Yong-Hwa Park</div>
          <div class="card-venue">Proc. of SPIE, 2023</div>
          <div class="card-links">
            <a href="https://doi.org/10.1117/12.2649500" target="_blank" rel="noopener">Link</a>
            <a href="https://sites.google.com/view/sungjin-website/publications-conferences/face-recognition" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/head_pose.gif' | relative_url }}" alt="Head Pose Estimation">
        <div class="card-body">
          <div class="card-title">Head Pose Estimation Method Using Depth Camera Based on 3D Point Cloud</div>
          <div class="card-authors"><span class="me">Sungjin Cheong</span>, Sunghyun Lee, Yoon Seop Lim, Yong-Hwa Park</div>
          <div class="card-venue">Conference of The Korean Society of Mechanical Engineers, 2022</div>
          <div class="card-links">
            <a href="https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11181942" target="_blank" rel="noopener">Link</a>
            <a href="https://sites.google.com/view/sungjin-website/publications-conferences/head-pose-estimation" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/simulation_amcw.png' | relative_url }}" alt="Validation of Simulation Model for 3D iToF Sensor">
        <div class="card-body">
          <div class="card-title">Validation of Simulation Model for 3D Indirect Time-of-Flight Sensor</div>
          <div class="card-authors">Sunghyun Lee, Yoon Seop Lim, <span class="me">Sungjin Cheong</span>, Yong-Hwa Park</div>
          <div class="card-venue">Conference of The Korean Society of Mechanical Engineers, 2022</div>
          <div class="card-links">
            <a href="https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11182118" target="_blank" rel="noopener">Link</a>
            <a href="https://sites.google.com/view/sungjin-website/publications-conferences/itof-simulation" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/histo.png' | relative_url }}" alt="Infrared Small Object Detection">
        <div class="card-body">
          <div class="card-title">Infrared Small Object Detection Based on Histogram Transformation</div>
          <div class="card-authors"><span class="me">Sungjin Cheong</span>, Wonho Jung, Yong-Hwa Park</div>
          <div class="card-venue">Conference of The Korean Society of Mechanical Engineers, 2022</div>
          <div class="card-links">
            <a href="https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11061948" target="_blank" rel="noopener">Link</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/sr.gif' | relative_url }}" alt="Depth Image Super Resolution">
        <div class="card-body">
          <div class="card-title">Depth Image Super Resolution Method for Time-of-Flight Camera Using Single Image Depth Estimation</div>
          <div class="card-authors">Yoon Seop Lim, Sunghyun Lee, <span class="me">Sungjin Cheong</span>, Yong-Hwa Park</div>
          <div class="card-venue">Conference of The Korean Society of Mechanical Engineers, 2022</div>
          <div class="card-links">
            <a href="https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11061915" target="_blank" rel="noopener">Link</a>
            <a href="https://sites.google.com/view/sungjin-website/publications-conferences/super-resolution" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/depth_correction.png' | relative_url }}" alt="Depth Error Correction of 3D Scanning Sensor">
        <div class="card-body">
          <div class="card-title">Depth Error Correction of 3D Scanning Sensor Using Machine Learning</div>
          <div class="card-authors">Sunghyun Lee, Yoon Seop Lim, <span class="me">Sungjin Cheong</span>, Yong-Hwa Park</div>
          <div class="card-venue">Conference of The Korean Society of Mechanical Engineers, 2022</div>
          <div class="card-links">
            <a href="https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE11061919" target="_blank" rel="noopener">Link</a>
            <a href="https://sites.google.com/view/sungjin-website/publications-conferences/depth-error-correction" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

    </div>
  </div>
  <a href="#projects" class="scroll-arrow" aria-label="Scroll to Projects">
    <svg width="30" height="30" viewBox="0 0 30 30"><polyline points="7,12 15,20 23,12" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></svg>
  </a>
</section>

<section id="projects" class="content-section alt">
  <div class="section-inner">
    <h2 class="section-heading reveal">Past Projects</h2>
    <div class="card-list">

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/carla.gif' | relative_url }}" alt="Autonomous driving education with CARLA">
        <div class="card-body">
          <div class="card-title">Educational Content for Autonomous Driving with CARLA</div>
          <div class="card-org">Divine Technology Inc., Seoul, Republic of Korea</div>
          <div class="card-desc"><strong>Achieved Outcomes:</strong> Produced online educational material and corresponding CARLA simulation practice code targeted to undergraduate and graduate school students, consisting of perception, decision, and control.</div>
          <div class="card-role">(Role: Camera, LiDAR perception part including lane detection, calibration, 2D/3D object detection, tracking etc.)</div>
          <div class="card-links">
            <a href="https://human.kaist.ac.kr/" target="_blank" rel="noopener">Link</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/sensors.png' | relative_url }}" alt="Radar, LiDAR and camera integrated platform">
        <div class="card-body">
          <div class="card-title">Radar, LiDAR, and Camera Sensor Integrated Platform</div>
          <div class="card-org">LG Innotek Inc., Seoul, Republic of Korea</div>
          <div class="card-desc"><strong>Achieved Outcomes:</strong> Develop integrated automotive sensors software platform.</div>
          <div class="card-role">(Role: (Full) 3D data processing, LiDAR noise filtering, Human &amp; Object tracking algorithm, (Partly) Integrated sensor setup in vehicle, Viewer GUI)</div>
          <div class="card-links">
            <a href="https://lginnotek-virtualshowroom.com/autonomous-driving/" target="_blank" rel="noopener">Link</a>
          </div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/coast.png' | relative_url }}" alt="Infrared monitoring AI system for maritime rescue">
        <div class="card-body">
          <div class="card-title">Infrared Monitoring AI System For Maritime Rescue</div>
          <div class="card-org">Korean Coast Guard, Incheon, Republic of Korea</div>
          <div class="card-desc"><strong>Achieved Outcomes:</strong> Designed thermal-infrared target detection system specified for unmanned coast guard boats for maritime rescue search tasks.</div>
          <div class="card-role">(Role: Project leader, Dataset acquisition, Experiment, Overall framework design)</div>
        </div>
      </div>

      <div class="card-item reveal">
        <img class="card-thumb" src="{{ '/images/depth_map.gif' | relative_url }}" alt="iToF scanning LiDAR platform">
        <div class="card-body">
          <div class="card-title">iToF Scanning LiDAR Platform and Its Application Software</div>
          <div class="card-org">Intek Plus Inc., Daejon, Republic of Korea</div>
          <div class="card-desc"><strong>Achieved Outcomes:</strong> Proposed miniaturized indirect time-of-flight AMCW LiDAR system and its application software tailored to driver monitoring system (DMS) and highly precise 3D scanner.</div>
          <div class="card-role">(Role: (Full) 3D computer vision, (Partly) Optical system design &amp; Signal processing)</div>
          <div class="card-links">
            <a href="https://sites.google.com/view/sungjin-website/projects/3d-lidar-platform" target="_blank" rel="noopener">Details</a>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>
