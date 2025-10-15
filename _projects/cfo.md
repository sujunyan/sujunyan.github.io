---
layout: page
title: "Follow the Sun and Go with the Wind: Carbon Footprint Optimized Timely E-Truck Transportation"
img: /assets/img/12.jpg
importance: 1
category: work
---
Joint work with [Qiulin Lin](https://lin-qiulin.github.io/), [Minghua Chen](https://www.mhchen.com/), and [Haibo Zeng](https://www.faculty.ece.vt.edu/zeng/index.html)

This project is a follow-up project of [Energy-Efficient Timely Transportation of Long-Haul Heavy-Duty Truck](https://www.mhchen.com/projects/trucking.html).

---
### **Highlights**

- Accepted for publication in <span style="color:blue">Nature Communications</span>.
- <span style="color:blue">Best paper award</span> at ACM e-Energy 2023.
- We study an important yet challenging problem , namely the carbon footprint optimization problem for e-trucks.
- We provide a novel problem formulation, which incurs low model complexity and reveals a useful problem structure. We develop an efficient algorithm with performance guarantee.
- **Key technical idea:** The problem is easy either when there is no charging or when there is only charging. Our idea is to separate the combined challenging problem into those two easy subproblems and combine their solutions.
- **Key messages from evaluation:**
Our method complements the **36%** carbon reduction from electrification with an additional **25%** decrease, totaling a **61%** reduction. 
With our method, we can achieve comparable carbon reductions **9** years sooner than zero-emission truck adoption alone.

<!--
---

### **Slides**

<iframe  src="{{ '/assets/pdf/cfo.slides.pdf' | relative_url }}" width="100%" height="500">
</iframe>

<iframe src="https://onedrive.live.com/embed?resid=246D3C20B0FC822F%21350&amp;authkey=!AFe9PhuYTjFYlyE&amp;em=2&amp;wdAr=1.7777777777777777&amp;wdEaaCheck=0" width="100%" height="500px" frameborder="0">这是嵌入 <a target="_blank" href="https://office.com">Microsoft Office</a> 演示文稿，由 <a target="_blank" href="https://office.com/webapps">Office</a> 提供支持。</iframe>
-->
---

### **Description**

Electrifying heavy-duty trucks is crucial for decarbonizing transportation, but maximizing their potential requires minimizing the carbon footprint of timely deliveries. This complex optimization task involves strategic path, speed, and charging planning, which traditional methods struggle to optimize at scale. We present a novel stage-expanded graph formulation that reduces complexity and reveals a useful problem structure. Our formulation naturally decomposes the problem into more tractable subproblems, allowing efficient coordination between routing and charging decisions, and maintains a manageable graph size. We exploit these structural insights to design an efficient algorithm with strong performance guarantees. Simulations using real-world data over the U.S. highway system demonstrate that our method complements the **36%** carbon reduction from electrification with an additional **25%** decrease, totaling a **61%** reduction. Moreover, our carbon-optimized strategy, applicable to various truck types, can achieve comparable carbon reductions **9** years sooner than zero-emission truck adoption alone. 
This approach significantly accelerates transportation decarbonization, offering a powerful tool in the fight against climate change.

<!-- 
We study the carbon footprint optimization (CFO) of a heavy-duty e-truck traveling from an origin to a destination across a national highway network subject to a hard deadline, by optimizing path planning, speed planning, and intermediary charging planning. Such a CFO problem is essential for carbon-friendly e-truck operations. However, it is notoriously challenging to solve due to (i) the hard deadline constraint, (ii) positive battery state-of-charge constraints, (iii) non-convex carbon footprint objective, and (iv) enormous geographical and temporal charging options with diverse carbon intensity. Indeed, we show that the CFO problem is NP-hard. 

As a key contribution, we show that under practical settings it is equivalent to finding a generalized restricted shortest path on a stage-expanded graph, which extends the original transportation graph to model charging options. Compared to alternative approaches, our formulation incurs low model complexity and reveals a problem structure useful for algorithm design. We exploit the insights to develop an efficient dual-subgradient algorithm that always converges. 
As another major contribution, we prove that (i) each iteration only incurs polynomial-time complexity, albeit it requires solving an integer charging planning problem optimally, and (ii) the algorithm generates optimal results if a condition is met and solutions with bounded optimality loss otherwise. 

Extensive simulations based on real-world traces show that our scheme reduces up to 28% carbon footprint compared to baseline alternatives. The results also demonstrate that e-truck reduces 56% carbon footprint than internal combustion engine trucks.
-->


---
### **Publications**
###### **Notes on Difference**
E-Energy'23 [1] is one of the first work that gives the problem formulation for the CFO problem and gives an efficient algorithm for solving CFO. CDC'23 [2] supplements e-Energy'23 [1] by studying the theoretic hardness of CFO and provide a bi-criteria approximation algorithm with stronger theoretic performance guarantee (but much higher run-time complexity). 
In our journal paper NC'25 [3], we provide an improved algorithm and more comprehensive evaluations and discussions. The journal version NC'25 [3] also focuses more on the practical significance of CFO and its connection to the broader climate change framework.
The poster and demo papers [4,5] give some preliminary results in the early stage of this project.


##### **Conference Papers**
[1] **J. Su** , Q. Lin, and M. Chen, “Follow the Sun and Go with the Wind: Carbon Footprint Optimized Timely E-Truck Transportation”, in Proceedings of 14th International Conference on Future Energy Systems (ACM e-Energy 2023), Orlando, Florida, June 20 - 23, 2023. **(Best Paper Award).** [[pdf](https://www.mhchen.com/papers/CFO_eEnergy.23.pdf)] [[arxiv](https://arxiv.org/abs/2305.11912)]

[2] **J. Su**, Q. Lin, M. Chen, and H. Zeng, “Minimizing Carbon Footprint for Timely E-Truck Transportation: Hardness and Approximation Algorithm”, (invited), in Proceedings of the 62th IEEE Conference on Decision and Control (CDC), Singapore, December 13-15, 2023. [[arxiv](https://arxiv.org/abs/2308.09866)]

##### **Journal Articles**
[3] **J. Su**, Q. Lin, and M. Chen, “Optimizing Carbon Footprint in Long-Haul Heavy-Duty E-Truck Transportation”, Nature Communications, accepted for publication, 2025.

##### **Poster and Demo Papers**

[4] **J. Su**, M. Chen, and H. Zeng, “Energy Efficient Timely Transportation : A Comparative Study of Internal Combustion Trucks and Electric Trucks”, in Proceedings of the 8th ACM International Conference on Systems for Energy-Efficient Built Environments, Cities, and Transportation (ACM BuildSys 2021), Coimbra, Portugal, November 17-18, 2021. (poster paper) [<a href="{{ '/assets/pdf/buildsys21.etruck.pdf' | relative_url }}">pdf</a>]

[5] **J. Su**, M. Chen, and H. Zeng, “E2Pilot: An Energy-Efficient Navigation System for Long-haul Timely Truck Transportation”, in Proceedings of 13th International Conference on Future Energy Systems (ACM e-Energy 2022), virtual conference, June 28 - July 1, 2022. (demo paper) [<a href="{{ '/assets/pdf/eenergy22.e2pilot.demo.pdf' | relative_url }}">pdf</a>]

##### **Patent**

[6] M. Chen, **J. Su**, and Q. Lin, "Carbon Footprint Optimized Timely E-Truck Transportation", 14 Aug 2025, U.S. Patent No. US2025/0258006.


##### **Thesis**

[7] "Minimizing Emission and Carbon Footprint for Timely Heavy-Duty Truck Transportation", Ph.D. Dissertation, City University of Hong Kong, 2025. [[link](https://scholars.cityu.edu.hk/en/studentTheses/minimizing-emission-and-carbon-footprint-for-timely-heavy-duty-tr)] [[pdf](http://lbms03.cityu.edu.hk/theses/ftt/phd-ds-315657520.pdf)]