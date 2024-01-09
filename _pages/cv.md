---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Department of Mechanical Science and Bioengineering, [Osaka University][ou], Japan, 2025 (expected)
* [Young Researchers' Exchange Programme][ethyrep], [ETH Zurich][ethz], Switzerland, October 2023 - January 2024
* M.E. in Department of Mechanical Science and Bioengineering, [Osaka University][ou], Japan, March 2022
* B.E. in Department of Systems Science, [Osaka University][ou], Japan, March 2021
* Associate D.E., Department of Mechanical Engineering, [National Institute of Technology, Nagano College][nitc], Japan, March 2019
* [AFS Exchange Program][afs], SMK Seri Badong, Malaysia, 2015
  
Languages
======

4: Native, 3: Fluent, 2: Good, 1: Fair
* <span style="color: #171717; display: inline-block; width: 5.5em; "> Japanese     </span> --- &nbsp; 4
* <span style="color: #171717; display: inline-block; width: 5.5em; "> English      </span> --- &nbsp; 3
* <span style="color: #171717; display: inline-block; width: 5.5em; "> Malay        </span> --- &nbsp; 2
<p style="margin-bottom: 0.5em; "></p>

* <span style="color: #4a4a4a; display: inline-block; width: 5.5em; "> Fortran      </span> --- &nbsp; 3
* <span style="color: #4a4a4a; display: inline-block; width: 5.5em; "> Python       </span> --- &nbsp; 2
* <span style="color: #4a4a4a; display: inline-block; width: 5.5em; "> C            </span> --- &nbsp; 1
* <span style="color: #787878; display: inline-block; width: 5.5em; "> Linux/Shell  </span> --- &nbsp; 2

<i class="fab fa-fw fa-github" aria-hidden="true"></i> <a href="https://github.com/wataiwashi/TIL/" target="_blank">GitHub repository: Today I Learned (TIL)</a>

<p style="margin-bottom: 1.5em; "></p>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% if post.first %}
    {% include archive-single-talk-cv.html %}
    {% endif %}
  {% endfor %}</ul>

<p style="margin-bottom: 1.5em; "></p>

Research proposal-based use of supercomputer systems
======

|  Supercomputer system  |  Category  |  Year  |
| ---- | ---- | ---- |
|  Fugaku, RIKEN Center for Computational Science, Japan  |  Trial Access Projects  | 2023 |
|  SQUID, Cybermedia Center, Osaka University, Japan  |  Large-Scale High-Performance Computing Projects  | 2023 |
|  Research Center for Computational Science, National Institutes of Natural Sciences, Japan  |  RCCS Computational Resource Category (B)  | 2023 |

  
[ou]:https://www.osaka-u.ac.jp/en
[nitc]:https://www.nagano-nct.ac.jp/english/index.php
[afs]:https://afs.org/
[ethyrep]:https://leadinghouseasia.ethz.ch/funding-instruments/mobility-grants/young-researchers-exchange-programmes/young-researchers--exchange-programme---special-2023-call.html
[ethz]:https://ethz.ch/en.html
