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
* Ph.D in Department of Mechanical Science and Bioengineering, [Osaka University][ou], Japan, 2025 (expected)
* M.E. in Department of Mechanical Science and Bioengineering, [Osaka University][ou], Japan, 2022
* B.E. in Department of Systems Science, [Osaka University][ou], Japan, 2021
* Associate D.E., Department of Mechanical Engineering, [National Institute of Technology, Nagano College][nitc], Japan, 2019
* [AFS Exchange Program][afs], SMK Seri Badong, Malaysia, 2015
  
Languages
======
<table border="0">
  <tr>
    <td class="width-fix">・Alt+Z</td>
    <td> [右端で折り返す]の設定/解除</td>
  </tr>
  <tr>
    <td class="width-fix">・Ctrl+/</td>
    <td> 選択した行のコメントの設定/解除</td>
  </tr>
  <tr>
    <td class="width-fix">・Shift+Alt+A</td>
    <td> 選択した範囲のコメント設定/解除</td>
  </tr>
</table>

4: Native, 3: Fluent, 2: Good, 1: Fair
* <span style="color: #171717; "> Japanese    --- 4 </span>
* <span style="color: #171717; "> English     --- 3 </span>
* <span style="color: #171717; "> Malay       --- 2 </span>
* <span style="color: #4a4a4a; "> Fortran     --- 3 </span>
* <span style="color: #4a4a4a; "> Python      --- 2 </span>
* <span style="color: #4a4a4a; "> C           --- 1 </span>
* <span style="color: #787878; "> Linux/Shell --- 2 </span>

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
[ou]:https://www.osaka-u.ac.jp/en
[nitc]:https://www.nagano-nct.ac.jp/english/index.php
[afs]:https://afs.org/
