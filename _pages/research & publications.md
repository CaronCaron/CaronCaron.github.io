---
layout: archive
title: "Researches & Publications"
permalink: /researches & publications/
author_profile: true
---

• Research of a numerical simulation of Rosensweig Instability with LBM (2022-2023)
======
Co-authors: Xiaodong Niu, Adnan Khan
---
investigating the lubrication/sealing techniques 
The Application of Magnetic Fluids as Lubricating and Sealing Media in Extreme Space Environments
Developed a numerical simulation of Rosensweig instability (spikes and rupture controlling) in a sandwiched
ternary system based on Lattice Boltzmann method and phase field method. Related work are accepted as oral
speech in 12th National fluid mechanics Academic Conference and 17th Asian Congress of Fluid Mechanics

>>>Talks at the forthcoming 17th Asian Congress of Fluid Mechanics(ACFM 2023) at Beijing, China (Aug 2023)<br>

Zhang Y, Khan A, Niu X. A numerical study of deformation-rupture of ferrofluid layer in a ternary flow.<br>

>>>Talks at the 12th National Conference on Fluid Mechanics (NCFM 2022) at Xian, China (Nov 2022)<br>

Zhang Y, Khan A, Niu X. Phase Field Simulation of Magnetically Controlled Deformation Rupture of a Magnetic Fluid Layer on a Liquid Substrate [C] Summary of the 12th National fluid mechanics Academic Conference. 2022:1.<br>
[DOI:10.26914/c.cnkihy.2022.068744]<br>

Niu X, Khan A, Zhang Y. A simplified phase-field lattice Boltzmann method with a self-corrected magnetic field for the evolution of spike structures in ferrofluids [C] Summary of the 12th National fluid mechanics Academic Conference.<br>
[DOI:2022:1. DOI:10.26914/c.cnkihy.2022.068157]<br>

  #---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>
  
• Research of lubrication/sealing application of magnetic fluid (2021-2022)
======
Co-authors: Xiaodong Niu， Xiangfan Li, Yaping Wang, Mingfu Wen
---
This work refers to the application of magneitic fluid as lubricant and sealing technique in various special environments (in space, in micro medical devices,in water) 
Specially, in harsh cosmic environments, the existance of vacuum, radiation, and tehrmal cycling can lead to a disaster if any leakage happens.
While,The magnetic response characteristics of magnetic fluid make it applicable to control and easy to avoid pollution and leakage. 
Therefore, it's meaningful to consider advance techniques of magnetic fluid application. In fact, the emergence of magnetic fluid originated from the sealing problem of early space suit, 
and is still an alternative approach for lubrication and sealing with great potential in space exploration.<br>

Related publications:
[Zhang Y, Li X, Wang, Y, Wen M, Khan A, Niu X. A Brief Review of Magnetic Fluid Lubrication/Seal in Space, Lubrication Engineering, 2023. 48(03):147-156] (http://eng.stu.edu.cn/)

  #---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>
  
• Research of a 3D simulation of PEMFC integrated with TED (2018-2019)
======
Co-authors: Qinghe Yao, Trevor Hocksun Kwan
---




  #---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------<br>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

#一个 for 循环，用于迭代作者的出版物。在每次迭代中，我们包含一个 HTML 片段，以显示文章的标题和相关信息。每个构建的页面都会显示所有出版物，按照最近发表的文章从新到旧的顺序排列。
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


